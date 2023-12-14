---
layout: default
title: XAI for LM4Code
nav_order: 5
---
# Explainable AI for LM4Code
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---


## Surveys for General XAI
- **Interpretable Machine Learning, 2020**, [paper](https://christophm.github.io/interpretable-ml-book/)
- **Explainable AI (XAI): Core ideas, techniques, and solutions**, CSUR 2023, [paper](https://orca.cardiff.ac.uk/id/eprint/152361/1/3561048.pdf)
- **Techniques for interpretable machine learning**, Communications of the ACM, 2019, [paper](https://dl.acm.org/doi/fullHtml/10.1145/3359786)
- **Post-hoc interpretability for neural nlp: A survey**, CSUR 2023, [paper](https://dl.acm.org/doi/pdf/10.1145/3546577)
- **Stop explaining black box machine learning models for high stakes decisions and use interpretable models instead, Nature Machine Intelligence**, 2019, [paper](https://www.nature.com/articles/s42256-019-0048-x)
- **Interpretable machine learning: definitions, methods, and applications**, 2019, [paper](https://arxiv.org/pdf/1901.04592.pdf?fbclid=IwAR2frcHrhLc4iaH5-TmKKq263NVvAKHtG4uQoiVNDeLAG3QFzdje-yzZjiQ)
- **Evaluating explanation methods for deep learning in security**, EuroS&P 2020, [paper](https://ieeexplore.ieee.org/abstract/document/9230374/)
- **A survey of methods for explaining black box models, ACM Computing Surveys**, 2020, [paper](https://dl.acm.org/doi/abs/10.1145/3236009)
- **On the explainability of natural language processing deep models**, CSUR, 2022, [paper](https://dl.acm.org/doi/abs/10.1145/3529755)
- **From Anecdotal Evidence to Quantitative Evaluation Methods: A Systematic Review on Evaluating Explainable AI**, CSUR, 2023, [paper](https://dl.acm.org/doi/10.1145/3583558), [repository](https://github.com/utwente-dmb/xai-papers)

## Surveys for XAI for LM4Code
- **A systematic literature review of explainable AI for software engineering**, 2023, [paper](https://arxiv.org/abs/2302.06065)
- **Explainable ai for se: Challenges and future directions**, 2023, [paper](https://ieeexplore.ieee.org/abstract/document/10109341/)

## Repositories for General XAI
- **Awesome-explainable-AI**
    - [Repository](https://github.com/wangyongjie-ntu/Awesome-explainable-AI)
    - A collection of research materials on explainable AI/ML
- **awesome-machine-learning-interpretability**
    - [Repository](https://github.com/jphall663/awesome-machine-learning-interpretability)
    - A maintained and curated list of practical and awesome responsible machine learning resources.
- **lopusz/awesome-interpretable-machine-learning**
    - [Repository](https://github.com/lopusz/awesome-interpretable-machine-learning)
    - Opinionated list of resources facilitating model interpretability (introspection, simplification, visualization, explanation).
- **Explainable Artificial Intelligence**
    - [Repository](https://interpretable-ml-class.github.io/)
    - A course on Explainable Artificial Intelligence (XAI) and Interpretable Machine Learning (IML) at Harvard University
- **utwente-dmb/xai-papers**
    - [Repository](https://github.com/utwente-dmb/xai-papers)
    - This is an exploration and visualization website for a categorization of explainable AI papers, hosted on Github pages. The initial set of XAI papers was collected and labeled by Nauta et al. (2023) as part of a large-scale literature review on the evaluation of Explainable AI, published in ACM Computing Surveys.
- **samzabdiel/XAI**
    - [Repository](https://github.com/samzabdiel/XAI)
    - Papers and code of Explainable AI esp. w.r.t. Image classification

## Tools for XAI
- **shap**
    - [Repository](https://github.com/shap/shap)
    - SHAP (SHapley Additive exPlanations) is a game theoretic approach to explain the output of any machine learning model. It connects optimal credit allocation with local explanations using the classic Shapley values from game theory and their related extensions.
    - Paper: [A Unified Approach to Interpreting Model Predictions](https://arxiv.org/abs/1705.07874)
- **marcotcr/lime**
    - [Repository](https://github.com/marcotcr/lime)
    - Lime is about explaining what machine learning classifiers (or models) are doing. At the moment, it supports explaining individual predictions for text classifiers or classifiers that act on tables (numpy arrays of numerical or categorical data) or images, with a package called lime (short for local interpretable model-agnostic explanations).
    - Paper: [“Why Should I Trust You?” Explaining the Predictions of Any Classifier](https://arxiv.org/abs/1602.04938)
- **marcotcr/anchor**
    - [Repository](https://github.com/marcotcr/anchor)
    - Code for "High-Precision Model-Agnostic Explanations" paper
    - Paper: [High-Precision Model-Agnostic Explanations](https://homes.cs.washington.edu/~marcotcr/aaai18.pdf)
- **Transformer-Explainability**
    - [Repository](https://github.com/hila-chefer/Transformer-Explainability)
    - Official PyTorch implementation for Transformer Interpretability Beyond Attention Visualization, a novel method to visualize classifications by Transformer-based networks.
- **Ecco**
    - [Repository](https://github.com/jalammar/ecco)
    - Explain, analyze, and visualize NLP language models. Ecco creates interactive visualizations directly in Jupyter notebooks explaining the behavior of Transformer-based language models (like GPT2, BERT, RoBERTA, T5, and T0).
- **Captum**
    - [Repository](https://github.com/pytorch/captum)
    - Captum is a model interpretability and understanding library for PyTorch. Captum means comprehension in Latin and contains general-purpose implementations of integrated gradients, saliency maps, smooth grad, vargrad, and others for PyTorch models. It has quick integration for models built with domain-specific libraries such as torchvision, torchtext, and others.
- **AIX360**
    - [Repository](https://github.com/Trusted-AI/AIX360)
    - The AI Explainability 360 toolkit is an open-source library that supports interpretability and explainability of datasets and machine learning models. The AI Explainability 360 Python package includes a comprehensive set of algorithms that cover different dimensions of explanations along with proxy explainability metrics. The AI Explainability 360 toolkit supports tabular, text, images, and time series data.



## Papers for XAI4SE


### 2019
- [From typestate verification to interpretable deep models (invited talk abstract)](https://doi.org/10.1145/3293882.3338992) ISSTA 2019

### 2020
- [Real-time incident prediction for online service systems](https://doi.org/10.1145/3368089.3409672) FSE 2020
- [AMS: generating AutoML search spaces from weak specifications](https://dl.acm.org/doi/pdf/10.1145/3368089.3409700) FSE 2020

### 2021
- [Thinking Like a Developer? Comparing the Attention of Humans with Neural Models of Code](https://doi.org/10.1109/ASE51524.2021.9678712) ASE 2021
- [Vulnerability detection with fine-grained interpretations](https://arxiv.org/pdf/2106.10478) FSE 2021
- [Explaining mispredictions of machine learning models using rule induction](https://doi.org/10.1145/3468264.3468614) FSE 2021
- [Generalizable and interpretable learning for configuration extrapolation](https://dl.acm.org/doi/pdf/10.1145/3468264.3468603) FSE 2021
- [XAI tools in the public sector: a case study on predicting combined sewer overflows](https://doi.org/10.1145/3468264.3468547) FSE 2021
- [White-Box Analysis over Machine Learning: Modeling Performance of Configurable Systems](http://arxiv.org/pdf/2101.05362) ICSE 2021
- [NeuronFair: Interpretable White-Box Fairness Testing through Biased Neuron Identification](https://doi.org/10.1145/3510003.3510123) ICSE 2021
- [𝜀-weakened robustness of deep neural networks](https://doi.org/10.1145/3533767.3534373) ISSTA 2021

### 2022
- [Reentrancy Vulnerability Detection and Localization: A Deep Learning Based Two-phase Approach](https://dl.acm.org/doi/pdf/10.1145/3551349.3560428) ASE 2022
- [ThirdEye: Attention Maps for Safe Autonomous Driving Systems](https://dl.acm.org/doi/pdf/10.1145/3551349.3556968) ASE 2022
- [Unveiling Hidden DNN Defects with Decision-Based Metamorphic Testing](https://dl.acm.org/doi/pdf/10.1145/3551349.3561157) ASE 2022
- [Automatic Generation of Visualizations for Machine Learning Pipelines](https://dl.acm.org/doi/pdf/10.1145/3551349.3559504) ASE 2022
- [A real-world case study for automated ticket team assignment using natural language processing and explainable models](https://dl.acm.org/doi/pdf/10.1145/3551349.3561164) ASE 2022
- [XSA: eXplainable Self-Adaptation](https://dl.acm.org/doi/pdf/10.1145/3551349.3559552) ASE 2022
- [TAPHSIR: towards AnaPHoric ambiguity detection and ReSolution in requirements](https://dl.acm.org/doi/pdf/10.1145/3540250.3558928) FSE 2022
- [Blackbox adversarial attacks and explanations for automatic speech recognition](https://doi.org/10.1145/3540250.3558906) FSE 2022
- [Fairness-aware Configuration of Machine Learning Libraries](https://arxiv.org/pdf/2202.06196) ICSE 2022
- [Generating and Visualizing Trace Link Explanations](https://dl.acm.org/doi/pdf/10.1145/3510003.3510129) ICSE 2022
- [What Do They Capture? - A Structural Analysis of Pre-Trained Language Models for Source Code](https://doi.org/10.1145/3510003.3510050) ICSE 2022
- [One step further: evaluating interpreters using metamorphic testing](https://doi.org/10.1145/3533767.3534225) ISSTA 2022

### 2023
- [Robin: A Novel Method to Produce Robust Interpreters for Deep Learning-Based Code Classifiers](https://arxiv.org/pdf/2309.10644) ASE 2023
- [SCPatcher: Mining Crowd Security Discussions to Enrich Secure Coding Practices](https://doi.org/10.1109/ASE56229.2023.00040) ASE 2023
- [Generative Type Inference for Python](https://arxiv.org/pdf/2307.09163) ASE 2023
- [Better Patching Using LLM Prompting, via Self-Consistency](https://arxiv.org/pdf/2306.00108) ASE 2023
- [Scalable Industrial Control System Analysis via XAI-Based Gray-Box Fuzzing](https://doi.org/10.1109/ASE56229.2023.00161) ASE 2023
- [How Early Participation Determines Long-Term Sustained Activity in GitHub Projects?](https://dl.acm.org/doi/pdf/10.1145/3611643.3616349) FSE 2023
- [Distinguishing Look-Alike Innocent and Vulnerable Code by Subtle Semantic Representation Learning and Explanation](https://dl.acm.org/doi/pdf/10.1145/3611643.3616358) FSE 2023
- [Leveraging Feature Bias for Scalable Misprediction Explanation of Machine Learning Models](https://doi.org/10.1109/ICSE48619.2023.00135) ICSE 2023
- [Interpreters for GNN-Based Vulnerability Detection: Are We There Yet?](https://doi.org/10.1145/3597926.3598145) ISSTA 2023