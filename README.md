⚡ Variable DC Power Supply (1.5-24V, 0-2A)
Welcome to the repository for my variable DC power supply fabrication project. This repo documents the build and validation of a fully functional power supply capable of delivering 1.5-24V and 0-2A.


Originally fabricated for my Electronics Engineering Technician diploma, this device is now a permanent fixture on my workbench for breadboarding and powering microcontroller experiments.


🛠️ Build Highlights

PCB Assembly: The entire circuit board was hand-soldered to IPC standards, navigating complex surface-mount components and resolving solder bridging on a fine-pitch 40-pin LCD connector.



Custom Enclosure: The housing was designed in Fusion 360 to perfectly fit the transformer, PCB, touchscreen display, and cooling vents.


Validation: The power supply passed rigorous testing, including thermal profiling (staying under 125°C at full load) and oscilloscope signal verification to ensure a stable DC output.


🚀 IoT Smart Energy Meter Capstone (Completed) The fabrication, board-level troubleshooting, and thermal design skills honed during my variable DC power supply build were instrumental in bringing this IoT Smart Energy Meter Capstone to a successful close. This repository includes the final schematics, block diagrams, and PCB snapshots from the completed project.

Project Details: For our final capstone project, we successfully engineered an isolated IoT Smart Energy Meter for single-phase AC and DC applications (under 45V). The final system is built on a custom 4-layer PCB utilizing a PIC24 microcontroller paired with a 24-bit external ADC for highly precise, real-time data acquisition. We developed and deployed C firmware to process this telemetry, measuring real power, RMS voltage, and current with ±2% accuracy, and transmit it to a remote dashboard via a hardwired Ethernet connection.

Throughout the final fabrication and testing phases, we performed rigorous bench testing, hardware troubleshooting, and necessary component-level repairs to validate the hardware's performance and safety. As a result, the finalized design operates safely and efficiently around a strict isolated hot/cold side architecture.

📝 Important Note on the Project Charter: You will find the Project_Charter_Overview_WBS_Finished.pdf attached in the files. Please note that this charter was developed at the inception of the project. As the design progressed through testing and we incorporated valuable hands-on feedback, we made necessary technical pivots, most notably shifting away from our initial ESP32 concept to the much more precise PIC24 and external ADC architecture. Therefore, the final, fully realized hardware naturally evolved from the initial scope outlined in this original document.
