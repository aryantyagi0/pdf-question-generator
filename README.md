# 📘 PDF Visual Question Generator – Internship Assignment

This project was completed as part of an internship assignment. The goal was to build a Python-based tool that extracts content from an educational PDF and uses AI to generate visual questions from the extracted images.

---

## 🎯 Objectives

- Extract **text** and **images** from the provided sample PDF.
- Organize extracted content in a **structured JSON** format.
- Use an **AI model (BLIP)** to generate simple questions based on images.
- Output the AI-generated questions in another JSON file.

---

## 🗂 Project Structure

─ assignment.ipynb 
├── structured_output.json 
├── ai_generated_questions.json
├── pdf_images/ #
├── IMO_SamplePaper.pdf.zip # Original PDF file used for extraction (zipped)
└── README.md #
🚀 How to Run
▶️ In Google Colab:

    Open assignment.ipynb

    Upload the PDF file (or unzip IMO_SamplePaper.pdf.zip)

    Run each cell to extract content and generate questions
    🛠 Technologies Used

    Python 3

    PyMuPDF (fitz)

    Pillow

    Hugging Face Transformers (BLIP)

    Google Colab
