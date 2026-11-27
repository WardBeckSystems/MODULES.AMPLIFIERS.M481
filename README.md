# M481 · Amplifiers

Ward-Beck Systems M481, 1975|8. Wiki page: [M481 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M481.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 12 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 4 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 5 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 42 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 4 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 10 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [2 topics](FORUM.md): what owners and technicians said about it.

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQmRGVm9DZmZEWmc/view?resourcekey=0-1COA6d-lL7ki5DxGRFwnpw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQmRGVm9DZmZEWmc&resourcekey=0-1COA6d-lL7ki5DxGRFwnpw" width="240" alt="1975 - M481 - 481-04-002 - EKD OSCILLATOR-CUE AMPLIFIER.jpg"></a><br><sub>1975|8 · 481-04-002 - EKD OSCILLATOR-CUE AMPLIFIER · <a href="MECHANICAL/1975%20-%20M481%20-%20481-04-002%20-%20EKD%20OSCILLATOR-CUE%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M481.stl`](MECHANICAL/M481.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M481)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (assumed: 1.6" x 7" x 6.5", the common module)
- **From the drawing:** 0 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M481 - front panel.svg`)
- no drawing of the front panel: the panel is blank
- Made by `tools/module_models.py` (→ `MECHANICAL/M481.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQm9rREQ5eUdBREU/view?resourcekey=0-hBmSRRZWUmMQhAeLFOInUA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQm9rREQ5eUdBREU&resourcekey=0-hBmSRRZWUmMQhAeLFOInUA" width="240" alt="1975 - M481 - 481-02-021 - MICROFARADS UNLESS OTHERWISE SPECIFIED LAST COMPONENT DESIGNATIONS.jpg"></a><br><sub>1975|8 · 481-02-021 - MICROFARADS UNLESS OTHERWISE SPECIFIED LAST COMPONENT DESIGNATIONS · <a href="SCHEMATICS/1975%20-%20M481%20-%20481-02-021%20-%20MICROFARADS%20UNLESS%20OTHERWISE%20SPECIFIED%20LAST%20COMPONENT%20DESIGNATIONS%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1975 - 481-02-001 - OSCILLATOR CUE AMPLIFIER SCHEMATIC - DRN DM - ISS 2.jpg`, `1979 - 481-01-001 - M481B CUE, OSC, RE-ENTRY MODULE FUNCTIONAL DIAGRAM - DRN P. MAHONEY - ENG MRW - ISS 1.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

Not on Google Drive yet: `M481 - RTO-144 Connections.pdf`

## RTO-144 pinout

21 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 8 | RE-ENTRY THE M2 OUTPUT | out |  | variant |
| 11 | RE-ENTRY SELECTOR AND LEVEL CONTROL OF MASTER | control |  | variant |
| 12 | RE-ENTRY SELECTOR AND LEVEL CONTROL OF MASTER | control |  | variant |
| 13 | CUE/SOLO ASSI GN SWITCH SW2 ROUTES THIE | control |  | variant |
| 17 | RE-ENTRY THE M2 OUTPUT | out |  | variant |
| 19 | POWERSUPPLY POWER | power |  | variant |
| 21 | POWERSUPPLY POWER | power |  | variant |
| N | RE-ENTRY SELECTOR AND LEVEL CONTROL OF MASTER | control |  | variant |
| U | RE-ENTRY THE M2 OUTPUT | out |  | variant |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcjlSTVJfRHUzNDA/view?resourcekey=0-1PQTWCotKnM_jB44zniLVQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcjlSTVJfRHUzNDA&resourcekey=0-1PQTWCotKnM_jB44zniLVQ" width="240" alt="1975 - M481 - Oscilator and Cue Amp (2).pdf"></a><br><sub>1975|8 · Oscilator and Cue Amp (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM3pnQWtCQzNzOWs/view?resourcekey=0-3LKa7rlHfGAxYY7MEFQM9g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM3pnQWtCQzNzOWs&resourcekey=0-3LKa7rlHfGAxYY7MEFQM9g" width="240" alt="1975 - M481 - Oscilator and Cue Amp.pdf"></a><br><sub>1975|8 · Oscilator and Cue Amp</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdlBFaWJwQzNaNmc/view?resourcekey=0-eXwc-Q03b08it9B_nKQrtA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdlBFaWJwQzNaNmc&resourcekey=0-eXwc-Q03b08it9B_nKQrtA" width="240" alt="1975 - M481 - P001 - Title Page.jpg"></a><br><sub>1975|8 · P001 - Title Page</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY21zakw5Qkc2d0k/view?resourcekey=0-JDmbntCKT6tLhkcP9XaQsQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY21zakw5Qkc2d0k&resourcekey=0-JDmbntCKT6tLhkcP9XaQsQ" width="240" alt="1975 - M481 - P002 - 1-1.jpg"></a><br><sub>1975|8 · P002 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTDZUOWdzb3JIQTQ/view?resourcekey=0-re4mmyarkrDoljQuI0Klmw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTDZUOWdzb3JIQTQ&resourcekey=0-re4mmyarkrDoljQuI0Klmw" width="240" alt="1975 - M481 - P003 - 1-2.jpg"></a><br><sub>1975|8 · P003 - 1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLXVoanhTQk1zeGc/view?resourcekey=0-SXzI01cAqxAdB7aDZclGrg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLXVoanhTQk1zeGc&resourcekey=0-SXzI01cAqxAdB7aDZclGrg" width="240" alt="1975 - M481 - P004 - 1-3.jpg"></a><br><sub>1975|8 · P004 - 1-3</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1975 - 481-02-001 - OSCILLATOR CUE AMPLIFIER SCHEMATIC - DRN DM - ISS 2.kicad_sch](KICAD/1975%20-%20481-02-001%20-%20OSCILLATOR%20CUE%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20DM%20-%20ISS%202.kicad_sch)
- [1975 - M481 - 481-02-021 - MICROFARADS UNLESS OTHERWISE SPECIFIED LAST COMPONENT DESIGNATIONS.kicad_sch](KICAD/1975%20-%20M481%20-%20481-02-021%20-%20MICROFARADS%20UNLESS%20OTHERWISE%20SPECIFIED%20LAST%20COMPONENT%20DESIGNATIONS.kicad_sch)
- [1979 - 481-01-001 - M481B CUE, OSC, RE-ENTRY MODULE FUNCTIONAL DIAGRAM - DRN P. MAHONEY - ENG MRW - ISS 1.kicad_sch](KICAD/1979%20-%20481-01-001%20-%20M481B%20CUE%2C%20OSC%2C%20RE-ENTRY%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20P.%20MAHONEY%20-%20ENG%20MRW%20-%20ISS%201.kicad_sch)
- [M481.kicad_sym](KICAD/M481.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
