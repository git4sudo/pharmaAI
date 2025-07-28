# 🧠 Gemma3n-PharmaAI: AI-Powered Virtual Pharmacist

This project is a **multimodal conversational AI assistant** that interprets medicine packaging using Google’s [`gemma-3n-E2B-it`](https://huggingface.co/google/gemma-3n-E2B-it) model. It allows users to upload images of medicine and ask questions like usage, side effects, interactions, etc., through a continuous conversation loop.

---

## 📸 Example Use Case

> Upload a picture of a medicine strip or packaging and ask:
> - “What is this medicine used for?”
> - “What are the possible side effects?”
> - “Can this be taken with ibuprofen?”

---

## 🚀 Features

- Accepts **medicine images** and initiates a smart conversation
- Supports **continuous dialogue** with chat history
- Uses `{"role": ..., "content": ...}` style **chat templating**
- Works with **quantized models** using `bitsandbytes`
- Runs efficiently in **Google Colab**

---

## 🛠️ Setup Instructions

### 🔧 Install Dependencies

```bash
pip install transformers accelerate bitsandbytes torch torchvision
