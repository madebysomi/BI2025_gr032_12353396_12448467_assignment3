# BI2025 Assignment 3 - Group 032

[![DOI](https://zenodo.org/badge/1136533907.svg)](https://doi.org/10.5281/zenodo.18294073)


CRISP-DM workflow + provenance (PROV-O) using BI2025 Starvers

Authors: Somayeh Zeraati (12353396), Sandeep Kaur (12448467)  
Course: Business Intelligence (188.429), WS 2025, TU Wien  
Repository (URI/PID):

https://github.com/madebysomi/BI2025_gr032_12353396_12448467_assignment3

https://doi.org/10.5281/zenodo.18294073

---

## Contents

- Notebook: BI2025_gr032_12353396_12448467_wp.ipynb
- Report PDF: BI2025_gr032_12353396_12448467.pdf
- Dependencies: requirements.txt
- License: LICENSE (MIT)

---

## Dataset download and placement (required)

The notebook expects the dataset at this exact path:

data/datasets/immo_data/immo_data.csv

### Source

Kaggle dataset: Apartment rental offers in Germany (ImmoScout24)  
https://www.kaggle.com/datasets/corrieaar/apartment-rental-offers-in-germany

### Steps

1. Download the dataset CSV from Kaggle (a Kaggle account may be required).
2. Create the folder:
   data/datasets/immo_data/
3. Copy and rename the CSV file to exactly:
   data/datasets/immo_data/immo_data.csv

Important: The dataset is not included in this repository. Please follow the Kaggle license/terms shown on the dataset page.

---

## Environment setup (Conda recommended)

Python version: 3.11

### Create environment and install dependencies (terminal)

```bash
conda create -n BI2025 python=3.11 -y
conda activate BI2025
pip install -r requirements.txt
```

---

## Running the notebook

Open and run:
BI2025_gr032_12353396_12448467.ipynb

Notes:

- Some cells communicate with the BI2025 triplestore via the starvers package.
- Internet access is required for triplestore operations.

---

## Report generation

The notebook generates the LaTeX report under:
data/report/

---

## License

This repository is licensed under the MIT License. See LICENSE.

Dataset license is defined by the Kaggle dataset page. The dataset is not redistributed here.
