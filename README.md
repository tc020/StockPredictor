# 📈 Profit Prophet – Aktienprognosen & Unternehmensanalyse mit KI

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

## ⚙️ Tech Stack

| Komponente        | Funktion                                    |
|-------------------|---------------------------------------------|
| [Gradio](https://gradio.app/)         | Interaktive Benutzeroberfläche          |
| [AutoGluon](https://auto.gluon.ai/)   | Zeitreihenmodellierung & Prognose       |
| [KaggleHub](https://github.com/aliasOfKunal/kagglehub)         | Datendownload von Kaggle                |
| [SPARQLWrapper](https://rdflib.github.io/sparqlwrapper/) | Abfrage von Unternehmensdaten über Wikidata |
| Pandas, NumPy, PIL | Datenanalyse, Visualisierung & Bildverarbeitung |

---

## 📁 Projektstruktur
├── app.py                  # Hauptprogramm

├── images/                 # UI-Bilder (Header etc.)

├── requirements.txt        # Abhängigkeiten

├── README.md               # Diese Datei
