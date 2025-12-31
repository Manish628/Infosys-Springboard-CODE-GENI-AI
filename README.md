This project was developed as part of my Infosys Springboard Internship 6.0, where the focus was on building real-world AI applications using Generative AI, Optical Character Recognition (OCR), and interactive web frameworks.

📖 Project Introduction

CodeGen AI is an intelligent, ChatGPT-style web application designed to understand and analyze images, documents, and text files using OCR technology and Large Language Models (LLMs). The system enables users to upload files such as images, PDFs, Word documents, and text files, and automatically extracts meaningful information from them without requiring manual input.

The application integrates:

Ollama for running large language models locally

Streamlit for building an interactive and user-friendly chat interface

OCR (Tesseract) for extracting text from images and scanned documents

This project demonstrates how Generative AI can be combined with OCR to create an intelligent document understanding and code generation assistant.

🎯 Objectives of the Project

To build a ChatGPT-like AI interface using Streamlit

To automatically extract text from images and documents using OCR

To analyze uploaded content without requiring user explanations

To provide AI-generated summaries, explanations, and insights

To run AI models locally using Ollama for privacy and performance

🧠 Why OCR is Used in CodeGen AI

OCR (Optical Character Recognition) is used to convert non-editable content into machine-readable text.

Without OCR:

AI cannot understand images or scanned PDFs

Manual typing is required

Information extraction is slow and error-prone

With OCR:

Text is automatically extracted from images

Scanned documents become searchable

AI can understand handwritten or printed text

Improves automation and user experience

🔄 Step-by-Step OCR Integration in the Project
Step 1: Image or Document Upload

The user uploads:

Image (.png, .jpg)

PDF

Word document

Text file

Step 2: OCR Text Extraction

Images → Processed using pytesseract

PDFs → Parsed using pdfplumber

DOCX → Read using python-docx

OCR converts visual text into digital text.

Step 3: Automatic Content Understanding

Once the file is uploaded:

The extracted text is automatically analyzed

No manual explanation is required from the user

The AI generates information such as:

File summary

Key points

Purpose of the document

Code explanation (if code is detected)

Step 4: AI Processing using Ollama

Extracted content is sent to a local LLM via Ollama

The model understands the context

Generates human-like responses

Step 5: ChatGPT-Style Output

AI response is shown in a chat interface

Output is clear, structured, and easy to understand
