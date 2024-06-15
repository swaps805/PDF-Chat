# PDF Chatbot with Streamlit

This project is a Streamlit application that enables users to interactively chat with multiple PDFs using Retrieval-Augmented Generation (RAG) and vector databases.

## Usage
Clone the repository and run '''streamlit run app.py''' 


## How It Works

1. **PDF Loading**: PDFs are parsed and their text content is extracted using `PyPDF2`.
2. **Embedding Generation**: Sentences from the PDFs are converted into embeddings using a pre-trained model (Cohere embeddings).
3. **Vector Storage**: Embeddings are stored in a vector database (Faiss) for efficient retrieval.
4. **Query Processing**: User queries are embedded and compared with stored embeddings to find relevant text.
5. **Answer Generation**: Relevant text is used by a language model to generate contextually accurate responses using Cohere LLM.

![RAG Architechture](./images/RAG_arch.jpg)

#Screenshots of application

![Screenshot 1](./images/ss.png)

