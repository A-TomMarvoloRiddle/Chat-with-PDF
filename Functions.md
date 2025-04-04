# Function Details

### 1. **pdf_read(pdf_doc):** 
&nbsp;&ensp;&ensp; Reads the text from a PDF file using PyPDF2. <br>
&nbsp;&ensp;&ensp; Takes a list of PDF files as input. <br>
&nbsp;&ensp;&ensp; Returns the combined text from all PDF files. <br>

### 2. **get_chunks(text):** 
&nbsp;&ensp;&ensp; Splits the text into smaller chunks using RecursiveCharacterTextSplitter. <br>
&nbsp;&ensp;&ensp; Takes the text as input. <br>
&nbsp;&ensp;&ensp; Returns a list of chunks. <br>

### 3. **vector_store(text_chunks):** 
&nbsp;&ensp;&ensp; Creates a vector store from the text chunks using FAISS. <br>
&nbsp;&ensp;&ensp;Takes the chunks as input. <br>
&nbsp;&ensp;&ensp; Saves the vector store to a local file. <br>

### 4. **get_conversational_chain(tools, ques):** 
&nbsp;&ensp;&ensp; Creates a conversational chain for answering user questions. <br>
&nbsp;&ensp;&ensp; Takes a tool and a question as input. <br>
&nbsp;&ensp;&ensp;Returns the response to the question. <br>

### 5. **user_input(user_question):** 
&nbsp;&ensp;&ensp; Handles user input and provides answers to questions. <br>
&nbsp;&ensp;&ensp;Takes a user question as input. <br>
&nbsp;&ensp;&ensp; Loads the vector store, creates a retriever tool, and calls get_conversational_chain to get the response. <br>

### 6. **main():** 
&nbsp;&ensp;&ensp;The main entry point of the application. <br>
&nbsp;&ensp;&ensp; Sets up the Streamlit application, defines the user interface, and handles user input. <br>
&nbsp;&ensp;&ensp; These functions work together to create a chatbot that can answer user questions based on the content of uploaded PDF files. <br>
