<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&pause=1200&color=61AFEF&center=true&vCenter=true&width=700&lines=Digital+Design+%26+Verification;SystemVerilog+%7C+UVM+%7C+RTL;Coverage+Models%2C+Hand-Coded+from+Scratch" alt="Typing SVG" />
</div>

<h1 align="center">Atanu Mondal</h1>
<h3 align="center">Electronics Engineering Student • VLSI Design & Verification</h3>

<p align="center">
  <a href="https://linkedin.com/in/atanu-mondal7"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://mail.google.com/mail/?view=cm&fs=1&to=2007atanu.mondal@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

---

### 🔭 About Me

- 🎓 B.Tech Electronics (VLSI Design & Technology) Student
- 🌱 Developing expertise in **UVM**, **SystemVerilog Assertions (SVA)** while learning advanced protocol-level verification 
- 🛠️ Built mailbox-connected class-based testbenches (generator, driver, monitor, scoreboard); now rebuilding them as reusable Verification IP with **UVM** and **TLM ports**
- 💬 Open to technical discussion on digital logic design, object-oriented verification environments, and Python-based EDA automation

---

### 🧰 Tech Stack

**Languages & Methodologies**

![SystemVerilog](https://img.shields.io/badge/SystemVerilog-4B0082?style=for-the-badge)
![UVM](https://img.shields.io/badge/UVM-8A2BE2?style=for-the-badge)
![Verilog](https://img.shields.io/badge/Verilog-1E90FF?style=for-the-badge)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**EDA & Simulation Tools**

![Questa](https://img.shields.io/badge/Siemens_Questa-009999?style=for-the-badge&logo=siemens&logoColor=white)
![Icarus Verilog](https://img.shields.io/badge/Icarus_Verilog-333333?style=for-the-badge)
![GTKWave](https://img.shields.io/badge/GTKWave-4CAF50?style=for-the-badge)
![Quartus](https://img.shields.io/badge/Quartus_Prime-0071C5?style=for-the-badge&logo=intel&logoColor=white)

**Workflow**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux%2FWSL-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

### ⚙️ Featured Projects

**[UART Controller + UVM Testbench](https://github.com/atanumondal7/UART)**

Full RTL for a UART controller (TX/RX/top-level) in SystemVerilog, verified with an industry-standard UVM verification environment — `uvm_config_db`, TLM analysis ports, sequences, scoreboard-based data integrity checks. 

- **Baud-rate mismatch:** Handles baud-rate mismatch analytically rather than assuming a perfect divider. See [README](https://github.com/atanumondal7/UART/blob/main/README.md) for the ~0.46% timing margin calculation.
- **16x oversampling with mid-bit resampling:** Chosen over a simpler edge-triggered start. It costs more logic, but rejects line glitches and keeps sampling centered even with the ~0.46% baud mismatch.
- **Result:** Simulated in Questa with zero scoreboard mismatches and 100% of the manually coded coverage bins hit.

<img src="https://raw.githubusercontent.com/atanumondal7/UART/main/docs/uart_waveform.gif" />

`SystemVerilog` `UVM` `Questa` `Git`

---

**[SystemVerilog DV Workspace](https://github.com/atanumondal7/SystemVerilog-Workspace)**

Progressive collection of Verilog and SystemVerilog designs, from gate-level blocks to class-based, coverage-driven verification environments. Each project pairs a DUT with a self-checking testbench.

- **Design range:** Adders, 4-bit ALU, Priority Encoder, Decoder, FIFO Buffer and a Universal Shift Register
- **Verification progression:** Started with directed stimulus and `$monitor` statements, then moved to a coverage-driven ALU testbench (constrained-random stimulus, class-based scoreboard), and reworked that into a layered UVM-style architecture of generator, driver, monitor, scoreboard, and coverage, connected through virtual interfaces and mailboxes.
- **Tool progression:** The `basics/` directory holds my first Verilog code, simulated in Icarus Verilog and GTKWave. The later class-based and coverage-driven accordingly to Aldec Riviera and then Questa.
- **Debugging highlight:** On the Universal Shift Register, I traced a 2-cycle sampling offset between the monitor and the DUT. Fixed it by edge-priming the monitor and a 2-stage input history buffer, reaching 100% functional coverage.

`Verilog` `SystemVerilog` `Icarus Verilog` `GTKWave` `Questa` `Git`

---

<table>
<tr>
<td>

Each project pushes the verification methodology further — the [SystemVerilog DV Workspace](https://github.com/atanumondal7/SystemVerilog-Workspace) built the OOP/class-based foundation, and [UART](https://github.com/atanumondal7/UART) applies it against real protocol timing with a manually coded coverage model where the standard flow wasn't available.

</td>
</tr>
</table>

---

### 📊 GitHub Stats

<div align="center">
<img height="165" src="https://github-readme-stats-cy3c0c0e7-cyborgs-34b4.vercel.app/api?username=atanumondal7&show_icons=true&theme=nord&hide_border=true"/>
<img height="165" src="https://github-readme-stats-cy3c0c0e7-cyborgs-34b4.vercel.app/api/top-langs/?username=atanumondal7&layout=compact&theme=nord&hide_border=true"/>
</div>

<div align="center">
<img src="https://streak-stats.demolab.com?user=atanumondal7&theme=nord&hide_border=true"/>
</div>
