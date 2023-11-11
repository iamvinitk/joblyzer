# Project Outline & Abstract

## Project Title: Automated Keyword Extraction from Job Descriptions

## Team Members:
1. Naveen Kumar Kundla - 016021941
2. Sivakrishna Yaganti - 017428853
3. Vinit Kanani - 016651323

## Abstract
Applicant tracking systems (ATS) are commonly used by employers to automatically scan resumes for relevant keywords from job descriptions. However, many qualified candidates may be overlooked if their resumes lack explicit matches for keywords. This project aims to automate the extraction of key skills and qualifications from job descriptions using natural language processing. The extracted keywords can then be used to optimize resumes so they contain relevant terms that will enable candidates to successfully pass initial ATS screening. By improving keyword matching between applicant resumes and job descriptions, this system can help job seekers better tailor their resumes while enabling employers to more accurately identify qualified applicants that may have been previously overlooked.  Overall, automated keyword extraction will make the initial resume screening process more efficient for both applicants and employers.


## Project Outline
1. Introduction

    a. Problem Statement

    b. Motivation

    c. Related Work

    d. Proposed Solution

2. Data Collection

    a. Scrape job descriptions from greenhouse.io

    b. Kaggle dataset [Link](https://www.kaggle.com/datasets/khaliladimassi/cleaned-job-description)

3. Data Preprocessing & Cleaning for scraped data

    Extract plain text from HTML pages through parsing and stripping HTML tags, scripts, styling, and other non-text content.

4. Model Training

    a. Pre-trained model:
   - Spacy Models 
   - Standford NLP Model

    b. Fine-tuned model:
   - Fine-tune annotations for scraped data
   - Train model on fine-tuned data
   - Evaluate model performance

5. Results

    a. Compare performance of pre-trained and fine-tuned models

    b. Compare performance of different models

6. Conclusion

    a. Summary of results

    b. Future work

7. References


## Dataset
The data for this project will consist of 10000+ job descriptions scraped from greenhouse.io, a popular recruiting software platform. Additionally, a dataset of over 160,000 cleaned annotated job descriptions from Kaggle might be utilized to evaluate the models.

## Ethical considerations

### Global Impact
The project would help job-seekers to better tailor their resumes resulting in more efficient job search. This would also benefit employers by enabling them to more accurately identify qualified applicants that may have been previously overlooked. But, the project can also be misused to bypass the initial screening process and get unqualified candidates through the door.

### Economic Impact
This project would benefit both the job-seekers and employers by making the initial resume screening process more efficient. However, if the candidates misuse the project to bypass the initial screening process, it would result in higher costs for employers.

### Environmental Impact
The project would not have any significant environmental impact. The training of models would require computing resources, but the impact would be negligible.

### Societal Impact
The project can have a significant positive impact to the well qualified candidates. However, the project can also be misused to deceive the employers.
