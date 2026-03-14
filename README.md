# Advanced Helical Spring Engineering Suite

### Multi-Parameter Optimization based on Shigley's Mechanical Engineering Design

This professional engineering tool is designed to optimize helical compression springs using established mechanical principles. It bridges the gap between theoretical calculations and practical CAD automation, specifically tailored for mechanical engineers and researchers.

---

##  Key Features

* **Optimization Engine**: Automatically searches for the most mass-efficient wire diameter ($d$) and spring index ($C$) within defined safety factors.
* **Fatigue Analysis**: Real-time evaluation of fatigue safety factors using **Gerber**, **Goodman**, and **Soderberg** failure criteria.
* **3D Visualization**: Interactive 3D model rendering using **Three.js** with an option to export designs as **STL** files for 3D printing.
* **SolidWorks Automation**: Generates a dynamic **VBA Macro** that can be directly pasted into SolidWorks to automate the 3D modeling process.
* **Engineering Reports**: Generates a professional PDF report containing material properties, stress analysis, and stability diagnostics.

---

##  Technical Specifications

### Physics & Mechanics

The suite utilizes the following engineering formulations:

* **Shear Stress ($\tau$)**: Calculated with the **Wahl Factor** ($K_w$) to account for curvature and direct shear.
* **Surge Frequency**: Evaluates the natural frequency to prevent resonance during high-speed operations.
* **Stability**: Checks for buckling risks based on the slenderness ratio ($L_0/D$).

### Material Library

Includes standard engineering materials:

* Music Wire (ASTM A228)
* Hard-Drawn Steel (ASTM A227)
* Chrome-Vanadium (ASTM A232)

---

##  Tech Stack

* **Frontend**: HTML5, CSS3 (Modern UI/UX)
* **Graphics**: [Three.js](https://threejs.org/) (3D Rendering), [Chart.js](https://www.chartjs.org/) (Analytics)
* **Utilities**: [html2pdf.js](https://ekoopmans.github.io/html2pdf.js/) (Report Generation)
* **CAD Integration**: SolidWorks API (VBA)

---

##  How to Use

1. **Input Parameters**: Enter your required forces ($F_{max}, F_{min}$), deflection, and operating frequency.
2. **Run Optimization**: Click "Run Optimization Search" to find the best design.
3. **Analyze**: Review the Fatigue Failure Envelope and Engineering Diagnostics.
4. **Export**:
* Click **"Export PDF Report"** for documentation.
* Click **"Copy SolidWorks Macro"** and run it in SolidWorks to generate the model instantly.



---

## Author

**Arafat Hossain**
*Mechanical Engineering Student*
Focusing on Deep Learning, Research, and Engineering Automation.

---

> **Note**: This tool is developed following the standards of **Shigley's Mechanical Engineering Design**. Always verify results for critical applications.

---
