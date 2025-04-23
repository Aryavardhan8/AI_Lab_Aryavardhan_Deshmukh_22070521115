# 🧠 AI-Based Text Summarizer (Case Study – TE7014)

This is a case study project for the Artificial Intelligence Lab (TE7014), where we built an AI-based document summarizer using Natural Language Processing (NLP) techniques. The tool automatically extracts the most important sentences from a .docx file using the TextRank algorithm.

Built with using Python + Streamlit.
<br>



### 📌 Problem Statement

Reading and understanding large documents is time-consuming.
This project solves that by generating concise summaries from uploaded documents — ideal for students, researchers, or professionals.
<br>
<br>
<br>
<br>




### 🎯 Objectives

Build a practical AI application using NLP.
Preprocess text and apply feature extraction.
Use cosine similarity and PageRank to rank sentences.
Create an interactive web app using Streamlit.
Map real-world AI techniques to the lab syllabus.
<br>
<br>
<br>
<br>





### 🧰 Tech Stack
Component            Tool/Library

Programming          Python
NLP                  scikit-learn, re
Similarity           cosine_similarity
Graph Algorithm      networkx (PageRank)
File Handling        python-docx
UI                   Streamlit
<br>
<br>
<br>
<br>




### 🚀 How It Works

Upload a .docx file.
Extracts and cleans the text.
Splits text into sentences.
Vectorizes them using TF-IDF.
Computes sentence similarity using cosine similarity.
Builds a graph and applies TextRank.
Returns top N ranked sentences as a summary.
<br>
<br>
<br>
<br>




### 📸 App UI Preview

Upload interface (accepts .docx)
Displays original text
Displays generated summary
Button to download summary as .txt
<br>
<br>
<br>
<br>





🔍 Example

Input:
Artificial Intelligence is transforming the world. It helps doctors diagnose diseases. AI also powers self-driving cars.
<br>
<br>



Output:
Artificial Intelligence is transforming the world. It helps doctors diagnose diseases.
<br>
<br>
<br>
<br>




🧪 Mapping to Lab Syllabus (TE7014)


Lab Topic	                      This Project Uses
NLP Tools	                      scikit-learn, regex
Preprocessing                  	Sentence tokenization, stop word removal
Feature Extraction	            TF-IDF vectorizer
Similarity Metrics	            Cosine Similarity
AI Algorithm	                  PageRank (TextRank)
Case Study Implementation	      Document Summarizer Web App
<br>
<br>
<br>
<br>




🖥️ How to Run Locally

Clone the repo:
git clone https://github.com/your-username/text-summarizer-case-study.git
cd text-summarizer-case-study
Install requirements:
pip install -r requirements.txt
Run the app:
streamlit run app.py
<br>
<br>
<br>
<br>



📂 File Structure

📁 text-summarizer-case-study
├── app.py                # Streamlit frontend
├── summarizer.py         # TextRank logic
├── sample.docx           # Test file
├── requirements.txt
└── README.md



