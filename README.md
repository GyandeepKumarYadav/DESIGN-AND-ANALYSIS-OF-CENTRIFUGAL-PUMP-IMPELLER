
# Design and Analysis of a Centrifugal Pump Impeller

## 📌 Overview

This project focuses on the **design, modeling, and structural analysis** of a **semi-open type centrifugal pump impeller**, a critical component used for fluid transfer applications. The aim is to design an efficient impeller, perform mechanical analysis, and recommend an optimal material based on performance metrics.

## 🔧 Tools & Technologies

* **CAD Software:** Autodesk Fusion 360
* **Simulation Tool:** ANSYS Student 2021 R1
* **Additional Simulation:** SolidWorks 2020
* **Material Comparison:** Grey Cast Iron vs. Glass Fiber Reinforced Plastic (GFRP)

## ⚙️ Design Specifications

| Parameter         | Value    |
| ----------------- | -------- |
| Head              | 24 m     |
| Discharge         | 95 LPM   |
| Speed             | 2880 RPM |
| Shaft Diameter    | 25 mm    |
| Impeller Diameter | 144 mm   |
| No. of Blades     | 4        |

## 📊 Analysis Summary

### Structural Analysis Results

| Material       | Max Stress (MPa) | Deformation (mm) | Mass (kg) |
| -------------- | ---------------- | ---------------- | --------- |
| Grey Cast Iron | 5.43             | 0.00156          | 0.7146    |
| GFRP           | 1.87             | 0.00051          | 0.1935    |

### Modal Analysis Results (Natural Frequencies - Hz)

| Mode | Grey Cast Iron | GFRP   |
| ---- | -------------- | ------ |
| 1    | 3390           | 5834   |
| 2    | 3468.2         | 6009.8 |
| 3    | 3478.2         | 6026.4 |
| 4    | 3689.8         | 6412.2 |
| 5    | 4297.6         | 7752   |
| 6    | 4300.9         | 7758.8 |

## ✅ Key Findings

* **GFRP outperformed Grey Cast Iron** in all mechanical metrics: stress, deformation, and natural frequency.
* **Weight reduction** was significant with GFRP (approx. 72% lighter), enhancing pump efficiency.
* GFRP demonstrated **higher stiffness and lower resonance risk**, making it ideal for high-speed applications.

## 📈 Future Scope

* Perform **CFD analysis** to assess fluid flow performance.
* Experiment with **different blade numbers** and impeller types (semi-closed, closed).
* Scale design for **industrial-level pump systems** and validate performance through prototype testing.

## 📁 Repository Structure

```
├── README.md
├── Design/
│   └── Fusion360_CAD_Model.f3d
├── Analysis/
│   └── ANSYS_Results/
│       ├── Structural/
│       └── Modal/
├── Report/
│   └── Design_and_Analysis_of_Centrifugal_Pump.pdf
└── Images/
    └── Views, Mesh, Stress Plots, etc.
```

## 👨‍💻 Authors

* \GYANDEEP KUMAR YADAV
* Department of Mechanical Engineering
* \UIET PANJAB UNIVERSITY





