# Awesome-LLM-EN
  [![Awesome](https://img.shields.io/badge/Awesome-LLM-EN)](https://github.com/Rongtao-Xu/Awesome-LLM-EN) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
  ![](https://img.shields.io/github/last-commit/Rongtao-Xu/Awesome-LLM-EN?color=green) 
 ![](https://img.shields.io/badge/PRs-Welcome-red)
 ![](https://img.shields.io/github/stars/Rongtao-Xu/Awesome-LLM-EN?color=yellow)
![](https://img.shields.io/github/forks/Rongtao-Xu/Awesome-LLM-EN?color=lightblue) 

<div style="text-align: justify">


This is a compilation on "LLMs for Embodied Navigation," including state-of-the-art benchmarks and datasets.  

 
In recent years, the rapid advancement of Large Language Models (LLMs) like GPT has garnered increasing attention for their potential in various practical applications. The integration of LLMs with Embodied Intelligence has emerged as a new focal area. Embodied Intelligence underscores that intelligent behavior stems not just from computational models but also involves physical interactions between robots or intelligent agents and their environment. The essence of embodied intelligence is that genuine intelligence requires the context of both the body and the surrounding environment, necessitating systems that can perceive through sensors and act via actuators. This integration is especially critical for applications that demand language and image processing capabilities. Overall, the amalgamation of LLMs and embodied intelligence offers immense potential and opens up new avenues for AI application, raising fresh research challenges including model interpretability and real-time performance.

Among the numerous applications of LLMs, navigation tasks stand out as they require deep environmental understanding and quick, accurate decision-making. LLMs can enrich embodied intelligence systems with advanced environmental perception and decision-making support through their robust language and image processing skills. This article focuses on navigation, offering a comprehensive summary of the integration between LLMs and embodied intelligence. It covers state-of-the-art models, research methodologies, and evaluates the pros and cons of current embodied navigation models and datasets. Finally, the article provides insights into the role of LLMs in embodied intelligence based on the latest research, projecting future developments in the field.
</div>

<p align="center">
  <img src="figs/Awesome-LLM-EN.png" width="800">
</p>

## News
😊 This project is under development. You can hit the **STAR** and **WATCH** to follow the updates.
* Our Awesome-LLM-EN reasoning paper: is now public.

## Overview
In this repository, we collect recent advances in unifying LLMs and Agents. We have identified two commonly used general models: *1) LLM for Planner and *2) LLM for Semantic Understanding..

<p align="center">
  <img src="figs/PlanningPic.png" width = "800"/>
</p>

<p align="center">
  <img src="figs/SemanticPic.png" width = "800"/>
</p>

## Table of Contents
- [Awesome-LLM-EN](#awesome-llm-en)
  - [News](#news)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Related Surveys](#related-surveys)
 -  [LLMs for Grounded Language Understanding](#llms-for-grounded-language-understanding)
  - [LLMs for Few-Shot Planning](#llms-for-grounded-few-shot-planning)
  - [Applications](#applications)
    - [Navigation](#navigation)
    - [Assistant](#assistant)

## Related Surveys

* A Real 3D Embodied Dataset for Robotic Active Visual Learning (IEEE, 2022) [[paper]](https://ieeexplore.ieee.org/abstract/document/9729641)
* ProcTHOR: Large-Scale Embodied AI Using Procedural Generation (Arxiv, 2022) [[paper]](https://arxiv.org/pdf/2206.06994.pdf)
* SOON: Scenario Oriented Object Navigation with Graph-based Exploration (Arxiv, 2021) [[paper]](https://arxiv.org/pdf/2103.17138.pdf)
* Room-Across-Room: Multilingual Vision-and-Language Navigation with Dense Spatiotemporal Grounding (Arxiv, 2020) [[paper]](https://arxiv.org/pdf/2010.07954.pdf)
* Reverie: Remote embodied visual referring expression in real indoor environments (Arxiv, 2019) [[paper]](https://arxiv.org/pdf/1904.10151.pdf)
* Vision-and-Language Navigation: Interpreting visually-grounded navigation instructions in real environments (CVPR, 2018) [[paper]](https://arxiv.org/pdf/1711.07280.pdf)
* Touchdown: Natural Language Navigation and Spatial Reasoning in Visual Street Environments (CVPR, 2019) [[paper]](https://arxiv.org/pdf/1811.12354.pdf)
## LLMs for Grounded Language Understanding
"Grounded Language Understanding" aims to reconcile the abstract symbols processed by language models with concrete entities, actions, or states in the physical or simulated world. This is pivotal for applications requiring real-world interaction, such as robotic control, natural language interfaces, or advanced research in Embodied Intelligence.

  Within this context, LLMs like GPT-3, GPT-4, and BERT can integrate with sensors, databases, or simulated environments to generate and interpret language applicable to real-world scenarios. In a robotic setting, for instance, an LLM could interpret sensor data, process natural language directives, and issue control signals to the robot, thereby bridging high-level language and low-level actions.

  LLMs' application in grounded language understanding is an evolving research area, intersecting with disciplines such as robotics, computer vision, and human-computer interaction. Techniques like Few-Shot Learning and Transfer Learning are commonly used to adapt these pre-trained models to specialized grounding tasks with minimal additional training.

  Although LLMs have advanced significantly in NLP, they primarily excel in text generation or classification and seldom engage with tangible entities or real-world situations. Their limitations include a lack of foundational knowledge, impairing their ability to process interrelated concepts and function in interactive settings . To mitigate these issues, researchers have employed various strategies, such as 1) fine-tuning pre-trained models, 2) implementing reinforcement learning algorithms for decision-making in complex environments, and 3) devising specialized architectures for multimodal learning.

  For example, Yang et al. introduced LLM-Grounder, which integrates GPT-4 with CLIP for applications in 3D visual grounding. Carta et al.\cite{carta2023grounding}utilized online reinforcement learning to boost LLM performance in reinforcement learning tasks, improving both sample efficiency and generalization.

  Despite their immense potential and practical applications, LLMs face numerous technical and theoretical challenges in grounded language understanding. These include the integration of text, images, and sensor data, latency reduction for real-time applications, and maintaining training efficiency without sacrificing performance. With ongoing research and emerging technologies, significant advancements in this domain are anticipated.
# Star History

[![Star History Chart](https://api.star-history.com/svg?repos=PlexPt/Awesome-LLM-EN&type=Date)](https://star-history.com/#PlexPt/Awesome-LLM-EN&Date)
