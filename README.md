# Gemini RAG App

This is the Gemini RAG (Retrieval-Augmented Generation) App, which allows users to chat with PDF documents. The app uses Streamlit for the user interface, PyPDF2 for reading PDF files, and Langchain with Google Generative AI for question answering.

## Features

- Upload multiple PDF files.
- Extract text from the uploaded PDF files.
- Split the extracted text into manageable chunks.
- Create a vector store using FAISS and Google Generative AI embeddings.
- Answer user questions based on the content of the uploaded PDF files.

## Installation

To use this application, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/MSimsek07/gemini-rag-app.git
    cd gemini-rag-app
    ```

2. **Create and activate a virtual environment:**

    ```bash
    python3 -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Set up the environment variables:**

    Create a `.env` file in the root directory of the project and add your Google API key:

    ```env
    GOOGLE_API_KEY=your_google_api_key_here
    ```

## Usage

1. **Run the Streamlit app:**

    ```bash
    streamlit run app.py
    ```

2. **Upload PDF files:**

    - Use the sidebar to upload your PDF files.
    - Click on the "Submit & Process" button to process the uploaded PDFs.

3. **Ask questions:**

    - Type your question in the text input field.
    - The app will display the answer based on the content of the uploaded PDFs.

## Contributing

If you want to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [PyPDF2](https://pypi.org/project/PyPDF2/)
- [Langchain](https://langchain.readthedocs.io/)
- [Google Generative AI](https://cloud.google.com/generative-ai)

## Contact

If you have any questions or feedback, please open an issue in the repository or contact the repository owner.

---

Enjoy using the Gemini RAG App! 🚀
