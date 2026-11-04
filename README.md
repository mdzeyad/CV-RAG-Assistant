# CV RAG Assistant – AI-Powered Resume Search

This project is a simple AI-based CV Search Assistant that helps recruiters find candidates based on skills and information mentioned in their CVs.

### Project Features
- Extracts text from PDF and DOCX CV files.
- Supports multiple CV documents.
- Splits CV text into smaller chunks.
- Generates text embeddings using Sentence Transformers.
- Uses FAISS for semantic similarity search.
- Searches candidate skills and displays supporting evidence.
- Provides a simple web interface using Gradio.

### Technologies Used
- Python
- Google Colab
- Sentence Transformers
- FAISS
- Hugging Face Transformers (FLAN-T5)
- Gradio
- PyPDF
- Python-docx

### Example Query
**Question:** Which candidates have Python experience?

**Result:**
- CV10077.pdf – Python Programming.
- CV16264.pdf – Python listed under Programming Languages.

### Project Objective
To make CV screening easier by allowing recruiters to search candidate profiles and identify relevant skills with supporting evidence.

### Note
This is a prototype developed for learning and demonstrating document retrieval and AI-assisted CV search. Search results should be verified against the original CVs.
