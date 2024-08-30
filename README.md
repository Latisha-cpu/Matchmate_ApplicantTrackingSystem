# Matchmate_ApplicantTrackingSystem
## Overview
Matchmate_ATS is an Applicant Tracking System (ATS) designed to enhance resume evaluation and job description matching using advanced generative AI models. Leveraging the power of Google’s Gemini model, this tool assists in evaluating resumes against job descriptions, providing a detailed match percentage, and identifying missing keywords.

## Features

1)Resume Upload: Supports uploading resumes in PDF or DOCX formats.

2)Job Description Input: Allows users to paste job descriptions for comparison.

3)Text Extraction: Extracts text from uploaded PDF and DOCX files.

4)AI-Powered Matching: Utilizes the Google Gemini model to analyze and match resumes with job descriptions.

5)Result Evaluation: Provides a job description match percentage and highlights missing keywords.

6)User Feedback: Displays recommendations based on the match percentage.


# Installation and usage - 

Follow these steps - 

1)pip install -r requirements.txt

2)Create a .env file in the root directory and add your Google API key:
  GOOGLE_API_KEY=your_google_api_key

# Usage
Run the Streamlit App:
streamlit run app.py

# Upload Resume and Input Job Description:

1)Paste the job description in the provided text area.

2)Upload your resume in PDF or DOCX format.

3)Click on the "Submit" button to process the input.


# Project Structure:

app.py: Main Streamlit application file.

requirements.txt: List of required Python packages.

.env: Configuration file for environment variables.

# Dependencies

streamlit

google-generativeai

python-docx

PyPDF2

python-dotenv
