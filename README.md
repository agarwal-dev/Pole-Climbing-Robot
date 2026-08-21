# Pole Climbing Robot

Design and development of a **detachable friction-based pole climbing robot** for surveillance and inspection applications, developed as a B.Tech project.

## Project Overview

The robot uses a **spring-assisted wheel mechanism** to generate normal force between high-grip wheels and the pole surface, producing the friction required for vertical climbing.

The design was developed for poles with different diameters and includes a wireless control and surveillance system.

## Key Features

- Four-wheel friction-based climbing mechanism
- Spring-generated normal force for wheel traction
- Designed for **50–100 mm pole radii**
- High-grip rubber wheels
- Worm-gear DC motors for high torque and self-locking
- Detachable and lightweight wooden frame
- ESP32-based wireless motion control
- ESP32 camera module for surveillance

## Design & Calculations

- Friction requirement: `nμN ≥ mg`
- Spring-generated normal force: `N = Fs cosθ`
- Wheel radius: **40 mm**
- Coefficient of friction: **0.6–0.8**
- Design load: **5 kg**
- Calculated torque requirement: **1 N·m per motor**
- Motors with torque greater than **10 kg-cm** were selected

## Prototype Development

The initial **60 × 60 mm** wooden frame was found to be excessively heavy and was redesigned using **40 × 40 mm** sections.

The prototype was iteratively refined to address wheel alignment, structural weight, friction, motor loading and fabrication accuracy.

## Electronics

- ESP32
- BTS7960 motor driver
- Worm-gear DC motors
- 3S Li-ion/LiPo battery
- ESP32 camera module

## Tools Used

- SolidWorks
- CAD modelling and assembly
- Mechanical calculations
- Prototype fabrication

## Applications

- Electric pole inspection
- Telecom tower inspection
- Industrial structure inspection
- Remote surveillance
- Hazardous-environment inspection

## Preview

CAD model, circuit, mechanical prototype and testing images are included in this repository.

## Project Status

**Completed**
