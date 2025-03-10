Name: Bayana Sravya Sindhu<br/>
AI Resume Screening & Candidate Ranking System<br/>
<b>Overview</b><br/>
This project is an AI-driven Resume Screening & Candidate Ranking System developed using Streamlit, PyPDF2, and Scikit-learn. The system analyzes resumes and ranks them based on their relevance to a given job description using TF-IDF vectorization and cosine similarity.</br>

<b>Key Features:</b><br/>
<ul>Job Description Input: Users can enter a job description as a reference.</ul>
<ul> Bulk Resume Upload: Supports uploading multiple resumes in PDF format.</ul>
<ul> Automated Text Extraction: Extracts text from resumes for analysis.</ul>
<ul> Intelligent Ranking: Uses AI to rank resumes based on relevance.</ul>
<ul> User-Friendly Display: Shows ranked results in a descending order of relevance.</ul>

<b>Installation</b>
<b>Prerequisites:</b>
Ensure Python is installed on your system. Then, install the required dependencies using:<br/>

  pip install streamlit PyPDF2 scikit-learn pandas<br/>
How to Use:<br/>
Run the application with the command:<br/>

  streamlit run app.py<br/>
Enter the job description in the provided input box.<br/>
Upload PDF resumes to be analyzed.<br/>
The system will extract text, calculate similarity scores, and display a ranked list of resumes.<br/>
Code Breakdown:<br/>
🔹 extract_text_from_pdf(file) → Extracts text from uploaded PDF resumes.<br/>
🔹 rank_resumes(job_description, resumes)<br/>

Converts job descriptions and resumes into TF-IDF vectors.<br/>
Computes cosine similarity to determine the relevance of each resume.<br/>
Returns a ranked list based on similarity scores.<br/>
Streamlit UI:<br/>
✔️ Takes job description input<br/>
✔️ Allows multiple resume uploads<br/>
✔️ Displays a ranked list of resumes for easy comparison<br/>

This system simplifies and automates the resume screening process, making it easier for recruiters to identify the best candidates quickly! 🚀
