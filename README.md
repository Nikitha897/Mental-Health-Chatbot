# 🧠 AI-Powered Mental Health Chatbot (Generative AI + ML)

An **AI-driven mental health support chatbot** designed to provide empathetic, context-aware conversations using **Large Language Models (LLMs)** combined with **Retrieval-Augmented Generation (RAG)**. This project focuses on **emotional support, stress relief, and mental well-being guidance** while maintaining ethical AI practices and user privacy.

> ⚠️ **Disclaimer**: This chatbot is **not a medical professional** and does not provide diagnoses or treatment. It is intended only for mental health support and self-help guidance.

---

## 🚀 Features

* 🤖 Therapist-style empathetic conversations
* 📚 Retrieval-Augmented Generation (RAG) for factual grounding
* 🔍 Semantic search over mental health resources
* 🔐 Privacy-focused (runs locally, no user data stored)
* 🧘 Coping strategies for stress, anxiety, and emotional regulation
* 🗣️ Natural, human-like responses using LLMs

---

## 🏗️ System Architecture

```
User Input
   ↓
SentenceTransformer (Embeddings)
   ↓
FAISS Vector Database (Semantic Search)
   ↓
Large Language Model (Mistral 7B / LLaMA)
   ↓
Prompt Engineering + Safety Guardrails
   ↓
Empathetic AI Response
```

---

## 🧠 AI / ML Models Used

### 🔹 Large Language Model (LLM)

* **Mistral 7B (GGUF)**
  *(Alternative: LLaMA 2 / LLaMA 3)*

**Why?**

* Strong natural language understanding
* Generates empathetic, therapist-style responses
* Efficient and open-source
* Suitable for local and academic use

---

### 🔹 Embedding Model

* **SentenceTransformers – `all-MiniLM-L6-v2`**

**Purpose:**

* Converts user queries into semantic vectors
* Enables contextual similarity search

---

### 🔹 Vector Database

* **FAISS (Facebook AI Similarity Search)**

**Purpose:**

* Fast and efficient semantic retrieval
* Grounds responses using mental health knowledge

---

## 🧩 Key Concepts Used

* **Generative AI** – Human-like text generation
* **Retrieval-Augmented Generation (RAG)** – Reduces hallucinations
* **Prompt Engineering** – Ethical and safe responses
* **Natural Language Processing (NLP)**
* **Semantic Search & Vector Embeddings**

---

## 🛡️ Ethical AI & Safety

* No medical diagnosis or prescriptions
* Crisis disclaimers included
* Focus on grounding exercises and emotional validation
* Encourages professional help when required

---

## 🛠️ Tech Stack

* **Python**
* **Mistral 7B / LLaMA**
* **FAISS**
* **SentenceTransformers**
* **ctransformers**
* **Google Colab / Local Inference**

---

## 📌 Use Cases

* Stress and anxiety support
* Emotional check-ins
* Mental health awareness tools
* AI-driven wellness applications

---

## 📈 Future Enhancements

* Emotion detection using BERT-based models
* Voice-based interaction
* Multilingual support
* Mobile & web interface (React)

---

## 👩‍💻 Author

**Nikitha Joseph**
Aspiring Data Scientist | Generative AI Enthusiast

---

## ⭐ If you find this project useful

Give it a ⭐ on GitHub and feel free to contribute or fork!
