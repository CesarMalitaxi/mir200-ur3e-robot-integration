# Autonomous Mobile Robot Integration — MiR200 & UR3e

**Academic Robotics Project | Universidad Europea de Madrid | 2025–2026**

## Project Overview

Integration of a MiR200 autonomous mobile robot (AMR) with a Universal Robots UR3e collaborative robotic arm to automate material handling and transportation between workstations.

The project was developed and physically tested in a university robotics laboratory.

The main objective was to coordinate autonomous navigation, robot-to-robot communication and material manipulation within a single automated workflow.

## Technologies and Equipment

- **MiR200:** autonomous mobile robot for material transport
- **UR3e:** six-axis collaborative robotic arm
- **MiR Robot Interface:** map configuration and mission programming
- **Navigation:** autonomous localization, path planning and obstacle avoidance using the robot's integrated capabilities
- **Digital I/O:** coordination and status signaling between robotic systems
- **Industrial automation:** sequential control, mission logic and functional testing

## System Architecture

The system integrates two robotic platforms with different responsibilities.

**MiR200 — Mobile platform**

- Configuration of navigation maps
- Definition of permitted, restricted and low-speed zones
- Programming of autonomous transport missions
- Navigation between predefined workstations

**UR3e — Robotic manipulator**

- Material handling at the loading station
- Execution of programmed manipulation sequences
- Coordination with the MiR200 through control signals

## Operational Workflow

1. The MiR200 navigates autonomously to the UR3e workstation.
2. Upon arrival, a control signal initiates the coordinated loading sequence.
3. The UR3e manipulates and places the parts onto the mobile platform.
4. After the loading operation is completed, the MiR200 continues to the destination station.

The complete sequence was tested using the physical robots.

## Navigation and Mission Development

The project involved configuring maps for laboratory and adjacent circulation areas.

Navigation parameters included restricted zones, preferred routes, reduced-speed areas and predefined positions.

Additional missions and supervisory logic were developed for internal transport tasks.

## Validation and Results

The team demonstrated the coordinated operation of the MiR200 and UR3e in a real laboratory environment.

**Verified outcomes:**

- Autonomous navigation to a programmed workstation
- Coordination between the mobile robot and robotic manipulator
- Physical loading of parts onto the MiR200
- Continuation of the transport mission after loading

These results demonstrate system
