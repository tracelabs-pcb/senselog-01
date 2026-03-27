# SENSLOG-01 — Multi-Sensor Data Logger

**Status: PCB-Design abgeschlossen — unbestückt**  
**Tool:** KiCad | **Layer:** 4-Layer | **Hersteller-ready:** Ja

---

## Projektbeschreibung

Kompakter Multi-Sensor Datenlogger mit integrierter Messung von
Spannung, Strom und Widerstand sowie mehreren digitalen Sensoren.
Daten werden über verschiedene Schnittstellen ausgegeben und
auf SD-Karte gespeichert. Integriertes regelbares Netzteil
für 5V, 3,3V und 1,8V bis 500mA über Schraubklemmen.

**Besonderheiten:**
- Spannungs-, Strom- und Widerstandsmessung
- Integriertes Netzteil: 5V / 3,3V / 1,8V bis 500mA
- Datenspeicherung auf SD-Karte
- Multi-Protokoll: USB-C, CAN, RS485, RS232, SPI, I²C
- Via-Stitching, Leiterbahnlängen-Matching

---

## Hardware

| Komponente | Beschreibung |
|---|---|
| Schnittstellen | USB-C, CAN, RS485, RS232, SPI, I²C |
| Speicher | SD-Karte |
| Messung | Spannung, Strom, Widerstand |
| Netzteil | 5V / 3,3V / 1,8V, je bis 500mA, Schraubklemme |
| Stackup | 4-Layer (Signal / GND / Power / Signal) |
| Tool | KiCad |

---

## PCB

- 4-Layer mit durchgehender GND-Plane
- Via-Stitching für EMV-Optimierung
- Leiterbahnlängen-Matching auf kritischen Bussen

---

## Ausschlüsse

Portfolioprojekt — kein Serienprodukt, kein CE/EMV.

---

## Dateien in diesem Repository

- `/kicad/` — KiCad Projektdateien
- `/screenshots/` — PCB- und Schematic-Ansichten

---

> Entwickelt von [Shawn Schneider](https://tracelabs-pcb.de)  
> — PCB-Design & Lötservice, Wolfsburg
