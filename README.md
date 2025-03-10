Name: Bayana Sravya Sindhu<br/>
AI Resume Screening & Candidate Ranking System<br/>
<b>Overview</b><br/>
This project is an AI-driven Resume Screening & Candidate Ranking System developed using Streamlit, PyPDF2, and Scikit-learn. The system analyzes resumes and ranks them based on their relevance to a given job description using TF-IDF vectorization and cosine similarity.</br>

<b>Key Features:</b><br/>
✔️ Job Description Input: Users can enter a job description as a reference.
✔️ Bulk Resume Upload: Supports uploading multiple resumes in PDF format.
✔️ Automated Text Extraction: Extracts text from resumes for analysis.
✔️ Intelligent Ranking: Uses AI to rank resumes based on relevance.
✔️ User-Friendly Display: Shows ranked results in a descending order of relevance.

Installation
Prerequisites:
Ensure Python is installed on your system. Then, install the required dependencies using:

  pip install streamlit PyPDF2 scikit-learn pandas
How to Use:
Run the application with the command:

  streamlit run app.py
Enter the job description in the provided input box.
Upload PDF resumes to be analyzed.
The system will extract text, calculate similarity scores, and display a ranked list of resumes.
Code Breakdown:
🔹 extract_text_from_pdf(file) → Extracts text from uploaded PDF resumes.
🔹 rank_resumes(job_description, resumes)

Converts job descriptions and resumes into TF-IDF vectors.
Computes cosine similarity to determine the relevance of each resume.
Returns a ranked list based on similarity scores.
Streamlit UI:
✔️ Takes job description input
✔️ Allows multiple resume uploads
✔️ Displays a ranked list of resumes for easy comparison

This system simplifies and automates the resume screening process, making it easier for recruiters to identify the best candidates quickly! 🚀
