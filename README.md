# Lab 5 - Exploratory Data Analysis (EDA) & Visualization Basics

EDA is a library that analyzes student data through histograms and scatter plots as well as cleaning the data.

## Environment Setup

Add environment.txt file to /src

```txt
pytest
pandas
matplotlib
seaborn # nicer defaults than pure matplotlib
ipykernel
notebook
```

Setup environment through Mamba / Conda

```python
mamba create -n lab_4 --file environment.txt -y
mamba activate lab_4
```

## Dataset Description

The student_csv file being analyzed contains information including a student number, their ID, age, GPA, gender, major, and year in school.
