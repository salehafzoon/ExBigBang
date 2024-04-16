# ExBigBang
### Title: A Dynamic Approach for Explainable Persona Classification through Contextualized Hybrid Transformer Analysis

![Python](https://img.shields.io/badge/Python-Compatible-green.svg)
[![Colab](https://img.shields.io/badge/Google%20Colab-Open-orange.svg)]()

## Abstract
In user-centric design, persona development is crucial for understanding user behaviour, capturing needs, identifying key audience segments, and supporting decision-making. However, the complexity of today's user interactions reinforces the need for a contextualized approach to align designs closely with actual user needs. Previous studies have enhanced persona classification's ability to understand user behaviours; yet, its struggle to capture contextual information by combining textual and tabular data remains a significant challenge. Additionally, these models struggle with explainability, making their interpretability and the justification of their predictions largely unexplored. To address this, in this study, we present ExBigBang (Explainable BigBand), a hybrid (text-tabular) approach that leverages transformers to effectively model contextual features for persona classification. Specifically, ExBigBang integrates a text-tabular transformer model to incorporate contextual information from metadata, domain knowledge and user profiling. Through a cyclical process of user profiling and persona classification, it dynamically ensures a continuously updated reflection of user behaviours. Our experiments validate our model's robustness on a benchmark persona classification dataset. The ablation study highlights the impact of integrating textual and tabular data through our transformer-based model, while our application of Explainable AI (XAI) techniques elucidates the reasons behind its predictions in persona classification.


## Contributions

- Presenting a hybrid contextualization approach for persona development, utilizing a text-tabular transformer classifier.
- Introducing a dynamic framework that focuses on the interplay between user profiling and persona classification, producing a cyclical enhancement process for continuous refinement and relevance.
- Adopting XAI principles to enhance transparency by elucidating impactful factors within persona classification.

## Figures

| ![First Image Description](documents/Model_pipeline.png) | 
|:----------------------------------------------------------:|
| Fig.1 - User data’s odyssey via the BigBang profiling approach.|



| ![First Image Description](documents/Deep_NN_arch.png) | ![Second Image Description](documents/Transformer_arch.png) |
|:----------------------------------------------------------:|:-----------------------------------------------------------:|
| Fig.2 - Deep NN architecture for benchmarking.             | Fig.3 - Transformer architecture for persona development.   |

## Getting Started

#### 1. Clone and Install

```bash
# Clone the repo

git clone https://github.com/salehafzoon/BigBang.git
