---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

### Pilot Workload Estimation via Multimodal Machine Learning
<table style="border: none; border-collapse: collapse;">
    <tr>
        <td style="padding: 10px; border: none;">
            <div style="width: 400px; height: 600px; border-radius: 15px; overflow: hidden;">
                <img src="../images/pilot_workload/sim_setup.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: cover;">
            </div>
        </td>
        <td style="padding: 10px; border: none; vertical-align: top; font-size: 16px;">
            <b>In Progress</b>
            <br>
            <b>This project is sponsored by a research subsidiary of an automotive company.</b>
            <br><br>
            Currently being involved in the development of a multimodal machine learning model aimed at estimating eVTOL (electric Vertical Take-off & Landing) aircraft pilot workload during various flight operations. As a member of a team consisting of researchers and engineers, we have been collecting multimodal biometric data (including Heart Rate, Eye Gaze, GSR, etc.) from pilots engaged in simulated flights with a VTOL aircraft.
            Our data collection process includes obtaining ground truth labels for pilot workload, gathered through pilots' self-evaluation using the NASA Task Load Index (TLX) questionnaire. Additionally, we are currently engaged in signal processing of the collected data and working on building a multimodal machine learning feature extraction system to estimate pilot workload.
            <br>
            <a href = "https://sjhpark.github.io/project_desc/pilot_workload">More</a>
        </td>
    </tr>
</table>
---

### Large Generative Model On-Device Deployment & Optimization
<table style="border: none; border-collapse: collapse;">
    <tr>
        <td style="padding: 10px; border: none;">
            <div style="width: 400px; height: 300px; border-radius: 15px; overflow: hidden;">
                <img src="../images/on_device_ml/jetson1.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: cover;">
            </div>
        </td>
        <td style="padding: 10px; border: none; vertical-align: top; font-size: 16px;">
            <b>Sept - Dec 2023</b>
            <br>
            Deployed and optimized a large generative model (72 million parameters) for a virtual garment try-on system based on the model proposed by <a href = "https://openaccess.thecvf.com/content/CVPR2021/papers/Ge_Parser-Free_Virtual_Try-On_via_Distilling_Appearance_Flows_CVPR_2021_paper.pdf">Parser-Free Virtual Try-on via Distilling Apperance Flows (2021)</a>, on an NVIDIA Jetson Nano 4GB. The model is convolution and residual connection-based, consisting of two sub-models: the Warping model and the Generative model. As a member of a team of five, I was responsible for compressing the model using various techniques such as quantization, pruning, and model knowledge distillation. Additionally, I conducted sensitivity analysis to evaluate each convolution channel and layer concerning compression techniques.
            <br>
            <a href = "https://sjhpark.github.io/project_desc/on_device_ml">More</a> | <a href="https://github.com/sjhpark/Virtual-Try-On-Deployment-Kit.git">GitHub</a>
        </td>
    </tr>
</table>
---

### Cockpit View Segmentation for Adaptive Copilot Systems
<table style="border: none; border-collapse: collapse;">
    <tr>
        <td style="padding: 10px; border: none;">
            <div style="width: 400px; height: 360px; border-radius: 15px; overflow: hidden;">
                <img src="../images/cockpit_view/compare.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: contain;">
            </div>
        </td>
        <td style="padding: 10px; border: none; vertical-align: top; font-size: 16px;">
            <b>Motivation: </b>
            With the growing focus on urban air mobility, the development of next-generation air mobility systems has become
            a paramount area of research. This project is motivated from a semi-autonomous approach, wherein pilots remain within the aircraft, supported by advanced co-pilot systems to alleviate their workload during flight operations.
            To enhance adaptive co-pilot systems, a key aspect is identifying instances when pilots experience high workloads, and one effective
            method for workload assessment is analyzing pilots’ eye gaze. 
            The instance segmentation approach enables a granular understanding of the pilot’s visual focus, contributing valuable insights into workload distribution during different phases of flight.
            <br><br>
            As a member of a team of three, I took charge of custom data collection and preprocessing, and the development, training, and evaluation of the instance segmentation model. I used Detectron2, an open-source object detection and instance segmentation platform provided by FAIR (Facebook AI Research) to train and fine-tune a pre-trained model for instance segmentation.
            <br>
            <a href = "https://sjhpark.github.io/project_desc/cockpit_view">More</a> | <a href="https://github.com/sjhpark/pilotview_segmentation.git">GitHub</a>
        </td>
    </tr>
</table>
---

### Human Facial Emotion Recognition & Classification
<table style="border: none; border-collapse: collapse;">
    <tr>
        <td style="padding: 10px; border: none;">
            <div style="width: 400px; height: 200px; border-radius: 15px; overflow: hidden;">
                <img src="../images/emotion_recog/baseCNN_results.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: cover;">
            </div>
        </td>
        <td style="padding: 10px; border: none; vertical-align: top; font-size: 16px;">
            <b>Very first ML team project</b>
            <br>
            Built a CNN model to recognize and classify human emotions from facial images as a part of a semester-long machine learning team project.
            The objective was to build and train a model that can identify the emotion of a person from its face. As a member of a four person team, 
            I took charge of the data collection and preprocessing. Furthermore, I was responsible for the development, training, and evaluation of the CNN model.
            <br>
            <a href = "https://sjhpark.github.io/project_desc/emotion_recog">More</a> | <a href="https://github.com/sjhpark/Facial_Emotion_Classifier.git">GitHub</a>
        </td>
    </tr>
</table>
---

### Depth Map of Vehicle Stereo Vision Road Views
<table style="border: none; border-collapse: collapse;">
    <tr>
        <td style="padding: 10px; border: none;">
            <div style="width: 400px; height: 400px; border-radius: 15px; overflow: hidden;">
                <img src="https://user-images.githubusercontent.com/83327791/216810695-f6107eef-dbdd-4948-bf83-0a7224d810fe.gif" alt="Project Image" style="width: 100%; height: 50%; object-fit: cover;">
                <img src="https://user-images.githubusercontent.com/83327791/216809049-2ad7d0da-6a2a-4e4c-8ccc-f56f23034872.gif" alt="Project Image" style="width: 100%; height: 50%; object-fit: cover;">
            </div>
        </td>
        <td style="padding: 10px; border: none; vertical-align: top; font-size: 16px;">
            Disparity map is used in conventional computer vision to reconstruct the 3D depth structure of a scene from two stereo vision images (left and right).
            <br>
            In this project, I computed disparity maps from vehicle road view images using KITTI Stereo 2015 dataset.
            <br>
            <a href="https://github.com/sjhpark/Depth-Map.git">GitHub</a>
        </td>
    </tr>
</table>
---
