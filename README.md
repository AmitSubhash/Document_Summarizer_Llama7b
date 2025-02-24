# Document Summarizer Llama7b

Meet **Document Summarizer Llama7b**—your new best friend for turning dense documents into digestible nuggets of wisdom. Born from a caffeine-fueled, 12-hour hackathon sprint by a dynamic team (Amit, Adith, Saai, and Mithileshan), this tool dives deep into PDFs, images, and Excel sheets with the prowess of a linguistic llama on a mission.

Not only does it summarize your documents with style, but it also comes equipped with a conversational Q&A interface. And with its nifty web extension, you can even chat with websites—making the internet spill its secrets just for you!

## Features

- **Document Processing:**  
  Extracts text from PDFs (using `pypdf`), images (via `pytesseract` and PIL), and Excel files (with `pandas`).

- **Conversational AI:**  
  Summarizes documents and generates key questions using a robust language model (powered by the Groq API and models like `gemma2-9b-it`).

- **Interactive Interface:**  
  Runs on Streamlit, ensuring a smooth and engaging user experience.

- **Web Extension:**  
  Interrogate websites directly to extract and summarize online content.

## Installation Guide

1. Clone repository:
git clone https://github.com/AmitSubhash/Document_Summarizer_Llama7b.git
cd Document_Summarizer_Llama7b

2. Install dependencies:

pip install -r requirements.txt

## Usage

Launch the interface:
streamlit run app.py
Supported operations:
1. Upload document (PDF/image/Excel)
2. Get auto-generated summary
3. Ask follow-up questions via chat

## Development

**Contribution Welcome**  
Open to feature requests, bug reports, and PRs through GitHub issues.

**License**  
Open-source (free for educational/personal use)

**Team**  
Amit Subhash, Adith, Saai, Mithileshan - Luddy Hackathon 2024
