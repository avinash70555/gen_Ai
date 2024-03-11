# Generative AI Project
<br>



Natural Language Processing (NLP) Conversational Assistant

As part of my ongoing exploration and application of Natural Language Processing techniques, I developed a powerful and intuitive conversational assistant using Python and Streamlit. This application enables users to engage in dynamic and context-aware conversations with a system that integrates information from multiple PDF documents.

Key Features:

1.Document Processing:

The application allows users to upload multiple PDF documents.
Utilizes the PyPDF2 library to extract text from each page of the uploaded PDFs.
Text Chunking:

Implements a custom text splitter that breaks down large text blocks into manageable chunks, enhancing processing efficiency.
Employs a character-based approach with specified chunk size and overlap.

2.Semantic Embeddings:

Leverages state-of-the-art embeddings from OpenAI for semantic understanding of text chunks.
Integrates with the FAISS vector store for efficient storage and retrieval of semantic information.

3.Conversational Memory:

Implements a Conversation Buffer Memory to retain and recall past interactions.
Utilizes a conversational retrieval chain to enhance the context-awareness of the assistant.

4.User Interface:

Developed a user-friendly interface using Streamlit with a clean and responsive design.
Allows users to input questions related to the uploaded documents.

5.Conversational AI Models:

Supports multiple conversational models, such as OpenAI's Chat model and Hugging Face's transformer models.
Utilizes these models to generate contextually relevant responses.

6.Real-time Interaction:

Facilitates real-time interactions, displaying user and system messages in a visually appealing format.
Enhances user experience through HTML templates and customizable styles.

7.Flexibility and Scalability:

The application supports flexibility by allowing users to choose between different conversational models and embeddings.
Demonstrates scalability by handling multiple PDFs and large text datasets efficiently.


8.Technologies Used:

Python, Streamlit, PyPDF2, OpenAI Embeddings, Hugging Face Transformers, FAISS, dotenv
This project showcases my proficiency in NLP, system integration, and user interface design, highlighting my ability to create innovative solutions for information retrieval and interaction within a conversational context.





