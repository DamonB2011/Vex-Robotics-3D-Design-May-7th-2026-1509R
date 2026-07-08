

# VEX V5RC May 7th 2026: Override Concept Bot By Team 1509R 🤖 (Third link has my 3D models as of May 7th 2026)

[![Game Mode: Override](https://shields.io)](https://vexrobotics.com)
[![Platform: V5](https://shields.io)](https://www.vexrobotics.com/v5?___store=vexroboticseu&___from_store=vexrobotics&srsltid=AfmBOoqiGvIiCY4PqpkoBhdZmyuRsv4nirsKSBZtGMfOeJtA4jTMdO6H)
[![Status: Concept/WIP](https://shields.io)](https://docs.google.com/document/d/17ZKdZGmnVa-AxawCWBdLEw7KyN8BN2ed9QluvtwbDcA/edit?usp=sharing)

This is my robot designed for the 2026 VEX Robotics Competition. The robot has a mirrored DR4B lift for vertical domination, and an adaptive intake to respond to the multiple game elements presented in the game.

---

## Project Structure and CAD Studios

The robot is broken up into individual Part Studios to ensure correct spacing and a perfectly mirrored design. I'm using OnShape for all of my CAD work.

### Drivetrain (DT)

- **Studio:** Mirrored DT / DT
- **Frame:** Perfectly symmetrical C-channel structure, evenly distributing weight.
- **Wheel Setup:** Hybrid drivetrain setup for a good blend of defense and offense (traction wheels for drive/defense, omni wheels for maneuvering).
- **Gearing:** A calculated 36:60 gear ratio is implemented to allow for a decent speed and torque balance.
- **Hardware:** Standard 36t shafts used, with shaft disassembled states clearly defined for ease of maintenance.

### Lift System (DR4B)

- **Studio:** Modified DR4B 1509R / Mirrored DR4B
- **Design:** Highly adapted version of 1509R's ultra-efficient Double Reverse Four-Bar lift.
- **Interactivity:** The DR4B Interactive studio is utilized for the DR4B mechanism to ensure a 100% vertical lift that doesn't swing.
- **Evolution:** Moved from basic DR4B prototypes to this mirrored side design to ensure no lateral movement.

### Manipulator & Intake

- **Studio:** Claw Concept / Roller
- **Grip:** Multi-axis grip that allows the robot to effectively grab and pick up pins and cups from all directions (front/back claw and left/right claw).
- **Active Intake:** High-speed roller is implemented to quickly snatch game elements from directly in front of the robot, applying the "touch it, own it" mentality.
- **Symmetry:** The claw design is fully mirrored for maximal motor efficiency and consistent clamping force.

---

## Engineering Optimization

The design places strong emphasis on tolerances and clearances throughout.

- **Part Studio 1:** Primary Part Studio where all the final assemblies are done, also for global parameter settings.
- **Spacing:** Special Part Studio made to ensure there's enough room to ensure the DR4B doesn't hit the drivetrain.
- **Assembly 1:** The top-level assembly where the complete robot is put together for basic motion testing, and for determining the center of mass.

## Strategic Goals

1. **Field Control:** The traction wheels, along with a 36:60 gear ratio, will allow for solid mid-field control and defense.
2. **Advanced Scoring:** The high reach of the vertical lift makes it easy to score at the highest level.
3. **Vision Integration:** The fully symmetrical structure ensures an optimized space for a vision sensor that can consistently track the opponent's AprilTags and make strategic plays.

---

## License

This design is made to help and inspire future VRC teams. If you wish to use this robot or aspects of the DR4B or claw, please credit team 1509R.
