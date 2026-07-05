# AI Resume Analyzer

An AI-powered Resume Analyzer built with **Flask** and the **Google Gemini API**. Upload your resume in PDF format and receive an intelligent analysis with strengths, weaknesses, ATS optimization suggestions, missing skills, and personalized improvement recommendations.

## Features

- Upload PDF resumes
- AI-powered resume analysis
- ATS-friendly improvement suggestions
- Skill gap identification
- Resume scoring and feedback
- Clean and responsive user interface
- Secure file upload handling

## Tech Stack

- Python
- Flask
- HTML5
- CSS3
- JavaScript
- Google Gemini API
- pdfplumber

## Project Structure

```
AI-Resume-Analyzer/
│── app.py
│── config.py
│── utils.py
│── requirements.txt
│── .env.example
│── README.md
│
├── templates/
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
└── uploads/
```

## Installation

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/AI-Resume-Analyzer.git
cd AI-Resume-Analyzer
```

### Create a virtual environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

## Environment Variables

Create a `.env` file in the project root.

```
GEMINI_API_KEY=your_google_gemini_api_key
SECRET_KEY=your_secret_key
```

## Run Locally

```bash
python app.py
```

Open your browser:

```
http://127.0.0.1:5000
```

## Deploy on Render

Build Command

```bash
pip install -r requirements.txt
```

Start Command

```bash
gunicorn app:create_app
```

Don't forget to add your environment variables in the Render dashboard.

## Screenshots

Add screenshots of:

- Home Page
- Resume Upload
- Analysis Result
- Dashboard

## Future Improvements

- DOCX resume support
- Resume history
- User authentication
- Multiple resume comparison
- Downloadable PDF reports
- AI interview preparation

## License

This project is intended for educational and portfolio purposes.

## Author

Developed by **krimal**
