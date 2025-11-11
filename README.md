# 🧠 Text2Vis

## 📘 Project Overview
**Text2Vis** is an advanced **AI-powered text-to-visualization** project that transforms natural language text prompts into **high-quality images**.  
It leverages **Fooocus (a fine-tuned Stable Diffusion model)** along with **Hugging Face Transformers** to generate visually compelling content directly from textual descriptions.

This project demonstrates the power of **Generative AI** — combining **Stable Diffusion** for visual creativity and **NLP models** for prompt understanding.

---

## 🎯 Objective
- Convert **text prompts** into **AI-generated images** with realistic or artistic styles.  
- Integrate **Fooocus** and **Stable Diffusion** for creative image generation.  
- Utilize **Hugging Face models** for text preprocessing, prompt enhancement, and embedding generation.  
- Build a framework for developers to explore **prompt-to-image workflows**.

---

## ⚙️ Technologies Used
| Category | Tools / Libraries |
|-----------|-------------------|
| 🧠 **AI Model** | Fooocus (based on Stable Diffusion) |
| 💬 **NLP** | Hugging Face Transformers |
| 🖼️ **Image Generation** | Diffusers, Torch, PIL |
| 🌐 **Interface** |  Flask  |
| 🧩 **Other Libraries** | `torch`, `diffusers`, `transformers`, `accelerate`, `safetensors`, `PIL`, `requests` |

---

## 🧠 How It Works
1. **Input:** User provides a **text prompt** (e.g., "A futuristic city skyline at sunset").  
2. **Preprocessing:** The text is enhanced using a **Hugging Face language model** (e.g., GPT or T5).  
3. **Generation:** The refined prompt is passed to the **Fooocus Stable Diffusion pipeline**.  
4. **Output:** The model generates a **high-resolution image** that visually represents the input text. 

---

## 🖼️ Example Results

| Input Prompt | Generated Output |
|---------------|------------------|
| "A serene forest with glowing mushrooms" | 🖼️ Realistic AI-generated forest scene |
| "A cyberpunk city at night with neon lights" | 🖼️ High-quality futuristic artwork |
| "A portrait of an astronaut exploring Mars" | 🖼️ Stylized digital painting |
