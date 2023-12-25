# Chat with Multiple PDFs

This Streamlit application enables users to interact with multiple PDF documents through a chat interface. The application leverages various NLP (Natural Language Processing) and conversation models to provide a dynamic and interactive experience.

## Files

### `app.py`

This file contains the main application logic using Streamlit. Key functionalities include:

- Uploading multiple PDFs
- Extracting text from PDFs
- Splitting text into chunks
- Creating a vector store for efficient retrieval
- Implementing a conversational chain using language models
- Displaying chat messages in a user-friendly interface

### `htmlTemplates.py`

This file defines HTML templates and CSS for styling the chat messages. It includes templates for both user and bot messages, enhancing the visual appeal of the conversation interface.

### `test.py`

Similar to `app.py`, this file contains the application logic. It is a useful resource for testing and refining the functionality before integrating it into the main application.

## Usage

1. **Upload Documents:**
   - Use the sidebar to upload multiple PDF documents.

2. **Ask Questions:**
   - Enter questions related to the uploaded documents in the text input.

3. **Chat Interface:**
   - The application generates a chat interface displaying user and bot messages.

4. **Processing:**
   - Click the "Process" button to initiate the processing of uploaded documents.

5. **Conversation History:**
   - The application maintains a conversation history, allowing users to see previous interactions.



## How to Run

1. Ensure you have the required dependencies installed. You can install them using:

   ```bash
   pip install streamlit PyPDF2 langchain

2. streamlit run app.py
    ```bash
    streamlit run app.py

    Access the application at http://localhost:8501 in your web browser.
    