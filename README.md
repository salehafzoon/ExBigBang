# BigBang
### Title: A Dynamic Approach for Persona Development through Context-Aware, Time-Aware, and Multi-Modal Transformer Analysis

![Python](https://img.shields.io/badge/Python-Compatible-green.svg)
[![Colab](https://img.shields.io/badge/Google%20Colab-Open-orange.svg)]()

## Abstract

In user-centred design and marketing, a persona represents a target customer's characteristics, needs, preferences, and behaviours.
Constructing customer personas enables organizations to offer personalized services that align with their target audience's needs, and pain points, resulting in higher customer satisfaction.
In this regard, earlier works investigated user profiling using machine learning and filtering techniques, along with studies focused on persona development by employing qualitative, quantitative, and automated approaches.
The main research challenge in extracting relevant features from customer activities for persona development lies in the complexity of customer behaviour, contextual understanding, and potential data biases.
To address this challenge, this paper presents a context-aware and time-aware pipeline to construct, enrich, and augment users' profiles through personas developed by transformers. We introduce a dynamic approach, namely BigBang, adaptive to customer behaviour changes, thus addressing the challenge of behavioural variability and the static nature of personas. Context awareness will focus on extracting more meaningful and relevant features by considering factors related to the user's previous interactions. Considering temporal aspects, we capture trends, seasonality, and behavioural changes, vital for accurate and up-to-date personas. Finally, by leveraging a multi-modal transformer, the approach enables deeper insight extraction from customer activities, helping to uncover latent features and behavioural nuances.
We assess the feasibility of the proposed approach by utilizing a real-world dataset and examining cognitive features within the persona, emphasizing its efficacy for comprehensive behavioural analysis.


## Contributions

- Providing a context-aware and time-aware profiling approach using a multi-modality-aware feature extraction technique.
- Introducing a dynamic method for persona development, focusing on the interplay between sophisticated user profiling and multi-modal transformer technology.


## Figures

| ![First Image Description](documents/Model_pipeline.png) | 
|:----------------------------------------------------------:|
| Fig.1 - User data’s odyssey via the BigBang profiling approach.|



| ![First Image Description](documents/Deep_NN_arch.png) | ![Second Image Description](documents/Transformer_arch.png) |
|:----------------------------------------------------------:|:-----------------------------------------------------------:|
| Fig.2 - Deep NN architecture for benchmarking.             | Fig.3 - Transformer architecture for persona development.   |


## Results

| Models                    | Accuracy | Precision | Recall | F-score |
|---------------------------|----------|-----------|--------|---------|
| ML TF-IDF only            | 0.73     | 0.72      | 0.80   | 0.76    |
| ML model multi-modal      | 0.76     | 0.76      | 0.79   | 0.78    |
| Deep NN text-only         | 0.79     | 0.80      | 0.79   | 0.79    |
| Deep NN multi-modal       | 0.80     | 0.80      | 0.82   | 0.81    |
| Transformer text-only     | 0.90     | 0.78      | **0.88** | 0.83    |
| Transformer multi-modal   | **0.91** | **0.80**  | 0.87 | **0.84** |

## Getting Started

#### 1. Clone and Install

```bash
# Clone the repo

git clone https://github.com/salehafzoon/BigBang.git
