This project is an Applicant Tracking System (ATS) developed using Streamlit, Python, and Gemini LLM. It allows users to upload resumes in PDF format, input job descriptions, and receive detailed analyses of the resumes.

Resume Upload: Accepts resumes in PDF format.
Job Description Input: Allows input of job descriptions to compare against resumes.
Detailed Analysis: Provides a summary of the resume, highlights strengths and weaknesses, and evaluates alignment with the job description.
Percentage Match: Calculates the percentage match between the resume and the job description.
Improvement Tips: Offers suggestions on how to improve the resume or which domains to focus on.

Clone the repository and navigate to the project directory.
Install the required packages using pip install -r requirements.txt.
Set up your Poppler path (required for pdf2image) and update the poppler_path variable in the code.
Configure the Gemini API by signing up for an API key from Google Generative AI and replacing the placeholder with your actual API key.

Run the Streamlit app using streamlit run app.py.
Open the app in your browser and follow the instructions to upload a resume and input a job description.
