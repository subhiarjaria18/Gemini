# Content Engine

Content Engine is a project designed to answer user prompts related to multiple PDF documents provided by the user. It leverages the power of language models and advanced data retrieval techniques to analyze, compare, and generate insights from PDF documents.

## Features

- Analyze multiple PDF documents.
- Generate insights and answer user queries related to the provided documents.
- Highlight differences and similarities between documents.
- Use advanced language models for natural language understanding and generation.

## Tech Stack

- **Python**: Programming language used for backend logic.
- **Streamlit**: Framework for creating the frontend interface.
- **google-generativeai**: Library for integrating Google Generative AI models.
- **python-dotenv**: Library for managing environment variables.
- **langchain==0.2.6**: Library for managing and utilizing language models.
- **PyPDF2**: Library for PDF manipulation.
- **chromadb**: Vector store for managing embeddings.
- **faiss-cpu**: Library for efficient similarity search and clustering of dense vectors.
- **langchain_google_genai**: Integration of LangChain with Google Generative AI.
- **langchain-community**: Community-supported modules and extensions for LangChain.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/subhiarjaria18/content-engine.git
    cd content-engine
    ```

2. **Create a virtual environment and activate it**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up environment variables**:
    Create a `.env` file in the root directory and add your environment variables:
    ```env
    GOOGLE_API_KEY=your_google_api_key
    ```

## Usage

1. **Run the Streamlit app**:
    ```bash
    streamlit run app.py
    ```

2. **Upload your PDF documents**: Use the provided interface to upload multiple PDF documents.

3. **Ask questions**: Enter your prompts related to the content of the uploaded PDFs and receive answers and insights.


