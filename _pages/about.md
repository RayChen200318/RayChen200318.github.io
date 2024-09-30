---
permalink: /
title: "Introduction about me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a fourth year undergraduate student from [School of Economics](https://soe.xmu.edu.cn/), [Xiamen University](https://www.xmu.edu.cn/). My research interest includes causal Inference, machine learning, spatial statistics and Bayesian statistics.

I'm very fortunate to be advised by [Prof. Xu Xingbai](https://faculty.xmu.edu.cn/XXB/zh_CN/index.htm) from [School of Economics](https://soe.xmu.edu.cn/), [Xiamen University](https://www.xmu.edu.cn/).

Academic Background and Skills
======
During my undergraduate studies, I earned A+ grades in **Real Analysis**, **Advanced Algebra**, **C Programming**, **Differential Equations** and A in most core courses, including **Mathematical Analysis**, **Probability Theory**, **Mathematical Statistics**, **Stochastic Processes**, **Time Series Analysis**, **Bayesian Statistics**, etc. 

I am proficient in using R and Python for data processing and analysis. I have uploaded most of my coursework and code from core courses to GitHub. Notably, this includes the **Robust Model-free Bayesian Classifier** I developed and the replication code for the paper _Estimation and Selection of a Spatial Lag Model_.

I am currently working on a research project in Spatial Statistics and continuing to enhance my knowledge through graduate-level courses in **Artificial Intelligence and Machine Learning**, **Large Sample Theory**, and **Advanced Econometrics**.


Professional Experiences
======
<div style="display: flex; justify-content: space-between;">
  <span>June 2023 - Present</span>
  <span>Research Assistant</span>
</div>  
<br>
During this period, I worked as a research assistant (RA) for [Prof. Xu Xingbai](https://faculty.xmu.edu.cn/XXB/zh_CN/index.htm). My responsibilities include:
<br>
* **Literature Review:** Search for, read, and summarize academic literature related to the research topic to help determine research directions and methodologies.<br>
* **Data Collection:** Collect required data from databases, experiments, or surveys, ensuring data integrity and accuracy.<br>
* **Data Analysis:** Use tools like R and Python to clean, analyze, and visualize data to derive meaningful conclusions.<br>
* **Coding and Maintenance:** Develop algorithms and models for research projects to implement the necessary experimental functions.<br>
* **Assisting in Paper Writing:** Participate in the writing and editing of academic papers, including drafting manuscripts, creating figures, and organizing references.<br>
* **Meeting Participation:** Regularly attend research group meetings to report work progress, discuss research issues, and plan next steps.<br>
* **Teaching Assistance:** Assist the professor in preparing course materials and guiding students in completing related tasks.<br>
<br>
<div style="display: flex; justify-content: space-between;">
  <span>March 2024 - June 2024</span>
  <span>Peer Teaching Assistant</span>
</div>  
<br>
I worked as a peer teaching assistant for the course **Real Analysis**. My responsibilities include:
<br>
* **Provided Personalized Guidance:** Offered one-on-one consultations for students who needed extra help, tailoring my assistance to their individual learning needs.<br>
* **Developed Supplemental Resources:** Created additional study guides, problem sets, and solution manuals to support students outside of class hours.<br>
* **Encouraged Peer Collaboration:** Facilitated study groups among students to promote collaborative learning and peer support.<br>
<br>
<div style="display: flex; justify-content: space-between;">
  <span>July 2024 - September 2024</span>
  <span>Research Assistant</span>
</div>  
<br>
During this period, I worked as a research assistant (RA) for [Prof. Liu Jingyuan](https://faculty.xmu.edu.cn/LJY/zh_CN/index.htm). My work involved translating the Chinese subtitles of Professor Liu's online courses into English.

Researches and Projects
======

Estimation and Selection of Spatial Weight Model Using Linear Quadratic Instrumental Variables
------
Building upon recent developments in spatial econometric models that address the misspecification of spatial weight matrices through adaptive LASSO techniques, my research aims to enhance the selection of instrumental variables within this framework. Specifically, I introduce linear quadratic forms of instrumental variables to improve the estimation properties of the model. This approach seeks to refine the estimation process by leveraging more informative instruments, thereby achieving better convergence rates and oracle properties. By incorporating these advanced IV selection methods, my work contributes to a more robust and efficient unified framework for the estimation and selection of spatial weight matrices in spatial econometric analysis.
<br>
The research proposal and core codes on this project can be found at ([link](https://github.com/RayChen200318/Estimation-and-Selection-of-Spatial-Weight-Matrices-Using-Linear-Quadratic-Instrumental-Variables)).

A Robust Model-free Bayesian Classifier
------
Numerous algorithms have been developed for classification tasks in machine learning, with the Naive Bayes classifier (NBC) being one of the simplest. Despite its effectiveness, NBC's assumptions of attribute independence and normal distribution are often violated. Bayesian networks (BN) model relationships between attributes but require complex, NP-hard training and rely on prior probability distributions, which can lead to poor performance if mismatched with the data. I applied Principal Component Analysis (PCA) for data preprocessing and used cross-validation to select the optimal number of principal components. I also estimated prior probabilities using M-estimation to enhance model robustness. This led to the development of the robust model-free Bayesian classifier (RMFBC). Testing RMFBC on several UCI datasets, I found it outperformed NBC in all cases and surpassed BN in some cases. This concludes that RMFBC offers a competitive alternative for datasets with non-normal distributions and high-dimensional, highly correlated attributes.
<br>
The full article and core codes on this project can be found at ([link](https://github.com/RayChen200318/A-robust-model-free-Bayesian-classifier)).
