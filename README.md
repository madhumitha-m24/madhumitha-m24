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

### ABOUT

Hardware systems engineer specializing in register-transfer level (RTL) microarchitecture, FPGA timing optimization, Software Defined Radio (SDR) signal processing, and embedded hardware-software integration.

Work spans SystemVerilog SoC interconnect design, asynchronous FIFO clock-domain crossing (CDC) controllers, real-time 64-PSK wireless transceivers, and autonomous robotics FSM micro-engines.

──────────────

### SKILLS

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

### PROJECT HIGHLIGHTS

#### ⚡ [PixelStream-fpga](https://github.com/madhumitha-m24/PixelStream-fpga)
> **Adaptive Asynchronous FIFO for FPGA Video Pixel Streaming**

<p>
  <img src="https://img.shields.io/badge/Verilog_HDL-00599C?style=flat-square" alt="Verilog HDL" />
  <img src="https://img.shields.io/badge/CDC_Sync-0f172a?style=flat-square&logo=target&logoColor=38bdf8" alt="CDC Sync" />
  <img src="https://img.shields.io/badge/Gray--Code-1e293b?style=flat-square&color=60a5fa" alt="Gray-Code" />
  <img src="https://img.shields.io/badge/iverilog-1E88E5?style=flat-square" alt="iverilog" />
  <img src="https://img.shields.io/badge/GTKWave-6A1B9A?style=flat-square" alt="GTKWave" />
</p>

* **Engineering Challenge:** Mitigating clock domain crossing (CDC) metastability and pixel jitter across unsynchronized camera-to-display clock domains.
* **Microarchitecture:** Parameterizable dual-clock asynchronous FIFO with 2-stage Gray-code pointer synchronizers (`sync_r2w.v`, `sync_w2r.v`), binary-to-Gray conversion logic, and real-time overflow/underflow flag monitoring.
* **Verification & Metrics:** Cycle-accurate timing verification in Icarus Verilog with GTKWave waveform inspection; guaranteed zero data loss under arbitrary read/write clock frequency ratios.

---

#### 📡 [pluto-sdr-64psk-voice-transceiver](https://github.com/madhumitha-m24/pluto-sdr-64psk-voice-transceiver)
> **Real-Time 64-PSK Voice Transceiver on ADALM-PLUTO SDR**

<p>
  <img src="https://img.shields.io/badge/ADALM--PLUTO_SDR-1e293b?style=flat-square&logo=cpu&logoColor=a78bfa" alt="ADALM-PLUTO" />
  <img src="https://img.shields.io/badge/GNU_Radio-3776AB?style=flat-square&logo=gnuradio&logoColor=white" alt="GNU Radio" />
  <img src="https://img.shields.io/badge/Python_DSP-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/64--PSK-0f172a?style=flat-square&color=38bdf8" alt="64-PSK" />
  <img src="https://img.shields.io/badge/RRC_Filter-6A1B9A?style=flat-square" alt="RRC Filter" />
</p>

* **Engineering Challenge:** Delivering low-latency, bandwidth-efficient wireless voice transmission over noisy radio frequency (RF) channels with dynamic phase jitter.
* **Microarchitecture:** End-to-end DSP flow with 64-PSK digital modulation (6 bits/symbol), Root-Raised Cosine (RRC, $\alpha=0.35$) pulse-shaping filters for inter-symbol interference (ISI) suppression, and carrier phase synchronization loops.
* **Verification & Metrics:** Validated via hardware-in-the-loop over-the-air audio streaming on ADALM-PLUTO SDR with clean constellation clustering and robust demodulation.

---

#### ⚖️ [weighted-roundrobin-arbiter](https://github.com/madhumitha-m24/weighted-roundrobin-arbiter)
> **Layered Weighted Round-Robin Bus Arbiter in SystemVerilog**

<p>
  <img src="https://img.shields.io/badge/SystemVerilog-002B49?style=flat-square" alt="SystemVerilog" />
  <img src="https://img.shields.io/badge/SoC_Interconnect-0f172a?style=flat-square&logo=target&logoColor=38bdf8" alt="SoC Bus" />
  <img src="https://img.shields.io/badge/WRR_Arbitration-1e293b?style=flat-square&color=60a5fa" alt="WRR" />
  <img src="https://img.shields.io/badge/ModelSim-6A1B9A?style=flat-square" alt="ModelSim" />
  <img src="https://img.shields.io/badge/Testbenches-10b981?style=flat-square" alt="Verification" />
</p>

* **Engineering Challenge:** Eliminating bus contention across competing multi-master SoC clients while guaranteeing zero starvation and proportional bandwidth allocation.
* **Microarchitecture:** Fully parameterized layered arbiter with dynamic weight-reload registers, priority update logic, and single-cycle grant generation without idle bubble states.
* **Verification & Metrics:** Verified through SystemVerilog layered testbenches with randomized client request patterns, validating fair credit depletion and immediate bandwidth convergence.

---

#### 🤖 [robot](https://github.com/madhumitha-m24/robot)
> **FPGA-Driven Autonomous Navigation & Embedded Controller**

<p>
  <img src="https://img.shields.io/badge/Verilog_HDL-00599C?style=flat-square" alt="Verilog HDL" />
  <img src="https://img.shields.io/badge/ESP32_C++-E7352C?style=flat-square&logo=espressif&logoColor=white" alt="ESP32" />
  <img src="https://img.shields.io/badge/FSM_Micro--Engine-0f172a?style=flat-square&logo=target&logoColor=38bdf8" alt="FSM" />
  <img src="https://img.shields.io/badge/UART_%7C_PWM-1E88E5?style=flat-square" alt="UART/PWM" />
  <img src="https://img.shields.io/badge/Ultrasonic_Filter-43A047?style=flat-square" alt="Ultrasonic" />
</p>

* **Engineering Challenge:** Achieving microsecond-level obstacle reflex and coordinated multi-actuator motion control through deterministic hardware-software co-design.
* **Microarchitecture:** Hardware-synthesized finite state machine (FSM) core, echo pulse-width calculation unit for ultrasonic ranging, custom asynchronous UART parser (`uart_rx.v`), and high-resolution PWM motor controllers paired with ESP32 telemetry.
* **Verification & Metrics:** Sub-millisecond reaction latency to dynamic obstacles; tested on physical mobile robotic platform with synchronized telemetry transmission.

---

#### 🧩 [mini_soc](https://github.com/madhumitha-m24/mini_soc)
> **Modular System-on-Chip (SoC) Micro-Core Fabric**

<p>
  <img src="https://img.shields.io/badge/Verilog_HDL-00599C?style=flat-square" alt="Verilog HDL" />
  <img src="https://img.shields.io/badge/ALU_Datapath-0f172a?style=flat-square&logo=cpu&logoColor=38bdf8" alt="ALU" />
  <img src="https://img.shields.io/badge/Bus_Multiplexer-1e293b?style=flat-square&color=60a5fa" alt="Bus Mux" />
  <img src="https://img.shields.io/badge/iverilog-1E88E5?style=flat-square" alt="iverilog" />
  <img src="https://img.shields.io/badge/GTKWave-6A1B9A?style=flat-square" alt="GTKWave" />
</p>

* **Engineering Challenge:** Designing an ultra-compact, deterministic SoC compute fabric with plug-and-play execution units and minimal gate count.
* **Microarchitecture:** Modular Arithmetic Logic Unit (ALU), multi-channel multiplexed bus interconnects, sequencing state control, and memory-mapped register interface.
* **Verification & Metrics:** Automated regression test suite executed via `iverilog` testbenches with comprehensive GTKWave waveform tracing confirming cycle-accurate execution.

──────────────

### SYSTEM TELEMETRY

<div align="center">

<p align="center">
  <img src="https://img.shields.io/badge/TELEMETRY_LINK-ONLINE-10b981?style=for-the-badge&logo=statuspal&logoColor=white&labelColor=0f172a" />
  <img src="https://img.shields.io/badge/TARGET_DOMAINS-RTL_%7C_FPGA_%7C_SDR-38bdf8?style=for-the-badge&logo=cpu&logoColor=white&labelColor=0f172a" />
  <img src="https://img.shields.io/badge/DESIGN_PIPELINE-VERIFIED-818cf8?style=for-the-badge&logo=target&logoColor=white&labelColor=0f172a" />
</p>

<!-- GitHub Stats & Top Languages -->
<p align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=madhumitha-m24&show_icons=true&theme=dark&hide_border=true&bg_color=0f172a&title_color=38bdf8&icon_color=60a5fa&text_color=94a3b8" alt="GitHub Stats" />
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=madhumitha-m24&layout=compact&theme=dark&hide_border=true&bg_color=0f172a&title_color=38bdf8&text_color=94a3b8" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=madhumitha-m24&theme=dark&background=0f172a&stroke=1e293b&ring=38bdf8&fire=38bdf8&currStreakNum=38bdf8&sideNums=94a3b8&currStreakLabel=60a5fa&sideLabels=94a3b8&dates=64748b" alt="GitHub Streak" />
</p>

<!-- ACTIVITY CONTRIBUTION GRAPH -->
<p align="center">
  <img src="https://raw.githubusercontent.com/madhumitha-m24/madhumitha-m24/output/github-contribution-grid-snake.svg" alt="Contribution Graph" width="100%" onError="this.style.display='none'" />
</p>

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

</div>

──────────────

<div align="center">

<sub><code>SYSTEM TELEMETRY: NOMINAL</code> · <code>RTL VERIFICATION: PASS</code> · <code>HARDWARE & SYSTEMS REPOSITORIES VERIFIED</code></sub>

</div>
