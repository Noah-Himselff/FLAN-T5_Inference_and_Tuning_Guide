# FLAN-T5_Inference_and_Tuning_Guide
A Guide to Generative AI: Harnessing Large Language Models with Transformers and PEFT for NLP Tasks

# FLAN-T5 Experiments and Fine-Tuning Guide

## Overview

This repository provides a comprehensive guide to leveraging generative AI with FLAN-T5 variants for NLP tasks. It includes detailed experiments, fine-tuning techniques using the Transformers library, and parameter-efficient fine-tuning (PEFT) approaches.

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
   - [Basic Experiments](#basic-experiments)
   - [Full Fine-Tuning](#full-fine-tuning)
   - [Parameter-Efficient Fine-Tuning (PEFT)](#parameter-efficient-fine-tuning-peft)
6. [License](#license)

## Introduction

This guide aims to help you harness the power of large language models (LLMs) using FLAN-T5 variants. Through a series of experiments and fine-tuning techniques, you'll learn how to optimize these models for various NLP tasks.

## Installation

To get started, clone the repository and install the required dependencies:

```bash
git clone https://github.com/Noah-Himselff/FLAN-T5_Inference_and_Tuning_Guide.git
cd FLAN-T5_Inference_and_Tuning_Guide
```

Ensure you have access to GPUs for efficient model training and inference.
For the full fine tune notebook (part 2) I used 2 * T4 accelerator and for PEFT (part 3) one T4 or P100 would suffice

## Usage
## Basic Experiments
The first notebook, demonstrates how to call the FLAN-T5 model and basic command lines. It also includes examples of 0-shot to few-shot inference.


## Full Fine-Tuning
In the second notebook, we use the Transformers library to fully fine-tune FLAN-T5-Large on two T4 GPUs. This section covers data preparation, model training, and evaluation on the knkarthick/dialogsum text summary dataset.


## Parameter-Efficient Fine-Tuning (PEFT)
The third notebook, employs the PEFT library for parameter-efficient fine-tuning on FLAN-T5-Large and XL models using a single P100 GPU. This approach reduces computational overhead while maintaining performance.

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/Noah-Himselff/FLAN-T5_Inference_and_Tuning_Guide/blob/main/LICENSE) file for more details.
