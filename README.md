# COVID-19 Vaccination and Mortality from Chronic Diseases in Türkiye

BSc graduation thesis (Management Information Systems, Işık University, 2024) examining how COVID-19 vaccination rates across Turkish provinces relate to deaths from major disease groups, and how data analysis and machine learning can support this kind of public-health question.

## What the project does

- Combines province-level data on first- and second-dose vaccination rates, 2020 population (TÜİK) and deaths by disease group (e.g. circulatory, respiratory, tumours)
- Groups provinces into four vaccination bands (A: 0–25%, B: 25–50%, C: 50–75%, D: 75–100%)
- Explores the data with bar, pie and scatter plots, yearly trends and correlation matrices
- Fits a **multiple linear regression** model: `Deaths = β0 + β1 · (1st dose / population) + β2 · (2nd dose / population)`

## Key findings

- Deaths from circulatory system diseases were the most frequent cause across vaccination bands.
- Nationally, most provinces fell into band C for two doses; Istanbul fell into band B and İzmir into band C.

## Files

| File | Description |
| :--- | :--- |
| `Covid19_Proje (1).ipynb` | Analysis and modelling notebook |
| `Covid-19AşıOranlarıVeÖlümlüHastalıklar.csv` | Dataset: vaccination rates and deaths by province |
| `DamlaSuYayla_Tez.pdf` | Full thesis (Turkish) |
| `DamlaSuYayla_TezPoster.pdf` | Thesis poster (Turkish) |

## Tech stack

`Python` · `pandas` · `NumPy` · `scikit-learn` · `statsmodels` · `SciPy` · `Matplotlib` · `Seaborn` · Google Colab

> The notebook and thesis are written in Turkish.
