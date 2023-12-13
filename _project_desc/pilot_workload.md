---
title: "Pilot Workload Estimation"
permalink: /project_desc/pilot_workload
collection: project_desc
---
<h2>Motivation</h2><br>
With the growing focus on urban air mobility, the development of next-generation air mobility systems has become a paramount area of research. This project is motivated by a semi-autonomous approach, where pilots remain within the aircraft, supported by advanced co-pilot systems to alleviate their workload during flight operations.
To enhance adaptive co-pilot systems, a key aspect is identifying instances when pilots experience high workloads. One way to assess pilots' mental and physical workloads during flight operations is to use various biometric data, such as heart rate, eye gaze, GSR, response time, etc., as inputs to a statistical estimator.
In this project, we are developing a machine learning model to estimate pilots' stress levels using physiological data measured during target flight operations.
<br><br>
<h2>Introduction</h2><br>
Currently I am being involved in the development of a multimodal machine learning model aimed at estimating eVTOL (electric Vertical Take-off & Landing) aircraft pilot workload during various flight operations. As a member of a team consisting of researchers and engineers, we have been collecting multimodal biometric data (including Heart Rate, Eye Gaze, GSR, etc.) from pilots engaged in simulated flights with a VTOL aircraft. Our data collection process includes obtaining ground truth labels for pilot workload, gathered through pilots' self-evaluation using the NASA Task Load Index (TLX) questionnaire. Additionally, we are currently engaged in signal processing of the collected data and working on building a multimodal machine learning feature extraction system to estimate pilot workload. 
<br><br>
<h2>Simulated Flight</h2><br>
One of our objectives is to measure pilots' mental and physical workload during flight maneuvers of VTOLs, the next generation of air mobility. Since this mode of air transportation has barely been commercialized, collecting biometric data while flying inside actual VTOLs is nearly impossible. Furthermore, this could pose a safety hazard, as physiological sensors attached to pilots can be sources of distraction during flights. For this reason, we collected data from pilots while they were flying inside a simulated environment, using Xplane12, a flight simulation game developed by Laminar Research.
<div style="width: 300px; height: 400px; border-radius: 15px; overflow: hidden; text-align: center;">
    <img src="../images/pilot_workload/sim_setup.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: contain;">
</div>
<br><br>
<h2>Data & Sensors</h2><br>
For a more accurate estimation of pilot workload, we chose to collect seven different modalities of physiological data. These include heart rate, galvanic skin response, eye gaze, response time, body pose, brain activity, and grip force. Our experiment set up is inspired by the work presented in <a href = "https://s2.smu.edu/~eclarson/pubs/2021_IMWUTCognitive_Load.pdf">Objective Measures of Cognitive Load Using Deep Multi-Modal Learning: A Use-Case in Aviation (2021)</a>.
<video controls="controls" width="400" height="800">
  <source src="../images/pilot_workload/experiment.MOV">
</video> 
<br>
<h3>Heart Rate</h3><br>
We collected heart rate using a wristband heart rate monitor.
<div style="width: 400px; height: 400px; border-radius: 15px; overflow: hidden; text-align: center;">
    <img src="../images/pilot_workload/e4.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: contain;">
</div>
<br>
<h3>Galvanic Skin Response</h3><br>
We collected galvanic skin response by wrapping electropads around the fingers of the participants. These electropads are connected to a wireless GSR sensor.
<div style="width: 400px; height: 400px; border-radius: 15px; overflow: hidden; text-align: center;">
    <img src="../images/pilot_workload/gsr.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: contain;">
</div>
<br>
<h3>Eye Gaze</h3><br>
We collected the participants' eye gaze using eye-tracking glasses.
<div style="width: 400px; height: 400px; border-radius: 15px; overflow: hidden; text-align: center;">
    <img src="../images/pilot_workload/eyetracking.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: contain;">
</div>
<br>
<h3>Response Time</h3><br>
We collected the participants' response time approximately every 15 seconds by activating a vibration motor attached to their collarbone. Participants were required to press a clicker whenever they felt the vibration.
<div style="width: 400px; height: 400px; border-radius: 15px; overflow: hidden; text-align: center;">
    <img src="../images/pilot_workload/response_time_clicker.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: contain;">
</div>
<br>
<h3>Body Pose</h3><br>
We collected upper body joint poses in 3D spatial coordinates (x, y, z) using an Xbox Kinect camera.
<div style="width: 400px; height: 300px; border-radius: 15px; overflow: hidden; text-align: center;">
    <img src="../images/pilot_workload/kinect.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: contain;">
</div>
<br>
<h3>Brain Activity</h3><br>
We collected brain activity using an fNIR (Functional near-infrared spectroscopy) sensor. This sensor emits non-invasive near-infrared light to estimate cortical hemodynamic activity.
<div style="width: 200px; height: 400px; border-radius: 15px; overflow: hidden; text-align: center;">
    <img src="../images/pilot_workload/fnir.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: contain;">
</div>
<br>
<h3>Grip Force</h3><br>
We collected the participants' grip force during the simulated flight using two individual force-sensing resistor strips attached to the joystick.
<div style="width: 300px; height: 500px; border-radius: 15px; overflow: hidden; text-align: center;">
    <img src="../images/pilot_workload/joystick.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: contain;">
</div>
