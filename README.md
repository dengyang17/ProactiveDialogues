# ProactiveDialogues
Proactive Dialogue Systems - Paper Reading List

Outline
- [Survey](#Survey)
- [Tutorial](#Tutorial)
- [Proactive Open-domain Dialogues](#Proactive-Open-domain-Dialogue-Systems)
  - [Target-guided Open-domain Dialogues](#Target-guided-Open-domain-Dialogues)
  - [Emotional Support Dialogues](#Emotional-Support-Dialogues)
  - [Prosocial Dialogues](#Prosocial-Dialogues)
- [Proactive Task-oriented Dialogue Systems](#Proactive-Task-oriented-Dialogue-Systems)
  - [Enriched Task-oriented Dialogues](#Enriched-Task-oriented-Dialogues)
  - [System-initiated Sub-dialogues](#System-initiated-Sub-dialogues)
  - [Non-collaborative Dialogues](#Non-collaborative-Dialogues)
- [Proactive Conversational Information-Seeking Systems](#Proactive-Conversational-Information-Seeking-Systems)
  - [Asking Clarification Questions](#Asking-Clarification-Questions)
  - [User Preference Elicitation](#User-Preference-Elicitation)
  - [Over-specified Query Management](#Over-specified-Query-Management)
- [Proactive Hybrid Dialogues](#Proactive-Hybrid-Dialogue-Systems)
- [Proactivity in LLM-based Dialogue Systems](#Proactivity-in-LLM-based-Dialogue-Systems)
  - [In-context Learning / Prompt-based Methods](#In-context-Learning-/-Prompt-based-Methods)
  - [Supervised Fine-tuning](#Supervised-Fine-tuning)
  - [Reinforcement Learning](#Reinforcement-learning)


## Survey
- [A Survey on Proactive Dialogue Systems: Problems, Methods, and Prospects](https://doi.org/10.48550/arXiv.2305.02750) (IJCAI 2023 Survey Track)
- [How to Approach Ambiguous Queries in Conversational Search: A Survey of Techniques, Approaches, Tools, and Challenges](https://doi.org/10.1145/3534965) (ACM Computing Surveys, 2022)
- [Let's Negotiate! A Survey of Negotiation Dialogue Systems](https://doi.org/10.48550/arXiv.2212.09072)
- [A Survey on Asking Clarification Questions Datasets in Conversational Systems](https://aclanthology.org/2023.acl-long.152/) (ACL 2023)

## Tutorial
- [Goal Awareness for Conversational AI: Proactivity, Non-collaborativity, and Beyond](https://aclanthology.org/2023.acl-tutorials.1/) (ACL 2023)
- [Proactive Conversational Agents](https://dl.acm.org/doi/10.1145/3539597.3572724) (WSDM 2023)
- [Proactive Conversational Agents in the Post-ChatGPT World](https://dl.acm.org/doi/abs/10.1145/3539618.3594250) (SIGIR 2023)

## Proactive Open-domain Dialogue Systems
### Target-guided Open-domain Dialogues
- [Target-Guided Open-Domain Conversation](https://doi.org/10.18653/v1/p19-1565) (ACL 2019) [[repo](https://github.com/squareRoot3/Target-Guided-Conversation)]
- [Proactive Human-Machine Conversation with Explicit Conversation Goal](https://doi.org/10.18653/v1/p19-1369) (ACL 2019) [[repo](https://ai.baidu.com/broad/introduction?dataset=duconv)]
- [Keyword-Guided Neural Conversational Model](https://arxiv.org/abs/2012.08383) (AAAI 2021) [[repo](https://github.com/zhongpeixiang/CKC)]
- [TopKG: Target-oriented Dialog via Global Planning on Knowledge Graph](https://aclanthology.org/2022.coling-1.62) (COLING 2022) [[repo](https://github.com/yyyyyyzt/topkgchat)]
- [Interacting with Non-Cooperative User: A New Paradigm for Proactive Dialogue Policy](https://doi.org/10.48550/arXiv.2204.07433) (SIGIR 2022)
- [Dialogue Planning via Brownian Bridge Stochastic Process for Goal-directed Proactive Dialogue](https://aclanthology.org/2023.findings-acl.25/) (ACL 2023 Findings) [[repo](https://github.com/iwangjian/Color4Dial)]
- [Target-oriented Proactive Dialogue Systems with Personalization: Problem Formulation and Dataset Curation](https://aclanthology.org/2023.emnlp-main.72/) (EMNLP 2023) [[repo](https://github.com/iwangjian/TopDial)]
- [Reinforced Target-driven Conversational Promotion](https://aclanthology.org/2023.emnlp-main.775/) (EMNLP 2023) [[repo](https://github.com/huyquangdao/RTCP)]

### Emotional Support Dialogues
- [Towards Emotional Support Dialog Systems](https://doi.org/10.18653/v1/2021.acl-long.269) (ACL 2021) [[repo](https://github.com/thu-coai/Emotional-Support-Conversation)]
- [MISC: A Mixed Strategy-Aware Model integrating COMET for Emotional Support Conversation](https://doi.org/10.18653/v1/2022.acl-long.25) (ACL 2022) [[repo](https://github.com/morecry/MISC)]
- [Improving Multi-turn Emotional Support Dialogue Generation with Lookahead Strategy Planning](https://arxiv.org/abs/2210.04242) (EMNLP 2022) [[repo](https://github.com/lwgkzl/MultiESC)]
- [Knowledge-enhanced Mixed-initiative Dialogue System for Emotional Support Conversations](https://doi.org/10.48550/arXiv.2305.10172) (ACL 2023) [[repo](https://github.com/dengyang17/KEMI)]

### Prosocial Dialogues
- [ProsocialDialog: A Prosocial Backbone for Conversational Agents](https://arxiv.org/abs/2205.12688) (EMNLP 2022) [[repo](https://github.com/skywalker023/prosocial-dialog)]
- [Just Say No: Analyzing the Stance of Neural Dialogue Generation in Offensive Contexts](https://arxiv.org/abs/2108.11830) (EMNLP 2021) [[repo](https://github.com/abaheti95/ToxiChat)]
- [The MORAL INTEGRITY CORPUS: A Benchmark for Ethical Dialogue Systems](https://arxiv.org/abs/2204.03021) (ACL 2022) [[repo](https://github.com/SALT-NLP/mic)]

## Proactive Task-oriented Dialogue Systems
### Enriched Task-oriented Dialogues
- [Adding Chit-chat to Enhance Task-oriented Dialogues](https://arxiv.org/abs/2010.12757) (NAACL 2021) [[repo](https://github.com/facebookresearch/accentor)]
- [KETOD: Knowledge-enriched Task-oriented Dialogue](https://arxiv.org/abs/2205.05589) (NAACL 2022 Findings) [[repo](https://github.com/facebookresearch/ketod)]
- ["What do others think?": Task-Oriented Conversational Modeling with Subjective Knowledge](https://arxiv.org/abs/2305.12091)

### System-initiated Sub-dialogues
- [Database Search Results Disambiguation for Task-oriented Dialog Systems](https://arxiv.org/abs/2112.08351) (NAACL 2022)
- [TITAN : Task-oriented Dialogues with Mixed-Initiative Interactions]() (IJCAI 2023)
- [Towards Asking Clarification Questions for Information Seeking on Task-Oriented Dialogues.](https://arxiv.org/abs/2305.13690) [[repo](https://github.com/alexa/dstc11-track5)]

### Non-collaborative Dialogues
- [Deal or No Deal? End-to-End Learning for Negotiation Dialogues](https://aclanthology.org/D17-1259/) (EMNLP 2017) [[repo](https://github.com/facebookresearch/end-to-end-negotiator)]
- [Decoupling Strategy and Generation in Negotiation Dialogues](https://aclanthology.org/D18-1256/) (EMNLP 2018) [[repo](https://stanfordnlp.github.io/cocoa/)]
- [Persuasion for Good: Towards a Personalized Persuasive Dialogue System for Social Good](https://aclanthology.org/P19-1566/) (ACL 2019) [[repo](https://gitlab.com/ucdavisnlp/persuasionforgood)]
- [End-to-End Trainable Non-Collaborative Dialog System](https://arxiv.org/abs/1911.10742) (AAAI 2020) [[repo](https://gitlab.com/ucdavisnlp/antiscam)]
- [DialoGraph: Incorporating Interpretable Strategy-Graph Networks into Negotiation Dialogues](https://arxiv.org/abs/2106.00920) (ICLR 2021) [[repo](https://github.com/rishabhjoshi/DialoGraph_ICLR21)]
- [Improving Dialog Systems for Negotiation with Personality Modeling](https://github.com/princeton-nlp/NegotiationToM) (ACL 2021) [[repo](https://arxiv.org/abs/2010.09954)]
- [PEPDS: A Polite and Empathetic Persuasive Dialogue System for Charity Donation](https://aclanthology.org/2022.coling-1.34/) (COLING 2022) [[repo](https://github.com/Mishrakshitij/PEPDS)]


## Proactive Conversational Information-Seeking Systems
### Asking Clarification Questions
- [Asking Clarifying Questions in Open-Domain Information-Seeking Conversations](https://arxiv.org/abs/1907.06554) (SIGIR 2019) [[repo](https://github.com/aliannejadi/qulac)]
- [Building and Evaluating Open-Domain Dialogue Corpora with Clarifying Questions](https://aclanthology.org/2021.emnlp-main.367/) (EMNLP 2021) [[repo](https://github.com/aliannejadi/ClariQ)]
- [Generating Clarifying Questions for Information Retrieval](https://www.microsoft.com/en-us/research/uploads/prod/2020/01/webconf-2020-camera-zamani-et-al.pdf) (WWW 2020)
- [Abg-CoQA: Clarifying Ambiguity in Conversational Question Answering](https://openreview.net/pdf?id=SlDZ1o8FsJU) (AKBC 2021) [[repo](https://github.com/MeiqiGuo/AKBC2021-Abg-CoQA)]
- [PACIFIC: Towards Proactive Conversational Question Answering over Tabular and Textual Data in Finance](https://aclanthology.org/2022.emnlp-main.469/) (EMNLP 2022) [[repo](https://github.com/dengyang17/PACIFIC/)]

### User Preference Elicitation
- [Towards Conversational Search and Recommendation: System Ask, User Respond](https://dl.acm.org/doi/10.1145/3269206.3271776) (CIKM 2018) [[repo](https://github.com/evison/Conversational)]
- [Estimation-Action-Reflection: Towards Deep Interaction Between Conversational and Recommender Systems](https://dl.acm.org/doi/abs/10.1145/3336191.3371769) (WSDM 2020) [[repo](https://ear-conv-rec.github.io/)]
- [Unified Conversational Recommendation Policy Learning via Graph-based Reinforcement Learning](https://arxiv.org/abs/2105.09710) (SIGIR 2021) [[repo](https://github.com/dengyang17/unicorn)]
- [Comparison-based Conversational Recommender System with Relative Bandit Feedback](https://arxiv.org/abs/2208.09837) (SIGIR 2021) [[repo](https://github.com/fffffarmer/RelativeConUCB)]
- [Multiple Choice Questions based Multi-Interest Policy Learning for Conversational Recommendation](https://arxiv.org/abs/2112.11775) (WWW 2022) 

### Over-specified Query Management
- [INSCIT: information-seeking conversations with mixed-initiative interactions](https://arxiv.org/abs/2207.00746) (TACL 2023) [[repo](https://github.com/ellenmellon/INSCIT)]


## Proactive Hybrid Dialogue Systems
- [Towards Conversational Recommendation over Multi-Type Dialogs](https://aclanthology.org/2020.acl-main.98/) (ACL 2020) [[repo](https://github.com/liuzeming01/durecdial)]
- [Where to Go for the Holidays: Towards Mixed-Type Dialogs for Clarification of User Goals](https://aclanthology.org/2022.acl-long.73/) (ACL 2022)
- [Fusing Task-oriented and Open-domain Dialogues in Conversational Agents](https://arxiv.org/abs/2109.04137) (AAAI 2022) [[repo](https://github.com/tomyoung903/FusedChat)]
- [SalesBot: Transitioning from Chit-Chat to Task-Oriented Dialogues](https://aclanthology.org/2022.acl-long.425/) (ACL 2022) [[repo](https://github.com/miulab/salesbot)]
- [A Unified Multi-task Learning Framework for Multi-goal Conversational Recommender Systems](https://dl.acm.org/doi/10.1145/3570640) (TOIS 2023) [[repo](https://github.com/dengyang17/UniMIND)]
- [MidMed: Towards Mixed-Type Dialogues for Medical Consultation](https://aclanthology.org/2023.acl-long.453/) (ACL 2023) [[repo](https://github.com/xmshi-trio/MidMed)]
- [NewsDialogues: Towards Proactive News Grounded Conversation](https://aclanthology.org/2023.findings-acl.224/) (ACL 2023 Findings) [[repo](https://github.com/SihengLi99/NewsDialogues)]
- [OPERA: Harmonizing Task-Oriented Dialogs and Information Seeking Experience](https://arxiv.org/abs/2206.12449) (TWEB 2023)
- [COOPER: Coordinating Specialized Agents towards a Complex Dialogue Goal](https://arxiv.org/abs/2312.11792) (AAAI 2024) [[repo](https://github.com/YiCheng98/Cooper)]


## Proactivity in LLM-based Dialogue Systems
### In-context Learning / Prompt-based Methods
- [Controllable Mixed-Initiative Dialogue Generation through Prompting](https://aclanthology.org/2023.acl-short.82/) (ACL 2023) [[repo](https://github.com/maxlchen/Controllable-Mixed-Initiative-Dialogue-Generation)]
- [Ask an Expert: Leveraging Language Models to Improve Strategic Reasoning in Goal-Oriented Dialogue Models](https://aclanthology.org/2023.findings-acl.417/) (ACL 2023 Findings)
- [Improving Language Model Negotiation with Self-Play and In-Context Learning from AI Feedback](https://arxiv.org/abs/2305.10142) [[repo](https://github.com/FranxYao/GPT-Bargaining)]
- [Prompting and Evaluating Large Language Models for Proactive Dialogues: Clarification, Target-guided, and Non-collaboration](https://arxiv.org/abs/2305.13626) (EMNLP 2023 Findings) [[repo](https://github.com/dengyang17/LLM-Proactive)]

### Supervised Fine-tuning
- [Building Emotional Support Chatbots in the Era of LLMs](https://arxiv.org/abs/2308.11584) [[repo](https://anonymous.4open.science/r/ExtESC-2761/README.md)]

### Reinforcement Learning
- [Prompt-Based Monte-Carlo Tree Search for Goal-oriented Dialogue Policy Planning](https://aclanthology.org/2023.emnlp-main.439/) (EMNLP 2023) [[repo](https://github.com/jasonyux/GDPZero)]
- [Plug-and-Play Policy Planner for Large Language Model Powered Dialogue Agents](https://arxiv.org/abs/2311.00262) (ICLR 2024) [[repo](https://github.com/dengyang17/PPDPP)]
