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

## **Monash Time Series Forecasting Archive**

- **Description**  
  The Monash Time Series Forecasting Archive provides a comprehensive collection of real-world time series datasets. Covering domains such as finance, tourism, healthcare, and more, it features a range of frequencies (annual, monthly, weekly, daily, sub-daily) and an extensive variety of time series lengths. By unifying multiple benchmark datasets into a single repository, the archive enables transparent and reproducible forecasting research.

- **Purpose**  
  Designed to facilitate rigorous evaluation and benchmarking, the Monash Archive offers researchers and practitioners a **standardized** environment to **develop, compare, and refine** forecasting models. Its wide coverage of frequencies and domains helps assess model robustness and generalization.

- **Key Features**  
  - **Diverse Domains**: Finance, economics, energy, tourism, and more, reflecting real-world forecasting challenges.  
  - **Multiple Frequencies**: Annual, monthly, weekly, daily, and sub-daily observations for different forecast horizons.  
  - **Rich Benchmarking Environment**: Aggregates well-known datasets (e.g., M1, M3, M4, tourism) under a consistent format, streamlining model comparison.  
  - **Open Access & Reproducibility**: Publicly available with standardized metadata and documentation, ensuring transparent experimentation.  
  - **Community-Driven Updates**: Continually expanded with new datasets and usage examples contributed by the forecasting community.

> **More Information**  
> - **Official Website**: [https://forecastingdata.org/](https://forecastingdata.org/)  
> - **Reference Paper**: [Hyndman et al., 2021](https://robjhyndman.com/papers/Monash_Forecasting_Archive.pdf)  


### **GIFT-Eval: A Benchmark for General Time Series Forecasting Model Evaluation**

- **Description**  
  Spanning 23 datasets, over 144,000 time series, and 177 million data points, GIFT-Eval covers 7 domains and 10 frequencies, ranging from short- to long-term forecasts. Additionally, it provides a non-leaking pretraining dataset of approximately 230 billion data points, specifically designed for large-scale foundation models in time series.

- **Purpose**  
  Designed to evaluate deep learning, statistical, and foundation models under a **unified and diverse** setting, aiming to assess their **zero-shot** forecasting capabilities and generalization performance.

- **Key Features**  
  - **Extensive Data Coverage**: Encompasses 7 domains (e.g., finance, energy, traffic) with various time frequencies and multivariate input structures.  
  - **Comprehensive Benchmarks**: Includes **17 baselines** (statistical, deep learning, and foundation models) for performance comparisons across different algorithmic paradigms.  
  - **Non-Leaking Pretraining Data**: Around **230 billion** data points, enabling fair and large-scale model pretraining.  
  - **Open-Source Code & Leaderboard**: Facilitates reproducibility and competitive benchmarking.  
  - **Multi-Task Evaluation**: Covers short-, medium-, and long-term forecast horizons, evaluating models in **zero-shot** scenarios for both univariate and multivariate tasks.

> **More Information**  
> - **Paper**: [arXiv:2410.10932](https://arxiv.org/abs/2410.10932)  
> - **Project**: [https://github.com/SalesforceAIResearch/gift-eval](https://github.com/SalesforceAIResearch/gift-eval)

### **Context is Key (CiK): A Benchmark for Forecasting with Essential Textual Information**

- **Description**  
  “Context is Key” (CiK) provides a novel time series forecasting benchmark that pairs numerical data with **carefully crafted textual context**. By requiring models to integrate **multiple modalities**—including structured time series and unstructured natural language—CiK addresses the gap where traditional forecasting often ignores **human-generated** background knowledge or constraints. 

- **Purpose**  
  CiK aims to evaluate how effectively statistical models, foundation models, and especially **LLM-based** forecasters can incorporate contextual information to produce **more accurate** and **context-aware** predictions. It emphasizes the **textual nuances** that human forecasters often rely upon but which many models overlook.

- **Key Features**  
  - **Multimodal Data**: Combines **time series** with **diverse textual context** to capture real-world forecasting scenarios where domain knowledge and constraints are crucial.  
  - **Wide Range of Methods**: Benchmarks **statistical**, **time series foundation**, and **LLM-based** models, offering a comprehensive view of how different paradigms handle context.  
  - **Simple Yet Effective Prompting**: Introduces a **prompt-based** approach that notably boosts forecasting performance, highlighting **LLMs’ capability** to leverage additional textual cues.  
  - **Critical Insights**: Uncovers **strengths** and **limitations** of LLM-based forecasting methods, guiding future research in **multimodal forecasting**.  
  - **Accessible Visualizations**: The benchmark can be visualized at [this link](https://arxiv.org/abs/2410.18959), facilitating a clearer understanding of **context integration**.

> **More Information**  
> - **Paper**: [arXiv:2410.18959](https://arxiv.org/abs/2410.18959)  
> - **Authors**: Andrew Robert Williams, Arjun Ashok, Étienne Marcotte, Valentina Zanetdeschi, Jithendaraa Subramanian, Roland Riachi, James Requeima, Alexandre Lacoste, Irina Rish, Nicolas Chapados, Alexandre Drouin  
> - **Submission**: 24 Oct 2024  
> - **Comments**: Preprint; first two authors contributed equally

## **Time-MMD: Multi-Domain Multimodal Dataset for Time Series Analysis**

- **Description**  
  Time-MMD is the first **multi-domain, multimodal time series dataset**, spanning 9 primary data domains. It ensures **fine-grained modality alignment**, eliminates data contamination, and provides **high usability** for real-world time series analysis (TSA). This benchmark is designed to integrate numerical series data with **domain-specific textual knowledge**, unlocking the untapped potential of textual data in enhancing forecasting tasks.

- **Purpose**  
  Time-MMD addresses the limitations of existing time series models that rely solely on numerical data. By seamlessly combining numerical and textual modalities, it enables **in-depth multimodal evaluations** and promotes advancements in multimodal TSA models. Additionally, the accompanying library **MM-TSFLib** facilitates the seamless use of the dataset for benchmarking and model development.

- **Key Features**  
  - **Multi-Domain Coverage**: Includes 9 domains with diverse real-world applications, ensuring broad utility.  
  - **Multimodal Alignment**: Provides structured numerical data alongside rich textual context, enabling models to leverage domain-specific knowledge.  
  - **Benchmarking Library**: Features **MM-TSFLib**, the first multimodal time series forecasting library for streamlined analysis.  
  - **Significant Performance Gains**: Demonstrates up to **15% error reduction** on average and up to **40% reduction** in domains rich with textual data when transitioning from unimodal to multimodal approaches.  
  - **Open Access Resources**: The dataset and library are publicly available to revolutionize TSA applications and research.

> **More Information**  
> - **Paper**: [arXiv:2406.08627](https://arxiv.org/abs/2406.08627)  
> - **Authors**: Haoxin Liu, Shangqing Xu, Zhiyuan Zhao, Lingkai Kong, Harshavardhan Kamarthi, Aditya B. Sasanur, Megha Sharma, Jiaming Cui, Qingsong Wen, Chao Zhang, B. Aditya Prakash  



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

