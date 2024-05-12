# PaperScribe : RAG-based PDF Chat

PaperScribe is an LLM-powered chatbot designed to assist with reading and understanding PDF documents. It utilizes Streamlit for the user interface, LangChain for text processing, and OpenAI for language model capabilities.

![image](https://github.com/MadhumithaKolkar/PaperScribe_RAG_AI/assets/54811937/89dc9013-9561-46df-bc07-48d4e2553d91)

## About

This application offers the following features:
- **Upload PDF**: Users can upload a PDF document.
- **Text Extraction**: The uploaded PDF is processed to extract text.
- **Text Splitting**: Text is split into smaller chunks for efficient processing.
- **Embeddings**: Text embeddings are generated using OpenAI's embeddings model.
- **Vector Storage**: Embeddings are stored and indexed using FAISS for quick retrieval.
- **Question Answering**: Users can ask questions about the PDF content, and PaperScribe provides relevant answers.
- **Interactive Interface**: The user interacts with PaperScribe through an intuitive web interface powered by Streamlit.

Created by Madhumitha Kolkar, 2024.

## How to Use

1. Upload a PDF document.
2. Ask questions about the content of the PDF.
3. PaperScribe will provide relevant answers based on the text extracted from the PDF.

## Installation

To run PaperScribe locally, follow these steps:

1. Clone the repository:
   >>>https://github.com/MadhumithaKolkar/PaperScribe_RAG_AI.git

3. Install the required dependencies:
- Streamlit
- PyPDF2
- LangChain
- FAISS
- dotenv
- streamlit-extras
- openai

3. Create a .env file with your OPENAI_API_KEY and pass it to your llm instance and OpenAIEmbeddings call.
4. Run the Streamlit app:
>>> streamlit run main.py


