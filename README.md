# Resume-Screening-and-Recommendation
Resume Analyzer & Job Recommendation System
This project is a Flask-based web application that performs intelligent resume parsing and provides job recommendations using machine learning. Users can upload their resumes in PDF or TXT format, and the app will extract useful information and recommend a suitable job role based on the content.

 Features
Upload and parse resumes (PDF/TXT)

Clean and preprocess resume text

Predict resume category using ML

Recommend suitable job roles

Extract:

 Contact Number

 Email

 Name

 Skills

 Education

 Machine Learning Models
Pre-trained Random Forest classifiers are used:

Category Classifier: Predicts job category from resume

Job Recommender: Suggests a job title based on resume content
Both models use TF-IDF Vectorizers for text transformation.

 Libraries & Tools Used
Flask – Web framework

PyPDF2 – PDF parsing

re – Regular expressions for data extraction

pickle – Load ML models

HTML (Jinja templates) – Frontend rendering
