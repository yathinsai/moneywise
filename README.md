# MoneyWise Gen Z v2

A lightweight student-led financial literacy MVP for grades 6–8.

## Contents
- `index.html` — interactive Vanilla JS web interface
- `data/questions.json` — 20 multiple-choice questions with explanations
- `data/scenarios.json` — 10 decision challenges with feedback
- `data/faqs.json` — 20 FAQ entries

## Run locally
From the `moneywise-v2` directory:

```bash
python3 -m http.server 8000
```

Open http://localhost:8000 . Do not open `index.html` directly via `file://` because browser security may block JSON fetches.

## Deploy to GitHub Pages
Commit `index.html` and the `data/` directory to a public repository. In repository Settings → Pages, deploy from the main branch root. The site uses relative data paths.

## Privacy and evaluation
Progress and feedback are stored in localStorage on the current browser only. No account or server is used. The Export button produces a local JSON file; do not collect identifying details from minors. Feedback is not synchronized between devices. For workshop pre/post measurement, use an approved anonymous assessment with the same five questions before and after.

## Content review status
The 20 questions, 10 scenarios, and 20 FAQs are editorial drafts with manually checked arithmetic and wording, **not yet independently reviewed by an educator or tested with teens**. Complete educator review and a small teen usability pilot before publicly describing the content as validated.

## Pilot testing
Recruit 3–5 teens with parent/venue permission. Ask each to finish two scenarios, five quiz items, find one FAQ, and submit anonymous feedback. Record task completion, confusing wording, and bugs; revise before a 10–20 student workshop.
