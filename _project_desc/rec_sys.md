---
title: "Movie Recommendation System for Streaming Platform with One Million Simulated Users"
permalink: /project_desc/rec_sys
collection: project_desc
---

<h2>Motivation</h2><br>
Streaming platforms face a significant challenge: users often struggle to discover relevant content within vast libraries of movies and shows. This can lead to poor user engagement and satisfaction. Our project aimed to solve this content discovery problem by developing a personalized recommendation system that could effectively connect users with content they're likely to enjoy, thereby improving the overall streaming experience and platform engagement.
<h2>Introduction</h2><br>
<div style="width: 800px; height: 300px; border-radius: 15px; overflow: hidden; text-align: center;">
    <img src="../images/RAG/Q&A_pipeline.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: contain;">
</div>
This project addresses the growing need for personalized content discovery in streaming platforms, where users often struggle to find relevant content among vast libraries. Our objective was to develop and deploy a scalable movie recommendation system that could effectively serve personalized suggestions to a user base of one million simulated users while maintaining system reliability and performance.
<br><br>
<h2>Methods</h2><br>
The recommendation system was implemented using collaborative filtering with matrix factorization techniques, specifically utilizing the Alternating Least Squares (ALS) algorithm. The data preprocessing pipeline was designed to handle various user-movie interactions, including views, ratings, and watch time metrics. The deployment infrastructure was built around a Jenkins-based CI/CD pipeline that automated testing and deployment processes. We containerized our model serving using Docker to ensure consistent behavior across different environments. We implemented comprehensive metrics collection through Prometheus for system observability and created detailed Grafana dashboards for real-time monitoring and alerting.
<br><br>
<h2>Results</h2><br>
Through rigorous A/B testing, the system demonstrated meaningful improvements up to 30% in user engagement metrics. We observed a 15% increase in average watch time per user and a downward trend in users' time selecting content. The infrastructure maintained 99.9% model serving availability throughout the testing period, with recommendation generation consistently staying under 100ms response time. 
<br><br>
<h2>Discussion</h2><br>
The project delivered a production-ready recommendation system with robust monitoring and deployment infrastructure. During implementation, we learned the critical importance of thorough feature engineering for improving recommendation quality. The comprehensive monitoring system proved invaluable for early detection of model drift, while our zero-downtime deployment strategy enabled continuous model updates without service interruption. Regular A/B testing provided concrete validation of improvements and guided further optimization efforts.
<br><br>
<!-- <div style="width: 800px; height: 500px; border-radius: 15px; overflow: hidden; text-align: center;">
    <img src="../images/RAG/RAG_App.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: contain;">
</div> -->
