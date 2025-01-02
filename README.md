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
 
### **InstructTime: Advancing Time Series Classification with Multimodal Language Modeling (WSDM2025)**
- **Authors**: Mingyue Cheng, Yiheng Chen, Qi Liu, Zhiding Liu, Yucong Luo
- **Abstract**: This paper introduces **InstructTime**, a novel framework for time series classification by reformulating it as a multimodal learning task. The model leverages pre-trained language models to handle task-specific instructions and raw time series data simultaneously. Key components include a time series discretization module, an alignment projection layer, and autoregressive pre-training to boost transferability and generalization. Extensive experiments show superior performance on benchmark datasets.
- **Key Contributions**:
  - Reformulates time series classification as a learning-to-generate paradigm.
  - Addresses modality representation gaps using alignment projection.
  - Highlights the necessity of autoregressive pre-training for cross-domain tasks.

### **CrossTimeNet: Cross-Domain Pre-training with Language Models for Transferable Time Series Representations (WSDM2025)**
- **Authors**: Mingyue Cheng, Xiaoyu Tao, Qi Liu, Hao Zhang, Yiheng Chen, Defu Lian
- **Abstract**: This paper presents **CrossTimeNet**, a cross-domain self-supervised learning (SSL) framework for time series data. By using a novel time series tokenization module, the model transforms raw time series into discrete tokens optimized through reconstruction. CrossTimeNet demonstrates the ability to transfer knowledge across domains and tasks effectively, showing superior performance in real-world classification scenarios.
- **Key Contributions**:
  - Introduces time series tokenization for cross-domain SSL.
  - Leverages pre-trained language models (PLMs) for initialization.
  - Empirically validates its transferability across diverse domains.
 
  
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

