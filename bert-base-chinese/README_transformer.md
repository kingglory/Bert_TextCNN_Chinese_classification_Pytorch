---
language: zh
---

# Bert-base-chinese

## Table of Contents
- [Model Details](#model-details)
- [Uses](#uses)
- [Risks, Limitations and Biases](#risks-limitations-and-biases)
- [Training](#training)
- [Evaluation](#evaluation)
- [How to Get Started With the Model](#how-to-get-started-with-the-model)


# Model Details
- **Model Description:**
This model has been pre-trained for Chinese, training and random input masking has been applied independently to word pieces (as in the original BERT paper).

- **Developed by:** HuggingFace team
- **Model Type:** Fill-Mask
- **Language(s):** Chinese
- **License:** [More Information needed]
- **Parent Model:** See the [BERT base uncased model](https://huggingface.co/bert-base-uncased) for more information about the BERT base model.


## Uses

#### Direct Use

This model can be used for masked language modeling 



## Risks, Limitations and Biases
**CONTENT WARNING: Readers should be aware this section contains content that is disturbing, offensive, and can propagate historical and current stereotypes.**

Significant research has explored bias and fairness issues with language models (see, e.g., [Sheng et al. (2021)](https://aclanthology.org/2021.acl-long.330.pdf) and [Bender et al. (2021)](https://dl.acm.org/doi/pdf/10.1145/3442188.3445922)).


## Training

#### Training Procedure
* **type_vocab_size:** 2
* **vocab_size:** 21128
* **num_hidden_layers:** 12

#### Training Data
[More Information Needed]

## Evaluation

#### Results

[More Information Needed]


## How to Get Started With the Model
```python
from transformers import AutoTokenizer, AutoModelForMaskedLM

tokenizer = AutoTokenizer.from_pretrained("bert-base-chinese")

model = AutoModelForMaskedLM.from_pretrained("bert-base-chinese")

```





