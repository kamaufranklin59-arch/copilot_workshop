# Project instructions

- This is a static, dependency-free browser project. Keep each page self-contained and offline: its markup, CSS, quiz data, and JavaScript belong in that page. `index.html` is the primary page; `space_quiz.html` is an independent variant. Change both only when parity is requested.
- Keep implementations simple and readable. Avoid adding libraries, build tooling, external assets, or scripts. Prefer descriptive names and minimal comments; comment only when intent is not clear from the code.
- Preserve accessible behavior: use native buttons, retain progressbar and answer-group labels and live feedback, and respect reduced-motion preferences. In `index.html`, keep focus moving to the first answer on question changes and to the replay button on results.
- Preserve quiz rules: answer indices are zero-based, only correct answers increase the score, and all answers are disabled after a selection to prevent duplicate scoring.
- Follow the existing CSS custom properties and dark-mode values when styling. Keep visual changes consistent across themes.
- There is no build step, test runner, or lint command. Test by opening the relevant HTML file directly in a browser. Smoke-test correct and incorrect answers, score and feedback, question advancement, keyboard operation and focus, completion, and replay reset. Do not add a server or dependencies just for testing.
