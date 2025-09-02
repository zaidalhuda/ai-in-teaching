# AI in Teaching @ Stirling College, Chengdu University
*A step‑by‑step teaching guide for Data Science, Digital Media, and Sports — with Stirling policies, ready‑to‑run activities, and links to trusted AI tools.*

---

## 0) Quick Start (for busy weeks)
1. **Pick a module goal** (e.g., “students compare two regressors on a noisy dataset”).
2. **Choose the AI support mode**: brainstorm → outline → draft → critique → refine (never “write it for me”).  
3. **Add a process log**: require students to paste prompts, iterations, and citations in an appendix.
4. **Use a mini‑viva** (3–5 min) to check understanding.
5. **Mark for process + product** using the rubric snippets below.
6. **Declare AI use** using the template in the *Academic Integrity* section.

---

## 1) Ethical AI & Local Policy (Stirling summary)

- **Use AI ethically and transparently**: students may use AI for ideation, planning, summarising, debugging, and critique if permitted by the assignment; they must **acknowledge** all AI assistance. Misuse is handled under academic misconduct.  
- **Assessment design**: integrate AI where it surfaces thinking (e.g., *critique an AI answer*, *compare to sources*, *improve with rationale*). **Avoid detectors** as proof of misconduct; focus on evidence of learning and oral checks.  
- **Module example – SPSU813 (Understanding Global Sport)**: AI may support study tasks (planning, summarising, proofreading), **not** generate final answers; always **cite AI** and **verify** claims.
- **Submission**: coursework normally via the **VLE** (https://vle.zycdu.net) with a receipt.  
- **Feedback**: formal feedback is normally due within **15 working days**.  
- **Extensions**: coursework extensions up to **7 days** (14 for dissertations) for approved reasons; late submissions lose **3 marks/day** (to 7 days).  
- **Attendance**: absence from **>⅓** prescribed classes (or missing mandatory classes) may **cap the module at 40**.  
- **Progression & classification (concise)**: minimum credits to progress — **80 (Y1)**, **200 (Y2)**, **320 (Y3)**; classification uses **Y3–4**, excludes lowest **20 credits**, rounds weighted average, with boundaries **70/60/50/40** and a **predominance rule**.

> Always check the official Stirling pages for the latest regulations and updates.

---

## 2) How to use this README
- Adopt the **lesson recipes** for your major below.
- Copy an **assignment brief** template and tune the allowed AI support.
- Add a **process log** requirement (prompts, drafts, tools, citations).
- Use the **rubric snippets** to grade consistently across modules.
- Attach the **AI declaration** (per‑student).

---

## 3) Major‑by‑Major Teaching Recipes

### A) Data Science
**Programme alignment (core themes):** Python/Java; SQL & NoSQL (MongoDB, Neo4J); Hadoop/Spark; ML & DL (NLP/CV); Data Strategy; UX; Security; 60‑credit Honours Project.

**Starter activities**
- *Rapid concept warm‑up (10 min):* Define **supervised learning** with **reference + example**; list assumptions and role of labels; post via Mentimeter.
- *Mini simulation lab (35 min):* Compare **Linear Regression vs Decision Tree Regression** on a small dataset; interpret MAE/R²; propose improvements (features, CV, regularisation).
- *Smart literature scan (20–30 min):* From a target paper, extract: question, method, variables (IV/DV), results, limitations; then find **conflicting papers** and contrast.
- *Ethics checkpoint (10 min):* data protection, bias, explainability; 3 bullet mitigations.

**Suggested tools**  
Data & ML: NumPy (https://numpy.org), pandas (https://pandas.pydata.org), scikit‑learn (https://scikit-learn.org), Jupyter (https://jupyter.org), Weka (https://www.cs.waikato.ac.nz/ml/weka/), TensorFlow (https://www.tensorflow.org), PyTorch (https://pytorch.org).  
Data viz: Matplotlib (https://matplotlib.org), Plotly (https://plotly.com).  
Databases: MySQL (https://www.mysql.com), MongoDB (https://www.mongodb.com), Neo4j (https://neo4j.com).  
Big data: Hadoop (https://hadoop.apache.org), Spark (https://spark.apache.org).  
Coding assistants: GitHub Copilot (https://github.com/features/copilot), ChatGPT (https://chat.openai.com).

**Assignment brief (example)**  
> *Goal:* Build, explain, and evaluate a model that predicts bicycle demand from weather + calendar data.  
> *Allowed AI:* brainstorming, outline, code review, bug hints, literature pointers. **Not allowed:** AI‑written report or final code segments without attribution.  
> *Deliverables:* (1) Notebook; (2) 1200‑word report; (3) **Process log** (prompts, drafts, tools, citations); (4) 4‑min viva.  
> *Marking:* product 60 (accuracy, clarity, evidence), process 30 (reproducibility, log quality), oral 10.

**Rubric snippet (DS)**  
- Excellent: model well‑tuned; clear feature rationale; reproducible pipeline; uncertainty & ethics addressed; process log complete and critical.  
- Pass: working model; basic validation; readable code; process log lists steps.  
- Weak: metrics cherry‑picked; no CV; unexplained code; missing process evidence.

---

### B) Digital Media
**Focus:** UX/human‑computer interaction; multimedia production; generative assets with clear rights & provenance; accessibility.

**Starter activities**
- *Storyboard remix (20 min):* AI generates **three alternative story beats**; students pick one and produce a quick animatic; reflect on tone, pacing, and audience.
- *Alt‑text studio (15 min):* Improve auto‑generated alt‑text for 5 assets; check WCAG clarity.
- *Ethical brief (15 min):* For any gen‑image/video asset: state **prompt, source model, license, editing**; add a **provenance tag** in credits.

**Suggested tools**  
Design & motion: Figma (https://www.figma.com), Photopea (https://www.photopea.com), DaVinci Resolve (https://www.blackmagicdesign.com/products/davinciresolve), Runway (https://runwayml.com).  
Audio: Audacity (https://www.audacityteam.org), Auphonic (https://auphonic.com).  
Accessibility: WAVE (https://wave.webaim.org).  
Scripting/assistants: ChatGPT (https://chat.openai.com), Claude (https://claude.ai), Perplexity (https://www.perplexity.ai).

**Mini‑brief (DM)**  
> Produce a 30‑sec motion teaser for a campus event. **Allow AI** for idea boards and rough voiceover; **forbid** AI‑generated final script/footage unless explicitly credited and rights cleared. Ship with **asset log** + **alt‑text pack**.

---

### C) Sports
**Focus:** global sport context; policy; analytics for performance & participation; ethics of data from wearables and minors.

**Starter activities**
- *Policy snapshot (20 min):* Compare **two national policies** on grassroots sport; summarise differences and likely outcomes.
- *KPI mini‑dashboard (30 min):* Build a simple pandas or spreadsheet dashboard for participation metrics; discuss data quality & sampling bias.
- *Tech audit (15 min):* Evaluate a wearable’s privacy/accuracy trade‑offs; propose safer data practices.

**Suggested tools**  
Analytics: pandas (https://pandas.pydata.org), Google Sheets (https://www.google.com/sheets/about/), Flourish (https://flourish.studio).  
Sport research: OECD education stats (https://stats.oecd.org), WHO (https://www.who.int/data).  
Assistants: Perplexity (https://www.perplexity.ai), ChatGPT (https://chat.openai.com).

**Mini‑brief (Sports)**  
> Write a 1000‑word policy memo on increasing student participation using **two evidence‑based levers**; include a one‑page KPI dashboard; **declare** any AI assistance.

---

## 4) Academic Integrity Toolkit

**What must be cited/acknowledged**
- All **AI tools** used (name, version/date, URL), with **exact prompts** and a 1–2 line reflection per major change.  
- All datasets, code snippets, images/audio/video (with license).  
- Recommended referencing style: **IEEE**; keep direct quotations **≤10%**; prefer paraphrase with citation.

**AI Use Declaration (paste into appendix)**
```
I used the following AI tools during this assignment: <tool, version/date>. 
Purpose(s): <brainstorming / outline / debugging / critique / translation / proofreading>.
Sample prompts & excerpts are included in my process log. I verified all facts and take full responsibility for the content.
Signature & date:
```

**Signs of healthy use**
- Process log shows iteration, verification, and cross‑checking with primary sources.  
- Student can explain decisions in a viva without the tool.

**Not acceptable**
- AI writes the final answer/code unacknowledged; fabricated citations; unverified claims; bypassing assignment rules.

---

## 5) Lesson Recipes (ready to run)

### Recipe 1 — “Supervised Learning in 10” (DS, Sports Analytics)
**Objective:** students articulate a precise definition with assumptions and give a referenced example.  
**Flow:** 3’ pair search → 5’ write & cite → 2’ share to Mentimeter → 5’ plenary contrasts.  
**Evidence:** screenshots + references in appendix.

### Recipe 2 — “Two Regressors Enter…” (DS)
**Objective:** compare Linear Regression vs Decision Tree on the same dataset.  
**Flow:** 5’ setup → 20’ model & metrics → 10’ improvement ideas → 5’ share.  
**Evidence:** notebook + 150‑word rationale + process log.

### Recipe 3 — “Literature Contrast” (All majors)
**Objective:** extract method/variables/findings; locate **contradictory** evidence.  
**Flow:** 10’ extract → 10’ counter‑search → 10’ contrast table.  
**Evidence:** one‑page matrix with citations.

### Recipe 4 — “Critical Design Sprint: Health Tech” (All majors)
**Objective:** design a viable concept with ethics & data minimisation built‑in.  
**Flow:** 10’ scope + persona → 10’ USP/value prop → 10’ risk/mitigation.  
**Evidence:** one‑pager + pitch.

---

## 6) Rubric Snippets (drop‑in)

**Process (common, 30%)**: evidence of iteration; verification; citations; clear AI declaration.  
**Product (60%)**: accuracy/quality; clarity; relevance; originality within rules.  
**Oral (10%)**: clarity; command of decisions; integrity of explanation.

*(Adjust weightings per module.)*

---

## 7) Programme Alignment (Data Science quick view)

- **Year 1:** Introduction to Computing Science · Programming & UI Design · English for Academic Purposes · General English · Personal Academic Study Skills · Integrated Project  
- **Year 2:** Understanding Global Sport (shared) · Database Principles & Applications · Scripting for Data Science · NoSQL & Data Warehousing · Introduction to Data Science · Practical Statistics  
- **Year 3:** Introduction to Machine Learning · UX Design · Sports Policy · NLP & Computer Vision · Data Strategy · Programming Language Paradigms  
- **Year 4:** Data Science Applications · Artificial Intelligence (half) · Cyber Security (half) · Distributed Data Science Systems · **Computing Science Project (60 credits)**

> Map your assignment LOs to **SCQF** level descriptors and module descriptors when designing AI‑supported tasks.

---

## 8) References (official & tools)

### Official (Stirling)
- Programme Handbook — BSc (Hons) Data Science (Stirling College, Chengdu University)
- University of Stirling regulations and policies (assessment & award of credit; degree classifications; attendance & engagement; assessment policy & procedure)
- Student Charter; Equality, Diversity & Inclusion
- Extenuating Circumstances guidance
- VLE (https://vle.zycdu.net); Library Search (https://librarysearch.stir.ac.uk)

### Tools & platforms
- NumPy — https://numpy.org  
- pandas — https://pandas.pydata.org  
- scikit‑learn — https://scikit-learn.org  
- Jupyter — https://jupyter.org  
- TensorFlow — https://www.tensorflow.org  
- PyTorch — https://pytorch.org  
- Weka — https://www.cs.waikato.ac.nz/ml/weka/  
- Matplotlib — https://matplotlib.org  
- Plotly — https://plotly.com  
- MySQL — https://www.mysql.com  
- MongoDB — https://www.mongodb.com  
- Neo4j — https://neo4j.com  
- Hadoop — https://hadoop.apache.org  
- Spark — https://spark.apache.org  
- Figma — https://www.figma.com  
- Photopea — https://www.photopea.com  
- DaVinci Resolve — https://www.blackmagicdesign.com/products/davinciresolve  
- Runway — https://runwayml.com  
- Audacity — https://www.audacityteam.org  
- Auphonic — https://auphonic.com  
- WAVE — https://wave.webaim.org  
- Google Sheets — https://www.google.com/sheets/about/  
- Flourish — https://flourish.studio  
- Perplexity — https://www.perplexity.ai  
- ChatGPT — https://chat.openai.com  
- GitHub Copilot — https://github.com/features/copilot

---

### Changelog
- **2025‑09‑02** — Aligned with Stirling Data Science handbook and Autumn 2024 AI workshop; added policy summary, lesson recipes, and declaration template.
