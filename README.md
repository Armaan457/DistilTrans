# Hindi to English Machine Translation Optimization using Fine-Tuning and Knowledge Distillation


Experimental fine-tuning and knowledge distillation for Hindi–English translation models.

## Overview

This project explores two complementary approaches to optimization:

1. **Fine-tuning** (`finetune.ipynb`) — Adapt a pretrained Marian MT model on parallel Hindi–English data for improved translation quality.
2. **Knowledge Distillation** (`distill.ipynb`) — Compress a teacher model into a smaller, faster student while preserving translation performance.

## Key Results

- Fine-tuned models achieve improved BLEU on held-out English→Hindi translation tasks.
- Distilled student models reduce inference latency and footprint while maintaining acceptable BLEU scores.