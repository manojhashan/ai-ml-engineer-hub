<div align="center">

# AI/ML Engineer Hub

### From your first Python program to production AI systems

**A practical AI & Machine Learning engineering roadmap with clear learning steps, project ideas and progress checklists.**

![Phases: 18](https://img.shields.io/badge/Phases-18-2563eb?style=flat-square)
![Subtopics: 409](https://img.shields.io/badge/Subtopics-409-7c3aed?style=flat-square)
![Learning: Project based](https://img.shields.io/badge/Learning-Project%20based-059669?style=flat-square)
![Format: Markdown](https://img.shields.io/badge/Format-Markdown-475569?style=flat-square)

[Start here](#start-here) · [Explore the roadmap](#roadmap-at-a-glance) · [Choose a path](#choose-your-path) · [Track progress](#track-your-progress) · [Add resources](#resources-and-contributions)

</div>

---

## What is this repository?

AI/ML Engineer Hub organizes a broad AI engineering curriculum into **18 phases and 409 subtopic entries**, from mathematics and Python to machine learning, deep learning, LLMs, RAG, agents and production systems.

Use it to answer three questions: **What should I learn? What should I build? How do I know I understand it?** Each phase has a purpose, prerequisites, a completion checkpoint and project ideas. Expand its checklist to see the full topic list.

> **සිංහලෙන්:** AI/ML ඉගෙනගන්න පටන්ගන්නේ කොතැනින්ද, ඊළඟට ඉගෙනගන්නේ මොනවාද, ඒ දේවල්වලින් හදන්න පුළුවන් projects මොනවාද කියලා මේ roadmap එකෙන් බලන්න පුළුවන්. මුලින් Python සහ අවශ්‍ය Maths ඉගෙනගෙන කුඩා project එකක් හදන්න. හැම topic එකම ඉවර වෙනකම් ඉන්න අවශ්‍ය නැහැ.

**Current scope:** the complete topic checklist and project suggestions are available below. Individual subtopic YouTube resources are still to be curated. Projects are suggestions to build; completed implementations are not included in this repository yet.

## Start here

1. **Find your starting point.** New to programming? Begin with Phase 03 and revise Phase 01 as needed. Already comfortable with Python? Try Phase 04's completion checkpoint.
2. **Learn mathematics alongside code.** Work through the relevant parts of Phase 02 while implementing small Python examples.
3. **Use engineering habits early.** Learn Git, the command line, virtual environments and debugging from Phases 03 and 15 as soon as you start a project.
4. **Learn one topic at a time.** Write a short explanation in your own words and practise without copying a tutorial.
5. **Build and evaluate.** Complete a small project, inspect its failures and document what you learned before adding more tools.
6. **Record your progress.** Fork the repository or keep your own copy and edit `[ ]` to `[x]` as you complete topics.

> The phase numbers preserve the source roadmap's organization. They are a guide, not a requirement to master every earlier topic before moving forward. Computer vision, NLP and advanced production topics can be studied selectively.

### Your first learning milestone

Build a **student marks calculator** that accepts marks, validates input, calculates averages and saves a report. Use functions, handle invalid input and write instructions explaining how to run it. This brings together basic mathematics, Python and Git without requiring an ML framework.

### A repeatable study cycle

**Learn → Practise → Build → Evaluate → Explain → Revisit**

A topic is ready to check off when you can explain it simply, implement a small example and describe a common mistake. Watching a video is a starting point.

## Roadmap at a glance

Select a phase to jump to its purpose, projects and expandable checklist.

| Phase | Area | Main focus | Subtopics |
| :---: | --- | --- | :---: |
| 01 | [Basic Mathematics](#phase-01) | Numbers, equations and graphs | 8 |
| 02 | [Mathematics for Machine Learning](#phase-02) | Vectors, calculus, probability and optimization | 31 |
| 03 | [Python Programming Fundamentals](#phase-03) | Programming, data structures and debugging | 28 |
| 04 | [Python for Data Science](#phase-04) | Cleaning, exploring and visualizing data | 13 |
| 05 | [SQL & Databases](#phase-05) | Queries, joins and database design | 15 |
| 06 | [Machine Learning](#phase-06) | Models, validation and evaluation | 39 |
| 07 | [Deep Learning](#phase-07) | Neural networks and training | 29 |
| 08 | [Computer Vision](#phase-08) | Images, detection and segmentation | 15 |
| 09 | [Natural Language Processing](#phase-09) | Text processing and representations | 20 |
| 10 | [Generative AI & LLMs](#phase-10) | Language model applications and adaptation | 26 |
| 11 | [RAG Systems](#phase-11) | Document retrieval and grounded answers | 26 |
| 12 | [Agentic AI](#phase-12) | Tool use, state and workflows | 24 |
| 13 | [MCP (Model Context Protocol)](#phase-13) | Connecting applications to tools and data | 13 |
| 14 | [AI Backend Development](#phase-14) | APIs, validation and inference | 23 |
| 15 | [Software Engineering & DevOps](#phase-15) | Git, testing, containers and delivery | 25 |
| 16 | [MLOps & LLMOps](#phase-16) | Tracking, pipelines and monitoring | 22 |
| 17 | [Cloud Computing](#phase-17) | Infrastructure and managed AI services | 17 |
| 18 | [Advanced AI Engineering](#phase-18) | System design and responsible AI | 35 |

## Choose your path

All paths share a foundation. Pick a specialization after you can write Python, analyze a dataset and evaluate a basic ML model.

| Goal | Suggested route | Portfolio milestone |
| --- | --- | --- |
| Start from zero | 01 + 03, then essential 02, then 04-06 | Data analysis and a baseline prediction model |
| ML engineering | Foundation, then 06, 14-16 and one cloud from 17 | A tested API with reproducible training |
| Computer vision | Foundation, then 07-08 and relevant 14-16 | An image application with failure analysis |
| NLP and language models | Foundation, relevant 07 + 09, then 10 | A text application with evaluation examples |
| GenAI application engineering | Foundation, then 10-11, 14-15 and 12 when needed | A document assistant with citations and evaluation |
| Production AI systems | Your specialization, then 14-17 and relevant 18 | A system with monitoring and a documented design |

**Foundation** means practical Python, essential mathematics, data preparation and basic ML evaluation. Bring backend and Git skills forward whenever your project needs them. MCP in Phase 13 is an optional extension for projects that need it.

## Understand the level labels

| Label | How to approach it |
| --- | --- |
| **B - Beginner** | Learn the idea and practise a small example. |
| **I - Intermediate** | Apply the idea in a project and evaluate the result. |
| **A - Advanced** | Explore deeper implementation, research or production tradeoffs when needed. |

The checklist retains the spreadsheet's original labels: **48 Beginner, 177 Intermediate and 184 Advanced entries**. They are rough guidance; some introductory skills appear in later phases or carry advanced labels. Use the prerequisites and learning notes to decide when to study them. Repeated concepts are revisited in different contexts, so 409 counts entries rather than unique concepts.

---

## The complete roadmap

<a id="phase-01"></a>

### Phase 01 · Basic Mathematics

Build confidence with the numbers, equations and graphs used throughout AI and machine learning.

**Before you start:** No prior programming experience.

**Learning note:** Start here if school mathematics feels unfamiliar. Practise with small examples before moving on.

**Completion checkpoint:** Explain a function, rearrange a simple equation and calculate percentages.

<details>
<summary><strong>Open the learning checklist · 8 subtopics</strong></summary>

#### Basic Mathematics

- [ ] Basic Arithmetic — **B**
- [ ] Fractions & Percentages — **B**
- [ ] Algebra — **B**
- [ ] Equations & Inequalities — **B**
- [ ] Functions & Graphs — **B**
- [ ] Exponents & Logarithms — **B**
- [ ] Basic Geometry — **B**
- [ ] Basic Trigonometry — **B**

</details>

**Project ideas**

- Math practice notebook
- Student marks calculator

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-02"></a>

### Phase 02 · Mathematics for Machine Learning

Understand the mathematics behind model predictions, training and evaluation.

**Before you start:** Phase 01; learn alongside Phase 03 to turn ideas into code.

**Learning note:** Start with vectors, descriptive statistics, probability and derivatives. Return to advanced mathematics when a project needs it.

**Completion checkpoint:** Explain vectors, derivatives, probability and gradient descent with worked examples.

<details>
<summary><strong>Open the learning checklist · 31 subtopics</strong></summary>

#### Linear Algebra

- [ ] Vectors — **I**
- [ ] Matrices — **B**
- [ ] Matrix Multiplication — **I**
- [ ] Dot Product — **B**
- [ ] Transpose & Inverse — **B**
- [ ] Eigenvalues & Eigenvectors — **A**

#### Calculus

- [ ] Limits — **B**
- [ ] Derivatives — **I**
- [ ] Partial Derivatives — **A**
- [ ] Chain Rule — **A**
- [ ] Gradients — **A**

#### Probability

- [ ] Basic Probability — **I**
- [ ] Conditional Probability — **I**
- [ ] Bayes' Theorem — **B**
- [ ] Probability Distributions — **I**

#### Statistics

- [ ] Mean, Median & Mode — **B**
- [ ] Variance & Standard Deviation — **B**
- [ ] Normal Distribution — **B**
- [ ] Sampling — **B**
- [ ] Hypothesis Testing — **B**
- [ ] Correlation & Covariance — **B**
- [ ] Covariance — **B**

#### Optimization

- [ ] Cost / Loss Functions — **B**
- [ ] Gradient Descent — **B**
- [ ] Learning Rate — **B**
- [ ] Local & Global Minima — **B**

#### Information Theory

- [ ] Entropy — **B**
- [ ] Cross-Entropy — **B**
- [ ] KL Divergence — **A**

#### Applied Mathematics

- [ ] Discrete Mathematics — **B**
- [ ] Numerical Methods — **A**

</details>

**Project ideas**

- Linear algebra visualizer
- Probability simulation
- Gradient descent from scratch
- Gradient Descent Visualizer
- Probability & Statistics Simulation

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-03"></a>

### Phase 03 · Python Programming Fundamentals

Write, debug and organize Python programs before using ML libraries.

**Before you start:** Basic computer skills; Phase 01 can be studied in parallel.

**Learning note:** Complete the basics first. Study concurrency, design patterns and memory topics after building a few programs.

**Completion checkpoint:** Build a program with functions, file handling and error handling, and explain how it works.

<details>
<summary><strong>Open the learning checklist · 28 subtopics</strong></summary>

#### Python Basics

- [ ] Syntax — **B**
- [ ] Variables & Data Types — **B**
- [ ] Operators — **B**
- [ ] Conditional Statements — **B**
- [ ] Loops — **I**
- [ ] Functions — **B**

#### Python Data Structures

- [ ] Strings — **B**
- [ ] Lists — **B**
- [ ] Tuples — **B**
- [ ] Sets — **B**
- [ ] Dictionaries — **B**
- [ ] List Comprehensions — **B**

#### Programming Concepts

- [ ] File Handling — **B**
- [ ] Exception Handling — **B**
- [ ] OOP — **I**
- [ ] Modules & Packages — **B**
- [ ] Lambda Functions — **B**
- [ ] Virtual Environments — **B**

#### Developer Basics

- [ ] Debugging — **B**
- [ ] Working with JSON — **I**
- [ ] HTTP & API Basics — **I**
- [ ] pip & Package Management — **B**

#### Computer Science Fundamentals

- [ ] Data Structures & Algorithms (DSA) — **B**
- [ ] Time & Space Complexity (Big O) — **A**

#### Advanced Python

- [ ] Memory Management — **B**
- [ ] Multithreading & Multiprocessing — **A**
- [ ] Design Patterns — **A**
- [ ] Clean Code Principles — **B**

</details>

**Project ideas**

- Student Management System
- Expense Tracker
- File Organizer
- Algorithm Visualizer
- Concurrent API Data Fetcher

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-04"></a>

### Phase 04 · Python for Data Science

Turn raw datasets into clean tables, useful visualizations and clear findings.

**Before you start:** Phase 03 basics and basic statistics from Phase 02.

**Learning note:** Document every cleaning decision. Keep an untouched copy of the original data.

**Completion checkpoint:** Clean a dataset, create useful plots and explain your findings in a notebook.

<details>
<summary><strong>Open the learning checklist · 13 subtopics</strong></summary>

#### Python Libraries

- [ ] NumPy — **I**
- [ ] Pandas — **I**
- [ ] Matplotlib — **I**
- [ ] Seaborn — **I**

#### Data Preparation

- [ ] Data Loading — **I**
- [ ] Data Cleaning — **I**
- [ ] Missing Value Handling — **I**
- [ ] Outlier Detection — **I**
- [ ] Data Transformation — **I**

#### Data Analysis

- [ ] Exploratory Data Analysis (EDA) — **I**
- [ ] Descriptive Statistics — **I**
- [ ] Data Visualization — **I**
- [ ] Feature Relationships — **I**

</details>

**Project ideas**

- Sales Data Analysis
- Student Performance Analysis
- Netflix Dataset EDA

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-05"></a>

### Phase 05 · SQL & Databases

Store, query and combine data for analysis and applications.

**Before you start:** Basic Python and an understanding of rows and columns.

**Learning note:** Choose one relational database first. Other database engines are alternatives to explore later.

**Completion checkpoint:** Design a small database and answer questions using joins, grouping and a window function.

<details>
<summary><strong>Open the learning checklist · 15 subtopics</strong></summary>

#### SQL Fundamentals

- [ ] Database Concepts — **I**
- [ ] SELECT / WHERE — **I**
- [ ] ORDER BY — **I**
- [ ] GROUP BY / HAVING — **I**
- [ ] INSERT / UPDATE / DELETE — **I**

#### Intermediate SQL

- [ ] INNER / LEFT / RIGHT JOIN — **I**
- [ ] Subqueries — **I**
- [ ] Common Table Expressions (CTEs) — **I**
- [ ] Window Functions — **I**
- [ ] Indexes — **I**

#### Database Development

- [ ] Relational Database Design — **I**
- [ ] Normalization — **I**
- [ ] PostgreSQL — **I**
- [ ] MySQL — **I**
- [ ] MongoDB Basics — **I**

</details>

**Project ideas**

- Student Database
- E-commerce Database
- Sales Reporting Database

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-06"></a>

### Phase 06 · Machine Learning

Build baseline models, evaluate them fairly and improve them with evidence.

**Before you start:** Phases 02-04; SQL is useful for real datasets.

**Learning note:** Learn splitting and leakage prevention before tuning. Fit preprocessing and resampling on training data only.

**Completion checkpoint:** Compare models on suitable validation data and report metrics on an untouched test set.

<details>
<summary><strong>Open the learning checklist · 39 subtopics</strong></summary>

#### ML Fundamentals

- [ ] AI vs ML vs Deep Learning — **I**
- [ ] Supervised Learning — **I**
- [ ] Unsupervised Learning — **I**
- [ ] Reinforcement Learning Basics — **I**
- [ ] Scikit-learn Workflow — **I**

#### Supervised Algorithms

- [ ] Linear Regression — **I**
- [ ] Polynomial Regression — **I**
- [ ] Logistic Regression — **I**
- [ ] K-Nearest Neighbors — **I**
- [ ] Naive Bayes — **I**
- [ ] Decision Trees — **I**
- [ ] Random Forest — **I**
- [ ] Support Vector Machines — **I**

#### Unsupervised Algorithms

- [ ] K-Means Clustering — **I**
- [ ] Hierarchical Clustering — **I**
- [ ] DBSCAN — **I**
- [ ] Principal Component Analysis (PCA) — **I**

#### Model Development

- [ ] Data Preprocessing — **I**
- [ ] Feature Engineering — **I**
- [ ] Feature Selection — **I**
- [ ] Train / Validation / Test Split — **I**
- [ ] Cross Validation — **I**
- [ ] Hyperparameter Tuning — **I**
- [ ] Ensemble Learning — **I**
- [ ] Imbalanced Dataset Handling — **I**
- [ ] SMOTE — **A**
- [ ] Data Leakage Prevention — **I**
- [ ] Model Calibration — **A**
- [ ] Threshold Optimization — **A**
- [ ] Time Series Forecasting — **A**
- [ ] Recommendation Systems — **A**

#### Evaluation

- [ ] Confusion Matrix — **I**
- [ ] Accuracy / Precision / Recall / F1 — **I**
- [ ] ROC-AUC — **I**
- [ ] MAE / MSE / RMSE / R² — **I**
- [ ] Overfitting & Underfitting — **I**

#### Explainable AI

- [ ] Explainable AI (XAI) — **I**
- [ ] SHAP — **A**
- [ ] LIME — **A**

</details>

**Project ideas**

- House Price Prediction
- Customer Churn Prediction
- Customer Segmentation
- Loan Approval Prediction
- Time Series Forecasting
- Explainable Churn Prediction
- Recommendation Engine

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-07"></a>

### Phase 07 · Deep Learning

Understand neural networks and train them with a deep learning framework.

**Before you start:** Phase 06, Python, vectors, gradients and the chain rule.

**Learning note:** Choose one framework first. Distributed training and advanced generative architectures can wait.

**Completion checkpoint:** Train a small neural network, inspect training curves and explain how you reduced overfitting.

<details>
<summary><strong>Open the learning checklist · 29 subtopics</strong></summary>

#### Neural Network Fundamentals

- [ ] Perceptron — **I**
- [ ] Neurons & Layers — **I**
- [ ] Activation Functions — **I**
- [ ] Forward Propagation — **I**
- [ ] Loss Functions — **I**
- [ ] Backpropagation — **A**
- [ ] Gradient Descent & Optimizers — **I**

#### Training Techniques

- [ ] Learning Rate — **I**
- [ ] Regularization — **I**
- [ ] Dropout — **I**
- [ ] Batch Normalization — **I**
- [ ] Early Stopping — **I**
- [ ] Data Augmentation — **I**

#### Deep Learning Architectures

- [ ] Artificial Neural Networks (ANN) — **I**
- [ ] Convolutional Neural Networks (CNN) — **I**
- [ ] RNN — **I**
- [ ] LSTM & GRU — **I**
- [ ] Autoencoders — **I**
- [ ] Transfer Learning — **I**

#### Frameworks

- [ ] PyTorch — **I**
- [ ] TensorFlow — **I**
- [ ] Keras — **I**

#### Advanced Architectures

- [ ] Attention Mechanism — **I**
- [ ] Transformer Architecture — **A**
- [ ] Generative Adversarial Networks (GANs) — **A**
- [ ] Diffusion Models — **A**
- [ ] Self-Supervised Learning — **A**

#### Performance

- [ ] GPU Computing & CUDA Basics — **A**
- [ ] Distributed Training — **A**

</details>

**Project ideas**

- MNIST Digit Classifier
- Cat vs Dog Classifier
- Plant Disease Detection
- Transformer from Scratch (small scale)
- Image Generation Experiment

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-08"></a>

### Phase 08 · Computer Vision

Work with images and video through classification, detection and segmentation.

**Before you start:** Phase 07, especially CNNs and transfer learning.

**Learning note:** This is a specialization. Choose it when your projects involve images or video.

**Completion checkpoint:** Evaluate an image model on held-out examples and inspect the cases where it fails.

<details>
<summary><strong>Open the learning checklist · 15 subtopics</strong></summary>

#### Image Processing

- [ ] Image Representation & Color Spaces — **I**
- [ ] Filtering & Edge Detection — **I**
- [ ] Thresholding — **I**
- [ ] Image Transformations — **I**
- [ ] OpenCV — **I**

#### Computer Vision Tasks

- [ ] Image Classification — **I**
- [ ] Object Detection — **I**
- [ ] Image Segmentation — **I**
- [ ] Face Detection — **I**
- [ ] Object Tracking — **I**
- [ ] OCR — **I**

#### Modern CV Models

- [ ] YOLO — **I**
- [ ] Transfer Learning for Vision — **I**
- [ ] Vision Transformers (ViT) — **A**
- [ ] Model Evaluation & mAP — **I**

</details>

**Project ideas**

- Helmet Detection System
- Real-time YOLO Object Detection
- PPE Detection System
- License Plate OCR

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-09"></a>

### Phase 09 · Natural Language Processing

Represent text and build systems that classify, compare and extract information.

**Before you start:** Phase 06; Phase 07 before transformer-based work.

**Learning note:** Learn text preprocessing and evaluation before moving to large transformer models.

**Completion checkpoint:** Evaluate a text classifier and compare a simple baseline with a stronger representation.

<details>
<summary><strong>Open the learning checklist · 20 subtopics</strong></summary>

#### Text Processing

- [ ] Text Cleaning — **I**
- [ ] Tokenization — **I**
- [ ] Stemming & Lemmatization — **I**
- [ ] Stop Words — **I**
- [ ] Bag of Words — **I**
- [ ] TF-IDF — **I**

#### NLP Tasks

- [ ] Text Classification — **I**
- [ ] Sentiment Analysis — **I**
- [ ] Named Entity Recognition (NER) — **I**
- [ ] Text Similarity — **I**
- [ ] Text Summarization — **I**

#### Language Representations

- [ ] Word Embeddings — **I**
- [ ] Word2Vec — **I**
- [ ] GloVe — **I**
- [ ] Sequence Models — **I**
- [ ] Attention Mechanism — **I**

#### Transformers

- [ ] Transformer Architecture — **A**
- [ ] BERT — **I**
- [ ] GPT Concepts — **I**
- [ ] Hugging Face Transformers — **A**

</details>

**Project ideas**

- Spam Classifier
- Fake News Detection
- Sentiment Analysis
- Resume Classifier

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-10"></a>

### Phase 10 · Generative AI & LLMs

Build applications around language models and understand adaptation and evaluation.

**Before you start:** Python, basic NLP and transformer concepts; Phase 14 API basics alongside this phase.

**Learning note:** Begin with one model and one use case. Fine-tuning and multimodal work are later extensions.

**Completion checkpoint:** Build an LLM application with structured results, an evaluation set and measured cost and latency.

<details>
<summary><strong>Open the learning checklist · 26 subtopics</strong></summary>

#### LLM Fundamentals

- [ ] Generative AI Concepts — **I**
- [ ] Large Language Models — **I**
- [ ] Transformer Architecture Review — **A**
- [ ] Tokens & Tokenization — **I**
- [ ] Context Windows — **I**

#### Working with LLMs

- [ ] Prompt Engineering — **I**
- [ ] System / User Prompts — **I**
- [ ] Zero-shot & Few-shot Prompting — **I**
- [ ] LLM APIs — **I**
- [ ] Streaming Responses — **I**
- [ ] Function / Tool Calling — **I**

#### Models & Adaptation

- [ ] Hugging Face Hub — **I**
- [ ] Open-source LLMs — **I**
- [ ] Fine-tuning — **A**
- [ ] LoRA & QLoRA — **I**
- [ ] LLM Evaluation — **I**
- [ ] Safety & Guardrails — **I**

#### Advanced LLM Engineering

- [ ] LLM Quantization — **A**
- [ ] Model Distillation — **A**
- [ ] Parameter-Efficient Fine-Tuning (PEFT) — **A**
- [ ] Structured Outputs — **I**
- [ ] Multimodal AI — **A**
- [ ] Vision Language Models (VLMs) — **A**
- [ ] Speech-to-Text (STT) — **I**
- [ ] Text-to-Speech (TTS) — **I**
- [ ] LLM Evaluation Frameworks — **I**

</details>

**Project ideas**

- LLM Chatbot
- AI Resume Analyzer
- AI Email Assistant
- Document Summarizer
- Multimodal AI Assistant
- Fine-tuned Domain Chatbot

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-11"></a>

### Phase 11 · RAG Systems

Connect language models to documents and evaluate retrieval as well as answers.

**Before you start:** Phase 10, embeddings and basic application development.

**Learning note:** Start with a small, known document collection. Inspect retrieved chunks before adding infrastructure.

**Completion checkpoint:** Build a document assistant with citations and test whether retrieval finds the evidence needed to answer.

<details>
<summary><strong>Open the learning checklist · 26 subtopics</strong></summary>

#### RAG Foundations

- [ ] RAG Architecture — **A**
- [ ] Document Loading — **A**
- [ ] Text Extraction — **A**
- [ ] Chunking Strategies — **A**
- [ ] Metadata — **A**

#### Retrieval Components

- [ ] Embeddings — **I**
- [ ] Vector Search — **I**
- [ ] Similarity Metrics — **A**
- [ ] Vector Databases: FAISS / ChromaDB / Pinecone — **I**

#### RAG Frameworks

- [ ] LangChain — **A**
- [ ] LlamaIndex — **A**
- [ ] Retrievers — **A**
- [ ] Hybrid Search — **A**
- [ ] Reranking — **A**

#### Advanced RAG

- [ ] Query Rewriting — **A**
- [ ] Metadata Filtering — **A**
- [ ] Context Compression — **A**
- [ ] RAG Evaluation — **A**
- [ ] Retrieval Optimization — **A**

#### Advanced Retrieval

- [ ] Semantic Search — **A**
- [ ] Parent-Child Retrieval — **A**
- [ ] Knowledge Graph RAG — **A**
- [ ] Graph-based Retrieval — **A**
- [ ] Contextual Retrieval — **A**
- [ ] RAGAS Evaluation — **A**
- [ ] Multimodal RAG — **A**

</details>

**Project ideas**

- PDF Chatbot with citations
- University Knowledge Assistant
- Company Knowledge Assistant
- Knowledge Graph RAG Assistant
- RAG Evaluation Benchmark

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-12"></a>

### Phase 12 · Agentic AI

Build tool-using workflows with explicit state, permissions and evaluation.

**Before you start:** Phase 10; Phase 11 for document-based agents; Phase 14 API basics.

**Learning note:** Start with a single agent or deterministic workflow. Add multiple agents when a measured need appears.

**Completion checkpoint:** Build a bounded workflow, test tool failures and add human approval for consequential actions.

<details>
<summary><strong>Open the learning checklist · 24 subtopics</strong></summary>

#### Agent Fundamentals

- [ ] AI Agent Concepts — **A**
- [ ] Agent Architecture — **A**
- [ ] Reasoning & Planning — **A**
- [ ] ReAct Pattern — **A**
- [ ] Tool Calling — **A**
- [ ] Memory — **A**

#### Agent Frameworks

- [ ] LangGraph — **A**
- [ ] CrewAI — **A**
- [ ] AutoGen / Microsoft Agent Framework — **A**

#### Agent Workflows

- [ ] Single-Agent Workflows — **A**
- [ ] Multi-Agent Systems — **A**
- [ ] Human-in-the-loop — **I**
- [ ] Agent Evaluation — **A**
- [ ] Agentic RAG — **A**
- [ ] Safety & Permissions — **A**

#### Advanced Agent Engineering

- [ ] Agent Planning — **A**
- [ ] Reflection & Self-Correction — **A**
- [ ] Agentic Workflow Patterns — **A**
- [ ] State Management — **A**
- [ ] Long-term Memory — **A**
- [ ] Agent Observability — **A**
- [ ] Agent Security — **A**
- [ ] Agent Testing & Evaluation — **A**
- [ ] Human Approval Workflows — **A**

</details>

**Project ideas**

- AI Research Agent
- Multi-Agent Research System
- AI Travel Planner
- AI Coding Assistant
- Human-approved Workflow Agent
- Agent Evaluation Test Suite

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-13"></a>

### Phase 13 · MCP (Model Context Protocol)

Understand how AI applications connect to tools and data through Model Context Protocol.

**Before you start:** Phase 12 concepts, Python and backend authentication basics.

**Learning note:** Learn protocol concepts before choosing a framework. Check current official specifications when implementing.

**Completion checkpoint:** Build a small MCP server, connect a client and test authorized and rejected tool requests.

<details>
<summary><strong>Open the learning checklist · 13 subtopics</strong></summary>

#### MCP Fundamentals

- [ ] What MCP Solves — **A**
- [ ] MCP Architecture — **A**
- [ ] Hosts, Clients & Servers — **A**
- [ ] Transport Concepts — **A**

#### MCP Building Blocks

- [ ] Tools — **A**
- [ ] Resources — **A**
- [ ] Prompts — **I**
- [ ] Tool Discovery & Invocation — **A**

#### MCP Development

- [ ] Build MCP Server with Python — **A**
- [ ] Build / Connect an MCP Client — **A**
- [ ] Integrate MCP with Agents — **A**
- [ ] Authentication & Authorization — **A**
- [ ] Security Best Practices — **A**

</details>

**Project ideas**

- GitHub MCP Assistant
- Database MCP Server
- Local File Assistant using MCP

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-14"></a>

### Phase 14 · AI Backend Development

Expose AI functionality through validated, documented and secure APIs.

**Before you start:** Phase 03, HTTP basics and a working model or AI feature.

**Learning note:** Learn basic endpoints early when a project needs them. GPU inference optimization belongs much later.

**Completion checkpoint:** Serve predictions or answers through an API with validation, error handling and tests.

<details>
<summary><strong>Open the learning checklist · 23 subtopics</strong></summary>

#### Web Fundamentals

- [ ] HTTP / HTTPS — **A**
- [ ] Request & Response — **A**
- [ ] REST API Principles — **I**
- [ ] JSON — **I**
- [ ] Status Codes — **A**

#### Python Backend

- [ ] FastAPI — **I**
- [ ] Flask Basics — **I**
- [ ] Pydantic — **A**
- [ ] Dependency Injection — **A**
- [ ] Async Python — **A**
- [ ] WebSockets — **A**

#### API Security & Integration

- [ ] Authentication — **A**
- [ ] JWT — **A**
- [ ] OAuth 2.0 Basics — **A**
- [ ] API Keys & Secrets — **I**
- [ ] External API Integration — **I**
- [ ] API Documentation — **I**

#### Production API Engineering

- [ ] Rate Limiting — **A**
- [ ] API Security — **I**
- [ ] Secrets Management — **A**
- [ ] Batch Inference — **A**
- [ ] Real-time Inference — **A**
- [ ] GPU Inference Optimization — **A**

</details>

**Project ideas**

- ML Prediction REST API
- RAG API
- AI Agent Backend

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-15"></a>

### Phase 15 · Software Engineering & DevOps

Make projects reproducible, testable and easier to maintain and deliver.

**Before you start:** Python and a working project; learn Git basics as soon as you start coding.

**Learning note:** Use Git, the command line and environment variables early. Learn containers and orchestration progressively.

**Completion checkpoint:** Package a project with clear setup instructions, automated checks and a reproducible runtime.

<details>
<summary><strong>Open the learning checklist · 25 subtopics</strong></summary>

#### Developer Workflow

- [ ] Git Basics — **A**
- [ ] GitHub — **A**
- [ ] Branching & Pull Requests — **A**
- [ ] Code Structure & Clean Code — **A**
- [ ] Environment Variables — **A**

#### Operating Systems

- [ ] Linux Basics — **I**
- [ ] Command Line — **A**
- [ ] File Permissions — **A**
- [ ] Processes — **A**
- [ ] Bash Scripting — **A**
- [ ] SSH — **A**

#### Testing & Delivery

- [ ] Unit Testing — **A**
- [ ] pytest — **I**
- [ ] API Testing — **I**
- [ ] Docker — **I**
- [ ] Docker Compose — **I**
- [ ] GitHub Actions — **I**
- [ ] CI/CD — **I**
- [ ] Kubernetes Basics — **A**

#### Testing & Quality

- [ ] Integration Testing — **A**
- [ ] Performance Testing — **A**
- [ ] Load Testing — **A**

#### Infrastructure & Delivery

- [ ] Redis Caching — **I**
- [ ] Load Balancing — **A**
- [ ] Message Queues — **A**

</details>

**Project ideas**

- Dockerized ML Application
- Dockerized RAG Application
- Automated Test & Deployment Pipeline
- Load-tested AI API
- Redis-cached Inference API

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-16"></a>

### Phase 16 · MLOps & LLMOps

Track experiments, version artifacts and monitor AI behavior after deployment.

**Before you start:** Phase 06 or 10, backend basics and Phase 15 workflow skills.

**Learning note:** Start with reproducibility and tracking. Add monitoring based on your application needs.

**Completion checkpoint:** Reproduce an experiment, identify the deployed version and monitor quality, latency and failures.

<details>
<summary><strong>Open the learning checklist · 22 subtopics</strong></summary>

#### MLOps Fundamentals

- [ ] MLOps Lifecycle — **I**
- [ ] Reproducible Experiments — **A**
- [ ] Experiment Tracking — **A**
- [ ] MLflow — **A**
- [ ] Model Versioning — **A**
- [ ] Model Registry — **A**

#### Pipelines & Data

- [ ] ML Pipelines — **A**
- [ ] DVC — **A**
- [ ] Data / Model Validation — **A**
- [ ] Feature Pipelines — **A**

#### Production Monitoring

- [ ] Model Deployment — **A**
- [ ] Model Monitoring — **A**
- [ ] Data Drift & Model Drift — **A**
- [ ] Logging & Observability — **A**
- [ ] Logging & Monitoring — **A**
- [ ] AI Observability — **A**
- [ ] Cost & Latency Optimization — **A**

#### LLMOps

- [ ] LLM Evaluation — **A**
- [ ] Prompt / Model Versioning — **I**
- [ ] Tracing — **A**
- [ ] Cost & Latency Monitoring — **A**
- [ ] Guardrails — **A**

</details>

**Project ideas**

- End-to-end MLflow Pipeline
- Model Monitoring Dashboard
- LLM Evaluation & Tracing Pipeline

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-17"></a>

### Phase 17 · Cloud Computing

Understand cloud infrastructure and deploy a small AI service.

**Before you start:** Phases 14-15 and basic networking concepts.

**Learning note:** Choose one cloud first. Use local projects while learning and check service pricing before provisioning resources.

**Completion checkpoint:** Deploy a small service, configure least-privilege access and explain its operating costs.

<details>
<summary><strong>Open the learning checklist · 17 subtopics</strong></summary>

#### Cloud Fundamentals

- [ ] Cloud Concepts — **I**
- [ ] Compute / Storage / Networking — **A**
- [ ] IAM & Permissions — **A**
- [ ] Regions & Availability Zones — **A**

#### AWS

- [ ] S3 — **A**
- [ ] EC2 — **A**
- [ ] Lambda — **A**
- [ ] IAM — **A**
- [ ] SageMaker — **A**
- [ ] Bedrock — **A**
- [ ] CloudWatch — **I**

#### Azure

- [ ] Azure Fundamentals — **I**
- [ ] Azure AI Services — **I**
- [ ] Azure Machine Learning — **I**

#### Google Cloud

- [ ] Google Cloud Fundamentals — **I**
- [ ] Vertex AI — **I**
- [ ] Cloud Storage — **I**

</details>

**Project ideas**

- Deploy ML API to Cloud
- Cloud-hosted RAG Application
- Managed ML Endpoint

[Back to roadmap](#roadmap-at-a-glance)

---

<a id="phase-18"></a>

### Phase 18 · Advanced AI Engineering

Design reliable AI systems and communicate engineering tradeoffs.

**Before you start:** Completed projects plus relevant backend, operations and cloud experience.

**Learning note:** Treat this as a reference library. Every tool is not a prerequisite for applying for a role.

**Completion checkpoint:** Document a system design with evaluation, security, observability, scaling and cost tradeoffs.

<details>
<summary><strong>Open the learning checklist · 35 subtopics</strong></summary>

#### System Design

- [ ] AI System Design Fundamentals — **A**
- [ ] Monoliths & Microservices — **A**
- [ ] Distributed Systems — **A**
- [ ] Scalability & Reliability — **A**

#### Performance & Infrastructure

- [ ] Caching with Redis — **I**
- [ ] Load Balancing — **A**
- [ ] Message Queues — **A**
- [ ] Apache Kafka — **A**
- [ ] Apache Airflow — **A**
- [ ] Data Engineering Basics — **A**

#### Production AI

- [ ] AI Security — **A**
- [ ] LLM Guardrails — **A**
- [ ] Prompt Injection & Data Protection — **I**
- [ ] Observability — **A**
- [ ] Cost & Latency Optimization — **A**
- [ ] High Availability — **A**

#### AI Security & Responsible AI

- [ ] Responsible AI — **A**
- [ ] AI Ethics — **A**
- [ ] Bias & Fairness — **A**
- [ ] Data Privacy — **A**
- [ ] Explainability — **A**
- [ ] Adversarial Attacks — **A**
- [ ] Prompt Injection — **I**
- [ ] LLM Security — **A**
- [ ] AI Governance — **A**

#### Advanced Infrastructure

- [ ] GPU Inference Optimization — **A**
- [ ] High Availability — **A**
- [ ] Distributed Systems Design — **A**

#### Professional Development

- [ ] Technical Documentation — **A**
- [ ] System Design Interviews — **A**
- [ ] AI/ML Technical Interviews — **A**
- [ ] Research Paper Reading — **A**
- [ ] Kaggle Competitions — **A**
- [ ] Open Source Contributions — **A**
- [ ] GitHub Portfolio Management — **A**

</details>

**Project ideas**

- Scalable Enterprise AI Assistant
- Production RAG + Agent Platform
- End-to-end AI System Design
- Secure Enterprise AI Assistant
- Scalable Production AI Platform

[Back to roadmap](#roadmap-at-a-glance)

---

## Build a portfolio you can explain

Choose a few projects and improve them beyond the tutorial. For each project, include:

- **Problem:** who it helps and what a useful result looks like.
- **Data:** its source, limitations and preparation steps.
- **Approach:** a simple baseline and why you chose the final method.
- **Evaluation:** suitable metrics, held-out examples and failure cases.
- **Reproducibility:** dependencies, setup and steps to run or retrain.
- **Engineering:** relevant tests, error handling and clear configuration.
- **Reflection:** tradeoffs, limitations and what you would improve next.

For LLM and RAG projects, include example questions, expected behavior, citation checks where relevant, and measured latency and cost. A working demo with honest evaluation is more useful than a long list of tools.

## Track your progress

The checkboxes in this README are a template. They do not save personal progress automatically. Fork the repo or edit your own copy, then commit your updates.

```markdown
- [ ] Functions - B
- [x] Variables & Data Types - B
```

Use this optional weekly log in your own notes:

| Week | Topic or phase | What I built or practised | Evidence / notes | Next step |
| --- | --- | --- | --- | --- |
| 01 | Python basics | Marks calculator | Add your project link | Add file handling |

Check a topic when you can explain it, demonstrate it and identify a common error. Revisit it when your projects reveal a gap.

## Resources and contributions

**YouTube resource curation is pending.** This version provides the complete learning structure first. Resource recommendations can be added after review.

When adding a resource, place it beneath the matching subtopic in its checklist. Prefer one clear introduction and, where useful, one practical follow-up. Use this format:

```markdown
- [ ] Functions - **B**
  - Watch: [Actual video title](VIDEO_URL) - Creator / English or Sinhala / Duration
  - Why this resource: Explain its coverage and who it suits.
  - Practise: Write a function that validates marks and calculates an average.
  - Checked: YYYY-MM-DD / Relevant language or library version, if applicable
```

Replace the example fields with real information before contributing. Link to the specific video or playlist rather than a YouTube search page.

### Resource review checklist

- Does it teach this specific subtopic with clear explanations?
- Is it accurate, with useful examples or exercises?
- Are prerequisites, language and duration clear?
- For framework tutorials, are the versions and APIs still relevant?
- Is the link available, and does it go to the original creator?
- Does it add value beyond resources already listed?

Corrections, clearer explanations, practical exercises and broken-link fixes are welcome. Keep subtopics under the appropriate phase, explain substantial changes and avoid adding many resources that teach the same thing. When suggesting a new topic, describe where it fits and what prerequisite it needs.

## Source and scope

The phase order, **409 subtopic entries**, level labels and project suggestions were transcribed from **AI_ML_Complete_Zero_to_Hero_Roadmap.xlsx**, supplied for this repository. The introduction, learning notes, completion checkpoints and suggested paths provide additional guidance around that outline.

The spreadsheet itself is not included in the repository. Similar project ideas and repeated subtopics are retained to preserve the supplied roadmap. Tool names reflect the source; consult current official documentation when implementing a project.

This is a learning guide. Choose topics that support your goals, build projects you understand and return to advanced subjects as your needs grow.

---

<div align="center">

**Learn the fundamentals. Build something useful. Explain your decisions.**

[Start learning](#start-here) / [Explore all phases](#roadmap-at-a-glance)

</div>
