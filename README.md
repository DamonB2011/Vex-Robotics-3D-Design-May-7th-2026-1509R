

# VEX V5RC May 7th 2026: Override Concept Bot By Team 1509R 🤖

[![Game Mode: Override](https://shields.io)](https://vexrobotics.com)
[![Platform: V5](https://shields.io)]()
[![Status: Concept/WIP (Work in Progress)](https://docs.google.com/document/d/17ZKdZGmnVa-AxawCWBdLEw7KyN8BN2ed9QluvtwbDcA/edit?tab=t.0)
(https://docs.google.com/document/d/17ZKdZGmnVa-AxawCWBdLEw7KyN8BN2ed9QluvtwbDcA/edit?tab=t.0)

A high-performance, symmetrical robot design for the 2026 VEX Robotics Competition season. This project focuses on vertical dominance via a mirrored DR4B lift and a multi-modal intake system.

---

## 🛠 Project Structure & CAD Studios

The design is modularized across several specialized Part Studios to ensure precision spacing and structural symmetry. The main Engine that is running my 3D Model is OnShape.

### 🏎️ Drivetrain (DT)
*   **Studio: `Mirrored DT` / `DT`**
    *   **Frame:** Fully symmetrical C-channel chassis for balanced weight distribution.
    *   **Wheel Configuration:** Hybrid drive utilizing **Traction Wheels** (defense/stability) and **Omni Wheels** (agility).
    *   **Gearing:** Optimized **36:60 Gear Ratio** for a competitive balance between torque and traversal speed.
    *   **Hardware:** Integrated **36t Shafts** with documented `Shaft Disassembled` views for maintenance.

### 🏗️ Lift System (DR4B)
*   **Studio: `Modified DR4B 1509R` / `Mirrored DR4B`**
    *   **Architecture:** Double Reverse Four-Bar based on the high-efficiency 1509R linkage.
    *   **Interactivity:** Developed using the `DR4B Interactive` studio to ensure a 100% linear vertical travel path.
    *   **Evolution:** Iterated from `Basic DR4B` prototypes to a final `Mirrored Side` assembly to eliminate lateral sway.

### 🏗️ Manipulator & Intake
*   **Studio: `Claw Concept` / `Roller`**
    *   **Multi-Axis Grip:** Features both **Front/Back** and **Left/Right** claw designs to handle Pins and Cups from any orientation.
    *   **Active Intake:** High-speed **Roller** system for "Touch It, Own It" game element acquisition.
    *   **Symmetry:** Fully `Mirrored Claw` assembly to maximize motor efficiency and gripping force.

---

## 📐 Engineering Optimization
This repository emphasizes precision tolerances and clearance management:

-   **`Part Studio 1`**: Central hub for final assembly and global variable management.
-   **`Spacing`**: Dedicated studio for interference checking between the DR4B arms and the internal drivetrain components.
-   **`Assembly 1`**: Final top-level assembly for motion testing and center-of-mass analysis.

## 🚀 Strategic Goals
1.  **Midfield Dominance:** Use high-traction wheels and 36:60 gearing to control the central zones.
2.  **High-Tier Stacking:** Utilize the linear DR4B reach to efficiently score on the highest goals.
3.  **Vision Alignment:** Symmetrical chassis design optimized for AI Vision Sensor mounting and AprilTag tracking.

---

## 📝 License
This design is intended for the VRC community. Please credit 1509R if you use elements of this DR4B or Claw geometry.
