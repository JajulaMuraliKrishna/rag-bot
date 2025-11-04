RAG Bot: Retrieval-Augmented Generation for Document Summarization

Project Description:
RAG Bot is an automated system built in Python and Colab to extract and summarize content from PDF, Word, and Excel files as per user requirements. It leverages Retrieval-Augmented Generation to intelligently search, analyze, and generate concise summaries from unstructured documents.

Features:
Supported Input: PDF, Word (.docx), Excel (.xlsx) documents
Document Extraction: Uses Unstructured, pdfplumber, OpenPyXL for file parsing
Semantic Search: Vector embeddings via HuggingFace (all-MiniLM-L6-V2)
Vector Database: ChromaDB for fast document retrieval
Question Answering: HuggingFace Transformers pipeline
User Interface: Gradio web app for interactive summary requests
Deployment: Colab runtime, shareable via Gradio Live

Tech Stack:
Python 3.12
LangChain (Community)
Unstructured Word Document Loader
pdfplumber, OpenPyXL, pandas
Sentence-Transformers (HuggingFace)
Huggingface Embeddings
Recursive Character Text splitter
ChromaDB
Goolge/flan-t5-large 
Gradio UI
Colab Notebook

Installation & Usage:
1. Clone and Install Dependencies
   git clone https://github.com/JajulaMuraliKrishna/rag-bot.git
   cd rag-bot
   pip install -r requirements.txt
2. Run in Colab
   Open rag_bot.ipynb in Colab.
   Ensure dependencies are installed.
   Upload your document (PDF, DOCX, XLSX) per notebook instructions.
   Interact with the Gradio UI to request summaries or answers.
3. Gradio Web Interface
   The notebook launches an interactive Gradio app.
   If running in Colab, a public share link will be provided.

Example Usage:
1. Upload Document
2. Ask a Question or Request a Summary 
3. View Summarized Outputs with Supporting References

