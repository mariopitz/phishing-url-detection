# Phishing URL Detection

Questo progetto ha l'obiettivo di individuare URL di phishing utilizzando tecniche di Machine Learning supervisionato.
A partire da un dataset di URL etichettati come legittimi o phishing, sono state applicate tecniche di esplorazione dei dati, preprocessing, feature engineering e addestramento di diversi modelli di classificazione.

I modelli utilizzati sono:
- Logistic Regression
- Naive Bayes
- K-Nearest Neighbors (KNN)

Le performance sono state valutate tramite cross-validation e metriche standard di classificazione.

---

## Dataset
Il dataset utilizzato è:
**PhiUSIIL Phishing URL Dataset**

Il dataset contiene URL etichettati come:
- 0: URL legittimo
- 1: URL phishing

Include sia feature numeriche sia attributi testuali, dai quali sono state estratte ulteriori caratteristiche.

---

## Librerie utilizzate
Il progetto è stato sviluppato in Python e utilizza le seguenti librerie principali:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## Struttura del codice
Il codice è organizzato in un unico notebook/script che segue le seguenti fasi:

1. Import delle librerie
2. Caricamento del dataset
3. Exploratory Data Analysis (EDA)
4. Preprocessing e feature engineering
5. Addestramento dei modelli
6. Cross-validation
7. Valutazione dei risultati
8. Analisi delle metriche e visualizzazione (confusion matrix, ROC curve)

---

## Esecuzione del codice

### Notebook *.ipynb*
1. Aprire il notebook con Google Colab
2. Importare il dataset *PhiUSIIL Phishing URL Dataset* in
```
from google.colab import files
files.upload()
```
4. Eseguire tutte le celle in ordine
