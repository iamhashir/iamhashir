# Repository Audit — Implementation First

This file is a working map of the repositories connected to my GitHub history.

The ranking is intentionally **not based on README quality or repository names**. A missing README is a presentation problem, not a technical-quality score.

## How projects are ranked

Priority is based on:

1. **Actual implementation depth** — source structure, architecture, algorithms, data flow, state management, networking, persistence, etc.
2. **Real-world usefulness** — whether the project solves an operational/product problem rather than only demonstrating syntax.
3. **Technical distinctiveness** — systems/networking, offline-first design, real-time state, native code, AI/OCR, integrations, etc.
4. **Completeness** — meaningful feature surface, multiple modules, deployability, tests/docs where present.
5. **Presentation** — README/screenshots/demo. This improves recruiter value, but it does not determine the underlying rank.

### Audit legend

- **✅ Code audited** — ranking is based on source files/dependencies/architecture inspected directly.
- **◐ Partially audited** — enough implementation was inspected to place it approximately.
- **○ Provisional** — mainly repository structure/metadata/history; needs a deeper source pass before final judgment.

Two GitHub identities appear in this engineering history:

- `iamhashir` — current primary profile
- `ihashirr` — older CV-linked account/repositories that are also visible through the connected GitHub installation

---

# Overall engineering ranking

## Tier S — Flagship / strongest portfolio material

These projects contain the strongest combination of implementation depth, real-world scope and recruiter value.

| Rank | Project | Account | Visibility | Audit | Why it ranks highly | Presentation action |
|---:|---|---|---|---|---|---|
| 1 | `mess-manager` | `ihashirr` | Private | ✅ | Modern React Native operations app with customers, subscriptions, menus, attendance, payments, expenses and orders. Includes a real SQLite offline cache, dirty/deleted state, queued synchronization/retries and OCR-assisted receipt entry. | **Private flagship / case study. README upgraded.** |
| 2 | `42curcus` / `ft_transcendence` | `iamhashir` | Public | ✅ | Broad systems progression culminating in a real-time multiplayer platform. Strong C/C++ foundation plus WebSockets, Docker, backend architecture and custom frontend runtime work. | **Public flagship / pin.** |
| 3 | `ipac-operations-app` | `iamhashir` | Private | ◐ | Substantial current Expo/React Native operations application using Supabase, charts, QR code generation, image workflows and a multi-module business domain. | **Private flagship / sanitized case study only.** |
| 4 | `real_estate_management` | `iamhashir` | Public | ✅ | Modern full-stack operations product covering properties, clients, deal pipeline, agents, commissions, history, reporting and search. | **Public flagship / pin.** |
| 5 | `IRC` | `ihashirr` | Public | ✅ | Real C++ network server using non-blocking sockets, `poll()`, per-client buffers, command parsing/dispatch, channel/user state and connection lifecycle management. | **Systems flagship. Existing README; polish visually if needed.** |
| 6 | `Customer_service_agent` | `iamhashir` | Public | ✅ | WhatsApp Cloud API system with webhook handling, intent routing, conversational state, guided product flows, response rendering and human handoff. | **Public flagship / pin. README upgraded.** |
| 7 | `secret-hitler` | `ihashirr` | Public | ✅ | Modern real-time browser game built with Next.js/React and Convex. Backend game logic alone is a large stateful module with a dedicated schema. | **Strong realtime project. README should be upgraded, but current connection is read-only.** |
| 8 | `Audify` | `iamhashir` | Public | ✅ | Full-stack AI audio publishing app with OpenAI generation, Convex storage/data, Clerk auth, search/discovery and generated artwork. | **Public flagship / pin. README upgraded.** |
| 9 | `Qrcode_nisrine` | `ihashirr` | Public | ✅ | Practical barcode-control-room application using Next.js, TypeScript, `bwip-js`, Sharp and server/API routes to generate company barcode assets. | **Strong business-tool project. Existing README.** |
| 10 | `cv_portfolio` | `iamhashir` | Public | ✅ | Current portfolio is itself a modern frontend project using Next.js/React, Three.js/R3F, animation systems and Playwright performance/browser tests. | **Pin if recruiter-facing presentation remains polished.** |
| 11 | `MINISHELLING` | `iamhashir` | Public | ✅ | Real shell implementation in C with tokenizer, parser, AST, expansion, globbing, heredoc, built-ins, pipelines, redirections, signals and process execution. | **Strong systems supporting project. README upgraded from two lines.** |
| 12 | `Code-Smith` | `ihashirr` | Public | ✅ | Much stronger than its default README suggests: authenticated student/fee data entry, monthly paid/unpaid state, searchable records, reporting, PDF/XLSX/CSV export APIs and Firebase auth. | **README is badly underselling it; current connection is read-only.** |

---

## Tier A — Strong supporting engineering work

| Project | Account | Audit | What the code actually shows | Action |
|---|---|---|---|---|
| `philo` | `iamhashir` | ✅ | 42 concurrency project around threads, mutexes, timing and synchronization. | Keep public; strong systems proof. |
| `Twitter_clone` | `iamhashir` | ✅ | **Not a web Twitter clone.** Native C++/openFrameworks tweet-data explorer loading a large CSV dataset, rendering responsive UI and topic-based interactive filters. | README added; consider renaming repo eventually. |
| `Movie-Recommendation-System` | `ihashirr` | ✅ | Python/sklearn notebook using CountVectorizer, cosine similarity, numeric normalization, popularity ranking and matplotlib against a movie-opening dataset. | Good ML/data-science supporting project; README missing and repo is read-only here. |
| `clevland` | `iamhashir` | ◐ | BiomedCLIP + local Mistral/Ollama medical-image/chat prototype with local-model inference. | Technically interesting, but **clarify provenance/authorship before featuring** because current README points to another clone source. |
| `MultiPage` | `iamhashir` | ✅ | React Native/Expo food browsing app with category animation, local product model, native-stack navigation and detailed item screens. | README added; useful mobile-development history. |
| `minitalk` | `ihashirr` | ◐ | 42-style Unix inter-process communication project. | Audit source deeper before final placement. |
| `printf-42` | `ihashirr` | ◐ | Custom formatted-output implementation from the 42 curriculum. | Keep as systems/C foundation, not a pin. |
| `42-libft` | `ihashirr` | ◐ | Foundational C utility library from 42. | Keep as technical history. |
| `desizaiqa` | `iamhashir` | Private | ○ | Private AI/design-related project; not enough audited source in this pass to rank confidently. | Deep audit privately before case-study decision. |
| `mit_portfolio` | `iamhashir` | Private | ○ | Newer private portfolio codebase. | Review against `cv_portfolio`; keep only one canonical public story. |

---

## Tier B — Useful breadth / earlier product work

These are real projects, but they should sit behind the flagship set.

| Project | Account | Audit | Notes / action |
|---|---|---|---|
| `tourismApp` | `iamhashir` | ◐ | Large earlier tourism/frontend application. Choose one tourism repo as canonical and archive/test-hide the duplicates. |
| `tourism_app` | `iamhashir` | ◐ | Another substantial tourism variant. Compare code/features against `tourismApp` before choosing canonical version. |
| `tourism_final` | `iamhashir` | ○ | Tourism variant; likely consolidation candidate. |
| `Travel_tourism_app` | `iamhashir` | ○ | Tourism variant; likely consolidation candidate. |
| `tourism_test` | `iamhashir` | ○ | Deployment/test branch-style tourism repo; archive after canonical version is selected. |
| `Monster-Roblox` | `iamhashir` | ○ | Game-development history. Needs source/screenshots audit before deciding whether it deserves stronger placement. |
| `interacctive-surface` | `iamhashir` | ✅ | HTML Canvas drawing surface with mouse drawing, colors, line thickness, resize/reset and audio/assets. Nice creative-coding history, but technically small. |
| `CodeLabII-2020-2021` | `iamhashir` | ○ | University-era development work; useful historical context. |
| `Arduino` | `ihashirr` | ○ | Hardware/creative-computing history. Inspect before deciding if it should be shown in a broader creative-computing portfolio. |
| `cube` | `ihashirr` | ○ | Needs implementation audit before ranking. |
| `DRUM_KIT_PROJECT` | `ihashirr` | ○ | Earlier interactive/web work; useful learning history but not a current flagship. |
| `portfolio` | `ihashirr` | ○ | Older personal portfolio, superseded by newer portfolio work. |
| `hashir-portfolio` | `iamhashir` | ◐ | Older static portfolio. Superseded by `cv_portfolio`; archive/mark legacy. |
| `web` | `ihashirr` | ○ | Generic older web repository; audit before deciding whether it contains unique work. |
| `github` | `ihashirr` | ○ | Older generic repository; low priority until source proves otherwise. |

---

## Tier C — Learning / coursework / small experiments

| Project | Account | Reason / action |
|---|---|---|
| `42utils` | `iamhashir` | Utility/archive material; useful inside the 42 story, weak as a standalone recruiter repo. |
| `minish-under` | `iamhashir` | Minishell-related fragment; consolidate with `MINISHELLING`/`42curcus`. |
| `42sp-piscine` | `iamhashir` | Early 42 exercises. Keep as history or archive. |
| `42_examRank2` | `iamhashir` | Exam practice. Unfeature/archive. |
| `42-exam-lost` | `iamhashir` | Exam-related practice. Unfeature/archive. |
| `42_exam_rank_5` | `ihashirr` | Exam/practice material. Unfeature. |
| `React-Clone` | `iamhashir` | Small clone/learning project unless future code audit reveals more. |
| `Color-Switch-Replica` | `iamhashir` | Replica/learning project. |
| `2nd_clone` | `iamhashir` | Clone/practice naming and older work; audit only if there is reason to preserve publicly. |
| `Clone_1` | `iamhashir` | Clone/practice project. |
| `Clone_task_3` | `iamhashir` | Clone/task project. |
| `react_tail` | `iamhashir` | Small React/Tailwind experiment. |
| `Smart_app_1` | `iamhashir` | **Downgraded after source audit.** It is an older Expo “Fruits Animating Calculator,” not the restaurant-management app from the CV. |
| `web-page` | `iamhashir` | Generic early web project; keep only if a later code audit finds a distinct feature/story. |
| `pushing-swap` | `ihashirr` | 42/practice history; inspect if needed, otherwise keep secondary. |

---

## Tier D — Empty / tutorial / profile noise

| Project | Account | Action |
|---|---|---|
| `github-slideshow` | `iamhashir` | GitHub tutorial → archive. |
| `story` | `iamhashir` | Empty → archive/delete if unnecessary. |
| `pushing-swap` | `iamhashir` | Empty → archive/delete. |
| `hassan_philo` | `iamhashir` | Empty public repo → archive/delete. |
| `hasan_philo` | `iamhashir` | Empty private repo → archive/delete if unnecessary. |
| `philo` | `ihashirr` | Empty/duplicate old-account repo → ignore in favor of `iamhashir/philo`. |
| `42Core` | `ihashirr` | Empty old-account repository → archive/ignore. |
| `rush-group-project` | `ihashirr` | Empty → archive/ignore. |

---

# Profile / infrastructure repository

| Repository | Purpose |
|---|---|
| `iamhashir/iamhashir` | GitHub profile README, profile assets, workflows and this repository-audit file. It is profile infrastructure, not a software-project ranking entry. |

---

# README / presentation priority queue

A strong repository with no README is **not** a weak project. The README is simply the missing interface between the code and a recruiter.

## Completed in this audit

- ✅ `iamhashir/MINISHELLING` — replaced a two-line README with tokenizer/parser/AST/execution architecture documentation.
- ✅ `iamhashir/Twitter_clone` — added README explaining the actual C++/openFrameworks data-visualization implementation.
- ✅ `iamhashir/MultiPage` — added README documenting the React Native food-ordering UI and its true scope.
- ✅ `ihashirr/mess-manager` — replaced stale Firestore-only documentation with the current offline-first SQLite/sync/OCR architecture.

Already improved earlier:

- ✅ `iamhashir/Audify`
- ✅ `iamhashir/Customer_service_agent`
- ✅ `iamhashir/42curcus`
- ✅ `iamhashir/cv_portfolio`

## Highest-value documentation gaps remaining

1. **`ihashirr/Code-Smith`** — default Next.js README badly undersells a real data/fees/report-generation app. **Read-only through the current connection.**
2. **`ihashirr/secret-hitler`** — substantial modern realtime game; needs architecture/game-state README. **Read-only through the current connection.**
3. **`ihashirr/Movie-Recommendation-System`** — no README; add notebook methodology/results summary. **Read-only through the current connection.**
4. **`iamhashir/clevland`** — README exists, but provenance/authorship needs clarification before making it recruiter-facing.
5. **Tourism family** — inspect all variants, choose the strongest one, then give only that version a polished README and archive the rest.
6. **`Monster-Roblox`** — source/screenshot audit before deciding whether documentation will meaningfully raise portfolio value.

---

# Best public-facing set on `iamhashir`

If the goal is a recruiter scanning the **current `iamhashir` profile**, the strongest public mix today is:

1. `42curcus` — systems + realtime architecture
2. `real_estate_management` — modern business/full-stack product
3. `Customer_service_agent` — external API + automation/state
4. `Audify` — AI-enabled full-stack app
5. `cv_portfolio` — modern frontend/performance/design work
6. `MINISHELLING` — direct Unix/process/parser systems proof

`Twitter_clone` is now a much better secondary repo than its name suggests, and could replace `MINISHELLING` for a role emphasizing creative computing/native C++ visualization rather than backend/systems.

Private projects such as `mess-manager` and `ipac-operations-app` may be stronger than several public repos, but they should be represented through **sanitized case studies** rather than exposing client/business data.

---

# Main corrections from the first ranking

The original ranking was too influenced by names and READMEs. Direct source inspection changed several conclusions:

- **`Smart_app_1` moved down** — source shows an older animated fruit calculator, not the modern restaurant app.
- **`MultiPage` moved up** — source shows a real React Native food-ordering interface with navigation, product data and animation.
- **`Twitter_clone` moved up significantly** — it is a native C++/openFrameworks tweet-data visualization, not a generic frontend clone.
- **`MINISHELLING` moved up** — it contains a real tokenizer/parser/AST/expander/executor shell architecture hidden behind a two-line README.
- **`mess-manager` entered the top tier** — its current source contains a serious offline-first mobile architecture and OCR expense workflow.
- **`IRC` entered the top tier** — source shows a genuine nonblocking C++ network server with a `poll()` event loop and command dispatcher.
- **`secret-hitler` entered the top tier** — modern Next/Convex game with a substantial backend state machine.
- **`Code-Smith` moved high** — the default README hides authenticated data entry, fee state, reports and document-export APIs.

---

## Rule going forward

> **Inspect the code first. Improve the README second. Rank the engineering, not the marketing.**

This file should be updated as the remaining provisional repositories receive deeper source audits.
