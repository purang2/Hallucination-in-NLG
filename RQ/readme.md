
## A List of Research Questions


### Hallucination in Abstractive Summarization

There are 2 categories of hallucination in Abstractive Summarization (AbSum) task. (same as below.)

- **Intrinsic Hallucination** : contradicted from source document.
- **Extrinsic Hallucination (More challenging)** : not mentioned in source document, cannot verified.

![image](https://user-images.githubusercontent.com/46081500/218894853-2f05fe57-8439-4e0f-a7b9-e28be7a2c7d5.png)


### Hallucination Metrics 

> ***🤔How to detect hallucinated contents?***

In AbSum, the main 2 related survey papers ([[Huang et al., 2021]](https://arxiv.org/abs/2104.14839) , [[Ji et al., 2022]](https://arxiv.org/abs/2202.03629)) divide hallucination metrics into two categories like below.

- **Unsupervised Metrics**: IE-based metric, NLI-based metric, QA-based metric.
- **Semi-supervised Metrics**: Semi-supervised metrics are trained on the synthetic data generated from summarization datasets. Trained on these task-specific corpora, models can judge whether the generated summaries are hallucinatory. ***(from [Ji et al., 2022](https://arxiv.org/abs/2202.03629))*** 
