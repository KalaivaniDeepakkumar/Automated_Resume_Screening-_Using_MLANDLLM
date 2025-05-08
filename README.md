# Automated_Resume_Screening-_Using_MLANDLLM
Automated Resume Screening Using ML and LLM
# Abstract
The proposed system revolutionizes recruitment by automating resume screening using Machine Learning and a Large Language Model (LLM). A Random Forest classifier first filters resumes with 94–95% accuracy based on job functions. Shortlisted candidates are then rigorously ranked (0–100) by Gemini-1.5 LLM, evaluating skills, education, and achievements while excluding demographic data to ensure fairness. A Streamlit dashboard offers HR teams clear candidate comparisons and AI-generated summaries. This data-driven, bias-free platform ensures merit-based selection and promises future integration with ATS for complete recruitment automation.
# System requirements
# Development Environment:
Google Colab for model development and testing with GPU support.

Python 3 is the primary programming language for ease and ML library support.

# Core Libraries & Tools:
Scikit-learn for building the Random Forest classifier.

Google Gemini API for LLM-based resume evaluation and bias-free scoring.

# Data Parsing & NLP:
PyPDF2 and docx2txt for extracting text from resumes (PDF, DOCX, TXT).

NLTK/spaCy for text preprocessing and entity recognition.

# Dashboard & Interface:
Streamlit for building an interactive HR dashboard for resume viewing, scoring, and AI summaries.

# Database & Integration:
MongoDB (NoSQL) for storing resumes, job details, and evaluation results.

PyMongo for fast database communication and data retrieval.

# Hardware Requirements:
Processor: Minimum Intel i5/Ryzen 5; preferred i7/i9 or Ryzen 7/9.

RAM: Minimum 8GB; recommended 16GB+ for smooth ML and LLM execution.

Storage: At least 50GB SSD for fast access.

Internet: Stable broadband for API access and cloud integration.
# Project Workflow
1.Frontend Interface (Streamlit): HR professionals upload job requirements and candidate resumes, view AI-generated assessments, and interact with a user-friendly dashboard.

2.Resume Submission & Storage: Uploaded resumes are stored in MongoDB, ensuring scalable and fast access to candidate profiles and job data.

3.Document Parsing Module: Extracts text from various resume formats/layouts to standardize data for further processing.

4.Initial Classification (Random Forest): Resumes are filtered and matched to the most relevant job roles with 94–95% accuracy using a trained Random Forest classifier.

5.Deep Analysis (Gemini LLM): Cleared resumes undergo semantic evaluation using Gemini-1.5 LLM, scoring candidates (0–100) based on skills, experience, education, and relevance—while ensuring fairness by omitting demographic info.

6.Real-Time Processing: The system handles high volumes of applications with speed and accuracy, dynamically updating the recruiter dashboard.

7.Dashboard Display & Insights: HR can view detailed feedback, seriousness indicators, suitability scores, and AI-generated summaries to assist in fair decision-making.

# Conclusion
The Automated Resume Screening System effectively combines machine learning and large language models to revolutionize recruitment. Using a Random Forest classifier, resumes are accurately matched to job roles with up to 95% accuracy. Google’s Gemini LLM enhances evaluation by analyzing candidates across technical skills, achievements, education, experience, and skill relevance, while ensuring unbiased assessments. MongoDB ensures secure and scalable data storage throughout the pipeline. Overall, the system streamlines screening and improves hiring fairness through smart, modular automation.


# DEPLOYMENT LINK
HR INTERFACE - https://resumescreening-dmsfdeqtqngyxfpaljh4dn.streamlit.app/
CANDIDATE INTERFACE - https://resumescreening-9ygshxjdfavm3vnwuhzyrg.streamlit.app/
