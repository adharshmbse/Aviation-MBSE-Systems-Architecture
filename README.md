<img width="1920" height="1080" alt="Screenshot (658)" src="https://github.com/user-attachments/assets/1b220dbc-a8fa-4668-9a5e-444236184e9f" />
<img width="1920" height="1080" alt="Screenshot (656)" src="https://github.com/user-attachments/assets/4dac5b36-adc7-43c0-849e-7f136cab0cef" />
<img width="1920" height="1080" alt="Screenshot (658)" src="https://github.com/user-attachments/assets/df6d0aaf-16bd-42f4-9b56-1d96773acfd3" />
<img width="1920" height="1080" alt="Screenshot (656)" src="https://github.com/user-attachments/assets/28875856-8be2-4d1e-83be-d83562e74be5" />
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

## 🛸 Project Update (August 2026): Multi-Platform Avionics & Data Architecture Validation

Successfully expanded the systems architecture portfolio across two complex autonomous vehicle domains: an **Autonomous Cargo UAV (Emergency Medical Logistics)** and a **Tactical Heavy Cargo Helicopter Maritime Platform**. Both systems have been fully modeled, allocated, and verified using the Thales Arcadia Methodology inside Eclipse Capella.

 1. Object-Oriented Operational Telemetry Framework
 
Natively structured and compiled formal Data Class Diagrams (`[CDB]`) within the Operational Analysis layer to govern real-time flight mission data streams. Generated true database entities mapping out core flight parameters:
*   `cargo weight : Decimal` — Heavy mass parameters managed via strict precision constraints.
*   `Target latitude / longitude / altitude : Float` — Floating-point numeric strings for real-time navigation autopilot calculations.
*   *Verification Status:* 100% healthy model registry tracking with zero `<undefined>` token anomalies or data packet fragmentation.

2. Physical Architecture Allocation (`[PAB]`) & Mass Budgeting

Deployed robust physical layer architectures mapping out internal electronic circuit cards (Behavior Components) nested inside structural system boundaries:
*   **Hosted Avionics Modules:** Configured `flight control computer board`, `autopilot flight computer`, `winch telemetry control`, and `power distribution board`.
*   **Avionics Bus Network:** Routed dedicated real-time data links, including `radio command bus`, `avionics data bus`, and `cargo manifest data` tracks.
*   **Physical Constraint Mapping:** Integrated explicit physical engineering weights directly inside the property registries (`unit mass = 0.45` to `1.2` units) to mathematically calculate multi-tier hardware mass thresholds.

 3. End-to-End Traceability Matrix Verification
 
Passed the complete multi-project repository through the Capella Model Validation Safety Engine. 
*   **Result:** Generated flawless Traceability Compliance Matrices (`[MTX]`) fully populated with solid diagonal `X` cross-reference verification codes.
*   **System Status:** Natively compiled with a confirmed green status of **"Operation has been successful"**—proving 100% structural trace integrity with absolutely zero orphan blocks, zero compilation flags, and zero validation design errors.

* **System Optimization Update (September 2026):** Successfully integrated multi-node physical constraint mapping elements directly into the PAB system registry. The model architecture now dynamically tracks payload mass tolerances across active telemetry channels with zero database compilation warnings.
