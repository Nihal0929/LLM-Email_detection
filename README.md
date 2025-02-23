# LLM-Email-Detection

This repository contains code for benchmarking large language models for few-shot email spam detection. The project evaluates different baseline techniques and introduces **Spam-T5**, a modified [Flan-T5](https://huggingface.co/google/flan-t5-base) model which significantly outperforms other models.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
## Introduction

This project aims to benchmark various large language models for the task of email spam detection. It includes the implementation of **Spam-T5**, a modified version of Flan-T5, which has shown significant improvements in performance.

## Installation

To install the necessary dependencies, follow these steps:

```bash
git clone https://github.com/Nihal0929/LLM-Email-Detection.git
cd LLM-Email-Detection
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt --extra-index-url https://download.pytorch.org/whl/cu116
```

## Usage

To run the model and evaluate its performance, use the following commands:

```bash
# Example command to run the model
python run_model.py --config configs/spam_t5_config.json
```

