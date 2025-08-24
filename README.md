# 🎥 AI Text-to-Video with CogVideoX

This project demonstrates **AI-powered text-to-video generation** using [CogVideoX-2B](https://huggingface.co/THUDM/CogVideoX-2b) from Hugging Face Diffusers.

---

## 🚀 Features
- Generate short videos directly from text prompts
- Runs on **Google Colab** with free GPU (Tesla T4 tested)
- Supports longer videos by stitching 6-second segments

---

## 📽️ Demo

👉 [Watch Demo (12s)](demo.mp4)

---

## 📒 Notebook

Run it on Colab:  

[![Open In Colab](https://colab.research.google.com/drive/1uROrSXSfqxJ8h1x8biD0z9znyrBpUiBl#scrollTo=MD83jDvI2RWD)

---

## 🛠 Tech
- Python, PyTorch  
- Hugging Face Diffusers, Transformers, Accelerate  
- Google Colab  

---

## 💡 Key Learning
Efficiently running large diffusion models on small GPUs (T4) using **CPU offloading** and **segment-based generation**.
