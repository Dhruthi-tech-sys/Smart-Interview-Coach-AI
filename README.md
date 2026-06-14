# Smart Interview Coach AI

## Overview

Smart Interview Coach AI is an AI-powered web application that helps students and job seekers prepare for interviews. The system analyzes a resume, identifies skills and projects, generates interview questions, evaluates responses, and provides personalized feedback.

## Problem Statement

Many candidates struggle to prepare effectively for interviews because they do not know what questions to expect or how to evaluate their answers. This project aims to provide an intelligent interview preparation platform that simulates a real interview experience.

## Features

### Current Features
- Upload Resume (PDF)
- Extract Resume Text
- Detect Skills from Resume

### Upcoming Features
- AI-Based Interview Question Generation
- Role-Based Question Selection
- Answer Evaluation and Scoring
- Feedback Generation
- Interview Performance Dashboard
- Report Generation

## Tech Stack

### Frontend
- Streamlit

### Backend
- Python

### Libraries
- PyPDF2
- SpaCy
- NLTK
- Hugging Face Transformers
- Pandas

## Project Structure

```text
Smart-Interview-Coach-AI/

├── app.py
├── resume_parser.py
├── requirements.txt
├── README.md
│
├── data/
├── resumes/
├── reports/
└── images/
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Smart-Interview-Coach-AI.git
```

Move to project directory:

```bash
cd Smart-Interview-Coach-AI
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

## Workflow

1. Upload Resume
2. Extract Resume Content
3. Detect Skills and Projects
4. Generate Interview Questions
5. Evaluate Candidate Answers
6. Generate Feedback Report

## Future Enhancements

- Voice-Based Interview Simulation
- AI Mock Interview Sessions
- Real-Time Speech Analysis
- Personalized Learning Recommendations
- Interview History Tracking

## Project Status

### Phase 1
- [x] Resume Upload
- [x] PDF Text Extraction

### Phase 2
- [ ] Skill Extraction
- [ ] Question Generation

### Phase 3
- [ ] Answer Evaluation
- [ ] Feedback System

### Phase 4
- [ ] Deployment

## Author

Your Name

## License

This project is developed for educational and internship purposes.# Smart-Interview-Coach-AI