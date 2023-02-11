# Hallucinations in abssum
Hallucinations in Abstractive Summarization


## Paper List


### #1: Hallucination words ( or tokens ) Filtering & Weighting
- **A Token-level Reference-free Hallucination Detection Benchmark for Free-form Text Generation ( T. Liu et al., ACL 2022 ) | [[Paper (link)]](https://arxiv.org/abs/2104.08704)**
   - they present HADES ( HAllucination DEtection dataSet ) dataset.
- **Controlling hallucinations at word level in data-to-text generation (C. Rebuffel et al., International Journal, 2021) | [[Paper]](https://link.springer.com/article/10.1007/s10618-021-00801-4)**
- Detecting Hallucinated Content in Conditional Neural Sequence Generation (Zhou et al. (Carnegie Mellon Univ & FAIR), ACL-IJCNLP 21) | [[Paper]](https://aclanthology.org/2021.findings-acl.120.pdf)
   -  propose a task to predict whether each token in the output sequence is hallucinated (not contained in the input) 
   -  collect new manually annotated evaluation sets for this task.
   -  introduce a method for learning to detect hallucinations using pretrained language models finetuned on synthetic data that includes automatically inserted hallucinations.
- Reducing Quantity Hallucinations in Abstractive Summarization (Zhao, Cohen and Webber (Univ of Edinburgh), Findings of EMNLP 20) | [[Paper]](https://arxiv.org/abs/2009.13312)

### #2. Hallucination Similarity Metric
- 

### #3: Cutting-edge Papers of Hallucination Problem (Abs sum or Text Generation)
- On Faithfulness and Factuality in Abstractive Summarization (Maynez et al. (Google Research) ,ACL 20) | [[Paper]](https://aclanthology.org/2020.acl-main.173/)
- Hallucinated but Factual! Inspecting the Factuality of Hallucinations in
    Abstractive Summarization (M.Cao, Dong and Cheung, ACL 22) | [[Paper]](https://aclanthology.org/2022.acl-long.236/)
- **Survey of Hallucination in Natural Language Generation: Section 7 ⇒ ( Abs Sum) (Ji et al., ACM Computing Surveys, Nov 2022)** [[Paper]](https://dl.acm.org/doi/abs/10.1145/3571730)
- Faithful to the Document or to the World? Mitigating Hallucinations via
    Entity-linked Knowledge in Abstractive Summarization (Dong, Wieting and Verga, preprint, Apr 2022) | [[Paper]](https://arxiv.org/abs/2204.13761)
- Retrieval Augmentation Reduces Hallucination in Conversation (Shuster et al. (FAIR), Findings of EMNLP 21)| [[Paper]](https://arxiv.org/abs/2104.07567)
- **TruthfulQA: Measuring How Models Mimic Human Falsehoods (Lin, Hilton and Evans (Univ of Oxford & OpenAI), ACL 22) | [[Paper]](https://arxiv.org/abs/2109.07958)**
