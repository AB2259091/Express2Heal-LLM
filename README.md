# Express2Heal – Fine-Tuned LLM for Mental Health Support

## 📌 Project Overview
**Express2Heal** is a **fine-tuned Large Language Model (LLM)** designed to assist in **mental health conversations** by generating empathetic, context-aware, and coherent responses.  
The project leverages **state-of-the-art NLP techniques**, **quantization for optimization**, and a **custom-curated dataset** to build a reliable AI-driven mental health assistant.

---

## 🚀 Key Features
- **Fine-Tuned LLaMA & DeepSeek Models** – optimized for **mental health dialogue generation**.
- **Quantized Inference** – faster and memory-efficient deployment using **Unsloth**.
- **Custom Mental Health Dataset** – curated & preprocessed TEI-encoded transcripts.
- **High-Quality Responses** – designed for empathy, safety, and contextual accuracy.
- **FastAPI Backend** – scalable, production-ready REST API.
- **Dockerized Deployment** – portable and easy to integrate with cloud platforms.
- **Hugging Face Space Support** – ready-to-run environment for quick demos.

---

## 🧠 Tech Stack
- **Language Models:** LLaMA, DeepSeek (quantized)
- **Frameworks & Tools:** PyTorch, Hugging Face Transformers, Unsloth
- **Backend:** FastAPI
- **Deployment:** Docker, Hugging Face Spaces
- **Data Processing:** Python, Regex, TEI Parsing
- **Version Control:** Git, GitHub

---

## 📂 Dataset
Our dataset consists of **annotated mental health transcripts**:
- Preprocessed TEI-encoded files  
- Structured into `Patient Expression` and `Psychotherapist Response`  
- Cleaned, normalized (lowercase), and filtered for quality

---

## 🔧 Training Pipeline
1. **Data Preprocessing**: Tokenization, TEI parsing, text normalization.  
2. **Model Selection**: LLaMA and DeepSeek architectures chosen for optimal performance.  
3. **Fine-Tuning**: Supervised fine-tuning on curated dataset.  
4. **Quantization**: Applied using **Unsloth** to reduce model size while maintaining accuracy.  
5. **Evaluation**: Measured perplexity, coherence, and safety metrics.  
6. **Deployment**: Packaged using Docker and served via FastAPI.  
7. **Testing**: Verified performance with real-world mental health dialogues.  

---
