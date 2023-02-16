
## A List of Research Questions


### Hallucination in Abstractive Summarization

> ***🤔What is hallucination & hallucinated contents in Abstractive Summarization?***

There are 2 categories of hallucination in Abstractive Summarization (AbSum) task. (same as below.)

- **Intrinsic Hallucination** : contradicted from source document.
- **Extrinsic Hallucination (More challenging)** : not mentioned in source document, cannot verified.

![image](https://user-images.githubusercontent.com/46081500/218894853-2f05fe57-8439-4e0f-a7b9-e28be7a2c7d5.png)


### Hallucination Metrics 

> ***🤔How to detect hallucinated contents?***

In AbSum, the main 2 related survey papers ([[Huang et al., 2021]](https://arxiv.org/abs/2104.14839) , [[Ji et al., 2022]](https://arxiv.org/abs/2202.03629)) divide hallucination metrics into two categories like below.

- **Unsupervised Metrics**: IE-based metrics, NLI-based metrics, QA-based metrics. => **(🚧TBA)**
  - An Example of IE-based Metric from [Ji et al., 2022](https://arxiv.org/abs/2202.03629): ![image](https://user-images.githubusercontent.com/46081500/219263471-29cd33ca-51f2-48cf-8e7e-c8e4d859af8d.png)

  - An Example of NLI-based Metric (from [SummaC, Laban et al., TACL 2022](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00453/109470/SummaC-Re-Visiting-NLI-based-Models-for)]: ![image](https://user-images.githubusercontent.com/46081500/219264108-55ce27d0-ca0e-4cfa-ae29-1976e875ce5c.png)


> An Example of QA-based Metric => [[FEQA: A Question Answering Evaluation Framework for Faithfulness
Assessment in Abstractive Summarization, ACL 2020]](https://arxiv.org/pdf/2005.03754.pdf)
> ![image](https://user-images.githubusercontent.com/46081500/218945714-4197f87f-350d-4e83-a248-4309826d43bc.png)


- **Semi-supervised Metrics**: Semi-supervised metrics are trained on ***the synthetic data (same as figure) generated from summarization datasets.*** Trained on these task-specific corpora, models can judge whether the generated summaries are hallucinatory. ***(from [Ji et al., 2022](https://arxiv.org/abs/2202.03629))*** 
> ![image](https://user-images.githubusercontent.com/46081500/218901003-69e5c770-e697-43b4-9f6a-a87396776662.png)



### 
