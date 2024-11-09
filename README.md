# Klassifizierung von Essensbildern mit Convolutional Neural Networks

Dieses Projekt ist eine schriftliche Ausarbeitung im Modul Deep Learning an der Fachhochschule Südwestfalen. Ziel des Projekts ist es, die Klassifizierung von Essensbildern mithilfe von Convolutional Neural Networks (CNNs) zu untersuchen und zu implementieren. Die Arbeit behandelt alle relevanten Schritte von der Problemstellung über die Datenvorbereitung bis hin zur Implementierung und Bewertung der Modelle.

## Inhaltsverzeichnis
1. [Einleitung](#einleitung)
2. [Stand der Technik](#stand-der-technik)
3. [Beschreibung der Problemstellung](#beschreibung-der-problemstellung)
4. [Datensatzbeschreibung](#datensatzbeschreibung)
5. [Datenvorverarbeitung](#datenvorverarbeitung)
6. [Implementierung der Lösung](#implementierung-der-loesung)
7. [Modelltraining und Evaluation](#modelltraining-und-evaluation)
8. [Kritische Reflexion](#kritische-reflexion)
9. [Fazit](#fazit)

## Einleitung
In der Einleitung wird die Bedeutung der Bildklassifizierung im Bereich der Lebensmittelindustrie hervorgehoben, z. B. für Qualitätskontrolle und Ernährungsanalyse. Convolutional Neural Networks haben sich in den letzten Jahren als besonders leistungsstark für diese Aufgabe erwiesen.

## Stand der Technik
Dieser Abschnitt beschreibt die aktuellen Fortschritte im Bereich der Lebensmittelbildklassifizierung und die Herausforderungen, die mit der Klassifizierung solcher Bilder verbunden sind.

## Beschreibung der Problemstellung
Es wird die spezifische Problemstellung behandelt, die für das Projekt relevant ist. Ziel ist es, ein Modell zu entwickeln, das Essensbilder in verschiedene Kategorien klassifizieren kann.

## Datensatzbeschreibung
In diesem Abschnitt wird der verwendete Datensatz vorgestellt und erläutert, wie die Daten aufbereitet wurden, um eine optimale Performance zu gewährleisten.

### Datenvorbereitung
- **Skalierung und Normalisierung**: Bilddaten werden vorverarbeitet, um einheitliche Eingaben für das Modell sicherzustellen.
- **Datenaugmentation**: Techniken zur Datenaugmentation werden angewendet, um die Robustheit des Modells zu erhöhen.

## Implementierung der Lösung
Die Implementierung erfolgt in Python mit der Bibliothek PyTorch. Es werden zwei Modelle verwendet:
- **SimpleCNN**: Ein einfaches CNN-Modell, das als Basis dient.
- **TinyVGG**: Eine angepasste Version des bekannten VGG-Modells.

## Modelltraining und Evaluation
Der Trainingsprozess der Modelle wird beschrieben, einschließlich der verwendeten Evaluationsmetriken und Ergebnisse.

## Kritische Reflexion
In diesem Abschnitt wird eine kritische Analyse der Ergebnisse durchgeführt, wobei sowohl die Stärken als auch die Schwächen der Ansätze hervorgehoben werden.

## Fazit
Abschließend werden die wichtigsten Erkenntnisse zusammengefasst und mögliche Weiterentwicklungen vorgeschlagen.

## Installation und Ausführung
### Voraussetzungen
- Python 3.x
- PyTorch
### Installation
1. Klonen Sie das Repository:
   ```bash
   git clone <repository-url>
