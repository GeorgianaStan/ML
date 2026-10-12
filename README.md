<!-- TOC -->
* [Machine Learning](#machine-learning)
  * [Project Structure](#project-structure)
  * [Technologies and Libraries](#technologies-and-libraries)
  * [Setup](#setup)
    * [1. Create and activate a virtual environment](#1-create-and-activate-a-virtual-environment)
    * [2. Install dependencies](#2-install-dependencies)
    * [3. Configure the Jupyter interpreter](#3-configure-the-jupyter-interpreter)
  * [Usage](#usage)
<!-- TOC -->

# Machine Learning

A personal workspace for Machine Learning courses, exercises, and projects.

## Project Structure

```text
ML/
├── .venv/
├── ML/
│   ├── Projects/
│   │   ├── project_1.ipynb
│   │   └── project_2.ipynb
│   └── Courses/
│       ├── course_1.ipynb
│       └── course_2.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Technologies and Libraries

- Python
- Jupyter Notebook
- pandas
- Matplotlib
- Seaborn

## Setup

### 1. Create and activate a virtual environment

Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### 2. Install dependencies

```powershell
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
```

### 3. Configure the Jupyter interpreter

Select the project's `.venv` interpreter
when opening or running a notebook.

## Usage

- `ML/Projects/` contains personal Machine Learning projects.
- `ML/Courses/` contains notebooks and exercises from courses.
