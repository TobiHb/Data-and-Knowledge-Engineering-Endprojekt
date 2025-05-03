# 🧠 Data and Knowledge Engineering – Endprojekt

## Projekt: Spieleranalyse mit relationalen und RDF-Datenquellen  
**Autor**: Tobias Hundsberger  
**Matrikelnummer**: h12042646

---

## 📌 Projektbeschreibung

In diesem Projekt wird gezeigt, wie Daten aus **relationalen Datenbanken** mit **RDF-Datenquellen (DBpedia)** zusammengeführt und analysiert werden können. Die Applikation ist im Rahmen des Kurses *Data and Knowledge Engineering* entstanden.

Ziel ist es, Daten über Fußballspieler aus einem Fifa-Datensatz mit zusätzlichen Informationen aus DBpedia zu kombinieren, abzufragen und sinnvoll auszuwerten.

---

## 🗂️ Inhalt des Notebooks

Das Jupyter Notebook führt folgende Schritte durch:

1. **Initialisierung einer relationalen Datenbank** mit Fifa-Spielerdaten
2. **Erweiterung der Datenbank** mit Daten aus DBpedia über eine SPARQL-Abfrage
3. **Verknüpfung beider Datenquellen** zur Anreicherung der Informationen
4. **Erstellung von Views und Abfragen**, z. B.:
   - Alle brasilianischen Fußballspieler
   - Spieler mit einer Gesamtbewertung über 88
   - Sortierung der Spieler nach Gehalt

---

## 🔍 Technologien & Tools

- SQLite (relationale Datenbank)
- SPARQL (Abfrage von RDF-Daten über DBpedia)
- Python (Jupyter Notebook)
- Bibliotheken: `sqlite3`, `requests`, `pandas`, `rdflib` (ggf. je nach Implementation)

