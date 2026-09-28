# 👋 Hi, I'm Sergio Zapata Valenciano

🎓 **Electronic Engineer (Licenciatura)** — Instituto Tecnológico de Costa Rica (TEC)  
📍 Costa Rica | 🧠 Digital design & verification, computer architecture, mixed-signal hardware  
🔎 Open to **VLSI / ASIC design, design verification, and PCB / hardware engineering** roles

---

## 🔍 About Me

I'm an electronic engineer working at the intersection of **digital IC design, computer architecture, and hardware you can actually touch**.
I've taken designs from RTL to GDSII, built and verified RISC-V hardware on FPGA, and designed multilayer mixed-signal PCBs with RF sections.

I like understanding how systems really behave: debugging with waveforms, measuring instead of assuming, and reporting results honestly, including the hypotheses that didn't hold.

---

## 🛠️ Technical Skills

**Digital design & verification**
- Verilog, SystemVerilog, testbench development, assertions, functional verification
- RTL-to-GDSII flow: Synopsys DC / ICC2 (SAED 90 nm)
- FPGA: Xilinx Vivado, Artix-7 (Nexys A7), timing closure and utilization analysis
- Verilator, waveform analysis and debugging

**Computer architecture**
- RISC-V ISA (RV32I/M), pipelining, hazards and forwarding
- Vector / SIMD processing (RVV), custom ISA extensions
- Hardware–software co-design, bare-metal firmware

**Analog, mixed-signal & PCB**
- KiCad (multilayer boards), LTspice, Multisim
- RF front-ends, impedance matching, EMI/EMC fundamentals, PDN and decoupling
- Open-source analog flow: Xschem, ngspice, SkyWater Sky130 PDK

**Programming & systems**
- C, Python, x86-64 Assembly, RISC-V Assembly, MATLAB/Simulink
- Linux (Ubuntu, Kali, WSL), Git / GitHub, LaTeX

---

## 📌 Selected Projects

🔹 **RVV-lite Vector Coprocessor on PicoRV32 (Undergraduate thesis)**  
Implemented a 15-instruction subset of the RISC-V Vector Extension as a PCPI coprocessor on a Nexys A7 FPGA (4 × 32-bit lanes, 8 × 128-bit vector register file). Timing closed at **100 MHz** (WNS +0.094 ns). Measured cycle reductions of up to **~64%** on dot product and **62%** on FIR versus scalar execution, validated with statistical analysis (Welch's t-test, ANOVA, regression). Fully documented, with RTL analysis, FSM diagrams, and timing waveforms.

🔹 **RISC-V Core with Kyber / ML-KEM Vector Acceleration** *(in progress)*  
A RISC-V core built from scratch with custom vector ISA extensions for post-quantum cryptography (NTT, modular arithmetic). Vector unit integrated directly into the pipeline. Validated against NIST ACVP vectors (110/110 passing), with cycle-level constant-time verification. FPGA synthesis on Nexys A7-100T underway.  
🔗 [core-riscv-kyber](https://github.com/Sergiozapata13/core-riscv-kyber)

🔹 **Cross-validated RISC-V Emulators (x86-64 NASM + C)**  
Two independent RV32IM emulators, one written entirely in x86-64 assembly and one in C with an SDL2 frontend. Both support CSRs, RARS syscalls, MMIO keyboard/framebuffer, and a disassembler. Validated against each other with differential trace comparison (18,972 identical instructions) and benchmarked head-to-head.  
🔗 [emulador-riscv-x86](https://github.com/Sergiozapata13/emulador-riscv-x86) · [emulador-riscv-c](https://github.com/Sergiozapata13/emulador-riscv-c)

🔹 **4-bit ALU at Transistor Level (Sky130)** *(in progress)*  
CMOS ALU with 8 operations (add, subtract, full 4×4 multiply, magnitude compare, AND/OR/XOR), designed with Xschem + ngspice on the open-source Sky130 PDK, with delay and power characterization.  
🔗 [alu4bit-sky130](https://github.com/Sergiozapata13/alu4bit-sky130)

🔹 **RTL-to-GDSII Projects (Synopsys, SAED 90 nm)**  
Full physical design flow for a register-bank execution unit and a Micro8088 processor, from synthesis through place & route.

🔹 **Verification Projects (SystemVerilog / UVM concepts)**  
Verification environments for an Intel 8088 register bank and an IEEE-754 floating-point unit.  
🔗 [reg-bank-8088](https://github.com/Sergiozapata13/reg-bank-8088) · [fpu-ieee754](https://github.com/Sergiozapata13/fpu-ieee754)

🔹 **STM32 USB + RF Board (KiCad)**  
Multilayer mixed-signal PCB with LDO regulation, ferrite-bead filtering, and an nRF24L01+ RF section with discrete LC impedance matching.

🔹 **WiFi / IoT Security Lab** *(in progress)*  
ESP32 as a target device, Raspberry Pi as the orchestration platform, and packet-capture analysis on Kali Linux.

---

## 📫 Contact

- 💼 LinkedIn: [linkedin.com/in/sergio-zv](https://www.linkedin.com/in/sergio-zv)
- 💻 GitHub: [github.com/Sergiozapata13](https://github.com/Sergiozapata13)
- ✉️ szapatav.26@gmail.com

---

⭐ Feel free to explore my repositories or reach out if you're working on digital design, verification, computer architecture, or hardware systems.
