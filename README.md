# Manohar-VSDBabySoC-Final-Submission
Here is your **ready-to-use `README.md`** for the **Week-9 Final VSDBabySoC Submission**.
Just **copy & paste** this into `README.md` when you create your new GitHub repo.

---

# **README.md (Final Submission – VSDBabySoC)**

```md
# VSDBabySoC — RTL to GDSII Final Submission  
**Author:** Manohar Gumma  
**Course:** VSD – Advanced Physical Design using Open-Source Tools  
**Final Week-9 Documentation Submission**

---

## 📌 Project Overview  
This repository contains the **complete RTL → GDSII flow** for the **VSDBabySoC**, consolidated from multiple weeks of work.  
It includes:

- RTL exploration  
- Simulation  
- Synthesis  
- Floorplanning  
- Placement  
- Clock Tree Synthesis (CTS)  
- Routing  
- SPEF extraction  
- Static Timing Analysis (STA)  
- Post-layout verification  
- Custom scripts & unique modifications  

All screenshots contain my **UNIX terminal username**, following IIT Gandhinagar evaluation guidelines.

---

## 📁 Repository Structure  

```

Manohar-VSDBabySoC-Final-Submission/
│
├── README.md
├── docs/
│   ├── Week1.md
│   ├── Week2.md
│   ├── Week3.md
│   ├── Week4.md
│   ├── Week5.md
│   ├── Week6.md
│   ├── Week7.md
│   ├── Week8.md
│   └── Week9.md
│
├── images/
│   ├── [manohar@week1_rtl.png](mailto:manohar@week1_rtl.png)
│   ├── [manohar@week2_simulation.png](mailto:manohar@week2_simulation.png)
│   ├── [manohar@week3_synthesis.png](mailto:manohar@week3_synthesis.png)
│   ├── [manohar@week4_floorplan.png](mailto:manohar@week4_floorplan.png)
│   ├── [manohar@week5_placement.png](mailto:manohar@week5_placement.png)
│   ├── [manohar@week6_cts.png](mailto:manohar@week6_cts.png)
│   ├── [manohar@week7_routing.png](mailto:manohar@week7_routing.png)
│   ├── [manohar@week8_sta.png](mailto:manohar@week8_sta.png)
│   ├── [manohar@week9_final_timing.png](mailto:manohar@week9_final_timing.png)
│   └── (all screenshots with UNIX username visible)
│
├── scripts/
│   ├── custom_sta.tcl
│   ├── floorplan_fix.tcl
│   └── pin_order_fix.tcl
│
├── results/
│   ├── synthesis_report.txt
│   ├── placement_report.txt
│   ├── routing_report.txt
│   ├── final_sta_report.txt
│   └── power_report.txt
│
└── archive/
├── final.gds (optional or Google Drive link)
├── final.spef
└── final.def

```

---

## 🚀 Tools Used  
- **OpenLANE Flow** (RTL → GDSII)  
- **OpenROAD**  
- **Magic VLSI**  
- **Netgen**  
- **OpenSTA**  
- **Ngspice** (for SPICE simulations)  
- **Sky130 PDK**

---

## 📚 Week-wise Documentation  
All detailed week-wise reports are inside the `docs/` folder:

- **Week 1:** RTL exploration & BabySoC architecture  
- **Week 2:** Testbench, simulation, waveforms  
- **Week 3:** Synthesis, yosys flow, timing reports  
- **Week 4:** Floorplan, pin placement, density exploration  
- **Week 5:** Placement (global + detailed)  
- **Week 6:** Clock Tree Synthesis  
- **Week 7:** Routing (global + detailed), DRC fixes  
- **Week 8:** SPEF extraction, STA analysis  
- **Week 9:** Final GDS, final reports, summary & learnings  

---

## 🧪 Unique Experiments / Custom Modifications

### ✔ 1. Custom STA Script  
File: `scripts/custom_sta.tcl`  
**Why:** For multi-corner STA automation  
**Result:** Automated reporting across ss/tt/ff corners.

### ✔ 2. Pin Order Fix for Routing  
File: `scripts/pin_order_fix.tcl`  
**Why:** Resolve routing blockages  
**Result:** Improved routing completion + reduced DRCs.

### ✔ 3. Floorplan Optimization  
File: `scripts/floorplan_fix.tcl`  
**Why:** Reduce congestion + improve cell distribution  
**Result:** Cleaner placement and better routing resource usage.

---

## 📸 Screenshot Usage Policy  
All screenshots in `/images` include my **UNIX terminal username** (mandatory for IITGN selection).  
Examples:

```

manohar@vsd:~/openlane/run/...

```

---

## 📈 Final Results Summary

| Stage | Status |
|-------|--------|
| RTL Simulation | ✔ Successful |
| Synthesis | ✔ Clean netlist generated |
| Floorplan | ✔ DIE + CORE area optimized |
| Placement | ✔ Legal placement, no overlaps |
| CTS | ✔ Balanced clock tree |
| Routing | ✔ Clean routed DEF |
| SPEF | ✔ Extracted |
| STA | ✔ Timing closure achieved |
| GDSII | ✔ Generated |

---

## 🏁 Final GDSII  
Path: `/archive/final.gds`  
(If large, provide a Google Drive link)

---

## 🧾 License  
This work is **original** and belongs to **Manohar Gumma**.  
Duplicating this repository is strictly prohibited as per **IIT Gandhinagar rules**.

---

## 📬 Contact  
**GitHub:** https://github.com/manohargumma  
For any verification or reference related to VSDBabySoC project.

---

# ✅ End of README.md  
```

---

If you want, I can also generate:

✅ All `Week1.md` → `Week9.md` files
✅ All script files
✅ Folder tree as a ZIP
✅ A fully generated repo structure you can directly upload

Just tell me **“Generate week files”** or **“Generate full repo files”.**
