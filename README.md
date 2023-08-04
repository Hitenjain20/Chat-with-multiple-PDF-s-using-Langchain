# Chat-with-multiple-PDF-s-using-Langchain

Chat with Multiple PDFs is an innovative application that allows users to interactively chat with multiple PDF documents simultaneously. The application is built using various powerful frameworks and libraries, including Langchain, Huggingface Hub, PyPDF2, python-dotenv, and Streamlit. By leveraging Huggingface embeddings, the application creates embeddings for the text extracted from PDFs using the PyPDF2 module. Faiss-CPU serves as the vector store for storing these embeddings efficiently. To generate answers, the application uses the google/flan-t5-xxl model. Additionally, for the same purpose, GPT4All models and Lamini can also be utilized. Moreover, the application incorporates its own memory mechanism to prevent it from producing hallucinations.


## Features ##


* Chat with Multiple PDFs simultaneously.
* Extract text from the PDF files.
* Generate embeddings using Huggingface embeddings from the text extracted.
* Efficiently store embeddings using Faiss-CPU as a vector store.
* Utilize google/flan-t5-xxl model for answer generation.
* Flexibility to switch between GPT4All models and Lamini for answer generation.
* Incorporated memory mechanism to avoid hallucinations.


## Installations ##


* `pip install langchain`
* `pip install pypdf2`
* `pip install hubggingface_hub`
* `pip install python-dotenv`
* `pip install streamlit`
* `pip install faiss-cpu`

## USAGE ##


Run the Streamlit application:

`streamlit run app.py


* 'Access the application at http://localhost:8501 in your web browser.'
* 'Chat with Multiple PDFs by typing your queries and getting answers from the selected model.'
