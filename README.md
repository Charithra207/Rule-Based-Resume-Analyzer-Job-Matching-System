#Overview
This project is a Java-based resume analysis and job-matching system designed to evaluate candidate suitability against job descriptions. It processes resumes and job descriptions, extracts structured information, computes eligibility scores, identifies skill gaps, detects bias, and ranks candidates using rule-based logic and basic NLP techniques.
The system focuses on logic-driven backend processing rather than machine learning models.

#Problem Statement
Recruiters often receive large volumes of resumes that are difficult to evaluate manually. This project aims to:
*Automate resume analysis
*Match candidates with job requirements
*Highlight missing skills and experience gaps
*Improve fairness by detecting biased terms in job descriptions

#Features
*Resume parsing and structured data extraction
*Skill matching between resumes and job descriptions
*Candidate eligibility scoring and ranking
*Skill gap identification
*Career gap and experience analysis
*Bias detection in job descriptions
*JSON-based input and output processing

#Technologies Used
*Java
*Regular Expressions (Regex)
*JSON Processing (Gson)
*Apache OpenNLP (basic NLP tasks)
*Apache Tika (text extraction)
*File Handling & Modular Backend Design

#System Design
1. Resume and job description data are provided in JSON format
2. Text is normalized and processed using Regex and NLP utilities
3. Skills, experience, education, and gaps are extracted
4. Matching logic calculates eligibility scores
5. Candidates are ranked and results are generated as JSON reports
