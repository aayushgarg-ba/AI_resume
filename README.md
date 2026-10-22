# RoleMatch AI — Resume & Job Match Assistant

A beginner-friendly portfolio MVP built with HTML, CSS, and vanilla JavaScript.

## Features
- Compare pasted resume text with a pasted job description.
- Display a transparent keyword-overlap indicator and terms to review.
- Suggest practical resume-tailoring next steps.
- Create a structured prompt for contextual feedback from ChatGPT or Gemini.
- Keep resume text in the browser; no account, server, or API key is required.

## Important scope note
The match percentage is a simple keyword-overlap indicator, not an AI assessment or hiring probability. The AI feedback step is performed by the external AI assistant the user chooses; this static site does not call an AI model itself. This avoids exposing a secret API key in a public front-end app.

## Run locally
Open `index.html` in a modern browser. Click **Load sample**, then **Analyse match**. Try **Copy AI feedback prompt** and paste it into a free AI assistant.

## Publish with GitHub Pages
1. Sign in to GitHub and create a new **Public** repository named `rolematch-resume-assistant`.
2. Upload `index.html` to the repository root. You may also upload this README and `product_case_study.md`.
3. Open **Settings → Pages**.
4. Under build/deployment, choose **Deploy from a branch**; select `main` and `/(root)`, then Save.
5. Wait for GitHub Pages to finish deploying. The URL usually follows `https://YOUR-USERNAME.github.io/rolematch-resume-assistant/`.
6. Open the actual URL in a private/incognito window and test the sample flow, copy prompt, and mobile layout. Do not report the URL as live until it loads successfully.

GitHub account access is required to create and publish the repository. Do not put API keys, personal resumes, or other private data in the public repository.
