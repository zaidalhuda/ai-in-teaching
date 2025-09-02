# AI in Teaching 

A practical, step-by-step guide to help teachers plan **responsible, effective AI use** in courses — from policy and prompting to lessons, assessment, accessibility, and risk. This version includes **many concrete examples** you can copy‑paste into teaching.

---

## Quick Start

1) **Pick one main assistant** you’ll use this term  
   Recommended: [ChatGPT](https://chat.openai.com), [Claude](https://claude.ai), [Gemini](https://gemini.google.com), [Perplexity](https://www.perplexity.ai).  
   (Choose one to reduce cognitive load; you can compare later.)

2) **Publish a short Class AI Use Agreement** (template below)  
   State where AI is **allowed / limited / not allowed**, how to **acknowledge AI use**, and privacy basics.

3) **Plan one AI-supported lesson** (Module 4)  
   Use AI for ideation, materials, and differentiation — then **verify** and **cite** sources.

---

## Contents

- [Module 1 — Responsible, Human-Centred AI Use](#module-1--responsible-human-centred-ai-use)  
- [Module 2 — Choose & Configure Your Main Assistant](#module-2--choose--configure-your-main-assistant)  
- [Module 3 — Prompting Patterns (Cheatsheet + Library)](#module-3--prompting-patterns-cheatsheet--library)  
- [Module 4 — Lesson Planning with AI (Workflow + Examples)](#module-4--lesson-planning-with-ai-workflow--examples)  
- [Module 5 — Assessment, Integrity & the AI Assessment Scale](#module-5--assessment-integrity--the-ai-assessment-scale)  
- [Module 6 — Accessibility & Inclusive Design](#module-6--accessibility--inclusive-design)  
- [Module 7 — Data Privacy & Risk Awareness](#module-7--data-privacy--risk-awareness)  
- [Module 8 — Build a Course-Specific Custom GPT (Optional)](#module-8--build-a-course-specific-custom-gpt-optional)  
- [Tools Directory (Teacher-Friendly Picks)](#tools-directory-teacher-friendly-picks)  
- [Discipline Spotlights (Concrete Use Cases)](#discipline-spotlights-concrete-use-cases)  
- [Policy Templates & Examples](#policy-templates--examples)  
- [AI Tool Adoption Rubric](#ai-tool-adoption-rubric)  
- [Implementation Timeline (Faculty PD)](#implementation-timeline-faculty-pd)  
- [Custom GPT Instruction Template](#custom-gpt-instruction-template)  
- [Acknowledging AI Assistance](#acknowledging-ai-assistance)  
- [FAQ](#faq)  
- [Contributing & License](#contributing--license)  
- [References](#references)  
- [Changelog](#changelog)

---

## Module 1 — Responsible, Human-Centred AI Use

**Principles**
- Keep **human agency** central; prioritize learning, not automation for its own sake.
- Provide **opt-outs** and human alternatives when AI assists decisions.
- Be transparent about **what AI can/can’t do** and its limitations.

**Class AI Use Agreement (Syllabus snippet — copy/adapt)**
> **Purpose**: AI can support brainstorming, drafting, and practice. It does **not** replace critical thinking or original work.  
> **Where allowed**: [e.g., ideation, outline, practice quizzes]. **Where limited**: [e.g., editing only]. **Not allowed**: [e.g., take-home exam answers].  
> **Privacy**: Do **not** upload personal/student data or assessments with PII.  
> **Quality & Bias**: Verify facts, check sources, and reflect on bias.  
> **Credit**: When AI is used, include an “AI Assistance” note (see section below).  
> **Equity**: Alternative non-AI paths are available for all required tasks.  
> **Opt-out**: Students may choose human alternatives for AI-enabled features.

---

## Module 2 — Choose & Configure Your Main Assistant

Pick one: **ChatGPT**, **Claude**, **Gemini**, or **Perplexity**. Then **configure** it:

- Set audience and level (e.g., “first-year students”), expected output formats, and tone.  
- Create a **profile prompt** that the assistant sees every time (your teaching context, constraints, and formatting needs).  
- Turn on **web citations** (if available), and ask for a short “limitations & bias” note in teacher outputs.

**Profile prompt (copy‑paste and edit)**
```
You are a teaching assistant helping [level] students at Stirling College (Chengdu University).
Default outputs: bullet points + short paragraphs, clear headings, tables when useful.
Always include sources/links for factual claims and a brief "limitations & bias" note for teacher-facing material.
Avoid personal data; never request or process PII. Offer differentiated outputs (basic/standard/challenge).
```

---

## Module 3 — Prompting Patterns (Cheatsheet + Library)

**Prompt Skeleton**
```
Role: You are a [subject] lecturer helping [level] students at Stirling College.
Task: [create X], aligned to [module outcomes].
Audience/Tone: [plain, accessible, bilingual if needed].
Constraints: [time limit, word count, sources to cite, region-specific examples].
Non-goals: [what to avoid/omit].
Quality checks: [fact-checking, bias check, add limitations note].
Output format: [markdown/slide outline/table].
```

**Reusable techniques**
- **Zero-shot** (clear instruction, no examples)  
- **Few-shot** (show 1–3 examples to copy style)  
- **Meta-prompting** (give a schema/steps to follow)  
- **Self-consistency** (ask for 3 variants, then a final)  
- **Generate-knowledge → Answer** (make a bullet fact list, *then* answer)  
- **Critique & revise** (ask the model to critique its own draft, then improve)

**Prompt Library (copy‑paste)**

1) *Lesson Outline (90 minutes)*  
```
Create a 90‑minute lesson plan on [topic] for [level], aligned to these outcomes: [paste].
Include: timings, activities, checks for understanding, materials list, exit ticket.
Differentiate with basic/standard/challenge tasks, and add a bilingual glossary (EN/中文).
Add source links for any facts and a short "limitations & bias" note for teachers.
```

2) *Socratic Questions*  
```
Generate 10 Socratic questions that progressively lead students to [concept].
Label by level (starter/core/extension). Include likely misconceptions and how to address them.
```

3) *Quiz + Rationales*  
```
Create a 6‑question mixed quiz (MCQ + short answer) on [topic] with an answer key and short rationales.
Tag each question with Bloom’s level and common distractors.
```

4) *Differentiated Reading*  
```
Write two versions of a reading on [topic]:
- 300 words (simple), - 600 words (standard). Add a 10‑term glossary with CEFR level.
```

5) *Rubric Builder*  
```
Make a 4‑level analytic rubric for [task], aligned to [outcomes]. Criteria: [list].
Add examples for each performance level. Provide a 1‑minute oral defense prompt.
```

6) *Code Lab (step‑check)*  
```
Design a short lab where students implement [algorithm] in [language].
Provide step checks: inputs/expected outputs after each step, and 3 common bugs with fixes.
```

7) *ELL/ESP Speaking Drills*  
```
Create 5 short role‑plays for [context], targeting [vocab/grammar].
Include teacher notes: prompts to elicit, error‑correction strategies, and cultural notes (EN/中文).
```

---

## Module 4 — Lesson Planning with AI (Workflow + Examples)

**Outcome‑first workflow (about 60 minutes)**
1) Paste module outcomes + week topic; ask for a **90‑min active‑learning lesson** with checks for understanding.  
2) Generate **materials**: slides outline, short reading, exit ticket.  
3) **Differentiate**: request basic/standard/challenge versions and multilingual glossary.  
4) **Verification pass**: require source links; then manually **spot‑check**.

**Example: Week 3 – Academic Writing (Paraphrasing & Citation)**  
- *Activities*: AI‑generated practice pairs (original → paraphrase → teacher feedback checklist), peer review using a rubric, 5‑item exit ticket.  
- *Materials*: Two readings (300/600 words) with vocabulary list; MLA/APA citation mini‑guide; academic integrity reminder.  
- *Assessment*: In‑class paraphrase with **source attached** + reflection (“What did AI help with? What did you change?”).

**Example: Calculus – Product Rule**  
- Warm‑up retrieval (derivative basics), guided examples with **error‑spotting**, partner practice set with increasing difficulty, mini‑whiteboard checks, and a 2‑minute oral explanation prompt.

**Example: CS – Sorting Algorithms Lab**  
- Implement selection sort, then compare to built‑in sort on random arrays; include **step checks** and 3 common bug patterns; reflection on time complexity.

---

## Module 5 — Assessment, Integrity & the AI Assessment Scale

Use an **AI Assessment Scale** to clarify where/when AI fits in assessment (Levels 1–5 from “No AI” → “AI as co‑pilot”).

**Examples by level**
- **Level 1 (No AI)**: In‑class closed‑book quiz; oral micro‑viva on homework logic.  
- **Level 2 (AI limited)**: AI allowed for **outline only**; submit outline with final essay and a change log.  
- **Level 3 (AI permitted)**: Drafting with AI allowed; student must provide **process evidence** (prompts, selected outputs, revisions).  
- **Level 4 (AI partner)**: Student co‑creates with AI; graded on **prompt quality**, **verification**, and **reflection**.  
- **Level 5 (AI as toolchain)**: Project journals track use of multiple tools; emphasis on design decisions and human judgment.

**Integrity without detectors**
- Collect **process artifacts** (notes, drafts, version history).  
- Use **oral verifications** (1–3 minute defenses).  
- Design **context‑specific prompts** that require class‑specific data, diagrams, or local examples.  
- Make **rubrics** value reasoning, evidence, and reflection, not just final wording.

---

## Module 6 — Accessibility & Inclusive Design

- Use AI to **adapt** readings (simplify language, add examples, bilingual glossaries) and generate **multiple means of engagement**.  
- Follow **UDL (Universal Design for Learning)** and ensure equitable access when adopting tools.  
- Ask AI to draft **alt text** and **transcripts**, then review.

**Alt‑Text Prompt**
```
Write concise, descriptive alt text (max 125 chars) for this image: [paste brief description].
Include the pedagogical intent (what learners should notice).
```

---

## Module 7 — Data Privacy & Risk Awareness

- Define AI/GenAI in **plain language** for students and staff.  
- Avoid uploading any **student‑identifiable data**; keep custom assistants **private**.  
- Review third‑party tool **data policies**, **retention**, and **model‑training** settings.  
- Provide **opt‑out** paths and equivalent human alternatives.

**Privacy Checklist (copy‑paste)**
- [ ] No PII/student work uploaded to public tools  
- [ ] Tool vendor’s data use/retention reviewed  
- [ ] Access limited to staff who need it; revoke when not needed  
- [ ] Opt‑out and alternatives communicated in syllabus/assignment  
- [ ] School storage/backups follow policy

---

## Module 8 — Build a Course-Specific Custom GPT (Optional)

- Upload only materials you **own** or can share (syllabus, rubrics, anonymized handouts).  
- Write instructions that reflect course standards, age level, and inquiry‑based learning.  
- Keep it **private**; disclose if students will interact with it; provide **human alternatives** (opt‑out).

**Seed files to include**
- Syllabus, weekly outcomes, exemplar answers (teacher‑only), rubrics, style guides, frequent misconceptions, bilingual glossary.

---

## Tools Directory (Teacher-Friendly Picks)

**Chat & research**
- [ChatGPT](https://chat.openai.com) · [Claude](https://claude.ai) · [Gemini](https://gemini.google.com) · [Perplexity](https://www.perplexity.ai)

**Lesson planning / class utilities**
- [MagicSchool AI](https://www.magicschool.ai) · [Eduaide](https://www.eduaide.ai) · [Brisk Teaching](https://www.briskteaching.com) · [Curipod](https://curipod.com) · [Quizizz AI](https://quizizz.com) · [NotebookLM](https://notebooklm.google/) · [Canva](https://www.canva.com)

**Extra research helpers**
- [Elicit](https://elicit.org) · [Hugging Face Chat](https://huggingface.co/chat)

**Image/visual**
- [Canva](https://www.canva.com) · [DALL·E](https://openai.com/research/dall-e) · [Midjourney](https://www.midjourney.com)

> Use the **AI Tool Adoption Rubric** below before adding new tools to your course.

---

## Discipline Spotlights (Concrete Use Cases)

**1) English Composition (Year 1)**  
- *AI‑assisted task*: generate **outline options** for a compare/contrast essay; students choose and revise.  
- *Process evidence*: include AI prompts, 1 draft with tracked changes, and a 150‑word reflection.  
- *Rubric highlights*: thesis clarity, evidence integration, citation accuracy, reflection quality.

**2) Mathematics (Calculus I – Product Rule)**  
- *Warm‑up*: retrieval quiz (no AI).  
- *Practice*: AI generates **errorful** examples; students fix and explain.  
- *Exit ticket*: 3 problems mixing symbolic and word problems.

**3) Computer Science (Intro Python)**  
- *Lab*: implement search on a list; **step checks** after each function.  
- *Debugging*: ask AI to produce **3 buggy snippets**; students diagnose with tests.

**4) Business (Marketing)**  
- *Case*: AI drafts two customer personas for Chengdu context; students validate with real data sources.  
- *Assessment*: pitch deck with **sources** and annotated AI contributions.

**5) Health/Nursing (Ethics & Communication)**  
- *Role‑play*: difficult patient conversation scripts (EN/中文).  
- *Reflection*: students critique AI’s script for empathy, clarity, and safety.

**6) Engineering (Materials Lab)**  
- *Pre‑lab*: AI generates hazard checklist + measurement table.  
- *Report*: students submit raw data, calculations, and **method diagram** drawn by themselves.

**7) EFL / ESP (Speaking)**  
- *Drills*: role‑plays for hotel check‑in / hospital triage; include pronunciation tips.  
- *Assessment*: recorded dialogue + short oral defense of vocabulary choices.

**8) Art & Design (Visual Communication)**  
- *Brief*: AI helps create a style board and constraint list; students produce original work.  
- *Studio critique*: rubric emphasizes composition decisions and iteration notes.

---

## Policy Templates & Examples

### A) Syllabus AI Use Statement (copy/adapt)

- **Allowed**: brainstorming ideas, outlines, language refinement;  
- **Limited**: summarizing sources *with citations*;  
- **Not allowed**: generating final assignment text, take‑home exam answers.  
- **Privacy**: do not upload personal data or identifiable student work.  
- **Acknowledgement**: include an “AI Assistance” note in submissions.  
- **Opt‑out**: human alternatives available for any required AI feature.

### B) By-Assignment Examples

- **Reading response**: AI allowed to **outline** and **clarify**, student writes final text; attach outline + reflection.  
- **Lab report**: AI allowed to **format** and **grammar‑check**; raw data analysis and discussion are student‑authored.  
- **Oral viva**: AI may help generate **practice questions**; exam is in‑person, AI‑free (controlled).

### C) Classroom Practice Ideas
- Generate exercises, adapt texts to levels/ages, and pilot feedback reports; evaluate quality and limits; revert to **handwritten** or **in‑class** when needed.  
- Use AI‑generated texts as objects to **edit, verify sources, change register**, and **critique**.

---

## AI Tool Adoption Rubric

Score prospective tools (1–5) on:

1) **Accuracy & Learning Value** (aligns with outcomes; improves engagement/understanding)  
2) **Transparency** (explains limitations; shows sources when relevant)  
3) **Privacy & Data Minimization** (no PII required; clear data practices; retention controls)  
4) **Accessibility/UDL** (works with AT; multilingual support; low‑bandwidth options)  
5) **Equity & Inclusion** (doesn’t disadvantage subgroups; supports diverse languages/cultures)  
6) **Opt‑out Availability** (human alternative for any AI‑enabled decision or feature)

**Example (filled)**  
| Criterion | Score (1–5) | Evidence/Notes |
|---|:--:|---|
| Accuracy & Learning Value | 4 | Quiz generator aligned to outcomes; teacher review needed |
| Transparency | 3 | Gives links but some are generic |
| Privacy & Minimization | 4 | Opt‑out of training; no account needed for students |
| Accessibility/UDL | 3 | Works on mobile; needs better screen‑reader support |
| Equity & Inclusion | 4 | Multilingual; examples can be localized |
| Opt‑out Availability | 5 | Full human‑only path available |

---

## Implementation Timeline (Faculty PD)

**Week 0** — Share this guide; collect course outcomes; choose 1 assistant tool.  
**Week 1** — Publish Class AI Use Statement; run a 45‑min prompting workshop.  
**Week 2** — Pilot 1 AI‑supported lesson; gather student feedback.  
**Week 3** — Adjust policy; design 1 assessment with clear AI level; create rubrics.  
**Week 4+** — Build a small prompt library per module; consider a private course assistant.

---

## Custom GPT Instruction Template

Paste this into your assistant’s “system/instructions”:

```
You are a course assistant for [Course Name] at Stirling College (Chengdu University).
Goals: Support [level] students to meet [learning outcomes].
Do:
- Use plain language; scaffold explanations; offer structured outlines and examples.
- Ask one clarifying question only if essential to meet the request.
- Provide sources/links for factual claims; flag uncertainty and common misconceptions.
- Offer differentiated outputs (basic/standard/challenge) when preparing materials.
- Respect privacy: never request or process PII or student-identifiable work.
- Include a short “limitations & bias check” note for teacher-facing outputs.

Don’t:
- Produce final graded work or complete summative assessments.
- Fabricate citations or statistics; if unsure, say so and propose how to verify.
- Store or reuse any user content beyond the current session.

Formatting defaults:
- Use markdown with headings, bullet lists, and tables when helpful.
- End teacher materials with a quick verification checklist.

Ethics & Safety:
- Avoid harmful/biased content; offer inclusive, culturally aware examples.
- Provide human alternatives for any AI-enabled suggestion (opt-out).
```

---

## Acknowledging AI Assistance

Students (and staff) should credit AI support succinctly, e.g.:

> “**AI Assistance**: ChatGPT used for brainstorming structure and drafting a study plan. Sources were verified and all writing was reviewed and revised by the author.”

This encourages transparency without overstating reliance.

---

## FAQ

**Q1: Should I use AI detectors?**  
A: Use with extreme caution; false positives/negatives are common. Focus on **process evidence**, **oral checks**, and **context‑specific tasks** instead.

**Q2: Can students upload data to tools?**  
A: Avoid uploading PII or identifiable student work to public tools. Prefer local files or institutionally approved platforms.

**Q3: How do I grade AI‑assisted work fairly?**  
A: Make AI permissions explicit per assignment; grade on reasoning, evidence, and reflection. Require a brief “AI Assistance” note.

**Q4: What about accessibility?**  
A: Generate alternative formats (summaries, audio transcripts, bilingual glossaries). Test with screen readers when possible.

---

## Contributing & License

Pull requests welcome (examples, prompt libraries, discipline‑specific lesson plans).  
License: **CC BY 4.0** unless otherwise noted.

---

## References

- **UNESCO – Guidance for Generative AI in Education & Research (2023)** — human‑centred approach; inclusion, equity, and linguistic diversity; policy measures for GenAI in education. https://www.unesco.org/en/articles/guidance-generative-ai-education-and-research
- **U.S. Dept. of Education — AI in Teaching & Learning (Toolkit, 2024)** — plain‑language definitions, privacy/civil‑rights considerations, examples for leaders and teachers. https://tech.ed.gov/ai/
- **TeachAI / Code.org — AI Guidance for Schools (living resource)** — governance, assessment, classroom practice. https://teachai.org/
- **UDL Guidelines (CAST)** — design for learner variability and accessibility. https://udlguidelines.cast.org/
- **Common Sense Education — Privacy & Security** — K‑12 privacy overviews and tool reviews. https://commonsense.org/education/topics/privacy

---

## Changelog

- **v1.1 (expanded)** — Added prompt library, discipline spotlights, rubric example, PD timeline, FAQ.  
- **v1.0** — Initial guide with modules, tools, templates.
