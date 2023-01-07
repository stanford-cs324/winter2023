---
layout: default
title: Topics / Syllabus
nav_order: 3
has_children: false
---

# Class Topics (Winter 2023)

As a reading resource, please find a list of class topics and relevant materials below. Under each topic, we include a list of related readings, including lecture notes, blog posts, papers, and other resources.

We broadly organize class topics under three areas: **(1)** [Fundamentals](#fundamentals), **(2)** [Survey of Existing FMs and their Applications](#survey-of-existing-fms-and-their-applications), and **(3)** [Societal Considerations & Impact](#societal-considerations--impact). The list below of relevant readings and materials is not exhaustive; we'll be updating this page as we go through the quarter, and encourage you to dig deeper into the topics that interest you. These topics are also *not in order* of when they'll be covered in class. 

Special thanks to the original content creators, including course notes from a [past version of CS 324](https://stanford-cs324.github.io/winter2022/lectures/).

---

### Table of Contents  
- [**Fundamentals**](#fundamentals)  
  - [What are foundation models (FMs) and why are they interesting?](#what-are-foundation-models-fms-and-why-are-they-interesting)  
  - [How does *data* impact FMs and what are the downstream effects?](#how-does-data-impact-fms-and-what-are-the-downstream-effects)  
  - [How do we *train* FMs and what are the downstream effects?](#how-do-we-train-fms-and-what-are-the-downstream-effects)  
  - [Model Architectures and Training Objectives for FMs](#model-architectures-and-training-objectives-for-fms)  
  - [Emergent Behaviors and Capabilities](#emergent-behaviors-and-capabilities)  
  - [Adapting FMs to New Tasks and Data Domains](#adapting-fms-to-new-tasks-and-data-domains)  
  - [Training Methods and Infrastucture](#training-methods-and-infrastucture)

- [**Survey of Existing FMs and their Applications**](#survey-of-existing-fms-and-their-applications)  
  - [Text and (Masked) Language Modeling FMs](#text-and-masked-language-modeling-fms)   
  - [Image-Text and Multimodal FMs](#image-text-and-multimodal-fms)    

- [**Societal Considerations & Impact**](#societal-considerations--impact)  
  - [Security and Privacy](#security-and-privacy)
  - [Environmental Impact](#environmental-impact)  
  - [Legal Considerations](#legal-considerations)

---

## Fundamentals 

### What are foundation models (FMs) and why are they interesting?   
* *Background on Neural Networks (course series from Andrej Karpathy)*:
  - [Neural Networks: Zero to Hero](https://github.com/karpathy/nn-zero-to-hero)

* *Course Notes*:  
  - [Large Language Model (LLM) Capabilities](https://stanford-cs324.github.io/winter2022/lectures/capabilities/)  

* *Blog Posts*:
  - [How Foundation Models Changed Our Work](https://hazyresearch.stanford.edu/blog/2022-11-16-whatsup)

* *Papers*:  
  - [Language Models are Few Shot Learners](https://arxiv.org/abs/2005.14165)  
  - [On the Opportunities and Risks of Foundation Models](https://arxiv.org/abs/2108.07258)  

### How does *data* impact FMs and what are the downstream effects?
* *Course Notes*:  
  - [Data for Training FMs](https://stanford-cs324.github.io/winter2022/lectures/data/)
  - [Harms From Data (Part 1)](https://stanford-cs324.github.io/winter2022/lectures/harms-1/)
  - [Harms From Data (Part 2)](https://stanford-cs324.github.io/winter2022/lectures/harms-2/)

* *Blog Posts*:
  - [Foundation Models are Entering their Data-Centric Era](https://hazyresearch.stanford.edu/blog/2022-10-11-datacentric-fms)

* *Papers*:  
  - [The Pile: An 800GB Dataset of Diverse Text for Language Modeling](https://arxiv.org/abs/2101.00027)
  - [Deduplicating Training Data Makes Language Models Better](https://arxiv.org/abs/2107.06499)
  - [Scaling Laws and Interpretability of Learning from Repeated Data](https://arxiv.org/abs/2205.10487)
  - [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜](https://dl-acm-org.stanford.idm.oclc.org/doi/abs/10.1145/3442188.3445922)

### Model Architectures and Training Objectives for FMs  

* *Course Notes*:
  - [LLM Architectures](https://stanford-cs324.github.io/winter2022/lectures/modeling/)  
  - [LLM Training Objectives](https://stanford-cs324.github.io/winter2022/lectures/training/)

* *Blog Posts*:

* *Papers*: 
  - [Attention Is All You Need](https://arxiv.org/abs/1706.03762)  
  - [ELECTRA: Pre-training Text Encoders as Discriminators Rather Than Generators](https://arxiv.org/abs/2003.10555)  
  - [Unifying Language Learning Paradigms](https://arxiv.org/abs/2205.05131)  
  - [Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/abs/1910.10683)  


### Emergent Behaviors and Capabilities  

* *Course Notes*:  
  - [Scaling Laws](https://stanford-cs324.github.io/winter2022/assets/pdfs/Scaling%20laws%20pdf.pdf)  

* *Blog Posts*:  
  - [How Does In-context Learning Work?](https://ai.stanford.edu/blog/understanding-incontext/)

* *Papers*: 
  - [Scaling Laws for Neural Language Models](https://arxiv.org/abs/2001.08361)  
  - [Show Your Work: Scratchpads for Intermediate Computation with Language Models](https://arxiv.org/abs/2112.00114)    
  - [Chain of Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)  
  - [Ask Me Anything: A simple strategy for prompting language models](https://arxiv.org/abs/2210.02441)  
  - [Emergent Abilities of Large Language Models](https://arxiv.org/abs/2206.07682)  
  - [Data Distributional Properties Drive Emergent Few-Shot Learning in Transformers](https://arxiv.org/abs/2205.05055)    
  - [An Explanation of In-Context Learning as Implicit Bayesian Inference](https://arxiv.org/abs/2111.02080)  
  - [Rethinking the Role of Demonstrations: What Makes In-Context Learning Work?](https://arxiv.org/abs/2202.12837)


### Adapting FMs to New Tasks and Data Domains    

* *Course Notes*:
  - [Adapting Large Language Models](https://stanford-cs324.github.io/winter2022/lectures/adaptation/)  

* *Blog Posts*:  

* *Papers*:
  - [Multitask Prompted Training Enables Zero-Shot Task Generalization](https://arxiv.org/abs/2110.08207)    
  - [Finetuned Language Models Are Zero-Shot Learners](https://arxiv.org/abs/2109.01652)    
  - [Prefix-Tuning: Optimizing Continuous Prompts for Generation](https://arxiv.org/abs/2101.00190)    
  - [Training Language Models to Follow Instructions with Human Feedback](https://arxiv.org/abs/2203.02155)  
  - [The Power of Scale for Parameter-Efficient Prompt Tuning](https://arxiv.org/abs/2104.08691)  
  - [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)  
  - [Fast Model Editing at Scale](https://arxiv.org/abs/2110.11309)  


### Training Methods and Infrastructure  

* *Course Notes*:  

* *Blog Posts*:  
  - [The Technology Behind BLOOM Training](https://huggingface.co/blog/bloom-megatron-deepspeed)  

* *Papers*:  
  - [Decentralized Training of Foundation Models in Heterogeneous Environments](https://arxiv.org/abs/2206.01288)   
  - [Megatron-LM: Training Multi-Billion Parameter Language Models Using
Model Parallelism](https://arxiv.org/abs/1909.08053)  
  - [FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness](https://arxiv.org/abs/2205.14135)  
  - [Training Processes (Section 2.5), OPT: Open Pre-trained Transformer Language Models](https://arxiv.org/abs/2205.01068) (Also see [full logbook of training](https://github.com/facebookresearch/metaseq/blob/main/projects/OPT/chronicles/README.md))  




---

## Survey of Existing FMs and their Applications

### Text and (Masked) Language Modeling FMs  

* *Course Notes*:  

* *Blog Posts*:  
  - [Aligning Language Models
  to Follow Instructions](https://openai.com/blog/instruction-following/)  
  - [PubMedGPT](https://crfm.stanford.edu/2022/12/15/pubmedgpt.html)  

* *Papers*:  
  - [Language Models are Unsupervised Multitask Learners](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)
  - [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)  
  - [Training Language Models to Follow Instructions with Human Feedback](https://arxiv.org/abs/2203.02155)
  - [CodeGen: An Open Large Language Model for Code with Multi-Turn Program Synthesis](https://ui.adsabs.harvard.edu/abs/2022arXiv220313474N/abstract)
  - [Highly Accurate Protein Structure Prediction with AlphaFold](https://pubmed.ncbi.nlm.nih.gov/34265844/)
  - [Language Models of Protein Sequences at the Scale of Evolution Enable Accurate Structure Prediction](https://www.biorxiv.org/content/10.1101/2022.07.20.500902v1)
  - [GatorTron: A Large Language Model for Clinical Natural Language Processing](https://www.medrxiv.org/content/10.1101/2022.02.27.22271257v2.full) 
  - [Pile of Law: Learning Responsible Data Filtering from the Law and a 256GB Open-Source Legal Dataset](https://arxiv.org/abs/2207.00220)  
  - [LegalBench: Prototyping a Collaborative Benchmark for Legal Reasoning
](https://arxiv.org/abs/2209.06120)  


### Image-Text and Multimodal FMs  

* *Course Notes*:  

* *Blog Posts*:  

* *Papers*: 
  - [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020)  
  - [Zero-Shot Text-to-Image Generation](https://arxiv.org/abs/2102.12092)  
  - [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239)  
  - [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752)  
  - [Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding](https://arxiv.org/abs/2205.11487)  
  - [Imagen Video: High Definition Video Generation with Diffusion Models](https://arxiv.org/abs/2210.02303)  
  - [Make-A-Video: Text-to-Video Generation without Text-Video Data](https://arxiv.org/abs/2209.14792)  
  - [DreamFusion: Text-to-3D using 2D Diffusion](https://arxiv.org/abs/2209.14988)  
  - [Point-E: A System for Generating 3D Point Clouds from Complex Prompts](https://arxiv.org/abs/2212.08751)  
  - [Flamingo: a Visual Language Model for Few-Shot Learning](https://arxiv.org/abs/2204.14198)  
  - [CM3: A Causal Masked Multimodal Model of the Internet](https://arxiv.org/abs/2201.07520)  
  - [A Generalist Agent](https://arxiv.org/abs/2205.06175)
  - [Video PreTraining (VPT): Learning to Act by Watching Unlabeled Online Videos](https://arxiv.org/abs/2206.11795)  
  - [MineDojo: Building Open-Ended Embodied Agents with Internet-Scale Knowledge](https://arxiv.org/abs/2206.08853)  

---

## Societal Considerations & Impact

### Security and Privacy  

* *Course Notes*:  
  - [Security and Privacy](https://stanford-cs324.github.io/winter2022/assets/pdfs/Privacy%20pdf.pdf)  

* *Blog Posts*:  

* *Papers*:  
  - [Extracting Training Data from Large Language Models](https://arxiv.org/abs/2012.07805)   
  - [Fair Learning](https://texaslawreview.org/fair-learning/)  
  - [Large Language Models Can Be Strong Differentially Private Learners
](https://arxiv.org/abs/2110.05679)  
  - [Can Foundation Models Help Us Achieve Perfect Secrecy?](https://arxiv.org/abs/2205.13722)

### Environmental Impact 
* *Course Notes*:  
  - [Environmental Impact](https://stanford-cs324.github.io/winter2022/lectures/environment/)  

* *Blog Posts*:  

* *Papers*:  
  - [Energy and Policy Considerations for Deep Learning in NLP](https://arxiv.org/abs/1906.02243)  
  - [Carbon Emissions and Large Neural Network Training](https://arxiv.org/abs/2104.10350)  
  - [Unraveling the Hidden Environmental Impacts of AI Solutions for Environment](https://arxiv.org/abs/2110.11822)  
  - [Environment Section, On the Opportunities and Risks of Foundation Models](https://crfm.stanford.edu/assets/report.pdf#environment)  

### Legal Considerations 

* *Course Notes*:  
  - [Legality](https://stanford-cs324.github.io/winter2022/lectures/legality/)  

* *Blog Posts*:  
  - [From Discrimination in Machine Learning to Discrimination in Law, Part 1: Disparate Treatment](https://ai.stanford.edu/blog/discrimination_in_ML_and_law/)  
  - [From Discrimination in Machine Learning to Discrimination in Law, Part 2: Disparate Impact](https://ai.stanford.edu/blog/discrimination_in_ML_and_law_p2/)  

* *Papers / Articles*:  
  - [Internet Law](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3191751)  
  - [AI Regulation Is Coming](https://hbr.org/2021/09/ai-regulation-is-coming)  
  - [Legality Section, On the Opportunities and Risks of Foundation Models](https://crfm.stanford.edu/assets/report.pdf#legality)  
