# MoE-Adapters++
Code for paper "[**MoE-Adapters++: Towards More Efficient and Flexible Continual Learning Approaches for Vision-Language Models**]"

## Table of Contents
- [MoE-Adapters++](#moe-adapters)
  - [Table of Contents](#table-of-contents)
  - [Abstract](#abstract)
  - [Approach](#approach)
  - [Install](#install)
  - [Data preparation](#data-preparation)
  - [Model ckpt](#model-ckpt)
  - [MTCL](#mtcl)
    - [Test stage](#test-stage)
    - [Train stage](#train-stage)
  - [Class Incremental Learning](#class-incremental-learning)
    - [Train stage](#train-stage-1)
  - [Citation](#citation)
  - [Acknowledgement](#acknowledgement)


## Install
This repository uses the same implementation as MoE-Adapters4CL
```bash
conda create -n MoE_Adapters4CL python=3.9
conda activate MoE_Adapters4CL
conda install pytorch==2.1.0 torchvision==0.16.0 torchaudio==2.1.0 pytorch-cuda=11.8 -c pytorch -c nvidia
cd cil
pip install -r requirements.txt
```

