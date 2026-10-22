# RoleMatch AI — Product Case Study

## Problem
Students applying to internships often need to tailor their resumes quickly, but may struggle to identify which role requirements are already demonstrated in their experience and which need attention.

## Target user
Students and early-career applicants applying to internships and entry-level roles.

## Product hypothesis
If applicants can compare a resume with a job description and receive a short, actionable list of terms and next steps, they will be better equipped to tailor their applications with less manual effort.

## MVP solution
- Two text inputs: resume and job description.
- Local keyword comparison in the browser.
- Terms found and terms to review.
- Practical tailoring suggestions.
- A structured prompt to request deeper, contextual feedback from an external AI assistant.

## Why the AI handoff is deliberate
This is a static, no-backend portfolio demo. Calling a paid AI API directly from public JavaScript would expose a secret key. The MVP instead gives users control over whether and where to send their text. The site clearly labels which results are local keyword analysis and which feedback comes from the external AI assistant.

## Success metrics to test
1. Task completion: percentage of test users who complete a comparison without help.
2. Time to first useful action: time from page open to identifying one relevant resume improvement.
3. Perceived usefulness: 1–5 rating after reviewing the output.
4. Trust and clarity: percentage of users who correctly understand the match score is not a hiring probability.
5. AI prompt handoff rate: percentage of users who choose to copy the prompt.

## Usability test plan
Ask 3–5 students to use a fictional resume and internship description. Observe whether they can load sample data, run the comparison, explain the score, and copy the prompt. Ask what they would change before using it for a real application. Do not collect or retain their personal resumes.

## Known limitations
- Keyword scan is not semantic and may miss synonyms or context.
- The starter vocabulary is limited and should be expanded based on testing.
- No accounts, server storage, or automatic cross-device syncing.
- External AI feedback depends on the selected service and its own policies.
- Suggestions must be checked by the user; the app should never encourage inventing experience.

## Next steps
1. Publish on GitHub Pages and test the public URL.
2. Conduct a small usability test and record observations.
3. Improve vocabulary and synonym handling based on evidence.
4. Consider a secure server-side AI integration only if there is a clear need and a sustainable, privacy-conscious hosting plan.
