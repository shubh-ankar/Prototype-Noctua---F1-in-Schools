# 🦉 Prototype Noctua

Prototype Noctua is a miniature race car we designed from scratch as first-year mechanical engineering students. The goal? Build something fast, aerodynamic, lightweight — and learn as much as possible while doing it.

Through design iterations, CFD analysis, and careful prototyping, we created a car that was not just regulation-compliant, but exceeded our expectations. This project helped us translate classroom theory into real engineering decisions.

---

## 🎯 Objectives

- Minimize aerodynamic drag (target: < 0.4 drag coefficient)
- Ensure directional stability via center of mass tuning
- Maximize downforce without violating regulations
- Use lightweight materials and precise manufacturing
- Apply core mechanical engineering principles (CFD, FEA, CAM)

---

## 🛠️ Tools Used

| Tool/Software     | Purpose                          |
|------------------|----------------------------------|
| Fusion 360        | 3D CAD modeling                  |
| SimScale          | CFD & FEA simulations            |
| CNC Milling       | Chassis manufacturing            |
| 3D Printing       | Wings, wheels, tether guides     |
| Vernier Calipers  | Precision post-manufacture checks|

---

## 📐 Methodology

### 1. **Research & Design**
- Studied F1 principles, boundary layer theory, Magnus effect
- Designed ~9 iterations of the car in Fusion 360
- Focused on smooth curvature to prevent flow separation

### 2. **Simulation & Analysis**
- Used **CFD** to study drag forces and wake patterns
- Used **FEA** to analyze stress in wings and chassis
- Ensured consistent test conditions with bounding boxes in simulations

### 3. **Manufacturing**
- CNC-milled chassis to precise tolerances
- SLA 3D-printed parts in resin for low mass and smooth surface
- Sanded and primed body, then painted using a tested spray process

---

## 📸 Sample Visuals

![CAD Model](media/P11 [Final car analysis render].png)
*A render of the final car body*

![CFD Streamlines](CFD/Images/P11 [Wake Analysis-2].png)
*CFD analysis showing smooth airflow around the body*


---

## 📊 Key Outcomes

- ✅ Final drag force: **0.28** (22% below target)
- ✅ Front wing downforce increased grip by ~15%
- ✅ Center of Mass optimized for both tip-resistance and directional control
- ✅ Weight balanced at ~50g (compliant with competition rules)
- ✅ Achieved aesthetically clean finish and structurally sound assembly

---

## 📚 What We Learned

- Iteration matters — small design tweaks made big simulation differences.
- CFD setups must be precise — boundary conditions can break results.
- Structural integrity must be balanced with aerodynamic needs.
- Manufacturing constraints (like drill bit sizes) affect CAD freedom.
- Documentation and teamwork were as important as the design.

---

## 📂 Folder Structure

Prototype-Noctua/
├── CAD/ # STL files for all components
├── CFD/
│ ├── images/ # Simulation screenshots
├── docs/ # Full report, presentations, etc.
├── media/ # Renders used in this README
└── README.md # You're reading it!

---

## ✨ About the Name

**Noctua** is Latin for Owl, inspired by *Athene Noctua* — the Owl of Minerva, symbol of wisdom. Like the owl, we gained insight only after deep exploration and testing. Prototype Noctua is a reflection of that growth.

---

> *"Wisdom arrives only with dusk."* — G.W.F. Hegel

---

🚀 Thanks for checking out our project! Feedback is always welcome.
