[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

# Ferien & Feiertage – Web-App

**Ferien & Feiertage** ist eine moderne Web-App zur Anzeige und zum Export von Schulferien und Feiertagen für deutsche Bundesländer. Die Daten werden live von [openholidaysapi.org](https://www.openholidaysapi.org/de/) geladen – ein API-Key ist nicht erforderlich.

## Funktionen

- **Bundesland, Jahr und Datenart wählen:** Auswahl von Bundesland, Jahr und ob Ferien, Feiertage oder beides angezeigt werden sollen.
- **Vergleich zweier Bundesländer:** Optional können die Ferien/Feiertage von zwei Bundesländern verglichen werden. Überlappungen werden hervorgehoben.
- **Dynamische Jahr-Auswahl:** Die verfügbaren Jahre werden je nach Bundesland und Datenart automatisch ermittelt.
- **Tabellarische Darstellung:** Übersichtliche Tabelle mit Typ, Bezeichnung, Start, Ende und Anzahl der Tage.
- **Einzeltage auflisten:** Umschaltung zwischen Zeiträumen und einzelnen Tagen.
- **Export:** Tabelle als Excel (.xlsx) oder PDF exportieren.
- **Druckfunktion:** Optimierte Druckansicht.
- **Responsive Design:** Funktioniert auf Desktop und Mobilgeräten.

## Nutzung

1. Öffne die `index.html` im Browser.
2. Wähle ein Bundesland und ein Jahr aus.
3. Optional: Aktiviere den Vergleich und wähle ein zweites Bundesland.
4. Wähle die gewünschte Datenart.
5. Klicke auf **Suchen**.
6. Die Ergebnisse erscheinen in der Tabelle.
7. Über die Toolbar können die Daten als Excel/PDF exportiert, gedruckt oder als Einzeltage angezeigt werden.

## Technische Details

- **Datenquelle:** [openholidaysapi.org](https://www.openholidaysapi.org/de/)
- **Export:** [SheetJS](https://sheetjs.com/) für Excel, [jsPDF](https://github.com/parallax/jsPDF) für PDF
- **Frontend:** Reines HTML, CSS und JavaScript, keine weiteren Abhängigkeiten

## Lizenz & Autor

MIT License  
© 2025 Wolfgang Saal, Böllenborn

Download & Quellcode: [github.com/wsaal68/](https://github.com/wsaal68/)

---

**Hinweis:** Die Daten werden automatisiert von einer öffentlichen API geladen. Es wird keine Gewähr für