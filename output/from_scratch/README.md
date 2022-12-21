---
tags:
- generated_from_trainer
model-index:
- name: from_scratch
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# from_scratch

This model is a fine-tuned version of [](https://huggingface.co/) on the None dataset.
It achieves the following results on the evaluation set:
- Loss: 1.9846

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 0.0001
- train_batch_size: 3
- eval_batch_size: 2
- seed: 42
- gradient_accumulation_steps: 64
- total_train_batch_size: 192
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-06
- lr_scheduler_type: linear
- lr_scheduler_warmup_steps: 10000
- num_epochs: 20.0

### Training results



### Framework versions

- Transformers 4.12.5
- Pytorch 1.8.1+cu111
- Datasets 2.5.2
- Tokenizers 0.10.3
