# Machine Learning and Data Mining 2 – Lab work

Lab work for the course Machine Learning and Data Mining 2.

## Labs
| Lab | Topic | Folder |
|-----|-------|--------|
| 1 | Principal Component Analysis | `lab01-pca/` |
| 2 | Clustering | `lab02-clustering/` |

## Setup
```
pip install -r requirements.txt
jupyter notebook
```

## Data
Data files are in each lab’s `data/` folder

- **Lab 1 – PCA:** Wine Quality, UCI Machine Learning Repository (ID 186).    <br>
  Download: https://archive.ics.uci.edu/dataset/186/wine+quality    <br>
  Files: `winequality-red.csv`, `winequality-white.csv` (separator `;`), `winequality.names` (description).    <br>
  License: CC BY 4.0.   <br><br>
  Citation: P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis.   <br>
  Modeling wine preferences by data mining from physicochemical properties.   <br>
  In Decision Support Systems, Elsevier, 47(4):547-553, 2009. ISSN: 0167-9236.
  https://doi.org/10.1016/j.dss.2009.05.016

- **Lab 2 – Clustering (Part 1, k-means):** Seeds, UCI Machine Learning Repository (ID 236).    <br>
  Download: https://archive.ics.uci.edu/dataset/236/seeds    <br>
  File: `seeds_dataset.txt` (whitespace-separated, no header; 7 features + class label 1–3).    <br>
  License: CC BY 4.0.   <br><br>
  Citation: M. Charytanowicz, J. Niewczas, P. Kulczycki, P. Kowalski and S. Łukasik.   <br>
  Seeds [Dataset]. UCI Machine Learning Repository, 2010.
  https://doi.org/10.24432/C5H30K