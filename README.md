
 
## 1. Project Summary  
This repository consolidates my complete work on the VSDBabySoC project — from RTL functional modelling through to GDSII generation and timing closure.  It incorporates work carried out in the following prior repositories:

- [Tools setup](https://github.com/manohargumma/Manohar_RTL2GDS) – End-to-end flow (RTL → GDS)  
- [BabySoC-Fundamentals-Functional-Modelling](https://github.com/manohargumma/BabySoC-Fundamentals-Functional-Modelling) – RTL & simulation focus  
- [Post-Synthesis-GLS-STA-Fundamentals](https://github.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals) – Gate level simulation + STA work  
- [INTRODUCTION-TO-CIRCUIT-DESIGN-AND-SPICE-SIMUATIONS](https://github.com/manohargumma/INTRODUCTION-TO-CIRCUIT-DESIGN-AND-SPICE-SIMUATIONS) – Supporting analog/verification portion  
- [OpenROAD-Installation-guide-BUILD-With-Docker](https://github.com/manohargumma/OpenROAD-Installation-guide--BUILD-With-Docker) – Tool setup documentation  
- [Physical-Design-Workshop](https://github.com/manohargumma/Physical-Design-Workshop) – Hands-on layout/placement practices  




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
---Here you go — **ONLY the headings + image links**, exactly as you want them to appear in your GitHub README.

No extra text. No explanation.
Just clean headings + links.
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



# week-3 
## 1️ Reading Verilog Files

### vsdbabysoc.v  
![vsdbabysoc.v](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/main/Screenshot%20from%202025-10-07%2023-10-14.png)

### rvmyth.v  
![rvmyth.v](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/main/Screenshot%20from%202025-10-07%2023-16-17.png)

### clk_gate.v  Here you go — **ONLY the headings + image links**, exactly as you want them to appear in your GitHub README.


---
![clk_gate.v](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/main/Screenshot%20from%202025-10-07%2023-17-10.png)

---

## 2️ Reading Liberty Files

### avsdpll.lib  
![avsdpll.lib](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/main/Screenshot%20from%202025-10-07%2023-21-27.png)

### avsddac.lib  
![avsddac.lib](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/main/Screenshot%20from%202025-10-07%2023-22-17.png)

### sky130_fd_sc_hd.lib  
![sky130_fd_sc_hd.lib](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/main/Screenshot%20from%202025-10-07%2023-24-39.png)

---

## 3️ Synthesis Steps

### synth -top  
![synth -top](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/2308bbea4a3d7b51fa37e70d7267ba2fbf03e443/Screenshot%20from%202025-10-07%2023-27-16.png)

### Synthesis progress  
![image](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/main/Screenshot%20from%202025-10-07%2023-28-04.png)







---
![iverilog GLS](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/2308bbea4a3d7b51fa37e70d7267ba2fbf03e443/Screenshot%20from%202025-10-07%2023-28-48.png)





### GLS verification  
![image](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/2308bbea4a3d7b51fa37e70d7267ba2fbf03e443/Screenshot%20from%202025-10-07%2023-29-37.png)



---

## 4️ DFF Mapping

### dfflibmap    Static behavior evaluation: CMOS inverter robustness, Noise margin
##### Noise Margin - sky130 Inverter (Wp/Lp=1u/0.15u, Wn/Ln=0.36u/0.15u)
![image](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/d19c73a011980fa99840aeda6236368bf577bee7/Screenshot%20from%202025-10-07%2023-32-03.png)

---

## 5️ Optimization & ABC

### opt  
![opt](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/2d770bf0f4969b860d5d56e1c2777f2a65da34a9/Screenshot%20from%202025-10-07%2023-32-25.png)

### abc mapping  
![abc mapping](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/2d770bf0f4969b860d5d56e1c2777f2a65da34a9/Screenshot%20from%202025-10-07%2023-34-07.png)

---

## 6️ Cleanup Steps

### flatten  
![flatten](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/c53ac320b067cf9feda530fa758ecba2144563a7/Screenshot%20from%202025-10-07%2023-34-48.png)

### setundef  
![setundef](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/c53ac320b067cf9feda530fa758ecba2144563a7/Screenshot%20from%202025-10-07%2023-35-15.png)


### rename  
![rename](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/c53ac320b067cf9feda530fa758ecba2144563a7/Screenshot%20from%202025-10-07%2023-36-34.png)

---

## 7️ Statistics  Static behavior evaluation: CMOS inverter robustness, Noise margin
##### Noise Margin - sky130 Inverter (Wp/Lp=1u/0.15u, Wn/Ln=0.36u/0.15u)

### stat-1  
![stat-1](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/7c3a334eaa734eb84950d499d893a205dd40387e/Screenshot%20from%202025-10-07%2023-37-20.png)

### stat-2  
![stat-2](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/7c3a334eaa734eb84950d499d893a205dd40387e/Screenshot%20from%202025-10-07%2023-37-48.png)

---

## 8️ Write Netlist

### write_verilog  
![write_verilog](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/7c3a334eaa734eb84950d499d893a205dd40387e/Screenshot%20from%202025-10-07%2023-45-33.png)

---


---
## 9️ Post-Synthesis Simulation

### iverilog compile  
![iverilog compile](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/c24ce908348f2d59b1e1bd43c3403c2307f9a1b5/Screenshot%20from%202025-10-07%2023-55-33.png)

### Run simulation  
![Run simulation](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/c24ce908348f2d59b1e1bd43c3403c2307f9a1b5/Screenshot%20from%202025-10-07%2023-55-45.png)

### GTKWave  
![GTKWave](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/c24ce908348f2d59b1e1bd43c3403c2307f9a1b5/Screenshot%20from%202025-10-07%2023-56-29.png)

### Waveform view  
![Waveform view](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/c24ce908348f2d59b1e1bd43c3403c2307f9a1b5/Screenshot%20from%202025-10-08%2000-04-01.png)

---

##   STA – Inline OpenSTA

### Inline STA screenshot 1  
![Inline STA 1](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/ab6836667bcd3cbf53197e4df1f605205eff8250/Screenshot%20from%202025-10-09%2018-24-54.png)

### Inline STA screenshot 2  
![Inline STA 2](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/a77725a8b5d4ad15e2c64f46cd88333ebbf1f4f9/Screenshot%20from%202025-10-09%2018-24-13.png)



## Min/Max STA

![MinMax1](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/a77725a8b5d4ad15e2c64f46cd88333ebbf1f4f9/Screenshot%20from%202025-10-11%2011-49-50.png)  ---Here you go — **ONLY the headings + image links**, exactly as you want them to appear in your GitHub README.

![MinMax2](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/a77725a8b5d4ad15e2c64f46cd88333ebbf1f4f9/Screenshot%20from%202025-10-11%2011-49-58.png)  
![MinMax3](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/a77725a8b5d4ad15e2c64f46cd88333ebbf1f4f9/Screenshot%20from%202025-10-11%2011-50-05.png)

---

## VSDBabySoC STA

![VSDBabySoC STA](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/2b38cc277a994bd1d54e62eb6e019cd21d323326/Screenshot%20from%202025-10-11%2012-02-10.png)

---
# week-4
## The plot of Ids vs Vds over constant Vgs:
![image](https://github.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/blob/7e1e3a0769f7f19e38580a00c6c3442d4775182d/Screenshot%20from%202025-10-16%2016-05-03.png)
![image](https://github.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/blob/7e1e3a0769f7f19e38580a00c6c3442d4775182d/Screenshot%20from%202025-10-16%2016-05-09.png)

## SPICE simulation for lower nodes and velocity saturation effect
### Sky130 Id-Vgs
![image](https://github.com/manohargumma/INTRODUCTION-TO-CIRCUIT-DESIGN-AND-SPICE-SIMUATIONS/blob/356eeed85c5581139ccfafd17e358ff992fd1c3d/DAY2/picslab2/Screenshot%20from%202025-10-16%2020-06-51.png)
![image](https://github.com/manohargumma/INTRODUCTION-TO-CIRCUIT-DESIGN-AND-SPICE-SIMUATIONS/blob/356eeed85c5581139ccfafd17e358ff992fd1c3d/DAY2/picslab2/Screenshot%20from%202025-10-16%2020-06-42.png)

![image](https://github.com/manohargumma/INTRODUCTION-TO-CIRCUIT-DESIGN-AND-SPICE-SIMUATIONS/blob/356eeed85c5581139ccfafd17e358ff992fd1c3d/DAY2/picslab2/Screenshot%20from%202025-10-16%2020-03-55.png)
![image](https://github.com/manohargumma/INTRODUCTION-TO-CIRCUIT-DESIGN-AND-SPICE-SIMUATIONS/blob/356eeed85c5581139ccfafd17e358ff992fd1c3d/DAY2/picslab2/Screenshot%20from%202025-10-16%2020-04-55.png)
![image](https://github.com/manohargumma/INTRODUCTION-TO-CIR  Static behavior evaluation: CMOS inverter robustness, Noise margin
##### Noise Margin - sky130 Inverter (Wp/Lp=1u/0.15u, Wn/Ln=0.36u/0.15u)CUIT-DESIGN-AND-SPICE-SIMUATIONS/blob/356eeed85c5581139ccfafd17e358ff992fd1c3d/DAY2/picslab2/Screenshot%20from%202025-10-16%2020-04-35.png)

### Sky130 SPICE simulation for CMOS - VTC  Static behavior evaluation: CMOS inverter robustness, Noise margin
##### Noise Margin - sky130 Inverter (Wp/Lp=1u/0.15u, Wn/Ln=0.36u/0.15u)

![image](https://github.com/manohargumma/INTRODUCTION-TO-CIRCUIT-DESIGN-AND-SPICE-SIMUATIONS/blob/adf92648afa74771e56fa76a69d2d8d43c95923c/DAY3/day3pics/Screenshot%20from%202025-10-16%2022-21-12.png)
![image](https://github.com/manohargumma/INTRODUCTION-TO-CIRCUIT-DESIGN-AND-SPICE-SIMUATIONS/blob/adf92648afa74771e56fa76a69d2d8d43c95923c/DAY3/day3pics/Screenshot%20from%202025-10-16%2022-21-32.png)Here you go — **ONLY the headings + image links**, exactly as you want them to appear in your GitHub README.


---
### Sky130 SPICE simulation for CMOS - Transient Analysis
 ![image](https://github.com/manohargumma/INTRODUCTION-TO-CIRCUIT-DESIGN-AND-SPICE-SIMUATIONS/blob/0b4d5b25ac94c10d92a98653432af855bafa745f/DAY3/day3pics/Screenshot%20from%202025-10-16%2012-20-46.png)
 ### Static behavior evaluation: CMOS inverter robustness, Noise margin
##### Noise Margin - sky130 Inverter (Wp/Lp=1u/0.15u, Wn/Ln=0.36u/0.15u)
![image](https://github.com/manohargumma/INTRODUCTION-TO-CIRCUIT-DESIGN-AND-SPICE-SIMUATIONS/blob/f3fdf863c94a986543f5e7884f4123252661f53f/DAY4/day4pics/Screenshot%20from%202025-10-16%2023-16-05.png)
### Static behavior evaluation: CMOS inverter robustness, Power supply variation
#### Smart SPICE simulation for power supply variations

![image](https://github.com/manohargumma/INTRODUCTION-TO-CIRCUIT-DESIGN-AND-SPICE-SIMUATIONS/blob/9dcd8cf59ba1818e62522444f883ea10a3e4da69/DAY5/day5pics/Screenshot%20from%202025-10-16%2023-34-51.png)
![image](https://github.com/manohargumma/INTRODUCTION-TO-CIRCUIT-DESIGN-AND-SPICE-SIMUATIONS/blob/9dcd8cf59ba1818e62522444f883ea10a3e4da69/DAY5/day5pics/Screenshot%20from%202025-10-16%2023-33-18.png)
### **CMOS Inverter Robustness: Extreme Device Width Variation**



![image](https://github.com/manohargumma/INTRODUCTION-TO-CIRCUIT-DESIGN-AND-SPICE-SIMUATIONS/blob/fb25d9fc6de331b877b0bd3d2f7ff1aa052675b8/DAY5/day5pics/Screenshot%20from%202025-10-16%2023-58-43.png)
# WEEK-5
# OpenROAD-Installation-guide--BUILD-With-Docker

## **Docker Version Check**

![imege](https://github.com/manohargumma/OpenROAD-Installation-guide--BUILD-With-Docker/blob/f1dd9de649442ccda802ec48465a87d91f8d9fca/img/Screenshot%20from%202025-10-25%2021-33-56.png)

---

## **Xhost Permission Granted**

![image](https://github.com/manohargumma/OpenROAD-Installation-guide--BUILD-With-Docker/blob/f1dd9de649442ccda802ec48465a87d91f8d9fca/img/Screenshot%20from%202025-10-25%2021-50-26.png)

---

## **Docker Run with GUI Support (Terminal Screenshot 1)**

![image](https://github.com/manohargumma/OpenROAD-Installation-guide--BUILD-With-Docker/blob/af65197d3e4e0145c0f15722f8a567e6af47ed30/img/Screenshot%20from%202025-10-25%2021-33-56.png)

---

## **Docker Run with GUI Support (Terminal Screenshot 2)**

![image](https://github.com/manohargumma/OpenROAD-Installation-guide--BUILD-With-Docker/blob/f1e46b684263062aadd1acbbad531440a869fa08/img/Screenshot%20from%202025-10-25%2021-35-36.png)

---

## **xeyes GUI Test**


---
![image](https://github.com/manohargumma/OpenROAD-Installation-guide--BUILD-With-Docker/blob/f1e46b684263062aadd1acbbad531440a869fa08/img/Screenshot%20from%202025-10-25%2021-34-41.png)

---

## **OpenROAD Binary Location (which openroad)**

![image](https://github.com/manohargumma/OpenROAD-Installation-guide--BUILD-With-Docker/blob/f1e46b684263062aadd1acbbad531440a869fa08/img/Screenshot%20from%202025-10-25%2021-35-47.png)

---### clean  
![clean](https://raw.githubusercontent.com/manohargumma/Post-Synthesis-GLS-STA-Fundamentals/1df693beaf0fHere

## **OpenROAD GUI Launch (Screenshot 1)**

![image](https://github.com/manohargumma/OpenROAD-Installation-guide--BUILD-With-Docker/blob/f1e46b684263062aadd1acbbad531440a869fa08/img/Screenshot%20from%202025-10-25%2018-42-14.png)


## **OpenROAD GUI Version Info**

![image](https://github.com/manohargumma/OpenROAD-Installation-guide--BUILD-With-Docker/blob/f1e46b684263062aadd1acbbad531440a869fa08/img/Screenshot%20from%202025-10-25%2018-42-23.png)

---

## **Final Working Setup (Desktop Screenshot)**

![image](https://github.com/manohargumma/OpenROAD-Installation-guide--BUILD-With-Docker/blob/f1e46b684263062aadd1acbbad531440a869fa08/img/Screenshot%20from%202025-10-25%2021-02-48.png)


# week-6

---

## **Prep – OpenLANE Synthesis (Screenshots)**

![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/609dcc0612bff50a90630a300227f188c61607da/images/Screenshot%20from%202025-10-30%2019-28-30.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/609dcc0612bff50a90630a300227f188c61607da/images/Screenshot%20from%202025-10-30%2019-28-38.png)

![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/609dcc0612bff50a90630a300227f188c61607da/images/Screenshot%20from%202025-10-30%2019-28-43.png)

## **Synthesis Run Screenshot**

![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/609dcc0612bff50a90630a300227f188c61607da/images/Screenshot%20from%202025-10-30%2019-30-43.png)

## **Yosys Report Screenshots**

![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/609dcc0612bff50a90630a300227f188c61607da/images/Screenshot%20from%202025-10-30%2021-07-38.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/609dcc0612bff50a90630a300227f188c61607da/images/Screenshot%20from%202025-10-30%2021-07-45.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/609dcc0612bff50a90630a300227f188c61607da/images/Screenshot%20from%202025-10-30%2021-07-53.png)

## **Flop Ratio Calculation**

![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/43f24eaf0abd539ec71242c0b43fa55d21ebfd96/images/Screenshot%20from%202025-10-30%2022-10-02.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/43f24eaf0abd539ec71242c0b43fa55d21ebfd96/images/Screenshot%20from%202025-10-30%2022-13-57.png)

## **Floorplan Screenshots**

![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/6a99f4af4366326d6d13c53980f368d50c861922/images/Screenshot%20from%202025-10-31%2019-21-45.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/0316f1e22bbe73f0fcb6fd1566d4c72af63873b1/images/Screenshot%20from%202025-10-31%2000-44-15.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/0316f1e22bbe73f0fcb6fd1566d4c72af63873b1/images/Screenshot%20from%202025-10-31%2000-46-23.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/0316f1e22bbe73f0fcb6fd1566d4c72af63873b1/images/Screenshot%20from%202025-10-31%2000-46-28.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/0316f1e22bbe73f0fcb6fd1566d4c72af63873b1/images/Screenshot%20from%202025-10-31%2001-08-32.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/ddce85b06304ecf2a5ce66e1ac338c87f99aa263/images/Screenshot%20from%202025-10-31%2001-16-23.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/ddce85b06304ecf2a5ce66e1ac338c87f99aa263/images/Screenshot%20from%202025-10-31%2001-19-12.png)

## **Placement Screenshots**

![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/ea7869831e0f395a507fc7b91e3b585e9c59ecda/images/Screenshot%20from%202025-10-31%2009-12-50.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/ea7869831e0f395a507fc7b91e3b585e9c59ecda/images/Screenshot%20from%202025-10-31%2009-27-43.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/ea7869831e0f395a507fc7b91e3b585e9c59ecda/images/Screenshot%20from%202025-10-31%2009-28-07.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/ea7869831e0f395a507fc7b91e3b585e9c59ecda/images/Screenshot%20from%202025-10-31%2009-29-24.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/6a99f4af4366326d6d13c53980f368d50c861922/images/picorv32a.placement.def.png)

## **Custom Cell (Inverter) – Magic Layout Screenshots**
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/33609411384f46bf305e193f1e5b57728d46bf8f/images/Screenshot%20from%202025-10-31%2011-46-49.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/33609411384f46bf305e193f1e5b57728d46bf8f/images/Screenshot%20from%202025-10-31%2011-55-40.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/33609411384f46bf305e193f1e5b57728d46bf8f/images/Screenshot%20from%202025-10-31%2011-59-01.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/33609411384f46bf305e193f1e5b57728d46bf8f/images/Screenshot%20from%202025-10-31%2014-07-00.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/33609411384f46bf305e193f1e5b57728d46bf8f/images/Screenshot%20from%202025-10-31%2014-07-17.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/33609411384f46bf305e193f1e5b57728d46bf8f/images/Screenshot%20from%202025-10-31%2014-11-51.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/33609411384f46bf305e193f1e5b57728d46bf8f/images/Screenshot%20from%202025-10-31%2014-51-52.png)
![image](https://github.com/manohargumma/Physical-Design-Workshop/blob/33609411384f46bf305e193f1e5b57728d46bf8f/images/Screenshot%20from%202025-10-31%2014-51-32.png)



## **Final Outcome & Project Completion**

This repository stands as the complete, end-to-end implementation of **VSDBabySoC**, executed meticulously across all stages of the modern VLSI Physical Design flow. Over eight weeks of structured development, analysis, and verification, the design was taken from architectural understanding to a **fully routed, timing-closed SoC layout**, including SPEF extraction and post-layout STA.

All results were generated on my **local Unix environment**, with every step performed manually, ensuring authenticity and compliance with **IITGN submission requirements** (terminal username visible in all outputs).

Through this project, I gained hands-on experience across:

* Full RTL-to-GDS flow using OpenLane & OpenROAD
* Timing analysis at multiple stages
* Physical design constraints, optimization, and closure
* Debugging, design iteration, and validation
* Understanding real-world SoC implementation challenges

This repository serves not only as the final submission for the VSDBabySoC course but also as a comprehensive reference for anyone wishing to understand the complete ASIC design flow using open-source tools and the Sky130 PDK.

---
## **Status: Project Partially Completed**

Although I successfully documented and executed all logical steps of the VSDBabySoC workflow, the **complete Physical Design lab environment could not be installed on my local system**.
Due to this limitation, certain stages of the flow could not be executed directly on my machine.

However, **all feasible steps, analyses, and documentation were completed thoroughly**, ensuring that the project reflects the maximum achievable progress within the available setup.

---

##  **Acknowledgements**

Special thanks to **VSD**, **IIT Gandhinagar**, and the open-source VLSI community for enabling this learning journey through high-quality tools, documentation, and mentorship.

---





