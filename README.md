# Awesome-LLM-Reliability-Robustness-Safety
<!-- Awesome-LLM-Robustness: a curated list of Robustness, Reliability and Safety in Large Language Models -->

\
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/hee9joon/Awesome-Diffusion-Models) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Made With Love](https://img.shields.io/badge/Made%20With-Love-red.svg)](https://github.com/chetanraj/awesome-github-badges)

This repository contains a collection of resources and papers on **Reliability**, **Robustness**  and **Safety** in **Large Language Models (LLMs)**.

<!-- ## Contents
- [Resources](#resources)
  - [Introductory Posts](#introductory-posts)
  - [Introductory Papers](#introductory-papers)
  - [Introductory Videos](#introductory-videos)
  - [Introductory Lectures](#introductory-lectures)
  - [Tutorial and Jupyter Notebook](#tutorial-and-jupyter-notebook)

- [Papers](#papers)
  - [Survey](#survey)
  - [Reliability](#reliability)
    - [Generation](#generation)
    - [Segmentation](#segmentation)
  - [Robustness](#robustness)
    - [Generation](#generation-1)
    - [Conversion](#conversion)



# Resources
## Introductory Posts

**How diffusion models work: the math from scratch** \
*Sergios Karagiannakos,Nikolas Adaloglou* \
[[Website](https://theaisummer.com/diffusion-models/?fbclid=IwAR1BIeNHqa3NtC8SL0sKXHATHklJYphNH-8IGNoO3xZhSKM_GYcvrrQgB0o)] \
24 Sep 2022

**A Path to the Variational Diffusion Loss** \
*Alex Alemi* \
[[Website](https://blog.alexalemi.com/diffusion.html)] [[Colab](https://colab.research.google.com/github/google-research/vdm/blob/main/colab/SimpleDiffusionColab.ipynb)] \
15 Sep 2022

## Introductory Papers

**Understanding Diffusion Models: A Unified Perspective** \
*Calvin Luo* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2208.11970)] \
25 Aug 2022

**How to Train Your Energy-Based Models** \
*Yang Song, Diederik P. Kingma* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2101.03288)] \
9 Jan 2021

## Introductory Videos
**diffusion-for-beginners** \

## Introductory Lectures
**diffusion-for-beginners** \

## Tutorial and Jupyter Notebook
**diffusion-for-beginners** \ -->



# Papers

## Evaluation

**Holistic Evaluation of Language Models** \
*Percy Liang, Rishi Bommasani, Tony Lee, Dimitris Tsipras, Dilara Soylu, Michihiro Yasunaga, Yian Zhang, Deepak Narayanan, Yuhuai Wu, Ananya Kumar, Benjamin Newman, Binhang Yuan, Bobby Yan, Ce Zhang, Christian Cosgrove, Christopher D. Manning, Christopher Ré, Diana Acosta-Navas, Drew A. Hudson, Eric Zelikman, Esin Durmus, Faisal Ladhak, Frieda Rong, Hongyu Ren, Huaxiu Yao, Jue Wang, Keshav Santhanam, Laurel Orr, Lucia Zheng, Mert Yuksekgonul, Mirac Suzgun, Nathan Kim, Neel Guha, Niladri Chatterji, Omar Khattab, Peter Henderson, Qian Huang, Ryan Chi, Sang Michael Xie, Shibani Santurkar, Surya Ganguli, Tatsunori Hashimoto, Thomas Icard, Tianyi Zhang, Vishrav Chaudhary, William Wang, Xuechen Li, Yifan Mai, Yuhui Zhang, Yuta Koreeda* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2211.09110)] [[Website](https://crfm.stanford.edu/helm/latest/)] [[Github](https://github.com/stanford-crfm/helm)] [[Blog](https://crfm.stanford.edu/2022/11/17/helm.html)] \
16 Nov 2022

**Prompting GPT-3 To Be Reliable** \
*Chenglei Si, Zhe Gan, Zhengyuan Yang, Shuohang Wang, Jianfeng Wang, Jordan Boyd-Graber, Lijuan Wang* \
ICLR 2023. [[Paper](https://arxiv.org/abs/2210.09150)] [[Github](https://github.com/NoviScl/GPT3-Reliability)] \
17 Oct 2022

**Plex: Towards Reliability using Pretrained Large Model Extensions** \
*Dustin Tran, Jeremiah Liu, Michael W. Dusenberry, Du Phan, Mark Collier, Jie Ren, Kehang Han, Zi Wang, Zelda Mariet, Huiyi Hu, Neil Band, Tim G. J. Rudner, Karan Singhal, Zachary Nado, Joost van Amersfoort, Andreas Kirsch, Rodolphe Jenatton, Nithum Thain, Honglin Yuan, Kelly Buchanan, Kevin Murphy, D. Sculley, Yarin Gal, Zoubin Ghahramani, Jasper Snoek, Balaji Lakshminarayanan* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2207.07411)] \
15 Jul 2022

**How Robust is GPT-3.5 to Predecessors? A Comprehensive Study on Language Understanding Tasks** \
*Xuanting Chen, Junjie Ye, Can Zu, Nuo Xu, Rui Zheng, Minlong Peng, Jie Zhou, Tao Gui, Qi Zhang, Xuanjing Huang* \
arXiv 2023. [[Paper](https://arxiv.org/abs/2303.00293)][[Github](https://github.com/textflint/textflint)]
1 Mar 2023




## Reliability
### Uncertainty Estimation

**Teaching Models to Express Their Uncertainty in Words** \
*Stephanie Lin, Jacob Hilton, Owain Evans* \
TMLR 2022. [[Paper](https://arxiv.org/abs/2205.14334)] [[Github](https://github.com/sylinrl/CalibratedMath)] [[TMLR](https://openreview.net/forum?id=8s8K2UZGTZ)] [[Slide](https://owainevans.github.io/pdfs/chai_calibration_owain.pdf)]\
28 May 2022

**Semantic Uncertainty: Linguistic Invariances for Uncertainty Estimation in Natural Language Generation** \
*Lorenz Kuhn, Yarin Gal, Sebastian Farquhar*
ICLR 2023. [[Paper](https://arxiv.org/abs/2302.09664)] 
19 Feb, 2022


### Calibration


### Ambiguity 

**CLAM: Selective Clarification for Ambiguous Questions with Generative Language Models** \
*Lorenz Kuhn, Yarin Gal, Sebastian Farquhar* \
arXiv 2022. [[Paper](https://arxiv.org/abs/2303.09508)] \
15 Dec 2022


### Hallucination


### Truthful 

**TruthfulQA: Measuring How Models Mimic Human Falsehoods** \
*Stephanie Lin, Jacob Hilton, Owain Evans* \
ACL 2022. [[Paper](https://arxiv.org/abs/2109.07958)] [[Github](https://github.com/sylinrl/TruthfulQA)] [[Blog](https://www.lesswrong.com/posts/PF58wEdztZFX2dSue/how-truthful-is-gpt-3-a-benchmark-for-language-models)] \
8 Sep 2021

**Truthful AI: Developing and governing AI that does not lie** \
*Owain Evans, Owen Cotton-Barratt, Lukas Finnveden, Adam Bales, Avital Balwit, Peter Wills, Luca Righetti, William Saunders*
arXiv 2021. [[Paper](https://arxiv.org/abs/2110.06674)] [[Blog](https://www.lesswrong.com/posts/aBixCPqSnTsPsTJBQ/truthful-ai-developing-and-governing-ai-that-does-not-lie)]\
13 Oct, 2021




## Robustness
### Invariance


### Distribution Shift



### Generalization

### Adversarial 



## Safety

### Bias

### Fairness

### Privacy




<!-- # Research Team & Reseachers 

- [Owain Evans](https://owainevans.github.io/): Research Associate in Artificial Intelligence, University of Oxford
 -->

