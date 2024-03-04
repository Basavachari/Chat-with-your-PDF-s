# ChatAppPDF

ChatAppPDF is a project that allows you to chat with your PDFs. It leverages the Gemini Pro library for PDF manipulation and vectorization, enabling you to retrieve content from PDFs and interact with them in a chat-like interface.

## Features

- Chat with PDFs: Communicate with your PDF documents as if you were having a conversation.
- Gemini Pro Integration: Utilize the powerful features of Gemini Pro for PDF manipulation and vectorization.
- Content Retrieval: Extract specific content from PDFs and retrieve it within the chat interface.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Basavachari/Chat-with-your-PDF-s
    ```
2. Install required dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Create .env file and add the following:

   ```bash
    GOOGLE_API_KEY=your_api_key
    ```
4. Run the code using the following command:

   ```bash
   streamlit run app.py
   ```
## Details 
- This applicaition can handle any no of files (PDF).
- Try to get the content from those files only if the query is not relavent to the files given it will display the ```answer is not available in the context ```.

## Demo
- The application is deployed in the following link : [ChatAppPDF](https://chat-with-your-pdf-s-tlsbgv2tgrdhvutnbzsbep.streamlit.app/)