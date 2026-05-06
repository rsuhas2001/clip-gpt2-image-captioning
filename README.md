# AI Image Captioning Analysis (CLIP + GPT-2)

An image captioning pipeline combining CLIP for vision encoding and GPT-2 for caption generation, evaluated across multiple fine-tuning strategies and decoding methods on 2,500+ images.

## Features
- CLIP + GPT-2 image-to-caption pipeline
- Comparison of full fine-tuning vs. LoRA vs. frozen strategies
- Multiple decoding methods evaluated (greedy, beam search, top-k, top-p)
- LoRA reduced computational requirements by 99% with minimal quality loss

## Tech Stack
Python, PyTorch, Hugging Face Transformers, OpenAI CLIP, GPT-2, PEFT (LoRA)

## Setup
git clone https://github.com/rsuhas2001/clip-gpt2-image-captioning.git
cd clip-gpt2-image-captioning
pip install -r requirements.txt
python train.py
python evaluate.py

## Author
Suhas Ramachandra — MS in Data Analytics Engineering, Northeastern University
