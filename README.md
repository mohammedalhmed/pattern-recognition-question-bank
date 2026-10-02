# Pattern Recognition Question Bank — بنك أسئلة تمييز الأنماط

Interactive Arabic study application for **Pattern Recognition** coursework. It transforms a large question set into a browser-based training and exam experience that works without a backend.

## Highlights

- **144 questions** organized across lectures 1, 3, 4, 6, 7, and 8.
- Training mode with immediate answer feedback.
- Exam mode with scoring after completion.
- Filtering by question type.
- Review workflow for incorrect answers.
- Automatic progress persistence using `localStorage`.
- Responsive Arabic interface.
- Works offline after the page is loaded.
- No framework or backend required.

## Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111111)
![LocalStorage](https://img.shields.io/badge/LocalStorage-111111?style=flat-square)
![RTL](https://img.shields.io/badge/Arabic_RTL-111111?style=flat-square)

## Learning Flow

```text
Choose Mode
    ↓
Filter / Start
    ↓
Answer Questions
    ↓
Immediate Feedback or Exam Scoring
    ↓
Review Mistakes
    ↓
Progress Saved Locally
```

## Run Locally

Because the application is static, it can be opened directly or served with a simple local server:

```bash
python3 -m http.server 4173
```

Then open:

```text
http://localhost:4173
```

## Project Structure

```text
.
├── index.html
└── README.md
```

The application is intentionally packaged as a single-page static study tool so it can be moved, hosted, or used offline with minimal setup.

## What This Project Demonstrates

This project focuses on turning academic material into a practical learning product using **interaction design, progress persistence, assessment modes, and Arabic-first UX**.
