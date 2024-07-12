# Entwicklung von Powerlifting in der Schweiz

## Projektübersicht

Dieses Projekt analysiert die Entwicklung von Powerlifting in der Schweiz unter Verwendung von Daten, die von [Open Powerlifting](https://openpowerlifting.org/) bereitgestellt werden. Ziel ist es, Trends und Veränderungen im schweizerischen Powerlifting über die letzten 20 Jahre zu identifizieren und zu visualisieren.

## Autor

Sandro Gassner

## Datum

25. Juni 2024

## Inhalte

- Datenimport und Bereinigung
- Analysen der Powerlifting-Wettkämpfe in der Schweiz
- Entwicklungen in verschiedenen Alters- und Gewichtsklassen
- Vergleiche zwischen den Geschlechtern

## Verwendete R-Pakete

- `data.table`
- `tidyverse`
- `stringr`
- `knitr`
- `kableExtra`
- `RColorBrewer`
- `ggpubr`
- `reshape`
- `httr`
- `utils`

## Datenquellen

Die Daten wurden von der Webseite [Open Powerlifting](https://openpowerlifting.org/) heruntergeladen und verarbeitet. Die Daten umfassen alle erfassten Wettkämpfe, die in der Schweiz stattfanden. Internationale Wettkämpfe und nicht erfasste Wettkämpfe wurden ausgeschlossen.

## Datenaufbereitung

Die Datenaufbereitung umfasst:

1. Download und Extraktion der neuesten Open Powerlifting CSV-Datei.
2. Filtern der Daten für Wettkämpfe, die in der Schweiz stattfanden.
3. Entfernen von Spalten und Datensätzen, die für die Analyse nicht relevant sind.
4. Gruppierung der Daten nach Altersklassen und Geschlechtern.
5. Berechnung von DOTS für eine standardisierte Bewertung der Leistung.

## Analysen

### Starts an allen Wettkämpfen pro Jahr und Verband

Diese Analyse zeigt die absolute Anzahl der Starts an Wettkämpfen pro Jahr und Verband. Dabei werden alle Teilnehmer gezählt, unabhängig davon, ob sie an mehreren Wettkämpfen teilgenommen haben.

### Anzahl aktiver Athletinnen und Athleten pro Jahr und Verband

Diese Analyse zeigt die Anzahl der Athletinnen und Athleten, die im jeweiligen Jahr mindestens an einem Wettkampf teilgenommen haben. Jeder Athlet wird nur einmal pro Jahr gezählt.

### Starts an nationalen Wettkämpfen nach Geschlecht

Diese Analyse zeigt die Anzahl der Starts an nationalen Wettkämpfen, unterteilt nach Geschlecht.

### Starts an nationalen Wettkämpfen nach Alterskategorie

Diese Analyse zeigt die Anzahl der Starts an nationalen Wettkämpfen, unterteilt nach Alterskategorie.

### Frauenanteil an nationalen Wettkämpfen

Diese Analyse zeigt den Anteil der Frauen an nationalen Wettkämpfen in Prozent.

### Average DOTS Podium

Diese Analyse zeigt die durchschnittlichen DOTS-Werte der Podiumsplatzierungen, unterteilt nach Geschlecht und Alterskategorie.

### Starts und DOTS nach Gewichtsklasse

Diese Analysen zeigen die Anzahl der Starts und die durchschnittlichen DOTS-Werte der Podiumsplatzierungen, unterteilt nach Gewichtsklassen.

## Ergebnisse

Die Ergebnisse der Analysen werden in Form von Tabellen und Grafiken dargestellt, um die Entwicklungen im Powerlifting in der Schweiz zu visualisieren. Die Analysen zeigen Trends in der Anzahl der Starts, der aktiven Athleten, der Geschlechterverteilung und der Leistungsentwicklung über die letzten 20 Jahre.

---

## Kontakt

Für Fragen oder Anmerkungen kann der Kraftdreikampfverband Schweiz unter [inanzen@kraftdreikampf] kontaktiert werden.
