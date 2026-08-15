# Multi-Platform Avionics System Architecture Portfolio
## Model-Based Systems Engineering (MBSE) Repository

This repository contains the end-to-end mechatronic systems architecture models for an **Autonomous Cargo UAV Drone** and an **Unmanned Autonomous Helicopter (UAV)**. Both aircraft platforms were engineered utilizing the rigorous **Thales Arcadia Methodology** inside the **Capella Workbench** modeling engine to ensure 100% functional and structural lifecycle traceability.

---

##  Core Architectural Framework & Methodology
By shifting away from traditional document-based systems engineering, this portfolio demonstrates structural requirements validation across all 4 layers of the Arcadia lifecycle:
1. **Operational Analysis (OA):** Mapping real-world stakeholder needs (Hospital Base, Emergency Camp, Shipyard Crane, Oil Rig Boss).
2. **System Analysis (SA):** Initial boundary scoping, external actors allocation, and high-level flight command data loop definitions.
3. **Logical Architecture (LA):** Breaking down internal system behavior into abstract modular software execution blocks.
4. **Physical Architecture (PA):** Final physical hardware node placement, electronic component encapsulation, and copper data bus link wiring.

---

##  Project 1: Unmanned Autonomous Helicopter (UAV)
* **Mission Profile:** Heavy Maritime Cargo Logistics (Automated Shipyard-to-Offshore Rig payload transport).
* **Operational Scope:** Designed to automate heavy cargo box deliveries from a physical shipyard crane operator outpost across open-ocean flight paths out to a remote oil rig boss terminal.
* **System Boundaries:** Central avionics computing chassis hosting distinct mechatronic physical layers.
* **Hardware/Software Nesting:** The abstract `Cargo Management Subsystem` software logic module is directly encapsulated inside the physical `winch telemetry control board` hardware board circuit enclosure.
* **Fail-Safe & Redundancy:** Engineered a multi-channel hardware communication pipeline routing data between the core `flight control computer board`, a high-power satellite radio transceiver module, and a redundant `backup inertial navigation board imu` to secure vehicle tracking during complete radio blackout states.

---

##  Project 2: Autonomous Cargo UAV Drone
* **Mission Profile:** Emergency Medical Supply Logistics (Clean, high-speed payload transit routing between hospitals and remote emergency camps).
* **Operational Scope:** Engineered for high-speed, critical medical payload transport, linking city hospital hubs directly to distant field medical stations during crisis scenarios.
* **Avionics Routing Configuration:** Multi-node component architecture linking flight management computer boards, autonomous payload locking actuators, and power distribution systems cleanly across a shared avionics data network.

---

##  Verification & Compliance Controls
Systems integration layout validity is maintained on database-level matrices. Every physical board implementation maps flawlessly down the diagonal tracking grid axis of the compiled **Traceability Matrix**, verifying that 100% of software logic components match corresponding hardware circuitry with zero architectural design faults, orphan nodes, or validation description errors.

---

##  Repository Directory Structure
* `/Capella Project Models`: Houses the raw ` melodymod` repository files and model trees ready for local workbench import.
* `/Architecture Blueprints`: High-definition, structural diagram snapshots including `[PAB]` Physical Architecture Blank sheets and verified compliance matrix tables.

---
*Ready to deploy these production-grade mechatronic modeling, system validation, and avionics architecture capabilities within the global aerospace, autonomous systems, and defense domains.*
