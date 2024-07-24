---
title: CustomizedLLMApp
emoji: 💬
colorFrom: yellow
colorTo: purple
sdk: gradio
sdk_version: 4.36.1
app_file: app.py
pinned: false
---

An example chatbot using [Gradio](https://gradio.app), [`huggingface_hub`](https://huggingface.co/docs/huggingface_hub/v0.22.2/en/index), and the [Hugging Face Inference API](https://huggingface.co/docs/api-inference/index).
This code creates an interactive chat application using Gradio and the HuggingFace Inference API. It integrates a PDF document processing and search system to provide context-aware responses. The MyApp class loads and processes text from a PDF, builds a vector database using SentenceTransformers and FAISS, and enables searching for relevant document excerpts based on a query. The respond function retrieves relevant document sections to provide contextual responses to user inputs, enhancing the chat interface. The Gradio interface, configured with example queries and a title, launches the app to answer questions related to Canadian tourism.
