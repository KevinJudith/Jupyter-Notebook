# Jupyter-Notebook

This is an installation guide to setup Jupyter Notebook on MacOS. You can find more information on the official website https://jupyter.org/

## Install Brew

Homebrew is a package manager for MacOS and Linux that allows to download and install software packages using your terminal.
If you have brew on your computer, you can directly go to the next step. 

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Follow the on-screen instructions to complete the installation

## Install Python

```bash
brew install python
```
to check the version installed
```bash
python3 --version
```
You should see something like `Python 3.12.4` 

## Install Jupyter

```bash
pip3 install jupyter
```

To run the notebook: 
```
jupyter notebook
```
To run the lab:
```bash
jupyter lab
```

## Install Jupyter via Homebrew

```bash
brew install jupyter
```




