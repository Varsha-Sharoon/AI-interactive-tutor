# AI-interactive-tutor
Overview : 

AI Interactive Study Tutor is a learning assistant built using Generative AI.
It converts uploaded notes or images into simple, conversational explanations, generates quizzes, evaluates student answers, and re-explains misunderstood topics — creating a personalized, interactive learning experience.

Tools and Technologies Used :

Python , Streamlit , Groq API (LLaMA 3.1 models) – Generative AI for explanations and quizzes

Pytesseract + Pillow – OCR (image text extraction)

 Requirements : 

The project requires a few Python libraries to run properly.

The required libraries are: Streamlit, Groq, Pytesseract, and Pillow.

These tools enable the app to create an interactive interface, connect with the Groq API for explanations and quizzes, and extract text from uploaded images.

steps/workflow  : 

Step 1: Designed and developed the project logic in Jupyter Notebook, starting from data extraction, text processing, and prompt creation for AI explanation.

Step 2: Integrated Groq’s LLaMA 3.1 model to generate simplified conversational explanations and automatic quiz questions based on extracted notes.

Step 3: Implemented a feedback system where the AI evaluates student answers and re-explains incorrect responses in simpler terms.

Step 4: Converted the complete notebook into an interactive Streamlit web app, combining OCR, explanation, quiz, feedback, and re-test features in one interface.

Step 5: Validated the end-to-end workflow to ensure smooth interaction between text extraction, AI explanation, and student learning feedback loop.

Results and Conclusions

The app successfully transforms static notes into an interactive learning session.
Students receive clear, beginner-friendly explanations and adaptive quizzes, improving comprehension.
This project demonstrates how Generative AI and OCR can combine to build personalized digital tutors that simplify complex topics effectively.

Future Enhancements

In the future, this AI tutor can be enhanced with voice-based explanations, PDF and handwritten note support, and student progress tracking for personalized learning insights.
Deployment on Streamlit Cloud or Hugging Face Spaces will allow users and recruiters to interact with the app online without local setup.
