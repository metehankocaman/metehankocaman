# Metehan Kocaman

Electrical Engineering graduate (Carleton University, Ottawa).  
I build and verify digital + embedded systems — FPGA RTL, hardware-facing software, and comms-focused prototypes — and I’m most in my element when there’s a real signal path, timing constraints, and debugging involved.

---

## What I’m focused on

- **Digital hardware & verification:** SystemVerilog RTL, FSM/datapath design, self-checking testbenches, BRAM-based designs, on-board validation (ILA, waveforms, reproducible sims)
- **Embedded + instrumentation:** UART/SPI/I2C workflows, test automation (PyVISA/SCPI), lab tool integration, and writing software that drives hardware reliably
- **Communications interest:** I’m especially drawn to practical comms problems (serial links, timing, noise/robustness, protocol correctness) and want to keep building deeper here

I like projects that force clean thinking: clear interfaces, measurable correctness, and evidence (simulation + hardware capture) instead of vibes.

---

## Highlight projects

### FPGA: Moving Average + BRAM + Verification Environment
A moving-average core backed by BRAM with a structured SystemVerilog verification setup (driver/monitor/scoreboard).  
Emphasis on **debugging a faulty baseline**, fixing control/datapath alignment issues, and proving correctness with self-checking tests.

### FPGA: UART 8N1 @ 9600 (RX/TX + 16× tick enable)
UART receiver/transmitter with mid-bit sampling, framing error handling, and a baud tick generator.  
Validated through simulation, terminal I/O, and ILA capture.

### FPGA: Fibonacci Generator (Datapath + FSM)
Controller–datapath architecture with manual/auto modes and a strict stop condition.  
Built to be readable, verifiable, and demonstrably correct on hardware.

### Capstone (WIP to publish): FBG-Based Archery Analyzer
- FBG sensors + ESP32 acquisition + Python GUI visualization/reporting  
- Built calibration/peak detection workflows (Python/MATLAB)  
- Replaced broken commercial optical hardware with a DIY webcam spectrometer approach  
- Goal: a repeatable measurement pipeline you can actually trust

---

## Tools I use

**HDL / FPGA:** SystemVerilog, Vivado, ILA, constraints (XDC), simulation + waveform debug  
**Software:** Python, MATLAB, C/C++  
**Embedded / Test:** ESP32, UART/SPI/I2C, PyVISA, SCPI  
**Lab:** scope / logic analyzer / spectrum tools (as needed)

---

## Contact

- Email: metehankocaman@outlook.com  
- LinkedIn: https://www.linkedin.com/in/metehan-kocaman
