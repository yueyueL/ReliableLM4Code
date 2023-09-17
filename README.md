![image](https://github.com/yueyueL/ReliableLM4Code/assets/60457190/ffea1cd8-7329-4c61-a12e-ebb7ac31511b)![image](https://github.com/yueyueL/ReliableLM4Code/assets/60457190/f6fd7409-7998-43ea-bea5-607ef6d9339f)![image](https://github.com/yueyueL/ReliableLM4Code/assets/60457190/8c8890cd-4d77-4bde-80d0-ef82d917757c)![image](https://github.com/yueyueL/ReliableLM4Code/assets/60457190/8e5009f2-a9b7-4859-8be2-2f27eb5ffd74)# ReliableLM4Code
![GitHub last commit]()
![badge]()

This repository contains a curated list of papers, PhD theses, datasets, and tools that are devoted to research on Machine Learning for Software Engineering. The papers are organized into popular research areas so that researchers can find recent papers and state-of-the-art approaches easily.

Please feel free to send a pull request to add papers and relevant content that are not listed here.

> Note: to quickly access this page, use []()

## Content
- [SLR](#slr)
    - [SLR process](#slr-process)
        - [Strategy](#strategy)
        - [Manual Search Venues](#manual-venues)
    - [Tools](#tools)
- [Papers](#papers)
    - [Type Inference](#type-inference)
    - [Data Collection and Labeling](#data)
        - [Sampling Bias](#sampling-bias)
        - [Label Inaccuracy](#label-inaccuracy)
        - [Data Noise](#data-noise)
    - [System Design and Learning](#design)
        - [Data Snooping](#data-snooping)
        - [Spurious Correlations](#spurious-correlations)
        - [Inappropriate Data Proprocessing](#data-proprocessing)
        - [Inappropriate Model Design](#model-design)
    - [Performance Evaluation](#evaluation)
        - [Inappropriate Baseline](#baseline)
        - [Inappropriate Test Set](#test-set)
        - [Low Reproducibility](#low-reproducibility)
        - [Inappropriate Performance Measures](#performance-measures)
    - [Deployment and Maintainance](#deployment)
        - [Lab-only evaluation](#lab-only)
        - [Model Attack Threats](#model-attack)
        - [Security concerns in generated code](#security-concerned)
- [Research Groups](#research-groups)
- [Venues](#venues)

# SLR
## SLR Process
### Manual Search Venues
### Strategy
## SLR Tools

# Papers
## Type Inference

- **Dos and Don'ts of Machine Learning in Computer Security** (2022), USENIX Security 22, D Arp, et al. [[pdf]](https://www.usenix.org/system/files/sec22-arp.pdf)
- **Machine/deep learning for software engineering: A systematic literature review** (2022), TSE 22, Simin Wang, et al. [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9772253)
- **Trustworthy AI: From principles to practices** (2023), arxiv, BO Li, et al. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3555803)

## Data Collection and Labeling
### Sampling Bias
Deep Learning Based Vulnerability Detection: Are We There Yet?
Does data sampling improve deep learning-based vulnerability detection? Yeas! and Nays!
On the Value of Oversampling for Deep Learning in Software Defect Prediction
Robust Learning of Deep Predictive Models from Noisy and Imbalanced Software Engineering Datasets
An empirical study of deep learning models for vulnerability detection

### Label Inaccuracy
Robust Learning of Deep Predictive Models from Noisy and Imbalanced Software Engineering Datasets
XCode: Towards Cross-Language Code Representation with Large-Scale Pre-Training
Understanding and Tackling Label Errors in Deep Learning-Based Vulnerability Detection (Experience Paper)

### Data Noise
Slice-Based Code Change Representation Learning
Are we building on the rock? on the importance of data preprocessing for code summarization
Neural-Machine-Translation-Based Commit Message Generation: How Far Are We?

## System Design and Learning
### Data Snooping
AutoTransform: automated code transformation to support modern code review process
Can Neural Clone Detection Generalize to Unseen Functionalitiesƒ
CD-VulD: Cross-Domain Vulnerability Discovery Based on Deep Domain Adaptation
Deep just-in-time defect prediction: how far are we?
Patching as translation: the data and the metaphor
An empirical study of deep learning models for vulnerability detection
Keeping Pace with Ever-Increasing Data: Towards Continual Learning of Code Intelligence Models
Revisiting Learning-based Commit Message Generation
Syntax and Domain Aware Model for Unsupervised Program Translation
How Effective Are Neural Networks for Fixing Security Vulnerabilities
Towards More Realistic Evaluation for Neural Test Oracle Generation
On the Evaluation of Neural Code Summarization

### Spurious Correlations
Deep Learning Based Vulnerability Detection: Are We There Yet?
Diet code is healthy: simplifying programs for pre-trained models of code
Explaining mispredictions of machine learning models using rule induction
Interpreting Deep Learning-based Vulnerability Detector Predictions Based on Heuristic Searching
Thinking Like a Developer? Comparing the Attention of Humans with Neural Models of Code
Vulnerability detection with fine-grained interpretations
What do they capture? a structural analysis of pre-trained language models for source code
An empirical study of deep learning models for vulnerability detection
Towards Efficient Fine-Tuning of Pre-trained Code Models: An Experimental Study and Beyond

### Inappropriate Data Proprocessing
Deep Learning Based Vulnerability Detection: Are We There Yet?

### Inappropriate Model Design
Deep Learning Based Vulnerability Detection: Are We There Yet?
Enhancing DNN-Based Binary Code Function Search With Low-Cost Equivalence Checking
Improving automatic source code summarization via deep reinforcement learning
Patching as translation: the data and the metaphor
Reinforcement-Learning-Guided Source Code Summarization Using Hierarchical Attention
XCode: Towards Cross-Language Code Representation with Large-Scale Pre-Training
RepresentThemAll: A Universal Learning Representation of Bug Reports
Template-based Neural Program Repair

## Performance Evaluation
### Inappropriate Baseline
Towards More Realistic Evaluation for Neural Test Oracle Generation

### Inappropriate Test Set
Deep Learning Based Program Generation From Requirements Text: Are We There Yet?
Generating realistic vulnerabilities via neural code editing: an empirical study

### Low Reproducibility
An extensive study on pre-trained models for program understanding and generation

### Inappropriate Performance Measures
Deep Learning Based Vulnerability Detection: Are We There Yet?
Improving automatic source code summarization via deep reinforcement learning
Multi-task learning based pre-trained language model for code completion
On the Value of Oversampling for Deep Learning in Software Defect Prediction
Patching as translation: the data and the metaphor
Reinforcement-Learning-Guided Source Code Summarization Using Hierarchical Attention
SynShine: Improved Fixing of Syntax Errors
An empirical study of deep learning models for vulnerability detection
Revisiting Learning-based Commit Message Generation
Tare: Type-Aware Neural Program Repair
How Effective Are Neural Networks for Fixing Security Vulnerabilities
Towards More Realistic Evaluation for Neural Test Oracle Generation
GitHub Copilot AI pair programmer: Asset or Liability?


## Deployment and Maintainance
### Lab-only evaluation
Examining Zero-Shot Vulnerability Repair with Large Language Models
A Performance-Sensitive Malware Detection System Using Deep Learning on Mobile Devices
Diet code is healthy: simplifying programs for pre-trained models of code
When Code Completion Fails: A Case Study on Real-World Completions
Lost at C: A User Study on the Security Implications of Large Language Model Code Assistants
Grounded Copilot: How Programmers Interact with Code-Generating Models
LLaMA-Reviewer: Advancing Code Review Automation with Large Language Models through Parameter-Efficient Fine-Tuning
Compressing Pre-trained Models of Code into 3 MB

### Model Attack Threats
You Autocomplete Me: Poisoning Vulnerabilities in Neural Code Completion
Adversarial Robustness of Deep Code Comment Generation
An extensive study on pre-trained models for program understanding and generation
Generating Adversarial Examples for Holding Robustness of Source Code Processing Models
Semantic Robustness of Models of Source Code
You see what I want you to see: poisoning vulnerabilities in neural code search
Contrabert: Enhancing code pre-trained models via contrastive learning
On the robustness of code generation techniques: An empirical study on github copilot
Two sides of the same coin: Exploiting the impact of identifiers in neural code comprehension
Multi-target Backdoor Attacks for Code Pre-trained Models
Backdooring Neural Code Search
ReCode: Robustness Evaluation of Code Generation Models
Natural Attack for Pre-trained Models of Code
Coprotector: Protect open-source code against unauthorized training usage with data poisoning
On the Security Vulnerabilities of Text-to-SQL Models

### Security concerns in generated code
Asleep at the Keyboard? Assessing the Security of GitHub Copilot's Code Contributions
Automated repair of programs from large language models
Cctest: Testing and repairing code completion systems
Analyzing Leakage of Personally Identifiable Information in Language Models
CodexLeaks: Privacy Leaks from Code Generation Language Models in GitHub Copilot

# Research Groups


# Venues
## Conferences
- **AI Domain**
    - **AAAI**, the Association for the Advancement of Artificial Intelligence
    - **ACL**, the Association for Computational Linguistics
- **SE Domain**
    - **ICSE**, the International Conference on Software Engineering
    - **FSE**, Symposium on the Foundations of Software Engineering
    - **ASE**, the International Conference on Automated Software Engineering
    - **ISSTA**, the International Symposium on Software Testing and Analysis
    - **ISSRE**, IEEE International Symposium on Software Reliability
    - **SANER**, IEEE International Conference on Software Analysis, Evolution, and Reengineering Engineering
    - **OOPSLA**, the ACM Conference on Systems, Programming, Languages, and Applications
- **Security Domain**
    - **S&P**, IEEE Symposium on Security and Privacy
    - **USENIX Security**, USENIX Security Symposium
- **Internet and Web technology Domain**
    - **WWW**, International World Wide Web Conference

## Journals
- **SE Domain**
    - **TSE**, the IEEE Transactions on Software Engineering
    - **TOSEM**, ACM Transactions on Software Engineering and Methodology
    - **JSS**, Journal of Systems and Software
- **Security Domain**
    - **TDSC**, IEEE Transactions on Dependable and Secure Computing
    - **TIFS**, IEEE Transactions on Information Forensics and Security
