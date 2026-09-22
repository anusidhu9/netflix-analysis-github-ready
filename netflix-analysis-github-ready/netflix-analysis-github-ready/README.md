# Netflix Analysis

## Overview

This project contains a cleaned, GitHub-ready Jupyter Notebook for analyzing Netflix data with Python.

The notebook is organized as an exploratory data analysis workflow, including:

- Loading and inspecting the dataset
- Data cleaning and preparation
- Exploratory analysis
- Data visualization
- Analysis of patterns in the Netflix dataset

The original notebook is preserved as the basis of the cleaned project; outputs and local machine-specific paths have been removed so it can be run from a shared project repository.

## Project Structure

```text
netflix-analysis/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   └── README.md
├── notebooks/
│   └── netflix-analysis.ipynb
└── outputs/
    └── figures/
        └── .gitkeep
```

## Setup

### 1. Clone the repository

```bash
git clone <your-github-repository-url>
cd netflix-analysis
```

### 2. Create a virtual environment

Windows:

```bash
python -m venv .venv
.venv\Scripts\activate
```

macOS/Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Add the dataset

Place the required Netflix CSV dataset inside:

```text
data/
```

The notebook is configured to use a project-relative data path. If your CSV has a different filename, update the dataset path in the notebook.

### 5. Run the notebook in VS Code

Open the project folder in VS Code, open:

```text
notebooks/netflix-analysis.ipynb
```

Select the Python environment created above as the notebook kernel and run the cells from top to bottom.

## Requirements

The project uses Python with common data-analysis and visualization libraries. See `requirements.txt` for the package list.

## Notes

- Notebook outputs and execution counts were removed to keep the repository clean.
- Machine-specific file paths were replaced with project-relative paths where applicable.
- Generated figures can be stored under `outputs/figures/`.
- Do not commit passwords, API keys, tokens, or other sensitive information.

## Dataset

### Data

The required dataset has been uploaded to the `data/` folder and is ready to be used by the notebook.

