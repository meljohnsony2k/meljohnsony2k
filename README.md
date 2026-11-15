<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Mel Johnson, Mechatronics Engineer" src="assets/banner-light.svg" width="100%">
</picture>

I build and test systems where software meets hardware: feedback control, sensor fusion, embedded firmware and vehicle electronics. I like to get close to the real thing, measure it, model it, and make it run reliably.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/stats-dark.svg">
  <img alt="43.08 s fastest class run, 4.9 m error over 450 m, 3x slower drift, 6x longer hinge life" src="assets/stats-light.svg" width="100%">
</picture>

**Master of Mechatronics Engineering (Manufacturing)**, University of Melbourne<br>
**Bachelor of Technology, Electronics and Communication Engineering (IoT and Sensors)**, VIT Vellore

---

### Robotics, sensing and control

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/meljohnsony2k/autonomous-mining-vehicle-sensor-fusion"><img src="assets/projects/mining.jpg" width="100%" alt="Mining vehicle localisation"></a>
<br><b><a href="https://github.com/meljohnsony2k/autonomous-mining-vehicle-sensor-fusion">Autonomous Mining Vehicle Localisation</a></b>
<br>UKF fusion of IMU, LiDAR (AMCL) and GPS in ROS that keeps the vehicle localised when GPS drops out in tunnels. Error grows about 3× slower than LiDAR alone. Tested on a custom robot.
<br><sub>ROS · UKF · Gazebo · LiDAR · Python</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/meljohnsony2k/asc-plant-monitoring-robot"><img src="assets/projects/plant-robot.jpg" width="100%" alt="Plant monitoring robot"></a>
<br><b><a href="https://github.com/meljohnsony2k/asc-plant-monitoring-robot">Autonomous Plant Monitoring Robot</a></b>
<br>Wheel odometry with a measured error model, odometry and vision fusion, mission logic and LiDAR obstacle stopping. Detection turnaround cut from 30 to 60 s down to under 5 s.
<br><sub>ROS · Sensor fusion · Odometry · LiDAR · YOLO</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/meljohnsony2k/kobuki-hill-climb"><img src="assets/projects/kobuki.jpg" width="100%" alt="Kobuki hill climb"></a>
<br><b><a href="https://github.com/meljohnsony2k/kobuki-hill-climb">Kobuki Hill Climb</a></b>
<br>Statechart controller for an obstacle course and ramp. Fastest run in the class (43.08 s). Succeeds on 98.5% of 200 random courses and robots in a custom simulator.
<br><sub>Statecharts · LabVIEW · myRIO · Python · Monte Carlo</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/meljohnsony2k/ev3-inverted-pendulum-control"><img src="assets/projects/ev3.jpg" width="100%" alt="EV3 inverted pendulum"></a>
<br><b><a href="https://github.com/meljohnsony2k/ev3-inverted-pendulum-control">EV3 Inverted Pendulum</a></b>
<br>Model fitted from a step test, then a lead controller that balances an unstable pendulum with 47° phase margin, plus integral action for steering loads. Simulated as it runs on the robot, at 5 ms.
<br><sub>Loop shaping · Nyquist · System ID · Simulink · Python</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/meljohnsony2k/pendulum-anti-sway"><img src="assets/projects/pendulum.jpg" width="100%" alt="Pendulum anti-sway"></a>
<br><b><a href="https://github.com/meljohnsony2k/pendulum-anti-sway">Pendulum Anti-Sway</a></b>
<br>Computer vision tracking of a hanging load, then a person, a feedback controller and input shaping compared. Input shaping settles in 1.4 s against 3.8 s by hand.
<br><sub>OpenCV · System ID · Input shaping · Python</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/meljohnsony2k/gyroscope-dynamics"><img src="assets/projects/gyro.jpg" width="100%" alt="Gyroscope dynamics"></a>
<br><b><a href="https://github.com/meljohnsony2k/gyroscope-dynamics">Gyroscope Dynamics</a></b>
<br>3 DOF model derived with Newton-Euler and Lagrange, fitted to sensor data. Matches the measured nutation period and precession rate.
<br><sub>MATLAB · SymPy · Rigid body dynamics</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/meljohnsony2k/smartphone-pedestrian-navigation"><img src="assets/projects/pedestrian-nav.jpg" width="100%" alt="Smartphone pedestrian navigation"></a>
<br><b><a href="https://github.com/meljohnsony2k/smartphone-pedestrian-navigation">Smartphone Pedestrian Navigation</a></b>
<br>Step counting, gyro and compass fused in a Kalman filter, and loop closure, from a phone's IMU alone. 4.9 m RMS position error over a 450 m lap against GPS.
<br><sub>IMU · Kalman filter · Sensor calibration · Python</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/meljohnsony2k/mechanical-pet-turtle"><img src="assets/projects/turtle.jpg" width="100%" alt="Mechanical pet turtle"></a>
<br><b><a href="https://github.com/meljohnsony2k/mechanical-pet-turtle">Mechanical Pet Turtle</a></b>
<br>Swimming robot with a 23:1 gear train, Chebyshev linkages and a retracting head driven by a stepper and ultrasonic sensor. Firmware tested against a mocked Arduino.
<br><sub>Mechanisms · Arduino · Laser cutting · C++</sub>
</td>
</tr>
</table>

### Automotive and manufacturing

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/meljohnsony2k/autostarke-lexus-engineering-projects"><img src="assets/projects/lexus.jpg" width="100%" alt="Lexus lounge conversion"></a>
<br><b><a href="https://github.com/meljohnsony2k/autostarke-lexus-engineering-projects">Lexus Special Projects (R&D internship)</a></b>
<br>VIP lounge seat conversion and off road kit for a Lexus LX570, plus PID controlled extending walls for a truck mounted showroom. Real vehicles, delivered to clients.
<br><sub>Wiring harness · ECU diagnostics · Arduino · PID · Fusion 360</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/meljohnsony2k/vortex-diagnostics-toolkit"><img src="assets/projects/vortex.jpg" width="100%" alt="Vortex diagnostics toolkit"></a>
<br><b><a href="https://github.com/meljohnsony2k/vortex-diagnostics-toolkit">Vortex Diagnostics Toolkit (BMW / MINI)</a></b>
<br>Command line tool that reads VIN, module versions, fault codes and battery voltage over ENET, and runs a safety check before coding. Tested against a simulated DoIP gateway.
<br><sub>DoIP · UDS · Python · Automotive diagnostics</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/meljohnsony2k/prusa-mk4s-design-for-manufacture"><img src="assets/projects/prusa.jpg" width="100%" alt="Prusa MK4S DFM"></a>
<br><b><a href="https://github.com/meljohnsony2k/prusa-mk4s-design-for-manufacture">Prusa MK4S Design for Manufacture</a></b>
<br>Printer parts redesigned for CNC, injection moulding and sheet metal, then inspected against tolerances. Y axis assembly took 18 min against 37 min predicted.
<br><sub>SolidWorks · DFM/DFA · Tolerance analysis</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/meljohnsony2k/hinge-quality-reliability"><img src="assets/projects/hinge.jpg" width="100%" alt="Hinge reliability"></a>
<br><b><a href="https://github.com/meljohnsony2k/hinge-quality-reliability">3D Printed Hinge Quality and Reliability</a></b>
<br>Gage R&R, process capability and Weibull life analysis. Better print settings brought every dimension into spec and made hinges last 6× longer.
<br><sub>Gage R&R · Cp/Cpk · Weibull · Python</sub>
</td>
</tr>
</table>

### Tools

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/meljohnsony2k/rideshare-gst-ledger"><img src="assets/projects/gst.jpg" width="100%" alt="Rideshare GST ledger"></a>
<br><b><a href="https://github.com/meljohnsony2k/rideshare-gst-ledger">Rideshare GST Ledger</a></b>
<br>Offline web tool that turns bank CSV exports into weekly GST working papers, with auto categorisation and a review queue.
<br><sub>HTML · JavaScript · Data processing</sub>
</td>
</tr>
</table>

---

### Toolkit

| Area | Tools |
|---|---|
| **Controls and robotics** | ROS, Gazebo, sensor fusion (UKF, EKF, Kalman), IMU calibration, SLAM, PID and loop shaping, system identification, statecharts, PLC (Ladder, Structured Text) |
| **Automotive** | Vehicle electronics, CAN, DoIP and UDS diagnostics, ECU diagnostics (Toyota Techstream, OBD-II), BMW coding (E-Sys), wiring harness integration |
| **Embedded and software** | C/C++, Arduino, myRIO, Python, MATLAB/Simulink, LabVIEW |
| **Design and manufacturing** | SolidWorks, Fusion 360, AutoCAD, DFM/DFA, tolerance analysis, Gage R&R, reliability analysis |

[LinkedIn](https://linkedin.com/in/meljohnsony2k) · meljohnsony2k@gmail.com · Melbourne, Australia
