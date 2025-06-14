# Data Visualization with Python

This repository contains a structured course on data visualization using Python's Matplotlib library. The course is organized into multiple Jupyter notebooks, each focusing on different visualization techniques.

## Project Structure

```
.
├── _Course_DataViz_CrystalClearCode_.pdf   # Course documentation
├── csvStudentGen.py                        # Student data generator
├── data/
│   ├── courses.csv                         # Course dataset
│   └── randomStudentData.csv               # Generated student data
└── src/
    └── matplotlib_notebooks/               # Tutorial notebooks
        ├── tp1.ipynb
        ├── tp2.ipynb
        ├── tp3.ipynb
        ├── tp4.ipynb
        ├── tp5.ipynb
        ├── tp6.ipynb
        └── tp7.ipynb
```

## Prerequisites

- Python 3.x
- Jupyter Notebook
- pandas
- matplotlib

## Setup

1. Create and activate a virtual environment:
```bash
python -m venv dataviz_venv
source dataviz_venv/bin/activate
```

2. Install required packages:
```bash
pip install jupyter pandas matplotlib
```

3. Alternatively:
```bash
pip install -r requirements.txt
```

## Usage

1. Navigate to `src/matplotlib_notebooks/` and open any of the tutorial notebooks (tp1.ipynb through tp7.ipynb)

2. Start Jupyter Notebook server:
```bash
jupyter notebook .
```
## Course Materials

Refer to `_Course_DataViz_CrystalClearCode_.pdf` for detailed course content and instructions.

## Tutorial Notebooks

The course is divided into several practical tutorials:
- `tp1.ipynb` through `tp7.ipynb`: Progressive lessons covering various aspects of data visualization with Matplotlib

Each notebook contains practical exercises and examples to help you master data visualization concepts.
