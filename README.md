# DSCI 552 — Homework 3

Jesse Ngo

Time-domain feature extraction from the UCI AReM (Activity Recognition based on Multisensor data fusion) time series data, with bootstrap confidence intervals for each feature's standard deviation, plus ISLR exercise 3.7.4.

## Structure

```
.
├── README.md
├── .gitignore
├── requirements.txt
├── data
│   └── AReM
│       ├── bending1 ... walking   (one folder per activity, datasetN.csv per instance)
│       ├── bendingType.pdf
│       └── sensorsPlacement.pdf
└── notebook
    └── Ngo_Jesse_HW3.ipynb
```

## Running

```
pip install -r requirements.txt
```

Open `notebook/Ngo_Jesse_HW3.ipynb` in Jupyter and run all cells. The data is loaded with the relative path `../data/AReM`. Three data files were cleaned by hand: `bending2/dataset4.csv` (spaces replaced with commas) and `cycling/dataset9.csv`, `cycling/dataset14.csv` (trailing comma removed).

## Data

AReM dataset, UCI Machine Learning Repository:
https://archive.ics.uci.edu/ml/datasets/Activity+Recognition+system+based+on+Multisensor+data+fusion+%28AReM%29
