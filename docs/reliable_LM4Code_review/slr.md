---
layout: default
title: SLR
parent: Pitalls_Survey
---

# Systematic Literature Survey Process (SLR)
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---


## Process

To conduct a systematic review, we need to follow complete steps to collect, analyze and review the relevant literature works.

![Study_identification_and_selection_process](https://github.com/yueyueL/ReliableLM4Code/assets/60457190/5598c243-88ad-422a-9a49-08e72d064079)


Please feel free to send a pull request to add papers and relevant content that are not listed here.  We uploaded our completed paper lists to Google Drive with detailed reviewed information. 

([Rewiew paper lists](https://docs.google.com/spreadsheets/d/1DtE7WxjmHkDi9-jPV3H3D68klXeiKLr4prQRVbL3Qgg/edit?usp=sharing))



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
- [elsapy](https://github.com/ElsevierDev/elsapy): A Python module for use with api.elsevier.com.
- [dblp-python](https://github.com/ElsevierDev/elsapy): A simple Python wrapper around the DBLP API, currently supporting author search and author and publication lookup.

**SnowBalling:**
- [Litmap](https://app.litmaps.com/): Litmaps are visual citation maps that help you understand how your research connects. (*Both DOI list and Title list are ok for search !!!*)
- [SnowGlobe](https://snowglobe.soc.northwestern.edu/): SnowGlobe is a program that assists with literature searching, using a technique called snowballing. (*Articles written after 2021 will not be able to be searched or found !!!*)
- [CitationGecko](https://www.citationgecko.com/): This is a tool that uses the citation relations between scientific papers to help researchers find interesting and relevant paper.



