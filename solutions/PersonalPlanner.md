---
layout: default
title: Personal Planner (Power Apps)
---

# Personal Planner (Power Apps)

Ein persönlicher Planner in **Power Apps**, der die **Mitarbeiter-Planung** einfach und effizient macht.  
Planung von **Tasks, Orders und Vacation** pro Mitarbeiter – vollständig in **Dataverse** gespeichert.

**LinkedIn-Post:**  
https://www.linkedin.com/posts/fabian-brandt-2b1a36100_poweratelier-powerplatform-lowcode-activity-7405567835789344770-tHUX

---

## Problem / Ziel

Ziel war es, **Daily Planning** in Power Apps praxisnäher und benutzerfreundlicher zu machen:
- schnelle Umplanung im Alltag
- Verschieben von Zuweisungen über Mitarbeiter hinweg
- fein granular pro Tag anpassbar

---

## Key Features

### Drag & Drop Planung
- Planung per **Drag & Drop** über wiederverwendbare Templates
- Items können zwischen Mitarbeitern verschoben werden oder auf Tagesebene angepasst werden

### Optional: Click-to-move
Für schnelle Änderungen:
1. Planning-Item auswählen
2. Ziel-Tag im Kalender anklicken
3. Item wird dorthin verschoben

### Layout komplett konfigurierbar
- Row height
- Column width
- Pagination
- Date range
- Defaults: Start ab „heute“

---

## Daten & Architektur

### Dataverse als Basis
Alle Planungsdaten werden vollständig in **Dataverse** gespeichert – als stabile, skalierbare Grundlage (z. B. später für Power BI).

### PCF für Drag & Drop
Für Drag & Drop wird eine **PCF-Komponente** genutzt (by Scott Durow).  
Planner-Logik, Datenmodell und UI-Verhalten sind **custom-built**.

---

## Ergebnis / Learnings

- Umsetzung in **4 Tagen**
- Fokus auf Klarheit, Kontrolle und echte Anforderungen
- Vergleich: Versuch mit vibe.powerapps.com / generierten Pages führte nach mehreren Stunden nicht zu einem nutzbaren Ergebnis

---

## Roadmap / Ideen
- Power BI Dashboard (auf Basis der Dataverse-Daten)
- UX-Feinschliff (Keyboard, Shortcuts, schnellere Bulk-Aktionen)
- Validierungen (Konflikte, Kapazitäten, Abhängigkeiten)

---

## Screenshots / DemoVideo

<iframe width="1840" height="1035" src="https://www.youtube.com/embed/wguuDynQRZI" title="Power Apps Personal Planner" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>




