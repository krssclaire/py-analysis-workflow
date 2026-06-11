# Python Data Analysis Workflows

## What is this repository?
This repository contains reusable Python workflows for exploratory data analysis, statistical modelling and research projects.
The workflows are designed to be easy to use, reproducible and accessible to students, researchers and analysts with limited programming experience.

### Objective
The goal of this project is not only to automate analyses, but also to help users understand the statistical methods behind them through guided explanations, visualizations and interpretation notes.

## Frameworks available
Framework | Description                                           | Status
----------|------------------------------------------------------ |-------
OLS       | Ordinary Least Squares for Multiple Linear Regression | 🚧 WIP
EDA       | Exploratory Data Analysis                             | 🚧 WIP
LOG-REG   | Logistic Regression                                   | 📋Planned

## How to use
### Prerequisites
* VSCode installed from the [official page](https://code.visualstudio.com/download)
*  The [Latest version](https://www.python.org/downloads/) of  Python

### Project setup
1. Clone the project in preferred folder in VScode terminal with `git clone https://github.com/krssclaire/py-analysis-workflow.git`, or Download ZIP folder and extract
2. Create virtual environment  
    * In the project folder, create a **virtual environment** through VSCode Terminal with `python -m venv .venv` which would create a `.venv` folder that will contain all necessary dependencies
    * activate environment
        * in Windows Powershell terminal  
        `.venv\Scripts\activate`
        * in Bash  
        `source .venv/Scripts/activate`

### Install dependencies
* `pip install -r requirements.txt` to install dependencies from _requirements.txt_ file

### Select interpreter
Config VSCode to select the right interpreter
* Press `Ctrl + Shift + P`, then select _Python: Select Interpreter >(.venv)_  

## Jupyter
Config Jupyter in .venv
* `pip install notebook ipykernel`
* then select kernel from the upper-right corner of the notebook

## Usage
1. Choose a framework.
2. Place the Excel file inside the framework data folder.
3. Open the notebook.
4. Run all cells.
5. Read the generated outputs and interpretations.

## Repository structure
```
py-analysis-workflow
|
├── frameworks/
│   ├── eda/
│   └── ols/
│
├── requirements.txt
└── README.md
```

## 