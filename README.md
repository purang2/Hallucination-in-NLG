# Hallucinations in abssum
Hallucinations in Abstractive Summarization ***(A Research Internship Project at [@UNIST AIGS](https://sites.google.com/view/language-intelligence-lab))***


> **🤔Can you be sure that Generative AIs (=Language models) generate reliable text / informations?**

> ***What if it doesn't?***



## 📝Brief Information



In the general context outside of NLP, **hallucination is a psychological term referring to a particular type ofperception.** Blom [[14]](https://link.springer.com/book/10.1007/978-1-4419-1223-7) define ***hallucination as “a percept, experienced by a waking individual, in the absence of an appropriate stimulus from the extracorporeal world”.*** Simply put, a hallucination is an unreal perception that feels real.

The undesired phenomenon of *****“NLG models generating unfaithful or nonsensical text”***** shares similar characteristics with such psychological hallucinations – explaining the choice of terminology. Hallucinated text gives the impression of being fluent and natural despite being unfaithful and nonsensical.

It appears to be grounded in the real context provided, although it is actually hard to specify or verify the existence of such contexts. Similar to psychological hallucination, which is hard to tell apart from other “real” perceptions, ***hallucinated text is also hard to capture at first glance.***

***- [Survey of Hallucination in Natural Language Generation (Z. Ji et al., 2022)](https://arxiv.org/pdf/2202.03629.pdf)-***


## Paper List


### #1: Hallucination words ( or tokens ) Filtering & Weighting
- **A Token-level Reference-free Hallucination Detection Benchmark for Free-form Text Generation ( T. Liu et al., ACL 2022 ) | [[Paper (link)]](https://arxiv.org/abs/2104.08704)**
   - they present HADES ( HAllucination DEtection dataSet ) dataset.
- **Controlling hallucinations at word level in data-to-text generation (C. Rebuffel et al., International Journal, 2021) | [[Paper]](https://link.springer.com/article/10.1007/s10618-021-00801-4)**
- Detecting Hallucinated Content in Conditional Neural Sequence Generation (Zhou et al. (Carnegie Mellon Univ & FAIR), ACL-IJCNLP 21) | [[Paper]](https://aclanthology.org/2021.findings-acl.120.pdf)
   -  propose a task to predict whether each token in the output sequence is hallucinated (not contained in the input) 
   -  collect new manually annotated evaluation sets for this task.
   -  introduce a method for learning to detect hallucinations using pretrained language models finetuned on synthetic data that includes automatically inserted hallucinations.
   -  Experiments on **machine translation (MT) and abstractive summarization** demonstrate that our proposed approach consistently outperforms strong baselines on all benchmark datasets.
- Reducing Quantity Hallucinations in Abstractive Summarization (Zhao, Cohen and Webber (Univ of Edinburgh), Findings of EMNLP 20) | [[Paper]](https://arxiv.org/abs/2009.13312)

### #2. Hallucination Similarity Metric
- 

### #3: Cutting-edge Papers of Hallucination Problem (Abs sum or Text Generation)
- On Faithfulness and Factuality in Abstractive Summarization (Maynez et al. (Google Research) ,ACL 20) | [[Paper]](https://aclanthology.org/2020.acl-main.173/)
   - In this paper we have analyzed limitations of these models for abstractive document summarization and found that these models are highly prone to hallucinate content that is unfaithful to the input document.
- Hallucinated but Factual! Inspecting the Factuality of Hallucinations in
    Abstractive Summarization (M.Cao, Dong and Cheung, ACL 22) | [[Paper]](https://aclanthology.org/2022.acl-long.236/)
- **Survey of Hallucination in Natural Language Generation: Section 7 ⇒ ( Abs Sum) (Ji et al., ACM Computing Surveys, Nov 2022)** [[Paper]](https://dl.acm.org/doi/abs/10.1145/3571730)
- Faithful to the Document or to the World? Mitigating Hallucinations via
    Entity-linked Knowledge in Abstractive Summarization (Dong, Wieting and Verga, preprint, Apr 2022) | [[Paper]](https://arxiv.org/abs/2204.13761)
- Retrieval Augmentation Reduces Hallucination in Conversation (Shuster et al. (FAIR), Findings of EMNLP 21)| [[Paper]](https://arxiv.org/abs/2104.07567)
- **TruthfulQA: Measuring How Models Mimic Human Falsehoods (Lin, Hilton and Evans (Univ of Oxford & OpenAI), ACL 22) | [[Paper]](https://arxiv.org/abs/2109.07958)**
