<div align="center">

```
██████╗ ██████╗ ██╗ ██████╗ ██╗  ██╗████████╗
██╔══██╗██╔══██╗██║██╔════╝ ██║  ██║╚══██╔══╝
██████╔╝██████╔╝██║██║  ███╗███████║   ██║   
██╔══██╗██╔══██╗██║██║   ██║██╔══██║   ██║   
██████╔╝██║  ██║██║╚██████╔╝██║  ██║   ██║   
╚═════╝ ╚═╝  ╚═╝╚═╝ ╚═════╝ ╚═╝  ╚═╝   ╚═╝  
```

### Computer Engineering · University of Alabama
**FPGA Development · Digital Design · EDA Tooling**

[![](https://img.shields.io/badge/Focus-FPGA%20%26%20RTL%20Design-1B2A4A?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyek0xMiA0YzQuNDEgMCA4IDMuNTkgOCA4cy0zLjU5IDgtOCA4LTgtMy41OS04LTggMy41OS04IDgtOHoiLz48L3N2Zz4=)](https://github.com/brighht)
[![](https://img.shields.io/badge/Board-Lattice%20iCE40%20UPduino-0E7490?style=for-the-badge)](https://github.com/brighht)
[![](https://img.shields.io/badge/Tools-Quartus%20Prime%20%7C%20Cadence%20%7C%20LTspice-2563EB?style=for-the-badge)](https://github.com/brighht)

</div>

---

## About

I'm a Computer Engineering student at the University of Alabama, focused on the intersection of **digital hardware design** and **EDA tooling**. My work lives at the boundary where logic meets silicon — building and verifying designs that actually run on real hardware.

I work with FPGAs not just as a learning tool but as a platform for solving real problems: serial communication interfaces, display controllers, and eventually softcore processors. On the software side, I build systems-level applications in C/C++ where performance and hardware awareness matter.

---

## Hardware I Work With

| Board | Fabric | Toolchain |
|---|---|---|
| Lattice iCE40 UPduino 3.1 | 5.3K LUTs · 30 DSPs · 1Mb SPRAM | OSS CAD Suite (Yosys + nextpnr) |
| Intel DE1 (Altera Cyclone II) | 20K LEs · PLLs · embedded memory | Quartus Prime |

---

## Projects

### 🔷 FPGA & Digital Design

#### [`modulo60-bcd-counter`](https://github.com/brighht/modulo60-bcd-counter)
> Modulo-60 BCD counter implemented in Quartus Prime schematic capture on the DE1 FPGA board. Counts 00–59 with correct carry chain, reset logic, and 7-segment display output. Built as part of coursework in digital electronics; debugged missing carry connections and floating control pins through simulation and hardware verification.

`Quartus Prime` `Schematic Capture` `BCD Logic` `DE1 Board` `7-Segment Display`

---

#### [`uart-controller-ice40`](https://github.com/brighht/uart-controller-ice40) *(in progress)*
> UART transmitter and receiver implemented in Verilog on the Lattice iCE40 UPduino 3.1. Includes FSM-based TX/RX modules, simulation testbench, and hardware validation. Part of a broader series building communication protocol IPs on open-source FPGA tooling.

`Verilog` `UART` `FSM Design` `UPduino` `OSS CAD Suite` `Testbench`

---

### ⚙️ Systems & C/C++

#### [`football-tactics-visualizer`](https://github.com/brighht/football-tactics-visualizer) *(in progress)*
> Desktop application for visualizing and animating football (soccer) tactics, built in C/C++ with SDL2 on Linux (WSL2). Renders a pitch, supports real-time player movement, and is being extended with tactic playback and formation editing. Motivated by a genuine interest in football analysis.

`C/C++` `SDL2` `WSL2` `2D Graphics` `Game Loop Architecture`

---

## Skills & Tools

```
HDL          →  Verilog · (learning SystemVerilog)
FPGA Tools   →  Quartus Prime · OSS CAD Suite · Yosys · nextpnr
EDA / Sim    →  Cadence · LTspice · OrCAD · ModelSim
Languages    →  C · C++ · (Python for scripting)
Platforms    →  Lattice iCE40 · Intel Cyclone II · WSL2 / Linux
```

---

## What I'm Building Toward

Right now I'm working through a self-directed series of FPGA projects on the UPduino — UART, SPI, display controllers, and eventually a minimal softcore CPU. The goal is to build genuine hardware intuition, not just pass coursework.

If you're working on digital design, FPGA tooling, or embedded systems and want to connect — feel free to reach out.
bright.andohh@gmail.com

---

<div align="center">

*University of Alabama · Computer Engineering · Tuscaloosa, AL*

</div>
