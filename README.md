# Build-an-AI-RAG-Assistant-Using-Lang-Chain
### This project is a Retrieval-Augmented Generation (RAG) application that allows users to upload PDF documents and ask natural language questions. It uses IBM Watsonx Foundation Models for both LLM inference and text embeddings, integrated with LangChain for document ### processing and Gradio for a user-friendly interface.

🔧 Features
📄 Upload any PDF document
❓ Ask questions based on the document content
🤖 Powered by IBM Watsonx LLM (meta-llama/llama-3-70b-instruct)
🔍 Embeddings via ibm/slate-125m-english-rtrvr
🧱 Vector store using ChromaDB
🧠 RetrievalQA chain for intelligent answers
🌐 Gradio interface for easy interaction
🧰 Tech Stack
IBM Watsonx AI SDK
LangChain
Gradio
ChromaDB
Python
🚀 How It Works
Document Loading: PDF is parsed using PyPDFLoader.
Text Splitting: Content is chunked using RecursiveCharacterTextSplitter.
Embedding: Chunks are embedded using Watsonx embedding model.
Vector Store: ChromaDB stores the embeddings.
RetrievalQA: LangChain retrieves relevant chunks and queries the LLM.
Gradio UI: Users interact via a simple web interface.
