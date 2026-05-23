<div align="center">

Overhead-Line-Mechanical-Clearance-Tool

**Engineering tool for overhead AL3 conductor analysis**
*Mechanical clearance · Thermal ampacity · Sag & Swing*

[![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python)](https://python.org)
[![IEC 60826](https://img.shields.io/badge/IEC-60826:2017-1B3A6B?style=flat-square)](https://www.iec.ch/)
[![IEEE 738](https://img.shields.io/badge/IEEE-738--2023-2563EB?style=flat-square)](https://standards.ieee.org/)
[![EEHC](https://img.shields.io/badge/EEHC-AL3%20Spec-0F766E?style=flat-square)](.)

</div>

---

Screenshots

<div align="center">

| Main Interface | Thermal Analysis | Wind Load |
|:-:|:-:|:-:|
| ![Main](screenshots/main.jpg) | ![Thermal](screenshots/thermal.jpg) | ![Wind](screenshots/wind.jpg) |

</div>

---

What it does

- **Mechanical** — calculates conductor sag, swing angle, and tension under wind and temperature using the EN 50341 cubic state-change equation
- **Thermal** — finds conductor temperature and maximum ampacity using the full IEEE 738-2023 heat balance model
- **Wind Load** — applies the complete IEC 60826:2017 formula with gust factor, span reduction, and drag correction
- **13 AL3 conductors** built-in (16 mm² → 400 mm², EEHC specification)

---

Download & Run

**Option A — Windows EXE (no Python needed)**
Download `Overhead-Line-Mechanical-Clearance-Tool.zip`, extract, and run `OverheadLineAnalyzer.exe`

**Option B — Python source**
```bash
pip install customtkinter matplotlib
python overhead_line_v4.py
```

---

Documentation

Full technical documentation with all 17 equations, input reference, and conductor database:
[Overhead-Line-Mechanical-Clearance-Tool_Documentation_1.pdf](Overhead-Line-Mechanical-Clearance-Tool_Documentation_1.pdf)

---

<div align="center">

Made by **Mohamed Ezaldine** · IEC 60826 · IEEE 738-2023 · EEHC

</div>
