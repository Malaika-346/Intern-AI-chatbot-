# Intern-AI-chatbot-
AI Chatbot to Answer Intern Queries | Built with Hugging Face Transformers &amp; Gradio | Real-time semantic search over FAQs to support interns efficiently | Deployed via Google Colab

# 🤖 AI Chatbot for Intern Support

This project is an AI-powered chatbot designed to answer intern queries and provide real-time support. It uses semantic similarity with sentence-transformers and provides relevant answers based on historical FAQs and support tickets.

## 🔍 Features
- Real-time Q&A chatbot for interns
- Uses semantic search with `MiniLM-L6-v2` from Hugging Face
- Lightweight, fast, and runs directly on Google Colab
- Interactive Gradio interface for user queries

## 🛠️ Tech Stack
- Language Model: `sentence-transformers/MiniLM-L6-v2`
- Interface: `Gradio`
- Libraries: `transformers`, `scikit-learn`, `sentence-transformers`
- Platform: Google Colab

## 📂 Files Included
- `intern_chatbot.ipynb`: Main notebook with code
- `faq_data.json`: Sample FAQ data
- `README.md`: Project documentation

## 💡 How It Works
1. The model encodes all FAQ questions into vector embeddings.
2. User input is converted into an embedding using the same model.
3. Cosine similarity is calculated between user query and all FAQs.
4. The most similar question is returned with its answer.

## 📌 Use Cases
- Intern onboarding support system
- Automated helpdesks
- Education platforms with pre-loaded FAQ support

---

Built with ❤️ using Hugging Face Transformers & Gradio

---

