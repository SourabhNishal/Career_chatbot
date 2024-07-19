# Career_chatbot
Career Chatbot
Introduction
The Career Chatbot project aims to develop a user-friendly chatbot application that assists users in obtaining career-related information. This chatbot is designed to offer guidance and support by interacting with users, extracting valuable insights from career-related documents, and providing relevant responses to their queries.

Purpose of this Project
The primary purpose of this project is to create an intuitive and effective tool that helps users navigate their career-related questions and concerns. By leveraging advanced text extraction, processing, and question-answering technologies, the chatbot provides users with accurate and helpful career advice based on the information available in a PDF document.

Project Scope
The scope of this project includes:

Developing a GUI-based chatbot application using Tkinter.
Extracting and processing text from a career-related PDF document.
Implementing embeddings and similarity search to handle user queries.
Providing an easy-to-use interface for users to interact with the chatbot.
Integrating LangChain for advanced question-answering capabilities.
Overview of the Proposed System
The proposed system consists of a desktop application with the following components:

Text Extraction: Utilizes PyPDF2 to extract text from the provided PDF document.
Text Processing: Splits the extracted text into chunks for efficient indexing and search.
Embedding and Search: Uses OpenAI embeddings and FAISS to index and search text chunks.
Question Answering: Employs LangChain's question-answering model to generate responses to user queries.
User Interface: Provides a Tkinter-based GUI for users to interact with the chatbot, including a chat window, user input field, and a submission button.
Advantages of This Project
User-Friendly Interface: Provides an intuitive and interactive interface for users to get career-related information.
Efficient Text Handling: Handles large amounts of text efficiently through chunking and embedding techniques.
Accurate Responses: Delivers accurate and contextually relevant responses using advanced question-answering models.
Scalability: Can be extended to include more features or integrate additional data sources in the future.
Different Modules and Functionalities of This Project
PDF Text Extraction Module:
Extracts text from PDF pages using PyPDF2.
Text Processing Module:
Splits the extracted text into chunks for easier handling and search.
Embedding and Search Module:
Converts text chunks into embeddings and indexes them using FAISS for similarity search.
Question Answering Module:
Uses LangChain’s question-answering chain to generate responses based on user queries.
User Interface Module:
Provides a Tkinter-based GUI with components for displaying chat history and receiving user input.
Technology Stack
Python: Programming language used for development.
Tkinter: GUI toolkit for creating the desktop application interface.
Pillow: Library for handling image files.
PyPDF2: Library for extracting text from PDF documents.
LangChain: Framework for embeddings and question-answering.
FAISS: Library for efficient similarity search and indexing.
Proposed System
The proposed system will provide a desktop application that allows users to interact with a career-focused chatbot. The system will feature a user-friendly interface where users can enter their queries and receive responses based on the information extracted from a PDF document. The application will be equipped with functionalities for text extraction, processing, embedding, and question answering.

Existing System
Currently, there may be various career guidance tools and chatbots available, but they may lack integration with advanced text processing and question-answering technologies. Existing systems might also be limited in their ability to provide tailored responses based on specific career-related documents. This project aims to bridge these gaps by offering a more personalized and accurate career assistance tool.
