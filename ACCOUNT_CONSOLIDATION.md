# GitHub Account Consolidation Runbook

## Goal

Make **`iamhashir`** the single recruiter-facing GitHub identity for Malik Hashir while preserving historical contributions made through **`ihashirr`**.

### Identity

- Malik Hashir = `iamhashir` = `ihashirr`
- **Canonical account:** `iamhashir`
- **Legacy contribution account:** `ihashirr`
- **Collaborative organization:** `minapong`

Do **not** delete `ihashirr` during this migration. Historical PRs and contribution attribution should remain attached to that account.

---

# What stays where

## Keep in `minapong`

### `minapong/ft_transcendence`

Keep the MINA GAMES repository in the organization.

Reason:

- it is genuinely collaborative work
- the repository documents team ownership/contributions
- the org context is useful recruiter evidence
- transferring it to a personal account would weaken the collaboration story

Feature this repository from the `iamhashir` profile instead of duplicating it.

## Keep private on `iamhashir`

### `ipac-operations-app`

Do not expose private/client information. Represent it only through a sanitized case study if needed.

---

# Transfer sequence

Do the high-value repositories one at a time so links/submodules can be checked after each move.

## 1. IRC

### Transfer

From:

```text
ihashirr/IRC
```

To:

```text
iamhashir/IRC
```

### GitHub UI

Open the repository while signed in to the account with ownership rights:

```text
Repository → Settings → General → Danger Zone → Transfer
```

Enter the destination owner:

```text
iamhashir
```

and confirm the repository name when GitHub requests it.

### Post-transfer work

After this transfer, update `iamhashir/42curcus/.gitmodules`:

```diff
-[submodule "rank5/ft_irc"]
-    url = https://github.com/ihashirr/IRC.git
+[submodule "rank5/ft_irc"]
+    url = https://github.com/iamhashir/IRC.git
```

The IRC README has already been upgraded before transfer.

### Verify

- repository opens under `iamhashir/IRC`
- commit history is preserved
- `42curcus/rank5/ft_irc` still resolves
- old repository URL redirects correctly

---

## 2. mess-manager

### Transfer

```text
ihashirr/mess-manager
→ iamhashir/mess-manager
```

### Keep private

This project contains substantial modern implementation value, but it should remain private unless intentionally sanitized for public release.

### Already completed

Its README has been updated to document the current implementation:

- React Native / Expo
- SQLite offline cache
- dirty/deleted state
- sync queue and retries
- Firebase synchronization
- receipt OCR workflow
- customer/payment/expense/order/menu/attendance state

### Verify

- privacy remains **Private** after transfer
- history remains intact
- local/remote Git URLs are updated where this repository is actively developed

---

## 3. secret-hitler

### Transfer

```text
ihashirr/secret-hitler
→ iamhashir/secret-hitler
```

### After transfer

Rebuild the README from the implementation, including:

- Next.js / React architecture
- Convex backend/schema
- real-time game state
- lobby / player flow
- game-state transitions
- deployment/demo if still live

Do not market it as a small game clone; the repository contains a substantial stateful backend.

---

## 4. Code-Smith

### Transfer

```text
ihashirr/Code-Smith
→ iamhashir/Code-Smith
```

### After transfer

Replace the weak/default README with documentation of the actual application:

- authenticated workflow
- record/data creation
- payment / bill state
- private/admin screens
- upload flow
- bill API
- PDF-generation API
- search/reporting/export capabilities supported by the code

---

# Phase 2 — Optional supporting transfers

Do these only after the flagship migration is complete.

## 5. Qrcode_nisrine

```text
ihashirr/Qrcode_nisrine
→ iamhashir/Qrcode_nisrine
```

### Before transfer / promotion

Review the public repository for business/client-sensitive material.

The current README contains company-specific operational information, product identifiers and contact/business details. The technical implementation is strong, but recruiter presentation should not expose information that should remain private.

If appropriate, sanitize first; then transfer.

---

## 6. Movie-Recommendation-System

```text
ihashirr/Movie-Recommendation-System
→ iamhashir/Movie-Recommendation-System
```

Optional supporting ML/data-science project.

After transfer, add a README covering:

- dataset used
- feature construction
- CountVectorizer
- cosine similarity
- popularity ranking
- numeric normalization
- visualizations
- limitations of the recommendation methodology

---

## 7. Arduino

```text
ihashirr/Arduino
→ iamhashir/Arduino
```

Optional embedded/IoT breadth.

After transfer, document:

- ESP8266
- on-device HTTP server
- FastLED / WS2812B strip
- ultrasonic sensor
- browser control surface
- lighting/effect state machine

If photographs/video of the physical build exist, they would add much more value than badges.

---

# Do NOT transfer these standalone 42 repositories

The engineering is already represented in `iamhashir/42curcus`.

| Legacy repository | Canonical representation |
|---|---|
| `ihashirr/42-libft` | `42curcus/rank0/libft` |
| `ihashirr/printf-42` | `42curcus/rank1/ft_printf` |
| `ihashirr/minitalk` | `42curcus/rank2/minitalk` |
| `ihashirr/pushing-swap` | `42curcus/rank2/push_swap` |
| `ihashirr/cube` | `42curcus/rank4/cub3d` |
| exam repositories | 42 archive / historical record |

`IRC` is the exception because it is strong enough to deserve a recruiter-facing standalone repository.

---

# Do NOT migrate these legacy/noise repositories

- `ihashirr/web` — repository content/README identifies the upstream project as `hoisie/web`
- `ihashirr/github` — GitHub Skills tutorial repository
- `ihashirr/DRUM_KIT_PROJECT` — currently no meaningful implementation
- `ihashirr/42Core` — empty
- `ihashirr/rush-group-project` — empty
- `ihashirr/philo` — empty duplicate
- `ihashirr/portfolio` — superseded legacy portfolio duplicate
- `ihashirr/Audify` — canonical copy already exists as `iamhashir/Audify`

---

# Main-account cleanup after transfers

Do not perform this until the important transfers are safely complete.

## Archive / unfeature candidates

```text
github-slideshow
story
pushing-swap           # empty iamhashir copy
hassan_philo
hasan_philo
Clone_1
Clone_task_3
2nd_clone
React-Clone
42_examRank2
42-exam-lost
```

## Tourism cleanup

Keep:

```text
iamhashir/tourism_app
```

Review and then archive/unfeature redundant variants:

```text
tourismApp
tourism_final
Travel_tourism_app
tourism_test
```

## Portfolio cleanup

Canonical:

```text
iamhashir/cv_portfolio
```

Legacy:

```text
iamhashir/hashir-portfolio
ihashirr/portfolio
```

---

# `ihashirr` after consolidation

Do **not** delete the account.

Stop creating new work there.

Eventually make its public profile minimal and explicit:

```text
Malik Hashir

Legacy GitHub identity retained for historical contribution attribution.
Active profile: @iamhashir
```

This preserves old PR/contribution attribution while removing recruiter ambiguity.

---

# Main `iamhashir` profile after consolidation

Only rebuild the profile README once the repositories are in their final locations.

## Target pin candidates

1. `minapong/ft_transcendence`
2. `iamhashir/42curcus`
3. `iamhashir/real_estate_management`
4. `iamhashir/IRC`
5. `iamhashir/Customer_service_agent`
6. `iamhashir/secret-hitler` **or** `iamhashir/Audify`

The final choice should optimize for variety:

- real-time collaborative system
- systems/C/C++ depth
- business/full-stack application
- networking
- API/automation
- modern product or AI application

---

# Final profile README rules

The final README should be built from the consolidated repository evidence, not generic GitHub-profile trends.

Use:

- one distinctive self-controlled visual/animation
- short factual intro
- 4–6 strong project entries
- explicit MINA GAMES contribution
- links to portfolio/CV/LinkedIn
- concise stack grouped by actual usage

Avoid:

- broken external stats services
- decorative snake sections with no value
- excessive badges
- fake/unsupported metrics
- generic “passionate developer” copy
- impact claims that cannot be demonstrated

---

# Migration completion checklist

- [ ] Transfer `IRC`
- [ ] Update `42curcus/.gitmodules`
- [ ] Transfer `mess-manager` and preserve privacy
- [ ] Transfer `secret-hitler`
- [ ] Rewrite `secret-hitler` README
- [ ] Transfer `Code-Smith`
- [ ] Rewrite `Code-Smith` README
- [ ] Review/sanitize `Qrcode_nisrine`
- [ ] Decide on ML project transfer
- [ ] Decide on Arduino transfer
- [ ] Archive/unfeature obvious main-account noise
- [ ] Consolidate tourism duplicates
- [ ] Set final six pins
- [ ] Make `ihashirr` a legacy redirect profile
- [ ] Rebuild `iamhashir/iamhashir` README last
