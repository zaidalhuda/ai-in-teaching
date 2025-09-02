![AI in Teaching Banner](banner.svg)

# AI in Teaching @ Stirling College (Chengdu University)
**Majors focus:** Data Science · Digital Media · Sports

A practical, step-by-step guide to help teachers use AI responsibly and effectively in **all three Stirling College majors**. Everything is organized with concrete, copy-paste examples, prompts, and assignments tailored to **Data Science**, **Digital Media**, and **Sports** (analytics, coaching & management).

---

## Quick Start

1) **Pick one main assistant** you'll use this term  
   Recommended: [ChatGPT](https://chat.openai.com/) · [Claude](https://claude.ai/) · [Gemini](https://gemini.google.com/) · [Perplexity](https://www.perplexity.ai/)

2) **Publish a short Class AI Use Agreement** (template below)  
   Clarify where AI is **allowed / limited / not allowed**, how to **acknowledge AI**, and privacy basics.

3) **Pilot one AI-supported lesson** this week (Module 4)  
   Use AI for ideation, materials, and differentiation - then **verify** and **cite** sources.

> **Stirling alignment:** Focus on academic integrity, transparency about AI use, and process evidence—detectors are unreliable; use oral checks and artifacts instead.

---

## Contents

- [Module 1 - Responsible, Human-Centred AI Use](#module-1--responsible-humancentred-ai-use)  
- [Module 2 - Choose & Configure Your Assistant](#module-2--choose--configure-your-assistant)  
- [Module 3 - Prompting Patterns (Cheatsheet + Library)](#module-3--prompting-patterns-cheatsheet--library)  
- [Module 4 - Lesson Planning (Workflow + Examples)](#module-4--lesson-planning-workflow--examples)  
- [Module 5 - Assessment, Integrity & AI Levels](#module-5--assessment-integrity--ai-levels)  
- [Module 6 - Accessibility & Inclusive Design](#module-6--accessibility--inclusive-design)  
- [Module 7 - Data Privacy & Risk (per major)](#module-7--data-privacy--risk-per-major)  
- [Module 8 - Custom Course Assistant](#module-8--custom-course-assistant-optional)  
- [Module 9 - Advanced Prompting Techniques](#module-9--advanced-prompting-techniques)
- [Tools by Major](#tools-by-major)  
- [Capstone Ideas by Major](#capstone-ideas-by-major)  
- [Policy Templates & Examples](#policy-templates--examples)   
- [Custom GPT Instruction Template](#custom-gpt-instruction-template)  
- [Acknowledging AI Assistance](#acknowledging-ai-assistance)   
- [References](#references)

---

## Module 1 - Responsible, Human-Centred AI Use

**Principles**
- Keep **human agency** central; AI assists learning but does not replace it.
- Provide **opt-outs** and alternative human paths for any AI-enabled activity.
- Be transparent about **capabilities, limits, bias, and verification**.
- Do **not** upload personal or student-identifiable data into public tools.
- **Policy note (Stirling):** Set expectations by assignment; require students to **acknowledge AI use** and submit **process evidence** where AI is allowed.

**Class AI Use Agreement (Syllabus snippet - copy/adapt)**  
> **Purpose**: AI supports brainstorming, drafting, practice, and feedback; it does **not** replace critical thinking or original work.  
> **Allowed**: ideation, outlines, feedback on clarity, language refinement; tool-based practice (see major-specific allowances below).  
> **Limited**: summarising sources *with citations*; code or design suggestions that require human review.  
> **Not allowed**: final graded work written by AI; uploading assessment briefs or student PII to public tools.  
> **Credit**: Include an "AI Assistance" note in submissions.  
> **Equity**: Non-AI routes are available for every required task.  
> **Review**: Policy will be revisited mid-semester.

---

## Module 2 - Choose & Configure Your Assistant

Pick one: [ChatGPT](https://chat.openai.com/), [Claude](https://claude.ai/), [Gemini](https://gemini.google.com/), or [Perplexity](https://www.perplexity.ai/). Then configure it:

- Set **audience/level** ("first-year", "capstone"), **format defaults** (tables, bullet lists), and **tone**.  
- Add a **profile prompt** that states your course context, output format, and a requirement for **sources + limitations note** in teacher outputs.  
- For technical courses, enable **code-friendly** responses (markdown code blocks). For digital media, allow **style constraints**. For sports, request **ethics/privacy reminders**.

### **Why Claude for Education?**

Claude excels at:
- **Long-form content creation** - detailed lesson plans, comprehensive rubrics, extensive reading materials
- **Document analysis** - reviewing student work, analyzing research papers, processing course materials
- **Iterative refinement** - multi-turn conversations to perfect lesson plans and assignments
- **Structured outputs** - consistent formatting for syllabi, rubrics, and assessment materials
- **Code review and debugging** - particularly strong for Data Science courses
- **Ethical reasoning** - built-in consideration of bias, fairness, and responsible AI use
- **Citation accuracy** - better at providing and formatting proper academic citations
- **Multi-language support** - helpful for bilingual glossaries and international students

**Profile prompt (copy-edit)**
```
You are a teaching assistant for [course] in the [Data Science / Digital Media / Sports] major at Stirling College (Chengdu University).
Default outputs: clear headings, bullet points, tables when useful. Provide sources/links for factual claims and a brief "limitations & bias" note for teacher-facing material.
Never request or process PII. Offer differentiated outputs (basic/standard/challenge). When generating code or design prompts, add a verification checklist.
For iterative tasks: Ask if I want to refine any specific aspect before moving to the next step.
```

---

## Module 3 - Prompting Patterns (Cheatsheet + Library)

**Prompt Skeleton**
```
Role: You are a [subject] lecturer helping [level] students at Stirling College.
Task: [create X], aligned to [module outcomes].
Audience/Tone: [plain, accessible, bilingual if needed].
Constraints: [time limit, word count, sources to cite, local examples].
Non-goals: [what to avoid].
Quality checks: [fact-check, add limitations/bias note].
Output format: [markdown/slide outline/table/code block/storyboard].
```

**Reusable techniques**
- **Few-shot style** (paste a short example to copy voice/format)  
- **Generate-facts → Answer** (facts list first, then response)  
- **Critique & improve** (ask for a critique pass, then revision)  
- **Self-consistency** (ask for 3 variants, then a final merged version)
- **Chain-of-thought** (ask AI to show reasoning steps)
- **Role-playing** (AI takes perspective of student, industry expert, etc.)

### **Expanded Prompt Library**

**General Teaching Prompts**

1) **90-min lesson outline**  
```
Create a 90-minute lesson on [topic] aligned to [outcomes] with timings, activities, checks for understanding, materials, and an exit ticket.
Differentiate tasks (basic/standard/challenge). Provide sources and a short "limitations & bias" note for teachers.
Include: 5-min warm-up, 3 main activities with transitions, formative assessment checkpoints, and wrap-up reflection.
```

2) **Socratic questions**  
```
Create 10 Socratic questions that guide students from intuitive understanding to formal reasoning about [concept]. 
Start with accessible, real-world connections and progress to abstract principles.
Include common misconceptions students might reveal through their answers.
Format as a progression: Questions 1-3 (activate prior knowledge), 4-7 (explore concept), 8-10 (synthesize and apply).
```

3) **Quiz + rationales**  
```
Create a 6-question mixed assessment (MCQ + short answer) on [topic] with:
- Complete answer key with 1-sentence rationales
- Bloom's taxonomy tags for each question
- Common wrong answers and why students choose them
- Estimated time per question
- Differentiated follow-up questions for different performance levels
```

**Assessment & Feedback Prompts**

4) **Rubric generator**
```
Create a detailed rubric for [assignment type] with:
- 4 performance levels (Exemplary, Proficient, Developing, Beginning)
- 5-6 criteria relevant to [learning outcomes]
- Specific, observable descriptors for each cell
- Point values and total scoring guide
- Self-assessment version for students
Include a "limitations & bias check" noting what this rubric might miss or unfairly emphasize.
```

5) **Personalized feedback generator**
```
Based on this assignment description: [paste assignment]
And these learning outcomes: [paste outcomes]
Create a template for giving constructive feedback that includes:
- 2 specific strengths to celebrate
- 1 area for growth with concrete next steps
- 1 question to promote deeper thinking
- Connection to course/program goals
Keep feedback encouraging and growth-focused.
```

6) **Peer review activity designer**
```
Design a structured peer review activity for [assignment] including:
- Clear instructions for reviewers (what to look for, how to give feedback)
- Review worksheet with specific questions
- Protocol for giving and receiving feedback
- Reflection questions for original authors
- Time allocation and classroom management tips
Make it work for [class size] students in [time limit].
```

**Differentiation & Accessibility Prompts**

7) **Multi-level content creator**
```
Take this core concept: [concept]
Create three versions:
- Foundation level: Essential understanding with concrete examples
- Standard level: Full concept with applications
- Extension level: Advanced connections and analysis
Each version should achieve the same learning outcome but through different pathways.
Include assessment criteria for each level.
```

8) **Universal design lesson adapter**
```
Adapt this lesson plan: [paste lesson] for students with diverse needs:
- Visual learners: diagrams, color coding, visual organizers
- Auditory learners: discussion, audio resources, verbal processing
- Kinesthetic learners: hands-on activities, movement, manipulation
- Students with attention challenges: chunk activities, built-in breaks
- English language learners: vocabulary support, visual aids, peer translation opportunities
Maintain the same learning objectives throughout.
```

**Engagement & Activity Prompts**

9) **Interactive activity generator**
```
Create an engaging 15-minute activity for [topic] that:
- Gets all students actively participating (not just volunteers)
- Checks understanding of [specific concept]
- Works in [classroom setup - lecture hall/lab/flexible space]
- Requires minimal prep and materials
- Includes a clear debrief/connection to broader learning
Provide step-by-step instructions and troubleshooting tips.
```

10) **Real-world connection maker**
```
For the topic [academic concept], create:
- 3 current, relevant real-world examples from different industries
- 1 local/regional case study relevant to our students
- Discussion questions connecting theory to practice
- Brief background context students need to understand each example
- Potential career connections for [major] students
```

**Subject-Specific Prompts by Major**

**Data Science Prompts**

11) **Dataset exploration guide**
```
Create a guided exploration worksheet for [dataset name/type] that helps students:
- Ask good initial questions about the data
- Identify potential data quality issues
- Formulate 3 hypotheses they could test
- Consider ethical implications of the data collection/use
- Plan appropriate visualizations
Include Python/R code snippets for common exploration tasks.
Include a "bias check" - what might this dataset be missing or overrepresenting?
```

12) **Model explanation activity**
```
Design an activity where students explain [ML algorithm] to different audiences:
- 5-year-old version (core intuition)
- Business stakeholder version (practical value, limitations)
- Technical peer version (mathematical foundation, parameters)
- Ethics board version (potential biases, failure modes)
Include evaluation criteria for each explanation type.
```

13) **Code review checklist generator**
```
Create a code review checklist for [assignment type - data cleaning/modeling/visualization] including:
- Technical correctness criteria
- Code style and documentation standards
- Reproducibility requirements
- Ethical considerations (bias, privacy, fairness)
- Performance and efficiency markers
Format as a student self-check and peer review tool.
```

**Digital Media Prompts**

14) **Creative brief generator**
```
Create a professional creative brief template for [project type] including:
- Client/audience analysis sections
- Technical specifications and constraints
- Style and tone guidelines
- Deliverables checklist
- Timeline and milestone markers
- Budget/resource considerations
- Success metrics and evaluation criteria
Make it industry-realistic but student-appropriate.
```

15) **Design critique framework**
```
Develop a structured critique protocol for [media type] projects that covers:
- Visual/aesthetic elements (composition, color, typography)
- Technical execution quality
- Conceptual strength and originality
- Audience appropriateness and accessibility
- Ethical considerations (representation, copyright, cultural sensitivity)
Include sentence starters to help students give constructive feedback.
```

16) **Portfolio development guide**
```
Create a step-by-step guide for students building their [media type] portfolio:
- Project selection criteria (diversity, quality, growth demonstration)
- Presentation format recommendations
- Artist statement template
- Technical documentation requirements
- Professional presentation tips
- Industry standards and expectations
- Online portfolio platform comparison
```

**Sports Analytics/Management Prompts**

17) **Performance analysis framework**
```
Design an analysis framework for [sport] performance that includes:
- Key performance indicators (KPIs) hierarchy
- Data collection methods and tools
- Statistical analysis approaches
- Visualization recommendations
- Contextual factors to consider (weather, opposition, stakes)
- Ethical guidelines for athlete data use
- Communication strategies for coaches vs. athletes vs. management
```

18) **Case study analyzer**
```
Create a case study analysis template for sports management scenarios covering:
- Stakeholder identification and interests
- Ethical considerations and conflicts
- Data privacy and consent issues
- Performance vs. wellbeing trade-offs
- Communication and decision-making processes
- Alternative solutions evaluation
- Implementation and monitoring plans
Include real examples from [specific sport/context].
```

**Research & Source Integration Prompts**

19) **Literature review organizer**
```
Help students organize research on [topic] by creating:
- Research question refinement guide
- Source evaluation criteria (credibility, relevance, recency)
- Citation and note-taking templates
- Synthesis frameworks for connecting multiple sources
- Gap identification strategies
- Bias detection questions for sources
- Academic writing integration techniques
```

20) **Fact-checking and verification guide**
```
Create a verification checklist for students evaluating [content type]:
- Source credibility indicators
- Cross-reference strategies
- Red flags for misinformation
- Primary vs. secondary source identification
- Statistical claim evaluation
- Expert consensus determination
- Update recency and relevance
Include practice examples with verified answers.
```

---

## Module 4 - Lesson Planning (Workflow + Examples)

**Outcome-first workflow (≈60 minutes)**
1) Paste outcomes + week topic → ask for an active learning plan with checks for understanding.  
2) Generate materials: slides outline, short reading, exit ticket.  
3) Differentiate: create basic/standard/challenge variants and a multilingual glossary.  
4) Verification pass: require links; manually spot-check and adapt to local context.

### Enhanced Lesson Planning with Claude

**Iterative Lesson Development Process**
```
1. Initial concept generation:
"Create a lesson outline for [topic] targeting [outcomes]. Include timing, key activities, and assessment points."

2. Material development:
"Now create supporting materials for this lesson: 
- Slide outline with key points
- 300-word reading with comprehension questions  
- Hands-on activity with clear instructions
- Exit ticket with 3 questions"

3. Differentiation:
"Adapt these materials for three learning levels. Ensure all students can achieve the core outcomes through different pathways."

4. Refinement:
"Review this lesson plan for potential barriers to learning. Suggest improvements for engagement, accessibility, and assessment."
```

### Examples by Major

**Data Science - Week 4: Supervised Learning & Overfitting**  
- *Activities*: mini-lab fitting a small model, **error analysis walk-through**, and a **hold-out vs. CV** comparison.  
- *Materials*: 300/600-word reading on bias-variance with 10-term glossary.  
- *Exit ticket*: 3 items on leakage, validation strategy, and metric trade-offs.

**Digital Media - Week 5: Storyboarding for Short-Form Video**  
- *Activities*: group storyboard challenge with **shot list templates**, AI-generated alternative angles, and peer critique rubric.  
- *Materials*: mood boards and script beat-sheet; accessibility note (captions/alt text).  
- *Exit ticket*: upload storyboard + 100-word creative rationale.

**Sports - Week 3: Intro to Performance Analytics**  
- *Activities*: small data exploration of match events; **KPIs vs. context** discussion; practice creating a **shot map** or **sprint profile**.  
- *Materials*: glossary (EN/中文) for common metrics; privacy/ethics mini-brief.  
- *Exit ticket*: pick one KPI, justify why it is **valid** and **actionable** for a coach.

---

## Module 5 - Assessment, Integrity & AI Levels

**AI Levels (set per assignment)**
1) **No AI** - closed-book quizzes, in-class derivations/orals.  
2) **AI limited** - outlines/brainstorming allowed; final text/code/design is student-authored.  
3) **AI permitted** - drafting with AI allowed; submit **process evidence** (prompts, outputs, change log).  
4) **AI partner** - co-creation; grade prompt quality, verification, and reflection.  
5) **AI toolchain** - complex projects; grade planning, tool orchestration, and decisions.

**Integrity without detectors**
- Collect **process artifacts** (drafts, prompt history, version diffs).  
- Use **micro-vivas** (1–3 minutes) to confirm understanding.  
- Localise tasks (datasets, assets, campus context) to reduce generic outputs.

### **Enhanced Assessment Strategies with Claude**

**Process Documentation Templates**
```
For AI-permitted assignments, students submit:
1. Initial brainstorming (human-generated)
2. AI conversation transcript with prompts used
3. Draft outputs from AI
4. Student revisions and rationale
5. Final submission with change log
6. Reflection on AI collaboration experience
```

**Micro-Viva Question Banks**
Create question sets that verify student understanding:
- **Concept explanation**: "Explain [key concept] in your own words"
- **Application**: "How would you apply this in [different context]?"
- **Troubleshooting**: "What would you do if [common problem]?"
- **Justification**: "Why did you choose [specific approach/solution]?"

---

## Module 6 - Accessibility & Inclusive Design

- Generate bilingual glossaries, plain-language versions, and reading/listening alternatives.  
- Ask AI to draft **alt text**, **captions**, and **transcripts** (then review).  
- Offer multiple means of action/expression: code, essay, presentation, prototype.

**Enhanced Accessibility Prompts**

**Alt-Text Prompt**
```
Write concise alt text (≤125 chars) for an image of [describe]. Include the learning focus (what students should notice).
Consider: What information is essential for understanding? What decorative elements can be omitted?
```

**Plain Language Converter**
```
Rewrite this technical explanation for [grade level] reading comprehension:
[paste complex text]
Maintain accuracy while using:
- Shorter sentences (max 20 words)
- Common vocabulary
- Active voice
- Clear logical flow
Include a glossary for unavoidable technical terms.
```

**Multi-modal Content Creator**
```
Transform this text-based content into multiple formats:
- Visual: infographic or diagram
- Audio: podcast script or audio explanation
- Kinesthetic: hands-on activity or demonstration
- Interactive: quiz or game format
All versions should achieve the same learning outcome.
```

---

## Module 7 - Data Privacy & Risk (per major)

> **Minimums:** Prefer privacy-preserving workflows, clear consent, and **opt-out** paths. For higher-risk uses, pilot small and monitor.

**Data Science**  
- Never upload raw datasets containing PII to public tools.  
- Prevent **data leakage** (train/test contamination) when co-creating with AI.  
- Document sources; avoid fabricated citations; verify statistics.

**Digital Media**  
- Respect **copyright & licenses** (assets, fonts, models).  
- Disclose synthetic media use; avoid deepfake likenesses without consent.  
- Provide accessible outputs (captions, transcripts, colour-contrast).

**Sports**  
- Athlete data is **sensitive**: anonymise, aggregate, or use public/open data.  
- Do not publish identifiable performance/health data without consent.  
- Consider context: metrics should inform coaching decisions, not stigmatise athletes.

### **Enhanced Privacy Protocols**

**Data Anonymization Checklist**
```
Before using any dataset for teaching:
□ Remove direct identifiers (names, IDs, addresses)
□ Check for quasi-identifiers (age + location + role)
□ Consider k-anonymity (minimum group size)
□ Review for sensitive attributes
□ Document anonymization process
□ Obtain appropriate permissions
□ Plan secure disposal of originals
```

**AI Tool Risk Assessment**
```
For each AI tool, evaluate:
- Data retention policies
- Geographic data storage
- User access controls
- Integration with other platforms
- Export/deletion capabilities
- Educational vs. commercial use terms
- Student age restrictions
```

---

## Module 8 - Custom Course Assistant (Optional)

- Upload materials you **own** or can share: syllabus, outcomes, rubrics, exemplar answers (teacher-only), misconceptions, bilingual glossary.  
- Keep it **private**; disclose to students; always provide a **non-AI alternative**.

**Seed instruction add-ons by major**  
- *Data Science*: prefer **explainable baselines** before advanced models; include **evaluation checklists**.  
- *Digital Media*: enforce **attribution rules**; add a "style constraints & originality" reminder.  
- *Sports*: add **ethics prompts** and **data-minimisation** defaults.

### **Advanced Course Assistant Setup**

**Claude Projects for Education**
Create dedicated Claude Projects with:
- Course syllabus and learning outcomes
- Assignment templates and rubrics
- Common misconceptions database
- Differentiated instruction examples
- Assessment strategies
- Student feedback templates

**Conversation Starters for Course Assistants**
```
- "Help me design a lesson on [topic] for week [X]"
- "Create assessment materials for [learning outcome]"
- "Suggest differentiation strategies for [activity]"
- "Generate discussion questions for [reading/video]"
- "Design a rubric for [assignment type]"
- "Create practice problems for [concept]"
```

---

## Module 9 - Advanced Prompting Techniques

### **Chain-of-Thought Prompting**
```
Let's work through this step-by-step:
1. First, identify the key learning objectives for [topic]
2. Then, consider what students already know about this topic
3. Next, determine the biggest conceptual challenges
4. Finally, design activities that address each challenge
Work through each step explicitly before providing the final lesson plan.
```

### **Role-Playing Prompts**
```
You are now a [first-year student / industry expert / worried parent / skeptical colleague] 
reviewing this [lesson plan/assignment/policy]. 
Provide feedback from that perspective, considering:
- What would concern this person most?
- What questions would they ask?
- What would they find most/least convincing?
```

### **Iterative Refinement Process**
```
1. Initial creation: "Create a basic [item] for [context]"
2. Critique phase: "Review this and identify 3 potential improvements"
3. Enhancement: "Revise based on those critiques"
4. Testing: "What questions might students have about this?"
5. Finalization: "Polish this for professional use"
```

### **Comparative Analysis Prompting**
```
Compare these three approaches to [teaching concept/assessment method]:
Approach A: [traditional method]
Approach B: [technology-enhanced method]  
Approach C: [innovative method]

For each approach, analyze:
- Learning effectiveness
- Implementation complexity
- Student engagement
- Resource requirements
- Accessibility considerations

Recommend the best approach for [specific context] with rationale.
```

### **Constraint-Based Prompting**
```
Design [learning activity] with these specific constraints:
- Time: [X] minutes
- Resources: [limited tech/no budget/specific tools]
- Class size: [Y] students
- Physical space: [lecture hall/lab/online]
- Student level: [beginner/intermediate/advanced]
- Learning style: [must accommodate visual/auditory/kinesthetic]
Work creatively within these limitations.
```

---

## Tools by Major

**Common chat & research**  
- [ChatGPT](https://chat.openai.com/) · [Claude](https://claude.ai/) · [Gemini](https://gemini.google.com/) · [Perplexity](https://www.perplexity.ai/)  
- [Elicit](https://elicit.org/) (paper discovery) · [NotebookLM](https://notebooklm.google/) (source-grounded notes)  
- [Canva](https://www.canva.com/) (quick visuals)

**Claude-Specific Educational Applications**
- **Long-form content**: Comprehensive lesson plans, detailed rubrics, extensive reading materials
- **Document analysis**: Upload and analyze student work, research papers, curriculum documents
- **Code review**: Debug and improve programming assignments across multiple languages
- **Iterative design**: Multi-turn conversations to perfect teaching materials
- **Citation management**: Generate properly formatted academic references
- **Ethical reasoning**: Built-in consideration of bias, fairness, and responsible AI use

**Data Science** (teaching-friendly)  
- **[Python](https://www.python.org/)**: Jupyter/Colab, [pandas](https://pandas.pydata.org/), [numpy](https://numpy.org/), [scikit-learn](https://scikit-learn.org/), matplotlib/plotly  
- **DL**: PyTorch/TensorFlow (intro labs), [Keras](https://keras.io/)  
- **Data**: [Kaggle Datasets](https://www.kaggle.com/datasets), [UCI ML Repository](https://archive.ics.uci.edu/)  
- **MLOps (lightweight)**: [DVC](https://dvc.org/), [Weights & Biases](https://wandb.ai/) (education tiers)  
- **Visualization**: [Tableau Public](https://public.tableau.com/) / [Power BI Desktop](https://www.microsoft.com/power-platform/products/power-bi/desktop) / [Plotly](https://plotly.com/python/)

**Digital Media**  
- **Design**: [Canva](https://www.canva.com/), [Figma](https://www.figma.com/) (education), Adobe Express/Firefly (check licenses)  
- **3D/Animation**: [Blender](https://www.blender.org/)  
- **Video**: [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve), [CapCut](https://www.capcut.com/) (education)  
- **Audio**: [Audacity](https://www.audacityteam.org/), [Ocenaudio](https://www.ocenaudio.com/)  
- **Image gen**: [DALL·E](https://openai.com/research/dall-e), [Midjourney](https://www.midjourney.com/) (use ethically; disclose)

**Sports**  
- **Analysis**: [Tableau Public](https://public.tableau.com/), [Power BI](https://powerbi.microsoft.com/), [Python](https://www.python.org/) ([pandas](https://pandas.pydata.org/), [numpy](https://numpy.org/)), [R](https://www.r-project.org/) ([tidyverse](https://www.tidyverse.org/))  
- **Video tagging**: [LongoMatch](https://www.longomatch.com/), [Kinovea](https://www.kinovea.org/) (motion review)  
- **Open data**: [StatsBomb open data](https://statsbomb.com/resources/), [FiveThirtyEight](https://fivethirtyeight.com/) archives (for teaching)  
- **Pose/vision (advanced)**: OpenPose/MediaPipe (for labs with consented, public videos)

> Always check institutional approvals and licenses before using external tools with students.

---

## Capstone Ideas by Major

**Data Science**
1) **Campus Energy Forecasting** - time-series models for building energy; optimisation suggestions with uncertainty ranges.  
2) **Student Support Early Signals** - privacy-preserving risk flagging with explainable baselines; fairness checks.
3) **AI-Assisted Course Recommendation System** - Personalized learning path suggestions based on student performance patterns
4) **Bias Detection in Recruitment Data** - Analysis of hiring patterns with fairness metrics and intervention recommendations

**Digital Media**
1) **Interactive Museum Guide** - multilingual micro-stories and AR wayfinding prototypes; accessibility by design.  
2) **Local Business Creative Suite** - brand system + templates + short-form content pack; licensing audit.
3) **Accessible Media Converter** - Tool that automatically generates captions, alt-text, and audio descriptions
4) **Cultural Heritage Digital Archive** - Immersive storytelling platform preserving local traditions and histories

**Sports**
1) **Performance Insights Toolkit** - open-data dashboards (shot maps, press intensity) with coach-friendly briefs.  
2) **Injury-Risk Communication Guide** - literature synthesis + prototype of **non-stigmatizing** decision aids for staff.
3) **Athlete Wellness Monitoring System** - Privacy-preserving platform for tracking training load and recovery
4) **Fan Engagement Analytics Platform** - Social media and attendance data analysis for sports marketing insights

---

## Policy Templates & Examples

### Syllabus AI Use Statement (copy/adapt)

- **Allowed**: brainstorming, outlines, language refinement; discipline-specific suggestions (see majors).  
- **Limited**: summarising sources with references; design/code suggestions (human review required).  
- **Not allowed**: final graded work produced by AI.  
- **Privacy**: no PII/student work in public tools; use approved platforms only.  
- **Acknowledgement**: include an "AI Assistance" note in submissions.  
- **Opt-out**: human alternatives for any required AI feature.  
- **Stirling note**: Reference your school/department's current AI guidance in assessment briefs.

### By-Assignment Examples
- **Reading response**: AI for outline/clarify; student writes final; attach outline + reflection.  
- **Lab report**: AI for formatting/grammar; analysis and interpretation are student-authored.  
- **Oral viva**: AI may generate practice questions; in-person assessment is AI-free.

### **Enhanced Policy Components**

**Student AI Literacy Requirements**
```
By week 4, all students should demonstrate:
□ Understanding of AI capabilities and limitations
□ Ability to write effective prompts for learning tasks
□ Knowledge of citation requirements for AI-assisted work
□ Awareness of bias and ethical considerations
□ Skills in fact-checking AI-generated content
```

**Faculty AI Use Guidelines**
```
When using AI for teaching:
□ Disclose AI use to students and institution
□ Verify all AI-generated factual claims
□ Provide non-AI alternatives for all activities
□ Respect student data privacy
□ Model responsible AI use practices
□ Stay updated on institutional policies
```

---

## Custom GPT Instruction Template

Paste into your assistant's "system/instructions":
```
You are a course assistant for [Course Name] at Stirling College (Chengdu University).
Goals: Support [level] students to meet [learning outcomes].

Context: This is a [semester/year] course in [major] focusing on [key themes]. Students have [prerequisite knowledge] and will go on to [next courses/career paths].

Do:
- Use plain language; scaffold explanations; offer structured outlines, examples, and checklists.
- Ask one clarifying question only if essential to meet the request.
- Provide sources/links for factual claims; flag uncertainty and common misconceptions.
- Offer differentiated outputs (basic/standard/challenge).
- Respect privacy: never request or process PII or student-identifiable work.
- Include a short "limitations & bias check" note for teacher-facing outputs.
- Support iterative improvement - ask if refinement is needed before considering task complete.
- Connect concepts to real-world applications relevant to [geographic region/industry context].

Don't:
- Produce final graded work or complete summative assessments.
- Fabricate citations or statistics; if unsure, say so and propose verification.
- Store or reuse any user content beyond the current session.
- Make assumptions about student abilities or backgrounds.

Formatting defaults:
- Use markdown with headings, bullet points, and tables when helpful.
- For Data Science: prefer simple, explainable baselines before advanced models; include evaluation checklists.
- For Digital Media: enforce attribution/licensing and originality reminders; add accessibility notes.
- For Sports: emphasise data minimisation, consent, and coach-facing clarity.

Special considerations for this course:
- [Add course-specific requirements, common misconceptions, or cultural considerations]
```

---

## Acknowledging AI Assistance

### **Detailed Attribution Templates**

**For Basic AI Use**
> "**AI Assistance**: [Tool name] used for brainstorming and initial outline generation. All content was reviewed, fact-checked, and significantly revised by the author."

**For Code/Technical Work**
> "**AI Assistance**: [Tool] provided initial code structure and debugging suggestions for [specific functions]. Code was tested, optimized, and documented by the author. Final algorithm design and implementation decisions were human-made."

**For Creative Work**
> "**AI Assistance**: [Tool] generated initial ideas and style suggestions. All creative decisions, content selection, and final artistic execution were completed by the author. Original concept and artistic vision remain entirely human-created."

**For Research Work**
> "**AI Assistance**: [Tool] helped organize sources and generate preliminary analysis frameworks. All source verification, critical analysis, and conclusions were conducted by the author. AI was not used for literature search or citation generation."

### **Process Documentation Template**
```
AI Assistance Log:
- Tool used: [name and version]
- Date(s) of use: [specific dates]
- Purpose: [brainstorming/editing/debugging/etc.]
- Prompts used: [key prompts, not full transcripts]
- Output used: [% of AI output retained vs. modified]
- Verification steps: [how accuracy was confirmed]
- Human contribution: [what student added/changed/created]
```

---

## Advanced Classroom Integration Strategies

### **AI-Enhanced Peer Learning**
```
Peer Review with AI Support:
1. Students draft initial work (human-only)
2. AI generates review questions specific to assignment criteria
3. Peers conduct reviews using AI-generated framework
4. Students revise based on peer feedback
5. AI helps generate reflection prompts on the peer review process
```

### **Flipped Classroom with AI**
```
Pre-Class Preparation:
- AI generates personalized study guides based on learning objectives
- Students use AI to test their understanding with practice questions
- AI identifies knowledge gaps and suggests additional resources

In-Class Application:
- Focus on higher-order thinking and problem-solving
- Use AI-generated scenarios for case study discussions
- AI helps facilitate small group work with targeted prompts
```

### **Assessment Innovation**
```
Process-Focused Assessment:
- Students document their problem-solving approach
- AI helps generate metacognitive reflection questions
- Assessment includes both final product and thinking process
- AI assists in creating personalized feedback
```

---

## Troubleshooting Common Challenges

### **Student Over-Reliance on AI**
**Prevention strategies:**
- Build assignments that require personal experience/opinion
- Use local/specific contexts AI won't know
- Include peer discussion and presentation components
- Require process documentation showing human thinking

### **Quality Control Issues**
**Solutions:**
- Create AI output evaluation checklists for students
- Teach fact-checking and source verification skills
- Use iterative refinement processes
- Implement peer review of AI-assisted work

### **Equity and Access Concerns**
**Approaches:**
- Provide free alternatives to premium AI tools
- Ensure non-AI pathways for all learning objectives
- Offer AI literacy training for all students
- Consider digital divide implications in assignment design

---

## Professional Development Resources

### **Staying Current with AI in Education**
- Follow education technology researchers and publications
- Join AI in education communities and forums  
- Attend workshops and conferences on educational AI
- Experiment with new tools in low-risk contexts
- Share experiences with colleagues

### **Building AI Literacy**
- Understand basic machine learning concepts
- Learn about bias, fairness, and ethics in AI
- Practice prompt engineering for educational contexts
- Develop critical evaluation skills for AI outputs
- Stay informed about privacy and data protection

---

## Rubrics (Download & Adapt)

- **Data Science**: [CSV](/mnt/data/rubric_data_science.csv) · [Markdown](/mnt/data/rubric_data_science.md)  
- **Digital Media**: [CSV](/mnt/data/rubric_digital_media.csv) · [Markdown](/mnt/data/rubric_digital_media.md)  
- **Sports**: [CSV](/mnt/data/rubric_sports.csv) · [Markdown](/mnt/data/rubric_sports.md)

### **AI Integration Assessment Rubrics**

**AI Collaboration Skills Rubric**
- **Exemplary**: Demonstrates sophisticated prompt crafting, critical evaluation of AI outputs, and seamless integration of AI assistance with human creativity
- **Proficient**: Uses AI effectively for appropriate tasks, verifies outputs, and maintains clear distinction between AI and human contributions  
- **Developing**: Shows basic AI interaction skills but needs support in critical evaluation and appropriate use boundaries
- **Beginning**: Limited understanding of AI capabilities; requires guidance on effective prompting and output evaluation

---

## References
- **UNESCO** – *Guidance for Generative AI in Education & Research* (human-centred, inclusion, equity).  
- **U.S. Dept. of Education (Office of EdTech)** – *Empowering Education Leaders: A Toolkit for Safe, Ethical, and Equitable AI Integration* (privacy, civil rights, opt-outs).  
- **Stirling (internal policy summary)** – *AI in Teaching & Assessments Workshop (Autumn 2024)* – staff/student guidance highlights on assessment and disclosure.  
- **Stirling College / Data Science** – *Programme Handbook (2023–2024)* – assessment & integrity context for DS modules.  
- **Teachers' prompting & critical use** – *Ways to Use AI Critically in the Classroom* – prompt-building, bias checks.
- **Anthropic** – *Claude for Education: Best Practices Guide* – responsible AI use in academic settings.
- **Partnership on AI** – *Tenets for Responsible AI in Education* – ethical framework for educational AI applications.
- **International Society for Technology in Education (ISTE)** – *AI Guidance for Schools* – implementation strategies and policy development.
