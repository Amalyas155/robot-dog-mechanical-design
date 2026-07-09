#  Robot Dog – Initial Mechanical Design

## Overview

This project presents the initial mechanical design of a simple quadruped robot (Robot Dog). The robot is designed to perform basic walking and jumping while maintaining stability through a lightweight and compact mechanical structure.

---

#  Concept Sketch

The following sketch illustrates the initial concept of the robot before creating the 3D model.

<img width="1149" height="1369" alt="ce4b2dd8-33b1-4aa6-80c6-43ebf7538bf2" src="https://github.com/user-attachments/assets/c1bae595-9f80-43cc-8bb1-facaaaf0c344" />


---

#  3D Design

The robot was modeled using **Tinkercad**. The design consists of a simple rectangular body with four identical legs connected through revolute joints.

<img width="910" height="611" alt="Screenshot 2026-07-09 215110" src="https://github.com/user-attachments/assets/59d5a915-c14f-4c3b-b111-81aca22d613d" />


---

# 1. Body and Chassis

The robot features a lightweight rectangular chassis with a hollow structure to accommodate electronic components such as the battery and controller. The simple body design reduces weight while improving structural stability.

---

# 2. Leg Design

The robot has four identical legs. Each leg consists of two rigid links connected by two revolute joints (Hip and Knee). This configuration allows the robot to perform walking and basic jumping movements while maintaining a simple mechanical design.

---

# 3. Number of Joints & Degrees of Freedom (DOF)

Each leg contains:

- Hip Joint → 1 DOF
- Knee Joint → 1 DOF

Total:

- 4 Legs
- 8 Joints
- 8 Degrees of Freedom (8 DOF)

This configuration provides sufficient flexibility while keeping the design simple.

---

# 4. Motor Selection

The robot uses **MG996R Servo Motors** due to their high torque, durability, and ease of control.

**Specifications**
- Metal Gear Servo
- High Torque
- Operating Voltage: 6–7.4 V
- Suitable for lightweight quadruped robots

---

# 5. Initial Torque Calculation

Assumptions:

- Robot weight = 2 kg
- Load on one leg = 0.5 kg
- Leg length = 0.13 m

Force:

F = m × g

F = 0.5 × 9.81 = 4.905 N

Torque:

τ = F × L

τ = 4.905 × 0.13 ≈ **0.64 N·m**

The selected servo motor can provide sufficient torque for the proposed design.

---

# 6. Stability & Center of Gravity

The center of gravity is positioned near the middle of the robot body to ensure better balance. The four-leg configuration distributes the load evenly, improving stability during standing, walking, and jumping.

---

# 7. Proposed Gait

The robot uses a **Trot Gait** for walking, where diagonal legs move together to provide stability and efficient motion.

For jumping, all four legs bend simultaneously before extending together to generate an upward force.

---

# 8. Expected Mechanical Problems

Possible challenges include:

- Joint wear
- Foot slippage
- High landing impact
- High power consumption
- Servo motor overheating
- Possible failure of 3D-printed components

---

#  Software

- Tinkercad
- GitHub

---

#  Author


**Amal Yasser**

