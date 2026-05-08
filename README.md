# Bärenpark – Lernprodukte

Eine Web-App der **Pädagogischen Hochschule Graubünden (PHGR)** zur Beurteilung von Lernprodukten aus drei Zyklen.

## Über die App

Die Bärenpark-Aufgabe wurde im Kontext der Weiterbildungen zur Einführung des Lehrplan 21 im Kanton Graubünden entwickelt. Sie diente als Einstiegsauftrag unter dem Titel «Diagnose – fördern – beurteilen».

Fünf Schülerinnen und Schüler aus Zyklus 1, 2 und 3 haben die gleiche Aufgabe gelöst. Die App ermöglicht es, die Lernprodukte (Bild + Audio) zu vergleichen und anhand von zyklusspezifischen Beurteilungsrastern zu beurteilen.

## Ordnerstruktur

```
baerenpark/
├── index.html          ← Hauptdatei (alles in einer Datei)
├── audio/
│   ├── Kind_1.mp3
│   ├── Kind_2.mp3
│   ├── Kind_3.mp3
│   ├── Kind_4.mp3
│   └── Kind_5.mp3
├── bilder/
│   ├── Kind_1.jpg
│   ├── Kind_2.jpg
│   ├── Kind_3.jpg
│   ├── Kind_4.jpg
│   └── Kind_5.jpg
└── raster/
    ├── Zyklus_1.png
    ├── Zyklus_2.png
    └── Zyklus_3.png
```

## Funktionen

- Audioplayer mit Play/Pause und Fortschrittsbalken
- Notizfeld pro Kind (wird lokal im Browser gespeichert)
- Beurteilungsraster per Zyklus-Tab umschaltbar
- Funktioniert auf Desktop und Smartphone

## Hosting

Die App läuft als statische Seite auf **GitHub Pages** — kein Server, kein Backend nötig.

Aktivieren unter: Repository → Settings → Pages → Branch `main` → Save

## Entwicklung

Erstellt mit HTML/CSS/JavaScript (keine externen Abhängigkeiten ausser Google Fonts).  
Design orientiert sich am Corporate Design der PHGR.

---

*PHGR – Pädagogische Hochschule Graubünden*
