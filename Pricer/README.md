# Product Pricer: LLaMA 3.1 Fine-Tuned Price Prediction from Descriptions

## Overview
This project focuses on building a **Product Pricer**—an AI-based tool that predicts the price of an item based on its description. Using the **LLaMA 3.1-8B model**, fine-tuned with **LoRA (Low-Rank Adaptation)** and **4-bit quantization**, the tool is designed to deliver accurate and efficient price predictions.

The dataset used for training and evaluation is sourced from https://huggingface.co/datasets/McAuley-Lab/Amazon-Reviews-2023 on Hugging Face, providing a wide range of item descriptions and associated prices.

All the steps, from data curation to fine-tuning and evaluation, are implemented inside a **Jupyter Notebook**, making it easy to follow, modify, and experiment with.

---

## Features
- Clean and curate dataset for robust model training.
- Create a custom `items.py` class for handling data and utilities.
- Evaluate baseline performance using the **pre-trained LLaMA 3.1-8B model**.
- Fine-tune the model using **LoRA with 4-bit quantization** for resource-efficient training.
- Evaluate the fine-tuned model and compare results.
- The fine-tuned model demonstrated improved performance over the base model, showcasing more accurate price predictions from item descriptions.

---

## Workflow

### 1. Dataset Curation
We start by curating and cleaning the dataset. This step ensures that the data is free from inconsistencies and ready for fine-tuning.

### 2. Baseline Evaluation with Base Model
Before fine-tuning, we evaluate the **base LLaMA 3.1-8B model** to establish a performance benchmark.  

### 3. Fine-Tuning with LoRA and 4-Bit Quantization
Next, we fine-tune the model using **LoRA and 4-bit quantization**, which makes the process both memory and compute efficient.  

### 4. Evaluation of Fine-Tuned Model
Finally, we evaluate the fine-tuned model on our test set to compare its performance against the baseline.  
The results showed that **our fine-tuned model outperformed the base model**, providing better and more consistent predictions.

---
