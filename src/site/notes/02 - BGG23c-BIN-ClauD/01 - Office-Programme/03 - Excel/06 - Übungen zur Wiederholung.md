---
{"dg-publish":true,"permalink":"/02 - BGG23c-BIN-ClauD/01 - Office-Programme/03 - Excel/06 - Übungen zur Wiederholung/"}
---

# Übungsaufgabe
Du bist Teil eines Teams, das für die Verwaltung von Patientendaten in einem Krankenhaus verantwortlich ist. Du hast eine Excel-Tabelle mit den Daten von verschiedenen Patienten erhalten. Die Tabelle enthält folgende Spalten: 

- Patientennummer
- Name
- Geburtsdatum
- Geschlecht
- Gewicht (in kg)
- Größe (in cm)
- Blutdruck (in mmHg)

Deine Aufgabe ist es, diese Daten zu formatieren und verschiedene Berechnungen durchzuführen. Erfasse dazu zunächst weitere, fiktive Patientendaten. Achte auf "realistische" Werte! Es sollen am Ende 10 Patienten vorhanden sein.

Schritte:
1. Formatierung der Excel-Tabelle:
   a) Setze einen Rahmen um die gesamte Tabelle.
   b) Markiere die Kopfzeile mit einer Hintergrundfarbe deiner Wahl.
   c) Markiere alle Spalten mit Patientendaten, jeweils mit einer anderen Hintergrundfarbe (die Überschriftenzeile bleibt in ihrer ursprünglichen Formatierung aus Aufgabe b).

	**Fortgeschrittene:**
	d) Benutze die Funktion "Bedingte Formatierung" um alle als bedenklich zu bewertenden Blutdruckwerte automatisch farblich zu markieren:

| Werte                                                   | Farbe |
| ------------------------------------------------------- | ----- |
| systolisch > 160, diastolisch >100                      | rot   |
| systolisch > 130 aber < 159, diastolisch >85 aber < 100 | gelb  |
| Werte darunter                                          | grün  |

2. Berechnungen durchführen und Anwendung von einfachen Funktionen:
   a) Lasse die Patientennummer automatisch hochzählen!
   b) In der Spalte "BMI" sollst du den Body-Mass-Index für jeden Patienten berechnen. Verwende dazu die Formel: Gewicht (in kg) geteilt durch (Größe in Meter) zum Quadrat.
   c) In der Zelle unter der Spalte "Gewicht" sollst du die Summe aller Gewichte berechnen.
   d) In der Zelle unter der Spalte "Alter" sollst du das Minimum und Maximum des Alters durch Formeln angeben lassen.
   e) In der Zelle unter der Spalte "Blutdruck" sollst du den höchsten Blutdruck und den niedrigsten Blutdruck finden und zusätzlich den Durchschnittswert des Blutdrucks aller Patienten (sowohl für die systolischen wie die diastolischen Werte).
   **Fortgeschrittene:**
   f) In den Zellen der Spalte "Geschlecht" (Spalte E) unterhalb der letzten Patientendaten sollen die Anzahl (*Funktion =SUMMEWENN(...)*) der männlichen, weiblichen und divers geschlechtlichen Patient:innen angegeben werden.
   g) Füge eine Spalte "Alter" nach der Spalte "Geburtsdatum" ein. Berechne auf Basis des aktuellen Datums (=HEUTE()) und des Geburtsdatum ins Spalte D das Alter des Patienten. (*Hinweis: Das Ergebnis der Formel muss als "Standard" formatiert werden und wird dann in Tagen angezeigt. Sinnvoll ist es, das Ergebnis also auch noch in Jahre umzurechnen.*)

4. Druckfunktionen:
   a) Füge eine Kopfzeile hinzu, die den Namen des Krankenhauses ("Klinikum Bebezett") auf der linken Seite und auf der rechten Deinen eigenen Namen enthält.
   b) Füge eine Fußzeile hinzu, die das Datum und die Seitenzahl enthält.
   c) Drucke die Tabelle als PDF-Datei aus.

**Quelle: [[Patientendaten.xlsx]]**

