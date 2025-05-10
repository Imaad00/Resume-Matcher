# 💼 Resume Matcher

**Resume Matcher** is an AI-powered tool to tailor your resume for specific job descriptions. It mimics an ATS (Applicant Tracking System) to help you extract keywords, improve relevance, and score your resume against job descriptions using NLP and vector similarity techniques.

---

## 🚀 Features

- ✅ Parses PDF resumes and job descriptions  
- 🧠 Extracts key skills and domain-specific terms using NLP  
- 🔍 Compares resumes to job descriptions using vector similarity (FastEmbed)  
- 📊 Generates insights on match percentage and keyword coverage  
- 💻 Supports batch processing and interactive single-resume mode  

---


## 🛠️ How to Install and Run

```bash
# Step 1: Clone the Repository
git clone https://github.com/Imaad00/Resume-Matcher.git
cd Resume-Matcher

# Step 2: Create a Virtual Environment
python -m venv env

# Step 3: Activate the Virtual Environment

# On Windows
env\Scripts\activate

# On macOS/Linux
source env/bin/activate

# Step 4: Install Required Packages
pip install textacy
pip install spacy
pip install pypdf
python -m spacy download en_core_web_md
python -m spacy download en_core_web_sm

# Step 5: Add Your Data
Put your resume PDFs in the Data/Resumes/ folder
Put your job description PDFs in the Data/JobDescription/ folder
Make sure to remove any previous files if needed

# Step 6: Run Batch Matching
python run_first.py
streamlit run streamlit_second.py

# OR Step 7: Run Interactive Matching for One Resume and JD
streamlit run streamlit_interactive.py
```
## 📌 License
This project is licensed under the Apache 2.0 License.

