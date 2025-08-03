# NLP Textanalyse – Yelp Bewertungen klassifizieren

[![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Jam-Reut/ml-nlp-text-analysis/HEAD?labpath=nlp-text-analysis.ipynb)

## Projektbeschreibung

In diesem Natural Language Processing (NLP) Projekt wird ein Klassifizierungsmodell erstellt, das **Yelp-Bewertungen** basierend auf ihrem Text automatisch in **1-Stern** oder **5-Stern** Kategorien einteilt.
Wir verwenden eine vorbereitete Machine Learning Pipeline, um die Textdaten zu verarbeiten und ein Modell zu trainieren.
Die verwendeten Yelp-Daten stammen von Kaggle und beinhalten unter anderem:
- `text`: Die eigentliche Bewertung
- `stars`: Bewertungs-Skala von 1 bis 5 (wir nutzen nur 1 und 5)
- `cool`, `useful`, `funny`: Community-Votes

## Projektstruktur

nlp-text-analysis/

- yelp.csv # Yelp-Datensatz
- nlp-yelp-text-analysis.ipynb 
- README.md # Diese Datei

## Ausführung

1. Starte das Projekt über den Binder-Button oben.
2. Öffne das Notebook `ml-nlp-text-analysis.ipynb`.
3. Führe das Notebook Schritt für Schritt aus.
4. Ziel ist es, ein Modell zu trainieren, das 1- und 5-Sterne-Bewertungen korrekt unterscheidet.

## Erwartetes Ergebnis

- Das Notebook erstellt ein Modell zur binären Textklassifikation. 
- Das Modell sollte anhand des Bewertungstextes mit akzeptabler Genauigkeit voraussagen können, ob eine Bewertung 1 oder 5 Sterne erhalten hat.

