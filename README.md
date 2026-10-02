# Hi, I'm Alex Marfo Appiah 👋

<img align="right" width="180" src="https://github.com/theboylexis.png" alt="Alex Marfo Appiah"/>

### Computer Engineering Student · Digital Hardware · FPGA · Backend Systems

I'm a Computer Engineering student at **KNUST** interested in understanding computing systems across the hardware–software boundary.

On the hardware side, I'm building experience in **digital design, RTL, FPGA implementation, processor architecture, verification, embedded systems, and computer architecture** as I explore hardware and semiconductor engineering.

On the software side, I work with **backend systems, APIs, databases, cloud infrastructure, asynchronous processing, and distributed systems**.

My long-term goal is to develop strong systems-level engineering skills spanning both hardware and software.

<br clear="right"/>

---

## Currently

- ⚡ Building and validating digital hardware using Verilog and FPGAs
- 🧠 Strengthening my foundations in RTL design, computer architecture, verification, and embedded systems
- 🔬 Exploring hardware and semiconductor engineering through hands-on projects
- 💻 Deepening my understanding of backend systems, APIs, databases, distributed systems, and infrastructure
- 🎓 BSc Computer Engineering, KNUST · GETFund Scholar · Expected graduation February 2028

---

## Technical Interests

### Hardware & Computer Engineering

- Digital hardware design
- RTL design and verification
- FPGA systems
- Processor and computer architecture
- Embedded systems
- Hardware/software co-design
- Digital IC design
- Semiconductor systems
- Reliable digital systems

### Software & Systems Engineering

- Backend engineering
- Distributed systems
- API design
- Databases
- Cloud infrastructure
- System design
- Asynchronous processing
- Performance and reliability

---

## Hardware & Embedded

<p>
  <img src="https://img.shields.io/badge/Verilog-000000?style=for-the-badge" alt="Verilog"/>
  <img src="https://img.shields.io/badge/RTL%20Design-000000?style=for-the-badge" alt="RTL Design"/>
  <img src="https://img.shields.io/badge/FPGA-000000?style=for-the-badge" alt="FPGA"/>
  <img src="https://img.shields.io/badge/Digital%20Design-000000?style=for-the-badge" alt="Digital Design"/>
  <img src="https://img.shields.io/badge/Computer%20Architecture-000000?style=for-the-badge" alt="Computer Architecture"/>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++"/>
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP32"/>
</p>

## Software & Systems

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" alt="Redis"/>
</p>

## Infrastructure & Tools

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Icarus%20Verilog-000000?style=for-the-badge" alt="Icarus Verilog"/>
  <img src="https://img.shields.io/badge/GOWIN%20EDA-000000?style=for-the-badge" alt="GOWIN EDA"/>
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code"/>
</p>

---

# Featured Projects

## ⚡ FPGA-Synthesizable 8-Bit CPU

A custom multi-cycle 8-bit processor designed from scratch in Verilog, verified end-to-end in simulation, and physically validated on a **Sipeed Tang Nano 20K FPGA**.

The processor uses an **8-bit datapath**, **16-bit fixed-width instructions**, and a custom **13-instruction ISA**.

### Architecture

The CPU includes:

- 8 × 8-bit general-purpose register file
- Arithmetic Logic Unit
- Program Counter
- Instruction Register
- Separate program and data memories
- Status register with Zero, Negative, and Carry/Borrow flags
- Instruction decoder
- Multi-cycle control unit
- Writeback datapath

### ISA

The processor supports:

```text
HALT
ADD
SUB
AND
OR
XOR
MOV
LOAD
STORE
CMP
JMP
BEQ
LDI
```

### Verification

Each major RTL subsystem was verified independently before full processor integration.

The complete CPU was then exercised through end-to-end machine-code programs using **Icarus Verilog**.

**13 / 13 assigned instructions were verified in simulation.**

### FPGA Implementation

The processor was synthesized and implemented for the **Tang Nano 20K** using GOWIN EDA.

Physical FPGA bring-up included:

- 27 MHz onboard clock integration
- board-level pin constraints
- SRAM programming through the onboard debugger
- onboard LED register inspection
- pushbutton synchronization
- mechanical switch debounce logic
- arithmetic hardware validation
- memory and data-movement validation
- logic and control-flow validation

Three hardware programs collectively exercised all 13 assigned instructions on the physical FPGA.

Observed architectural state matched the expected simulation results.

### Hardware Validation Status

```text
RTL design                  ✅
Module verification         ✅
CPU integration             ✅
Full ISA simulation         ✅
FPGA synthesis              ✅
Place & Route               ✅
FPGA programming            ✅
Physical hardware validation ✅
```

**Repository:** [FPGA-Synthesizable-8Bit-CPU](https://github.com/theboylexis/FPGA-Synthesizable-8Bit-CPU)

`Verilog` `RTL Design` `FPGA` `Digital Design` `Computer Architecture` `Processor Design` `Icarus Verilog` `GOWIN EDA`

---

## 💻 Smart Doc API

A production-oriented document intelligence backend for processing PDF, DOCX, and TXT documents with AI-powered analysis.

The project focuses on backend architecture, asynchronous processing, authentication, infrastructure, and deployment.

### Highlights

- JWT authentication
- 11 REST endpoints
- BullMQ job queues
- Redis caching
- Webhooks
- Rate limiting
- PostgreSQL
- CI/CD
- Nginx
- SSL
- AWS EC2, S3, and IAM
- Docker-based deployment

`Node.js` `Express` `PostgreSQL` `Prisma` `Redis` `BullMQ` `AWS` `Docker` `Linux`

---

## What I'm Building Toward

I'm working toward deeper expertise in **digital hardware, computer architecture, FPGA systems, RTL design, verification, embedded systems, and semiconductor engineering**.

At the same time, I'm continuing to strengthen my background in **backend and systems engineering**, particularly distributed systems, infrastructure, databases, APIs, and reliable software architecture.

I'm especially interested in the boundary between hardware and software — how processors are designed, how low-level systems behave, and how software ultimately interacts with the hardware beneath it.

---

## Connect

[LinkedIn](https://linkedin.com/in/alexmarfoappiah) · [Email](mailto:alexmarfo509@gmail.com)
