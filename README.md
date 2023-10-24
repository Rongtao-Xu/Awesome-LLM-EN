# Awesome-LLM-EN
  [![Awesome](https://img.shields.io/badge/Awesome-LLM-EN)](https://github.com/Rongtao-Xu/Awesome-LLM-EN) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
  ![](https://img.shields.io/github/last-commit/RManLuo/Awesome-LLM-EN?color=green) 
 ![](https://img.shields.io/badge/PRs-Welcome-red)
 ![](https://img.shields.io/github/stars/RManLuo/Awesome-LLM-EN?color=yellow)
![](https://img.shields.io/github/forks/RManLuo/Awesome-LLM-EN?color=lightblue) 

This is a compilation on "LLMs for Embodied Navigation," including state-of-the-art benchmarks and datasets.

In recent years, the rapid advancement of Large Language Models (LLMs) like GPT has garnered increasing attention for their potential in various practical applications. The integration of LLMs with Embodied Intelligence has emerged as a new focal area. Embodied Intelligence underscores that intelligent behavior stems not just from computational models but also involves physical interactions between robots or intelligent agents and their environment. The essence of embodied intelligence is that genuine intelligence requires the context of both the body and the surrounding environment, necessitating systems that can perceive through sensors and act via actuators. This integration is especially critical for applications that demand language and image processing capabilities. Overall, the amalgamation of LLMs and embodied intelligence offers immense potential and opens up new avenues for AI application, raising fresh research challenges including model interpretability and real-time performance.

Among the numerous applications of LLMs, navigation tasks stand out as they require deep environmental understanding and quick, accurate decision-making. LLMs can enrich embodied intelligence systems with advanced environmental perception and decision-making support through their robust language and image processing skills. This article focuses on navigation, offering a comprehensive summary of the integration between LLMs and embodied intelligence. It covers state-of-the-art models, research methodologies, and evaluates the pros and cons of current embodied navigation models and datasets. Finally, the article provides insights into the role of LLMs in embodied intelligence based on the latest research, projecting future developments in the field.

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
    - [KG-enhanced LLM Pre-training](#kg-enhanced-llm-pre-training)
    - [KG-enhanced LLM Inference](#kg-enhanced-llm-inference)
    - [KG-enhanced LLM Interpretability](#kg-enhanced-llm-interpretability)
  - [LLMs for Few-Shot Planning](#llms-for-grounded-few-shot-planning)
    - [LLM-augmented KG Embedding](#llm-augmented-kg-embedding)
    - [LLM-augmented KG Completion](#llm-augmented-kg-completion)
    - [LLM-augmented KG-to-Text Generation](#llm-augmented-kg-to-text-generation)
    - [LLM-augmented KG Question Answering](#llm-augmented-kg-question-answering)
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
# Star History

[![Star History Chart](https://api.star-history.com/svg?repos=PlexPt/Awesome-LLM-EN&type=Date)](https://star-history.com/#PlexPt/Awesome-LLM-EN&Date)
