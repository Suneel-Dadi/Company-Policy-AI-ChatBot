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

# Screen Shot Of Company Policy AI Chatbot
<img width="1617" height="820" alt="{5E8C9BB9-C3D8-46CC-922F-D65DA3907AFE}" src="https://github.com/user-attachments/assets/652f26c5-a076-46a8-9dfe-a8e37a38fd10" />

# Road map and Feature Enhancements
04. Mark items as completed only after they have been implemented and tested.
- [ ] Verify PDF extraction and document upload behavior.
- [ ] Show source passages or page references with answers.
- [ ] Build a small evaluation set of questions and expected source passages.
- [ ] Evaluate retrieval quality and answer correctness.
- [ ] Improve handling of missing answers and unsupported questions.
- [ ] Add clear errors for malformed or scanned PDFs.
- [ ] Improve the interface and loading feedback.
- [ ] Deploy the app securely, if deployment is appropriate.
- [ ] Add authentication and access controls if handling confidential documents.
05.  #Results, Limitations and License
Results and Evaluation
Record results only after testing the application. A useful evaluation set can include representative policy questions, the expected supporting passages, and the chatbot's answers.

# Potential measures include:
- Retrieval quality: whether the relevant policy passage appears among retrieved results.
- Answer correctness: whether the answer agrees with the source document.
- Citation accuracy: whether any cited source actually supports the answer.
- Latency: how long retrieval and answer generation take.
Do not publish invented accuracy percentages or performance scores. If evaluation has not been performed, state: Formal evaluation is not yet completed.
# Limitations
- Generated answers may be incomplete or incorrect.
- Output quality depends on PDF text extraction, chunking, retrieval, and the selected model.
- Scanned PDFs may require OCR if the current implementation does not support them.
- A local Ollama setup may require the model to be downloaded and running.
- The chatbot should not replace the original policy document or official HR guidance.

- # Project Demo Live Link :https://drive.google.com/file/d/1e-Nh1rKzEaF963UNZQFpHy6dt9ydG3_6/view?usp=sharing
- 
- ## 💡 Project Idea and Relevance

### 🎯 Project Idea
Organizations maintain important information in company policy documents, including leave policies, employee benefits, attendance rules, workplace guidelines, and IT policies. Employees often need to search through lengthy PDF documents to find answers to specific questions, which can be time-consuming.

The **Company Policy AI Chatbot** aims to simplify this process by allowing users to ask questions in natural language and receive relevant answers based on company policy documents.

### 🌍 Real-World Relevance
This project demonstrates how Artificial Intelligence (AI), Large Language Models (LLMs), and Retrieval-Augmented Generation (RAG) can be applied to real-world workplace information retrieval.

**Key benefits:**
- ⏱️ **Saves Time:** Helps users find relevant policy information without manually searching entire documents.
- 🔎 **Simplifies Information Access:** Makes policy documents easier to query using natural language.
- 🤖 **AI-Powered Interaction:** Provides a conversational interface for asking questions about company policies.
- 🏢 **Workplace Productivity:** Can help employees and HR teams access internal policy information more efficiently.
- 🚀 **Scalable Potential:** Can be extended to support multiple documents, additional policy categories, and more advanced retrieval capabilities.

### 👨‍💻 Learning Outcomes
Through this project, I explored how document processing, semantic search, vector databases, and Large Language Models can work together to build an AI-powered question-answering application.

**Project Goal:** To make company policy information more accessible, searchable, and easier to understand through conversational AI.

- ## 💡 Final Thoughts

This project demonstrates how **Generative AI and Retrieval-Augmented Generation (RAG)** can transform traditional company policy documents into an interactive knowledge assistant. 
By enabling employees to ask questions in natural language and retrieve relevant policy information, the chatbot aims to reduce manual searching, improve accessibility, and support faster decision-making.

**My vision:** Build a smarter, more reliable AI assistant that helps organizations make their internal knowledge accessible, searchable, and easier to understand.

*Built with Python, Generative AI, and a passion for solving real-world problems.* 🚀





