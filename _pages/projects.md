---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## Movie Recommendation System for Streaming Platform with One Million Simulated Users
<table style="border: none; border-collapse: collapse;">
    <tr>
        <td style="padding: 0px; border: none;">
            <div style="width: 900px; height: 350px; border-radius: 15px; overflow: visible; text-align: center;">
                <img src="../images/RAG/Q&A_pipeline.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: contain;">
            </div>
        </td>
    </tr>
    <tr>
        <td style="padding: 10px; border: none; vertical-align: top; font-size: 16px;">
            <!-- <b>Jan 2024 - Present</b><br> -->
            We developed and deployed a scalable movie recommendation system for a streaming platform, handling one million simulated users through collaborative filtering with matrix factorization techniques. The system achieved an 18% improvement in engagement metrics through comprehensive A/B testing, validated through increased watch time and reduced content selection time. We architected a robust MLOps infrastructure utilizing Jenkins for CI/CD pipelines, containerized model serving with Docker for zero-downtime deployments, and implemented extensive monitoring using Prometheus and Grafana dashboards for real-time system health and model performance tracking. The project demonstrated both technical depth in machine learning implementation and practical engineering skills in building production-ready systems that maintain high availability and performance standards.
            <br>
            <a href = "https://tartan-ishan.github.io/website/project_desc/RAG">More</a> 
        </td>
    </tr>
</table>
---

## Enhanced Large Language Model System with RAG and Tool Integration
<table style="border: none; border-collapse: collapse;">
    <tr>
        <td style="padding: 10px; border: none;">
            <div style="width: 400px; height: 600px; border-radius: 15px; overflow: hidden;">
                <img src="../images/pilot_workload/sim_setup.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: cover;">
            </div>
        </td>
        <td style="padding: 10px; border: none; vertical-align: top; font-size: 16px;">
            <br><br>
            Engineered a retrieval-augmented generation (RAG) system using the Pythia-1B model as our foundation, implementing LoRA-based parameter-efficient fine-tuning. The system integrated a calculator tool and dense retrieval capabilities to enhance performance on mathematical and factual queries. By combining these approaches with custom prompt engineering and optimization techniques, we achieved a 30% improvement in accuracy across target tasks. The implementation utilized PyTorch and Hugging Face's Transformers library, incorporating efficient training strategies that reduced computational requirements by 75% while maintaining performance gains. The resulting system demonstrated particularly strong performance in mathematical operations with 85% accuracy, while the dense retrieval component effectively surfaced relevant context for factual queries. CopyRetry
            <br>
            <a href = "https://tartan-ishan.github.io/website/project_desc/llm_rag">More</a>
        </td>
    </tr>
</table>
---

## Human Segmentation Pipeline for Videos in PyTorch 
<table style="border: none; border-collapse: collapse;">
    <tr>
        <td style="padding: 10px; border: none;">
            <div style="width: 400px; height: 300px; border-radius: 15px; overflow: hidden;">
                <img src="../images/on_device_ml/jetson1.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: cover;">
            </div>
        </td>
        <td style="padding: 10px; border: none; vertical-align: top; font-size: 16px;">
            Developed an end-to-end computer vision pipeline for human segmentation in videos, integrating insights from extensive research across 10+ papers. The system combined transformer and CNN architectures to achieve high-accuracy segmentation, incorporating portrait matting, multi-class body part segmentation, and anatomical landmark detection. Through targeted data augmentation on 200,000+ images and custom loss function implementation, we achieved a 15% improvement in segmentation accuracy. Video segmentation performance was enhanced by 30% using quantization-aware training and a custom detect-and-track system for improved temporal consistency. We leveraged TensorBoard and Weights & Biases for comprehensive performance monitoring and visualization throughout the development process. The resulting pipeline demonstrated robust performance across diverse scenarios while maintaining real-time processing capabilities.
            <br>
            <a href = "https://tartan-ishan.github.io/website/project_desc/segmentation">More</a>
        </td>
    </tr>
</table>
---

## Real-Time 6-DoF Pose Estimation for Novel Objects
<table style="border: none; border-collapse: collapse;">
    <tr>
        <td style="padding: 10px; border: none;">
            <div style="width: 400px; height: 360px; border-radius: 15px; overflow: hidden;">
                <img src="../images/cockpit_view/compare.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: cover;">
            </div>
        </td>
        <td style="padding: 10px; border: none; vertical-align: top; font-size: 16px;">
            Developed a real-time 6-DoF pose estimation pipeline for novel objects with no prior training data, achieving 85% accuracy through innovative synthetic data generation and domain adaptation strategies. Using platforms like Nvidia Isaac Sim and Blender, we created photorealistic training datasets with domain randomization to enhance generalization. The system bridged the synthetic-to-real domain gap through adversarial domain adaptation fine-tuning on limited real-world data. Through TensorRT optimization, we reduced both memory footprint and inference time by 60%, making the system suitable for edge deployment. The resulting pipeline demonstrated robust performance across varying environmental conditions while maintaining real-time processing capabilities.
            <br>
            <a href = "https://tartan-ishan.github.io/website/project_desc/pose">More</a>
        </td>
    </tr>
</table>
