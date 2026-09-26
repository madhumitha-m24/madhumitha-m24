<!-- customization guide:
     replace 'madhumitha-m24' with your exact github username.
     links and stats will resolve automatically.
-->

<div align="center">

<!-- HERO BANNER -->
<img src="https://capsule-render.vercel.app/api?type=soft&color=0:0f172a,40:180b30,100:0f172a&height=190&section=header&text=Madhumitha&fontSize=38&fontColor=38bdf8&fontAlign=50&fontAlignY=38&subtext=Focused%20on%20building%20efficient,%20scalable,%20and%20timing-accurate%20hardware%20systems.&subtextFontSize=14&subtextColor=94a3b8&subtextAlign=50&subtextAlignY=65" width="100%" alt="Developer Banner" />

<!-- ANIMATED TYPING HEADER -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=16&pause=1200&color=38BDF8&center=true&vCenter=true&width=600&height=40&lines=Building+Real-World+Systems;VLSI+%7C+FPGA+%7C+SoC+Engineer;RTL+Microarchitecture+%26+Timing;SDR+%26+Embedded+DSP+Systems" alt="Typing Header" />
  </a>
</p>

<!-- HARDWARE SPECIFICATION BADGES -->
<p align="center">
  <img src="https://img.shields.io/badge/languages-Verilog%20%7C%20SystemVerilog%20%7C%20C%20%7C%20C++%20%7C%20Python-1e293b?style=flat&logo=codeforces&logoColor=38bdf8&labelColor=0f172a" />
  <img src="https://img.shields.io/badge/eda%20%26%20hardware-Vivado%20%7C%20Yosys%20%7C%20ModelSim%20%7C%20GTKWave-1e293b?style=flat&logo=amd&logoColor=60a5fa&labelColor=0f172a" />
  <img src="https://img.shields.io/badge/dsp%20%26%20sdr-GNU%20Radio%20%7C%20ADALM--PLUTO-1e293b?style=flat&logo=cpu&logoColor=a78bfa&labelColor=0f172a" />
</p>

</div>

──────────────

### 01 / ABOUT

Hardware systems engineer specializing in register-transfer level (RTL) microarchitecture, FPGA timing optimization, Software Defined Radio (SDR) signal processing, and embedded hardware-software integration.

Work spans SystemVerilog SoC interconnect design, asynchronous FIFO clock-domain crossing (CDC) controllers, real-time 64-PSK wireless transceivers, and autonomous robotics FSM micro-engines.

──────────────

### 02 / SKILLS

*(Derived strictly from verified hardware and systems project repositories)*

```
├── 💻 Languages
│   ├── SystemVerilog (IEEE 1800)
│   ├── Verilog HDL
│   ├── C / C++
│   └── Python
│
├── 🔧 Hardware & EDA Toolchain
│   ├── AMD Xilinx Vivado ML
│   ├── Yosys Open Synthesis Engine
│   ├── Siemens ModelSim / GTKWave
│   ├── Icarus Verilog (iverilog)
│   ├── GNU Radio Companion / ADALM-PLUTO SDR
│   └── ESP32 Microcontrollers / Arduino
│
└── 🧩 Concepts & Engineering Patterns
    ├── RTL Microarchitecture & Pipelining
    ├── Clock Domain Crossing (CDC) Synchronization
    ├── Weighted Round-Robin (WRR) Bus Arbitration
    ├── Finite State Machines (FSMs) & UART Parsers
    └── Real-Time 64-PSK DSP & SDR Modulation
```

──────────────

### 03 / PROJECT HIGHLIGHTS

#### 01 / [PixelStream-fpga](https://github.com/madhumitha-m24/PixelStream-fpga)
> **Adaptive Asynchronous FIFO for FPGA Video Pixel Streaming**
* **Problem:** Mitigating clock domain crossing (CDC) metastability and pixel data loss across unsynchronized camera-to-display clock domains.
* **Architecture:** Developed a parameterizable asynchronous FIFO controller in Verilog with Gray-code pointer synchronization (`sync_r2w.v`, `sync_w2r.v`), occupancy monitoring, and packet integrity checking.
* **Stack:** Verilog HDL, Icarus Verilog, GTKWave, FPGA Logic Synthesis.

---

#### 02 / [pluto-sdr-64psk-voice-transceiver](https://github.com/madhumitha-m24/pluto-sdr-64psk-voice-transceiver)
> **Real-Time 64-PSK Voice Transceiver on ADALM-PLUTO SDR**
* **Problem:** Achieving low-latency, band-efficient wireless audio transmission over software-defined radio hardware.
* **Architecture:** Implemented a digital signal processing pipeline utilizing 64-PSK modulation, root-raised cosine (RRC) pulse shaping, and carrier recovery blocks in GNU Radio and Python.
* **Stack:** Python, GNU Radio Companion, ADALM-PLUTO SDR, Digital Signal Processing (DSP).

---

#### 03 / [weighted-roundrobin-arbiter](https://github.com/madhumitha-m24/weighted-roundrobin-arbiter)
> **Layered Weighted Round-Robin Bus Arbiter in SystemVerilog**
* **Problem:** Resolving bus contention among multi-master SoC clients while guaranteeing starvation-free, weighted bandwidth allocation.
* **Architecture:** Designed a parameterized layered arbiter with dynamic priority register updates and verified through SystemVerilog layered testbenches.
* **Stack:** SystemVerilog (IEEE 1800), Simulation Testbenches, RTL Bus Logic.

---

#### 04 / [robot](https://github.com/madhumitha-m24/robot)
> **FPGA-Driven Autonomous Navigation & Embedded Controller**
* **Problem:** Real-time obstacle avoidance and motor control requiring low-latency sensor parsing and reliable FSM transitions.
* **Architecture:** Integrated SystemVerilog navigation finite state machines, ultrasonic distance filtering, UART command parsers (`uart_rx.v`), and PWM drivers interfacing with ESP32 firmware.
* **Stack:** Verilog HDL, ESP32 C++, Ultrasonic Sensors, UART, PWM Controllers.

---

#### 05 / [mini_soc](https://github.com/madhumitha-m24/mini_soc)
> **Modular System-on-Chip (SoC) Micro-Core Fabric**
* **Problem:** Designing a minimal, deterministic hardware core fabric with extensible execution units for embedded processing.
* **Architecture:** Implemented ALU operation modules, multiplexer bus interconnects, and control logic driven by automated Icarus Verilog testbenches and GTKWave tracing.
* **Stack:** Verilog HDL, Icarus Verilog (`iverilog`), GTKWave.

──────────────

### 04 / SYSTEM TELEMETRY

<div align="center">

<!-- customization: replace 'madhumitha-m24' with your exact github handle if different -->
<p align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=madhumitha-m24&show_icons=true&theme=dark&hide_border=true&bg_color=0f172a&title_color=38bdf8&icon_color=60a5fa&text_color=94a3b8" alt="GitHub Stats" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=madhumitha-m24&layout=compact&theme=dark&hide_border=true&bg_color=0f172a&title_color=38bdf8&text_color=94a3b8" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=madhumitha-m24&theme=dark&background=0f172a&stroke=1e293b&alarm=38bdf8&fire=38bdf8&ring=38bdf8&bright_mode=false" alt="GitHub Streak" />
</p>

<!-- ACTIVITY CONTRIBUTION GRAPH -->
<p align="center">
  <img src="https://raw.githubusercontent.com/madhumitha-m24/madhumitha-m24/output/github-contribution-grid-snake.svg" alt="Contribution Graph" onError="this.style.display='none'" />
</p>

</div>

──────────────

<div align="center">

<sub>`STATUS: PRODUCTION READY | HARDWARE & SYSTEMS REPOSITORIES VERIFIED`</sub>

</div>
