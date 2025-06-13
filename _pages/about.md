---
permalink: /
title: "Welcome to my homepage!!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a research assistant with **Dr. Ming-Chung Chang** at the [Institute of Statistical Science, Academia Sinica](https://www.stat.sinica.edu.tw/eng/). Before joining Academia Sinica, I earned a Master’s degree in Applied Statistics from [the University of Michigan, Ann Arbor](https://lsa.umich.edu/stats), in 2024 and a Bachelor’s degree in Mathematics from [National Tsing Hua University](https://www.math.nthu.edu.tw/index.php) in 2023. For more details about my background, please refer to my CV.

# Research Interest
My general research lies in the intersection of **machine learning** & **statistics**, focused on collaboration, prediction, and interoperability. Here are some keywords that best describe my previous research projects:
- Sequential Decision Making
- Collaborative and Federated Learning
- Explainable AI

# Education
- Incoming PhD in Mathematics Research
  - Department of Mathematics, Imperial College London. 09/2025 - expected 09/2029
  - Advisor: Prof. Kelly W. Zhang
  
- Master of Science in Applied Statistics
  - Department of Statistics, The University of Michigan, Ann Arbor. 08/2023 - 12/2024
  - Advisor: Prof. Raed Al Kontar

- Bachelor of Science in Mathematics
  - Department of Mathematics, National Tsing Hua University. 09/2019 - 06/2023
  - Advisor: Dr. Ming-Chung Chang
 
# Publications

<details>
<summary><strong>1. Bootstrap Aggregation for Regression Problems via Generalized Least Squares</strong><br>
C.-Y. Chang and M.-C. Chang. Submitted, 2025.</summary>

Bootstrap aggregation, commonly known as bagging, is a foundational technique in ensemble learning aimed at improving the predictive performance of models. The effectiveness of bagging largely depends on how correlations among the aggregated models are managed. For example, random forests—a popular ensemble method—mitigate this issue by randomly selecting features to reduce the correlation between individual tree models. In this study, we introduce a bootstrap aggregation method for regression tasks based on the concept of generalized least squares to enhance the predictive accuracy of bagging models. Theoretical analysis and empirical experiments demonstrate the efficacy of the proposed approach.
</details>

<br>

<details>
<summary><strong>2. LLINBO: Trustworthy LLM In-the-Loop Bayesian Optimization</strong><br>
C.-Y. Chang, M. Azvar, C. Okwudire and R. A. Kontar. arXiv preprint arXiv:2505.14756, 2025. <a href="https://arxiv.org/abs/2505.14756">[arXiv link]</a></summary>

Bayesian optimization (BO) is a sequential decision-making tool widely used for optimizing expensive black-box functions. Recently, Large Language Models (LLMs) have shown remarkable adaptability in low-data regimes, making them promising tools for black-box optimization by leveraging contextual knowledge to propose high-quality query points. However, relying solely on LLMs as optimization agents introduces risks due to their lack of explicit surrogate modeling and calibrated uncertainty, as well as their inherently opaque internal mechanisms. This structural opacity makes it difficult to characterize or control the exploration–exploitation trade-off, ultimately undermining theoretical tractability and reliability. To address this, we propose \texttt{LLINBO}: LLM-in-the-Loop BO, a hybrid framework for BO that combines LLMs with statistical surrogate experts (e.g., Gaussian Processes ($\mathcal{GP}$)). The core philosophy is to leverage contextual reasoning strengths of LLMs for early exploration, while relying on principled statistical models to guide efficient exploitation. Specifically, we introduce three mechanisms that enable this collaboration and establish their theoretical guarantees. We end the paper with a real-life proof-of-concept in the context of 3D printing. The code to reproduce the results can be found at \url{https://github.com/UMDataScienceLab/LLM-in-the-Loop-BO}.

</details>

<br>

<details>
<summary><strong>3. FCBO: Federated Contextual Bayesian Optimization for Cross-Context Collaboration</strong><br>
C.-Y. Chang and R. A. Kontar. Ongoing, 2025.</summary>

In traditional Bayesian Optimization (BO), the client selects subsequent experimental points based solely on previously observed design points and outcomes. However, in Contextual Bayesian Optimization (CBO), decisions must also account for an observed context, enabling more tailored decision-making that adapts to each unique setting. This approach has proven widely applicable in fields such as news recommendation and drug discovery, where optimization decisions are heavily context-dependent. In this paper, we introduce \texttt{FCBO}, a unified framework that enables multiple clients to perform CBO jointly without sharing the raw data. We provide theoretical guarantees and validate the framework’s effectiveness through simulation studies and real-world applications, demonstrating significant improvements over existing methods.
</details>

<br>

<details>
<summary><strong>4. Improving the Stability of Accumulated Local Effects with D-Optimal Design</strong><br>
C.-Y. Chang and M.-C. Chang. Ongoing, 2025.</summary>

</details>

# Academic Advisors
- I am extremely fortunate to have been advised by [Dr. Ming-Chung Chang](https://sites.google.com/view/mcchang/), an Associate Research Fellow at the Institute of Statistical Science, Academia Sinica, during my senior year as a Mathematics student. He has guided my journey into the field of statistics from then until now.
- During my master's studies, I am very pleased to be advised by [Prof. Raed Al Kontar](https://alkontar.engin.umich.edu/), an Associate professor at the Department of Industrial and Operations Engineering, The University of Michigan, Ann Arbor. We collaboratively developed two papers on sequential decision-making, which sparked my interest in this field.

# Contact
- Address: 116, Statistical Science Building, Academia Sinica.
- Email: cchihyu at {umich.edu, stat.sinica.edu.tw}

Last Update: Jun. 3, 2025
