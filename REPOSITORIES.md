# Malik Hashir — Repository Audit & Portfolio Map

> **Identity rule:** `iamhashir`, `ihashirr`, and Malik Hashir are the same developer.
>
> `iamhashir` is the target **canonical professional account**. `ihashirr` is treated as a legacy identity whose contribution history should be preserved.

This file ranks the engineering work behind both personal GitHub accounts plus relevant collaborative work in `minapong`.

A weak or missing README does **not** make a project weak. Ranking is based primarily on the implementation itself.

## Ranking method

1. Source-code and architecture depth
2. Real-world usefulness
3. Technical distinctiveness
4. Completeness and feature surface
5. Collaboration / systems complexity
6. Presentation quality only after the above

### Audit legend

- **✅ Audited** — implementation inspected directly
- **◐ Partially audited** — enough source inspected for placement
- **○ Provisional** — needs deeper source inspection

---

# Strongest engineering work

## Tier S — Flagship material

| Rank | Project | Current owner | Visibility | Audit | Why it matters | Portfolio action |
|---:|---|---|---|---|---|---|
| 1 | [`ft_transcendence`](https://github.com/minapong/ft_transcendence) / **MINA GAMES** | `minapong` | Public | ✅ | Collaborative real-time multiplayer platform with WebSockets, Fastify, Prisma/SQLite, Docker/NGINX, matchmaking, tournaments, multiple games, authentication and the custom **Reactor** JSX/runtime architecture. Malik is documented as PO/PM/Developer and contributed across frontend architecture, Reactor, UI systems and backend work. | **Keep in org. Feature from main profile. Never duplicate/transfer to personal account.** |
| 2 | `mess-manager` | `ihashirr` | Private | ✅ | Modern Expo/React Native operations app with customers, subscriptions, attendance, menus, payments, expenses and orders. Includes SQLite offline persistence, dirty/deleted state, a persistent sync queue, retry behavior and OCR-assisted receipt processing. | **Transfer to `iamhashir` privately. Private flagship / sanitized case study. README upgraded.** |
| 3 | `ipac-operations-app` | `iamhashir` | Private | ✅ | Substantial business/operations mobile application using React Native/Expo and Supabase with operational data, reports, QR/image workflows and a large domain model. | **Keep private. Sanitized case study only.** |
| 4 | [`real_estate_management`](https://github.com/iamhashir/real_estate_management) | `iamhashir` | Public | ✅ | Full-stack real-estate operations product: properties, clients, deal pipeline, agents, commissions, reporting, history and workflow management. | **Public flagship / pin candidate.** |
| 5 | [`IRC`](https://github.com/ihashirr/IRC) | `ihashirr` | Public | ✅ | C++98 non-blocking IRC server using TCP sockets, `poll()`, per-client buffers, parsing/dispatch, registration state, channel state and real protocol commands. | **Transfer to `iamhashir`. Systems flagship. README upgraded.** |
| 6 | [`secret-hitler`](https://github.com/ihashirr/secret-hitler) | `ihashirr` | Public | ✅ | Modern real-time browser multiplayer game using Next.js/React and Convex, with a substantial backend game-state module and dedicated schema. | **Transfer to `iamhashir`, then build a proper architecture README.** |
| 7 | [`Customer_service_agent`](https://github.com/iamhashir/Customer_service_agent) | `iamhashir` | Public | ✅ | WhatsApp Cloud API automation with webhooks, intent routing, conversational state, guided product flows, response rendering and human handoff. | **Public flagship / pin candidate. README upgraded.** |
| 8 | [`Audify`](https://github.com/iamhashir/Audify) | `iamhashir` | Public | ✅ | AI audio publishing app with OpenAI generation, Convex persistence/media, Clerk authentication and searchable/discoverable content. | **Public flagship. Canonical copy already on main account.** |
| 9 | [`Qrcode_nisrine`](https://github.com/ihashirr/Qrcode_nisrine) | `ihashirr` | Public | ✅ | Next.js barcode/sticker generation system using `bwip-js`, Sharp, build-time data validation, GTIN/check-digit rules and generated print assets. | **Strong business tool. Transfer only after reviewing public client/business data.** |
| 10 | [`Code-Smith`](https://github.com/ihashirr/Code-Smith) | `ihashirr` | Public | ✅ | Next.js data/fee-management application with authenticated workflows, payment state, records, uploads and server APIs including bill/PDF generation. | **Transfer to `iamhashir`; README currently undersells it badly.** |
| 11 | [`cv_portfolio`](https://github.com/iamhashir/cv_portfolio) | `iamhashir` | Public | ✅ | Current interactive engineering portfolio using modern Next.js/React, Three.js/R3F, animation systems and Playwright/browser testing. | **Keep as canonical portfolio codebase.** |
| 12 | [`42curcus`](https://github.com/iamhashir/42curcus) | `iamhashir` | Public | ✅ | Consolidated 42 engineering archive spanning C/C++, Unix, graphics, processes, concurrency, networking, Docker and the final MINA GAMES submodule. | **Keep public. This is the canonical home for most older 42 work.** |

---

## Tier A — Strong supporting projects

| Project | Current owner | Audit | What the implementation shows | Action |
|---|---|---|---|---|
| [`MINISHELLING`](https://github.com/iamhashir/MINISHELLING) | `iamhashir` | ✅ | C shell with tokenization, parsing/AST, expansion, heredocs, pipelines, redirections, built-ins, signals and process execution. | Keep public. README upgraded. |
| `cube` | `ihashirr` | ✅ | Real Cub3D-style C raycaster: map parsing/validation, player initialization, raycasting, textured-wall rendering and movement. | **Do not transfer separately:** equivalent Cub3D work is already represented in `42curcus/rank4/cub3d`. |
| [`philo`](https://github.com/iamhashir/philo) | `iamhashir` | ✅ | Dining Philosophers concurrency work using threads, mutexes, timing and monitoring. | Keep public but secondary; also represented in `42curcus/rank3`. |
| [`Twitter_clone`](https://github.com/iamhashir/Twitter_clone) | `iamhashir` | ✅ | Despite the name, this is a C++/openFrameworks tweet-data visualization/explorer with CSV ingestion and interactive filtering. | Keep; README added. Consider eventual rename. |
| `Movie-Recommendation-System` | `ihashirr` | ✅ | Python/sklearn notebook with CountVectorizer, cosine similarity, numeric normalization, popularity ranking and matplotlib analysis. | Optional transfer; add methodology/results README after transfer. |
| `Arduino` | `ihashirr` | ✅ | ESP8266/FastLED embedded project with an on-device web server, WS2812B lighting effects and ultrasonic-sensor behavior. | **Good embedded/IoT breadth. Optional transfer to main account.** |
| [`tourism_app`](https://github.com/iamhashir/tourism_app) | `iamhashir` | ✅ | React 18 tourism application with routing for all seven Emirates, media-heavy destination pages, map links and componentized UI. | **Canonical tourism source. README upgraded.** |
| [`MultiPage`](https://github.com/iamhashir/MultiPage) | `iamhashir` | ✅ | React Native/Expo food-browsing interface with product model, native-stack navigation, detail screens and animation. | Keep as mobile-development history. README added. |
| `minitalk` | `ihashirr` | ✅ | C client/server IPC using Unix signals with mandatory + bonus implementations. | Do not transfer separately; represented in `42curcus/rank2/minitalk`. |
| `pushing-swap` | `ihashirr` | ✅ | Real Push Swap implementation with sorting algorithm, checker, linked-list/state handling and validation. | Do not transfer separately; represented in `42curcus/rank2/push_swap`. |
| `printf-42` | `ihashirr` | ◐ | Custom formatted-output implementation. | Do not transfer separately; represented in `42curcus/rank1/ft_printf`. |
| `42-libft` | `ihashirr` | ◐ | Foundational C utility library. | Do not transfer separately; represented in `42curcus/rank0/libft`. |
| [`clevland`](https://github.com/iamhashir/clevland) | `iamhashir` | ◐ | BiomedCLIP/local-model medical-image/chat prototype. | Technically interesting, but resolve provenance/authorship presentation before featuring. |
| `desizaiqa` | `iamhashir` | Private | ○ | Private AI/design-related work. | Deeper audit before case-study decision. |

---

# Work already consolidated inside `42curcus`

One major correction from the earlier migration idea: **most old standalone 42 repos do not need to be transferred.**

`iamhashir/42curcus` already contains the progression:

```text
rank0  libft
rank1  born2beroot · ft_printf · get_next_line
rank2  fract-ol · minitalk · push_swap
rank3  minishell · philosophers
rank4  C++ modules · cub3d · netpractice
rank5  C++ modules · ft_irc · inception
rank6  ft_transcendence / MINA GAMES
```

Therefore these legacy standalone repos should normally stay legacy rather than creating duplicates on the main account:

- `ihashirr/42-libft`
- `ihashirr/printf-42`
- `ihashirr/minitalk`
- `ihashirr/pushing-swap`
- `ihashirr/cube`
- old exam repositories

### Exception: `IRC`

`IRC` deserves a standalone transfer because it is strong enough to be a recruiter-facing networking project and is already referenced as the `rank5/ft_irc` submodule.

After `ihashirr/IRC` is transferred to `iamhashir/IRC`, update:

```text
iamhashir/42curcus/.gitmodules
```

from:

```text
https://github.com/ihashirr/IRC.git
```

to:

```text
https://github.com/iamhashir/IRC.git
```

---

# Duplicate / legacy families

## Portfolio family

- `ihashirr/portfolio`
- `iamhashir/hashir-portfolio`
- `iamhashir/cv_portfolio`
- `iamhashir/mit_portfolio` (private)

`ihashirr/portfolio` and `iamhashir/hashir-portfolio` share essentially the same older static portfolio structure/assets. They should **not both be migrated or promoted**.

**Canonical public portfolio:** `iamhashir/cv_portfolio`.

## Audify

- `ihashirr/Audify`
- `iamhashir/Audify`

Use **`iamhashir/Audify`** as the canonical copy. Do not transfer the old duplicate.

## Tourism family

- `iamhashir/tourism_app` ← **canonical source**
- `iamhashir/tourismApp`
- `iamhashir/tourism_final`
- `iamhashir/Travel_tourism_app`
- `iamhashir/tourism_test`

Keep `tourism_app` as the meaningful source repo. The others should eventually be archived/unfeatured after verifying nothing unique remains.

## Philosophers

- `ihashirr/philo` — empty legacy repo
- `iamhashir/philo` — populated
- `42curcus/rank3/philosphers` — consolidated curriculum copy

Use the `iamhashir` version / `42curcus` story.

---

# Repositories that should NOT move to the main account

| Repository | Why |
|---|---|
| `ihashirr/web` | Source/README identifies the upstream project as `hoisie/web`; not suitable as Malik portfolio work. |
| `ihashirr/github` | GitHub Skills “Introduction to GitHub” tutorial/template. |
| `ihashirr/DRUM_KIT_PROJECT` | Current repository contains only a tiny README and no implementation. |
| `ihashirr/42Core` | Empty. |
| `ihashirr/rush-group-project` | Empty. |
| `ihashirr/philo` | Empty duplicate. |
| `ihashirr/portfolio` | Legacy duplicate of older portfolio material. |
| `ihashirr/Audify` | Duplicate; canonical copy already exists on `iamhashir`. |
| exam repos | Useful history, weak recruiter signal and already covered by the broader 42 story. |

---

# Recommended account-transfer queue

Repository ownership transfer must be done manually in GitHub settings. The connector currently cannot change repository ownership.

## Phase 1 — High-value transfers

1. **`ihashirr/IRC` → `iamhashir/IRC`**
   - public systems/networking flagship
   - README already upgraded
   - after transfer, update `42curcus/.gitmodules`

2. **`ihashirr/mess-manager` → `iamhashir/mess-manager`**
   - keep private
   - strongest modern mobile/offline-first project
   - README already upgraded

3. **`ihashirr/secret-hitler` → `iamhashir/secret-hitler`**
   - public real-time project
   - rebuild README after transfer

4. **`ihashirr/Code-Smith` → `iamhashir/Code-Smith`**
   - public product/data workflow app
   - rebuild README after transfer

## Phase 2 — Useful breadth

5. **`ihashirr/Qrcode_nisrine` → `iamhashir/Qrcode_nisrine`**
   - only after checking whether all public client/business information is appropriate to expose

6. **`ihashirr/Movie-Recommendation-System` → `iamhashir/Movie-Recommendation-System`**
   - optional ML/data-science supporting project

7. **`ihashirr/Arduino` → `iamhashir/Arduino`**
   - optional embedded/IoT supporting project

---

# README / presentation work completed

- ✅ `iamhashir/42curcus`
- ✅ `iamhashir/Audify`
- ✅ `iamhashir/Customer_service_agent`
- ✅ `iamhashir/cv_portfolio`
- ✅ `iamhashir/MINISHELLING`
- ✅ `iamhashir/Twitter_clone`
- ✅ `iamhashir/MultiPage`
- ✅ `iamhashir/tourism_app`
- ✅ `ihashirr/mess-manager`
- ✅ `ihashirr/IRC`

## Highest-value README work remaining

1. `secret-hitler` — architecture/state-machine explanation after transfer
2. `Code-Smith` — replace generic/default presentation after transfer
3. `Movie-Recommendation-System` — methodology/results README if transferred
4. `Arduino` — explain hardware architecture and show physical build/media if transferred
5. `Qrcode_nisrine` — documentation is already strong; review privacy rather than rewrite for length

---

# Main-profile pin strategy after consolidation

The final public six should show different engineering strengths rather than six similar web apps.

### Target set

1. **`minapong/ft_transcendence`** — collaboration + real-time + custom runtime
2. **`iamhashir/42curcus`** — systems progression
3. **`iamhashir/real_estate_management`** — business/full-stack product
4. **`iamhashir/IRC`** — networking / non-blocking C++
5. **`iamhashir/Customer_service_agent`** — external API + automation/state
6. **`iamhashir/secret-hitler`** or **`iamhashir/Audify`** — real-time product vs AI product

`mess-manager` may be technically stronger than several public repos, but if it remains private it should be represented by a sanitized case study rather than forcing it into the public pin set.

---

# Main-account cleanup candidates

These are not deletion instructions. Archive only after verifying that no unique history/content needs to remain prominent.

### Strong archive / unfeature candidates

- `github-slideshow`
- `story`
- empty `pushing-swap`
- `hassan_philo`
- `hasan_philo`
- `Clone_1`
- `Clone_task_3`
- `2nd_clone`
- `React-Clone`
- `42_examRank2`
- `42-exam-lost`
- duplicate tourism variants after canonical verification
- `hashir-portfolio` after confirming `cv_portfolio` is fully canonical

---

# Important presentation rule

The final `iamhashir/iamhashir` profile README should be rebuilt **after** the transfer and cleanup work, not before it.

It should use:

- one controlled custom visual identity
- no broken third-party stat cards
- no generic contribution-snake filler unless it is reliable and actually useful
- factual project descriptions from inspected implementations
- MINA GAMES as visible collaborative proof
- a small number of strong projects
- direct portfolio/CV/contact links
- no inflated impact claims without evidence

---

## Rule going forward

> **Rank the engineering, not the repository name or marketing. Consolidate duplicate history instead of duplicating it again.**
