# HPINet: A Hierarchical Physics-Informed Node-Edge Integrating GCNN for AC Optimal Power Flow

This is the code repository for the paper:

> HPINet: A Hierarchical Physics-Informed Node-Edge Integrating GCNN for AC Optimal Power Flow
Zezheng Zhang, [Zezheng Zhang](https://example.com/zezheng), Zezheng Zhang, Zezheng Zhang, Zezheng Zhang, Zezheng Zhang, Zezheng Zhang, Zezheng Zhang* and Zezheng Zhang

*Corresponding author

[arXiv] [Paper with Code]
![项目相关的描述](image.png)

# Introduction
Alternating Current Optimal Power Flow (AC-OPF) aims to determine the most cost-effective resource allocation strategy while ensuring the stable operation of all components within the power system. Conventional AC-OPF solvers lack physical constraints such as generator power, voltage magnitude, and branch power, making it difficult to ensure the optimality and feasibility of solutions. Inspired by the relationship between power flow prediction and the state variations of the system across different operating stages, we propose HPINet, Hierarchical Physics-Informed Node-Edge Integrating Graph Convolutional Neural Network (GCNN), a novel approach that efficiently tackles the emerging challenge of minimizing power flow costs in an evolving power system. Specifically, we develop a topological data structure network based on two perspectives: node graphs and edge graphs. By applying stringent constraints to the states of key variables within these hierarchical networks during operation, the model is compelled to adhere to predefined operational limits while preserving critical features, thus guaranteeing precise predictions of optimal power generation. Furthermore, we introduce a temporal multi-feature assistance module designed to capture the spatiotemporal dependencies between generators and loads in OPF. This module provides additional features to support power generation predictions while establishing a critical link for topological data associations across temporal and spatial dimensions. Extensive experiments conducted on multiple authoritative datasets demonstrate that HPINet robustly addresses load planning challenges in existing power grids, achieving state-of-the-art performance compared to other advanced methods. 

# Environment Setup

To set up the environment for DOEI, follow these steps:

```sh
# create a clean conda environment from scratch
conda create --name DOEI python=3.7
conda activate DOEI

# install pip
conda install ipython
conda install pip

# install required packages
pip install -r requirements.txt
