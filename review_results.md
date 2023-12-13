
This repository contains supplementary material for the paper "[Pitfalls in Language Models for Code Intelligence: A Taxonomy and Survey](https://arxiv.org/abs/2310.17903)", submitted to the ACM Computing Surveys journal.

> Modern language models (LMs) have been successfully employed in source code generation and understanding, leading to a significant increase in research focused on learning-based code intelligence, such as automated
bug repair, and test case generation. Despite their great potential, **language models for code intelligence (LM4Code) are susceptible to potential pitfalls, which hinder realistic performance and further impact their reliability and applicability in real-world deployment**. Such challenges drive the need for a comprehensive understanding - not just identifying these issues but delving into their possible implications and existing solutions to build more reliable language models tailored to code intelligence. Based on a well-defined systematic research approach, we conducted an extensive literature review to uncover the pitfalls inherent in LM4Code. Finally, 67 primary studies from top-tier venues have been identified. After carefully examining these studies, we designed a taxonomy of pitfalls in LM4Code research and conducted a systematic study to summarize the issues, implications, current solutions, and challenges of different pitfalls for LM4Code systems. We developed a comprehensive classification scheme that dissects pitfalls across four crucial aspects: data collection and labeling, system design and learning, performance evaluation, and deployment and maintenance. Through this study, we aim to provide a roadmap for researchers and practitioners, facilitating their understanding and utilization of LM4Code in reliable and trustworthy ways.

Please feel free to send a pull request to add papers and relevant content that are not listed here.  We uploaded our completed paper lists to Google Drive with detailed reviewed information. 

([Rewiew paper lists](https://docs.google.com/spreadsheets/d/1DtE7WxjmHkDi9-jPV3H3D68klXeiKLr4prQRVbL3Qgg/edit?usp=sharing))



# Papers
## Type Inference

- **Dos and Don'ts of Machine Learning in Computer Security** (2022), USENIX Security, D Arp, et al. [[pdf]](https://www.usenix.org/system/files/sec22-arp.pdf)
- **Machine/deep learning for software engineering: A systematic literature review** (2022), TSE, Simin Wang, et al. [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9772253)
- **Trustworthy AI: From principles to practices** (2023), arxiv, BO Li, et al. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3555803)

## Data Collection and Labeling
### *Unbalanced Distribution*
- **Deep Learning Based Vulnerability Detection** (2021), arxiv, S Chakraborty, R Krishna, Y Ding, et al. [[pdf]](https://arxiv.org/pdf/2009.07235)
- **Does data sampling improve deep learning-based vulnerability detection? Yeas! and Nays!** (2023), ICSE, X Yang, et al. [[pdf]](https://shaoweiwang2010.github.io/papers/ICSE_2023_Sampling_Vulnerablity.pdf)
- **On the Value of Oversampling for Deep Learning in Software Defect Prediction** (2021), TSE, R Yedida, T Menzies. [[pdf]](https://arxiv.org/pdf/2008.03835)
- **Robust Learning of Deep Predictive Models from Noisy and Imbalanced Software Engineering Datasets** (2022), ASE, Z Li, et al. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3551349.3556941)
- **An empirical study of deep learning models for vulnerability detection** (2023), arxiv, B Steenhoek, et al. [[pdf]](https://arxiv.org/pdf/2212.08109)

### *Label Errors*
- **Robust Learning of Deep Predictive Models from Noisy and Imbalanced Software Engineering Datasets** (2022), ASE, Z Li, et al. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3551349.3556941)
- **XCode: Towards Cross-Language Code Representation with Large-Scale Pre-Training** (2022), TOSEM, Z Lin, et al. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3506696)
- **Understanding and Tackling Label Errors in Deep Learning-Based Vulnerability Detection (Experience Paper)** (2023), ISSTA, X Nie, et al. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3597926.3598037)

### *Data Noise*
- **Slice-Based Code Change Representation Learning** (2023), SANER, F Zhang, et al. [[pdf]](https://chenbihuan.github.io/paper/saner23-zhang-ccs2vec.pdf)
- **Are we building on the rock? on the importance of data preprocessing for code summarization** (2022), FSE, L Shi, et al. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3540250.3549145)
- **Neural-Machine-Translation-Based Commit Message Generation: How Far Are We?** (2018), ASE, Z Liu, et al. [[pdf]](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=5299&context=sis_research)

## System Design and Learning
### *Data Snooping*
- **AutoTransform: automated code transformation to support modern code review process** (2022), ICSE, Thongtanunam, Patanamon, Chanathip Pornprasit, and Chakkrit Tantithamthavorn. [[pdf]](https://www.researchgate.net/profile/Patanamon-Thongtanunam-2/publication/358486098_AutoTransform_Automated_Code_Transformation_to_Support_Modern_Code_Review_Process/links/6204767d075f695e892eb1f4/AutoTransform-Automated-Code-Transformation-to-Support-Modern-Code-Review-Process.pdf)
- **Can Neural Clone Detection Generalize to Unseen Functionalitiesƒ** (2021), ASE, C Liu, et al. [[pdf]](https://www.microsoft.com/en-us/research/uploads/prod/2022/01/Can-Neural-Clone-Detection-Generalize-to-UnseenFunctionalities.pdf)
- **CD-VulD: Cross-Domain Vulnerability Discovery Based on Deep Domain Adaptation** (2020), TDSC, S Liu, et al. [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9054952)
- **Deep just-in-time defect prediction: how far are we?** (2021), ISSTA, Z Zeng, et al. [[pdf]](https://par.nsf.gov/servlets/purl/10273272)
- **Patching as translation: the data and the metaphor** (2020), ASE, Y Ding, et al. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3324884.3416587)
- **An empirical study of deep learning models for vulnerability detection** (2023), ICSE, B Steenhoek, et al. [[pdf]](https://arxiv.org/pdf/2212.08109)
- **Keeping Pace with Ever-Increasing Data: Towards Continual Learning of Code Intelligence Models** (2302), ICSE, S Gao, et al. [[pdf]](https://arxiv.org/pdf/2302.03482)
- **Revisiting Learning-based Commit Message Generation** (2023), ICSE, J Dong, Y Lou, D Hao, et al. [[pdf]](https://www.cs.purdue.edu/homes/lintan/publications/commit-icse23.pdf)
- **Syntax and Domain Aware Model for Unsupervised Program Translation** (2302), ICSE, F Liu, J Li, L Zhang. [[pdf]](https://arxiv.org/pdf/2302.03908)
- **How Effective Are Neural Networks for Fixing Security Vulnerabilities** (2023), ISSTA, Y Wu, N Jiang, HV Pham, et al. [[pdf]](https://arxiv.org/pdf/2305.18607)
- **Towards More Realistic Evaluation for Neural Test Oracle Generation** (2305), ISSTA, Z Liu, K Liu, X Xia, et al. [[pdf]](https://arxiv.org/pdf/2305.17047)
- **On the Evaluation of Neural Code Summarization** (2022), ICSE, E Shi, Y Wang, L Du, et al. [[pdf]](https://arxiv.org/pdf/2107.07112)

### *Spurious Correlations*
- **Deep Learning Based Vulnerability Detection: Are We There Yet?** (2021), TSE, S Chakraborty, R Krishna, Y Ding, et al. [[pdf]](https://arxiv.org/pdf/2009.07235)
- **Diet code is healthy: simplifying programs for pre-trained models of code** (2022), FSE, Z Zhang, H Zhang, B Shen, et al. [[pdf]](https://arxiv.org/pdf/2206.14390)
- **Explaining mispredictions of machine learning models using rule induction** (2021), FSE, J Cito, I Dillig, S Kim, et al. [[pdf]](https://www.cs.utexas.edu/~isil/md.pdf)
- **Interpreting Deep Learning-based Vulnerability Detector Predictions Based on Heuristic Searching** (2021), TOSEM, D Zou, Y Zhu, S Xu, et al. [[pdf]](https://par.nsf.gov/servlets/purl/10281044)
- **Thinking Like a Developer? Comparing the Attention of Humans with Neural Models of Code** (2021), ASE, M Paltenghi, M Pradel. [[pdf]](https://www.software-lab.org/publications/ase2021.pdf)
- **Vulnerability detection with fine-grained interpretations** (2021), FSE, Y Li, S Wang, TN Nguyen. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3468264.3468597)
- **What do they capture? a structural analysis of pre-trained language models for source code** (2022), ICSE, Y Wan, W Zhao, H Zhang, et al. [[pdf]](https://arxiv.org/pdf/2202.06840)
- **An empirical study of deep learning models for vulnerability detection** (2023), ICSE, B Steenhoek, MM Rahman, R Jiles, et al. [[pdf]](https://arxiv.org/pdf/2212.08109)
- **Towards Efficient Fine-Tuning of Pre-trained Code Models: An Experimental Study and Beyond** (2023), ISSTA, E Shi, Y Wang, H Zhang, et al. [[pdf]](https://arxiv.org/pdf/2304.05216)

### *Inappropriate Model Design*
- **Deep Learning Based Vulnerability Detection: Are We There Yet?** (2021), TSE, S Chakraborty, R Krishna, Y Ding, et al. [[pdf]](https://arxiv.org/pdf/2009.07235)
- **Enhancing DNN-Based Binary Code Function Search With Low-Cost Equivalence Checking** (2022), TSE, H Wang, P Ma, Y Yuan, et al. [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9707874)
- **Improving automatic source code summarization via deep reinforcement learning** (2018), ASE, Y Wan, Z Zhao, M Yang, et al.[[pdf]](https://arxiv.org/pdf/1811.07234)
- **Patching as translation: the data and the metaphor** (2020), ASE, Y Ding, B Ray, P Devanbu, et al.[[pdf]](https://dl.acm.org/doi/pdf/10.1145/3324884.3416587)
- **Reinforcement-Learning-Guided Source Code Summarization Using Hierarchical Attention** (2020), TSE, W Wang, Y Zhang, Y Sui, et al. [[pdf]](https://opus.lib.uts.edu.au/bitstream/10453/139555/3/Binder1.pdf)
- **XCode: Towards Cross-Language Code Representation with Large-Scale Pre-Training** (2022), TOSEM, Z Lin, G Li, J Zhang, et al. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3506696)
- **RepresentThemAll: A Universal Learning Representation of Bug Reports** (2023), ICSE, S Fang, T Zhang, Y Tan, et al. [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10172597)
- **Template-based Neural Program Repair** (2023), ICSE, X Meng, X Wang, H Zhang, et al. [[pdf]](https://github.com/mxx1219/TENURE/blob/main/paper.pdf)

## Performance Evaluation
### *Inappropriate Baseline*
- **Towards More Realistic Evaluation for Neural Test Oracle Generationr** (2023), ARXIV, Z Liu, K Liu, X Xia, et al. [[pdf]](https://arxiv.org/pdf/2305.17047)

### *Inappropriate Evaluation Dataset*
- **Deep Learning Based Program Generation From Requirements Text: Are We There Yet?** (2020), TSE, H Liu, M Shen, J Zhu, et al. [[pdf]](https://liuhuigmail.github.io/publishedPappers/CodeGeneration.pdf)
- **Generating realistic vulnerabilities via neural code editing: an empirical study** (2022), FSE, Y Nong, Y Ou, M Pradel, et al. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3540250.3549128)

### *Low Reproducibility*
- **An extensive study on pre-trained models for program understanding and generation** (2022), ISSTA, Z Zeng, H Tan, H Zhang, et al. [[pdf]](https://lingming.cs.illinois.edu/publications/issta2022.pdf)

### *Inappropriate Performance Measures*
- **Deep Learning Based Vulnerability Detection: Are We There Yet?** (2021), TSE, S Chakraborty, R Krishna, Y Ding, et al. [[pdf]](https://arxiv.org/pdf/2009.07235)
- **Improving automatic source code summarization via deep reinforcement learning** (2018), ASE, Y Wan, Z Zhao, M Yang, et al. [[pdf]](https://arxiv.org/pdf/1811.07234)
- **Multi-task learning based pre-trained language model for code completion** (2020), ASE, F Liu, G Li, Y Zhao, et al. [[pdf]](https://arxiv.org/pdf/2012.14631)
- **On the Value of Oversampling for Deep Learning in Software Defect Prediction** (2021), TSE, R Yedida, T Menzies. [[pdf]](https://arxiv.org/pdf/2008.03835)
- **Patching as translation: the data and the metaphor** (2020), ASE, Y Ding, B Ray, P Devanbu, et al. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3324884.3416587)
- **Reinforcement-Learning-Guided Source Code Summarization Using Hierarchical Attention** (2020), TSE, W Wang, Y Zhang, Y Sui, et al. [[pdf]](https://opus.lib.uts.edu.au/bitstream/10453/139555/3/Binder1.pdf)
- **SynShine: Improved Fixing of Syntax Errors** (2022), TSE, Ahmed T, Ledesma N R, Devanbu P. [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9913705)
- **An empirical study of deep learning models for vulnerability detection** (2023), ICSE, B Steenhoek, MM Rahman, R Jiles, et al. [[pdf]](https://arxiv.org/pdf/2212.08109)
- **Revisiting Learning-based Commit Message Generation** (2023), ICSE, J Dong, Y Lou, D Hao, et al. [[pdf]](https://www.cs.purdue.edu/homes/lintan/publications/commit-icse23.pdf)
- **Tare: Type-Aware Neural Program Repair** (2023), ICSE, Q Zhu, Z Sun, W Zhang, et al. [[pdf]](https://xiongyingfei.github.io/papers/ICSE23a.pdf)
- **How Effective Are Neural Networks for Fixing Security Vulnerabilities** (2023), ISSTA, Y Wu, N Jiang, HV Pham, et al. [[pdf]](https://arxiv.org/pdf/2305.18607)
- **Towards More Realistic Evaluation for Neural Test Oracle Generation** (2305), ISSTA, Z Liu, K Liu, X Xia, et al. [[pdf]](https://arxiv.org/pdf/2305.17047)
- **GitHub Copilot AI pair programmer: Asset or Liability?** (2023), JSS, AM Dakhel, V Majdinasab, A Nikanjam, et al. [[pdf]](https://arxiv.org/pdf/2206.15331)

## Deployment and Maintainance
### *Real-World Constraints*
- **Examining Zero-Shot Vulnerability Repair with Large Language Models** (2023), S&P, H Pearce, B Tan, B Ahmad, et al. [[pdf]](https://arxiv.org/pdf/2112.02125)
- **A Performance-Sensitive Malware Detection System Using Deep Learning on Mobile Devices** (2020), TIFS, R Feng, S Chen, X Xie, et al. [[pdf]](https://arxiv.org/pdf/2005.04970)
- **Diet code is healthy: simplifying programs for pre-trained models of code** (2022), FSE, Z Zhang, H Zhang, B Shen, et al.[[pdf]](https://arxiv.org/pdf/2206.14390)
- **When Code Completion Fails: A Case Study on Real-World Completions** (2019), ICSE, VJ Hellendoorn, S Proksch, HC Gall, et al. [[pdf]](http://www.sback.it/publications/icse2019b.pdf)
- **Lost at C: A User Study on the Security Implications of Large Language Model Code Assistants** (2023), arxiv, G Sandoval, H Pearce, T Nys, et al. [[pdf]](https://www.usenix.org/system/files/sec23fall-prepub-353-sandoval.pdf)
- **Grounded Copilot: How Programmers Interact with Code-Generating Models** (2023), OOPSLA1, S Barke, MB James, N Polikarpova. [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3586030)
- **LLaMA-Reviewer: Advancing Code Review Automation with Large Language Models through Parameter-Efficient Fine-Tuning** (2308), arxiv, J Lu, L Yu, X Li, et al.[[pdf]](https://arxiv.org/pdf/2308.11148)
- **Compressing Pre-trained Models of Code into 3 MB** (2022), ASE, J Shi, Z Yang, B Xu, et al.[[pdf]](https://dl.acm.org/doi/pdf/10.1145/3551349.3556964)

### *Attack Threats*
- **You Autocomplete Me: Poisoning Vulnerabilities in Neural Code Completion** (2021), USENIX Security, R Schuster, C Song, E Tromer, et al. [[pdf]](https://www.usenix.org/system/files/sec21-schuster.pdf)
- **Adversarial Robustness of Deep Code Comment Generation** (2022), TOSEM, Y Zhou, X Zhang, J Shen, et al. [[pdf]](https://arxiv.org/pdf/2108.00213)
- **An extensive study on pre-trained models for program understanding and generation** (2022), ISSTA, Z Zeng, H Tan, H Zhang, et al. [[pdf]](https://lingming.cs.illinois.edu/publications/issta2022.pdf)
- **Generating Adversarial Examples for Holding Robustness of Source Code Processing Models** (2020), AAAI, H Zhang, Z Li, G Li, et al. [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/5469/5325)
- **Semantic Robustness of Models of Source Code** (2020), SANER, G Ramakrishnan, J Henkel, Z Wang, et al. [[pdf]](https://arxiv.org/pdf/2002.03043)
- **You see what I want you to see: poisoning vulnerabilities in neural code search** (2022), FSE, Y Wan, S Zhang, H Zhang, et al. [[pdf]](https://opus.lib.uts.edu.au/bitstream/10453/164890/2/fse22_code_attack_camera%20%281%29.pdf)
- **Contrabert: Enhancing code pre-trained models via contrastive learning** (2023), ICSE, S Liu, B Wu, X Xie, et al. [[pdf]](https://arxiv.org/pdf/2301.09072)
- **On the robustness of code generation techniques: An empirical study on github copilot** (2023), ICSE, A Mastropaolo, L Pascarella, E Guglielmi, et al. [[pdf]](https://arxiv.org/pdf/2302.00438)
- **Two sides of the same coin: Exploiting the impact of identifiers in neural code comprehension** (2023), ICSE, S Gao, C Gao, C Wang, et al. [[pdf]](https://yuyue.github.io/res/paper/NeuralCode-ICSE2023.pdf)
- **Multi-target Backdoor Attacks for Code Pre-trained Models** (2023), ACL, Y Li, S Liu, K Chen, et al. [[pdf]](https://arxiv.org/pdf/2306.08350)
- **Backdooring Neural Code Search** (2023), ACL, W Sun, Y Chen, G Tao, et al. [[pdf]](https://arxiv.org/pdf/2305.17506)
- **ReCode: Robustness Evaluation of Code Generation Models** (2022), ACL, S Wang, Z Li, H Qian, et al. [[pdf]](https://arxiv.org/pdf/2212.10264)
- **Natural Attack for Pre-trained Models of Code** (2022), ICSE, Z Yang, J Shi, J He, et al. [[pdf]](https://arxiv.org/pdf/2201.08698)
- **Coprotector: Protect open-source code against unauthorized training usage with data poisoning** (2022), WWW, Z Sun, X Du, F Song, et al. [[pdf]](https://arxiv.org/pdf/2110.12925)
- **On the Security Vulnerabilities of Text-to-SQL Models** (2211), ISSRE, X Peng, Y Zhang, J Yang, et al. [[pdf]](https://arxiv.org/pdf/2211.15363)

### *Security Concerns in Generated Code*
- **Asleep at the Keyboard? Assessing the Security of GitHub Copilot's Code Contributions** (2022), S&P, H Pearce, B Ahmad, B Tan, et al. [[pdf]](https://arxiv.org/pdf/2108.09293.pdf?trk=article-ssr-frontend-pulse_x-social-details_comments-action_comment-text)
- **Automated repair of programs from large language models** (2023), ICSE, Z Fan, X Gao, M Mirchev, et al. [[pdf]](https://abhikrc.com/pdf/ICSE23.pdf)
- **Cctest: Testing and repairing code completion systems** (2023), ICSE, Z Li, C Wang, Z Liu, et al. [[pdf]](https://arxiv.org/pdf/2208.08289)
- **Analyzing Leakage of Personally Identifiable Information in Language Models** (2023), S&P, N Lukas, A Salem, R Sim, et al. [[pdf]](https://arxiv.org/pdf/2302.00539)
- **CodexLeaks: Privacy Leaks from Code Generation Language Models in GitHub Copilot** (2023), USENIX Security, L Niu, S Mirza, Z Maradni, et al. [[pdf]](https://www.usenix.org/system/files/usenixsecurity23-niu.pdf)

# Public Tools
-  **ACCENT** (Adversarial Code Comment gENeraTor)
    - masked training
    - an identifier substitution approach to craft adversarial code snippets, which are syntactically correct and semantically close to the original code snippet, but may mislead the DNNs to produce completely irrelevant code comments.
    - TOSEM 2022
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3501256), [[code]](https://github.com/zhangxq-1/ACCENT-repository)

- **AutoTransform**
    - a Transformer-based NMT architecture to handle long sequences
    - through addressing the out-off vocabulary, BPE(Byte-Pair Encoding)
    - ICSE 2022
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3510003.3510067), [[code]](https://github.com/awsm-research/AutoTransform-Replication)

- **Functionality-generalization**
    - training set with diverse functionalities，out-of-vocabulary problem， incorporating locality into model architecture
    - ASE 2021
    - [[pdf]](https://ieeexplore.ieee.org/document/9678907), [[code]](https://github.com/thousfeet/Functionality-generalization)

- **CD-VulD**
    - a new system for Cross Domain Software Vulnerability Discovery using deep learning (DL) and domain adaptation (DA).
    - learn cross-domain representations
    - TDSC 2022
    - [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9054952)

- **DietCode**
    - explain to decrease the tokens
    - aims at lightweight leverage of large pre-trained models for source code
    - FSE 2022
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3540250.3549094), [[code]](https://github.com/zhangzwwww/DietCode)

- **BinUSE**
    - a practical and efficient equivalence check, using under-constrained symbolic execution (USE)
    - TSE 2023
    - [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9707874)

- **mmd**
    - model-agnostic explaination
    - The output of the technique can be useful for understanding limitations of the training data or the model itself
    - FSE 2021
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3468264.3468614), [[code]](https://github.com/facebookresearch/mmd)

- **Metropolis-Hastings Modifier (MHM)**
    - Adversarial Training
    - generates adversarial examples for DL models specialized for source code processing
    - AAAI 2020
    - [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/5469), [[code]](https://github.com/Metropolis-Hastings-Modifier/MHM)

- **ReVeal**
    - Data clean
    - TSE 2021
    - [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9448435), [[code]](https://github.com/VulDetProject/ReVeal)

- **ghost-dl**
    - a oversampling method
    - non-DL technique, (artificially generating members of a minority class prior to running a learner) dramatically improves deep learning
    - TSE 2021
    - [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9429914), [[code]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9429914)

- **HAN**
    - Hierarchical Attention Network
    - multiple structural code features (including control flow graph and AST) to reflect the code hierarchy, a two-layer attention network (a token layer and a statement layer)
    - TSE 2022
    - [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9031440)

- **RobustTrainer**
    - learning deep predictive models on raw training datasets where the mislabelled samples and the imbalanced classes coexist.
    - ASE 2022
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3551349.3556941), [[code]](https://github.com/RobustTrainer/RobustTrainers)

 - **SYNSHINE**
    - input with compiler errors, large neural model leveraging unsupervised pre-training, multi-label classification
    - TSE 2023
    - [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9913705), [[code]](https://zenodo.org/record/7789329)

- **CARROTA**
    - adversarial training and detection, an optimization-based attack technique
    - TOSEM 2022
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3511887), [[code]](https://github.com/SEKE-Adversary/CARROT)

- **CAT**
    - automated code-comment cleaning tool
    - FSE 2022
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3540250.3549145), [[code]](https://github.com/BuiltOntheRock/FSE22_BuiltOntheRock), [[pyton]](https://pypi.org/project/FSE22-CAT/0.0.1)

- **apr4codex**
    - APR / prompts for repair, APR techniques fix the incorrect solutions produced by language models in LeetCode contests.
    - ICSE 2023
    - [[pdf]](https://arxiv.org/pdf/2205.10583.pdf), [[code]](https://github.com/zhiyufan/apr4codex)

- **CCTEST**
    - test and repair code completion systems in black-box setting
    - ICSE 2023
    - [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10172845), [[HomePage]](https://sites.google.com/view/cctest-info/main-page)

- **ContraBERT**
    - an approach aims to improve the robustness of pre-trained models via contrastive learning, Contrastive Learning
    - ICSE 2023
    - [[pdf]](https://arxiv.org/pdf/2301.09072.pdf), [[HomePage]](https://sites.google.com/view/contrabert)

- **REPEAT**
    - a novel method for continual learning of code intelligence models
    - ICSE 2023
    - [[pdf]](https://arxiv.org/abs/2302.03482.pdf), [[code]](https://github.com/ReliableCoding/REPEAT)

- **RepresentThemAll**
    - a pre-trained approach that can learn the universal representation of bug reports and handle multiple downstream tasks
    - ICSE 2023
    - [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10172597), [[code]](https://github.com/ICSE-2023/RepresentThemALL)

- **TENURE** 
    - Template-based Neural Program Repair, which simultaneously absorbs the advantages of template- based and NMT-based APR methods
    - ICSE 2023
    - [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10172686), [[code]](https://github.com/mxx1219/TENURE)

- **CREAM**
    - A counterfactual reasoning-based framework, multi-task learning and counterfactual inference
    - ICSE 2023
    - [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10172869), [[code]](https://github.com/ReliableCoding/CREAM)
    
- **Telly**
    - four probing tasks related to lexical, syntactic, semantic, and structural code properties
    - Telly-𝐾 (efficiently fine-tunes pre-trained code models via selective layer freezing)
    - ISSTA 2023
    - [[pdf]](https://arxiv.org/pdf/2304.05216.pdf), [[code]](https://github.com/DeepSoftwareAnalytics/Telly)

- **TEval+**
    - a more realistic evaluation method TEval+ for NTOG and summarize seven rules of thumb to boost NTOG approaches into their practical usage
    - ISSTA 2023
    - [[pdf]](https://arxiv.org/pdf/2305.17047.pdf), [[code]](https://github.com/microsoft/toga)

- **analysing_pii_leakage**
    -  rigorous game-based definitions for three types of PII leakage via black-box extraction, inference, and reconstruction attacks with only API access to an LM
    - S&P 2023
    - [[pdf]](https://arxiv.org/pdf/2302.00539.pdf), [[code]](https://github.com/microsoft/analysing_pii_leakage)

- **CodexLeaks**
    - a semi-automated filtering method using a blind membership inference attack
    - USENIX Security 2023
    - [[pdf]](https://www.usenix.org/system/files/usenixsecurity23-niu.pdf), [[code]](https://github.com/niuliang42/CodexLeaks)

- **CoProtector**
    - Utilizing data poisoning techniques to arm source code repositories for defending against such exploits
    - WWW 2022
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512225), [[code]](https://github.com/v587su/CoProtector)

- **LLaMA-Reviewer**
    - an innovative framework that leverages the capabilities of LLaMA, a popular LLM, in the realm of code review
    - ISSRE 2023
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3485447.3512225), [[code]](https://doi.org/10.5281/zenodo.7991113)

- **Compressor**
    - a novel approach that can compress the pre-trained models of code into extremely small models with negligible performance sacrifice
    - ASE 2022
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3551349.3556964), [[code]](https://github.com/soarsmu/Compressor)

- **NNGen**
    - a simpler and faster approach to generate concise commit messages using the nearest neighbor algorithm
    - ASE 2018
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3238147.3238190), [[code]](https://goo.gl/63B976)

# New model
- **Actor-critic network**
    - an abstract syntax tree structure as well as sequential content of code snippets into a deep reinforcement learning framework
    - ASE 2018
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3238147.3238206)
      
- **CugLM**
    - a multi-task learning based pre-trained language model for code understanding and code generation with a Transformer-based neural architecture
    - ASE 2021
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3324884.3416591)

-  **SDA-Trans**
    -  adversarial training, unsupervised training
    - a syntax and domain-aware model for program translation, which leverages the syntax structure and domain knowledge to enhance the cross-lingual transfer ability
    - ICSE 2023
    - [[pdf]](https://arxiv.org/pdf/2302.03908.pdf)

- **Tare**
    -  a type-aware model for neural program repair to learn the typing rules
    - ICSE 2023
    - [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10172781), [[code]](https://zenodo.org/record/7029405)

- 
  
# XAI
- **Interpreting Deep Learning-based Vulnerability Detector Predictions Based on Heuristic Searching**
    - a framework for interpreting predictions of deep learning-based vulnerability detectors
    - The framework is centered at identifying a small number of tokens that make important contributions to a particular prediction, the novelty of the framework can be characterized as follows: (1) it does not assume the detector’s local decision boundary is linear; (2) it does not assume the features are independent of each other but instead braces the association between features when searching for important features; (3) it searches important features by perturbing examples, while considering feature combinations rather than individual features.
    - TOSEM 2021
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3429444)

- **Thinking Like a Developer? Comparing the Attention of Humans with Neural Models of Code**
    - A methodology for recording human attention
    - ASE 2021
    - [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9678712), [[code]](https://github.com/MattePalte/thinking-like-a-developer)

-  **Vulnerability detection with fine-grained interpretations**
    - IVDetect, an interpretable vulnerability detector with the philosophy of using Artificial Intelligence (AI) to detect vulnerabilities
    - FSE 2021
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3468264.3468597), [[code]](https://github.com/vulnerabilitydetection/VulnerabilityDetectionResearch)

- **What do they capture? a structural analysis of pre-trained language models for source code**
    - NaturalCC, a sequence modeling toolkit that allows researchers and developers to train custom models for many software engineering tasks
    - ICSE 2022
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3510003.3510050), [[code]](https://github.com/CGCL-codes/naturalcc)

- **ReCode: Robustness Evaluation of Code Generation Models**
    - a Robustness Evaluation framework for Code, aiming to provide comprehensive assessment for robustness of code generation models
    - define robustness metrics based on over 30 transformations for code on docstrings, function and variable names, code syntax, and code format
    - ACL 2023
    - [[pdf]](https://aclanthology.org/2023.acl-long.773.pdf), [[code]](https://github.com/amazon-science/recode.)

# New benchmark
- **Deep Learning Based Program Generation From Requirements Text: Are We There Yet?**
    - [[ReCa]](https://github.com/ds4an/CoDas4CG), a large scale dataset that is composed of longer requirements as well as validated implementations
    - TSE 2022
    - [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9173704)

- **Deep Learning Based Vulnerability Detection: Are We There Yet?**
    - [[Chromium_And_Debian_Vulnerability_Data]](https://bit.ly/3bX30ai), curated a real-world dataset from developer/user reported vulnerabilities of Chromium and Debian projects
    - TSE 2021
    - [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9448435)

- **Generating realistic vulnerabilities via neural code editing: an empirical study**
    - [[SARD]](https://samate.nist.gov/SARD), Synthetic dataset
    - [[Real-world dataset]](https://zenodo.org/record/6897604), a real-world dataset based on BigVul and PatchDB
    - FSE 2022
    - [[pdf]](https://dl.acm.org/doi/pdf/10.1145/3540250.3549128)

- **ReCode: Robustness Evaluation of Code Generation Models**
    - robustness evaluation metrics for code-generation tasks: Robust Passs@k, Robust Drops@k, and Robust Relatives@k
    - ACL 2023
    - [[pdf]](https://aclanthology.org/2023.acl-long.773.pdf)


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
