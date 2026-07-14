# AC/DC Flyback Power Converter — 5V / 2A

> **Industrial-grade isolated flyback converter** stepping down Ethiopian mains (220–240V AC / 50Hz) to a regulated 5V DC / 2A output. Designed as an internship project for **DAF Tech Social ICT Solutions**, June 2026.

---

## ⚠️ Safety Warning

This project operates directly from **220–240V AC mains voltage**. Incorrect assembly or handling can result in **electric shock, fire, or death**. Do not build or test this circuit unless you are qualified to work with mains-voltage electronics. Always disconnect from mains before touching the board.

---

## Project Overview

This repository contains the complete KiCad schematic, PCB layout, and bill of materials for a **10W isolated flyback AC/DC power converter**. The design converts Ethiopian standard mains voltage to a stable, regulated 5V DC output suitable for charging mobile phones and powering low-voltage electronics.

The design was built entirely from scratch during a 2-week internship period, covering component selection, schematic capture, PCB layout, and documentation.

---

## Specifications

| Parameter | Value |
|---|---|
| Input voltage | 220 – 240V AC |
| Input frequency | 50 Hz |
| Output voltage | 5V DC (regulated ±1%) |
| Output current | 2A maximum |
| Output power | 10W |
| Efficiency | ~82% |
| Isolation voltage | 3000V AC (IEC 62368-1) |
| Switching frequency | 65 kHz |
| Output ripple | < 50mVpp |
| PCB layers | 2 (double-sided) |
| PCB creepage | 6mm minimum (HV to LV) |
| Operating temperature | −10°C to +70°C |

---

## Topology

**Isolated flyback converter** using the STMicroelectronics VIPer22AS PWM controller IC, which integrates the power MOSFET and control logic in a single SO-8 package. Feedback regulation is achieved through a TL431 shunt regulator and PC817C optocoupler maintaining full galvanic isolation between primary (mains) and secondary (output) sides.

## License

This project is released for educational purposes. Use at your own risk. The authors accept no liability for damage, injury, or death resulting from the construction or use of this circuit.

