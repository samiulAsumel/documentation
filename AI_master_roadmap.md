# AI-Powered Expert Mastery Roadmap
## MD. Samiul Alam Sumel — Complete 180-Day Program
### লক্ষ্য: Expert AI User → Saudi Arabia Port IT Job 2027 Q2

---

## ভাষার নিয়ম (কখনো ভাঙবে না)

- বাংলা কথা → সবসময় **বাংলা হরফে** লিখবে
- English technical terms → **English-এ** লিখবে
- কখনো বাংলা কথা English হরফে লিখবে না
- আমি শুধু **"Day 1"**, **"Day 2"** বলব — বাকি সব তুমি দেবে

---

## তুমি কে — Context (কখনো ভুলবে না)

| বিষয় | তথ্য |
|-------|------|
| নাম | MD. Samiul Alam Sumel |
| অভিজ্ঞতা | ১২+ বছর Mongla Port Authority |
| লক্ষ্য | Saudi Arabia port IT job — 2027 Q2 |
| Portfolio | portbill.vercel.app, monthly-car-balance.vercel.app |
| শক্তি | Problem solving, AI-assisted building, port domain |
| দুর্বলতা | Code scratch থেকে লিখতে পারি না — AI দিয়ে করি |

---

## প্রতিদিনের Session Format (সব দিন — ব্যতিক্রম নেই)

```
① আগের দিনের ১টি Checkpoint review (২ মিনিট)
② আজকের Concept — কেন দরকার, কীভাবে কাজ করে (১৫ মিনিট)
③ Hands-on Task — actually করতে হবে (২০ মিনিট)
④ Domain Connection — Saudi port/DevOps/AWS-এ কীভাবে কাজে লাগবে (৫ মিনিট)
⑤ Checkpoint — বোঝার প্রমাণ (৫ মিনিট)
⑥ পরের দিনের Preview (২ মিনিট)
```

---

## 180-দিনের Complete Structure

| Phase | দিন | Focus |
|-------|-----|-------|
| Phase 1 | Day 1–15 | Claude Code Foundation |
| Phase 2 | Day 16–30 | Prompt Engineering Mastery (Anthropic Course) |
| Phase 3 | Day 31–45 | Architecture & Structure |
| Phase 4 | Day 46–60 | Full-Stack Real Projects |
| Phase 5 | Day 61–75 | Power User — MCP, Agents, Loops |
| Phase 6 | Day 76–90 | Claude Code Expert + Portfolio Polish |
| Phase 7 | Day 91–120 | AI-Assisted DevOps + Linux + AWS |
| Phase 8 | Day 121–150 | AI-Assisted Software Engineering |
| Phase 9 | Day 151–180 | Saudi Portfolio Final + Interview Ready |

---

---

# PHASE 1 — Claude Code Foundation (Day 1–15)

---

## Day 1 — Claude Code আসলে কী?

**ধারণা:**
ChatGPT তোমাকে text দেয় — তুমি কাজ করো। Claude Code **নিজেই** file খোলে, code লেখে, terminal চালায়, test করে। এই পার্থক্যটা সব কিছু বদলে দেয়।

**Task:**
`code.claude.ai` পেজটা খোলো। একটা নোটে লেখো — এই tool তোমার কোন real problem solve করতে পারবে।

**Domain Connection:**
portbill.vercel.app তুমি AI দিয়ে বানিয়েছিলে। Claude Code দিয়ে সেই কাজ আরো fast, আরো professional হবে।

**Checkpoint:**
এক sentence-এ বলো — agent আর chatbot-এর পার্থক্য কী?

---

## Day 2 — Anthropic-এর Vision + Model Selection

**ধারণা:**
Boris Cherny বলেছেন: "I imagine a world where everyone is able to program." তুমি programmer না — কিন্তু Claude Code দিয়ে তুমি programmer-এর মতো কাজ করতে পারবে।

| Model | কখন Use করবে |
|-------|--------------|
| Sonnet | শুরু করার জন্য, everyday কাজে |
| Opus | Complex architecture, important decisions |

**গুরুত্বপূর্ণ insight:** Cheap model use করলে বেশি token খায় — কারণ বেশি correction লাগে।

**Task:**
তোমার portbill project-এ কোন model use করতে সেটা decide করো এবং কারণ নোটে লেখো।

**Checkpoint:**
একটা project-এর জন্য কোন model choose করবে এবং কেন?

---

## Day 3 — Installation: VS Code দিয়ে শুরু

**Task:**
1. `code.visualstudio.com` থেকে VS Code download করো
2. Extension search-এ "Claude Code" লিখো — Anthropic-এর official টা install করো
3. একটা empty folder খোলো VS Code-এ
4. Claude Code panel open হচ্ছে কিনা দেখো

**Checkpoint:**
Claude Code panel VS Code-এ open হচ্ছে?

---

## Day 4 — Agent Loop: ভেতরে কী হয়?

**ধারণা:**
Claude একটা loop-এ কাজ করে:
```
① Input নাও → ② Reason করো → ③ Tool select করো
→ ④ Tool execute করো → ⑤ Result দেখো → ⑥ আবার reason করো
```

**Claude-এর Internal Tools:**

| Tool | কী করে |
|------|--------|
| `read_file` | File-এর content পড়ে |
| `write_file` | নতুন file তৈরি করে |
| `edit_file` | Existing file change করে |
| `run_command` | Terminal command চালায় |
| `list_directory` | Folder structure দেখে |
| `web_search` | Internet search করে |

**Task:**
Claude-কে বলো: "List the directory structure of this project and tell me what you found."

**Checkpoint:**
Claude কোন tool use করে file পড়ে? কোন tool দিয়ে command run করে?

---

## Day 5 — প্রথম Project: Personal Homepage

**Task — Exact Prompt:**
```
Build a personal homepage. Dark background (#0f0f13), light text (#e2e2e2),
accent color indigo (#6366f1). Sections: hero with my name Samiul Alam Sumel,
short bio about port operations specialist targeting Saudi Arabia,
links for LinkedIn and GitHub. HTML and CSS only, no JavaScript.
Enter Plan Mode first. Show me the plan before writing anything.
```

**Checkpoint:**
Browser-এ open হচ্ছে? Mobile-এ ঠিক দেখাচ্ছে?

---

## Day 6 — CLAUDE.md — সবচেয়ে Powerful File

**ধারণা:**
CLAUDE.md হলো তোমার project-এর "স্মৃতি"। প্রতি session-এ Claude এই file টা আগে পড়ে।

**Task — Homepage project-এ তৈরি করো:**
```markdown
# Project: My Homepage

## Stack
HTML5, CSS3 only. No JavaScript. No frameworks.

## Conventions
- All styles in style.css — no inline styles
- Dark theme: background #0f0f13, text #e2e2e2, accent #6366f1

## About Me
Port Operations Specialist — 12yr Mongla Port Authority
Targeting Saudi Arabia port IT roles — 2027

## Definition of Done
- Works in browser
- Mobile responsive
- All links present
```

**Checkpoint:**
CLAUDE.md file কি project root-এ আছে?

---

## Day 7 — Plan Mode + PRD.md

**Plan Mode activation:**
- Terminal-এ: `Shift+Tab` দুইবার
- VS Code-এ: Plan Mode button

**PRD.md Format:**
```markdown
# PRD: [Project Name]

## What Is This
[এক paragraph — product, user, purpose]

## Features
### Feature 1: [Name]
- Behavior: [X করলে কী হয়]
- Acceptance: [কখন done বলব]
- Edge cases: [empty/invalid input হলে কী]

## Tech Stack
[Languages, libraries, database]

## Design
[Colors, layout, responsive requirements]
```

**Task:**
একটা Task Manager-এর জন্য full PRD.md তৈরি করো।

**Checkpoint:**
PRD পড়ে কি Claude জানবে exactly কী বানাতে হবে?

---

## Day 8 — Perfect Prompt-এর Anatomy

**ধারণা:**
```
① Context — কী বানাচ্ছো, কার জন্য
② Features — exactly কী কী লাগবে (numbered list)
③ Tech stack — কোন technology use করবে
④ Constraints — কী করা যাবে না
⑤ Design — visual requirements
⑥ Starting point — Plan Mode দিয়ে শুরু করতে বলো
```

**Compare করো:**
```
❌ খারাপ: "Build a todo app."

✅ ভালো: "Build a todo app for one user. Tasks have title, due date,
priority (low/medium/high). Mark complete. Filter by status.
Data persists in localStorage. HTML/CSS/vanilla JS only.
Enter Plan Mode first."
```

**Task:**
তোমার next project-এর জন্য একটা full prompt লেখো।

**Checkpoint:**
একজন engineer তোমার prompt পড়ে exactly কী বানাবে বুঝতে পারবে?

---

## Day 9 — Token, Context Window, Multi-Session

**Token নিয়ম:**
Context 40-50% হলে new session শুরু করো।

**৪টি Continuity File:**

| File | Purpose |
|------|---------|
| `CLAUDE.md` | Auto-read প্রতি session-এ — conventions |
| `PRD.md` | Feature specification |
| `README.md` | Implementation status |
| `progress.md` | Decisions, rejected approaches |

**Session শুরু করার prompt:**
```
New session. Read these files in order:
1. CLAUDE.md
2. PRD.md
3. README.md (Implementation Status section)
4. progress.md
Tell me the current project state and where we left off.
```

**Checkpoint:**
New session-এ কি Claude বুঝলো কোথায় ছিলে?

---

## Day 10 — Interview Technique

**Prompt:**
```
Before writing any plan or code, interview me systematically about this project.
Ask me about: features, tech stack, UI decisions, data model, edge cases.
Do not proceed until the interview is complete.
```

**Checkpoint:**
Interview থেকে কী কী নতুন decision নিয়েছো?

---

## Day 11–12 — Feature by Feature Building

**Build Cycle:**
```
একটা feature → Plan Mode → Approve → implement → test → edge cases → next
```

**Task:**
Task Manager project — feature 1 only: শুধু task তৈরি।

---

## Day 13–14 — CF Agent Dashboard Build

**Prompt:**
```
Build a CF Agent Information Dashboard.
Features: vessel arrival date input, cargo type selector,
wharfrent calculation preview (7 days free, then daily rate),
deadline alert if approaching 7 days, print summary button.
HTML/CSS/vanilla JS only. Dark theme. Mobile responsive.
All calculations in utils/calculator.js only.
Enter Plan Mode first.
```

---

## Day 15 — Phase 1 Review

**Task:**
1. Homepage browser-এ open করো
2. Mobile width-এ resize করো
3. CLAUDE.md update করো
4. Phase 1-এ যা শিখলে সব নোটে লেখো

**Checkpoint:**
তুমি কি HTML source code কাউকে explain করতে পারবে?

---

---

# PHASE 2 — Prompt Engineering Mastery (Day 16–30)
## Anthropic Official Course সম্পূর্ণ করা

> এই phase-এ তুমি Anthropic-এর official prompt engineering notebooks গুলো complete করবে। এটা তোমার Claude Code skill-এর foundation আরো মজবুত করবে।

---

## Day 16 — Chapter 1: Basic Prompt Structure

**ধারণা:**
Messages API-এর structure বোঝো:
- `model` — কোন model use করবে
- `max_tokens` — কতটুকু response চাও
- `messages` — user/assistant alternating turns
- `system` — system prompt (আলাদা parameter)

**Task:**
Notebook `01_Basic_Prompt_Structure.ipynb` — সব exercises করো।
- Exercise 1.1: Claude-কে 1, 2, 3 count করাও
- Exercise 1.2: System prompt দিয়ে 3-year-old child-এর মতো response আনো

**Key Insight:**
System prompt = তোমার CLAUDE.md-এর equivalent। প্রতিটা API call-এ globally instructions দেওয়ার জায়গা।

**Port Connection:**
Saudi port IT-তে API integration করতে হবে — এই structure জানা mandatory।

**Checkpoint:**
`user` আর `assistant` messages কেন alternate করতে হয়?

---

## Day 17 — Chapter 2: Being Clear and Direct

**Golden Rule of Clear Prompting:**
"Show your prompt to a colleague. If they're confused, Claude's confused."

**Task:**
Notebook `02_Being_Clear_and_Direct.ipynb` করো।
- Exercise 2.1: Spanish-এ respond করাও
- Exercise 2.2: শুধু "Michael Jordan" — no other words
- Exercise 2.3: 800+ words-এর story লেখাও

**Key Insight:**
```
❌ "Build a billing system"
✅ "Build a CF agent billing system with vessel name input,
   cargo type dropdown, wharfrent calculation for 7-day free period,
   then $50/day. Show total. Print button. HTML/CSS/JS only."
```

**Checkpoint:**
তোমার আগের একটা bad prompt identify করো — কী missing ছিল?

---

## Day 18 — Chapter 3: Role Prompting

**ধারণা:**
Claude-কে specific role দিলে performance বাড়ে।

```python
# Without role
"Is this equation correct? 2x - 3 = 9, 2x = 6, x = 3"
# Claude might miss the error

# With role
SYSTEM = "You are a strict mathematics professor who catches every error."
# Claude will find the mistake
```

**Task:**
Notebook `03_Assigning_Roles_Role_Prompting.ipynb` করো।
- Exercise 3.1: Math correction — role prompting দিয়ে error ধরাও

**Port Connection:**
```
"You are a senior port operations IT architect with 20 years experience
in Saudi Arabia. Review this billing system design."
→ এই role দিলে Claude আরো relevant feedback দেবে।
```

**Checkpoint:**
Role prompting কীভাবে তোমার port projects-এ use করবে?

---

## Day 19 — Chapter 4: Separating Data and Instructions

**ধারণা:**
XML tags দিয়ে data আর instructions আলাদা করো:

```
❌ খারাপ:
"Summarize this: The vessel MV Karnaphuli arrived at Mongla Port..."

✅ ভালো:
"Summarize the following vessel arrival report:
<report>
The vessel MV Karnaphuli arrived at Mongla Port...
</report>"
```

**Task:**
Notebook `04_Separating_Data_and_Instructions.ipynb` করো।

**Key Insight:**
Template variables `{VESSEL_NAME}`, `{CARGO_TYPE}` — এগুলো তোমার port billing templates-এ use করো।

**Checkpoint:**
XML tags use করলে Claude-এর response কীভাবে improve হলো?

---

## Day 20 — Chapter 5: Formatting Output

**ধারণা:**
Claude-এর response format control করার techniques:

```
① Output format specify করো: "Respond in JSON"
② Claude-এর voice-এ শুরু করো (prefilling):
   Assistant: {"vessel_name": "  ← এখান থেকে Claude continue করবে
③ Length control: "In exactly 3 bullet points"
④ No preamble: "Skip the preamble. Start directly with..."
```

**Task:**
Notebook `05_Formatting_Output_and_Speaking_for_Claude.ipynb` করো।

**Port Connection:**
Saudi port IT-তে structured JSON output দরকার — API integration-এ।

**Checkpoint:**
Prefilling technique কীভাবে তোমার billing API-তে use করবে?

---

## Day 21 — Chapter 6: Precognition (Step by Step Thinking)

**ধারণা:**
Complex problems-এ Claude-কে আগে think করতে বলো:

```
❌ "What's the wharfrent for vessel X?"
✅ "Think step by step:
   1. First identify the cargo type and free period
   2. Calculate dwell time from arrival to today
   3. If dwell time > free period, calculate charges
   4. Show your work at each step
   Then give the final amount."
```

**Task:**
Notebook `06_Precognition_Thinking_Step_by_Step.ipynb` করো।

**Checkpoint:**
Step-by-step thinking কোন ধরনের problems-এ সবচেয়ে বেশি help করে?

---

## Day 22 — Chapter 7: Few-Shot Prompting

**ধারণা:**
Examples দিলে Claude exactly তোমার pattern follow করে:

```
Here are examples of how to format vessel reports:

<example>
Input: Vessel: MV Alpha, Arrived: Jan 1, Cargo: Container, Quantity: 500
Output: {"vessel": "MV Alpha", "arrival": "2025-01-01",
         "cargo_type": "container", "quantity": 500, "free_days": 7}
</example>

Now format this: Vessel: MV Beta, Arrived: Jan 5, Cargo: Bulk, Quantity: 1000
```

**Task:**
Notebook `07_Using_Examples_Few-Shot_Prompting.ipynb` করো।

**Checkpoint:**
Few-shot examples ছাড়া আর সহ — result কীভাবে আলাদা হলো?

---

## Day 23 — Chapter 8: Avoiding Hallucinations

**ধারণা:**
Claude confident tone-এ ভুল বলতে পারে। তিনটি technique:

```
① Quote-first approach:
   "Find quotes from the document that support your answer.
   If no quotes exist, say 'I cannot find this information.'"

② Explicit uncertainty:
   "If you're not sure, say 'I don't know' rather than guessing."

③ Source requirement:
   "Only answer based on the provided documentation."
```

**Task:**
Notebook `08_Avoiding_Hallucinations.ipynb` করো।

**Port Connection:**
Saudi port-এ wrong billing calculation = financial loss. Hallucination prevention = critical।

**Checkpoint:**
Claude কখন hallucinate করে সেটা তুমি কীভাবে detect করবে?

---

## Day 24 — Chapter 9: Complex Prompts from Scratch

**ধারণা:**
Complex prompt-এর সব layers:
```
① Role assignment
② Context and background
③ Task definition (numbered)
④ Input format (XML tags)
⑤ Output format (JSON/structured)
⑥ Examples (few-shot)
⑦ Edge case handling
⑧ Constraints
```

**Task:**
Notebook `09_Complex_Prompts_from_Scratch.ipynb` করো।
Port billing system-এর জন্য একটা complex system prompt লেখো।

---

## Day 25 — Appendix: Chaining Prompts

**ধারণা:**
একটা বড় task → ছোট ছোট steps-এ ভাগ করো:

```
Step 1 Prompt: "Extract vessel details from this report"
→ Output feeds into →
Step 2 Prompt: "Calculate wharfrent based on these vessel details"
→ Output feeds into →
Step 3 Prompt: "Generate formal billing notice from these calculations"
```

**Task:**
Notebook `10_1_Appendix_Chaining_Prompts.ipynb` করো।
Port billing pipeline-এর জন্য একটা 3-step chain design করো।

**Checkpoint:**
কখন single prompt better, কখন chaining better?

---

## Day 26 — Appendix: Tool Use

**ধারণা:**
Claude-কে external tools দিতে পারো:

```python
tools = [
    {
        "type": "web_search_20250305",
        "name": "web_search"
    }
]
```

Custom tools define করা যায়:
```
get_vessel_info(vessel_id) → vessel details
calculate_wharfrent(vessel_id, date) → charge amount
generate_bill(vessel_id) → PDF bill
```

**Task:**
Notebook `10_2_Appendix_Tool_Use.ipynb` করো।

**Port Connection:**
Saudi port IT-তে এই tool use pattern দিয়ে port management system build করবে।

---

## Day 27 — Appendix: Evaluations (Evals)

**ধারণা:**
AI output measure করার ৩টা method:

```
① Code-based grading: exact match check
   grade = output.lower() == "positive"

② Human grading: rubric দিয়ে human evaluate করে

③ Model-based grading: Claude নিজেই evaluate করে
   "Based on this rubric, score this response 1-5"
```

**Task:**
Notebook `10_3_Appendix_Empirical_Performance_Eval.ipynb` করো।
তোমার CF Agent Dashboard-এর billing calculation-এর জন্য একটা eval system design করো।

**Port Connection:**
Production system-এ deploy করার আগে evals চালাও — wrong billing আটকাও।

---

## Day 28 — Appendix: RAG + Search & Retrieval

**ধারণা:**
RAG = Retrieval Augmented Generation।
Claude-কে তোমার own documents থেকে answer করাও:

```
Vector Database → Search relevant docs → Feed to Claude → Answer
```

**Use cases তোমার জন্য:**
- Port regulation documents search
- Historical billing records query
- Saudi customs rules lookup

**Task:**
Notebook `10_4_Appendix_Search_and_Retrieval.ipynb` পড়ো।
একটা simple document Q&A system design করো — port regulations নিয়ে।

---

## Day 29–30 — Phase 2 Review + Integration

**Day 29 — Best Prompt Library তৈরি করো:**
Phase 1 + Phase 2 থেকে তোমার সেরা ১০টা prompt collect করো।

**Day 30 — Master System Prompt Template:**
```
You are [ROLE] with [YEARS] years of experience in [DOMAIN].

Context: [PROJECT CONTEXT]

Your task: [SPECIFIC TASK]

Rules:
- [CONSTRAINT 1]
- [CONSTRAINT 2]
- If unsure, say "I need more information about X"

Input format:
<[TAG]>
{INPUT}
</[TAG]>

Output format:
[EXACT FORMAT SPECIFICATION]

Examples:
<example>
[EXAMPLE INPUT → OUTPUT]
</example>
```

---

---

# PHASE 3 — Architecture & Structure (Day 31–45)

---

## Day 31 — Structure কেন Claude-এর Productivity বাড়ায়

**ধারণা:**
Well-structured codebase → Claude কম files পড়ে, targeted changes করে।
Disorganized codebase → Claude বেশি token খায়, বেশি mistakes করে।

**Single Responsibility Principle:**
```
❌ utils.js — কী আছে? কেউ জানে না
✅ dateFormatters.js — শুধু date formatting
✅ storage.js — শুধু localStorage
✅ calculator.js — শুধু billing calculation
```

---

## Day 32 — Layer Separation

**৪টি Layer সবসময় আলাদা:**
```
Presentation  → Components/UI — no business logic
Business      → Services — no database, no UI
Data Access   → Repos — only storage
Integration   → External APIs — isolated
```

**Task:**
Port Billing System-এর directory structure design করো।

---

## Day 33–35 — Naming Conventions + Project Structure

**CLAUDE.md-এ add করো:**
```markdown
## Naming Conventions
- Components: PascalCase noun (TaskListItem, VesselCard)
- Services: camelCase domain (billingService, vesselService)
- Utils: camelCase concern (dateFormatters, currencyUtils)
- Tests: same name + .test.js

## New Project Sequence
① Directory structure manually তৈরি করো
② CLAUDE.md লেখো
③ PRD.md লেখো
④ Claude-কে skeleton বানাতে বলো (empty files)
⑤ Skeleton review করো
⑥ Features implement করো one by one
```

---

## Day 36–40 — Port Billing Advanced System

**Day 36 — Prompt:**
```
Build an advanced port billing management system.
Features: multiple CF agent profiles, bulk vehicle billing,
monthly revenue reports, billing history search, PDF export.
File structure:
  index.html
  style.css
  services/billingService.js (all calculation logic)
  services/reportService.js (all report generation)
  storage/billingRepo.js (all localStorage — nowhere else)
  utils/pdfExport.js
  components/dashboard.js
  components/agentForm.js
No logic in HTML files. All data through billingRepo.js only.
Enter Plan Mode first.
```

**Day 37–40:** Features একটা একটা করে build করো।

---

## Day 41–43 — Weather Dashboard (External API)

**Prompt:**
```
Build a weather dashboard using Open-Meteo API (free, no key needed).
Features: city search, current weather, 7-day forecast,
loading spinner, error states, last city in localStorage.
All API calls through services/weatherApi.js only.
Async/await only — no .then().
Enter Plan Mode first.
```

---

## Day 44–45 — Master CLAUDE.md Template Final

```markdown
# Project: [Name]

## Architecture
[Stack, database, auth]

## Directory Structure
[Major folders এবং তাদের contents]

## Conventions
- Async: always async/await, never .then()
- All DB calls through: [which layer]
- No logic in HTML files

## Libraries
Used: [list]
Prohibited: [list with reasons]

## Definition of Done
1. Behavior correct
2. Edge cases handled
3. No console errors
4. Mobile responsive
5. Tested manually

## Port Connection
[Saudi port-এ কীভাবে relevant]
```

---

---

# PHASE 4 — Full-Stack Real Projects (Day 46–60)

---

## Day 46–48 — Full-Stack Fundamentals

**Stack:**
```
Frontend = browser-এ HTML/JS
Backend  = Node.js + Express
Database = SQLite (file-based)
```

**REST API:**
| Method | কাজ | Example |
|--------|-----|---------|
| GET | Data পড়া | GET /api/vessels |
| POST | নতুন create | POST /api/vessels |
| PUT | Update | PUT /api/vessels/:id |
| DELETE | Delete | DELETE /api/vessels/:id |

---

## Day 49–53 — Notes App: Full Stack Build

**Backend (Day 49):**
```
Build notes app backend. Node.js + Express + better-sqlite3. Port 3001.
Notes table: id, title, content, created_at, updated_at.
REST API: GET/POST/PUT/DELETE /api/notes.
All DB through server/db/notesRepo.js — no SQL in routes.
Error handling middleware. Enter Plan Mode first.
```

**Frontend (Day 50):**
```
Build frontend. Backend on port 3001.
Three-panel: sidebar (list), editor (active), empty state.
Auto-save: debounce 1 second.
All fetch calls through client/services/notesApi.js only.
```

**Day 51:** Integration tests — jest + supertest
**Day 52:** Security audit — SQL injection check
**Day 53:** Production readiness checklist

---

## Day 54–57 — Port Operations Management System

**এটা তোমার সবচেয়ে important portfolio project।**

**Prompt (Day 54):**
```
Build a Port Operations Management System.
Features:
- Vessel arrival tracking (name, arrival date, berth, status)
- Cargo manifest (type, quantity, CF agent, dwell time)
- Wharfrent calculator (auto based on dwell time + cargo type)
- Daily operations report (PDF export)
- CF agent portal (own cargo only — basic auth)
Tech: Node.js + Express + SQLite. Frontend: HTML/CSS/vanilla JS.
Layers: routes/ → services/ → repos/ → database
No SQL in routes. No business logic in routes.
Enter Plan Mode first. Architecture diagram first.
```

---

## Day 58–60 — Deployment + Review

**Day 58:** GitHub push — README + screenshots
**Day 59:** Vercel/Railway deploy — live URL
**Day 60:** Portfolio review — কোনটা Saudi interview-এ strongest?

---

---

# PHASE 5 — Power User Skills (Day 61–75)

---

## Day 61–63 — MCP: Model Context Protocol

**MCP দিয়ে Claude connect করে:**
- Default: files + terminal + web search
- MCP: GitHub + Notion + Slack + browser

**GitHub MCP (Day 62–63):**
```
List open issues in this repository.
Create issue: "CF billing shows wrong rate for vehicles over 14 days"
Open PR from feature/port-reports into main.
```

---

## Day 64–65 — Playwright: Browser Automation

```
Install: @playwright/mcp

Use:
Go to staging environment, login with test credentials,
create test vessel entry, verify it appears in dashboard.
```

---

## Day 66–68 — Parallel Sessions + Git Worktrees

**Parallel Sessions:**
```
Session 1 scope: client/ ONLY. Build frontend dashboard.
Session 2 scope: server/tests/ ONLY. Write API tests.
Session 3 scope: docs/ ONLY. Write documentation.
```

**Git Worktrees:**
```bash
git worktree add ../project-auth feature/authentication
git worktree add ../project-reports feature/reports
```

---

## Day 69–71 — Autonomous Loops

**Safe Loop Template:**
```
You will [task]. Rules:
- Do [specific action] only
- Do NOT change any logic
- Do not modify files outside [directory/]
- Process one file at a time, alphabetically
- After all files, output summary
Begin with [first file].
```

**কখন Loops ঠিক না:**
- New features with unclear scope
- Architecture decisions
- Unfamiliar codebase

---

## Day 72–75 — MCP Security + CLI Tool

**Security নিয়ম:**
```
① Minimum access — শুধু দরকারি directories
② Review before execute — production-এ কিছু করার আগে
③ No credentials in prompts — শুধু config file-এ
④ Specific instructions — "update tracker" vague
```

**CLI Tool (Day 73–74):**
```
Build Node.js CLI scaffolding tool.
scaffold create <template> <name> — project from template
scaffold list — available templates
Templates: web-basic, node-api
Replace {{PROJECT_NAME}} in all files. Use commander.
```

---

---

# PHASE 6 — Expert Level + Portfolio Polish (Day 76–90)

---

## Day 76–78 — Team Standup Tracker

```
Build team standup tracker.
DB: users (id, name, email),
standups (id, user_id, date, yesterday, today, blockers, created_at)
API: GET/POST users, GET standups by date, GET user history (14 days),
POST standup (upsert same user+date).
Validation: yesterday/today required max 1000 chars.
JSON: {data:...} success, {error:...} failure.
```

---

## Day 79–81 — Code Review + Security

**AI code-এর ৪টি failure point:**
```
① API hallucination — function exist করে না
② Edge case omission — boundary conditions miss
③ Security vulnerabilities — SQL injection
④ Confident incorrectness — confident ≠ correct
```

**Security Rules:**
```
❌ "SELECT * WHERE name = '" + userInput + "'"
✅ Parameterized queries সবসময়
❌ API keys in code
✅ Environment variables সবসময়
```

---

## Day 82–84 — Saudi Portfolio Polish

**GitHub README প্রতিটিতে:**
- Screenshots
- Architecture diagram
- Copy-paste setup instructions
- "Port Connection" section

**Interview Answers:**
```
Q: "Do you have Claude Code experience?"
A: "হ্যাঁ। আমি Claude Code দিয়ে ৬টি production-grade project
   বানিয়েছি — port billing, vessel tracking, CF agent portal।
   এগুলো Saudi port operations-এ directly applicable।"

Q: "You can't write code manually — is that a problem?"
A: "না। Saudi port-এ আমার কাজ port operations digitize করা।
   আমি port domain বুঝি — ১২ বছরের experience। Claude Code
   আমার technical tool। Output-টাই important।"
```

---

## Day 85–90 — Final Saudi Dashboard + Capstone

**Saudi Port Dashboard (Day 85–88):**
```
Build Saudi Port Operations Dashboard.
Features: vessel queue status, berth allocation,
CF agent billing portal (wharfrent), revenue reports,
alert system (overdue cargo, deadlines).
Node.js + Express + SQLite + HTML/CSS/JS.
Proper layers. Enter Plan Mode. Architecture first.
```

**Day 90 — Final Checkpoint:**
```
✅ "আমি এই codebase explain করতে পারি"
✅ "Bug হলে কী করতে হবে জানি"
✅ "Next feature add করতে পারবো"
✅ "Saudi interview-এ projects দেখাতে পারবো"
✅ "Claude Code আমার tool — এটা আমাকে empower করে"
```

---

---

# PHASE 7 — AI-Assisted DevOps + Linux + AWS (Day 91–120)

> এই phase থেকে তুমি DevOps Engineer হিসেবে AI use করতে শিখবে।
> প্রতিটা task-এ Claude Code ব্যবহার করবে।

---

## Day 91–95 — Linux Fundamentals (AI-Assisted)

**Day 91 — File System + Navigation:**

**Prompt to Claude:**
```
I'm learning Linux for a Saudi port IT DevOps role.
Teach me today's topic: Linux file system hierarchy.
- Explain what each major directory does (/etc, /var, /home, /opt, /tmp)
- Give me 5 practical commands I'll use daily
- Create a cheat sheet I can save
- Give me a hands-on exercise to practice
Port context: I'll manage servers running port management software.
```

**Hands-on Tasks:**
```bash
# Claude generate করবে এবং explain করবে:
ls -la /etc
pwd && whoami
find /var/log -name "*.log" -mtime -1
df -h && free -h
ps aux | grep nginx
```

**Day 92 — User Management + Permissions:**
```
Claude prompt: "Teach me Linux user management and file permissions.
Focus on: useradd, passwd, chmod, chown, sudo.
Create exercises for managing port application users."
```

**Day 93 — Process Management:**
```
Claude prompt: "Teach me Linux process management.
systemctl, journalctl, ps, kill, top, htop.
Saudi port context: managing port software services."
```

**Day 94 — Networking Basics:**
```
Claude prompt: "Teach me Linux networking commands.
ip, netstat, ss, curl, wget, ping, traceroute, nmap basics.
How to troubleshoot connectivity to port management APIs."
```

**Day 95 — Shell Scripting with AI:**
```
Claude prompt: "Help me write a shell script that:
1. Checks if port management service is running
2. If down: restarts it and sends alert email
3. Logs the event with timestamp to /var/log/port-monitor.log
4. Runs every 5 minutes via cron
I'll use this in Saudi port IT infrastructure."
```

---

## Day 96–100 — Docker + Containers (AI-Assisted)

**Day 96 — Docker Concepts:**
```
Claude prompt: "Teach me Docker fundamentals for a DevOps role.
- What is a container vs VM
- Docker architecture
- 10 most important commands
- Port connection: containerizing my port billing app"
```

**Day 97 — Dockerfile Writing:**
```
Claude prompt: "Write a production-ready Dockerfile for my
Node.js + Express + SQLite port billing application.
Include: multi-stage build, non-root user, health check,
proper .dockerignore. Explain every line."
```

**Day 98 — Docker Compose:**
```
Claude prompt: "Write docker-compose.yml for my port management system:
- Node.js backend (port 3001)
- Nginx reverse proxy (port 80)
- Volume for SQLite database persistence
- Environment variables from .env file
Add health checks and restart policies."
```

**Day 99 — Container Best Practices:**
```
Claude prompt: "Review my Dockerfile and docker-compose.yml.
Check for: security issues, image size optimization,
proper layer caching, secrets management.
I'll deploy this to Saudi port IT infrastructure."
```

**Day 100 — Docker Registry:**
```
Claude prompt: "Teach me how to:
1. Push my port-billing image to Docker Hub
2. Set up GitHub Actions to auto-build on push
3. Pull and run on a remote server
Write all commands I need."
```

---

## Day 101–105 — AWS Fundamentals (AI-Assisted)

**Day 101 — AWS Core Services:**
```
Claude prompt: "I'm learning AWS for Saudi port IT DevOps.
Teach me today: core services overview.
EC2, S3, RDS, VPC, IAM, CloudWatch, ECS.
Focus on what a port IT team would actually use.
Give me a visual mental model of how they connect."
```

**Day 102 — IAM + Security:**
```
Claude prompt: "Teach me AWS IAM deeply.
- Users, Groups, Roles, Policies
- Principle of least privilege
- Create a policy for my port billing app:
  needs S3 read/write, RDS read, CloudWatch logs
- What NOT to do (common mistakes)
Write the JSON policy for me and explain it line by line."
```

**Day 103 — EC2 + VPC:**
```
Claude prompt: "Teach me AWS EC2 and VPC for port IT.
- Launch EC2 instance
- Security Groups configuration for port management system
- VPC with public/private subnets
- Bastion host pattern for secure access
Create the AWS CLI commands to set this up."
```

**Day 104 — S3 + CloudFront:**
```
Claude prompt: "Teach me S3 and CloudFront.
- Host my port billing frontend on S3
- CloudFront distribution setup
- Custom domain with Route53
- HTTPS configuration
Give me step-by-step with AWS CLI commands."
```

**Day 105 — RDS Setup:**
```
Claude prompt: "Teach me AWS RDS.
- Migrate my SQLite port billing DB to PostgreSQL RDS
- Multi-AZ for high availability
- Automated backups
- Connection from EC2
Write migration script and connection code."
```

---

## Day 106–110 — Infrastructure as Code (Terraform/CloudFormation)

**Day 106 — Terraform Introduction:**
```
Claude prompt: "Teach me Terraform basics.
I need to provision AWS infrastructure for Saudi port IT.
- What is IaC and why use it
- Terraform workflow: init, plan, apply, destroy
- Write a simple Terraform config: EC2 + Security Group
Explain every line."
```

**Day 107 — Terraform for Port System:**
```
Claude prompt: "Write complete Terraform configuration for
my port management system on AWS:
- VPC with public/private subnets
- EC2 for Node.js backend (t3.medium)
- RDS PostgreSQL (db.t3.small, Multi-AZ)
- S3 for frontend hosting
- CloudFront distribution
- IAM roles with least privilege
- Security Groups
Use variables.tf and outputs.tf properly."
```

**Day 108 — CloudFormation:**
```
Claude prompt: "Convert my Terraform config to AWS CloudFormation.
I need both options for different organizations.
Explain the differences between Terraform and CloudFormation
for a Saudi port IT environment."
```

**Day 109–110 — Terraform State + Remote Backend:**
```
Claude prompt: "Teach me Terraform state management.
- Remote state in S3 with DynamoDB locking
- State file security
- Workspaces for dev/staging/prod environments
Set this up for my port management infrastructure."
```

---

## Day 111–115 — CI/CD Pipeline (AI-Assisted)

**Day 111 — GitHub Actions Introduction:**
```
Claude prompt: "Teach me GitHub Actions for CI/CD.
I need to automate deployment of my port billing app.
- Workflow YAML structure
- Triggers, jobs, steps
- Common actions
Write a basic workflow that runs tests on every PR."
```

**Day 112 — Complete CI Pipeline:**
```
Claude prompt: "Write a complete GitHub Actions CI pipeline for
my Node.js port billing app:
- Trigger: push to main and PRs
- Steps: install, lint, test, security scan (npm audit)
- Test coverage report
- Fail if coverage < 80%
- Notify on failure"
```

**Day 113 — CD Pipeline:**
```
Claude prompt: "Extend my GitHub Actions with CD:
- Build Docker image
- Push to ECR
- Deploy to EC2 via SSH
- Run health check after deployment
- Rollback if health check fails
- Zero-downtime deployment using Blue/Green
Use GitHub Secrets for credentials."
```

**Day 114 — Monitoring + Alerts:**
```
Claude prompt: "Set up monitoring for my port management system:
- CloudWatch metrics and alarms
- Alert if CPU > 80% or error rate > 1%
- Application logs structured JSON to CloudWatch
- Dashboard for vessel processing metrics
- Alert via SNS email to port IT team"
```

**Day 115 — Complete DevOps Pipeline Review:**
Code → GitHub → CI tests → Docker build → ECR → EC2 deploy → Monitor

---

## Day 116–120 — DevOps Portfolio Projects

**Day 116–118 — Port IT Infrastructure Project:**
```
Create a complete IaC repository for Saudi Port IT infrastructure:
- Terraform modules: networking, compute, database, cdn
- GitHub Actions: CI/CD pipeline
- Docker: containerized port management system
- Monitoring: CloudWatch dashboards
- Documentation: architecture diagram + runbook
README must be impressive enough for Saudi IT interview.
```

**Day 119 — Troubleshooting Practice:**
```
Claude prompt: "Give me 10 realistic DevOps troubleshooting scenarios
for a port management system on AWS:
- Application not starting
- Database connection timeout
- High CPU usage
- Deployment failure
- SSL certificate expired
For each: symptoms, diagnosis steps, solution"
```

**Day 120 — Phase 7 Review:**
তুমি এখন AI-assisted DevOps করতে পারছো কিনা verify করো।

---

---

# PHASE 8 — AI-Assisted Software Engineering (Day 121–150)

---

## Day 121–125 — Advanced Node.js + Express Patterns

**Day 121 — Middleware Architecture:**
```
Claude prompt: "Teach me Express.js middleware patterns for
production port management systems:
- Authentication middleware (JWT)
- Request validation middleware
- Error handling middleware
- Rate limiting
- Request logging with correlation IDs
Write complete, production-ready code."
```

**Day 122 — Database Patterns:**
```
Claude prompt: "Teach me database design patterns for port systems:
- Repository pattern with PostgreSQL
- Database migrations (using node-migrate)
- Connection pooling
- Transaction handling
- Indexes for vessel/cargo queries
Write the complete data model for Saudi port operations."
```

**Day 123 — API Design:**
```
Claude prompt: "Design a RESTful API for Saudi Port Operations:
- OpenAPI 3.0 specification
- Versioning strategy (/api/v1/)
- Pagination, filtering, sorting
- Error response standards
- Rate limiting headers
Generate the complete openapi.yaml."
```

**Day 124 — Testing Strategy:**
```
Claude prompt: "Write comprehensive tests for port billing API:
- Unit tests: calculation functions
- Integration tests: API endpoints
- E2E tests: complete billing workflow
- Test data factories
- Code coverage setup
Target: 85% coverage minimum."
```

**Day 125 — Performance Optimization:**
```
Claude prompt: "Optimize my port management API for Saudi operations:
- N+1 query problem identification and fix
- Redis caching strategy (vessel data, billing rates)
- Database query optimization
- Response compression
- Load testing with k6 — simulate 100 concurrent users"
```

---

## Day 126–130 — Python for DevOps + Data

**Day 126 — Python Basics with AI:**
```
Claude prompt: "I know JavaScript. Teach me Python for DevOps.
Focus on: file operations, subprocess, requests, json, csv.
Port context: processing vessel manifests and billing data.
Show me equivalent JS → Python translations."
```

**Day 127 — Python Scripts for Port Operations:**
```
Claude prompt: "Write Python scripts for Saudi port IT:
1. Parse vessel manifest Excel files
2. Calculate wharfrent bulk calculations
3. Generate monthly revenue report CSV
4. Send billing alerts via email (SMTP)
Use pandas, openpyxl, smtplib."
```

**Day 128 — Python + AWS Boto3:**
```
Claude prompt: "Teach me Python boto3 for AWS automation:
- S3: upload/download billing reports
- EC2: start/stop instances based on schedule
- RDS: create snapshots before maintenance
- CloudWatch: custom metrics for port operations
Write scripts I can run as Lambda functions."
```

**Day 129 — Lambda Functions:**
```
Claude prompt: "Build AWS Lambda functions for port automation:
1. Scheduled: daily billing summary email at 6am Saudi time
2. Triggered: process new vessel manifest when uploaded to S3
3. API Gateway: serverless endpoint for CF agent queries
Use Python + boto3. Include error handling and logging."
```

**Day 130 — Data Analysis:**
```
Claude prompt: "Write Python data analysis for Saudi port KPIs:
- Monthly vessel throughput trends
- Average dwell time by cargo type
- Revenue by CF agent
- Peak hours analysis
Use pandas + matplotlib. Generate PDF report."
```

---

## Day 131–135 — Security Engineering

**Day 131 — Application Security:**
```
Claude prompt: "Perform a security audit of my port billing system:
- OWASP Top 10 vulnerabilities
- Input validation gaps
- Authentication weaknesses
- Session management
- Sensitive data exposure
Give me a prioritized remediation plan."
```

**Day 132 — JWT + OAuth2:**
```
Claude prompt: "Implement secure authentication for port management:
- JWT with refresh tokens
- Role-based access (admin, operator, CF agent)
- Password hashing (bcrypt)
- Brute force protection
- Audit logging for all actions
Production-ready code with tests."
```

**Day 133 — AWS Security:**
```
Claude prompt: "Security hardening for port management on AWS:
- VPC security groups audit
- IAM policy review
- S3 bucket policies
- Encryption at rest and in transit
- Secrets Manager for credentials
- CloudTrail for audit logs
- GuardDuty setup
Give me a security checklist."
```

**Day 134 — Penetration Testing Basics:**
```
Claude prompt: "Teach me basic security testing for my port app:
- OWASP ZAP scan setup
- SQL injection testing
- XSS testing
- API security testing with Postman
- Common vulnerabilities to test
Saudi port context: protecting billing and cargo data."
```

**Day 135 — Security Documentation:**
```
Claude prompt: "Write security documentation for Saudi port IT:
- Security policy document
- Incident response playbook
- Password policy
- Access control matrix
- Data classification guide
Format suitable for Saudi government port authority."
```

---

## Day 136–140 — Microservices + Event-Driven Architecture

**Day 136 — Microservices Concepts:**
```
Claude prompt: "Teach me microservices for port IT systems.
- Monolith vs microservices trade-offs
- When to use microservices
- Service decomposition for port operations:
  * Vessel Service
  * Billing Service
  * Notification Service
  * Reporting Service
Draw the architecture for Saudi port system."
```

**Day 137 — Message Queues (SQS/Redis):**
```
Claude prompt: "Implement event-driven architecture for port billing:
- AWS SQS for vessel arrival events
- Processing billing when vessel clears customs
- Dead letter queue for failed processing
- Idempotency for billing events
Write Node.js consumer code."
```

**Day 138–140 — Complete Microservice Build:**
```
Build Vessel Notification Microservice:
- Listens to vessel arrival events via SQS
- Looks up CF agent contact info
- Sends WhatsApp/email notification
- Updates notification log in RDS
- Retry on failure
- CloudWatch metrics
Node.js + AWS SDK. Docker container. IaC with Terraform.
```

---

## Day 141–145 — System Design

**Day 141 — System Design Methodology:**
```
Claude prompt: "Teach me system design interview approach.
Walk me through designing a Port Management System:
- Requirements gathering
- Capacity estimation
- High-level design
- Component deep dive
- Scaling considerations
- Trade-offs discussion
I'll present this in Saudi IT interviews."
```

**Day 142 — Design: Billing System at Scale:**
```
Claude prompt: "Design a billing system for a large Saudi port:
- 500 vessel arrivals/day
- 10,000 CF agents
- Real-time billing updates
- 5-year data retention
- 99.99% uptime requirement
Draw complete architecture. Justify every choice."
```

**Day 143 — Design: Real-time Vessel Tracking:**
```
Claude prompt: "Design real-time vessel tracking system:
- WebSocket for live updates
- Redis for position caching
- PostgreSQL for historical data
- CDN for map tiles
- Mobile-responsive dashboard
Saudi port scale: 50 vessels simultaneously."
```

**Day 144–145 — Design Documentation:**
```
Claude prompt: "Write complete technical design documents:
- Architecture Decision Records (ADRs)
- System design diagrams (draw.io XML)
- API documentation (OpenAPI)
- Runbook for operations team
- Disaster recovery plan
Format: suitable for Saudi port authority presentation."
```

---

## Day 146–150 — Phase 8 Review + Integration

**Day 146–148 — Complete Software Project:**
Build a production-ready Port Staff Management System:
- Node.js backend + PostgreSQL
- Docker + Docker Compose
- GitHub Actions CI/CD
- AWS deployment (EC2 + RDS + S3)
- Security hardening
- Monitoring + Alerts
- Full documentation

**Day 149 — Code Quality Audit:**
সব Phase 4-8 projects-এ code quality check করো।

**Day 150 — Phase 8 Final Review:**
তুমি কি AI-assisted software engineering করতে পারছো?

---

---

# PHASE 9 — Saudi Portfolio Final + Interview Ready (Day 151–180)

---

## Day 151–155 — Portfolio Architecture

**Day 151 — Portfolio Website:**
```
Build professional portfolio website:
- Domain: samiulsumel.com
- Dark theme, professional design
- Sections: About, Skills, Projects, Experience, Contact
- Featured: 3 live project demos
- GitHub activity integration
- Saudi-focused: "Available for Saudi port IT roles"
Deploy on Vercel. Performance score 95+.
```

**Day 152–153 — Project Case Studies:**
প্রতিটি major project-এর জন্য case study লেখো:
```
Template:
## Project: Port Operations Management System

### Problem
[Saudi port-এ কী সমস্যা ছিল]

### Solution
[কী বানালাম — architecture diagram]

### Tech Stack
[Complete stack with versions]

### Impact
[Measurable results — time saved, accuracy improved]

### Saudi Relevance
[এই project Saudi port-এ directly applicable কীভাবে]

### Live Demo + GitHub
[Links]
```

**Day 154–155 — GitHub Profile Polish:**
- Profile README — impressive, Saudi-focused
- All repos: clear README, screenshots, setup guide
- Pinned repos: 6 best projects
- Contribution graph: consistent activity

---

## Day 156–160 — AI Tool Mastery Showcase

**Day 156 — AI Prompting Portfolio:**
তোমার সেরা prompts collect করো — categories:
- Port billing prompts
- DevOps automation prompts
- Security audit prompts
- System design prompts
- Data analysis prompts

**Day 157 — Prompt Library Document:**
```
Create "AI Prompting Playbook for Port IT Operations"
- 50+ ready-to-use prompts
- Categories: billing, vessels, agents, reports, maintenance
- Before/after examples showing quality difference
- ROI calculations: time saved using AI
This document = your unique value proposition for Saudi employers.
```

**Day 158–160 — AI Tools Deep Dive:**
```
Master these AI tools for Saudi IT job:
- Claude Code: complex system building
- GitHub Copilot: daily coding assistance
- Cursor IDE: AI-native development
- ChatGPT: quick lookups
- Perplexity: technical research
- v0.dev: UI component generation

For each tool: strengths, weaknesses, best use cases
Document with examples from your port projects.
```

---

## Day 161–165 — Saudi Job Market Research

**Day 161:**
```
Claude prompt: "Research Saudi Arabia IT job market for port technology:
- Major ports: King Abdulaziz, Jeddah Islamic Port, King Fahad Industrial
- Port operators: Saudi Ports Authority, DP World Saudi, Mawani
- Technology companies serving Saudi ports
- Required skills and certifications
- Salary ranges for port IT roles
- LinkedIn search strategies"
```

**Day 162 — LinkedIn Profile Optimization:**
```
Claude prompt: "Optimize my LinkedIn for Saudi port IT jobs:
- Headline: [AI-assisted suggestions]
- About section: [port expertise + AI skills]
- Experience: highlight AI tools usage
- Skills: list relevant to Saudi port IT
- Featured: my best projects
- Connections: Saudi port industry contacts to target
Write all content."
```

**Day 163–165 — Application Materials:**

**CV (Day 163):**
```
Claude prompt: "Write a professional CV for Saudi port IT role:
- 1.5 pages (Gulf standard)
- Name: MD. Samiul Alam Sumel
- 12 years Mongla Port Authority experience
- AI-powered project portfolio
- Skills: Claude Code, Node.js, AWS, Docker, Python
- Achievements: portbill.vercel.app used by real CF agents
Format: ATS-friendly, Gulf standard layout."
```

**Cover Letter Template (Day 164):**
```
Claude prompt: "Write a cover letter template for Saudi port IT:
- Show port domain expertise (12 years)
- Highlight AI tools proficiency
- Reference specific Saudi port technology needs
- Confident tone about unique value proposition
- Gulf-appropriate professional language
Leave placeholders for company-specific customization."
```

**Day 165 — Job Application Strategy:**
- Target companies list
- Application tracking system
- Follow-up templates
- Referral strategy

---

## Day 166–170 — Technical Interview Preparation

**Day 166 — Technical Questions:**
```
Claude prompt: "Generate 30 technical interview questions for
Saudi port IT DevOps role. Include:
- Linux administration (10 questions)
- AWS/Cloud (10 questions)
- Application deployment (5 questions)
- Security (5 questions)
For each: question, expected answer, how my port experience relates."
```

**Day 167 — System Design Interview:**
```
Practice these system design questions:
1. "Design a vessel tracking system for Saudi port"
2. "How would you architect billing system for 500 vessels/day?"
3. "Design a CF agent portal with real-time updates"
4. "How to migrate legacy port system to cloud?"

Claude-কে interviewer role দিয়ে practice করো।
```

**Day 168 — AI Expertise Questions:**
```
Q: "How do you use AI in your development workflow?"
A: [Prepare with specific examples, metrics, projects]

Q: "Can AI-generated code be trusted in production?"
A: [Your review process, security checks, testing approach]

Q: "What are the risks of AI-assisted development?"
A: [Hallucinations, security, dependency — your mitigations]
```

**Day 169 — Behavioral Interview (STAR method):**
```
Prepare STAR answers for:
- "Tell me about a complex problem you solved"
- "How did you learn a new technology quickly?"
- "Describe a time you automated a manual process"
- "How do you handle pressure and deadlines?"
Use your port experience + AI projects as examples.
```

**Day 170 — Mock Interview:**
Claude-কে interviewer বানাও। Complete mock interview করো।

---

## Day 171–175 — Advanced AI Skills Polish

**Day 171 — Prompt Engineering Expert:**
```
Complete mastery checklist:
✅ XML tags for data separation
✅ Few-shot examples for consistency
✅ Chain-of-thought for complex problems
✅ Role prompting for domain expertise
✅ Output format control
✅ Hallucination prevention
✅ Eval systems for quality assurance
✅ RAG for document-based queries
```

**Day 172 — AI Integration Patterns:**
```
Build an AI-powered Port Assistant:
- Natural language vessel queries
- Automatic billing calculation
- Anomaly detection in billing
- Document summarization
Using: Claude API + RAG + Tool Use + Streaming
Deploy as internal tool for Saudi port staff.
```

**Day 173 — Emerging AI Tools:**
```
Research and experiment with:
- Claude Projects for persistent context
- Claude Code autonomous mode
- AI code review tools
- AI monitoring (AIOps)
Document: how each tool applies to Saudi port IT
```

**Day 174–175 — AI ROI Documentation:**
```
Calculate and document AI productivity gains:
- Hours saved per week using Claude Code
- Error reduction rate vs manual coding
- Time to deploy new features
- Cost comparison: AI tools vs hiring
Create: "AI ROI Report for Port IT Operations"
This is your strongest argument for Saudi employers.
```

---

## Day 176–180 — Final Preparation + Launch

**Day 176 — Complete Portfolio Audit:**
সব projects live এবং working আছে কিনা verify করো।

**Day 177 — Interview Simulation Day:**
সম্পূর্ণ ৩ ঘন্টার mock interview করো।

**Day 178 — Saudi Network Building:**
- LinkedIn: 50+ Saudi port/IT professionals connect করো
- Message template send করো
- Join: Saudi tech communities

**Day 179 — Application Launch:**
প্রথম ১০টা application submit করো।

**Day 180 — Final Reflection:**

```
তুমি ১৮০ দিনে যা অর্জন করেছো:

CLAUDE CODE MASTERY:
✅ Claude Code দিয়ে production-grade apps বানাতে পারো
✅ CLAUDE.md, PRD.md, progress.md workflow জানো
✅ Plan Mode, parallel sessions, loops use করতে পারো
✅ MCP দিয়ে GitHub, browser automate করতে পারো

PROMPT ENGINEERING MASTERY:
✅ Anthropic-এর সব 9 chapters + appendix complete
✅ XML tags, few-shot, chain-of-thought জানো
✅ Hallucination prevent করতে পারো
✅ Eval systems বানাতে পারো

DEVOPS MASTERY:
✅ Linux administration confident
✅ Docker + containers deploy করতে পারো
✅ AWS (EC2, S3, RDS, IAM, CloudWatch) জানো
✅ Terraform দিয়ে IaC করতে পারো
✅ GitHub Actions CI/CD pipeline বানাতে পারো

SOFTWARE ENGINEERING:
✅ Node.js + Express production-grade API
✅ Python scripting for automation
✅ Security best practices
✅ System design করতে পারো

PORTFOLIO:
✅ 10+ live projects with documentation
✅ GitHub profile professional
✅ LinkedIn Saudi-optimized
✅ CV + Cover letter ready
✅ Interview answers prepared

Saudi port IT job-এর জন্য তুমি ready।
Inn Shah Allah — 2027 Q2 তে তুমি Saudi-তে থাকবে।
```

---

---

## Quick Reference Card

```
Perfect Prompt Formula:
Role + Context + Task (numbered) + Input (XML) + Output format + Examples + "Plan Mode first"

Session Start Formula:
Read CLAUDE.md → PRD.md → README.md → progress.md → confirm state → begin

Parallel Session Formula:
Scope: [dir/] ONLY. Do not touch [other dir/]. Task: [specific]. Plan Mode first.

Safe Loop Formula:
Rules: do X only, no logic change, scope bounded, summarize after all files.

Context Rule:
40-50% full → new session → use continuity files to resume

Model Selection:
Everyday/Learning → Sonnet | Complex/Autonomous → Opus | কখনো cheap করো না

DevOps Stack:
Linux → Docker → AWS → Terraform → GitHub Actions → Monitor

AI Tools Stack:
Claude Code → GitHub Copilot → Cursor → Claude API → v0.dev
```

---

## Saudi Job Connection — সবসময় মনে রাখো

```
১৮০ দিন পর তুমি পারবে:

✅ Port billing systems independently build করতে
✅ CF agent portals design করতে
✅ Vessel tracking dashboards deploy করতে
✅ AWS-এ production systems manage করতে
✅ CI/CD pipelines বানাতে এবং maintain করতে
✅ AI tools দিয়ে 10x productivity দেখাতে
✅ Saudi port IT team-এর সাথে technical কথা বলতে
✅ Interview-এ live projects দেখাতে
✅ Unique value: port domain + AI mastery + DevOps

এই combination Saudi recruiter-দের কাছে
অন্য সব candidates থেকে তোমাকে আলাদা করবে।

তুমি শুধু IT person না —
তুমি port domain expert যে AI দিয়ে technology build করে।
সেটাই Saudi-তে দরকার।
```

---

**শুরু করতে হলে "Day 1" লেখো।**

_Roadmap version: 2.0 | 180 Days | Target: Saudi Arabia 2027 Q2 | Inn Shah Allah_

_github.com/samiulAsumel | sa.sumel91@gmail.com | Mongla, Bangladesh | 2026_
