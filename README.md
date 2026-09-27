# Hi, I'm Alex Marfo Appiah 👋

### Computer Engineering Student · Hardware, Semiconductor Systems & Backend Engineering

I'm a Computer Engineering student at KNUST interested in understanding computing systems across both hardware and software.

On the hardware side, I'm currently building my foundation in **digital design, RTL, FPGA implementation, processor architecture, verification, and embedded systems** as I explore the broader field of **hardware and semiconductor engineering**.

On the software side, I continue to deepen my experience in **backend engineering, distributed systems, cloud infrastructure, APIs, databases, and system design**.

My long-term goal is to develop strong systems-level engineering skills across the hardware–software boundary.

---

## Currently

- 🔧 Designing and verifying digital hardware in Verilog
- ⚡ Implementing and validating a custom 8-bit processor for the Sipeed Tang Nano 20K FPGA
- 🧠 Strengthening foundations in digital logic, RTL design, processor architecture, hardware verification, and embedded systems
- 💻 Deepening my understanding of backend engineering, APIs, distributed systems, databases, and infrastructure
- 🔬 Exploring hardware and semiconductor engineering through hands-on digital design and FPGA projects
- 🎓 BSc Computer Engineering, KNUST · GETFund Scholar · Expected graduation February 2028

---

## Technical Interests

### Hardware & Semiconductor Engineering

- Digital hardware design
- RTL design and verification
- FPGA systems
- Processor and computer architecture
- Digital logic
- Embedded systems
- Hardware/software co-design
- Digital IC design
- Semiconductor engineering
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
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code"/>
</p>

---

## Featured Hardware Project

### FPGA-Synthesizable 8-Bit CPU

A custom multi-cycle 8-bit processor designed from scratch in Verilog with a 16-bit fixed-width instruction format and a custom 13-instruction ISA.

The processor includes an 8 × 8-bit register file, ALU, Program Counter, separate program and data memories, Instruction Register, status register, instruction decoder, multi-cycle control unit, and integrated datapath.

Each subsystem was implemented and verified independently before full CPU integration. The complete assigned ISA has been exercised through end-to-end simulation using Icarus Verilog, and the design has successfully completed FPGA synthesis for the Sipeed Tang Nano 20K.

**Key features:**

- 8-bit datapath
- 16-bit fixed-width instructions
- 8 general-purpose 8-bit registers
- Custom 13-instruction ISA
- Arithmetic and logical operations
- LOAD and STORE memory operations
- Immediate and register data movement
- CMP and status flag generation
- Conditional branching and jump control flow
- Multi-cycle FETCH, DECODE, EXECUTE, MEMORY, WRITEBACK, and HALT sequencing
- Module-level verification
- Full CPU integration testing
- 13 / 13 assigned instructions verified end-to-end
- FPGA synthesis completed successfully for the Sipeed Tang Nano 20K
- RTL v1.0 development checkpoint

**Current status:**

- RTL implementation complete
- Module-level and full-system simulation passing
- Complete 13-instruction ISA verified
- FPGA synthesis completed successfully for the Tang Nano 20K
- Preparing for board-level implementation and hardware validation

**Next phase:**

- FPGA board-level implementation
- Pin and clock integration
- Hardware validation on the Sipeed Tang Nano 20K
- Debugging and refinement based on physical FPGA behavior

**Repository:** [FPGA-Synthesizable-8Bit-CPU](https://github.com/theboylexis/FPGA-Synthesizable-8Bit-CPU)

`Verilog` `RTL Design` `FPGA` `Digital Design` `Computer Architecture` `Processor Design` `Icarus Verilog`

---

## Selected Software Project

### Smart Doc API

A production-oriented document intelligence backend for processing PDF, DOCX, and TXT documents with AI-powered analysis.

The project focuses on backend architecture, asynchronous processing, authentication, infrastructure, and production deployment.

**Highlights:**

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

I'm working toward deeper expertise in **hardware and semiconductor engineering**, beginning with digital design, RTL development, FPGA systems, processor architecture, and verification.

At the same time, I'm continuing to strengthen my background in **backend and systems engineering**, particularly in distributed systems, infrastructure, databases, APIs, and reliable software architecture.

I'm especially interested in the boundary between hardware and software: how processors are designed, how low-level systems behave, and how software ultimately interacts with the hardware beneath it.

---

## Connect

[LinkedIn](https://linkedin.com/in/alexmarfoappiah) · [Email](mailto:alexmarfo509@gmail.com)
