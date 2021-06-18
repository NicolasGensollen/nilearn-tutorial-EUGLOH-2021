[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NicolasGensollen/nilearn-tutorial-EUGLOH-2021/HEAD)

# nilearn tutorial EUGLOH 2021

This repository holds the materials for the Nilearn tutorial for the EUGLOH Summer School focused on Neuroscience.

The notebooks are based from previous nilearn tutorials:

- [Resting State and Brain Connectivity 2018 satellite workshop](https://github.com/illdopejake/RS2018_Nilearn_tutorial) given by [Gaël Varoquaux](https://github.com/GaelVaroquaux) and [Jacob Vogel](https://github.com/illdopejake).
- [NHA 2020 tutorial](https://emdupre.github.io/nha2020-nilearn/01-data-structures.html) given by [Elizabeth Dupre](https://github.com/emdupre).


## Install

To be able to run the tutorial materials we need a few things:

- **Python 3:** Most recent systems come with Python pre-installed. However, depending on your system, you might still have python 2 as your default Python.

<div class="alert alert-block alert-danger">
<b>Danger:</b> Nilearn does not support Python 2 anymore, so make sure to have Python 3 installed.
</div>

- **pip:** `pip` is the standard package manager for Python. It is a very powerful tool to manage your python packages. You can learn more on pip [here](https://realpython.com/what-is-pip/).

<div class="alert alert-block alert-info">
<b>Tip:</b> If you want to check whether you have pip installed:

**Linux:**

```
$ python -m pip --version
pip X.Y.Z from .../site-packages/pip (python X.Y)
```

**Windows:**

```
C:\> py -m pip --version
pip X.Y.Z from ...\site-packages\pip (python X.Y)
```
</div>

- **git:** `git` is the most popular VCS (version controlled software). Although we recommand having `git` installed to download these notebooks, you can also use the download button on GitHub. You can learn more on `git` [here](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F).


#### The easy case

If you have these tools installed, you can download the repository with the notebooks:

```
$ git clone git@github.com:NicolasGensollen/nilearn-tutorial-EUGLOH-2021.git
$ cd nilearn-tutorial-EUGLOH-2021
```

Install the requirements (this will install nilearn and its dependencies, as well as Jupyter-notebooks):

```
$ pip install -r requirements.txt
```

Launch the notebooks:

```
$ cd Notebooks
$ jupyter-notebook
```

#### The harder case 

If you don't have these tools installed already, we recommand to rely on [anaconda](https://www.anaconda.com/products/individual). `Anaconda` is a distribution of the Python programming languages for scientific computing which aims at simplifying package management and deployment. The distribution includes data-science packages suitable for Windows, Linux, and macOS.

Once you have downloaded and installed anaconda, you can create a new virtual environment dedicated to nilearn:

```
$ conda create -n nilearn python=3.9
$ conda activate nilearn
```

You can then go back to the "The easy case" section and follow the instructions.

### Running the turorial notebooks online

Alternatively, you can run the notebooks online via Binder by clicking this link: [https://mybinder.org/v2/gh/NicolasGensollen/nilearn-tutorial-EUGLOH-2021/HEAD](https://mybinder.org/v2/gh/NicolasGensollen/nilearn-tutorial-EUGLOH-2021/HEAD) or clicking the Binder badge at the top of the README file.

