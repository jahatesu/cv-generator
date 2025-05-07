# 📝 cv-generator
A simple web app to build and export CVs as PDF built with Flask and HTML/CSS. Users can input their information and download a professional-looking resume as a PDF. Ideal for students and job seekers who want a fast and clean way to generate resumes.
---
## 🚀 Features

- 🖊️ Input personal info, education, experience, and skills
- 🔍 Live preview of the resume
- 🎨 Option to choose from clean resume templates (coming soon)
- 📄 Download resume as a PDF
- ✨ AI-assisted content generation for summaries or job descriptions
---
## 🧭 User Flow

1. Visit the homepage and click “Start Building”
2. Fill out a form with your CV information
3. Preview the resume in a clean layout
4. Click “Download PDF” to save it locally
---
## 🛠️ Tech Stack

| Layer        | Tech               |
|--------------|--------------------|
| Backend      | Python (Flask)     |
| Frontend     | HTML,CSS,JavaScript|
| Styling      | Tailwind           |
| PDF Export   | WeasyPrint / pdfkit|
| AI           | OpenAI API (GPT-4) |
| Deployment   | Render             |

---

## 📆 Milestones

### ✅ Week 1: Planning
- [x] Define features & user flow
- [x] Create wireframes and repo
- [ ] Set up project structure with Flask

### ⏳ Week 2: Form + Preview
- [ ] Build input form
- [ ] Store user data and show preview

### ⏳ Week 3: PDF Export
- [ ] Style preview template
- [ ] Export resume as a PDF

### ⏳ Week 4: Polish & Deploy
- [ ] Add multiple templates (optional)
- [ ] Deploy to Render
- [ ] Finalize README and showcase

## 📁 Project Structure
cv-generator/
├── app/
│   ├── templates/
│   ├── static/
│   └── __init__.py
├── venv/
├── run.py
├── requirements.txt
├── .gitignore
└── README.md
