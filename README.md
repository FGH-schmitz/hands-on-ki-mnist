# Hands-on KI mit PyTorch: MNIST

Ein interaktives Jupyter Notebook zum Erlernen der Grundlagen des maschinellen Lernens mit PyTorch am Beispiel des MNIST-Datensatzes.\
Hier kannst du das notebook in Binder öffnen: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/FGH-schmitz/hands-on-ki-mnist/HEAD?urlpath=%2Fdoc%2Ftree%2FHands-on-KI-MNIST.ipynb)\
Hier kannst du das Notebook in Colab öffnen:  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/FGH-schmitz/hands-on-ki-mnist/blob/main/Hands-on-KI-MNIST.ipynb)

## Übersicht

Dieses Notebook führt durch die wichtigsten Schritte beim Training eines neuronalen Netzwerks:
- Laden und Visualisieren von Daten
- Implementierung eines einfachen fully connected Netzwerks
- Training des Modells
- Evaluation der Ergebnisse
- Visualisierung der Vorhersagen

## Lernziele

Nach Abschluss des Notebooks wirst du verstehen:
- Wie man ein neuronales Netz definiert und implementiert
- Den Standard-Trainingsloop in PyTorch

## Voraussetzungen

- Grundkenntnisse in Python
- Jupyter Notebook Umgebung
- Die in `requirements.txt` aufgeführten Pakete

## Installation

1. Klone oder lade die Dateien herunter
2. Installiere die erforderlichen Pakete:
   ```bash
   pip install -r requirements.txt
   ```
3. Starte Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Öffne `Hands-on-KI-MNIST.ipynb`

## Nutzung

Das Notebook ist als Hands-on Workshop konzipiert. Wichtige Code-Abschnitte sind bewusst unvollständig und sollen von dir implementiert werden:

1. **Netzwerk-Architektur**: Definiere die Layer und Aktivierungsfunktionen
2. **Loss-Funktion & Optimizer**: Wähle geeignete Trainingsparameter
3. **Trainingsloop**: Implementiere den Standard PyTorch Trainingsloop
4. **Evaluation**: Berechne die Accuracy auf Testdaten

## Datensatz

Der MNIST-Datensatz wird automatisch heruntergeladen und enthält:
- 60.000 Trainingsbilder (handgeschriebene Ziffern 0-9)
- 10.000 Testbilder
- Bildgröße: 28x28 Pixel, Graustufen

## Erwartete Ergebnisse

Mit den richtigen Hyperparametern solltest du eine Accuracy von 85-95% auf den Testdaten erreichen können.

## Zeitaufwand

Ca. 20 Minuten für die komplette Durchführung des Workshops.


