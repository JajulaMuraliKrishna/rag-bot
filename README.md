RAG Bot: Retrieval-Augmented Generation for Document Summarization

Project Description:
RAG Bot is an automated system built in Python and Colab to extract and summarize content from PDF, Word, and Excel files as per user requirements. It leverages Retrieval-Augmented Generation to intelligently search, analyze, and generate concise summaries from unstructured documents.

Features:
1. Supported Input: PDF, Word (.docx), Excel (.xlsx) documents
2. Document Extraction: Uses Unstructured, pdfplumber, OpenPyXL for file parsing
3. Semantic Search: Vector embeddings via HuggingFace (all-MiniLM-L6-V2)
4. Vector Database: ChromaDB for fast document retrieval
5. Question Answering: HuggingFace Transformers pipeline
6. User Interface: Gradio web app for interactive summary requests
7. Deployment: Colab runtime, shareable via Gradio Live

Tech Stack:
1. Python 3.12
2. LangChain (Community)
3. Unstructured Word Document Loader
4. pdfplumber, OpenPyXL, pandas
5. Sentence-Transformers (HuggingFace)
6. Huggingface Embeddings
7. Recursive Character Text splitter
8. ChromaDB
9. Goolge/flan-t5-large 
10. Gradio UI
11. Colab Notebook

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

