# Automated Resume Screener

Authors - Camden Weber, Justin Gong, Charlie Hoose, Aayushi Choudhary, Caleb Tran, Lara Papasian, Taylor Kim


## Project Overview
This project focuses on developing an automated resume screening system. Given a dataset of resumes, the system aims to identify approximately 15% of resumes that are most likely to be shortlisted for further review. The project involves feature extraction, model building, and a demonstration of the system's performance.


### Dataset
The dataset was sourced from Kaggle, containing over 2400 resumes in string and PDF formats, organized by industry. The industries include accounting, engineering, chef, finance, teacher, and many more. The data was unlabeled.

### Task
Our team of data scientists was tasked with analyzing these thousands of resumes and reporting approximately 15% of them for the next round of review.

### Feature Extraction
Extracted features from the resumes including skills, work experience, industry keywords, work position, sentiment analysis, and college.

### Model Building
K-Means Clustering
Model Type: Unsupervised learning model.
Function: Sorts resumes into clusters based on distance metrics.
Clusters: 6 clusters chosen to select approximately 15% of resumes.

## Conclusion
Our project successfully demonstrated a method for automating resume screening using data science techniques. The use of feature extraction and K-Means clustering allowed us to identify a subset of resumes for further review efficiently. The project showcases our attempt to create an automated resume screener and gives insight to how the resume screeners that are used by so many big companies today work.
