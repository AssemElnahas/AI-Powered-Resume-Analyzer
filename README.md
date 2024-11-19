AI-Powered ATS Resume Analyzer

An interactive web application built with Streamlit and NLP capabilities using spaCy, designed to analyze resumes for ATS (Applicant Tracking System) suitability. This tool predicts job-related keywords, checks for ATS-friendly structure, and provides essential resume insights.

Features

- File Upload: Supports .docx and .pdf formats for resume uploads.
- Text Extraction: Extracts text content from uploaded resumes.
- Keyword Prediction: Automatically predicts job-related keywords based on the most common words in the resume.
- ATS Suitability Analysis:
  - Detects job-related keywords present in the resume.
  - Checks for an ATS-friendly structure (e.g., simple formatting, minimal use of unconventional symbols).
  - Provides statistics like total keywords matched, total words, and overall ATS friendliness.
- Interactive UI: Built using Streamlit for user-friendly interaction and easy deployment.

Getting Started

Prerequisites

Make sure you have Python installed along with the following packages:

- `streamlit`
- `spacy`
- `pandas`
- `docx` (installed as `python-docx`)
- `pdfplumber`

You can install the required packages using:
