# Programming_for_DA
# Programming for Data Analytics

This repository contains my work for **Programming for Data Analytics**, including Python programming exercises, data analysis, and Jupyter Notebook activities.

The project environment is managed using **uv**, with Python, Pandas, Matplotlib, Seaborn, and Jupyter.

---

## Project Setup

The project was created and configured using the following tools:

* Python 3.14.2
* uv 0.12.16
* Pandas 3.0.6
* Matplotlib 3.11.2
* Seaborn 0.13.2
* Jupyter 1.1.1

---

## 1. Install uv

`uv` is used to manage the Python project, virtual environment, and dependencies.

```bash
pip install uv
```

Check that uv is installed:

```bash
uv --version
```

---

## 2. Initialise the Project

The project was initialised using:

```bash
uv init
```

This created the Python project:

```text
programming-for-da
```

The project configuration is stored in `pyproject.toml`.

---

## 3. Check Python Version

The Python version available in the environment was checked using:

```bash
python3 --version
```

The initial Python version was:

```text
Python 3.14.2
```

Pip was also upgraded/checked using:

```bash
python3 -m pip install --upgrade pip
```

---

## 4. Create the Virtual Environment

An attempt was initially made to create a Python 3.11 environment using:

```bash
uv venv --python3.11
```

This produced an error because the correct syntax is:

```bash
uv venv --python <PYTHON>
```

The following command was then used:

```bash
uv venv --python 3.11
```

Python 3.11.16 was successfully detected and the virtual environment was created.

However, `uv` produced the following warning:

```text
The requested interpreter resolved to Python 3.11.16,
which is incompatible with the project's Python requirement:
>=3.14
```

The virtual environment was therefore later recreated automatically using Python 3.14 when project dependencies were added.

---

## 5. Activate the Virtual Environment

The virtual environment was activated with:

```bash
source .venv/bin/activate
```

The Python version was initially:

```text
Python 3.11.16
```

After adding the project dependencies, `uv` recreated the environment using Python 3.14.2.

The current Python version is:

```text
Python 3.14.2
```

---

## 6. Create Project Folders

Two folders were created for the project:

```bash
mkdir data
mkdir L1
```

The resulting project structure is:

```text
Programming_for_DA/
│
├── data/
│
└── L1/
```

The `data` directory is intended to contain datasets used during the exercises.

The `L1` directory is used for Lesson 1 work.

---

## 7. Install Pandas

Pandas was added to the project using:

```bash
uv add pandas
```

This installed Pandas and its required dependencies, including NumPy.

The installed Pandas version is:

```text
pandas==3.0.6
```

---

## 8. Install Matplotlib and Seaborn

Matplotlib and Seaborn were added using:

```bash
uv add seaborn matplotlib
```

The installed versions are:

```text
matplotlib==3.11.2
seaborn==0.13.2
```

These libraries will be used for data visualisation and exploratory data analysis.

---

## 9. Install Jupyter

Jupyter was added to the project using:

```bash
uv add jupyter
```

This installed Jupyter and its supporting packages, including:

* JupyterLab
* Notebook
* IPython
* ipykernel
* ipywidgets
* nbconvert
* nbformat

Jupyter will be used to develop and run Python code interactively.

---

## 10. Lesson 1 Notebook

The Lesson 1 directory was created:

```bash
cd L1
```

An attempt was made to create a notebook using:

```bash
touch L1.ipynd
```

and:

```bash
touch L1.ipnb
```

These filenames were created during the initial setup.

### Correct Jupyter Notebook Extension

The standard Jupyter Notebook file extension is:

```text
.ipynb
```

Therefore, the Lesson 1 notebook should ultimately be named:

```text
L1.ipynb
```

The intended project structure is:

```text
Programming_for_DA/
│
├── data/
│
├── L1/
│   └── L1.ipynb
│
├── .venv/
├── pyproject.toml
├── uv.lock
└── README.md
```

---

## Technologies Used

### Python

Python is the primary programming language used for the project.

### uv

`uv` is used for:

* Python project initialisation
* Virtual environment management
* Dependency management
* Package installation

### Pandas

Pandas is used for:

* Data manipulation
* Data cleaning
* Data analysis
* Working with tabular datasets

### Matplotlib

Matplotlib is used for creating data visualisations and charts.

### Seaborn

Seaborn is used for statistical data visualisation and creating informative graphics.

### Jupyter

Jupyter provides an interactive environment for writing and executing Python code.

---

## Dependencies

The main project dependencies are:

```text
pandas
matplotlib
seaborn
jupyter
```

The project uses `pyproject.toml` to define project dependencies and `uv.lock` to lock the resolved package versions.

---

## Project Structure

The expected repository structure is:

```text
Programming_for_DA/
│
├── data/
│   └── # Data files
│
├── L1/
│   └── L1.ipynb
│
├── .venv/
│   └── # Local virtual environment
│
├── pyproject.toml
├── uv.lock
└── README.md
```

> **Note:** The `.venv` directory is a local virtual environment and should normally not be uploaded to GitHub. It can be recreated from the project configuration and lock file.

---

## Development Workflow

The basic workflow for this project is:

```text
Install uv
    ↓
Initialise project with uv
    ↓
Check Python version
    ↓
Create virtual environment
    ↓
Activate virtual environment
    ↓
Create project folders
    ↓
Add Pandas
    ↓
Add Matplotlib & Seaborn
    ↓
Add Jupyter
    ↓
Create Jupyter notebooks
    ↓
Perform data analysis
    ↓
Commit work to Git
    ↓
Push project to GitHub
```

---

## Current Status

The project environment has been successfully configured with:

* Python 3.14.2
* uv
* Pandas
* Matplotlib
* Seaborn
* Jupyter
* `data` directory
* `L1` directory

The next stage is to begin the Lesson 1 exercises in the Jupyter Notebook.

---

## Author

**Mark Opata**

**Programming for Data Analytics**
