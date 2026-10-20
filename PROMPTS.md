# Prompts used (AZ-900 Smart Quiz Builder)

I used **Claude (Anthropic)** as a build and learning partner. This file records my prompts in order, what each one produced, and why it worked.

> Unofficial study tool. Not affiliated with or endorsed by Microsoft.

## Prompt log

| # | What I asked Claude | What it produced | Why it worked |
|---|---|---|---|
| 1 | Pasted the hackathon email and asked: "help me understand what the assignment requires" | A plain-English summary of the task, the 5 challenges, dates, tools, judging and rules | I gave the **full original text**, so nothing was guessed |
| 2 | "What should I do? I want to use Claude and create the work" | A step-by-step plan and a question about which challenge to build | Stated my goal and the tool I wanted to use |
| 3 | Chose the **Flashcard Coach** | A working flashcard app with spaced repetition (24 original cards) | One clear, narrow choice |
| 4 | "Let's do this Smart Quiz Builder" | A working quiz app with instant explanations and a results screen | Clear goal; the brief defined what "good" looked like |
| 5 | Pasted the full hackathon brief: "what does this mean, explain to me" | Explained the extra requirements: GitHub repo, README, pitch deck, accuracy | Pasted the full document, then asked for a plain explanation |
| 6 | Corrected the deadline: "deadline is Friday 6pm" | Plan adjusted to the right deadline | I **checked the source** and corrected the AI |
| 7 | "What do you think I will be quizzed on in the exam?" | A search of the official AZ-900 skills outline and a list of likely topics | Triggered a **real source check**, not a guess |
| 8 | Asked what to do next, after the topic review | Added 9 identity and security questions (Conditional Access, Zero Trust, RBAC, Defender for Cloud, Purview) | Closed a **gap** that the topic review found |
| 9 | "Do GitHub and README, explain like I'm a child. My hardest topic was Azure management and governance" | A README built around my own struggle, a repo structure, and step-by-step GitHub steps | Added **my personal story** and asked for a simple style |
| 10 | Shared screenshots of my GitHub screens | Claude spotted that my README was still the empty starter file | Screenshots gave **exact evidence** |
| 11 | Asked to add questions for my hardest topic | 10 new management and governance questions (Policy vs RBAC, Service Health vs Resource Health, tags, Cost Management, locks, Log Analytics, Application Insights, Cloud Shell) | Targeted the exact confusion I had while studying |
| 12 | Reported: "it still shows 27 questions" and shared a screenshot | Found my old file was still live, and the correct question count was 38 | Reported **what I saw**, with evidence |
| 13 | Shared the file list when my website showed the README | Found the file was named `index.html.html` and gave a fix | A screenshot showed the real cause (a hidden file extension) |

## Prompt techniques I used

1. **Give full context.** I pasted the real hackathon documents instead of summarising them.
2. **Ask for plain language.** I asked for explanations "like to a child" until each step was clear.
3. **Use my own experience.** I told Claude that management and governance was my hardest topic, so the quiz targets real confusion.
4. **Check against sources.** I asked what the exam covers, which led to a search of the official skills outline and showed a gap.
5. **Correct the AI.** I fixed the deadline, and I recounted the questions when the numbers didn't match.
6. **Show evidence.** I shared screenshots when something broke, so the fix was exact.
7. **Iterate in small steps.** One feature or fix per prompt.

## What I checked myself (human review)

- [ ] Compared the questions with the official AZ-900 skills outline on Microsoft Learn
- [ ] Played every domain on the live site, on desktop and phone
- [ ] Confirmed the tool is labelled **unofficial** and uses **no Microsoft logos**
- [ ] Confirmed all questions are original (none copied from real exams)
