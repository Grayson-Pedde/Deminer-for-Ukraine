# REM-E: Remote Eradication of Mines and other Explosives

## Overview
REM-E (Remote Eradication of Mines and other Explosives) is a small-scale prototype of a remotely operated demining vehicle designed to provide a safer, lower-cost alternative to manual landmine removal. The project was completed as part of an engineering design and project management course and was developed by a team of five students.

The work culminated in a **46-page formal engineering report** detailing the background research, design decisions, budgeting, risk analysis, and prototype development.

---

## Project Motivation
Due to ongoing conflict in Ukraine, large portions of farmland remain contaminated with anti-personnel and anti-vehicle landmines. Manual demining is dangerous, slow, and expensive. REM-E explores a concept for a remotely operated vehicle that allows farmers to clear land while remaining at a safe distance, using readily available technology and replaceable components.

---

## My Role (Electrical Engineering)
Within the team of five, I was responsible for **all electrical system design and integration**, including:
- Electrical architecture and component selection  
- Power distribution and voltage regulation  
- Motor drivers and ESC integration  
- Bluetooth communication and control logic  
- Arduino programming and system bring-up  
- Electrical troubleshooting and testing  

---

## Electrical System Architecture
The electrical system was designed to separate high-power motor loads from low-voltage control electronics. A 12 V battery powered the drive motors and flail motor through motor drivers and an ESC, while a regulated 5 V supply powered the Arduino, Bluetooth module, and sensors.

![Electrical Circuit Diagram](images/circuit_diagram.jpg)

---

## Control and Communication
REM-E is controlled remotely using a smartphone via the Dabble app and an HM-10 Bluetooth module. The Arduino interprets control inputs and translates them into motor commands for both vehicle motion and flail operation. Considerable effort was required to decode Bluetooth input packets and correctly map them to control functions.

![Wiring and Electrical Integration](images/wiring.jpg)

---

## Mechanical Integration Support
While mechanical design and CAD were handled by other team members, close coordination was required to ensure the electrical layout fit within the SolidWorks-designed chassis. Component placement prioritized accessibility, serviceability, and protection from vibration and debris.

![SolidWorks CAD Model](images/solidworks_model.jpg)

---

## Prototype Assembly
The prototype vehicle integrated the electrical system into a reinforced tractor-style base. Internal wiring was routed to minimize interference and allow for maintenance. The design also allowed for future expansion, including additional sensors and attachments.

![Final Assembly](images/final_assembly.jpg)

---

## Budget and Cost Analysis
An initial project budget of $195 was established, with a large portion allocated to electrical components. Through reuse of existing materials and careful component selection, the **final prototype cost was reduced to approximately $101**, representing a significant cost savings.

![Project Budget Breakdown](images/budget.jpg)

---

## Challenges and Troubleshooting
Several challenges were encountered during development:
- High current draw from motors required careful driver selection and testing  
- ESC behavior required special initialization logic to ensure reliable startup  
- Power isolation was necessary to prevent logic-level brownouts  
- Vibration and space constraints influenced wiring and mounting decisions  

These issues were resolved through iterative testing, component isolation, and code refinement.

---

## Results and Outcomes
The final REM-E prototype successfully demonstrated:
- Remote control of vehicle motion and flail system  
- Safe separation between operator and hazardous environment  
- Stable electrical operation under load  
- A scalable design suitable for further iteration  

While the prototype is not intended for real-world deployment, it serves as a proof-of-concept and reference design for future humanitarian demining solutions.

---

## Documentation
A **46-page formal engineering report** accompanies this project and includes:
- Background research and problem analysis  
- Design concepts and selection criteria  
- Electrical and mechanical system breakdowns  
- Budgeting and bill of materials  
- Risk assessment and mitigation strategies  
- Project scheduling and lessons learned  

---

## Skills & Concepts Applied
- System-level electrical design  
- Motor drivers, ESCs, and high-current systems  
- Arduino and embedded C++ programming  
- Bluetooth communication (HM-10)  
- Power regulation and battery management  
- Electrical troubleshooting and testing  
- Interdisciplinary team collaboration  
