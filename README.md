# Progetto Machine Learning - Wine Type

> Machine Learning Project for University Milano Bicocca. 2023-2024. Voto: 30

[![Download Progetto IPYNB](https://img.shields.io/badge/Download%20Progetto-IPYNB-red.svg?style=for-the-badge)](https://github.com/Zeptogram/ml-wine-project/releases/download/mlrelease/Progetto.ipynb)
[![Download Relazione PDF](https://img.shields.io/badge/Download%20Relazione-PDF-lime.svg?style=for-the-badge)](https://github.com/Zeptogram/ml-wine-project/releases/download/mlrelease/Relazione.pdf)
[![Download Presentazione PDF](https://img.shields.io/badge/Download%20Presentazione-PDF-orange.svg?style=for-the-badge)](https://github.com/Zeptogram/ml-wine-project/releases/download/mlrelease/Slide.pdf)
[![Dataset Vini](https://img.shields.io/badge/Dataset-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/datasets/rajyellow46/wine-quality)
[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)

## Il Progetto

Lo scopo del progetto e l’obiettivo dell’elaborato consiste nello svolgimento di
un’analisi esplorativa di un dataset, ovvero un insieme di dati, con la costruzione e
valutazione di diversi modelli di apprendimento automatico, al fine di verificare la
loro efficacia nella comprensione e previsione di diverse categorie contenute nel
dataset.

Nello specifico, il dominio preso in considerazione riguarda l’indagine su un tipo di un
vino, basato sulla sua composizione chimica.

Lo scopo è quello di poter classificare un tipo di vino, rosso o bianco, in base
all’analisi e apprendimento sulle diverse categorie (features) del dataset selezionato.

## Il Dataset e le Features

Il dataset è stato selezionato con lo scopo di garantire coerenza e rilevanza nelle
successive analisi condotte, utilizzando dati sensati e non fittizi.

In particolare, la scelta è stata orientata verso un insieme di dati che si prestasse ad
un’analisi con Principal Component Analysis (PCA), la quale richiede una struttura
dati adatta, preferibilmente con variabili numeriche continue e non nulle.

Perciò si è scelto un dataset con categorie maggiormente di tipo numerico continuo.

Il dataset, come accennato in precedenza, riguarda la classificazione binaria di tipi di
vini date le seguenti features (categorie), le quali descrivono la composizione chimica
di un vino:
- __Fixed acidity (acido tartarico)__: Misura della quantità di acido tartarico presente
nel vino, espressa in grammi per decimetro cubo (g/dm³).
- __Volatile acidity (acido acetico)__: Misura della quantità di acido acetico presente
nel vino, espressa in grammi per decimetro cubo (g/dm³).
- __Citric acid (acido citrico)__: Quantità di acido citrico presente nel vino, espressa
in grammi per decimetro cubo (g/dm³).
- __Residual sugar (zucchero residuo)__: Quantità di zucchero residuo nel vino,
espressa in grammi per decimetro cubo (g/dm³).
- __Chlorides (cloruri)__: Concentrazione di cloruri nel vino, espressa in grammi di
cloruro di sodio per decimetro cubo (g/dm³).
4
- __Free sulfur dioxide (anidride solforosa libera)__: Quantità di anidride solforosa
libera nel vino, espressa in milligrammi per decimetro cubo (mg/dm³).
- __Total sulfur dioxide (anidride solforosa totale)__: Quantità totale di anidride
solforosa presente nel vino, espressa in milligrammi per decimetro cubo
(mg/dm³).
- __Density (densità)__: Densità del vino, espressa in grammi per decimetro cubo
(g/dm³).
- __pH__: Misura dell'acidità o basicità del vino su una scala da 0 a 14.
- __Sulphates (solfati)__: Concentrazione di solfati nel vino, espressa in grammi di
solfato di potassio per decimetro cubo (g/dm³).
- __Alcohol (alcol)__: Percentuale di alcol nel vino per volume (% vol).
- __Quality__: Qualità di un vino espressa con una valutazione da 0 a 10.

La qualità di un vino si esprime con un valore di valutazione da 0 a 10 dunque
potrebbe essere considerata categorica, mentre le altre features, che sono proprietà
chimiche, sono esprimibili attraverso valori continui.


## Autori

- Matteo Cavaleri
- Elio Gargiulo
- Cristian Piacente



