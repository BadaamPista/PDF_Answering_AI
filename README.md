                          PDF_Answering_AI

**Project Overview**

PDF Answering AI" generally refers to artificial intelligence technology that can process and respond to queries based on the content of PDF documents. Here’s a brief overview:
Document Understanding: AI-powered systems are trained to read and comprehend the contents of PDF files
Query Processing: Users can input questions or search queries related to the content within the PDF documents.
"""Based on the analysis of the PDF content, the AI generates responses that directly answer the user's questions or provide relevant information."""

**Setup Guide**

Certainly! Here's a clear set of instructions on how to run a project locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/BadaamPista/PDF_Answering_AI
   cd PDF_Answering_AI

   ```

2. **Setup environment variables (optional but recommended):**

   ```bash
   python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

   ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt

   ```

4. **Run the Flask application:**

   ```bash
   python app.py

   ```

5. **Open your web browser and go to:**

   ```
   http://127.0.0.1:5000/

6. **Upload your PDF file & begin asking questions!**

 Further Instructions(How to Run)
- Once the application is up and running and you have uploaded a PDF file:

- Navigate to the home page at http://127.0.0.1:5000/.

- Upload a PDF file on clicking the Upload Button.

- After uploading the PDF, you can enter a question related to its content in the provided question form.

- Click the "Ask" button to receive an answer based on the content of the PDF.

**Dependencies**

PyMuPDF2
transformers
Flask==3.0.3
keras==3.3.3
numpy==1.26.4
pandas==2.2.2
PyMuPDF==1.24.5
PyMuPDFb==1.24.3
requests==2.32.3
huggingface-hub==0.14.1
sentence-transformers==2.2.2

