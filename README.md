# IA_Project-
chat with Multiple PDFs Using LLM  This project leverages a Large Language Model (LLM) to enable intelligent interaction with multiple PDF documents. 
# Chat with Multiple PDFs Using LLM  

This project allows users to interact with multiple PDF documents using a Large Language Model (LLM). It simplifies working with large datasets by providing answers to queries, generating summaries, and delivering insights across multiple files.  

## Features  
- **PDF Parsing**: Extracts and processes text from multiple PDF documents.  
- **Query Handling**: Responds to user queries by referencing information across the PDFs.  
- **Summarization**: Generates concise summaries of the document content.  
- **Interactive UI**: Built with Streamlit for an intuitive user experience.  

## Technologies Used  
- **Python**: Backend processing and logic.  
- **Streamlit**: Interactive user interface.  
- **LLM Integration**: (e.g., OpenAI GPT or similar).  

## Installation  

1. **Clone the repository**:  
   ```bash
   git clone https://github.com/
   cd chat_with_pdfs
   
  2. **Set up a virtual environment (optional but recommended):**:

python -m venv venv  
source venv/bin/activate  
# On Windows: venv\Scripts\activate

3. **Install the required dependencies:**:
Install the required dependencies:
pip install -r requirements.txt

4. **Configure your API Key:**:
Obtain an API key from the LLM provider (GEMINI).
Add your API key to a .env file:
GOOGLE_API_KEY=your_api_key_here

6. **Configure your API Key:**:
Run the application:
streamlit run app.py
