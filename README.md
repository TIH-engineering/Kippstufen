# Kippstufen

[![release](https://img.shields.io/github/v/release/TIH-engineering/Kippstufen?label=release)](https://github.com/TIH-engineering/Kippstufen/releases)
[![Build](https://github.com/TIH-engineering/Kippstufen/actions/workflows/build.yml/badge.svg)](https://github.com/TIH-engineering/Kippstufen/actions/workflows/build.yml)
![Hardware](https://img.shields.io/badge/Hardware-KiCad-blue)
![License](https://img.shields.io/badge/License-CC--BY--NC--SA--4.0-lightgrey)

## 🔌 Leiterplattenbeschreibung

Die Leiterplatte **Kippstufen** dient zur Untersuchung verschiedener digitaler Grundschaltungen und Kippstufen. Sie wurde insbesondere für den Einsatz im Elektroniklabor und zur praktischen Ergänzung des Unterrichts entwickelt.

Auf der Leiterplatte sind unterschiedliche Schaltungsvarianten realisiert:

- **diskret aufgebaute Kippstufen** mit Transistoren
- **Kippstufe mit NE555-Timer**
- **bistabile Kippstufe** mit Logik-IC
- **monostabile Kippstufe** mit Logik-IC
- **astabile Kippstufe** mit Logik-IC

Über Taster und Steckverbinder können die Schaltungen angesteuert und unterschiedliche Betriebsarten untersucht werden. LEDs dienen zur optischen Anzeige der jeweiligen Ausgangszustände.

Bei der diskret aufgebauten Kippstufe ermöglichen Jumper die Konfiguration als **bistabile, monostabile oder astabile Kippstufe**. Zusätzlich sind Messanschlüsse vorgesehen, unter anderem zur Untersuchung der Kondensatorspannungen.

Die Leiterplatte eignet sich damit zur praktischen Untersuchung von **Schaltzuständen, Zeitverhalten, Rückkopplung und Oszillation** bei unterschiedlichen Realisierungen von Kippstufen.

> **Einsatzgebiet:** Laborübungen und Unterricht im Bereich Digitaltechnik / Elektronik

---

## 📥 Downloads

| Datei | Beschreibung |
|---|---|
| 📄 [Schaltplan (PDF)](../../releases/latest/download/schematic.pdf) | Schaltplan der Leiterplatte |
| 🖨️ [Leiterplatte (PDF)](../../releases/latest/download/pcb.pdf) | Leiterplattenansicht als PDF |
| 🔩 [Bohrplan (PDF)](../../releases/latest/download/drill.pdf) | Bohrdaten / Bohrplan |
| 📋 [Stückliste (Excel)](../../releases/latest/download/bom.xlsx) | Bill of Materials |
| 🌐 [Interactive BOM](../../releases/latest/download/ibom.html) | Interaktive Bestückungsansicht |
| 📦 [Fertigungsdaten](../../releases/latest/download/kicad.zip) | Gerber- und Bohrdaten |
| 🧊 [STEP-Modell](../../releases/latest/download/pcb.step) | 3D-Modell der Leiterplatte |

Die Dateien werden automatisch durch den Release-Workflow erzeugt.

---

## 🖥️ Leiterplatte

### Vorschau

| Oberseite | Unterseite |
|:---:|:---:|
| ![PCB Top](../../releases/latest/download/top.kicad.thumbnail.png) | ![PCB Bottom](../../releases/latest/download/bottom.kicad.thumbnail.png) |

### Oberseite

![PCB Top](../../releases/latest/download/top.kicad.png)

### Unterseite

![PCB Bottom](../../releases/latest/download/bottom.kicad.png)

---

## ℹ️ Projektinformationen

| Eigenschaft | Wert |
|---|---|
| **Projekt** | Kippstufen |
| **Software** | KiCad 10 |
| **Repository** | TIH-engineering/Kippstufen |
| **Autor** | TIH |
| **Lizenz** | CC BY-NC-SA 4.0 |

---

## 🗂️ Repository-Struktur

```text
.
├── .github/
│   └── workflows/       # GitHub Actions
├── .kibot/              # KiBot-Konfiguration
├── pcb/
│   ├── lib/             # Projektspezifische Bibliotheken
│   └── ...              # KiCad-Projektdateien
├── .gitignore
├── LICENSE
└── README.md