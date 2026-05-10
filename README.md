# California Housing - Machine Learning Project

Detta projekt är en individuell machine learning-uppgift baserad på California Housing-datasetet. Syftet med projektet är att bygga och utvärdera modeller som kan förutsäga bostadsvärden utifrån geografiska och socioekonomiska variabler.

## Innehåll

Projektet innehåller:

* Dataförståelse och EDA
* Data preprocessing med pipelines och ColumnTransformer
* Modelljämförelse mellan flera regressionsmodeller
* Hyperparameter-tuning med GridSearchCV
* Slutlig utvärdering och rekommendation

## Modeller

Följande modeller användes:

* DummyRegressor (baseline)
* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor

## Struktur

```text
data/
notebook
rapport
requirements.txt
README.md
```

## Installation

Installera beroenden:

```bash
pip install -r requirements.txt
```

## Körning

Öppna notebook-filen och kör:

```text
Restart & Run All
```

för att reproducera resultaten.

## Dataset

Projektet använder California Housing-datasetet (`housing.csv`).

