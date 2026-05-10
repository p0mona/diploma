# Zastosowanie algorytmów uczenia maszynowego w predykcji ryzyka wystąpienia cukrzycy na podstawie wskaźników zdrowotnych

Projekt stanowi część pracy dyplomowej i dotyczy zastosowania metod uczenia maszynowego do predykcji ryzyka wystąpienia cukrzycy na podstawie wybranych wskaźników zdrowotnych.

## 🎯 Cel projektu

Celem projektu jest opracowanie oraz porównanie wybranych modeli uczenia maszynowego pod kątem ich skuteczności w klasyfikacji ryzyka wystąpienia cukrzycy.

---

## 📂 Struktura repozytorium

* `.data/`
    * `diabetes_binary_5050split_health_indicators_BRFSS2015.csv`
* `main.ipynb`
* `.gitignore`
* `README.md`

---

## ⚙️ Wykorzystane technologie

Projekt został zrealizowany w języku Python 3.14.2 z wykorzystaniem następujących bibliotek:

- pandas 2.3.3
- numpy 2.3.5
- matplotlib 3.10.7
- seaborn 0.13.2
- scipy 1.16.3
- scikit-learn 1.7.2 
- catboost 1.2.8
- shap 0.51.0

---

## ▶️ Uruchomienie projektu

Projekt został przygotowany w formie Jupyter Notebook.

### 1. Sklonuj repozytorium

```bash
git clone https://github.com/p0mona/diploma.git
cd diploma 
```

### 2. Zainstaluj wymagane biblioteki

```bash
pip install -r requirements.txt
```
### 3. Uruchom Jupyter Notebook

```bash
jupyter notebook
```

### 4. Otwórz plik main.ipynb i wykonuj komórki krok po kroku
