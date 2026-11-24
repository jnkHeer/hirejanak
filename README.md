# Janak Raj | Portfolio & Resume

Senior Software Engineer with 8+ years building mobile apps, web dashboards and REST APIs for fintech, payments, healthcare, edtech and IoT.

- **Live portfolio:** https://hirejanak.web.app
- **Resume (PDF):** [resume/Janak_Raj_Resume.pdf](resume/Janak_Raj_Resume.pdf)
- **Resume (Word):** [resume/Janak_Raj_Resume.docx](resume/Janak_Raj_Resume.docx)
- **LinkedIn:** https://www.linkedin.com/in/janak-raj-software-dev

**Stack:** Flutter, Dart, Android (Kotlin, Java), iOS, Node.js, Python (FastAPI), REST APIs, AWS, Firebase, CI/CD

## What's in this repo

| Path | What it is |
|---|---|
| `public/index.html` | The portfolio site: a single, dependency-free HTML page (inline CSS and JS) |
| `public/Janak_Raj_Resume.pdf` | The resume served by the site's Download Resume buttons |
| `resume/resume.html` | Resume source; the PDF is printed from it |
| `resume/Janak_Raj_Resume.docx` | Word version of the resume |
| `firebase.json` | Firebase Hosting config for the `hirejanak` site |

## Run locally

```bash
cd public && python3 -m http.server 5178
```

Then open http://localhost:5178

## Rebuild the resume PDF

```bash
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless=new --no-pdf-header-footer \
  --print-to-pdf=public/Janak_Raj_Resume.pdf "file://$PWD/resume/resume.html"
cp public/Janak_Raj_Resume.pdf resume/
```

## Deploy

```bash
firebase deploy --only hosting:hirejanak
```

## Contact

janak206@gmail.com · +91 94650 65059
