**Real-Time Course Recommender System**

**Overview**

The Real-Time Course Recommender System is a web-based application designed to provide personalized course recommendations based on user inputs such as text, voice, or resume uploads. The system utilizes Natural Language Processing (NLP) techniques, including TF-IDF and RoBERTa, to generate relevant course suggestions. Additionally, it integrates career path insights to help users align their learning with future aspirations.

**Features**

1.User Input Handling: Supports text input, voice input (via Whisper AI), and resume upload (PDF processing with PyMuPDF).
2.Text Preprocessing: Cleans, tokenizes, and lemmatizes text while removing stopwords.
3.**TF-IDF** Keyword Matching: Matches user queries with course descriptions using Term Frequency-Inverse Document Frequency (TF-IDF).
4.**RoBERTa** Semantic Matching: Uses RoBERTa embeddings to compute cosine similarity between user input and course descriptions.
5.Career Path Integration: Links recommended courses to career trends using job market insights.
6.AI-Powered Chatbot: Provides additional guidance and communication for users.
7.Scalability: Utilizes FastAPI, Redis caching, and cloud deployment.


**Installation**

Prerequisites
Ensure you have the following installed:
Python 3.8+
pip
Git

**Clone the Repository**
git clone https://github.com/Devanandini04/Real-Time-Course-Recommender-System.git
cd Real-Time-Course-Recommender-System

**Install Dependencies**
pip install -r requirements.txt

**Usage**
Run the Application
python app.py

**Example Input & Processing**
Text Input: "I am looking for AI and ML courses to enhance my skills."
Voice Input: Convert speech to text using Whisper AI.
Resume Input: Extracts text from uploaded PDFs and processes it for recommendation.

**Contributing**
1.Fork the repository.
2.Create a new branch (git checkout -b feature-branch).
3.Make your changes and commit them (git commit -m 'Add new feature').
4.Push to the branch (git push origin feature-branch).
5.Create a Pull Request.
