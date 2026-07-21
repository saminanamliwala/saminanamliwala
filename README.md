<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=2F81F7&center=true&vCenter=true&width=700&lines=Hi+%F0%9F%91%8B+I'm+Samina+Attarwala;Design+Verification+Engineer;SystemVerilog+%7C+UVM+%7C+AXI+%7C+SPI;5%2B+Years+in+FPGA%2FASIC+Verification" alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Samina%20Attarwala-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samina-attarwala-6691b6212)
[![Email](https://img.shields.io/badge/Email-attarwalasamina1212%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:attarwalasamina1212@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-saminanamliwala-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/saminanamliwala)

</div>

---

## 👩‍💻 About Me

I'm a **Design Verification Engineer** with **5+ years** of experience building functional verification environments for **FPGA/ASIC** designs using **SystemVerilog and UVM**.

- 🛩️ Domain expertise in **Avionics** and **Embedded Control Systems** (safety-critical)
- 🔌 Hands-on with **AXI** and **SPI** interface protocol verification
- ✅ Experienced in **coverage closure**, **RTL debugging**, and **regression analysis**
- 🏆 Employee of the Quarter — Alpha Numero (July 2023)
- 🎯 Currently deepening expertise in **AXI4-Lite**, **UVM RAL**, and **CDC verification**

---

## 🛠️ Tech Stack

**Languages & Methodology**

![SystemVerilog](https://img.shields.io/badge/SystemVerilog-FF6B35?style=for-the-badge&logoColor=white)
![UVM](https://img.shields.io/badge/UVM%201.2-4CAF50?style=for-the-badge&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-5C6BC0?style=for-the-badge&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Protocols**

![AXI](https://img.shields.io/badge/AXI4--Lite-FF4081?style=for-the-badge&logoColor=white)
![AXI3](https://img.shields.io/badge/AXI3-E91E63?style=for-the-badge&logoColor=white)
![SPI](https://img.shields.io/badge/SPI-9C27B0?style=for-the-badge&logoColor=white)

**Tools & OS**

![QuestaSim](https://img.shields.io/badge/QuestaSim-00BCD4?style=for-the-badge&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![IBM DOORs](https://img.shields.io/badge/IBM%20DOORs-052FAD?style=for-the-badge&logo=ibm&logoColor=white)

---

## 🚀 Featured Projects

### 🔷 [AXI4-Lite Slave — UVM Verification Environment](https://github.com/saminanamliwala/axi4lite-uvm-tb)

> Full UVM 1.2 TB for an AXI4-Lite slave register file with mixed-access register types

![SystemVerilog](https://img.shields.io/badge/-SystemVerilog-FF6B35?style=flat-square)
![UVM](https://img.shields.io/badge/-UVM%201.2-4CAF50?style=flat-square)
![AXI4-Lite](https://img.shields.io/badge/-AXI4--Lite-FF4081?style=flat-square)
![Xcelium](https://img.shields.io/badge/-Cadence%20Xcelium-purple?style=flat-square)

- Shadow register **predictor** for automated scoreboard checking — no hardcoded expected values
- **WSTRB byte-lane masking** — each byte updated independently via `signal[i*8 +: 8]`
- Mixed register types: R/W, Read-Only (returns `0xDEADBEEF`), Write-Only (`SLVERR` on read)
- AW + W channels driven **simultaneously** per AXI4-Lite spec
- `uvm_config_db` VIF distribution | `analysis_port` Monitor→Scoreboard connectivity

---

### 🛩️ Avionics *(Industry Project)*

> System-level FPGA verification for an avionics Remote Electronic Unit

![SystemVerilog](https://img.shields.io/badge/-SystemVerilog-FF6B35?style=flat-square)
![UVM](https://img.shields.io/badge/-UVM-4CAF50?style=flat-square)
![Avionics](https://img.shields.io/badge/-Avionics-37474F?style=flat-square)

- UVM sequences for stimulus generation aligned with system design requirements
- Checkers for correctness validation across all test scenarios
- Regression execution, RTL failure debugging, and functional coverage closure

---

### 🎯 Positional Sensors *(Industry Project)*

> Verification of fixed-point arithmetic for avionics sensor interface designs

![SystemVerilog](https://img.shields.io/badge/-SystemVerilog-FF6B35?style=flat-square)
![UVM](https://img.shields.io/badge/-UVM-4CAF50?style=flat-square)
![Fixed-Point](https://img.shields.io/badge/-Fixed--Point%20Arithmetic-607D8B?style=flat-square)

- Fixed-point arithmetic verification: min/max values, overflow/underflow conditions
- Contributed to internal **mathematical block VIPs**
- Collaborated with clients to debug failures → led to refined design requirements

---

### 🔌 Protocol Verification — AXI3 & SPI 

> UVM environments for AXI3 and SPI protocol verification

- AXI3: Monitor, Scoreboard, functional coverage models for all 5 channel interactions
- SPI: Full UVM env — Driver, Monitor, Scoreboard; achieved functional + code coverage closure

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=saminanamliwala&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=saminanamliwala&layout=compact&theme=tokyonight&hide_border=true" />

</div>

---

## 🏆 Achievements

| Award | Organization | Year |
|-------|-------------|------|
| 🥇 Employee of the Quarter | Alpha Numero Technology Solutions | July 2023 |
| 🥈 Employee of the Month | Alpha Numero Technology Solutions | Nov 2022 |
| ✅ Selected — Verification Engineer | Eximus (Wipro) | — |

---

## 📚 Education

**B.E. — Electronics & Communication Engineering** | CGPA: 8.6/10  
Government Engineering College, Gandhinagar | 2016 – 2020  
*A+ in Digital Electronics | A+ in Control Systems*

---

<div align="center">

*"Verification is not just finding bugs — it's building confidence that a design is correct."*

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=saminanamliwala.saminanamliwala)

</div>
