# Medical LLM Fine-Tuning — Mistral-7B-Instruct with QLoRA

[![HuggingFace Model](https://img.shields.io/badge/🤗-Model-yellow)](https://huggingface.co/labdhu/mistral-7b-medical-qa)
[![W&B Report](https://img.shields.io/badge/W%26B-Training%20Report-orange)](https://wandb.ai/labdhu-toss-solutions/medical-llm-finetune)

## Problem Statement
[TO BE FILLED — three baseline failure patterns]

## Solution Architecture
[TO BE FILLED — diagram and description]

## Results
[TO BE FILLED — before/after comparison table]

## Tech Stack
- Model: mistralai/Mistral-7B-Instruct-v0.2
- Fine-tuning: QLoRA (r=16, alpha=32) via PEFT + TRL
- Dataset: lavita/medical-qa-datasets (8,000 samples)
- Training: Google Colab T4 GPU — 2h 28min
- Tracking: Weights & Biases
- Evaluation: ROUGE + BERTScore + LLM-as-Judge

## Training Results
| Step | Train Loss | Val Loss |
|------|-----------|----------|
| 100  | 1.878     | 1.877    |
| 200  | 1.907     | 1.862    |
| 300  | 1.911     | 1.856    |
| 400  | 1.888     | 1.849    |
| 500  | 1.874     | 1.846    |

## Project Structure
[TO BE FILLED]

## Demo
[TO BE FILLED — Gradio link]
