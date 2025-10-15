---
title: Research
icon: fas fa-flask
order: 1
---
## Research Projects
- [**Secure Algorithms for Vertically Federated Multi-Task Representation Learning**](https://singhankitpratap.github.io/sap_files/isit_pres25.pdf)| **Byzantine robustness, Low Rank Matrix Recovery, Multi-Task Representation Learning**| Relevant paper: [C5, C6](#conference-papers)
  
Imagine you want to predict lung disease using chest X-rays collected from different hospitals. To protect patient privacy, each hospital trains a model locally and only shares updates. However, some hospitals might use unreliable or compromised systems that send incorrect updates. These issues, known as Byzantine failures, can harm the overall learning process.

We developed a method called **Byzantine Resilient Federated Alternating Gradient Descent** that can still train accurate models even when several participants are Byzantine. It uses robust statistics and takes advantage of the low-rank structure in the data to learn in a sample efficient way.

It works for many **low rank matrix recovery problems**. One useful example is a **web-based recommender system** that suggests movies to users based on their ratings and reviews. Our method also applies to **compressed sensing, used in Magnetic Resonance Imaging to speed up scans**. It also reduces training time by allowing **large language models** to be trained faster using **multiple GPUs or servers**.

- [**Fast Federated Few-Shot Learning**](https://singhankitpratap.github.io/sap_files/icml_pres.pdf)| **PyTorch, Docker, AWS**| [Source code](https://github.com/singhankitpratap/Federated-ByzaltGDmin.git)| Relevant paper: [C4](#conference-papers), [J1](#journal-papers)
  
A **Byzantine-resilient** federated algorithm, AltGDmin, for low-dimensional representation learning a.k.a. Few-Shot Learning. It is **communication-efficient, robust to adversarial attacks**, and guarantees convergence. Deployed on **AWS** using **Docker Swarm**, the model achieves high accuracy using `5%` of the data compared to the problem dimension. 

- [**Resilient Federated Principal Subspace Estimation**](https://singhankitpratap.github.io/sap_files/isit_pres.pdf)| **PyTorch**| [Source code](https://github.com/singhankitpratap/subspace_median.git)| Relevant paper: [C3](#conference-papers)

A novel technique, **Subspace Median**, along with a **Python package** compatible with **PyTorch**, enabling **Principal Component Analysis (PCA)** on distributed or federated datasets across multiple devices, even in the presence of up to `50%` corrupt or erroneous devices.

- [**Federated Reinforcement Learning (RL)**](https://singhankitpratap.github.io/sap_files/fedreinf.pdf)| **PyTorch, Open AI’s Gym**| [Source code](https://github.com/singhankitpratap/fed_reinforce.git)| Relevant paper: [C1](#conference-papers)
  
A federated learning framework to efficiently manage data samples in dynamic systems like the **Open AI’s CartPole-v1 environment**, utilizing **policy gradient methods**. This work was developed using **PyTorch, Open AI’s Gym library**. Integrated principles of algorithm optimization and control theory were used to provide convergence guarantees.

## Publications
### Journal papers
- [J1] **AP Singh** and N Vaswani, [Byzantine-Resilient Federated PCA and Low Rank Column-wise Sensing](https://ieeexplore.ieee.org/abstract/document/10643192) \
  **IEEE Transactions on Information Theory**, August 2024.

### Conference papers
- [C6] **AP Singh**, AA Abbasi, and N Vaswani, [Byzantine-Resilient Federated Alternating Gradient Descent and Minimization for Partly-Decoupled Low Rank Matrix Learning](https://openreview.net/forum?id=iBOMvaa2aN) \
  **International Conference on Machine Learning 2025 (ICML 2025)**, July 2025.\
  [Presentation](https://singhankitpratap.github.io/sap_files/icml_pres25.pdf)\
  [Quick View](https://singhankitpratap.github.io/sap_files/ICML25.pdf)
- [C5] **AP Singh** and N Vaswani, Secure Algorithms for Vertically Federated Multi-Task Representation Learning\
  **IEEE International Symposium on Information Theory (ISIT 2025)**, June 2025.\
  [Presentation](https://singhankitpratap.github.io/sap_files/isit_pres25.pdf)
- [C4] **AP Singh** and N Vaswani, [Byzantine Resilient and Fast Federated Few-Shot Learning](https://proceedings.mlr.press/v235/singh24f.html) \
  **International Conference on Machine Learning 2024 (ICML 2024)**, July 2024.\
  [Presentation](https://singhankitpratap.github.io/sap_files/icml_pres.pdf)\
  [Quick View](https://singhankitpratap.github.io/sap_files/ICML.pdf)
- [C3] **AP Singh** and N Vaswani, [Byzantine-Resilient Federated Principal Subspace Estimation](https://ieeexplore.ieee.org/abstract/document/10619161) \
  **IEEE International Symposium on Information Theory (ISIT 2024)**, July 2024.\
  [Presentation](https://singhankitpratap.github.io/sap_files/isit_pres.pdf)
- [C2] **AP Singh** and N Vaswani, [Byzantine-resilient Federated Low-Rank Column-wise Compressive Sensing](https://ieeexplore.ieee.org/abstract/document/10313492) \
  **IEEE Annual Allerton Conference on Communication, Control, and Computing**, September 2023.\
  [Presentation](https://singhankitpratap.github.io/sap_files/allerton_pres.pdf)
- [C1] **AP Singh** and R Tali, [Byzantine Resilient Federated REINFORCE (GM-FedREINFORCE)](https://ieeexplore.ieee.org/abstract/document/10460041) \
  **IEEE International Conference on Machine Learning and Applications (ICMLA 2023)**, December 2023.\
  [Quick View](https://singhankitpratap.github.io/sap_files/fedreinf.pdf)

## Reviewing service
- International Conference on Artificial Intelligence and Statistics (AISTATS) (2024).
- *IEEE* International Symposium on Information Theory (ISIT) (2024).
