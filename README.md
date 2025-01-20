# 🩺 Medical Chatbot: End-to-End Solution

This project is an AI-powered medical chatbot designed to assist users with general medical inquiries. It integrates cutting-edge technologies, including OpenAI, Pinecone, Hugging Face, and LangChain, to provide accurate, contextual, and human-like responses.

---

## 🚀 Features

- **Conversational AI**: Delivers human-like medical assistance using OpenAI's GPT models.
- **Semantic Search**: Leverages Pinecone for efficient and scalable vector-based search.
- **Custom Embeddings**: Uses Hugging Face models to create domain-specific embeddings.
- **LangChain**: Manages workflows, pipelines, and integrations for seamless interaction between components.
- **End-to-End Workflow**: From user query processing to response generation, ensuring a smooth user experience.

---

## 🛠️ Technologies Used

- **[OpenAI](https://openai.com/)**: GPT models for generating accurate responses.
- **[Pinecone](https://www.pinecone.io/)**: Vector database for fast semantic search and document retrieval.
- **[Hugging Face](https://huggingface.co/)**: Pretrained transformer models for embeddings (e.g., `sentence-transformers`).
- **[LangChain](https://www.langchain.com/)**: Framework for chaining prompts, memory, and APIs.

---

## 📋 Prerequisites

1. Python 3.8 or higher
2. Virtual Environment (e.g., `venv` or `conda`)
3. API keys for:
   - OpenAI
   - Pinecone
4. Install the following dependencies:
   ```bash
   pip install openai langchain pinecone-client[grpc] sentence-transformers flask
