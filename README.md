# 🌉 BridgeGPT

[![License: MIT](https://img.shields.io/badge/Code-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![License: Apache 2.0](https://img.shields.io/badge/Model-Apache%202.0-green.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![Model](https://img.shields.io/badge/Model-BridgeGPT-blue)](https://github.com/guocheng519/BridgeGPT)
[![Paper](https://img.shields.io/badge/Paper-ACL'25-red)](https://aclanthology.org/2025.acl-long.662.pdf)

## 📖 Introduction

**BridgeGPT** is the first domain-specific fine-tuned large language model specialized for bridge engineering. BridgeGPT and its training methodology are presented in **[ACL'25] SDBench: A Survey-based Domain-specific LLM Benchmarking and Optimization Framework**.

📄 **Paper**: [Link to Paper](https://aclanthology.org/2025.acl-long.662.pdf)

## 🚀 Model Access

Download our pre-trained models from the following platforms:

| Platform | Model Link | Description |
|----------|------------|-------------|
| 🤗 **Hugging Face** | [TBD] | TBD |
| 🔧 **ModelScope** | [BridgeGPT-7B-Insturct-v0.1](https://www.modelscope.cn/models/citrus519/BridgeGPT-7B-Instruct-v0.1) | Mirror for faster access in China |

## 🏗️ Applications

We have developed an **Automated Bridge Maintenance LLM Framework** based on BridgeGPT, featuring two main applications:

### 1. 🤖 Data-Knowledge Dual-Driven Intelligent Q&A

![Data-Knowledge Q&A Demo](/BridgeGPT_QA_demo.gif)

Our bridge maintenance LLM seamlessly integrates with knowledge bases and databases to retrieve relevant information and provide contextually accurate answers tailored to real-world scenarios. This dual-driven approach ensures responses are both theoretically sound and practically applicable.

**Key Features:**
- Real-time knowledge base retrieval
- Database query integration
- Context-aware response generation
- Multi-source information synthesis

### 2. 🔍 Bridge Defect Detection & Report Generation

![Defect Detection Demo](/BridgeGPT_M_demo.gif)

We've trained a specialized small model for bridge defect detection using open-source datasets and integrated it into the BridgeGPT workflow. This enables BridgeGPT to automatically perform:

- **Problem Classification**: Automatically categorize different types of bridge defects
- **Data Processing**: Handle and preprocess inspection data
- **Result Analysis**: Provide a comprehensive analysis of detected issues
- **Report Generation**: Generate detailed inspection reports

This integrated solution significantly optimizes bridge maintenance workflows by automating time-consuming manual processes.


## 📚 Citation

If you use BridgeGPT in your research, please cite our paper:

```bibtex
@inproceedings{guo-etal-2025-sdbench,
    title = "{SDB}ench: A Survey-based Domain-specific {LLM} Benchmarking and Optimization Framework",
    author = "Guo, Cheng  and
      Kai, Hu  and
      Liang, Shuxian  and
      Jiang, Yiyang  and
      Gao, Yi  and
      Hua, Xian-Sheng  and
      Dong, Wei",
    editor = "Che, Wanxiang  and
      Nabende, Joyce  and
      Shutova, Ekaterina  and
      Pilehvar, Mohammad Taher",
    booktitle = "Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2025",
    address = "Vienna, Austria",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.acl-long.662/",
    doi = "10.18653/v1/2025.acl-long.662",
    pages = "13492--13506",
    ISBN = "979-8-89176-251-0",
    abstract = "The rapid advancement of large language models (LLMs) in recent years has made it feasible to establish domain-specific LLMs for specialized fields. However, in practical development, acquiring domain-specific knowledge often requires a significant amount of professional expert manpower. Moreover, even when domain-specific data is available, the lack of a unified methodology for benchmark dataset establishment often results in uneven data distribution. This imbalance can lead to an inaccurate assessment of the true model capabilities during the evaluation of domain-specific LLMs. To address these challenges, we introduce **SDBench**, a generic framework for generating evaluation datasets for domain-specific LLMs. This method is also applicable for establishing the LLM instruction datasets. It significantly reduces the reliance on expert manpower while ensuring that the collected data is uniformly distributed. To validate the effectiveness of this framework, we also present the **BridgeBench**, a novel benchmark for bridge engineering knowledge, and the **BridgeGPT**, the first LLM specialized in bridge engineering, which can solve bridge engineering tasks."
}
```


## 📄 License

The code of this project is licensed under the MIT License.
The model file is licensed under the Apache 2.0 License. 
See the [LICENSE](LICENSE) file for details.

## 📧 Contact

For questions and feedback, please reach out to:
- Email: guo.cheng@zju.edu.cn
- Issues: [GitHub Issues](https://github.com/guocheng519/BridgeGPT/issues)

---

<p align="center">
  <b>BridgeGPT</b> - Bridging the gap between AI and infrastructure management 🌉
</p>
