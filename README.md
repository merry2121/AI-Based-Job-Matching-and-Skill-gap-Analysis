
AI-Based Job Matching & Skill Gap Analysis
Overview
This project uses SBERT (Sentence-BERT) and machine learning to match resumes with job descriptions, identify missing skills, calculate similarity scores, and evaluate skill gaps.
Features
- Resume–Job similarity scoring
- Missing skill detection
- Skill gap percentage calculation
- CSV output generation
- Streamlit-based interactive demo
- Ethiopian SBERT model compatibility
Tech Stack
- Python
- Streamlit
- SBERT
- Scikit-learn
- Pandas & NumPy
- Ngrok (optional)
- Google Colab

Project Structure
- app.py – Streamlit app
- job_matching_model.pkl – Saved SBERT/ML model
- results.csv – Output scores
- requirements.txt – Dependencies
- README.md
How to Run
Option 1 – Local Machine
1. Install dependencies:
   pip install -r requirements.txt
2. Run the app:
   streamlit run app.py
Option 2 – Google Colab
1. Upload files
2. Install dependencies
3. Run Streamlit via Ngrok
Future Improvements
- Better NER-based skill extraction
- Amharic & Tigrinya resume support
- Permanent deployment (HF Spaces / Render)
- Recruiter-side dashboard

Author
Meron Kidane
# AI-Based-Job-Matching-and-Skill-gap-Analysis
