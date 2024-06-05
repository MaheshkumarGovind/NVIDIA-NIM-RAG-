# NVIDIA-NIM-RAG-



This Streamlit application demonstrates the use of NVIDIA AI endpoints for document embedding and question answering based on provided documents. The application allows users to embed documents, ask questions, and retrieve answers based on the embedded documents.

## Prerequisites

- Python 3.10  or higher
- `pip` package manager

## Setup

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/nvidia-nim-demo.git
    cd nvidia-nim-demo
    ```

2. **Create a virtual environment:**

    ```sh
    python -m venv venv
    ```

3. **Activate the virtual environment:**

    - **Windows:**
        ```sh
        .\venv\Scripts\activate
        ```
    - **MacOS/Linux:**
        ```sh
        source venv/bin/activate
        ```

4. **Install the required packages:**

    ```sh
    pip install -r requirements.txt
    ```

5. **Create a `.env` file and add your NVIDIA API key:**

    ```env
    NVIDIA_API_KEY=your_api_key_here
    ```

## Usage

1. **Run the Streamlit application:**

    ```sh
    streamlit run finalapp.py
    ```

2. **Embedding Documents:**

    - Place your PDF documents in the `./pdf` directory.
    - Click the "Documents Embedding" button to process the documents and create the vector store.

3. **Ask Questions:**

    - Enter your question in the provided text input box.
    - The application will retrieve the most relevant documents and provide an answer based on the context.

## Application Structure

- `finalapp.py`: Main application script.
- `requirements.txt`: List of required Python packages.
- `./pdf`: Directory to place PDF documents for embedding.

## Example

1. Start the application:
    ```sh
    streamlit run finalapp.py
    ```

2. Upload your PDF documents to the `./pdf` directory.

3. Click the "Documents Embedding" button to create the vector embeddings.

4. Enter a question in the text input box and receive answers based on the embedded documents.

## Contact

For any questions or issues, please contact [your email] or create an issue in the GitHub repository.
