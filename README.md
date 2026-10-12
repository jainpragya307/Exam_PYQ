# Exam Preparation & PYQ Assistant

## Features
- Student selection from `data/students.csv`
- Subject/unit-wise question bank from `data/questions.csv`
- Smart answer retrieval with TF-IDF and cosine similarity
- Dataset insights and CSV download

## Setup (Windows)
1. Install Python 3.10+ if needed.
2. Open this folder in VS Code.
3. Open Terminal in VS Code.
4. Run:
   ```bash
   python -m venv .venv
   .venv\Scripts\activate
   pip install -r requirements.txt
   streamlit run app.py
   ```
5. A browser tab should open automatically. If not, open the Local URL printed in the terminal.

## Files
- `app.py`: Streamlit application
- `data/students.csv`: sample student records
- `data/subjects.csv`: subject list
- `data/questions.csv`: sample question bank and reference answers

## Important
The included dataset is a starter sample. To meet a unique-dataset requirement, customize it with your own verified questions, subjects, unit mapping, and PYQ metadata. Do not claim these sample rows are official past-paper questions unless verified.
