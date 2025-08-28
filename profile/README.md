<div align="center">

# AudioLDM with LoRA

### **Enhancing Diffusion-Based Music Generation Performance with LoRA**.

Kim, Seonpyo, Geonhui Kim, Shoki Yagishita, Daewoon Han, Jeonghyeon Im, and Yunsick Sung. 2025. "Enhancing Diffusion-Based Music Generation Performance with LoRA" Applied Sciences 15, no. 15: 8646. https://doi.org/10.3390/app15158646

[![MDPI – Applied Sciences](https://img.shields.io/badge/MDPI-Applied%20Sciences-1D4B8F.svg?style=flat-square)](https://www.mdpi.com/2076-3417/15/15/8646)

<img width="3011" height="1759" alt="image" src="https://github.com/user-attachments/assets/f616c928-10e8-449e-8bf0-2485fd896b17" />

</div>

## Overview

This repository contains code for fine-tuning the Text-to-Audio model, AudioLDM, using the LoRA ([LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685) ) technique, as described in our paper.

---

## Abstract

Recent advancements in generative artificial intelligence have significantly progressed the field of text-to-music generation, enabling users to create music from natural language descriptions. Despite the success of various models, such as MusicLM, MusicGen, and AudioLDM, the current approaches struggle to capture fine-grained genre-specific characteristics, precisely control musical attributes, and handle underrepresented cultural data. This paper introduces a novel, lightweight fine-tuning method for the AudioLDM framework using low-rank adaptation (LoRA). By updating only selected attention and projection layers, the proposed method enables efficient adaptation to musical genres with limited data and computational cost. The proposed method enhances controllability over key musical parameters such as rhythm, emotion, and timbre. At the same time, it maintains the overall quality of music generation. This paper represents the first application of LoRA in AudioLDM, offering a scalable solution for fine-grained, genre-aware music generation and customization. The experimental results demonstrate that the proposed method improves the semantic alignment and statistical similarity compared with the baseline. The contrastive language–audio pretraining score increased by 0.0498, indicating enhanced text-music consistency. The kernel audio distance score decreased by 0.8349, reflecting improved similarity to real music distributions. The mean opinion score ranged from 3.5 to 3.8, confirming the perceptual quality of the generated music.

Keywords: text-to-music generation; Parameter-Efficient Fine-Tuning (PEFT); low-rank adaptation (LoRA)

## Citation

If you find this work useful, please cite our paper:

<div>

Kim, S., Kim, G., Yagishita, S., Han, D., Im, J., & Sung, Y. (2025). Enhancing Diffusion-Based Music Generation Performance with LoRA. Applied Sciences, 15(15), 8646. https://doi.org/10.3390/app15158646

</div>

---
