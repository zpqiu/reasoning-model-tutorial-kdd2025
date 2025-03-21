Welcome to our KDD’25 Tutorial, “Practical Guidance and Tutorial on Incentivizing Reasoning in LLMs using Distillation and Reinforcement Learning”.

Website: [Reasoning Model Tutorial](https://zpqiu.github.io/reasoning-model-tutorial-kdd2025/)


<!-- ##  Tutorial Date, Time, Location
TBD -->


## Tutorial Abstract

With reasoning models like DeepSeek-R1 and OpenAI’s o1 demonstrating breakthrough capabilities in complex problem-solving, there’s growing interest in the AI community about how to unlock similar capabilities in other large language models (LLMs). This hands-on tutorial dives into practical methods for building reasoning capabilities in LLMs through two primary approaches: knowledge distillation from advanced reasoning models and post-training with reinforcement learning techniques. Participants will learn how to transfer reasoning capabilities from cutting-edge models like DeepSeek-R1 into smaller LLMs such as Qwen and Llama, and then explore how reinforcement learning can take these capabilities even further. Through interactive Jupyter notebook, the participants will exercise through the entire process. By the end of this session, participants will be equipped with practical knowledge in how to incentivize reasoning capabilities into LLMs, understand how to use various frameworks for this task, and leave with hands-on experience that can be applied to their own projects.

## Target Audience and Prerequisites

**Target audience**: Data scientists and engineers who are interested in enhancing reasoning capabilities in LLMs for downstream tasks. The tutorial will be designed to accommodate participants with varying levels of expertise, from beginners to moderately skilled users, with the pace set to ensure beginners can follow comfortably.

**Prerequisites**: Basic knowledge of deep learning and LLM concepts, familiarity with Python programming. 


## Tutorial Outline

**1. Introduction and Lab Overview (20 Minutes)**

This part covers the core methodologies that can be leveraged to incentivize reasoning capabilities into large language models (LLMs) [1, 2, 4, 7, 10, 12]. First, we will explain how knowledge distillation [5, 11] works for transferring reasoning abilities from large models to smaller ones, covering concepts like long Chain-of-Thought data and teacher-student frameworks. Then, we will introduce how reinforcement learning (RL) can be applied to post-train LLMs for enhanced reasoning, including reward design and various RL algorithms [3, 8, 9, 13]. Moreover, to better evaluate the trained models, we will introduce the evaluation metrics specific to reasoning capabilities, such as chain-of-thought accuracy, thought length, and self-reflection behavior. Participants will leave this section with the theoretical knowledge needed to understand and implement the hands-on labs that follow.
   
**2. Hands-on: Setting Up the Environment for the Lab (10 Minutes)**

In this part we will introduce the lab environment, the libraries, frameworks, and datasets used in the exercise. We’ll guide the participants to conduct a quick verification process to ensure everyone’s environment is correctly configured.
   
**3. Hands-on: Extracting Reasoning Data (30 Minutes)**

In this lab, participants will learn how to automatically generate long Chain-of-Thought data that encapsulates reasoning processes from advanced reasoning models, such as DeepSeek-R1. We’ll demonstrate how to filter low-quality data and prepare it for distillation into smaller models using NeMo’s data processing tools [6]. Participants will work with Jupyter notebooks1 to practice these techniques and will take away a clear understanding of how to collect high-quality reasoning data from advanced models.

**4. Hands-on: Distilling Reasoning Capability into Smaller Models (60 Minutes)**

This lab will walk participants through implementing knowledge distillation in open-source models like Qwen and Llama using NVIDIA’s NeMo framework. We’ll cover the technical details of setting up distillation training experiment in NeMo, monitoring training progress effectively, and evaluating the results. Participants will take away practical experience in transferring reasoning abilities from large to smaller models while understanding how to optimize the process using NeMo’s scalable architecture.

**5. Hands-on: Post-training using Reinforcement Learning (60 minutes)**

This lab will teach participants how to set up a reinforcement learning environment for post-training LLMs to further enhance reasoning capabilities. We’ll cover topics including how to use the RL frameworks, how to design reward functions, and guide participants through the whole fine-tuning process using RL. This part will conclude with a comparison of RL results against the distillation approach, helping participants understand the strengths and weaknesses of each method. Participants will gain practical experience in applying RL to LLMs and will be able to implement these techniques in their own projects.

**6. Conclusion and Resources**

In conclusion, this tutorial will revisit the two post-training approaches discussed earlier, summarizing their suitable applications, limitations, and unresolved challenges. This overview aims to provide participants with valuable insights for practical industrial applications and potential future research directions. Participants will also receive a comprehensive set of resources, including online Jupyter Notebook tutorials, curated "awesome lists," and best practices for distillation and reinforcement learning (RL) training. These materials not only conclude our tutorial but also initiate a new phase in the attendees’ journey toward mastering reasoning models.


## Key References Published by Lecturers

1. DeepSeek R1 paper: "DeepSeek R1: An Open-Source LLM for Reasoning"
2. NeMo 2.0 framework documentation: https://nvidia.github.io/NeMo/
3. Relevant research on knowledge distillation in LLMs: [List 3-5 key papers]
4. RL for LLM training: [List 3-5 key papers]


## Resource Requirements

* Jupyter notebooks 
* APIs for accessing various reasoning models (free tiers)
* NeMo framework (open-source)
* Sample datasets for distillation and RL training
* Open-source models (Qwen, Llama)

## Short Bio of Tutors

**Zhaopeng Qiu** is currently working at NVIDIA as a Deep Learning Solution Architect. He graduated from Peking University in 2018. His research focuses on large language models (LLMs), recommender systems, and natural language processing (NLP). He has authored over 20 research papers published in leading journals and conferences, including KDD, AAAI, WWW, TKDE, NAACL, COLING, and others.

**Jingqi Zhang** is currently a Solution Architect at NVIDIA, specializing in large language models (LLMs). His work focuses on various aspects of LLMs including training methodologies, practical applications, and reasoning models. Prior to joining NVIDIA, Jingqi obtained both his Bachelor’s and Master’s degrees in Computer Science and Technology from Xi’an Jiaotong University.

**Shuang Yu is** a Solution Architect at NVIDIA focusing on LLMs. She holds a Bachelor's Degree in Automation and a Master's Degree in Computer Science from Tsinghua University. Before joining NVIDIA, Shuang worked as a software architect at IBM, where she led the development of an enterprise-level machine learning platform.

