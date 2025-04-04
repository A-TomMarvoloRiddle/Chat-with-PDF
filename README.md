# PDF Chatbot 📄🤖  

This is a **PDF-based chatbot** built using **Streamlit**, **PyPDF2**, and **Claude Sonnet API**. It enables users to upload **PDF files**, extract text, and ask questions about the content using **Natural Language Processing (NLP) and Machine Learning (ML)**.  

## Features 🚀  

✔ **Upload Multiple PDFs**: Users can upload multiple PDFs to extract text.  
✔ **Text Extraction**: The chatbot reads text from PDFs using PyPDF2.  
✔ **Text Chunking**: Large text is split into smaller, manageable chunks.  
✔ **Vector Store with FAISS**: Stores text chunks efficiently for retrieval.  
✔ **Conversational AI**: Uses **Claude Sonnet API** to process and answer user queries.  
✔ **Interactive UI**: Built with **Streamlit** for an easy-to-use web interface.  

## Technologies Used 🛠  

- **Python** 🐍  
- **Streamlit** (Web UI)  
- **PyPDF2** (PDF text extraction)  
- **FAISS** (Vector store for efficient text retrieval)  
- **LangChain** (NLP & ML framework)  
- **Claude Sonnet API** (AI-based conversation model)  
- **OpenAI & Anthropic APIs** (LLM integration)  

## How It Works 🤖  

1️⃣ **User uploads PDF files** → The chatbot extracts text.  
2️⃣ **Text is split into chunks** → Helps in better query matching.  
3️⃣ **FAISS stores the text** → Creates an efficient vector-based storage.  
4️⃣ **User asks a question** → The bot retrieves relevant text from PDFs.  
5️⃣ **Claude Sonnet API processes the query** → AI generates the response.  
6️⃣ **Answer is displayed** in the chat interface.  

## Usage Instructions 📝  

- Run the chatbot using **Streamlit**.  
- Upload PDFs via the **sidebar menu**.  
- Click **"Submit & Process"** to extract and store text.  
- Ask questions in the input field, and the chatbot will **provide accurate answers**.  

## Screenshots 🖼  
![image](https://github.com/user-attachments/assets/dfa9e926-24ce-4c9d-a3ff-d89109d5d679)
 
