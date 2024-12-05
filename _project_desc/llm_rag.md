---
title: "Enhanced Large Language Model System with RAG and Tool Integration"
permalink: /project_desc/llm_rag
collection: project_desc
---

<h2>Motivation</h2><br>
Large Language Models often struggle with mathematical computations and factual accuracy, leading to unreliable outputs in specialized tasks. While base models show impressive general capabilities, they frequently make errors in calculations and fact-based responses. Our project aimed to enhance LLM performance in these critical areas by combining retrieval-augmented generation with specialized tools, while maintaining computational efficiency through parameter-efficient fine-tuning.

<h2>Introduction</h2><br>
<div style="width: 800px; height: 300px; border-radius: 15px; overflow: hidden; text-align: center;">
    <img src="../images/llm_rag_1.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: contain;">
</div>
This project addressed the challenge of improving language model accuracy for specialized tasks, particularly in mathematical computations and factual queries. Our objective was to develop an enhanced LLM system that could effectively combine retrieval-augmented generation with tool usage while maintaining computational efficiency through parameter-efficient fine-tuning techniques.
<br><br>
<h2>Methods</h2><br>
We built the system using the Pythia-1B language model as our foundation, implementing Low-Rank Adaptation (LoRA) for efficient fine-tuning. The architecture integrated a dense retrieval system for accessing relevant information and a specialized calculator tool for handling mathematical operations. The implementation utilized PyTorch for the core model operations and Hugging Face's Transformers library for model management and tokenization. The retrieval system was designed with a hybrid approach, combining dense vector representations for semantic search with structured tools for mathematical processing.

<br><br>
<h2>Results</h2><br>
Performance testing demonstrated significant improvements in model capabilities. We achieved a 30% increase in accuracy across mathematical and factual queries compared to the base model. The LoRA-based fine-tuning approach reduced the training computational requirements by approximately 75% while maintaining performance improvements. The calculator tool integration showed particular effectiveness in mathematical queries, achieving 85% accuracy on arithmetic operations. The dense retrieval component demonstrated consistent performance in surfacing relevant context for factual queries.
 
<br><br>
<h2>Discussion</h2><br>
The project successfully demonstrated the effectiveness of combining multiple enhancement techniques in a single LLM system. Key insights included the importance of careful prompt engineering for tool use, the balance between retrieval quality and computational efficiency, and the effectiveness of LoRA for task-specific adaptations. The approach proved particularly effective for mathematical queries where the calculator tool could be leveraged, while the retrieval system showed strong performance in factual query resolution.
<br><br>

<h2>Role and Contribution</h2><br>
I designed and implemented the RAG architecture, including the dense retrieval system and calculator tool integration. I was responsible for implementing the LoRA fine-tuning process, optimizing the retrieval system parameters, and developing the evaluation framework for measuring accuracy improvements. 
<br><br>
<!-- <div style="width: 800px; height: 500px; border-radius: 15px; overflow: hidden; text-align: center;">
    <img src="../images/RAG/RAG_App.png" alt="Project Image" style="width: 100%; height: 100%; object-fit: contain;">
</div> -->
