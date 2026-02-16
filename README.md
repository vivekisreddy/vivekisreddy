# Vivek Reddy Kasireddy

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Robotics%20%26%20Software%20Engineering-007ACC?style=flat-square&logo=robotframework&logoColor=white" />
  <img src="https://img.shields.io/badge/Location-North%20Andover%2C%20MA-ff69b4?style=flat-square" />
  <img src="https://img.shields.io/badge/School-WPI-red?style=flat-square&logo=graduation-cap" />
</p>

---

## About Me

I am a **Computer Science & Robotics Engineering student at Worcester Polytechnic Institute (WPI)** with 3+ years of experience building scalable software systems, embedded platforms, and autonomous robotic architectures.

My work spans:

* 🤖 **Autonomous Systems, Perception, and Navigation**
* 💻 **Full-Stack & Backend Distributed Systems**
* ⚙️ **Embedded Systems, FPGA-Based Control, and Hardware/Software Co-Design**
* 🧠 **Machine Learning, Depth Estimation, and Computer Vision**
* 🧪 **Test Automation & Real-Time System Validation**

I am particularly interested in **systems engineering, robotics software, distributed backend systems, embedded control, perception, and high-performance applications engineering**.

---

## Education

**Worcester Polytechnic Institute (WPI)** — Worcester, MA
Bachelor of Science in Computer Science & Robotics Engineering
Expected Graduation: May 2026
GPA: 3.81/4.00 | 6× Dean’s List

**Relevant Coursework:**
Software Engineering, Artificial Intelligence, Operating Systems, Computer Networks, Systems Programming, Algorithms, Data Mining, Machine Learning, Embedded Systems, Controls Engineering, Robotics (Actuation, Sensing, Manipulation), Big Data Analytics, Reinforcement Learning for Robotics.

---

## Technical Skills

| Languages                                                             | Frameworks & Systems                                                                                                      | Hardware & Engineering                                                                                                              |
| --------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| C++, C, Python, TypeScript, JavaScript, SQL, Java, Verilog, HTML, CSS | AWS, React.js, Node.js, MySQL, REST APIs, PyTorch, TensorFlow, Scikit-Learn, Pandas, NumPy, Linux, Quartus, ModelSim, Git | FPGA (Altera), SPI, LVDS, ADC/PWM, Jetson (NVIDIA), LiDAR, OpenCV, CAD, Circuit Design, Embedded Control Loops, Vacuum Test Systems |

---

## Professional Experience

### Test Automation Engineer (Co-Op) — Brooks Automation

*Sept 2025 – Present*

* Architecting a real-time distributed control system across dual FPGA platforms, implementing SPI-based communication and LVDS signaling to ensure deterministic high-integrity data transfer across 2–10m physical links.
* Designing software-driven validation pipelines for vacuum chamber infrastructure, building automated test workflows, thermal stability verification procedures, and reproducible data logging systems.
* Bridging hardware/software layers to ensure control-system reliability under strict environmental constraints.

---

### Researcher & Perception Engineer — PeAR Lab, WPI

*Aug 2025 – Present*

* Designed and trained a custom U-Net–based depth estimation model (PyTorch) using phase-mask optical data and supervised ground truth capture.
* Implemented iterative image reconstruction algorithms (ADMM, FISTA) deployed on NVIDIA Jetson for real-time inference.
* Prototyping a mirror-based stereo vision architecture to enable depth perception without traditional dual-camera baselines.
* Evaluating system observability limits and informing next-generation multi-lens optical design.

---

### Automation & Lab Test Engineering Intern — Brooks Automation

*May 2025 – Aug 2025*

* Implemented SPI communication between master/slave Altera FPGA boards in Verilog, validating signal integrity through ModelSim simulation and physical cable-length testing.
* Designed FPGA-based embedded control logic to process ADC data and generate real-time PWM signals.
* Commissioned a custom vacuum chamber test stand integrating CAD designs and electromechanical subsystems.

---

### Product Developer — EPFL (Lausanne, Switzerland)

*March – May 2025*

* Developed a frontend search interface integrated with a campus-wide research database.
* Focused on query optimization, scalable data retrieval, and usability-centered design for high-volume academic datasets.

---

### Software Test Engineer — Solgud Robotics (Harvard University Startup)

*June 2023 – Sept 2023*

* Diagnosed and resolved localization, SLAM, object detection, and path-planning failures in autonomous robotic systems.
* Debugged sensor integration issues across LiDAR, IMU, and encoder pipelines.
* Improved navigation reliability across dynamic indoor environments through hardware/software validation cycles.

---

## Projects

---

# 🤖 Robotics & Autonomous Systems

### Autonomous Solar Panel Replacement Robot

* Designed FSM-driven autonomous robot with servo-actuated gripper for panel removal/replacement.
* Integrated line-following, IR control, and state-based task execution (85% task success rate).
  `C/C++`, `Embedded Systems`, `FSM`

### Escape Room Maze Runner Robot

* Built ramp-climbing robot with AprilTag-based localization (~1mm precision).
* Coordinated dual-robot synchronization for mechanical stability.
  `C/C++`, `Computer Vision`, `Localization`

### Industrial Serial-Arm Manipulation System

* Developed real-time vision-based object tracking system.
* Implemented inverse kinematics, trajectory generation, and control for 5-DOF robotic arm (95% control accuracy).
  `MATLAB`, `OpenCV`, `Kinematics`, `Control`

### Vehicle Perception Simulation (Unreal Engine)

* Developed LiDAR simulation modules in Unreal Engine using C++ to replicate autonomous driving perception environments.
  `C++`, `Simulation`, `LiDAR`

---

# ⚙️ Embedded & ECE Systems

### FPGA-Based SPI Communication Platform

* Designed master/slave FPGA communication system using SPI and validated signal reliability under long-distance constraints.
  `Verilog`, `SPI`, `ModelSim`

### Embedded Time & Temperature Display (MSP430)

* Implemented ADC12 temperature sensing and Timer A2 scheduling for real-time display logic.
  `Embedded C`, `ADC`, `Timers`

### Real-Time ADC-to-PWM Control Loop

* Built FPGA logic pipeline converting sensor data into deterministic PWM control signals.
  `FPGA`, `Embedded Control`

---

# 💻 CS / Software Engineering & Distributed Systems

### Tables4U – Restaurant Reservation Platform

* Built full-stack system using React frontend and AWS Lambda backend.
* Integrated API Gateway, RDS, and real-time reservation workflows.
  `AWS`, `React`, `TypeScript`, `SQL`

### ChoreMates – Multi-User Roommate Coordination App

* Designed scalable full-stack application supporting authentication, shared expense tracking, and grocery management.
* Implemented cloud-hosted backend services and API-driven state synchronization.
  `React`, `AWS`, `Node.js`

### HTTP Client/Server with Priority Packet Scheduling

* Implemented HTTP/1.1 client/server using socket programming.
* Designed custom packet scheduler to simulate router-level prioritization and improve throughput under congestion.
  `C/C++`, `Sockets`, `Wireshark`

### AI Path Planning & Heuristic Optimization

* Built modular path-planning engine implementing A*, hill climbing, and heuristic evaluation strategies.
* Benchmarked node expansion, runtime scaling, and convergence under obstacle constraints.
  `Python`, `Algorithms`, `Graph Search`

---

# 🧠 Machine Learning & AI

### Mudra AI – Real-Time ASL Gesture Translator

* Developed real-time ASL-to-text/voice system using MediaPipe landmark extraction (~90% detection accuracy).
* Integrated Gemini for language refinement and ElevenLabs TTS for speech output.
  `TensorFlow`, `Computer Vision`, `LLM Integration`

### Traffic Sign Classification

* Implemented CNN-based classifier achieving 99% accuracy on traffic sign dataset.
* Compared architectures across TensorFlow and PyTorch pipelines.
  `Deep Learning`, `CNNs`

### Phase-Mask Depth Estimation

* Built custom U-Net architecture for depth reconstruction from computational optics data.
* Conducted error analysis to inform multi-lens system redesign.
  `PyTorch`, `Computer Vision`

---

## Leadership

Vice President — South Asian Student Association (SASA)
Leading campus-wide programming, cross-cultural initiatives, and event coordination.

---

## Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/vivek-reddy-kasireddy/)
[![GitHub](https://img.shields.io/badge/GitHub-grey?style=for-the-badge\&logo=github\&logoColor=white)](https://github.com/vivekisreddy)

📧 [vivekkasireddyr@gmail.com](mailto:vivekkasireddyr@gmail.com)
📍 North Andover, MA

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=vivekisreddy&show_icons=true&theme=radical" width="45%"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=vivekisreddy&layout=compact&theme=radical" width="45%"/>
</p>


