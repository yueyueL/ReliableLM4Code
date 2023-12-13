# [ReliableLM4Code](https://yueyuel.github.io/ReliableLM4Code/)

This repository extends from our previous survey paper, "[Pitfalls in Language Models for Code Intelligence: A Taxonomy and Survey](https://arxiv.org/abs/2310.17903)". It includes necessary information for our research and a curated collection of LM4Code papers and other resources (datasets, tutorials, etc.). The focus is primarily on papers that use pre-trained models, especially large language models, to improve the reliability of language models in Software Engineering research.

For more details, please access this [site](https://yueyuel.github.io/ReliableLM4Code/)


> Modern language models (LMs) have been successfully employed in source code generation and understanding, leading to a significant increase in research focused on learning-based code intelligence, such as automated
bug repair, and test case generation. Despite their great potential, **language models for code intelligence (LM4Code) are susceptible to potential pitfalls, which hinder realistic performance and further impact their reliability and applicability in real-world deployment**. Such challenges drive the need for a comprehensive understanding - not just identifying these issues but delving into their possible implications and existing solutions to build more reliable language models tailored to code intelligence. Based on a well-defined systematic research approach, we conducted an extensive literature review to uncover the pitfalls inherent in LM4Code. Finally, 67 primary studies from top-tier venues have been identified. After carefully examining these studies, we designed a taxonomy of pitfalls in LM4Code research and conducted a systematic study to summarize the issues, implications, current solutions, and challenges of different pitfalls for LM4Code systems. We developed a comprehensive classification scheme that dissects pitfalls across four crucial aspects: data collection and labeling, system design and learning, performance evaluation, and deployment and maintenance. Through this study, we aim to provide a roadmap for researchers and practitioners, facilitating their understanding and utilization of LM4Code in reliable and trustworthy ways.

Please feel free to send a pull request to add papers and relevant content that are not listed here.  We uploaded our completed paper lists to Google Drive with detailed reviewed information. 

## Content
- [About our survey](https://yueyuel.github.io/ReliableLM4Code/docs/reliable_LM4Code_review)
- [What is LM4Code?](https://yueyuel.github.io/ReliableLM4Code/docs/LM4Code)
    - [LLMs](https://yueyuel.github.io/ReliableLM4Code/docs/LM4Code/LMmodels/)
    - [LM4Code Tasks](https://yueyuel.github.io/ReliableLM4Code/docs/LM4Code/SEtasks/)
    - [Benchmark Datasets](https://yueyuel.github.io/ReliableLM4Code/docs/LM4Code/benchmark/)
- [Relevant Surveys and Tutorial](https://yueyuel.github.io/ReliableLM4Code/docs/relevant_surveys/)
- [Explanable LM4Code](https://yueyuel.github.io/ReliableLM4Code/docs/xai_lm4code/)
- [Top Researchers in LM4Code](https://yueyuel.github.io/ReliableLM4Code/docs/researchers/)
- [Relevant Venus](https://yueyuel.github.io/ReliableLM4Code/docs/venus/)


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


# Language Models for Code Intelligence
## Decoder-only Models

### GPT-1
- Release Date: 2018-06
- Institute: OpenAI
- Paper: [Improving Language Understanding by Generative Pre-Training](https://www.cs.ubc.ca/~amuham01/LING530/papers/radford2018improving.pdf)

### GPT-2
- Release Date: 2019-02
- Institute: OpenAI
- Paper: [Language Models are Unsupervised Multitask Learners](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)

### GPT-3
- Release Date: 2020-05
- Institute: OpenAI
- Paper: [Language models are few-shot learners](https://papers.nips.cc/paper/2020/file/1457c0d6bfcb4967418bfb8ac142f64a-Paper.pdf)

### Codex
- Release Date: 2021-08
- Institute: OpenAI
- Paper: [Evaluating Large Language Models Trained on Code](https://arxiv.org/pdf/2107.03374.pdf)

### GPT-NeoX
- Release Date: 2022-04
- Access: [ckpt](https://github.com/EleutherAI/gpt-neox)
- Paper: [GPT-NeoX-20B: An Open-Source Autoregressive Language Model](https://arxiv.org/pdf/2204.06745.pdf)

### GPT-Neo
- Release Date: 2021-03
- Source: [Github](https://github.com/EleutherAI/gpt-neo)

### CodeGen
- Release Date: 2022/03
- Paper: [CodeGen: An Open Large Language Model for Code with Multi-Turn Program Synthesis](https://arxiv.org/abs/2203.13474)

### InstructGPT
- Release Date: 2022/01
- Paper: [Training language models to follow instructions with human feedback](http://arxiv.org/abs/2203.02155v1)

### CodeGeeX
- Title: CodeGeeX: A Pre-Trained Model for Code Generation with Multilingual Evaluations on HumanEval-X
- Year: 2023
- Paper: [Link](https://arxiv.org/abs/2303.17568)

### GPT-J
- Release Date: 2023/06
- Access: [GPT-J-6B](https://github.com/kingoflolz/mesh-transformer-jax/#gpt-j-6b), [GPT4All-J](https://github.com/nomic-ai/gpt4all#raw-model)
- Paper: [GPT-J-6B: 6B JAX-Based Transformer](https://arankomatsuzaki.wordpress.com/2021/06/04/gpt-j/)

### LLaMA
- Release Date: 2023-02
- Institute: Meta
- Paper: [LLaMA: Open and Efficient Foundation Language Models](https://research.facebook.com/publications/llama-open-and-efficient-foundation-language-models/)

### ChatGPT
- Release Date: 2022-11
- Access: [demo](https://openai.com/blog/chatgpt/), [api](https://share.hsforms.com/1u4goaXwDRKC9-x9IvKno0A4sk30)
- Origin: [Blog](https://openai.com/blog/chatgpt/)

### StableLM-Alpha
- Release Date: 2023/04
- Access: [StableLM-Alpha](https://github.com/Stability-AI/StableLM#stablelm-alpha)
- Paper: [Stability AI Launches the First of its StableLM Suite of Language Models](https://stability.ai/blog/stability-ai-launches-the-first-of-its-stablelm-suite-of-language-models)


### InCoder
- Paper: "InCoder: A Generative Model for Code Infilling and Synthesis"
- Authors: Daniel Fried et al.
- Release Date: 2023   
- Paper: [Link](http://arxiv.org/abs/2204.05999)

### GPT-4
- Release Date: 2023-03
- Institute: OpenAI
- Paper: [GPT-4 Technical Report](https://openai.com/research/gpt-4)

### WizardCoder
- Access: [WizardCoder](https://github.com/nlpxucan/WizardLM
- Release Date: 2023
- Paper: [WizardCoder: Empowering Code Large Language Models with Evol-Instruct
](https://arxiv.org/abs/2306.08568)

### PanGu-Coder
- Part of: PanGu-α
- Release Date: 2020
- Paper: ["PanGu-α: Large-scale Autoregressive Pretrained Chinese Language Models with Auto-parallel Computation"](https://arxiv.org/abs/2010.11934)

### OPT
- Release Date: 2022-05
- Access: [api](https://opt.alpa.ai), [ckpt](https://github.com/facebookresearch/metaseq/tree/main/projects/OPT)
- Paper: [OPT: Open Pre-trained Transformer Language Models](https://arxiv.org/pdf/2205.01068.pdf)

### StarCoder
- Release Date: 2023/05
- Access: [starcoder](https://huggingface.co/bigcode/starcoder)
- Papers: [StarCoder: A State-of-the-Art LLM for Code](https://huggingface.co/blog/starcoder), [StarCoder: May the source be with you!](https://drive.google.com/file/d/1cN-b9GnWtHzQRoE7M7gAEyivY0kl4BYs/view)

### SantaCoder
- Release Date: 2023/01
- Access: [santacoder](https://huggingface.co/bigcode/santacoder)
- Paper: [SantaCoder: don't reach for the stars!](https://arxiv.org/abs/2301.03988)

### PaLM
- Release Date: 2022-04
- Institute: Google
- Paper: [PaLM: Scaling Language Modeling with Pathways](https://arxiv.org/pdf/2204.02311.pdf)

### Vicuna
- Release Date: 2023/03
- Blog: [Link](https://lmsys.org/blog/2023-03-30-vicuna/)

### Flan-UL2
- Release Date: 2023-03
- Institute: Google
- Blog: [Flan-UL2 Blog](https://www.yitay.net/blog/flan-ul2-20b)

### CPM-Bee
- Release Date: 2022-10
- Institute: Baidu
- Paper: [CPM: A Large-scale Generative Chinese Pre-trained Language Model](https://arxiv.org/pdf/2012.00413.pdf)

### MT-NLG
- Release Date: 2022-01
- Institute: Microsoft
- Paper: [Using DeepSpeed and Megatron to Train Megatron-Turing NLG 530B, A Large-Scale Generative Language Model](https://arxiv.org/pdf/2201.11990.pdf)

### GLM
- Release Date: 2022-10
- Institute: Tsinghua University
- Paper: [GLM-130B: AN OPEN BILINGUAL PRE-TRAINED MODEL](https://arxiv.org/pdf/2210.02414.pdf)

### YaLM
- Release Date: 2022-06
- Institute: Yandex
- Blog: [YaLM Blog](https://medium.yandex/yandex-publishes-yalm-100b-its-the-largest-gpt-like-neural-network-in-open-source-d1df53d0e9a6)

### Alpaca
- Release Date: 2023-03
- Institute: Stanford University
- Access: [Alpaca GitHub](https://github.com/tatsu-lab/stanford_alpaca)

### RWKV-4
- Release Date: 2022-09
- Institute: Independent (BlinkDL)
- Access: [RWKV-4 GitHub](https://github.com/BlinkDL/RWKV-LM)

### Sparrow
- Release Date: 2022-09
- Institute: DeepMind
- Paper: [Improving alignment of dialogue agents via targeted human judgements](https://arxiv.org/pdf/2209.14375.pdf)

### Falcon
- Release Date: 2023-05
- Institute: Technology Innovation Institute (TII)
- Access: [Falcon Homepage](https://falconllm.tii.ae)

### Code Llama
- Release Date: 2023
- Institute: Meta (Facebook)
- Paper: [Code Llama: Open Foundation Models for Code](https://ai.meta.com/research/publications/code-llama-open-foundation-models-for-code/)

### RedPajama-INCITE
- Release Date: Not specified
- Blog: [RedPajama-INCITE Blog](https://www.together.xyz/blog/redpajama-models-v1)

### DeciCoder-1B
- Release Date: 2023-08
- Institute: Deci AI
- Blog: [DeciCoder Blog](https://deci.ai/blog/decicoder-efficient-and-accurate-code-generation-llm/)

### OpenLLaMA
- Release Date: 2023-05
- Institute: Not specified
- Access: [OpenLLaMA Access](https://huggingface.co/Salesforce/codegen25-7b-multi/blob/main/README.md)


### CodeGPT
- Release Date: 2021
- Paper: [CodeXGLUE: A Machine Learning Benchmark Dataset for Code Understanding and Generation](https://arxiv.org/pdf/2102.04664.pdf)


## Encoder-only Models
### BERT
- Release Date: 2018-10
- Institute: Google
- Paper: [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://aclanthology.org/N19-1423.pdf)

### ALBERT
- Release Date: 2019
- Paper: [ALBERT: A Lite BERT for Self-supervised Learning of Language Representations](https://arxiv.org/abs/1909.11942)

### RoBERTa
- Release Date: 2019
- Paper: [RoBERTa: A Robustly Optimized BERT Pretraining Approach](https://arxiv.org/abs/1907.11692)

### CodeBERT
- Release Date: 2020-04
- Institute: Microsoft
- Paper: [CodeBERT: A Pre-Trained Model for Programming and Natural Languages](https://arxiv.org/abs/2002.08155)

### GraphCodeBERT
- Release Date: 2022/03
- Access: [GraphCodeBERT](https://huggingface.co/microsoft/graphcodebert-base)
- Paper: [GraphCodeBERT: Pre-training Code Representations with Data Flow
](https://arxiv.org/abs/2009.08366)

## Encoder-decoder Models
### AlphaCode
- Release Date: 2022/02
- Access: [AlphaCode](https://alphacode.deepmind.com/)
- Institute: DeepMind

### T5
- Release Date: 2019
- Paper: [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/abs/1910.10683)
- Checkpoint: [Link](https://huggingface.co/t5-11b)

### CodeT5
- Release Date: 2021
- Access: [CodeT5](https://huggingface.co/salesforce/codet5-small)
- Paper: [CodeT5: Identifier-aware Unified Pre-trained Encoder-Decoder Models for Code Understanding and Generation](https://arxiv.org/abs/2109.00859)


### CodeT5+
- Release Date: 2023/05
- Access: [CodeT5+](https://github.com/salesforce/CodeT5/tree/main/CodeT5+)
- Paper: [CodeT5+: Open Code Large Language Models for Code Understanding and Generation](https://arxiv.org/abs/2305.07922)


### UnixCoder
- Release Date: 2022
- Access: [UniXcoder on Hugging Face](https://huggingface.co/microsoft/unixcoder-base)
- Paper: [UniXcoder: Unified Cross-Modal Pre-training for Code Representation
](https://arxiv.org/abs/2203.03850)

### PLBART
- Release Date: 2021
- Paper: [Unified Pre-training for Program Understanding and Generation
](https://arxiv.org/abs/2103.06333)


### CodeReviewer
- Release Date: 2022
- Access: [CodeReviewer](https://huggingface.co/microsoft/codereviewer)
- Paper: [Automating Code Review Activities by Large-Scale Pre-training](https://arxiv.org/abs/2203.09095)


## Relevant Surveys on LM4Code
- Large Language Models for Software Engineering: Survey and Open Problems, 2023, [paper](https://arxiv.org/pdf/2310.03533)
- Large Language Models for Software Engineering: A Systematic Literature Review, 2023, [paper](https://arxiv.org/abs/2308.10620)
- A Survey of Large Language Models for Code: Evolution, Benchmarking, and Future Trends, 2023, [paper](https://arxiv.org/pdf/2311.10372.pdf)
- Unifying the Perspectives of NLP and Software Engineering: A Survey on Language Models for Code, 2023, [paper](https://arxiv.org/abs/2311.07989)
- Software testing with large language model: Survey, landscape, and vision, 2023, [paper](https://arxiv.org/pdf/2307.07221)
- Pitfalls in Language Models for Code Intelligence: A Taxonomy and Survey, 2023, [paper](https://arxiv.org/pdf/2310.17903)
- Generative Artificial Intelligence for Software Engineering--A Research Agenda, 2023, [paper](https://arxiv.org/pdf/2310.18648)
-  A Survey on Large Language Model (LLM) Security and Privacy: The Good, the Bad, and the Ugly, 2023, [paper](https://arxiv.org/abs/2312.02003)
- Trustworthy and Synergistic Artificial Intelligence for Software Engineering: Vision and Roadmaps, 2023, [paper](https://arxiv.org/pdf/2309.04142)
- Large language models meet NL2Code: A survey, 2023, [paper](https://aclanthology.org/2023.acl-long.411.pdf)
- A Survey on Pretrained Language Models for Neural Code Intelligence, 2022, [paper](https://arxiv.org/abs/2212.10079)

## General Surveys on AI4SE
- A systematic literature review on the use of deep learning in software engineering research, TOSEM 2022, [paper](https://dl.acm.org/doi/pdf/10.1145/3485275)
- A survey on deep learning for software engineering, CSUR 2022, [paper](https://dl.acm.org/doi/abs/10.1145/3505243)
- Software engineering for AI-based systems: a survey, TOSEM 2021, [paper](https://dl.acm.org/doi/abs/10.1145/3487043)
- Machine/deep learning for software engineering: A systematic literature review, TSE 2022, [paper](https://ieeexplore.ieee.org/abstract/document/9772253/)
- Machine Learning Applied to Software Testing: A Systematic Mapping Study, 2019, [paper](https://ieeexplore.ieee.org/abstract/document/8638573/)
- A survey of machine learning for big code and naturalness, CSUR 2018, [paper](https://dl.acm.org/doi/abs/10.1145/3212695)

## General Surveys on LLM
- Large Language Models: A Comprehensive Survey of Applications, Challenges, Limitations, and Future Prospects, 2023, [paper](https://d197for5662m48.cloudfront.net/documents/publicationstatus/181139/preprint_pdf/edf41a1f2a93aadb235a3c3aff2dcf08.pdf)
- A survey of large language models, 2023, [paper](https://arxiv.org/pdf/2303.18223.pdf?fbclid=IwAR3GYBQ2P9Cww2HVM3oUbML9i5i3DMDBVv5_FvYWfEi-vdZqZoSM78jE2-s)
- A Survey on Evaluation of Large Language Models, 2023, [paper](https://arxiv.org/pdf/2307.03109.pdf)
- Recent advances in natural language processing via large pre-trained language models: A survey, CSUR 2023, [paper](https://arxiv.org/pdf/2111.01243)
- A Survey of GPT-3 Family Large Language Models Including ChatGPT and GPT-4, 2023, [paper](https://arxiv.org/pdf/2310.12321.pdf)
- Challenges and Applications of Large Language Models: A Survey, 2023, [paper](https://arxiv.org/pdf/2307.10169.pdf)
- Harnessing the power of llms in practice: A survey on chatgpt and beyond, 2023, [paper](https://arxiv.org/pdf/2304.13712.pdf)
- A Comprehensive Survey of AI-Generated Content (AIGC): A History of Generative AI from GAN to ChatGPT, 2023, [paper](https://arxiv.org/pdf/2303.04226.pdf)


## Repositories and Resources for LM4Code
- LLM4SE: Large Language Models for Software Engineering
    - [Repository](https://github.com/gai4se/LLM4SE)
    - This repository is associated with prominent software engineering conferences like ICSE, FSE, and ASE.
- Awesome-Code-LLM
    - [Repository](https://github.com/codefuse-ai/Awesome-Code-LLM)
    - This is the repo for one survey - a comprehensive review of LLM researches for code. Works in each category are ordered chronologically. A curated list of language modeling researches for code and related datasets.
- awesome-ai4code-papers
    - [Repository](https://github.com/bdqnghi/awesome-ai4code-papers)
    - A collection of recent papers, benchmarks and datasets of AI4Code domain.
- ml4code
    - [Repository](https://ml4code.github.io/)
    - Research on machine learning for source code.
- awesome-machine-learning-on-source-code
    - [Repository](https://github.com/src-d/awesome-machine-learning-on-source-code)
    - Cool links & research papers related to Machine Learning applied to source code (MLonCode)
- saltudelft/ml4se
    - [Repository](https://github.com/saltudelft/ml4se)
    - A curated list of papers, theses, datasets, and tools related to the application of Machine Learning for Software Engineering
- CUHK-ARISE/ml4code-dataset
    - [Repository](https://github.com/CUHK-ARISE/ml4code-dataset)
    - A collection of datasets for machine learning for big code



## Repositories and Resources for LLM
- Awesome-LLM4Tool: A Curated List of Resources for LLM Tools
    - [Repository](https://github.com/OpenGVLab/Awesome-LLM4Tool)
    - Offers a curated list of papers, repositories, tutorials, and resources related to large language models for tools.
- LLMsPracticalGuide: A Curated List of Practical Resources
    - [Repository](https://github.com/Mooler0410/LLMsPracticalGuide)
    - It includes an evolutionary tree of modern Large Language Models to trace the development over the years
- Hannibal046/Awesome-LLM
    - [Repository](https://github.com/Hannibal046/Awesome-LLM)
    - Awesome-LLM: a curated list of Large Language Model
- awesome-decentralized-llm
    - [Repository](https://github.com/imaurer/awesome-decentralized-llm)
    - Collection of LLM resources that can be used to build products you can "own" or to perform reproducible research.
- RUCAIBox/LLMSurvey
    - [Repository](https://github.com/RUCAIBox/LLMSurvey)
    - The official GitHub page for the survey paper "A Survey of Large Language Models".
- tensorchord/Awesome-LLMOps
    - [Repository](https://github.com/tensorchord/Awesome-LLMOps)
    - An awesome & curated list of best LLMOps tools for developers
- luban-agi/Awesome-Domain-LLM
    - [Repository](https://github.com/luban-agi/Awesome-Domain-LLM)
    - A curated list of domain-specific large language models in Chinese
- underlines/awesome-ml
    - [Repository](https://github.com/underlines/awesome-ml)
    - Curated list of useful LLM / Analytics / Datascience resources

# Benchmarks
## Bug Repair
### Defects4J
- Release year: 2014
- Paper: ["Defects4J: A Database of Existing Faults to Enable Controlled Testing Studies for Java Programs"](https://dl.acm.org/doi/10.1145/2610384.2628055)

### ManyBugs/IntroClass
- Release year: 2015
- Paper: ["The ManyBugs and IntroClass Benchmarks for Automated Repair of C Programs"](https://ieeexplore.ieee.org/document/7153570)

### BugAID
- Release year: 2016
- Paper: ["Discovering Bug Patterns in JavaScript"](https://dl.acm.org/doi/10.1145/2950290.2950308)

### CoCoNut
- Release year: 2020
- Paper: ["CoCoNuT: combining context-aware neural translation models using ensemble for program repair"](https://dl.acm.org/doi/10.1145/3395363.3397369)

### QuixBugs
- Release year: 2017
- Paper: ["QuixBugs: a multi-lingual program repair benchmark set based on the quixey challenge"](https://dl.acm.org/doi/10.1145/3135932.3135941)

### Bugs.jar
- Release year: 2018
- Paper: ["Bugs.jar: a large-scale, diverse dataset of real-world Java bugs"](https://dl.acm.org/doi/10.1145/3196398.3196473)

### BugsInPy
- Release year: 2020
- Paper: ["BugsInPy: A Database of Existing Bugs in Python Programs to Enable Controlled Testing and Debugging Studies"](https://dl.acm.org/doi/abs/10.1145/3368089.3417943)

### DeepFix
- Release year: 2017
- Paper: ["DeepFix: Fixing Common C Language Errors by Deep Learning"](https://ojs.aaai.org/index.php/AAAI/article/view/10742)


## Code Generation/Synthesis

### CONCODE
- Release year: 2018
- Paper: ["Mapping Language to Code in Programmatic Context"](https://arxiv.org/abs/1808.09588)

### HumanEval
- Release year: 2021
- Paper: ["Evaluating Large Language Models Trained on Code"](https://arxiv.org/abs/2107.03374) 

### MBPP/MathQA-Python
- Release year: 2021
- Paper: ["Program Synthesis with Large Language Models"](https://arxiv.org/abs/2108.07732) 

## Code Sumarization
### CODE-NN
- Release year: 2016
- Paper: ["Summarizing Source Code using a Neural Attention Model"](https://aclanthology.org/P16-1195/)

### TL-CodeSum
- Release year: 2018
- Paper: ["Summarizing Source Code with Transferred API Knowledge"](https://www.ijcai.org/proceedings/2018/314)

### CodeSearchNet
- Release year: 2019
- Paper: ["CodeSearchNet Challenge: Evaluating the State of Semantic Code Search"](https://arxiv.org/abs/1909.09436)

## Cites
If you find this repository useful, please cite our survey paper:
```
@article{she2023pitfalls,
  title={Pitfalls in Language Models for Code Intelligence: A Taxonomy and Survey},
  author={She, Xinyu and Liu, Yue and Zhao, Yanjie and He, Yiling and Li, Li and Tantithamthavorn, Chakkrit and Qin, Zhan and Wang, Haoyu},
  journal={arXiv preprint arXiv:2310.17903},
  year={2023}
}

@article{hou2023large,
  title={Large language models for software engineering: A systematic literature review},
  author={Hou, Xinyi and Zhao, Yanjie and Liu, Yue and Yang, Zhou and Wang, Kailong and Li, Li and Luo, Xiapu and Lo, David and Grundy, John and Wang, Haoyu},
  journal={arXiv preprint arXiv:2308.10620},
  year={2023}
}
```


