# Multimodal Data Processing System

## 🎯 Objective
A system capable of processing multimodal input files (PDF, DOCX, PPTX, TXT, Images, YouTube) and responding to natural language queries using the **Gemini API**.

## 🧠 Features
- 📄 Process text files: PDF, DOCX, PPTX, TXT  
- 🖼 Process images: Extracts text and descriptions  
- 🎥 Process YouTube links: Fetches metadata and summaries  
- 💬 Natural language querying over all uploaded content  
- 💻 Built using **Streamlit**, **Python**, and **Gemini Free API**

## ⚙️ Tech Stack
- Python 3.12  
- Streamlit  
- Gemini 1.5 Flash API  
- yt-dlp, PyPDF2, docx, pptx, Pillow  

## 🚀 How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
