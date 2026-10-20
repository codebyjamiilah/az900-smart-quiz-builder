# 📝 AZ-900 Smart Quiz Builder

> **Unofficial study tool. Not affiliated with, endorsed by, or sponsored by Microsoft.**
> All questions are original and written for learning. They are not real exam questions.

Built for the **Vibe Coding Hackathon: AZ-900 Exam Prep Edition** (#1MillionDevs, Power Learn Project Africa).

**🔗 Live demo:** https://codebyjamiilah.github.io/az900-smart-quiz-builder/
**🎥 Demo video:** [add link here]

---

## The problem

When I studied for Microsoft Azure Fundamentals (AZ-900), the part I found hardest was **Describe Azure management and governance**. Tools like Azure Policy, RBAC, resource locks, tags, Azure Advisor, Azure Monitor and the cost calculators have similar names and overlapping jobs, so it is easy to mix them up.

Many practice quizzes only mark an answer right or wrong. I needed to understand **why**, so I could tell similar services apart.

## The solution

A quiz app that explains **every** answer straight away, organised by the three AZ-900 areas:

1. Cloud Concepts
2. Architecture & Services
3. Governance & Management

## Features

- ✅ 27 original, scenario-style questions
- 💡 Instant explanation after every answer (right or wrong)
- 🎯 Choose one domain or all domains
- 🔀 Questions and answer options shuffled every time
- 📊 Results screen with score by domain
- 🔁 "Retry missed questions" button for targeted revision
- 🏆 Remembers your best score in your browser
- 📱 Works on phone and desktop, with light and dark mode

## How to run it

No installation needed.

1. Download or clone this repository.
2. Open `index.html` in any web browser.

Or use the live demo link above.

## Built with

- HTML, CSS and JavaScript in a single file (no backend, no accounts)
- **Claude (Anthropic)** for AI-assisted building, question drafting and prompt engineering
- GitHub Pages for hosting

## How the AI was used (prompt engineering)

I used Claude as a build partner and followed these steps:

1. Gave Claude the hackathon brief and asked it to explain the requirements.
2. Chose the Smart Quiz Builder challenge and asked for a working prototype.
3. Asked Claude to write original questions based on the public AZ-900 skills outline.
4. Asked Claude to find topics my first version missed (identity and security) and add questions for them.
5. Reviewed the content myself against Microsoft Learn.

My full prompts are in [`PROMPTS.md`](PROMPTS.md).

## Content accuracy

Questions are based on the public AZ-900 skills outline on Microsoft Learn. Always check the official outline and documentation, because Azure services and the exam change over time.

## Future ideas

- More questions focused on management and governance
- Timed exam mode
- Weak-area recommendations after each quiz
- Companion flashcard mode with spaced repetition
- Support for other Microsoft fundamentals certifications

## Author

**NAMAYANJA WANYANA JAMIILA**, Power Learn Project / #1MillionDevs
(namayanjajamiilah@gmail.com)

## Disclaimer

This project is for education only. "Microsoft" and "Azure" are trademarks of Microsoft Corporation. No Microsoft logos are used here.
