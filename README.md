WHO Mental Health Chatbot
Overview
This script creates a chatbot that provides information on mental health plans and programs initiated by the World Health Organization (WHO). The chatbot uses the LangChain library and is powered by the LLaMA3 model.
Dependencies
langchain
PyPDF2
json
langchain.document_loaders
langchain_community.document_loaders
langchain_core.messages
langchain_community.chat_models
langchain_community.document_loaders
Usage
Place the PDF files containing WHO mental health information in the data directory.
Run the script using Python (e.g., python script.py).
The script will prompt you to enter a question about WHO mental health plans and programs.
The chatbot will respond with an answer based on the information extracted from the PDF files.
Note
The script uses the SeleniumURLLoader to load data from WHO websites.
The script uses the UnstructuredPDFLoader to load data from PDF files.
The script uses the ChatOllama model to generate responses to user input.
The script extracts text from PDF files and uses it to train the chatbot.
Output
The script will print the response from the chatbot to the console. The response will be in the form of a text string.
Example
Enter your question to understand the mental health plans and programs initiated by WHO: What are the WHO guidelines for mental health?
Response: The WHO guidelines for mental health include... (extracted text from PDF files)
