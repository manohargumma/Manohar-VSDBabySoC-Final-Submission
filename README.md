# Manohar-VSDBabySoC-Final-Submission

# VSDBabySoC – Complete RTL-to-GDSII Journey  
**Author:** Manohar Gumma  
**GitHub:** https://github.com/manohargumma   
**Course/Project:** VSD – Advanced Physical Design Flow  
**Submission:** Week 9 – Final Documentation  

---
 
## 1. Project Summary  
This repository consolidates my complete work on the VSDBabySoC project — from RTL functional modelling through to GDSII generation and timing closure.  It incorporates work carried out in the following prior repositories:

- [Tools setup](https://github.com/manohargumma/Manohar_RTL2GDS) – End-to-end flow (RTL → GDS)  
- [BabySoC-Fundamentals-Functional-Modelling](https://github.com/manohargumma/BabySoC-Fundamentals-Functional-Modelling) – RTL & simulation focus  
- [Post-Synthesis-GLS-STA-Fundamentals](https://github.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals) – Gate level simulation + STA work  
- [INTRODUCTION-TO-CIRCUIT-DESIGN-AND-SPICE-SIMUATIONS](https://github.com/manohargumma/INTRODUCTION-TO-CIRCUIT-DESIGN-AND-SPICE-SIMUATIONS) – Supporting analog/verification portion  
- [OpenROAD-Installation-guide-BUILD-With-Docker](https://github.com/manohargumma/OpenROAD-Installation-guide--BUILD-With-Docker) – Tool setup documentation  
- [Physical-Design-Workshop](https://github.com/manohargumma/Physical-Design-Workshop) – Hands-on layout/placement practices  


Got it — you want the **images to be visible directly in the README**, not just links.

Here is the **markdown version with images displayed**, using your exact image URLs.

You can **copy–paste this directly into README.md** and GitHub will show all images.

---

#  **Tool Installation **

## **1. Yosys Installation**

![yosys](https://i.ibb.co/BHrLYbSv/Screenshot-from-2025-09-19-22-01-43.png)

---

## **2. Icarus Verilog Installation**

![iverilog](https://i.ibb.co/YTKYkBTX/Screenshot-from-2025-09-19-22-22-25.png)

---

## **3. GTKWave Installation**

![gtkwave](https://i.ibb.co/Xx35s7Sv/Screenshot-from-2025-09-19-22-28-02.png)

---

## **4. OpenTimer Installation**

![opentimer](https://i.ibb.co/21xRfkQ2/Screenshot-from-2025-09-19-22-41-46.png)

---

## **5. Ngspice Installation**

![ngspice](https://i.ibb.co/673CjR9K/Screenshot-from-2025-09-19-22-45-25.png)

---

## **6. Magic VLSI Installation**

![magic](https://i.ibb.co/Rk3G7Vxy/Screenshot-from-2025-09-19-22-54-03.png)

---

## **7. Docker & Tool Versions Check**

![docker-check](https://i.ibb.co/HLHVj20z/Screenshot-from-2025-09-20-16-25-11.png)

---

## **8. OpenLane + PDK Setup**

### **8.1 CIEL Remote PDK List**

![ciel-list-remote](https://i.ibb.co/9HhJJYqr/Screenshot-from-2025-09-20-18-32-29.png)

### **8.2 CIEL PDK Enable**

![ciel-enable](https://i.ibb.co/LdMnc6mF/Screenshot-from-2025-09-20-18-35-10.png)

### **8.3 OpenLane Test**

![openlane-test](https://i.ibb.co/WN9f0ZhX/Screenshot-from-2025-09-20-18-52-06.png)


# Week-2 


## **1. OpenLane + PDK Setup**

![img](https://i.ibb.co/dsK8PM3g/Screenshot-from-2025-10-03-18-49-27.png)

---

## **2. Design Preparation**

![img](https://i.ibb.co/Mkn1fvRt/Screenshot-from-2025-10-04-19-56-41.png)

---

## **3. Synthesis**

![img](https://i.ibb.co/208FSvYq/Screenshot-from-2025-10-04-20-02-14.png)

---

## **4. Floorplan**
Copy-paste directly into your `README.md`.

---

![img](https://i.ibb.co/RGx2DT45/Screenshot-from-2025-10-03-19-58-53.png)

---

## **5. Placement**

![img](https://i.ibb.co/xqx332CH/Screenshot-from-2025-10-03-20-56-07.png)

---

# Week-3 — Post-Synthesis GLS & STA — VSDBabySoC

![Tool-Yosys](https://img.shields.io/badge/Tool-Yosys-blue)
![Simulator-Icarus_Verilog](https://img.shields.io/badge/Simulator-Icarus_Verilog-orange)
![Analyzer-OpenSTA](https://img.shields.io/badge/Analyzer-OpenSTA-green)
![Library-sky130_fd_sc_hd](https://img.shields.io/badge/Library-sky130_fd_sc_hd-yellow)
![Platform-Linux](https://img.shields.io/badge/Platform-Linux-lightgrey)

---

# 1️⃣ Reading Verilog Files

### vsdbabysoc.v  
![vsdbabysoc.v](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/main/Screenshot%20from%202025-10-07%2023-10-14.png)

### rvmyth.v  
![rvmyth.v](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/main/Screenshot%20from%202025-10-07%2023-16-17.png)

### clk_gate.v  
![clk_gate.v](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/main/Screenshot%20from%202025-10-07%2023-17-10.png)

---

# 2️⃣ Reading Liberty Files

### avsdpll.lib  
![avsdpll.lib](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/main/Screenshot%20from%202025-10-07%2023-21-27.png)

### avsddac.lib  
![avsddac.lib](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/main/Screenshot%20from%202025-10-07%2023-22-17.png)

### sky130_fd_sc_hd.lib  
![sky130_fd_sc_hd.lib](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/main/Screenshot%20from%202025-10-07%2023-24-39.png)

---

# 3️⃣ Synthesis Steps

### synth -top  
![synth -top](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/2308bbea4a3d7b51fa37e70d7267ba2fbf03e443/Screenshot%20from%202025-10-07%2023-27-16.png)

### Synthesis progress  
![Synthesis progress](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/main/Screenshot%20from%202025-10-07%2023-28-04.png)

### Netlist generation  
![Netlist generation](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/2308bbea4a3d7b51fa37e70d7267ba2fbf03e443/Screenshot%20from%202025-10-07%2023-28-31.png)

### iverilog GLS  
![iverilog GLS](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/2308bbea4a3d7b51fa37e70d7267ba2fbf03e443/Screenshot%20from%202025-10-07%2023-28-48.png)

### GLS simulation output  
![GLS simulation output](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/2308bbea4a3d7b51fa37e70d7267ba2fbf03e443/Screenshot%20from%202025-10-07%2023-29-26.png)

### GLS verification  
![GLS verification](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/2308bbea4a3d7b51fa37e70d7267ba2fbf03e443/Screenshot%20from%202025-10-07%2023-29-37.png)

---

# 4️⃣ DFF Mapping

### dfflibmap  
![dfflibmap](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/d19c73a011980fa99840aeda6236368bf577bee7/Screenshot%20from%202025-10-07%2023-32-03.png)

---

# 5️⃣ Optimization & ABC

### opt  
![opt](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/2d770bf0f4969b860d5d56e1c2777f2a65da34a9/Screenshot%20from%202025-10-07%2023-32-25.png)

### abc mapping  
![abc mapping](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/2d770bf0f4969b860d5d56e1c2777f2a65da34a9/Screenshot%20from%202025-10-07%2023-34-07.png)

---

# 6️⃣ Cleanup Steps

### flatten  
![flatten](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/c53ac320b067cf9feda530fa758ecba2144563a7/Screenshot%20from%202025-10-07%2023-34-48.png)

### setundef  
![setundef](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/c53ac320b067cf9feda530fa758ecba2144563a7/Screenshot%20from%202025-10-07%2023-35-15.png)

### clean  
![clean](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/1df693beaf0f37367cb27a36cbf1a022b82c2001/Screenshot%20from%202025-10-07%2023-35-40.png)

### rename  
![rename](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/c53ac320b067cf9feda530fa758ecba2144563a7/Screenshot%20from%202025-10-07%2023-36-34.png)

---

# 7️⃣ Statistics

### stat-1  
![stat-1](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/7c3a334eaa734eb84950d499d893a205dd40387e/Screenshot%20from%202025-10-07%2023-37-20.png)

### stat-2  
![stat-2](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/7c3a334eaa734eb84950d499d893a205dd40387e/Screenshot%20from%202025-10-07%2023-37-48.png)

---

# 8️⃣ Write Netlist

### write_verilog  
![write_verilog](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/7c3a334eaa734eb84950d499d893a205dd40387e/Screenshot%20from%202025-10-07%2023-45-33.png)

---

# 9️⃣ Post-Synthesis Simulation

### iverilog compile  
![iverilog compile](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/c24ce908348f2d59b1e1bd43c3403c2307f9a1b5/Screenshot%20from%202025-10-07%2023-55-33.png)

### Run simulation  
![Run simulation](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/c24ce908348f2d59b1e1bd43c3403c2307f9a1b5/Screenshot%20from%202025-10-07%2023-55-45.png)

### GTKWave  
![GTKWave](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/c24ce908348f2d59b1e1bd43c3403c2307f9a1b5/Screenshot%20from%202025-10-07%2023-56-29.png)

### Waveform view  
![Waveform view](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/c24ce908348f2d59b1e1bd43c3403c2307f9a1b5/Screenshot%20from%202025-10-08%2000-04-01.png)

---

# 🔟 STA – Inline OpenSTA

### Inline STA screenshot 1  
![Inline STA 1](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/ab6836667bcd3cbf53197e4df1f605205eff8250/Screenshot%20from%202025-10-09%2018-24-54.png)

### Inline STA screenshot 2  
![Inline STA 2](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/a77725a8b5d4ad15e2c64f46cd88333ebbf1f4f9/Screenshot%20from%202025-10-09%2018-24-13.png)

---

# 1️⃣1️⃣ Min/Max STA

![MinMax1](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/a77725a8b5d4ad15e2c64f46cd88333ebbf1f4f9/Screenshot%20from%202025-10-11%2011-49-50.png)  
![MinMax2](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/a77725a8b5d4ad15e2c64f46cd88333ebbf1f4f9/Screenshot%20from%202025-10-11%2011-49-58.png)  
![MinMax3](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/a77725a8b5d4ad15e2c64f46cd88333ebbf1f4f9/Screenshot%20from%202025-10-11%2011-50-05.png)

---

# 1️⃣2️⃣ VSDBabySoC STA

![VSDBabySoC STA](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/2b38cc277a994bd1d54e62eb6e019cd21d323326/Screenshot%20from%202025-10-11%2012-02-10.png)

---
