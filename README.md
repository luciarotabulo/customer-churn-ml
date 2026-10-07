# Customer Churn Prediction

## Descrizione Progetto
Questo progetto ha l'obiettivo di analizzare i fattori che influenzano l'abbandono dei clienti (Churn-rate) e sviluppare un modello di Machine Learning per prevedere quali clienti sono a rischio, fornendo spunti per analisi prescrittive.

## Tech Stack & Librerie
- **Linguaggio:** Python 3.x
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `seaborn`, `matplotlib`
- **Machine Learning:** `scikit-learn`
- **Ambiente di sviluppo:** Jupyter Notebook / VS Code

## Struttura del Repository
- `data/`: Contiene i dataset utilizzati nell'analisi.
  - `raw`: dataset iniziale
  - `processed`: dataset pulito
- `notebooks/`: 
  - `01_eda_and_cleaning.ipynb`: Exploratory Data Analysis e pulizia dei dati
  - `02_ml_modeling.ipynb`: Addestramento, valutazione e confronto dei modelli

## Fasi dell'Analisi
1. **Exploratory Data Analysis (EDA):** Analisi delle distribuzioni, gestione dei valori mancanti e identificazione delle correlazioni.
2. **Feature Engineering & Preprocessing:** Encoding delle variabili categoriali e scaling numerico.
3. **Machine Learning Modeling:** Implementazione e confronto di modelli baseline (Regressione Logistica) e avanzati (Random Forest / XGBoost).
4. **Valutazione & Business Impact:** Analisi delle metriche (Precision, Recall, ROC-AUC) e raccomandazioni aziendali.

## Come Eseguire il Progetto
1. Clona il repository:
   ```bash
   git clone [https://github.com/tuo-username/customer-churn-ml.git](https://github.com/tuo-username/customer-churn-ml.git)