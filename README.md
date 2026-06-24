# ResumeAI — AI Resume Reviewer

An AI-powered resume reviewer built with Google Gemini API and Preact.
Runs entirely in the browser — no backend, no deployment needed.

## Features
- Resume scoring out of 100
- Strengths & gaps analysis
- ATS keyword checker
- AI-rewritten professional summary
- Top 3 actionable recommendations

## How to use
1. Get a free Gemini API key at https://aistudio.google.com/app/apikey
2. Open `resume-reviewer.html` in any browser
3. Paste your API key, upload your resume, enter target role → Analyse

## Tech
- Preact + htm (no build step)
- Google Gemini API (free tier)
- PDF.js for client-side PDF extraction
