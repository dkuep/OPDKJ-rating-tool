# OPDKJ-rating-tool

Es entsteht ein interaktives Rating Tool für die OPD-KJ2[^1].

[^1]: Operationalisierte Psychodynamische Diagnostik des Kindes- und Jugendalters Version 2. Siehe [opdkj.de](https://www.opdkj.de).

## Aktuelle Version

### Milestone v0.1
- "Digitalisierte Umsetzung der Befunderhebungsbögen"
- **Achse Beziehung** 
  - Rating der Kreise S1; A1,2,3; B1,2,3
  - Darstellung in Netz-Graphen mit graph.js analog zur Excel-Version.
  - [ ] eingaben limitieren 0-4
  - [ ] Pfeile hinzufügen
  - [ ] Resizing bei Änderung des Fensters
- **Achse Konflikt** 
  - Rating mit klick-barer Tabelle analog zum Bogen zur Befunderhebung.
- **Achse Struktur** 
  - Rating in einem Input-Raster analog zum Bogen zur Befunderhebung.
  - [ ] Altersstufen eingeben
  - [ ] Eingabe limitieren (0-3 0,5er Schritte)
  - [ ] Zeilengesamt und Gesamt vor-ausreichenen
- Rudimentäres Web-Layout
- Rudimentäres Print-Layout
  - unnötige Eingabe-Felder werden verborgen
  - [ ] druckfreundliches Layout angestrebt
- **ToDo**
- [ ] Alter Gebdat Klasse
- [ ] reset button evtl. auf Abschnitts-Ebene

### Dependancies v0.1
- Bootstrap v5
- Graph.js

## Roadmap 

### Milestone v0.2
- "Druckbar wie Befunderhebungsbögen"
  - [ ] raster 3x2
  - [ ] ändern beim Drucken oder bildschirm \<x
- evtl. Änderungen an bisherigen Bögen
  - [ ] Im Urzeigersinn, ermögliche a/b in einer Spalte

### Milestone v0.31
- Vergleichende Darstellung der Beziehungskreise
  - [ ] Vergleichende Kreise A:aktiv B:reaktiv etc.

### Milestone v0.32
- erweiterte Datenanalyse wie Excel-Version

### Milestone v0.41
- Web-forward Version / geeignet für Präsentationen etc.

### Milestone v0.42
- Print-Ansicht umschaltbar / Web Ansicht wie Druck-Version

### Milestone v0.51
- Daten-Export zum Download

### Milestone v0.52
- Daten-Import

### Milestone v0.5x
- evtl. weitere Export-Möglichkeiten (Datenbank, QR)

## Vision
- Erfassung
  - Nutzung als Erhebungsbogen auf unterschiedlichen Medien (PC, Tablet, Handy, leer ausdrucken als Bewertungsbogen)
  - Gemeinsames Rating in Konferenzen oder Lehre
  - Interaktives Bearbeiten/Abstimmen von Ratings in Klinik und Lehre
  - Auszüge aus Rating-Handbuch je nach Feld
- Datenaufbereitung
  - Vergleichend darstellte Beziehungs-Kreise
  - Berechnungen (Diagonalen, Flächen, Schwerpunkte) auch Überschneidungs-Flächen 
  - Vergleich von Zeitreihen oder unterschiedlichen Befunder:innen
- Weiternutzung
  - Archivierung durch 
    - Ausdrucken des Befundbogens
    - Maschinenlesbar speichern (Zeitreihen-Untersuchungen, Auswertung, Forschung)
      - Datenbank
      - QR Code
  - Wieder-Einlesen der Daten (evtl. in R/Shiny?)




