# ChatGPT Mastery — Operational Reference (March 2026)

> **Maintainer:** Vineet Gupta | AI Systems Architect & Prompt Engineer  
> **Last Updated:** March 24, 2026  
> **Purpose:** End-to-end operational guide for maximizing ChatGPT across all features, tools, model tiers, memory systems, personalization controls, and agentic workflows.

---

## Table of Contents
1. [Core Insight](#core-insight)
2. [Hidden Assumptions to Challenge](#hidden-assumptions-to-challenge)
3. [Model Architecture](#model-architecture-march-2026)
4. [Disabled & Retired Features](#disabled--retired-features)
5. [Query Formulation Strategies](#query-formulation-strategies)
6. [Memory Systems Architecture](#memory-systems-architecture)
7. [Tools, Commands & Features](#tools-commands--features)
8. [GPTs & Specialized Modes](#gpts--specialized-modes)
9. [Personalization & Taxonomy Controls](#personalization--taxonomy-controls)
10. [App Directory & Connectors](#app-directory--connectors)
11. [UI/UX Power Techniques](#uiux-power-techniques)
12. [Plan-Level Capability Matrix](#plan-level-capability-matrix)
13. [Advanced Power Patterns](#advanced-power-patterns)
14. [Prompt Templates by Task](#prompt-templates-by-task)
15. [Special Characters & Syntax](#special-characters--syntax)

---

## Core Insight

ChatGPT in March 2026 is not a chatbot — it is a **layered platform** of:
- Multiple parallel model tiers (Instant / Thinking / Pro)
- Persistent memory across chats and Projects
- An integrated App/Connector ecosystem
- Agentic execution via Codex
- File Library, Health Space, and Pulse intelligence layer

The gap between average and power-user output is almost entirely determined by how deliberately you navigate this architecture.

---

## Hidden Assumptions to Challenge

| Assumption | Reality |
|---|---|
| "GPT-5.4 Thinking is always better" | Instant is faster and sufficient for most tasks; Thinking burns rate limits |
| "Plugins still exist" | Retired; replaced by **Apps** in App Directory (Dec 2025) |
| "Legacy GPT-4o is available" | Retired February 13, 2026 — GPT-4o, GPT-4.1, o4-mini all removed |
| "Custom instructions only apply to new chats" | Fixed Nov 7, 2025 — apply instantly across **all existing chats** |
| "Memory is one system" | Three separate layers: explicit memory, reference chat history, Health memory |
| "Deep Research legacy mode works" | Deprecated March 19 → removed March 26, 2026 |

---

## Model Architecture (March 2026)

> Model picker redesigned **March 17, 2026**.

| Tier | Model | Speed | Best Use | Plan |
|---|---|---|---|---|
| **Instant** | GPT-5.3 | Fastest | Drafts, Q&A, iteration | All paid |
| **Thinking** | GPT-5.4 | Medium | Reasoning, code, research | Plus+ |
| **Pro** | GPT-5.4 Pro | Slowest | High-stakes, minimal errors | Pro only |
| **Mini (fallback)** | GPT-5.4 mini | Fast | Auto rate-limit fallback only | Paid plans |

**Configure menu unlocks:**
- `Auto-switch` toggle (Instant → Thinking based on query complexity)
- Legacy model access
- `Thinking Effort` levels: Light / Standard / Extended

**Context window:** GPT-5.4 Thinking = 256k tokens (128k in / 128k out), expanded February 20, 2026.

---

## Disabled & Retired Features

- ❌ GPT-4o, GPT-4.1, o4-mini — removed February 13, 2026
- ❌ GPT-5, GPT-5.1 Instant/Thinking/Pro — retired March 11, 2026
- ❌ Legacy Deep Research mode — deprecated March 19, removed March 26, 2026
- ❌ Nerdy base style preset — removed March 17, 2026
- ❌ Plugins — replaced by Apps in App Directory
- ❌ Voice on macOS desktop app — retired January 15, 2026
- ❌ GPT-5 Thinking mini (selectable) — retiring within 30 days of March 18, 2026

---

## Query Formulation Strategies

### Core Patterns

1. **Constraint-first:** Start with output format, persona, length — `"Act as [X]. Your task is [Y]. Output as [Z]."`
2. **Mid-response steering:** Upfront plan visible with Thinking/Pro — click `update` in sidebar to redirect before full output
3. **Retry menu upgrade:** Click `···` under any response → regenerate with Thinking or Pro
4. **`@` mentions in Projects:** Reference specific files or saved responses inline
5. **Interruption workflow:** Stop Deep Research or Pro runs mid-stream → inject new constraints → resume

### Thinking Effort Selection

| Effort Level | When to Use |
|---|---|
| **Light** | Quick reasoning, simple logic |
| **Standard** | Most complex tasks |
| **Extended** | Research synthesis, multi-step code, adversarial prompts |

---

## Memory Systems Architecture

| Layer | What It Stores | How to Control |
|---|---|---|
| **Explicit Memory** | Facts you tell it | Settings → Personalization → Memory |
| **Reference Chat History** | Context from past chats | Settings → toggle; shows cited source chats (Plus/Pro) |
| **Health Memory** | Health/medical context | Separate Health space; not used in training |
| **File Library** | All uploaded files (auto-saved) | Natural language queries: `"What did I upload about X?"` |

**File Library** launched March 23, 2026 — web only, Plus/Pro/Business.

### Memory Power Moves
- Explicitly teach ChatGPT client details → lightweight always-on project context
- Use Projects to create isolated memory per client/domain
- Ask: `"Compare what I uploaded this week with the strategy doc from January"`

---

## Tools, Commands & Features

### Agentic Tools

| Tool | Description | Plan |
|---|---|---|
| **Deep Research** | Full-screen report, editable plan, source pinning, app-connected sources (Feb 10, 2026) | Plus/Pro |
| **Codex** | Parallel coding agents in isolated worktrees; review diffs, push PRs; macOS + Windows | Free trial → Plus/Pro |
| **Pulse** | Daily async research from your memory; proactive visual summaries | Pro only |
| **Tasks (in Pulse)** | Scheduled automated prompt execution | Pro only |

### Creation Tools

| Tool | Notes |
|---|---|
| **ChatGPT Images** | Auto-saved at `chatgpt.com/images`; inline editing (Feb 27, 2026) |
| **Sora (Video)** | Credits-based; shared balance with Codex |
| **Interactive Code Blocks** | Write/edit/preview; export diagrams as images (Feb 19 + 27, 2026) |

### Learning Tools

- **Interactive Learning Modules:** 70+ math/science topics; real-time formula manipulation (March 10, 2026)
- **Study Mode + Quizzes:** Step-by-step problem walkthrough

### Commerce Tools

- **Shopping Research:** Personalized buyer's guides using memory + web
- **Instant Checkout:** Buy from Shopify merchants — US only

---

## GPTs & Specialized Modes

- **Custom GPTs:** Available at `chatgpt.com/gpts`; customize system prompts, knowledge files, tool access, actions
- **Health Space:** Sidebar → Health; connects Apple Health + medical records; iOS/web
- **Group Chats:** AI-mediated collaborative sessions — currently NZ, Japan, South Korea, Taiwan only
- **Codex Mode:** Separate agentic mode for parallel coding workflows

---

## Personalization & Taxonomy Controls

### Base Style Presets
`Default` | `Friendly` | `Efficient` | `Professional` | `Candid` | `Quirky`

### Granular Sliders (Settings → Personalization)
- **Warmth:** Low ↔ High
- **Enthusiasm:** Subdued ↔ Expressive
- **Header/List Density:** Prose ↔ Structured
- **Emoji Frequency:** None ↔ Frequent

> Changes apply **instantly across all chats** — no new conversation needed.

### Thinking Effort (Thinking/Pro models only)
`Light` | `Standard` | `Extended`

---

## App Directory & Connectors

- Browse: `chatgpt.com` → sidebar → **App Directory**
- Connectors renamed **Apps** — managed in one panel
- Add **Slack channels** or **Google Drive folders** as live Project sources
- Availability varies by plan and region
- Developers can submit apps for public listing

---

## UI/UX Power Techniques

| Technique | How | Impact |
|---|---|---|
| Clean copy | `Cmd+A` selects only conversation content | Paste-ready transcripts |
| Non-disruptive browsing | `Cmd+click` search results | Opens in new tab, preserves chat |
| Quick access | Hover chat → `⋯` → Pin Chat | Instant access to key threads |
| Bulk file input | Attach up to 20 files per message | Rich multi-document analysis |
| Prompt repair | Edit messages with image attachments | No restart needed |
| Entity deep-dives | Tap highlighted people/places/products | Sourced side panel without new query |
| Voice + text hybrid | Type mid-Voice-session | True multimodal input |
| Visual Voice | Voice answers stream text + images | Richer comprehension |
| Export visuals | Code Blocks → export diagrams as images | Reusable deliverables |
| Credit management | Settings → Codex → Usage Dashboard | Uninterrupted Codex/Sora sessions |

---

## Plan-Level Capability Matrix

| Feature | Free | Go | Plus | Pro | Business |
|---|---|---|---|---|---|
| GPT-5.3 Instant | ✓ | ✓ | ✓ | ✓ | ✓ |
| GPT-5.4 Thinking | via `+` | via `+` | ✓ | ✓ | ✓ |
| GPT-5.4 Pro | ✗ | ✗ | ✗ | ✓ | ✗ |
| Deep Research | limited | limited | ✓ | ✓ | ✓ |
| File Library | ✗ | ✗ | ✓ | ✓ | ✓ |
| Pulse + Tasks | ✗ | ✗ | ✗ | ✓ | ✗ |
| Codex | trial | trial | ✓ | ✓ (2x) | ✓ |
| Health Space | ✓ | ✓ | ✓ | ✓ | ✗ |
| Shared Projects | 5 | 10 | 10 | 100 | custom |
| Ads | ✓ | ✓ | ✗ | ✗ | ✗ |
| Group Chats | limited | — | — | — | — |

---

## Advanced Power Patterns

1. **Project-as-OS:** Load client SOPs, brand voice, and deliverable templates into a dedicated Project per client — every chat inside inherits full context
2. **Pulse for Client Intelligence:** Configure Tasks in Pulse to auto-research competitor signals, niche trends, and client updates daily
3. **Codex for Parallel Dev:** Run 3–5 agents on independent feature branches simultaneously; review diffs; push PRs without context switching
4. **Memory-as-CRM:** Explicitly teach ChatGPT client details, preferences, and project statuses
5. **Deep Research + Source Pinning:** Pin 2–3 authoritative domain sources + allow open web — reduces hallucination drift
6. **Mid-Thinking Steering:** Start Thinking run → observe upfront plan → redirect before full output — improves first-pass quality
7. **File Library Cross-Reference:** `"Compare the brief I uploaded last month with the new spec"` — synthesizes across entire library

---

## Prompt Templates by Task

```
# Research
"Act as a senior [domain] analyst. Research [topic]. Structure output as:
Executive Summary, Key Findings (numbered), Implications, Open Questions.
Use Extended thinking effort."

# Code Generation (Codex)
"Create isolated worktree agents for: [feature 1], [feature 2], [feature 3].
Return diffs for review. Target branch: [branch name]."

# Client Deliverable
"Using [client name] Project context, draft a [deliverable type] for [audience].
Tone: Professional. Length: [X words]. Format: [structure]."

# Daily Intelligence (Pulse Task)
"Every morning at 8am IST: Research latest developments in [industry].
Summarize top 3 signals. Flag anything actionable for [business context]."

# Deep Research
"Research [topic]. In the plan: pin sources [URL1], [URL2].
Allow general web for gaps. Output: full report with citations,
executive summary, and recommended actions."

# Mid-Thinking Injection
"[After seeing upfront plan] Update: also include [X constraint].
Ignore [Y section]. Prioritize [Z angle]."
```

---

## Special Characters & Syntax

| Symbol | Use |
|---|---|
| `@` | Mention files, sources, or Project context in chat |
| `···` | Three-dot menu under responses → retry, copy, regenerate with different model |
| `Cmd+A` | Select conversation content only (not UI chrome) |
| `Cmd+click` | Open links without leaving chat |
| `#` | Header structure in prompts (improves parsing in long prompts) |
| `---` | Section divider in long prompts (improves model structure adherence) |
| `" "` | Quote exact terms for precise retrieval or constraint |
| `[ ]` | Placeholder brackets for templated prompts |
| ` ``` ` | Code fencing for code blocks in prompts and responses |
| `**bold**` | Emphasis in prompts to signal priority constraints |

---

*This repository is a living reference. Last verified against OpenAI release notes: March 23–24, 2026.*
