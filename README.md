# Awesome Papers of Time Series Foundation Models 📈

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of foundational papers on **Time Series Foundation Models**, including advancements in universal forecasting, large-scale time series models, pre-training methods, and related benchmarks. This repository aims to serve as a starting point for researchers, practitioners, and enthusiasts to explore the rapidly growing field of time series modeling with foundational AI approaches.

---

## 🎯 Goals of This Repository
- **Centralized Knowledge**: Collect and organize important research papers in time series foundation models.
- **Continuous Updates**: Stay updated with the latest breakthroughs.
- **Open Contribution**: Encourage the community to share new and impactful papers.

---

## 📄 Table of Contents

- [Universal Time Series Models](#universal-forecasting-transformers)
- [Benchmarks and Datasets](#benchmarks-and-datasets)
- [Contributing](#contributing)

---

## 📚 Universal Forecasting Transformers

### **[MOIRAI: Unified Training of Universal Time Series Forecasting Transformers](https://arxiv.org/abs/2402.02592)**
- **Authors**: Gerald Woo, Chenghao Liu, Akshat Kumar, et al.
- **Abstract**: MOIRAI is a universal time series forecasting framework based on a masked encoder architecture. It tackles challenges like multi-frequency learning, any-variate forecasting, and flexible distribution modeling. Trained on the LOTSA dataset with over 27 billion observations, MOIRAI achieves state-of-the-art performance in both zero-shot and in-distribution tasks.
- **Key Contributions**:
  - Any-Variate Attention mechanism for handling arbitrary variable dimensions.
  - LOTSA, a large-scale open dataset for pre-training.
  - Mixture distributions for probabilistic forecasting.

---

### **[TimesFM: A Decoder-Only Foundation Model for Time-Series Forecasting](https://arxiv.org/abs/2310.10688)**
- **Authors**: A. Das, W. Kong, et al.
- **Abstract**: TimesFM introduces a decoder-only transformer framework for time-series forecasting, inspired by language model architectures. It achieves near-supervised performance in zero-shot settings and demonstrates strong long-range forecasting capabilities.
- **Key Contributions**:
  - Patch-based input/output design for flexible predictions.
  - Pre-trained on large-scale real-world and synthetic data.


### **[Chronos: Learning the Language of Time Series](https://arxiv.org/abs/2310.01728)**
- **Authors**: N. Gruver, M. Finzi, et al.
- **Abstract**: Chronos leverages natural language pre-training paradigms for time series forecasting by tokenizing time series data into discrete tokens. It employs synthetic data generation techniques to augment training and achieve state-of-the-art zero-shot performance.
- **Key Contributions**:
  - TSMixup and KernelSynth for data augmentation.
  - Use of language modeling techniques for forecasting.
 
### **[Timer: Generative Pre-trained Transformers Are Large Time Series Models](https://arxiv.org/abs/2402.02368)**
- **Authors**: Yong Liu, Haoran Zhang, Chenyu Li, Xiangdong Huang, Jianmin Wang, Mingsheng Long
- **Abstract**: This paper introduces **Timer**, a generative pre-trained transformer designed as a large-scale time series model (LTSM). Timer unifies heterogeneous time series into a single-series sequence (S3) format, leveraging large-scale datasets with up to 1 billion time points for pre-training. The model converts various time series tasks—forecasting, imputation, and anomaly detection—into a unified generative task. Timer demonstrates promising capabilities across multiple downstream tasks, advancing the development of LTSMs.
- **Key Contributions**:
  - Develops a unified S3 format to standardize time series data representation.
  - Utilizes large-scale pre-training to improve task generality and scalability.
  - Demonstrates effectiveness in forecasting, imputation, and anomaly detection.
    

### **[TimeGPT-1](https://arxiv.org/abs/2310.03589)**
- **Authors**: Azul Garza, Cristian Challu, Max Mergenthaler-Canseco
- **Abstract**: This paper introduces **TimeGPT**, the first foundational model for time series, capable of generating accurate predictions for datasets not seen during training. TimeGPT excels in zero-shot inference, combining statistical, machine learning, and deep learning methods. The model highlights the utility of large-scale time series models, reducing uncertainty and democratizing access to precise predictions.
- **Key Contributions**:
  - Establishes the first foundation model specifically for time series tasks.
  - Achieves state-of-the-art zero-shot inference performance.
  - Combines insights from multiple domains to enhance generalization.


### **[Advancing Time Series Classification with Multimodal Language Modeling](https://arxiv.org/abs/2403.12371)**
- **Authors**: Mingyue Cheng, Yiheng Chen, Qi Liu, Zhiding Liu, Yucong Luo
- **Abstract**: This paper introduces **InstructTime**, a novel framework that reformulates time series classification as a multimodal learning-to-generate task. It utilizes pre-trained language models to process both task-specific instructions and raw time series as inputs, addressing challenges in transferability and modality representation. Key designs include a time series discretization module, an alignment projection layer, and autoregressive pre-training to enhance cross-domain generalization.
- **Key Contributions**:
  - Introduces a multimodal framework for time series classification.
  - Employs alignment projection layers to address modality gaps.
  - Highlights autoregressive pre-training for cross-domain transferability.


### **[Cross-Domain Pre-training with Language Models for Transferable Time Series Representations](https://arxiv.org/abs/2403.12372)**
- **Authors**: Mingyue Cheng, Xiaoyu Tao, Qi Liu, Hao Zhang, Yiheng Chen, Defu Lian
- **Abstract**: This work proposes **CrossTimeNet**, a cross-domain self-supervised learning (SSL) framework designed to improve time series transferability. The model leverages a novel time series tokenization module to convert raw time series into discrete tokens optimized via reconstruction tasks. CrossTimeNet demonstrates its effectiveness in transferring knowledge across domains and boosting performance on downstream tasks.
- **Key Contributions**:
  - Develops a new tokenization module for cross-domain time series learning.
  - Utilizes pre-trained language models (PLMs) for initialization.
  - Validates performance through extensive real-world experiments.
 
  
---

## 📊 Benchmarks and Datasets

### **[LOTSA: Large-Scale Open Time Series Archive](https://arxiv.org/abs/2402.02592)**
- **Description**: A diverse dataset spanning 27 billion observations across 9 domains, including energy, healthcare, finance, and more.
- **Purpose**: Designed for pre-training large time series models.
- **Key Features**:
  - Multiple frequencies and domains.
  - Unified storage format using Apache Arrow.

### **Monash Time Series Forecasting Archive**
- **Description**: A collection of real-world time series datasets across diverse domains.
- **Link**: [Monash Archive](https://forecastingdata.org/)

XXXXXXX

---

## 🙌 Contributing

This list is a work in progress! Contributions are welcome and encouraged.

To add a new paper:
1. Fork this repository.
2. Add the paper details to the appropriate section.
3. Submit a pull request with a short description of your changes.

---

## 🌟 Acknowledgments

This repository is inspired by the rapid advancements in time series foundation models and aims to promote knowledge sharing within the community.

---

## 📧 Contact

If you have any questions or suggestions, feel free to reach out via [GitHub Issues](https://github.com/your-repo/issues) or email.

---

Happy Forecasting! 🚀

