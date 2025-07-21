# 📄 PDF Question Generator using AI

This project extracts text and images from an educational PDF (Class 1 Maths Olympiad Sample Paper) and uses AI to generate image-based questions. It was built as part of an internship assignment and demonstrates skills in Python, AI/ML, and document processing.

---

## ✅ Features

- 📄 Extracts text and images from PDF files
- 🧠 Uses a pre-trained BLIP model to generate captions for images
- ❓ Automatically generates visual questions from extracted images
- 📦 Outputs structured JSON data for use in educational applications

---

## ▶️ Run the Notebook in Google Colab

Click below to open and run the complete notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aryantyagi0/pdf-question-generator/blob/main/assignment.ipynb)

---

## 📁 Folder Structure

pdf-question-generator/
├── assignment.ipynb # Main Colab notebook
├── ai_generated_questions.json # Output: AI-generated Q&A from images
├── structured_output.json # Extracted text and image paths from PDF
├── pdf_images.zip # Zip file of all extracted images
├── README.md # This file

---

## 🧪 How it Works

1. **PDF Extraction**:
   - Uses `PyMuPDF` to extract text and images page by page.
   - Images are saved into a folder (`pdf_images/`) and referenced in JSON.

2. **Image Captioning**:
   - BLIP (Salesforce) model is used to describe each image using `transformers`.
   - These captions are converted into questions for students.

3. **Question Output**:
   - A final JSON file `ai_generated_questions.json` is created with:
     - The question
     - The image path
     - Optionally: multiple-choice image options (currently blank)

---

## 🔧 Requirements

- Python 3.x
- PyMuPDF
- Pillow
- Transformers
- Torch

All dependencies are installed within the notebook using `pip`.

---

## 📬 Submission Info

- Candidate: Aryan Tyagi  
- Internship Assignment: AI-based PDF Question Generator  
- Submission Format: GitHub repository

