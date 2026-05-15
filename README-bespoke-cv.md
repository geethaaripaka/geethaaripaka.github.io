# Bespoke CV

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=flat-square&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-red?style=flat-square&logo=streamlit&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_2.5_Flash-4285F4?style=flat-square&logo=google&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

Surgical CV rewrites powered by AI — only the bullets that need fixing, not a full rewrite.

---

<!-- Add demo link or screenshot here -->

---

## Features

- Side-by-side diff view of every suggested edit — accept or reject each change individually
- Live JD match score weighted by bullet-level impact, not just keyword presence
- ATS keywords woven into rewrites naturally, not appended as a separate list
- Downloads as Word (.docx) with original formatting, fonts, and structure preserved
- temperature=0 for consistent, repeatable output every time

---

## Tech Stack

| Tool | Purpose |
|---|---|
| Streamlit | UI and app framework |
| Gemini 2.5 Flash API | Bullet analysis and rewriting |
| python-docx | Reading and writing .docx files |
| BeautifulSoup | Extracting job descriptions from URLs |

---

## Run Locally

```bash
git clone https://github.com/geethaaripaka/bespoke-cv.git
cd bespoke-cv
pip install -r requirements.txt
streamlit run app.py
```

Add your Gemini API key to a `.env` file:

```
GEMINI_API_KEY=your_key_here
```

---

## Built By

**Geetha Aripaka** — Product Manager  
[github.com/geethaaripaka](https://github.com/geethaaripaka)
