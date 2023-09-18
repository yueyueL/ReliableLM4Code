# ReliableLM4Code
![GitHub last commit]()
![badge]()

This repository contains a curated list of papers, PhD theses, datasets, and tools that are devoted to research on Machine Learning for Software Engineering. The papers are organized into popular research areas so that researchers can find recent papers and state-of-the-art approaches easily.

Please feel free to send a pull request to add papers and relevant content that are not listed here.

> Note: to quickly access this page, use []()

## Content
- [SLR](#slr)
    - [Process](#slr-process)
    - [Methodology](#methodology)
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
## Process

To conduct a systematic review, we need to follow complete steps to collect, analyze and review the relevant literature works.

![SLR_Process]("D:\Work_Station\Github\ReliableLM4Code\picture\Study_identification_and_selection_process.png)

**Steps:**
- Define the Review Questions
- Develop the Protocol
- Search Strategy
- Study Selection
- Data Extraction
- Quality Assessment
- Snowballing/Citation Tracking
- Data Synthesis
- Write the Report
## Methodology
***Search String:***
- ***Keywords related to LMs:*** "LLM" OR "Large Language Model*" OR "Language Model*" OR
"LM" OR "PLM" OR "Pre-trained" OR "Pre-training" OR "Natural Language Processing"
OR "NLP" OR "Machine Learning" OR "ML" OR "Deep Learning" OR "DL" OR "Artificial
Intelligence" OR "AI" OR "Transformer" OR "BERT" OR "CODEX" OR "GPT" OR "T5" OR
"Sequence Model*" OR "Attention Model*" OR "Transfer Learning" OR "Neural Network*"
OR "ChatGPT" OR "GPT-*" OR "Deep neural network*" OR "DNN*"
- ***Keywords  related to SE tasks:*** "Software Engineering" OR "Software Development" OR "Program*" OR "Software Testing" OR "Software Mainten*" OR "SE" OR "Software Lifecycle" OR "Software Design*" OR "Code representation" OR "Code generation" OR "Code comment generation" OR "Code search" OR "Code localization" OR "Code completion" OR "Code summarization" OR "Method name generation" OR "Bug detection" OR "Bug localization" OR "Vulnerability detection" OR "Testing techniques" OR "Test case generation" OR "Program analysis" OR "Bug classification" OR "Defect prediction" OR "Program repair" OR "Code clone detection" OR "Bug report" OR "Software quality evaluation" OR "SATD detection" OR "Code smell detection" OR "Compiled-related" OR "Code review" OR "Software classification" OR "Code classification" OR "Code change" OR "Incident detection" OR "Requirement extraction" OR "Requirement traceability" OR "Requirement validation" OR "Effort cost prediction" OR "Mining GitHub/Github mining" OR "Mining SO (StackOverflow)/SO mining" OR "Mining app/App mining" OR "Mining tag/Tag mining" OR "Developer-based mining"
 
***Exclude criteria:***
- The paper whose number of pages is less than 8.
-  Studies of which their full texts are inaccessible.
-  Duplicate papers or similar studies with different versions from the same authors.
- The paper that is published as a SLR, review or survey.
- Short papers, tool demos and editorials.
- The paper that is published in a workshop or a doctoral symposium.
- Studies belonging to books, thesis, monographs, keynotes, panels, or venues not executing
the peer-review process.
- Non-English written literature.
- Literature not using language models.
- Papers presenting analyses of cyber attacks or Operating Systems

***Manual Search Venues:***
| Acronym | <center/>Venues<center> |
|---------|--------|
|ASE |International Conference on Automated Software Engineering|
|ESEC/FSE |Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering|
|ICSE |International Conference on Software Engineering|
|ISSTA |International Symposium on Software Testing and Analysis|
|TOSEM |Transactions on Software Engineering and Methodology|
|TSE| Transactions on Software Engineering|

## Tools
**Paper Collection**
- [slrtools](https://github.com/out0/slrtool): Tool for Performing Systematic Literature Review
- [elsapy](https://github.com/ElsevierDev/elsapy): https://github.com/ElsevierDev/elsapy
- [dblp-python](https://github.com/ElsevierDev/elsapy): A simple Python wrapper around the DBLP API, currently supporting author search and author and publication lookup.

**SnowBalling:**
- [Litmap](https://app.litmaps.com/): Litmaps are visual citation maps that help you understand how your research connects. (*Both DOI list and Title list are ok to search !!!*)
- [SnowGlobe](https://snowglobe.soc.northwestern.edu/): SnowGlobe is a program that assists with literature searching, using a technique called snowballing. (*Articles written after 2021 will not be able to be searched or found !!!*)
- [CitationGecko](https://www.citationgecko.com/): This is a tool that uses the citation relations between scientific papers to help researchers find interesting and relevant paper.


# Papers
## Type Inference

- **Dos and Don'ts of Machine Learning in Computer Security** (2022), USENIX Security 22, D Arp, et al. [[pdf]](https://www.usenix.org/system/files/sec22-arp.pdf)
- **Machine/deep learning for software engineering: A systematic literature review** (2022), TSE 22, Simin Wang, et al. [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9772253)
- **Trustworthy AI: From principles to practices** (2023), arxiv, BO Li, et al. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3555803)

## Data Collection and Labeling
### Sampling Bias
- **Deep Learning Based Vulnerability Detection: Are We There Yet?**
- **Does data sampling improve deep learning-based vulnerability detection? Yeas! and Nays!**
- **On the Value of Oversampling for Deep Learning in Software Defect Prediction**
- **Robust Learning of Deep Predictive Models from Noisy and Imbalanced Software Engineering Datasets**
- **An empirical study of deep learning models for vulnerability detection**

### Label Inaccuracy
- **Robust Learning of Deep Predictive Models from Noisy and Imbalanced Software Engineering Datasets**
- **XCode: Towards Cross-Language Code Representation with Large-Scale Pre-Training**
- **Understanding and Tackling Label Errors in Deep Learning-Based Vulnerability Detection (Experience Paper)**

### Data Noise
- **Slice-Based Code Change Representation Learning**
- **Are we building on the rock? on the importance of data preprocessing for code summarization**
- **Neural-Machine-Translation-Based Commit Message Generation: How Far Are We?**

## System Design and Learning
### Data Snooping
- **AutoTransform: automated code transformation to support modern code review process**
- **Can Neural Clone Detection Generalize to Unseen Functionalitiesƒ**
- **CD-VulD: Cross-Domain Vulnerability Discovery Based on Deep Domain Adaptation**
- **Deep just-in-time defect prediction: how far are we?**
- **Patching as translation: the data and the metaphor**
- **An empirical study of deep learning models for vulnerability detection**
- **Keeping Pace with Ever-Increasing Data: Towards Continual Learning of Code Intelligence Models**
- **Revisiting Learning-based Commit Message Generation**
- **Syntax and Domain Aware Model for Unsupervised Program Translation**
- **How Effective Are Neural Networks for Fixing Security Vulnerabilities**
- **Towards More Realistic Evaluation for Neural Test Oracle Generation**
- **On the Evaluation of Neural Code Summarization**

### Spurious Correlations
- **Deep Learning Based Vulnerability Detection: Are We There Yet?**
- **Diet code is healthy: simplifying programs for pre-trained models of code**
- **Explaining mispredictions of machine learning models using rule induction**
- **Interpreting Deep Learning-based Vulnerability Detector Predictions Based on Heuristic Searching**
- **Thinking Like a Developer? Comparing the Attention of Humans with Neural Models of Code**
- **Vulnerability detection with fine-grained interpretations**
- **What do they capture? a structural analysis of pre-trained language models for source code**
- **An empirical study of deep learning models for vulnerability detection**
- **Towards Efficient Fine-Tuning of Pre-trained Code Models: An Experimental Study and Beyond**

### Inappropriate Data Proprocessing
- **Deep Learning Based Vulnerability Detection: Are We There Yet?**

### Inappropriate Model Design
- **Deep Learning Based Vulnerability Detection: Are We There Yet?**
- **Enhancing DNN-Based Binary Code Function Search With Low-Cost Equivalence Checking**
- **Improving automatic source code summarization via deep reinforcement learning**
- **Patching as translation: the data and the metaphor**
- **Reinforcement-Learning-Guided Source Code Summarization Using Hierarchical Attention**
- **XCode: Towards Cross-Language Code Representation with Large-Scale Pre-Training**
- **RepresentThemAll: A Universal Learning Representation of Bug Reports**
- **Template-based Neural Program Repair**

## Performance Evaluation
### Inappropriate Baseline
- **Towards More Realistic Evaluation for Neural Test Oracle Generation**

### Inappropriate Test Set
- **Deep Learning Based Program Generation From Requirements Text: Are We There Yet?**
- **Generating realistic vulnerabilities via neural code editing: an empirical study**

### Low Reproducibility
- **An extensive study on pre-trained models for program understanding and generation**

### Inappropriate Performance Measures
- **Deep Learning Based Vulnerability Detection: Are We There Yet?**
- **Improving automatic source code summarization via deep reinforcement learning**
- **Multi-task learning based pre-trained language model for code completion**
- **On the Value of Oversampling for Deep Learning in Software Defect Prediction**
- **Patching as translation: the data and the metaphor**
- **Reinforcement-Learning-Guided Source Code Summarization Using Hierarchical Attention**
- **SynShine: Improved Fixing of Syntax Errors**
- **An empirical study of deep learning models for vulnerability detection**
- **Revisiting Learning-based Commit Message Generation**
- **Tare: Type-Aware Neural Program Repair**
- **How Effective Are Neural Networks for Fixing Security Vulnerabilities**
- **Towards More Realistic Evaluation for Neural Test Oracle Generation**
- **GitHub Copilot AI pair programmer: Asset or Liability?**


## Deployment and Maintainance
### Lab-only evaluation
- **Examining Zero-Shot Vulnerability Repair with Large Language Models** (2023), , H Pearce, B Tan, B Ahmad, R Karri… , et al.[[pdf]](https://arxiv.org/pdf/2112.02125)
- **A Performance-Sensitive Malware Detection System Using Deep Learning on Mobile Devices** (2020), , R Feng, S Chen, X Xie, G Meng… , et al.[[pdf]](https://arxiv.org/pdf/2005.04970)
- **Diet code is healthy: simplifying programs for pre-trained models of code** (2022), , Z Zhang, H Zhang, B Shen, X Gu , et al.[[pdf]](https://arxiv.org/pdf/2206.14390)
- **When Code Completion Fails: A Case Study on Real-World Completions** (2019), , VJ Hellendoorn, S Proksch, HC Gall… , et al.[[pdf]](http://www.sback.it/publications/icse2019b.pdf)
- **Lost at C: A User Study on the Security Implications of Large Language Model Code Assistants** (2023), , G Sandoval, H Pearce, T Nys, R Karri, S Garg… , et al.[[pdf]](https://www.usenix.org/system/files/sec23fall-prepub-353-sandoval.pdf)
- **Grounded Copilot: How Programmers Interact with Code-Generating Models** (2023), , S Barke, MB James, N Polikarpova , et al.[[pdf]](https://dl.acm.org/doi/pdf/10.1145/3586030)
- **LLaMA-Reviewer: Advancing Code Review Automation with Large Language Models through Parameter-Efficient Fine-Tuning** (2308), , J Lu, L Yu, X Li, L Yang, C Zuo , et al.[[pdf]](https://arxiv.org/pdf/2308.11148)
- **Compressing Pre-trained Models of Code into 3 MB** (2022), , J Shi, Z Yang, B Xu, HJ Kang, D Lo , et al.[[pdf]](https://dl.acm.org/doi/pdf/10.1145/3551349.3556964)

### Model Attack Threats
- **You Autocomplete Me: Poisoning Vulnerabilities in Neural Code Completion** (2021), , R Schuster, C Song, E Tromer… , et al.[[pdf]](https://www.usenix.org/system/files/sec21-schuster.pdf)
- **Adversarial Robustness of Deep Code Comment Generation** (2022), , Y Zhou, X Zhang, J Shen, T Han, T Chen… , et al.[[pdf]](https://arxiv.org/pdf/2108.00213)
- **An extensive study on pre-trained models for program understanding and generation** (2022), , Z Zeng, H Tan, H Zhang, J Li, Y Zhang… , et al.[[pdf]](https://lingming.cs.illinois.edu/publications/issta2022.pdf)
- **Generating Adversarial Examples for Holding Robustness of Source Code Processing Models** (2020), , H Zhang, Z Li, G Li, L Ma, Y Liu, Z Jin , et al.[[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/5469/5325)
- **Semantic Robustness of Models of Source Code** (2020), , G Ramakrishnan, J Henkel, Z Wang… , et al.[[pdf]](https://arxiv.org/pdf/2002.03043)
- **You see what I want you to see: poisoning vulnerabilities in neural code search** (2022), , Y Wan, S Zhang, H Zhang, Y Sui, G Xu, D Yao… , et al.[[pdf]](https://opus.lib.uts.edu.au/bitstream/10453/164890/2/fse22_code_attack_camera%20%281%29.pdf)
- **Contrabert: Enhancing code pre-trained models via contrastive learning** (2301), , S Liu, B Wu, X Xie, G Meng, Y Liu , et al.[[pdf]](https://arxiv.org/pdf/2301.09072)
- **On the robustness of code generation techniques: An empirical study on github copilot** (2023), , A Mastropaolo, L Pascarella, E Guglielmi… , et al.[[pdf]](https://arxiv.org/pdf/2302.00438)
- **Two sides of the same coin: Exploiting the impact of identifiers in neural code comprehension** (2023), , S Gao, C Gao, C Wang, J Sun, D Lo… , et al.[[pdf]](https://yuyue.github.io/res/paper/NeuralCode-ICSE2023.pdf)
- **Multi-target Backdoor Attacks for Code Pre-trained Models** (2023), , Y Li, S Liu, K Chen, X Xie, T Zhang, Y Liu , et al.[[pdf]](https://arxiv.org/pdf/2306.08350)
- **Backdooring Neural Code Search** (2023), , W Sun, Y Chen, G Tao, C Fang, X Zhang… , et al.[[pdf]](https://arxiv.org/pdf/2305.17506)
- **ReCode: Robustness Evaluation of Code Generation Models** (2022), , S Wang, Z Li, H Qian, C Yang, Z Wang… , et al.[[pdf]](https://arxiv.org/pdf/2212.10264)
- **Natural Attack for Pre-trained Models of Code** (2022), , Z Yang, J Shi, J He, D Lo , et al.[[pdf]](https://arxiv.org/pdf/2201.08698)
- **Coprotector: Protect open-source code against unauthorized training usage with data poisoning** (2022), , Z Sun, X Du, F Song, M Ni, L Li , et al.[[pdf]](https://arxiv.org/pdf/2110.12925)
- **On the Security Vulnerabilities of Text-to-SQL Models** (2211), , X Peng, Y Zhang, J Yang, M Stevenson , et al.[[pdf]](https://arxiv.org/pdf/2211.15363)

### Security concerns in generated code
- **Asleep at the Keyboard? Assessing the Security of GitHub Copilot's Code Contributions** (2022), , H Pearce, B Ahmad, B Tan… , et al.[[pdf]](https://arxiv.org/pdf/2108.09293.pdf?trk=article-ssr-frontend-pulse_x-social-details_comments-action_comment-text)
- **Automated repair of programs from large language models** (2023), , Z Fan, X Gao, M Mirchev… , et al.[[pdf]](https://abhikrc.com/pdf/ICSE23.pdf)
- **Cctest: Testing and repairing code completion systems** (2023), , Z Li, C Wang, Z Liu, H Wang, D Chen… , et al.[[pdf]](https://arxiv.org/pdf/2208.08289)
- **Analyzing Leakage of Personally Identifiable Information in Language Models** (2023), , N Lukas, A Salem, R Sim, S Tople, L Wutschitz… , et al.[[pdf]](https://arxiv.org/pdf/2302.00539)
- **CodexLeaks: Privacy Leaks from Code Generation Language Models in GitHub Copilot** (2023), , L Niu, S Mirza, Z Maradni, C Pöpper , et al.[[pdf]](https://www.usenix.org/system/files/usenixsecurity23-niu.pdf)
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
