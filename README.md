# Company-Policy-AI-ChatBot
An AI-powered Company Policy Chatbot that answers employee questions from company policy PDF documents using Python, Streamlit, LangChain, FAISS vector search, embeddings, and LLMs. It simplifies policy search through an interactive question-and-answer interface.
# Project Overview
Problem Statement :
Company policies can be long and difficult to search manually. Employees may spend time locating information about rules, procedures, leave policies, and workplace guidelines across PDF documents.
Objective
The goal of this project is to provide a simple question-and-answer interface that helps users find relevant information in authorized company policy documents.
How It Works
If your implementation uses Retrieval-Augmented Generation (RAG), the workflow is generally:
1. Load an authorized policy PDF.
2. Extract text from the document.
3. Split the text into smaller chunks.
4. Convert chunks into vector embeddings.
5. Store and search vectors using FAISS.
6. Retrieve relevant text for a user's question.
7. Pass the retrieved context to the configured language model.
8. Display the generated answer in the application.

02. Features and Advantages :
Features
- Ask questions in natural language about supported policy documents.
- Retrieve relevant passages from indexed documents, if implemented.
- Generate responses using a configured language model, if implemented.
- Provide a user interface using Streamlit, if used in this project.
- Support PDF input, subject to the application's actual file-handling code.
Advantages
- Can reduce the time spent manually searching lengthy documents.
- Makes policy information easier to query in natural language.
- Can help users locate relevant sections of policy documents.
- Can be extended to support additional documents and evaluation workflows.
These are intended benefits, not measured performance claims.

03. Technology Stack:
4. | Technology | Possible role |
|---|---|
Technology	         Possible role
Python	             Application logic
Streamlit          	 Web user interface
LangChain	           Connecting document processing, retrieval, and model components
FAISS	               Vector similarity search
Embedding model	     Representing text as vectors
Ollama	             Running a supported local language model
PDF
processing library	 Extracting text from PDF files

Architecture and Workflow
A typical RAG architecture for this type of application is:

<img width="1068" height="644" alt="image" src="https://github.com/user-attachments/assets/ac897250-2a2b-40f0-9aee-122ef4c41537" />






