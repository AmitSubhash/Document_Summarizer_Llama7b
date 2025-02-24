Meet Document Summarizer Llama7b—your new best friend for turning dense documents into digestible nuggets of wisdom. Born from a caffeine-fueled, 12-hour hackathon sprint by a dynamic team (Amit, Adith, Saai, and Mithileshan), this tool dives deep into PDFs, images, and Excel sheets with the prowess of a linguistic llama on a mission.

Not only does it summarize your documents with style, but it also comes equipped with a conversational Q&A interface. And with its nifty web extension, you can even chat with websites—making the internet spill its secrets just for you!

Features

Document Processing:
Extracts text from PDFs (using pypdf), images (via pytesseract and PIL), and Excel files (with pandas).
Conversational AI:
Summarizes documents and generates key questions using a robust language model (powered by the Groq API and models like gemma2-9b-it).
Interactive Interface:
Runs on Streamlit, ensuring a smooth and engaging user experience.
Web Extension:
Interrogate websites directly to extract and summarize online content.
Installation

Clone the repository and install the required packages:

git clone https://github.com/AmitSubhash/Document_Summarizer_Llama7b.git
cd Document_Summarizer_Llama7b
pip install -r requirements.txt
Usage

Launch the Streamlit app:

streamlit run app.py
Then, upload your document and let our quirky Llama7b transform your text into an insightful summary with a side of thought-provoking questions.

Contributing

We love quirky ideas and innovative approaches! If you have suggestions, spot a bug, or want to contribute new features, please open an issue or submit a pull request.

License

This project is open source and free to use for educational and personal projects.

Acknowledgements

A huge shout-out to our brilliant team—Amit, Adith, Saai, and Mithileshan—for bringing this project to life in a wild 12-hour hackathon sprint. Cheers to the hackathon spirit and to building tools that make information fun and accessible!
