# Curly Broccoli

A collection of learning notebooks. The current tutorial introduces classification with scikit-learn's built-in Breast Cancer Wisconsin dataset.

## Requirements

- Python 3.11
- Git

The notebook data is included with scikit-learn; no separate dataset download is required.

## Setup

From the repository root, create and activate a Python 3.11 virtual environment.

macOS / Linux:

```sh
python3.11 -m venv .venv311
source .venv311/bin/activate
```

Windows PowerShell:

```powershell
py -3.11 -m venv .venv311
.venv311\Scripts\Activate.ps1
```

Install the notebook dependencies:

```sh
python -m pip install --upgrade pip
python -m pip install -r notebooks/requirements.txt
```

## Run the notebook

Start Jupyter from the repository root:

```sh
jupyter notebook
```

Open `notebooks/classification/Classification_task_tutorial.ipynb`. In VS Code, select the `.venv311` Python interpreter and use it as the notebook kernel.
