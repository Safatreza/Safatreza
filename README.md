# Md Safat Rezanur Majumder – Engineering Portfolio

🎓 B.Sc. Aerospace Engineering, Technical University of Munich (expected Sep 2026)
📫 [Email](mailto:mdsafatrezanurmajumder@gmail.com) | [LinkedIn](https://www.linkedin.com/in/md-safat-rezanur-majumder-8496a7273/) | [GitHub](https://github.com/Safatreza)
📍 Munich, Germany | Available immediately · 15–20 h/week

---

## 🔎 Summary

Seasoned aerospace engineering student with advanced expertise in computational fluid dynamics, structural integrity analysis, and real‑time telemetry systems. Proficient in Python, MATLAB, ANSYS Fluent, and OpenFOAM to architect and automate high‑impact engineering solutions. Recognized for optimizing complex workflows, reducing operational lead times, and fostering interdisciplinary collaboration in dynamic R\&D environments.

---

## 🎯 Objective

To contribute as a working student in a forward‑thinking aerospace or automation engineering team, leveraging my technical acumen in simulation, data‑driven telemetry, and multidisciplinary optimization. Committed to accelerating project delivery through automation, enhancing system reliability, and driving innovation in emerging aerospace technologies.

---

## 🛠️ Technical Skills

* **Programming & Scripting:** Python · MATLAB · C/C++ · Bash
* **CFD & Simulation:** ANSYS Fluent · OpenFOAM · SimPy
* **FEM & Structural Analysis:** HyperWorks (HyperMesh) · MATLAB Toolboxes
* **Telemetry & Data:** MQTT · Pandas · Dash/Plotly · FastAPI
* **CAD & Robotics:** SolidWorks · ROS · RViz
* **Automation & Tools:** Git · Docker · Jenkins · Linux
* **GUI Development:** Tkinter · Dash

---

## 🎓 Education

**Technical University of Munich (TUM)**
B.Sc. Aerospace Engineering, 10/2023–09/2026 (expected)

* Focus: Control Systems · Systems Engineering · Structures · Propulsion · Computational Thermal & Fluids Engineering
* Honors: Deutschlandstipendium Recipient

**Daffodil International University, Dhaka**
B.Sc. Computer Science & Engineering, 01/2021–12/2022

* Focus: Data Structures · Algorithms · Mechatronics · Embedded Systems · Microprocessors & Microcontrollers
* Honors: Achieved Highest GPA in Cohort

---

## 🚀 Featured Propulsion & Simulation Projects

### 1. afterburner-cfd

**GitHub:** [https://github.com/Safatreza/afterburner-cfd](https://github.com/Safatreza/afterburner-cfd)
**Tools:** Python · ANSYS Fluent · CoolProp
**Overview:** Designed an automated workflow for afterburner injector and flame holder CFD analysis.

**Approach & Details:**

* Developed Python scripts to parameterize injector throat geometry and fuel injection angles, auto-generate Fluent journal files, and orchestrate batch simulations.
* Integrated CoolProp for real-gas property calculations across chamber pressures of 1–10 bar.
* Automated post-processing to extract temperature and velocity contour data, producing comparative PDF and PNG plots for each geometry variant.

**Impact:**

* Achieved a 12% increase in simulated thermal efficiency for the optimal injector design.
* Reduced mesh setup and batch launch time by 30%, enabling overnight design sweeps without manual intervention.

---

### 2. CFD\_Analysis\_Solidworks

**GitHub:** [https://github.com/Safatreza/CFD\_Analysis\_Solidworks](https://github.com/Safatreza/CFD_Analysis_Solidworks)
**Tools:** OpenFOAM · ParaView · SolidWorks
**Overview:** Performed UAV nozzle and duct flow simulations to minimize losses and flow separation.

**Approach & Details:**

* Imported SolidWorks CAD assemblies into OpenFOAM, applied snappyHexMesh meshing with boundary layer refinement, and executed turbulent k-ω SST simulations.
* Conducted parametric sweeps of diffuser angles and throat curvatures, using custom ParaView Python scripts to log pressure drop and velocity streamline metrics for 20 iterative designs.
* Identified recirculation and separation zones, then refined geometry to mitigate adverse flow.

**Impact:**

* Reduced total pressure loss by 18% and flow separation magnitude by 12%.
* Improved theoretical specific impulse by 8% and decreased backpressure by 10%, extending UAV flight endurance estimates by hours.

---

### 3. JetEngineCycleSimulator

**GitHub:** [https://github.com/Safatreza/JetEngineCycleSimulator](https://github.com/Safatreza/JetEngineCycleSimulator)
**Tools:** Python · Pandas · Matplotlib
**Overview:** Developed an object-oriented thermodynamic cycle simulator for jet-engine performance assessment.

**Approach & Details:**

* Architected modular Python classes for compressors, turbines, combustors, and regenerators with methods to calculate isentropic and polytropic processes.
* Leveraged CoolProp for accurate gas property lookups from 300 K to 1500 K under varied pressures.
* Implemented batch-sweep scripts to vary compressor pressure ratios and regenerator efficiencies, outputting CSV performance tables and Matplotlib efficiency curves.

**Impact:**

* Enabled rapid sensitivity studies, generating complete performance maps in under 10 seconds per sweep.
* Provided academic collaborators with clear efficiency-versus-pressure-ratio visualizations for design trade-off decisions.

---

### 4. SupersonicNozzleCalculations

**GitHub:** [https://github.com/Safatreza/SupersonicNozzleCalculations](https://github.com/Safatreza/SupersonicNozzleCalculations)
**Tools:** Python · NumPy · SciPy · Matplotlib
**Overview:** Created an automated 1-D solver for supersonic nozzle flow analysis with parameter sweeps.

**Approach & Details:**

* Implemented Rayleigh flow and normal shock equations to calculate Mach, pressure, and temperature distributions along nozzle contours.
* Provided a CLI for defining area-ratio sequences, running 100-sample param sweeps in under 5 seconds on standard laptops.
* Generated thrust vs. area ratio plots with annotated optimal design points using Matplotlib.

**Impact:**

* Reduced demonstration prep time for CFD coursework by 70%.
* Delivered thrust predictions within 2% of established textbook solutions.

---

## ✈️ UAV & Flight‑Dynamics Projects

### 5. valkyrie\_flight\_estimator

**GitHub:** [https://github.com/Safatreza/valkyrie\_flight\_estimator](https://github.com/Safatreza/valkyrie_flight_estimator)
**Tools:** Python · Pandas · SolidWorks API · Matplotlib
**Overview:** Developed a real-time estimator for UAV thrust, CG, and fuel-consumption.

**Approach & Details:**

* Parsed telemetry logs to compute instantaneous thrust and center-of-gravity shifts via SolidWorks mass-property API.
* Applied Kalman filtering to smooth sensor noise and estimate fuel burn rates dynamically.
* Built a Matplotlib-based GUI overlaying mission timeline charts and flight-envelope plots.

**Impact:**

* Achieved performance predictions within 3% of flight-test benchmarks.
* Empowered flight engineers to adjust mission parameters mid-flight based on live data.

---

### 6. uav\_simulator

**GitHub:** [https://github.com/Safatreza/uav\_simulator](https://github.com/Safatreza/uav_simulator)
**Tools:** Python · PyOpenGL · NumPy
**Overview:** Created a 6-DOF UAV simulation environment for control algorithm validation.

**Approach & Details:**

* Implemented Newton-Euler rigid-body dynamics and parameterized lift/drag models based on Mach and Reynolds numbers.
* Designed scenario scripts to define waypoints, wind profiles, and control inputs for diverse flight tests.
* Visualized trajectories in 3D via PyOpenGL.

**Impact:**

* Reduced physical test hours by 25%, accelerating control software iterations.
* Provided interactive lab tools for student demonstrations of flight dynamics.

---

### 7. flight\_dashboard

**GitHub:** [https://github.com/Safatreza/flight\_dashboard](https://github.com/Safatreza/flight_dashboard)
**Tools:** Flask · Chart.js · JavaScript
**Overview:** Developed a responsive web dashboard for live UAV telemetry and status monitoring.

**Approach & Details:**

* Created Flask REST endpoints to ingest MQTT telemetry messages and serve JSON to the front-end.
* Implemented Chart.js visualizations for altitude, speed, battery level, and temperature streams.
* Added WebSocket support for real-time updates in modern browsers.

**Impact:**

* Sustained <100 ms end-to-end latency under 100 concurrent clients.
* Improved anomaly detection response time by 30% through live alerts.

---

## 🔧 Embedded‑Systems & Tooling Projects

### 8. NozzleDesignTool

**GitHub:** [https://github.com/Safatreza/NozzleDesignTool](https://github.com/Safatreza/NozzleDesignTool)
**Tools:** Python · PyQt · CoolProp · Gmsh
**Overview:** Built a GUI application for parametric convergent-divergent nozzle design and mesh export.

**Approach & Details:**

* Developed PyQt forms for user input of geometric parameters and boundary conditions.
* Integrated CoolProp for real-gas thermophysical properties and generated Gmsh scripts for volume meshing.
* Enabled batch sensitivity runs with CSV output of geometric and mesh quality metrics.

**Impact:**

* Reduced design-iteration time by 60%, generating CFD-ready meshes in under 1 minute per configuration.
* Facilitated rapid prototype testing without dedicated CFD software licenses.

---

### 9. thrust-curve-analyzer

**GitHub:** [https://github.com/Safatreza/thrust-curve-analyzer](https://github.com/Safatreza/thrust-curve-analyzer)
**Tools:** Python · Pandas · Matplotlib
**Overview:** Created a desktop tool for test-stand thrust-curve processing and impulse calculation.

**Approach & Details:**

* Implemented Savitzky-Golay filtering for noise reduction and trapezoidal integration for total impulse.
* Designed Tkinter GUI for batch loading of CSV logs, curve comparison, and report export.

**Impact:**

* Processed 5+ test files in a single batch with 40% faster throughput.
* Achieved impulse calculation error <3% relative to hand calculations.

---

### 10. RefrigerationCycleSimulationTool

**GitHub:** [https://github.com/Safatreza/RefrigerationCycleSimulationTool](https://github.com/Safatreza/RefrigerationCycleSimulationTool)
**Tools:** Python · CoolProp · Matplotlib
**Overview:** Developed a vapor-compression refrigeration cycle simulator for performance evaluation.

**Approach & Details:**

* Modeled evaporator, compressor, condenser, and expansion valve processes using CoolProp for property data.
* Generated annotated P–h diagrams and calculated COP for refrigerants R134a and R600a over 5–25 °C ranges.

**Impact:**

* Enabled direct refrigerant performance comparisons, aiding selection of optimal working fluid for HVAC designs.

---

## 🔌 Electronics & Circuit Design

### 11. ECG\_circuit\_Design

**GitHub:** [https://github.com/Safatreza/ECG\_circuit\_Design](https://github.com/Safatreza/ECG_circuit_Design)
**Tools:** LTspice · PCB Layout · Spice Simulation
**Overview:** Designed and simulated a multi-parameter ICU ECG acquisition circuit.

**Approach & Details:**

* Created amplifier and band-pass filter stages in LTspice, optimizing for 0.5–150 Hz signals and low noise.
* Reviewed Eagle PCB schematics and validated analog front-end performance under ±2 mV input swings.

**Impact:**

* Improved SNR by 20 dB, meeting medical device signal-integrity standards.

---

### 12. Traffic\_signal\_Programmable\_Circuit

**GitHub:** [https://github.com/Safatreza/Traffic\_singnal\_Programmable\_Circuit](https://github.com/Safatreza/Traffic_singnal_Programmable_Circuit)
**Tools:** VHDL · Quartus Prime
**Overview:** Implemented a finite-state traffic light controller with pedestrian override functionality.

**Approach & Details:**

* Developed VHDL modules for timed state transitions, cycle counters, and asynchronous pedestrian requests.
* Constructed testbenches to simulate variable traffic patterns and validate timing constraints.

**Impact:**

* Verified correct state sequencing and timing in Quartus Prime simulation, ready for FPGA prototyping.

---

### 13. Raspbarry\_Pi\_Design

**GitHub:** [https://github.com/Safatreza/Raspbarry\_Pi\_Design](https://github.com/Safatreza/Raspbarry_Pi_Design)
**Tools:** Raspberry Pi · Python · SolidWorks
**Overview:** Integrated custom sensor PCB with Raspberry Pi for environmental data logging.

**Approach & Details:**

* Designed PCB layout for temperature, humidity, and pressure sensors in Eagle and SolidWorks enclosure models.
* Authored Python scripts to sample sensors at 1 Hz, store data in CSV, and serve via local Flask dashboard.

**Impact:**

* Enabled stable 24/7 data logging across 7 sensor nodes, supporting campus environmental monitoring.

---

## 📊 Data & Analysis Projects

### 14. VitalDataIngestor

**GitHub:** [https://github.com/Safatreza/VitalDataIngestor](https://github.com/Safatreza/VitalDataIngestor)
**Tools:** Python · Pandas
**Overview:** Developed an ETL pipeline for large-scale biomedical sensor datasets.

**Approach & Details:**

* Built modular loader supporting CSV, JSON, and binary inputs, with chunked processing for files up to 100 MB.
* Implemented data cleaning, outlier detection, and normalization modules for downstream ML tasks.

**Impact:**

* Processed 10,000+ records per minute, enabling rapid analytics for ICU telemetry research.

---

## 🏆 Awards & Honors

* **Deutschlandstipendium** – German Federal Ministry of Education & Research
* **National Merit Scholarship** – Government of Bangladesh

---

> “Der Vogelflug ist das Vorbild aller Flugtechnik.”
> — Otto Lilienthal






