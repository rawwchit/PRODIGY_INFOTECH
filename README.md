# 🧠 Generative AI Internship Projects – Prodigy InfoTech

This repository contains 4 key Generative AI tasks completed during my internship at **Prodigy InfoTech** (June–July 2025). Each project explores a foundational concept in generative AI using Python, PyTorch, and Hugging Face tools.

---

## 📌 Table of Contents

1. [Text Generation with GPT-2](#1-text-generation-with-gpt-2)
2. [Image Generation with Pre-trained Models](#2-image-generation-with-pre-trained-models)
3. [Text Generation with Markov Chains](#3-text-generation-with-markov-chains)
4. [Neural Style Transfer](#4-neural-style-transfer)
5. [Setup Instructions](#setup-instructions)

---

## 1. 📝 Text Generation with GPT-2

> Generate human-like text using OpenAI’s GPT-2 via the Hugging Face `transformers` library.

- Load the pre-trained GPT-2 model
- Input a prompt, generate coherent text continuation
- Tune generation with temperature, top-k, and top-p sampling

📂 File: https://colab.research.google.com/drive/1r1jfTvZG2K4-OQ6IfTVXAV9q8OKiGFG4?usp=sharing
🔗 Reference: [Hugging Face GPT-2 Docs](https://huggingface.co/gpt2)

---

## 2. 🖼️ Image Generation with Pre-trained Models

> Generate images from text prompts using Stable Diffusion (via Hugging Face `diffusers`).

- Pre-trained model: `CompVis/stable-diffusion-v1-4`
- Input: descriptive prompt like `"A cyberpunk street with neon lights"`
- Output: photo-realistic AI-generated image

📂 File: https://colab.research.google.com/drive/1fCX-sgm9ap3GSOe-xTiRsR1lbLh_9v2X?usp=sharing
🖼️ Example Prompt: `"Flying cars"`

---

## 3. 🔄 Text Generation with Markov Chains

> Create a basic text generator using a statistical Markov chain approach.

- Implemented using Python dictionaries
- Supports word-level bigram or trigram chains
- Generates random sentences based on a source corpus

📂 File: https://colab.research.google.com/drive/1NFclobDoHQitrnqNUXlv9PUXZdg1enk-?usp=sharing
🧠 Sample Corpus: Wikipedia intro, news article, Shakespeare

---

## 4. 🎨 Neural Style Transfer

> Apply the **artistic style** of one image (e.g., a famous painting) to the **content** of another.

- Uses a pre-trained `VGG-19` from `torchvision.models`
- Minimizes content loss + style loss to blend images
- Input: content image + style image → Output: stylized image

📂 File: https://colab.research.google.com/drive/11wBTDNKplERS9Lw03u0DV6ychn6aBZp2?usp=sharing
🎨 Example Style: *Starry Night*, *The Scream*, *The Great Wave*

---

## ⚙️ Setup Instructions

Install all dependencies with:

```bash
pip install torch torchvision diffusers transformers matplotlib accelerate
