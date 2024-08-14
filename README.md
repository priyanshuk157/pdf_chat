# Multiple PDF Chat Application using Groq
  This project is a Streamlit web application that allows users to upload multiple PDF files and ask questions related to the content of those PDF         files. The application leverages Groq, a question-answering model, to provide responses to user questions based on the content of the uploaded PDFs.     Additionally, it utilizes Google's Generative AI for text embeddings and Faiss for vector storage and similarity search.

### Features
  * **Upload PDF Files:** Users can upload multiple PDF files containing textual content.
  * **Ask Questions:** Users can ask questions related to the content of the uploaded PDF files.
  * **Question Answering:** The application utilizes the Groq model to provide answers to user questions based on the uploaded PDFs.
  * **Model Selection:** Users can select from different Groq models for question answering.
  * **Processing Indicator:** During PDF processing, a spinner indicates that the application is processing the uploaded PDFs.
  * **Responsive UI:** The Streamlit interface provides an intuitive and responsive user experience.

### Dependencies
  * Python 3.x
  * Streamlit
  * PyPDF2
  * langchain_groq
  * langchain_community
  * google.generativeai
  * dotenv

### Installation
  1. Clone the repository: `git clone https://github.com/your_username/your_repository.git`
  2. Navigate to the project directory: `cd your_repository`
  3. Install dependencies: `pip install -r requirements.txt`
  4. Set up environment variables:
       * Create a `.env` file in the project directory.
       * Add the following environment variables to the `.env` file:
         * `GROQ_API_KEY=your_groq_api_key`
         * `GOOGLE_API_KEY=your_google_api_key`
         Replace your_groq_api_key and your_google_api_key with your actual API keys for Groq and Google, respectively.
### Usage
  1. Run the Streamlit application: `streamlit run app.py`
  2. Access the application in your web browser at `http://localhost:8501`.
  3. Upload PDF files using the file uploader in the sidebar.
  4. Click on "Submit & Process" to process the uploaded PDF files.
  5. Ask questions related to the content of the PDF files in the provided text input box and click on "Submit" to get answers.
  6. Choose different Groq models from the sidebar for question answering.

