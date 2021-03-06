# BERT-Question-Answering
Answering questions on text documents using Bidirectional Encoder Representations from Transformers (BERT) [1].

## Overview

BERT is among the famous transformer-based deep learning architectures that have made headlines in recent years in NLP. Other notable architectures include the GPT family of models and BART, to name a few. 

A high-level attribute that distinguishes BERT from the GPT (Generative Pre-trained Transformer) class of models is that BERT is bidirectional while GPT is unidirectional. This has important consequences for the downstream tasks at which each architecture excels.
For example, the GPT family excels at generative tasks due to its autoregressive nature, while BERT shows its strength for tasks such as sentence classification. 
 
These transformer architectures for natural language understanding build from the original architecture [2].

![](img/transformer_architecture.png) 

BERT can be understood as borrowing heavily from the encoder portion of that original transformer architecture, while GPT can be understood as tracing its origins to the decoder portion of the original transformer architecture. 

![](img/Bert_Architecture.png) 

Key breakthroughs that have come with the transformer revolution in deep learning include self-supervision, which allows the training phase to leverage large unlabeled datasets for pre-training (see [3] for deeper discussions), 
and self-attention, which facilitates the encoding of long-range dependencies. The wide-spread dissemination of these innovations have driven a new era of scaling in cutting edge deep learning architectures.

![](img/cake.png) 

Yann LeCun's cake analogy from NIPS 2016. 

![](img/param_trend_1.png) 

A now out-of-date graph of the increasing size of cutting-edge deep learning architectures over time from [4].

## References

[1] Devlin, Jacob, Ming-Wei Chang, Kenton Lee, and Kristina Toutanova. "Bert: Pre-training of deep bidirectional transformers for language understanding." arXiv preprint arXiv:1810.04805 (2018).

[2] Vaswani, Ashish, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, ??ukasz Kaiser, and Illia Polosukhin. "Attention is all you need." Advances in neural information processing systems 30 (2017).

[3] Bommasani, Rishi, Drew A. Hudson, Ehsan Adeli, Russ Altman, Simran Arora, Sydney von Arx, Michael S. Bernstein et al. "On the opportunities and risks of foundation models." arXiv preprint arXiv:2108.07258 (2021).

[4] https://developer.nvidia.com/blog/scaling-language-model-training-to-a-trillion-parameters-using-megatron/

