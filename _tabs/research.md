---
title: Research
icon: fas fa-flask
order: 1
---
## Research Projects
- [**Fast Federated Few-Shot Learning**](https://github.com/singhankitpratap/singhankitpratap.github.io/raw/main/sap_files/icml_pres.pdf)| **PyTorch, Docker, AWS**| [Source code](https://github.com/singhankitpratap/Federated-ByzaltGDmin.git)| Relevant paper: [C4](#conference-papers), [J1](#journal-papers)
  
A **Byzantine-resilient** federated algorithm, AltGDmin, for low-dimensional representation learning a.k.a. Few-Shot Learning. It is **communication-efficient, robust to adversarial attacks**, and guarantees convergence. Deployed on **AWS** using **Docker Swarm**, the model achieves high accuracy using `5%` of the data compared to the problem dimension. 

- **Resilient Federated Principal Subspace Estimation**| **PyTorch**| [Source code](https://github.com/singhankitpratap/subspace_median.git)| Relevant paper: [C3](#conference-papers)

A novel technique, **Subspace Median**, along with a **Python package** compatible with **PyTorch**, enabling **Principal Component Analysis (PCA)** on distributed or federated datasets across multiple devices, even in the presence of up to `50%` corrupt or erroneous devices.

- **Federated Reinforcement Learning (RL)**| **PyTorch, Open AI’s Gym**| [Source code](https://github.com/singhankitpratap/fed_reinforce.git)| Relevant paper: [C1](#conference-papers)
  
A federated learning framework to efficiently manage data samples in dynamic systems like the **Open AI’s CartPole-v1 environment**, utilizing **policy gradient methods**. This work was developed using **PyTorch, Open AI’s Gym library**. Integrated principles of algorithm optimization and control theory were used to provide convergence guarantees.

## Publications
### Journal papers
- [J1] **AP Singh** and N Vaswani, [Byzantine-Resilient Federated PCA and Low Rank Column-wise Sensing](https://ieeexplore.ieee.org/abstract/document/10643192) \
  **IEEE Transactions on Information Theory**, August 2024.

### Conference papers
- [C4] **AP Singh** and N Vaswani, [Byzantine Resilient and Fast Federated Few-Shot Learning](https://proceedings.mlr.press/v235/singh24f.html) \
  **International Conference on Machine Learning 2024 (ICML 2024)**, July 2024.
- [C3] **AP Singh** and N Vaswani, [Byzantine-Resilient Federated Principal Subspace Estimation](https://ieeexplore.ieee.org/abstract/document/10619161) \
  **IEEE International Symposium on Information Theory (ISIT 2024)**, July 2024.
- [C2] **AP Singh** and N Vaswani, [Byzantine-resilient Federated Low-Rank Column-wise Compressive Sensing](https://ieeexplore.ieee.org/abstract/document/10313492) \
  **IEEE Annual Allerton Conference on Communication, Control, and Computing**, September 2023.
- [C1] **AP Singh** and R Tali, [Byzantine Resilient Federated REINFORCE (GM-FedREINFORCE)](https://ieeexplore.ieee.org/abstract/document/10460041) \
  **IEEE International Conference on Machine Learning and Applications (ICMLA 2023)**, December 2023.
