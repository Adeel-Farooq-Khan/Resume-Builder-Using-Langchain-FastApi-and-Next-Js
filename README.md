# AI Career Assistant 🎓💼

An intelligent assistant designed to enhance your job application experience. With a suite of AI-powered tools, AI Career Companion helps you create ATS-optimized resumes, evaluate job application fit, generate tailored cover letters, and prepare for interviews—all in one platform!

---

## 🚀 Features

1. **AI Resume Builder** 📝  
   Generate a resume optimized for the highest ATS score to boost visibility during the hiring process.

2. **Resume Evaluator** 📊  
   Upload your resume and a job description to receive a matching score along with specific improvement suggestions.

3. **Cover Letter Generator** 📄  
   Create a tailored cover letter using your resume, job description, and role information to stand out to recruiters.

4. **Interview Preparation** 🎯  
   Prepare for interviews by generating targeted MCQs based on the job description and level. Complete the test to see your score and track your progress.

---

## 🗂 Project Structure

```
project/
├── fast_api/                 # Backend (FastAPI)
│   ├── .env                  # API keys and configurations
│   ├── database.py
│   ├── file.txt
│   ├── graph.py
│   ├── main.py               # Main application entry
│   ├── models.py             # Database models
│   ├── requirements.txt      # Python dependencies
│   ├── schemas.py            # API schemas
│   └── utils.py              # Utility functions
└── next_js/                  # Frontend (Next.js)
    ├── .env
    ├── .eslintrc.json
    ├── next-env.d.ts
    ├── next.config.ts
    ├── package.json
    ├── postcss.config.mjs
    ├── public/
    ├── src/
    │   ├── app/
    │   │   ├── about
    │   │   ├── api
    │   │   ├── cover-letter
    │   │   ├── create-resume
    │   │   ├── dashboard
    │   │   ├── interview-prep
    │   │   ├── login
    │   │   ├── resume-checker
    │   │   └── signup
    │   ├── components/
    │   │   ├── theme-provider.tsx
    │   │   └── ui/           # UI components (button, card, etc.)
    │   └── lib/              # Utility functions
    ├── tailwind.config.ts
    └── tsconfig.json
```

---

## ⚙️ Installation Guide

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Adeel-Farooq-Khan/Resume-Builder-Using-Langchain-FastApi-and-Next-Js.git
   ```

2. **Backend Setup**:
   - Navigate to the `fast_api` directory:
     ```bash
     cd AI-Career-Assistant-with-Nextjs-FastAPI/fast_api
     ```
   - Create a virtual environment:
     ```bash
     python -m venv env
     ```
   - Activate the virtual environment:
     - On Windows:
       ```bash
       .\env\Scripts\activate
       ```
     - On macOS/Linux:
       ```bash
       source env/bin/activate
       ```
   - Install the required dependencies:
     ```bash
     pip install -r requirements.txt
     ```
   - Add your **Gemini API key** in the `.env` file.

3. **Frontend Setup**:
   - Navigate to the `next_js` directory:
     ```bash
     cd ../next_js
     ```
   - Install dependencies:
     ```bash
     npm install
     ```

---

## 🏃 Running the Project

1. **Run the Backend**:
   - In the `fast_api` directory, start the backend server:
     ```bash
     uvicorn main:app --reload
     ```

2. **Run the Frontend**:
   - In the `next_js` directory, start the frontend:
     ```bash
     npm run dev
     ```

---

## 📝 Usage

1. **AI Resume Builder**: Enter your details to generate a resume optimized for ATS detection.
2. **Resume Evaluator**: Upload your resume and job description to evaluate compatibility.
3. **Cover Letter Generator**: Get a cover letter customized to the job.
4. **Interview Preparation**: Answer MCQs based on your selected job level, and get instant feedback.

---

## 🛠️ Tech Stack

- **Backend**: FastAPI, Python
- **Frontend**: Next.js, Tailwind CSS
- **AI Models**: Gemini API for NLP processing

---

## 📌 Notes

- Ensure to enter your Gemini API key in the `.env` file under `fast_api`.
- Use separate terminals for backend and frontend servers.

---

