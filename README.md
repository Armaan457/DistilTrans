# DistilTrans

Experimental fine-tuning and knowledge distillation for Hindi–English translation models.

## Overview

This project explores two complementary approaches to optimization:

1. **Fine-tuning** (`finetune.ipynb`) — Adapt a pretrained Marian MT model on parallel Hindi–English data for improved translation quality.
2. **Knowledge Distillation** (`distill.ipynb`) — Compress a teacher model into a smaller, faster student while preserving translation performance.

## Key Results

- Fine-tuning improved English→Hindi translation quality from **23.66 BLEU** to **27.58 BLEU**.
- Knowledge distillation reduced model size by approximately **29%** (**76.38M → 54.31M parameters**).
- The distilled student model retained around **90%** of the teacher model’s translation performance while enabling more efficient deployment.