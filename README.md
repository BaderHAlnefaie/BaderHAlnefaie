<h1 align="center">Bader Alnefaie</h1>

<p align="center">
  <em>Building an OS you talk to, a linter for AI,<br>and whatever else won't leave me alone.</em>
</p>

<p align="center">
  <a href="https://baderalnefaie.dev"><img alt="baderalnefaie.dev" src="https://img.shields.io/badge/baderalnefaie.dev-006C35?style=for-the-badge&logo=vercel&logoColor=white&labelColor=1a1a1a" /></a>
  <img alt="CS @ KFUPM" src="https://img.shields.io/badge/CS-KFUPM-006C35?style=for-the-badge&labelColor=1a1a1a" />
</p>

<p align="center">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img alt="Swift" src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" />
  <img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
</p>

<p align="center">
  <img alt="Supabase" src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
  <img alt="Postgres" src="https://img.shields.io/badge/Postgres-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img alt="Prisma" src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img alt="Expo" src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" />
  <img alt="Vercel" src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />
</p>

---

### 🌵 Mirage — the linter for AI

A population of **persona-driven synthetic humans** that see and operate a real product's GUI with their own eyes, inside a sandbox, and return an evidence-backed verdict — deliberately **advisory and non-gating**. Arabic-first (Saudi/Gulf + English).

The canonical `mirage-report.json` is the authority; every UI is a lossy projection of it. Findings are cross-verified before they count, and the measurement laws are versioned like code.

Now running as a **hosted private beta**: the Hub takes a run, a separate credentialed runner executes it durably against a queue, and evidence lands in Postgres — so a crashed worker resumes instead of quietly reporting a finished run. A harness fault caps the verdict at `INCONCLUSIVE`; only product behaviour can produce PASS or BLOCK.

<p>
  <a href="https://mirage-sim.vercel.app"><img alt="Landing" src="https://img.shields.io/badge/Landing-mirage--sim-006C35?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://mirage-hub.vercel.app"><img alt="Hub" src="https://img.shields.io/badge/Hub-mirage--hub-006C35?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://mirage-simulation.vercel.app"><img alt="Console" src="https://img.shields.io/badge/Console-mirage--simulation-006C35?style=for-the-badge&logo=vercel&logoColor=white" /></a>
</p>

<sub>`TypeScript` engine + CLI · `React` + `Vite` console · `Next.js` hub & landing · `Postgres` + containerised runner · sandboxed browsers · source private</sub>

---

### 🔨 Also building

> Private for now — happy to walk through any of them.

<table>
<tr>
<td width="50%" valign="top">

**agentic-phone-os** 🔒

A phone shell with **no app icons**. You talk to it; an agent uses real tools and streams task UI on demand from a schema-locked component catalog — anything malformed gets rejected whole.

Verified on-device: it installs as the Android Home app, so the Home button lands you on the voice surface.

<sub>`Expo` `React Native` `Kotlin` `Supabase` `Zod`</sub>

</td>
<td width="50%" valign="top">

**KFUPM Course Planner** 🔒

Registration is a race, so this one runs the whole chain: **monitor** Banner 9 seat counts into SQLite and alert on the *edge*, not on every poll; **filter** each opening by whether it is actually reachable from the schedule I already hold — `actionable`, `reachable but rejected`, or `dead end`; **solve** for a better week with a bitmask DFS over joint moves.

The Assistant only turns a sentence into **schema-validated solver tool calls**. The AI never creates a schedule — at most it ranks ones the deterministic solver already proved. It also expires itself after the registration deadline instead of polling a dead term forever.

<sub>`Python` `FastAPI` `SQLite` `Anthropic` `Playwright`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Masar Academy** 🔒

Arabic-first (RTL) test-prep and future-skills platform for Saudi students — Qudurat, SAT, IELTS, Business, Enrichment.

23 courses with subscriptions, quizzes, assignments, parent panels, and completion certificates.

<sub>`Next.js 16` `TypeScript` `Prisma 7` `Auth.js v5` `Tailwind v4`</sub>

</td>
<td width="50%" valign="top">

**claude-workflow** 🔒

A local Anthropic-compatible gateway that sits under Claude Code and routes each agent to the model tier its task deserves.

Frontier model for hard debugging, fast tier for lookups. Ported to native Windows.

<sub>`Node.js` `Anthropic API` `Codex` `MIT-derived`</sub>

</td>
</tr>
</table>

---

### 🚀 Out in the world

<table>
<tr>
<td width="50%" valign="top">

#### 🛒 [Smoke Ring](https://github.com/BaderHAlnefaie/Smoke-Ring-Project)

Bilingual (عربي / EN) order-ahead storefront for a food truck. Customers browse, pay, and track their order live; staff run the kitchen from a board that drives each order through its lifecycle.

Money is stored as **integer halalas**, never floats, and prices are always recomputed server-side — the client only ever sends ids and quantities.

<sub>`Next.js 16` `React 19` `Supabase` `Moyasar` `Zustand` `Zod`</sub>

[**→ Live**](https://smoke-ring-project.vercel.app)

</td>
<td width="50%" valign="top">

#### 📊 [ClaudeUsage](https://github.com/BaderHAlnefaie/claude-usage)

Native macOS **menu bar app** for Claude Code usage: live 5-hour and weekly %, reset countdowns, burn rate, projected cap-hit time.

A few MB of RAM — no Electron, no credentials. It dims and shows `—` when data is stale instead of a confidently dead number, and every dollar figure is labelled an estimate.

<sub>`Swift` `SwiftUI` `AppKit`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🏐 [Volleyball-Bot](https://github.com/BaderHAlnefaie/Volleyball-Bot)

Club sign-ups opened exactly 7 days ahead and the good slots went in minutes. The bot reads the month's schedule **calendar image** with Claude Vision, extracts every Level 1 session as JSON, and emails me 3 minutes before sign-ups open.

Started on Tesseract OCR; Claude Vision read the messy grid far more reliably.

<sub>`Python` `discord.py` `Claude Vision`</sub>

</td>
<td width="50%" valign="top">

#### 🧩 What I keep coming back to

- Interfaces where the **model is the interface** — voice, generated UI, agents with real tools
- Tools for the way I actually work, not the way the docs assume
- Bilingual **Arabic-first** products: RTL as a first-class layout, not a flipped afterthought
- Being honest in the UI about what the program doesn't know

</td>
</tr>
</table>

---

<p align="center">
  <a href="https://github.com/BaderHAlnefaie/Smoke-Ring-Project"><img alt="Smoke Ring language" src="https://img.shields.io/github/languages/top/BaderHAlnefaie/Smoke-Ring-Project?style=flat-square&label=smoke-ring&color=006C35" /></a>
  <a href="https://github.com/BaderHAlnefaie/claude-usage"><img alt="ClaudeUsage language" src="https://img.shields.io/github/languages/top/BaderHAlnefaie/claude-usage?style=flat-square&label=claude-usage&color=006C35" /></a>
  <a href="https://github.com/BaderHAlnefaie/Volleyball-Bot"><img alt="Volleyball-Bot language" src="https://img.shields.io/github/languages/top/BaderHAlnefaie/Volleyball-Bot?style=flat-square&label=volleyball-bot&color=006C35" /></a>
  <img alt="Followers" src="https://img.shields.io/github/followers/BaderHAlnefaie?style=flat-square&logo=github&label=followers&color=006C35" />
</p>

<p align="center">
  <sub>The long version, with the work laid out as an orbit: <a href="https://baderalnefaie.dev"><b>baderalnefaie.dev</b></a></sub>
</p>

<p align="center">
  <sub>Ask me about any of the private ones — I like talking about the parts that were hard.</sub>
</p>
