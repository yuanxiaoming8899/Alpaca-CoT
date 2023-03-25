![Alpaca-CoT](https://github.com/PhoebusSi/alpaca-CoT/blob/main/figures/Alpaca-CoT-2.jpg)
# Evolving Alpaca: An Empirical Study on Instruction Tuning for Large Language Models (Alpaca-CoT)

This is the repository for the `Evolving Alpaca` project, which aims to extensively collect instruction-tuning datasets and conduct an in-depth empirical study based on LLaMA model [1].  `Evolving` is used to describe the continuous expansion of our instruction-tuning data collection, which will continuously enhance [Alpaca](https://github.com/tatsu-lab/stanford_alpaca)'s instruction-following capabilities.

You are in a warm welcome to provide us with any non-collected instruction-tuning datasets (or their sources). We will uniformly format them, train Alpaca model (and other LLMs in the early future) with these datasets, open source the model checkpoints, and conduct extensive empirical studies. We hope that our project can make a modest contribution to the open-source process of large language models, and reduce its threshold for NLP researchers to get started.

## Overview

[LLaMA](https://arxiv.org/abs/2302.13971v1) [1] is a great work that demonstrates the amazing zero-shot and few-shot ability. It significantly reduces the cost of training, finetuning, and using competitive large language models, i.e., LLaMA-13B outperforms GPT-3(175B) and LLaMA-65B is competitive to PaLM-540M. Recently, to boost the instruction-following ability of LLaMA, [Stanford Alpaca](https://github.com/tatsu-lab/stanford_alpaca) finetuned LLaMA-7B on 52K instruction-following data generated by the [Self-Instruct](https://arxiv.org/abs/2212.10560) [3] techniques. However, at present, the LLM research community still faces two challenges: 1. Even LLaMA still has high requirements for computing resources, and 2. There are not many open source datasets for instruction finetuning. 

To this end, we propose this project, which leverages various improvements that were subsequently proposed, with the following advantages:
- This repo contains code, modified from [here](https://github.com/tloen/alpaca-lora), which can **_finetune LLaMA cheaply and efficiently_** (without performance degradation compared to [Stanford Alpaca](https://github.com/tatsu-lab/stanford_alpaca)) by using [low-rank adaptation (LoRA)](https://arxiv.org/pdf/2106.09685.pdf) [4], [PEFT](https://github.com/huggingface/peft) and [bitsandbytes](https://github.com/TimDettmers/bitsandbytes). The `7b`, `13b` and `30b` versions of LLaMA models can be easily trained on a single 80G A100. 
- The models published in this repo significantly **_improve the ability to follow Chinese instructions_**, with the help of Chinese instruction datasets published by [BELLE](https://github.com/LianjiaTech/BELLE) [5].
- The models published in this repo significantly **_improve the CoT (reasoning) capability_**, using CoT datasets published by [FLAN]((https://arxiv.org/abs/2210.11416)) [6].
- This repo contains **_a [collection](https://huggingface.co/datasets/QingyiSi/Alpaca-CoT) of instruction-finetuning datasets that are continuously collected_**, which so far includes English, Chinese and CoT instructions. In addition, a collection of checkpoints trained with various instruction datasets is also provided.
- This repo contains **_extensive empirical studies and qualitative analysis_**, which may provide valuable findings and promote the exploration of LLM in the future.




[1]: [LLaMA: Open and Efficient Foundation Language Models](https://arxiv.org/abs/2302.13971v1)

[2]: [Stanford Alpaca: An Instruction-following LLaMA model](https://github.com/tatsu-lab/stanford_alpaca)

[3]: [Self-Instruct: Aligning Language Model with Self Generated Instructions](https://arxiv.org/abs/2212.10560)

[4]: [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/pdf/2106.09685.pdf)

[5]: [BELLE: Bloom-Enhanced Large Language model Engine](https://github.com/LianjiaTech/BELLE)

[6]: [FLAN: Scaling Instruction-Finetuned Language Models](https://arxiv.org/abs/2210.11416)

## Data Collection 
### Statistics
![data collection statistics](https://github.com/PhoebusSi/alpaca-CoT/blob/main/figures/piechart.png)
The current collection of instruction-finetuning datasets consists mainly of three parts:
- `alpaca_data_cleaned.json`: about 52K English instruction-following training samples.
- `belle_data_cn.json`:  about 0.5M Chinese |instruction-following training samples. 
- `CoT_data.json`: 9 CoT datasets involving about 75k samples.

More details on the usage and sources of different datasets can be found [here](https://github.com/PhoebusSi/alpaca-CoT/tree/main/data). 
## Download
You can download all the formatted data [here](https://huggingface.co/datasets/QingyiSi/Alpaca-CoT/tree/main).
## Fomatting
All data in our collection is formatted into the same templates, where each sample is as follows:
```
[
{"instruction": instruction string,
"input": input string, # (may be empty)
"output": output string}
]
```
Note that, for CoT datasets, we first use the [template](https://github.com/google-research/FLAN/blob/main/flan/v2/templates.py) provided by FLAN to change the original dataset into various Chain-of-Thoughts forms, and then convert it to the above format.


## Quantitative Analysis
  3.1 using different instruction data
  3.2 using different sizes of models
  3.3 Comparison with Alpaca and LLaMA


## Instruction Finetuning Based on LLaMA
### Setup

### Training

### Inference

## Citation
Please cite the repo if you use the data collection, code, and experimental findings in this repo. 