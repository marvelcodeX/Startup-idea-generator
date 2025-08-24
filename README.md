# Startup Idea Generator

This project is an **AI-powered startup idea generator** built with [Transformers](https://huggingface.co/transformers/) and [Gradio](https://www.gradio.app/).  
It uses the **LaMini-Flan-T5 (783M)** model to generate structured startup pitches from a given domain.

---

## 🚀 Features
- Input any **domain/industry keyword** (e.g., AgriTech, FinTech, EdTech).
- Generates a startup pitch with:
  1. **Business Idea** (2–3 sentences)  
  2. **Problem Statement** (challenge in the industry)  
  3. **Solution** (how the startup solves it)  
- Web-based UI powered by **Gradio**.
- Can be shared via a public Gradio link.

---

## 📦 Installation

Install dependencies:
```bash
pip install transformers gradio torch accelerate
