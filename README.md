# Hi guys, I'm Thomas 👋

**Electrical Engineering Student @ UCLA** · Computer Architecture · VLSI Design · Embedded Systems · Communication Systems

Third-year Electrical Engineering student interested in building efficient digital hardware systems. I enjoy working across the full development process, from RTL design and verification to FPGA implementation and performance analysis.

My projects usually start with a question about how a system should perform, and end with hardware that proves it — designed top-down, pushed to its limits, and benchmarked until the numbers back it up.

🎓 UCLA, B.S. Electrical Engineering
🔬 Currently exploring ASIC/RTL design, digital verification, and hardware acceleration

</div>

---

### 🛠️ Tools

| | |
|---|---|
| **Languages** | SystemVerilog · C/C++ · Python · Tcl · Assembly · Bash/Shell |
| **Technologies** | Synopsys Verdi/VCS · Xilinx Vivado · MATLAB · LTspice · Git · Artix-7 · ESP32 |

---

## 🚀 Projects

### [AI Hardware Accelerator](https://github.com/ToeMatLe/AI_Accelerator)
A TPU-inspired hardware accelerator built around a parameterized systolic array for matrix multiplication. The design uses parallel multiply-accumulate processing elements and supports BF16-compatible arithmetic and ReLU activation, allowing it to model key operations used in neural-network inference.

### [Digital Audio Visualizer](https://github.com/ToeMatLe/Digital-Audio-Visualizer)
An FPGA-based audio visualizer implemented on an Artix-7 device. The system captures real-time audio input, processes the signal using an FFT-based datapath, and displays the resulting frequency information as animated bars through a VGA output.

### [Pipelined RISC-V](https://github.com/ToeMatLe/Pipelined-RISCV)
A five-stage pipelined RV32 processor implemented in SystemVerilog, featuring hazard-detection logic and forwarding paths to resolve data dependencies while minimizing pipeline stalls. The processor includes an L1 data cache that exploits spatial and temporal locality, along with an MSI coherence protocol for consistent cache-line states and future multicore support. When synthesized in Xilinx Vivado for an Artix-7 FPGA, the design achieved a maximum clock frequency of 106 MHz.

### [Reaction Game](https://github.com/ToeMatLe/Reaction_Game)
An FPGA-based reaction-time game that measures how quickly a player responds to a visual stimulus. The design uses finite-state machines, counters, button debouncing, and display-control logic to manage the gameplay sequence and report the player's reaction time.

### [Maze Solving Car](https://github.com/ToeMatLe/ECE3-Autonomous-Car)
Final project for UCLA ECE 3: a fully autonomous line-following robot built using IR sensors, motor encoders, PID control, and a multi-stage state machine. The robot detects checkpoints, executes a 225° turn, accelerates through a timed section, and stops using encoder feedback. After tuning for speed and stability, it completed the course in 5.6 seconds, the fastest time among 196 students.

---

## 🎓 UCLA Tapeout Club

I'm a member of the [UCLA Tapeout Club](https://github.com/UCLA-Tapeout-Club), a student organization dedicated to giving members hands-on experience with the full digital chip design flow — from RTL design through synthesis and physical design — with the goal of taping out a real RISC-V based chip. 

Through the club, I contribute to the development and verification of a RISC-V-based chip while learning about RTL design, simulation, synthesis, timing analysis, physical design, and the practical challenges involved in preparing a design for tapeout.

---

## 📫 Connect
I'm always open to connecting with other students, engineers, and researchers interested in computer architecture, VLSI, FPGA design, embedded systems, or communication systems. Feel free to reach out to talk about projects, research, collaboration opportunities, or anything hardware-related.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thomas-1e/)
