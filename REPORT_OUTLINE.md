# PBL Activity 3 Report Outline
## Project Title
Subject-Wise Exam Preparation and PYQ Assistant Using Python

## Abstract
The project is a lightweight educational application that organizes subject-wise questions and prepared answers in CSV datasets. Students can browse questions by subject and unit, search for a similar question using TF-IDF and cosine similarity, and explore question-bank statistics through charts.

## Problem Statement
Students often keep subject questions, previous-year questions, and reference answers in separate files. Finding a relevant question and reviewing topic coverage can take time.

## Objectives
1. Organize student, subject, and question data in CSV files.
2. Filter questions by subject and unit.
3. Retrieve a relevant stored answer from a natural-language query.
4. Visualize question distribution by subject.
5. Demonstrate an NLP-based text similarity technique.

## Tools and Libraries
Python, Streamlit, Pandas, scikit-learn, Matplotlib, CSV.

## Dataset
Describe `students.csv`, `subjects.csv`, and `questions.csv`: columns, number of records, how the dataset was created/customized, and validation performed. Replace starter sample data with your own unique, verified dataset before final submission.

## Methodology
1. Read CSV files with Pandas.
2. Let the user choose a subject.
3. Filter the question bank to that subject.
4. Convert questions and keywords into TF-IDF vectors.
5. Calculate cosine similarity between the user's query and stored text.
6. Return the answer linked to the strongest sufficiently similar question.
7. Aggregate records and display charts for data insights.

## Beyond-Syllabus Concept
TF-IDF (Term Frequency–Inverse Document Frequency) and cosine similarity for NLP-based text retrieval. Explain that this retrieves an existing answer; it is not a generative AI model.

## Results and Testing
Insert genuine screenshots of:
- Question Bank page
- Smart Answer Finder with a successful match
- Data Insights dashboard
- CSV download or sample dataset

Test at least: subject selection, unit filter, a matching query, an unrelated query, and chart display. Report observed results honestly.

## Limitations
Answers are limited to the prepared dataset; similarity can fail for unusual wording or concepts not present in the CSV. Sample records must be verified and replaced/customized for the final unique dataset.

## Conclusion
Summarize how CSV-based data management, text retrieval, and visualization support exam preparation.

## References
Python documentation, Streamlit documentation, Pandas documentation, and scikit-learn documentation for TfidfVectorizer and cosine_similarity.
