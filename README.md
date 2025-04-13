ResumeMatchAI - Intelligent Resume Screening System
📌 Description:
An intelligent resume screening tool that matches resumes to a job description based on semantic similarity. Built with NLP and machine learning techniques, it uses PDF parsing, text preprocessing, and TF-IDF similarity scoring for efficient and accurate resume classification.

🛠️ Features:
Extract text from PDF resumes using PyMuPDF (fitz).

Preprocess resume and job description text: tokenization, stopwords removal, and lemmatization.

Vectorize text using TF-IDF to measure similarity.

Use cosine similarity to match the best resume to the job description.

Leverages pre-trained models for classification.
🖥️ How to Use:
Place your resume PDFs in the resumes/ folder or provide the path to individual PDF files.

Edit the job_description in the code to reflect your job opening.

Run the script
🔧 Requirements:
nltk

PyMuPDF

scikit-learn

joblib

pandas
