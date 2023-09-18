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

![Study_identification_and_selection_process](https://github.com/yueyueL/ReliableLM4Code/assets/60457190/e1b73870-a7da-489b-bf6c-d0577375f252)

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
<details>
<summary>Click to expand</summary>
| Acronym | <center/>Venues<center> |
|---------|--------|
|ASE |International Conference on Automated Software Engineering|
|ESEC/FSE |Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering|
|ICSE |International Conference on Software Engineering|
|ISSTA |International Symposium on Software Testing and Analysis|
|TOSEM |Transactions on Software Engineering and Methodology|
|TSE| Transactions on Software Engineering|
</details>
    
## Tools
**Paper Collection**
- [slrtools](https://github.com/out0/slrtool): Tool for Performing Systematic Literature Review
- [elsapy](https://github.com/ElsevierDev/elsapy): A Python module for use with api.elsevier.com.
- [dblp-python](https://github.com/ElsevierDev/elsapy): A simple Python wrapper around the DBLP API, currently supporting author search and author and publication lookup.

**SnowBalling:**
- [Litmap](https://app.litmaps.com/): Litmaps are visual citation maps that help you understand how your research connects. (*Both DOI list and Title list are ok for search !!!*)
- [SnowGlobe](https://snowglobe.soc.northwestern.edu/): SnowGlobe is a program that assists with literature searching, using a technique called snowballing. (*Articles written after 2021 will not be able to be searched or found !!!*)
- [CitationGecko](https://www.citationgecko.com/): This is a tool that uses the citation relations between scientific papers to help researchers find interesting and relevant paper.


# Papers
## Type Inference

- **Dos and Don'ts of Machine Learning in Computer Security** (2022), USENIX Security 22, D Arp, et al. [[pdf]](https://www.usenix.org/system/files/sec22-arp.pdf)
- **Machine/deep learning for software engineering: A systematic literature review** (2022), TSE 22, Simin Wang, et al. [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9772253)
- **Trustworthy AI: From principles to practices** (2023), arxiv, BO Li, et al. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3555803)

## Data Collection and Labeling
### *Sampling Bias*
- **Deep Learning Based Vulnerability Detection** (2021), , S Chakraborty, R Krishna, Y Ding… , et al.[[pdf]](https://arxiv.org/pdf/2009.07235)
- **Does data sampling improve deep learning-based vulnerability detection? Yeas! and Nays!** (2023), , X Yang, S Wang, Y Li, S Wang , et al.[[pdf]](https://shaoweiwang2010.github.io/papers/ICSE_2023_Sampling_Vulnerablity.pdf)
- **On the Value of Oversampling for Deep Learning in Software Defect Prediction** (2021), , R Yedida, T Menzies , et al.[[pdf]](https://arxiv.org/pdf/2008.03835)
- **Robust Learning of Deep Predictive Models from Noisy and Imbalanced Software Engineering Datasets** (2022), , Z Li, M Pan, Y Pei, T Zhang, L Wang, X Li , et al.[[pdf]](https://scholar.archive.org/work/fls7wlezhrdappl2f46gb6u5de/access/wayback/https://dl.acm.org/doi/pdf/10.1145/3551349.3556941)- **An empirical study of deep learning models for vulnerability detection** (2023), , B Steenhoek, MM Rahman, R Jiles… , et al.[[pdf]](https://arxiv.org/pdf/2212.08109)

### *Label Inaccuracy*
- **Robust Learning of Deep Predictive Models from Noisy and Imbalanced Software Engineering Datasets** (2022), , Z Li, M Pan, Y Pei, T Zhang, L Wang, X Li , et al.[[pdf]](https://scholar.archive.org/work/fls7wlezhrdappl2f46gb6u5de/access/wayback/https://dl.acm.org/doi/pdf/10.1145/3551349.3556941)
- **XCode: Towards Cross-Language Code Representation with Large-Scale Pre-Training** (2022), , Z Lin, G Li, J Zhang, Y Deng, X Zeng, Y Zhang… , et al.[[pdf]]()
- **Understanding and Tackling Label Errors in Deep Learning-Based Vulnerability Detection (Experience Paper)** (2023), , X Nie, N Li, K Wang, S Wang, X Luo… , et al.[[pdf]]()

### *Data Noise*
- **Slice-Based Code Change Representation Learning** (2023), , F Zhang, B Chen, Y Zhao… , et al.[[pdf]](https://chenbihuan.github.io/paper/saner23-zhang-ccs2vec.pdf)
- **Are we building on the rock? on the importance of data preprocessing for code summarization** (2022), , L Shi, F Mu, X Chen, S Wang, J Wang, Y Yang… , et al.[[pdf]](https://dl.acm.org/doi/pdf/10.1145/3540250.3549145)
- **Neural-Machine-Translation-Based Commit Message Generation: How Far Are We?** (2018), , Z Liu, X Xia, AE Hassan, D Lo, Z Xing… , et al.[[pdf]](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=5299&context=sis_research)

## System Design and Learning
### *Data Snooping*
- **AutoTransform: automated code transformation to support modern code review process** (2022), , P Thongtanunam, C Pornprasit… , et al.[[pdf]](https://www.researchgate.net/profile/Patanamon-Thongtanunam-2/publication/358486098_AutoTransform_Automated_Code_Transformation_to_Support_Modern_Code_Review_Process/links/6204767d075f695e892eb1f4/AutoTransform-Automated-Code-Transformation-to-Support-Modern-Code-Review-Process.pdf)
- **Can Neural Clone Detection Generalize to Unseen Functionalitiesƒ** (2021), , C Liu, Z Lin, JG Lou, L Wen… , et al.[[pdf]](https://www.microsoft.com/en-us/research/uploads/prod/2022/01/Can-Neural-Clone-Detection-Generalize-to-UnseenFunctionalities.pdf)
- **CD-VulD: Cross-Domain Vulnerability Discovery Based on Deep Domain Adaptation** (2020), , S Liu, G Lin, L Qu, J Zhang, O De Vel… , et al.[[pdf]]()
- **Deep just-in-time defect prediction: how far are we?** (2021), , Z Zeng, Y Zhang, H Zhang, L Zhang , et al.[[pdf]](https://par.nsf.gov/servlets/purl/10273272)
- **Patching as translation: the data and the metaphor** (2020), , Y Ding, B Ray, P Devanbu… , et al.[[pdf]](https://dl.acm.org/doi/pdf/10.1145/3324884.3416587)
- **An empirical study of deep learning models for vulnerability detection** (2023), , B Steenhoek, MM Rahman, R Jiles… , et al.[[pdf]](https://arxiv.org/pdf/2212.08109)
- **Keeping Pace with Ever-Increasing Data: Towards Continual Learning of Code Intelligence Models** (2302), , S Gao, H Zhang, C Gao, C Wang , et al.[[pdf]](https://arxiv.org/pdf/2302.03482)
- **Revisiting Learning-based Commit Message Generation** (2023), , J Dong, Y Lou, D Hao, L Tan , et al.[[pdf]](https://www.cs.purdue.edu/homes/lintan/publications/commit-icse23.pdf)
- **Syntax and Domain Aware Model for Unsupervised Program Translation** (2302), , F Liu, J Li, L Zhang , et al.[[pdf]](https://arxiv.org/pdf/2302.03908)
- **How Effective Are Neural Networks for Fixing Security Vulnerabilities** (2023), , Y Wu, N Jiang, HV Pham, T Lutellier, J Davis… , et al.[[pdf]](https://arxiv.org/pdf/2305.18607)
- **Towards More Realistic Evaluation for Neural Test Oracle Generation** (2305), , Z Liu, K Liu, X Xia, X Yang , et al.[[pdf]](https://arxiv.org/pdf/2305.17047)
- **On the Evaluation of Neural Code Summarization** (2022), , E Shi, Y Wang, L Du, J Chen, S Han, H Zhang… , et al.[[pdf]](https://arxiv.org/pdf/2107.07112)

### *Spurious Correlations*
- **Deep Learning Based Vulnerability Detection: Are We There Yet?** (2021), , S Chakraborty, R Krishna, Y Ding… , et al.[[pdf]](https://arxiv.org/pdf/2009.07235)
- **Diet code is healthy: simplifying programs for pre-trained models of code** (2022), , Z Zhang, H Zhang, B Shen, X Gu , et al.[[pdf]](https://arxiv.org/pdf/2206.14390)
- **Explaining mispredictions of machine learning models using rule induction** (2021), , J Cito, I Dillig, S Kim, V Murali, S Chandra , et al.[[pdf]](https://www.cs.utexas.edu/~isil/md.pdf)
- **Interpreting Deep Learning-based Vulnerability Detector Predictions Based on Heuristic Searching** (2021), , D Zou, Y Zhu, S Xu, Z Li, H Jin, H Ye , et al.[[pdf]](https://par.nsf.gov/servlets/purl/10281044)
- **Thinking Like a Developer? Comparing the Attention of Humans with Neural Models of Code** (2021), , M Paltenghi, M Pradel , et al.[[pdf]](https://www.software-lab.org/publications/ase2021.pdf)
- **Vulnerability detection with fine-grained interpretations** (2021), , Y Li, S Wang, TN Nguyen , et al.[[pdf]](https://dl.acm.org/doi/pdf/10.1145/3468264.3468597)
- **What do they capture? a structural analysis of pre-trained language models for source code** (2022), , Y Wan, W Zhao, H Zhang, Y Sui, G Xu… , et al.[[pdf]](https://arxiv.org/pdf/2202.06840)
- **An empirical study of deep learning models for vulnerability detection** (2023), , B Steenhoek, MM Rahman, R Jiles… , et al.[[pdf]](https://arxiv.org/pdf/2212.08109)
- **Towards Efficient Fine-Tuning of Pre-trained Code Models: An Experimental Study and Beyond** (2023), , E Shi, Y Wang, H Zhang, L Du, S Han, D Zhang… , et al.[[pdf]](https://arxiv.org/pdf/2304.05216)

### *Inappropriate Data Proprocessing*
- **Deep Learning Based Vulnerability Detection: Are We There Yet?** (2021), , S Chakraborty, R Krishna, Y Ding… , et al.[[pdf]](https://arxiv.org/pdf/2009.07235)

### *Inappropriate Model Design*
- **Deep Learning Based Vulnerability Detection: Are We There Yet?** (2021), , S Chakraborty, R Krishna, Y Ding… , et al.[[pdf]](https://arxiv.org/pdf/2009.07235)
- **Enhancing DNN-Based Binary Code Function Search With Low-Cost Equivalence Checking** (2022), , H Wang, P Ma, Y Yuan, Z Liu, S Wang… , et al.[[pdf]]()
- **Improving automatic source code summarization via deep reinforcement learning** (2018), , Y Wan, Z Zhao, M Yang, G Xu, H Ying, J Wu… , et al.[[pdf]](https://arxiv.org/pdf/1811.07234)
- **Patching as translation: the data and the metaphor** (2020), , Y Ding, B Ray, P Devanbu… , et al.[[pdf]](https://dl.acm.org/doi/pdf/10.1145/3324884.3416587)
- **Reinforcement-Learning-Guided Source Code Summarization Using Hierarchical Attention** (2020), , W Wang, Y Zhang, Y Sui, Y Wan, Z Zhao… , et al.[[pdf]](https://opus.lib.uts.edu.au/bitstream/10453/139555/3/Binder1.pdf)
- **XCode: Towards Cross-Language Code Representation with Large-Scale Pre-Training** (2022), , Z Lin, G Li, J Zhang, Y Deng, X Zeng, Y Zhang… , et al.[[pdf]]()
- **RepresentThemAll: A Universal Learning Representation of Bug Reports** (2023), , S Fang, T Zhang, Y Tan, H Jiang… , et al.[[pdf]]()
- **Template-based Neural Program Repair** (2023), , X Meng, X Wang, H Zhang, H Sun… , et al.[[pdf]]()

## Performance Evaluation
### *Inappropriate Baseline*
- **Towards More Realistic Evaluation for Neural Test Oracle Generationr** (2305), , Z Liu, K Liu, X Xia, X Yang , et al.[[pdf]](https://arxiv.org/pdf/2305.17047)

### *Inappropriate Test Set*
- **Deep Learning Based Program Generation From Requirements Text: Are We There Yet?** (2020), , H Liu, M Shen, J Zhu, N Niu, G Li… , et al.[[pdf]](https://liuhuigmail.github.io/publishedPappers/CodeGeneration.pdf)
- **Generating realistic vulnerabilities via neural code editing: an empirical study** (2022), , Y Nong, Y Ou, M Pradel, F Chen, H Cai , et al.[[pdf]](https://dl.acm.org/doi/pdf/10.1145/3540250.3549128)

### *Low Reproducibility*
- **An extensive study on pre-trained models for program understanding and generation** (2022), , Z Zeng, H Tan, H Zhang, J Li, Y Zhang… , et al.[[pdf]](https://lingming.cs.illinois.edu/publications/issta2022.pdf)

### Inappropriate Performance Measures
- **Deep Learning Based Vulnerability Detection: Are We There Yet?** (2021), , S Chakraborty, R Krishna, Y Ding… , et al.[[pdf]](https://arxiv.org/pdf/2009.07235)
- **Improving automatic source code summarization via deep reinforcement learning** (2018), , Y Wan, Z Zhao, M Yang, G Xu, H Ying, J Wu… , et al.[[pdf]](https://arxiv.org/pdf/1811.07234)
- **Multi-task learning based pre-trained language model for code completion** (2020), , F Liu, G Li, Y Zhao, Z Jin , et al.[[pdf]](https://arxiv.org/pdf/2012.14631)
- **On the Value of Oversampling for Deep Learning in Software Defect Prediction** (2021), , R Yedida, T Menzies , et al.[[pdf]](https://arxiv.org/pdf/2008.03835)
- **Patching as translation: the data and the metaphor** (2020), , Y Ding, B Ray, P Devanbu… , et al.[[pdf]](https://dl.acm.org/doi/pdf/10.1145/3324884.3416587)
- **Reinforcement-Learning-Guided Source Code Summarization Using Hierarchical Attention** (2020), , W Wang, Y Zhang, Y Sui, Y Wan, Z Zhao… , et al.[[pdf]](https://opus.lib.uts.edu.au/bitstream/10453/139555/3/Binder1.pdf)
- **SynShine: Improved Fixing of Syntax Errors** (2022), , T Ahmed, NR Ledesma… , et al.[[pdf]]()
- **An empirical study of deep learning models for vulnerability detection** (2023), , B Steenhoek, MM Rahman, R Jiles… , et al.[[pdf]](https://arxiv.org/pdf/2212.08109)
- **Revisiting Learning-based Commit Message Generation** (2023), , J Dong, Y Lou, D Hao, L Tan , et al.[[pdf]](https://www.cs.purdue.edu/homes/lintan/publications/commit-icse23.pdf)
- **Tare: Type-Aware Neural Program Repair** (2023), , Q Zhu, Z Sun, W Zhang, Y Xiong… , et al.[[pdf]](https://xiongyingfei.github.io/papers/ICSE23a.pdf)
- **How Effective Are Neural Networks for Fixing Security Vulnerabilities** (2023), , Y Wu, N Jiang, HV Pham, T Lutellier, J Davis… , et al.[[pdf]](https://arxiv.org/pdf/2305.18607)
- **Towards More Realistic Evaluation for Neural Test Oracle Generation** (2305), , Z Liu, K Liu, X Xia, X Yang , et al.[[pdf]](https://arxiv.org/pdf/2305.17047)
- **GitHub Copilot AI pair programmer: Asset or Liability?** (2023), , AM Dakhel, V Majdinasab, A Nikanjam… , et al.[[pdf]](https://arxiv.org/pdf/2206.15331)

## Deployment and Maintainance
### *Lab-only evaluation*
- **Examining Zero-Shot Vulnerability Repair with Large Language Models** (2023), , H Pearce, B Tan, B Ahmad, R Karri… , et al.[[pdf]](https://arxiv.org/pdf/2112.02125)
- **A Performance-Sensitive Malware Detection System Using Deep Learning on Mobile Devices** (2020), , R Feng, S Chen, X Xie, G Meng… , et al.[[pdf]](https://arxiv.org/pdf/2005.04970)
- **Diet code is healthy: simplifying programs for pre-trained models of code** (2022), , Z Zhang, H Zhang, B Shen, X Gu , et al.[[pdf]](https://arxiv.org/pdf/2206.14390)
- **When Code Completion Fails: A Case Study on Real-World Completions** (2019), , VJ Hellendoorn, S Proksch, HC Gall… , et al.[[pdf]](http://www.sback.it/publications/icse2019b.pdf)
- **Lost at C: A User Study on the Security Implications of Large Language Model Code Assistants** (2023), , G Sandoval, H Pearce, T Nys, R Karri, S Garg… , et al.[[pdf]](https://www.usenix.org/system/files/sec23fall-prepub-353-sandoval.pdf)
- **Grounded Copilot: How Programmers Interact with Code-Generating Models** (2023), , S Barke, MB James, N Polikarpova , et al.[[pdf]](https://dl.acm.org/doi/pdf/10.1145/3586030)
- **LLaMA-Reviewer: Advancing Code Review Automation with Large Language Models through Parameter-Efficient Fine-Tuning** (2308), , J Lu, L Yu, X Li, L Yang, C Zuo , et al.[[pdf]](https://arxiv.org/pdf/2308.11148)
- **Compressing Pre-trained Models of Code into 3 MB** (2022), , J Shi, Z Yang, B Xu, HJ Kang, D Lo , et al.[[pdf]](https://dl.acm.org/doi/pdf/10.1145/3551349.3556964)

### *Model Attack Threats*
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

### *Security concerns in generated code*
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
