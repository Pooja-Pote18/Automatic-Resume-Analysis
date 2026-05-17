# Automated-Resume-Screening-System

 This project is an **Automatic Resume Analysis Tool** that helps HR teams, recruiters, and students analyze resumes.  
    It extracts text from resumes (`PDF` & `DOCX`), preprocesses using **NLP**, compares against a given Job Description (JD),  and generates an **ATS Score (%)** for ranking candidates.


  ✅ Features:
  - Extracts text from resumes (`.pdf`, `.docx`)
  - Cleans & preprocesses text (stopwords removal, lemmatization)
  - Extracts keywords using **NLTK**
  - Calculates **ATS Score (%)** based on JD matching
  - Ranks candidates & exports results to `CSV`
    


  ⚙️ Tech Stack:
   - Python 3.10+
   - NLTK (NLP processing)
   - PyMuPDF (PDF extraction)
   - python-docx (DOCX extraction)
   - Pandas, NumPy (data analysis)


How it works:

  User uploads a resume PDF.
  
  Recruiter enters job description text.
  
  System extracts text from the resume.
  
  NLP preprocessing is applied:
  
     tokenization
     
     stop word removal
     
     stemming
     
  Resume and job description are converted into vectors.
 
  Similarity score is calculated.
  
  Based on the score, candidates are ranked.






▶️  **Share Linkedin Video Demo**


 https://www.linkedin.com/posts/pooja-pote-5a4526331_project-name-resume-analysis-using-ats-ugcPost-7340343112659087360-kK4R?utm_source=social_share_send&utm_medium=android_app&rcm=ACoAAFOMmcwBvT_W6U2U_mli4PNegGtq-NBSyxk&utm_campaign=whatsapp
