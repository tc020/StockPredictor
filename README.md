# 📈 Profit Prophet – Aktienprognosen mit Chronos

**Profit Prophet** ist eine interaktive Webanwendung zur Vorhersage von Aktienkursen und zur Anzeige von Unternehmenskennzahlen. Die App kombiniert KI-basierte Zeitreihenprognosen mit Echtzeit-Datenimport von **Kaggle** und Unternehmensinformationen aus **Wikidata**. Die Benutzeroberfläche wird mit **Gradio** bereitgestellt.

---

## 🔍 Features

- 🔄 **Täglicher Datenimport**: Automatischer Download aktueller Aktienkurse von Kaggle
- 🔮 **KI-gestützte Prognosen**: Vorhersage zukünftiger Aktienkurse mit AutoGluon
- 📊 **Interaktive Visualisierungen**: Prognoseplots für die ausgewählte Marke
- 🧠 **Wissensgraph-Integration**: Unternehmensdaten via Wikidata (Gewinn, Umsatz, Gründungsjahr etc.)
- 🌐 **Web-Oberfläche mit Gradio**: Benutzerfreundliches, interaktives Dashboard
- 🇩🇪 **Kommentierter Code auf Deutsch**: Verständlich dokumentierter Quellcode

---

## ⚙️ Technologieneinsatz

| Komponente        | Funktion                                    |
|-------------------|---------------------------------------------|
| [Gradio](https://gradio.app/)         | Interaktive Benutzeroberfläche          |
| [AutoGluon](https://auto.gluon.ai/)   | Zeitreihenmodellierung & Prognose       |
| [KaggleHub](https://github.com/aliasOfKunal/kagglehub)         | Datendownload von Kaggle                |
| [SPARQLWrapper](https://people.wikimedia.org/~bearloga/notes/wdqs-python.html) | Abfrage von Unternehmensdaten über Wikidata |
| Pandas, NumPy, PIL | Datenanalyse, Visualisierung & Bildverarbeitung |

---

## 📁 Projektstruktur
├── user-interface.ipynb    &emsp;&emsp;&emsp;&emsp;&emsp; # Hauptprogramm

├── images/    &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;# UI-Bilder (Header etc.)

├── dev/    &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;# Entwicklungsschritte

&emsp;&emsp;└── chronos_test.ipynb   &emsp;&emsp;&emsp;&emsp;# Ersten Schritte, verschiedene Datensätze & Konfigurationen mit Chronos

&emsp;&emsp;└── evaluation.ipynb   &emsp;&emsp;&emsp;&emsp;&emsp;# Evaluierung der Vorhersagen mit dem Frozen-Dataset vom 21.05.2025 

&emsp;&emsp;└── model-tests.ipynb    &emsp;&emsp;&emsp;&emsp;# Testläufe mit dem Laden von Fine-Tuning-Modellen

&emsp;&emsp;└── preprocessing_data.ipynb   &emsp;# Vorbereitung der Daten aus der Excel für Chronos

&emsp;&emsp;└── mockup_demo.ipynb    &emsp;&emsp;&emsp;# Funktionsloses Anschauungsbeispiel des UI über Gradio

&emsp;&emsp;└── google-test.ipynb    &emsp;&emsp;&emsp;&emsp;# Beispielbild für das Mockup

&emsp;&emsp;└── wissensgraph.ipynb  &emsp;&emsp;&emsp;# SPARQL und Wikidata

&emsp;&emsp;└── prototype.ipynb    &emsp;&emsp;&emsp;&emsp;&emsp;# Erster Versuch die Daten aus dem Preprocessing dem Modell zu füttern

├── README.md              &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; # Diese Datei


