# RAG-Documents-Question-and-answering

Retrieval-Augmented Generation (RAG) for Document Question and Answering (Q&A) | Python
•Document Q & A system built on LLM models via the Groq API Key to retrieve answers from the database
•PyPDFDirectoryLoader is used for document ingestion and RecursiveCharacterTextSplitter segments documents into chunks for embedding and retrieval
•OllamaEmbeddings model is used to create embeddings and InMemoryVectorStore is leveraged to store and retrieve the embeddings
•Create a retrieval chain and develop a Streamlit app interface that allows users to input queries
