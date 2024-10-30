# MTH5810 Module 9: Project - PCA

## Local Setup

Download the 4 3D dataset as a csv file named `m9-pca.csv`.


Install the latest versions of dependencies via chocolatey

```PowerShell
& choco install python
```

Configure a python virtual environment for the class (from the project directory):

```PowerShell
& python -m venv msoe
& ./msoe/Scripts/activate.ps1
& python -m pip install -U pip wheel
& pip install -r requirements.txt
```

And to run the notebooks:

```PowerShell
& ./msoe/Scripts/activate.ps1
& jupyter notebook
```
