# Biomedical Engineering Master Studies - projects 
## Table of Contents
- [OPSI](#opsi)
- [PGiPD](#pgipd)
- [WSI](#wsi)
- [Technologies](#technologies)
- [Contributors](#contributors)

## OPSI - Computational Foundations of Artificial Intelligence (Obliczeniowe Podstawy Sztucznej Inteligencji)
The goal of the project was to extract the respiratory component from the ECG (electrocardiogram) signal using different distributions. The results obtained had some inaccuracies, but reproduced the model respiratory component.

### Used distributions (scikit-learn implementations)
- PCA
- kPCA
- ICA

### Steps
1. Database selection [(Physionet's Sleep Apnea-ECG)](https://physionet.org/content/apnea-ecg/1.0.0/)
2. Data normalization
3. Distributions implementation
4. EDR visualization
5. Effects comparison

## PGiPD - Acquisition, Collection and Processing of Biomedical Data (Pozyskiwanie, Gromadzenie i Przetwarzanie Danych Biomedycznych)
The aim of the project was to repeat the operations carried out on the data in the scientific article, as well as to analyze the results obtained. In the course, however, the wavelet transform was abandoned in favor of fast Fourier transform (FFT). Nonetheless, it was not possible to obtain the same results as in the article.

## WSI - Introduction to Artificial Intelligence (Wprowadzenie do Sztucznej Inteligencji)
The goal of this project was to become familiar with the entire process that the data prepared for the AI undergoes. Starting with the selection of the database (archaic ones were selected for additional difficulty), through exploration and preprocessing, and ending with learning the selected models  and determining their effectiveness.

### Used models and statistics
- kNN algorythm
- SVM (Support Vector Machine)
- Decision Trees
- F1-score
- Accuracy
- Confusion matrix

### Steps
1. Dataset selection [(Echocardiogram)](https://archive.ics.uci.edu/dataset/38/echocardiogram)
2. Preprocessing (outliers removal, data division into train/test sets)
3. Classification with chosen models
4. Confusion matrix, accuracy and f1-score analysis.

## Technologies
- Python
- Pandas
- NumPy
- SciPy
- Scikit-Learn
- Matplotlib
- Seaborn

## Contributors
- [Marta Arendt](https://github.com/natrendt)
- [Maciej Mechliński](https://github.com/ciuek)
