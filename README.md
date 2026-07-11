# IQ Crew — Brand Asset Kit & Site Reference (v1.1)

Everything needed to represent **IQ Crew** consistently — design tokens, fonts, colour palettes, brand guidelines, and rules. 

The primary public gateway and official Brand Book v1.1 live on our GitHub Pages site at [iqcrew.com.au](https://iqcrew.com.au/). Both [`index.html`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/index.html) (site root) and [`brand-book.html`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/brand-book.html) serve the ratified Brand Book content in production.

---

## The Brand in One Sentence
> **IQ Crew is the only Australian Managed Service Provider (MSP) purpose-built to make offshore teams safe for regulated firms.**

**Master Tagline:** *Extend your team, not your risk.*

---

## Directory Index

| Folder / file | Contents |
|---|---|
| [`index.html`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/index.html) | **Site Root.** The live Brand Book v1.1 — governs all public styling, copy, and interactions. |
| [`brand-book.html`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/brand-book.html) | Compatibility alias for the live Brand Book v1.1. |
| [`guidelines-quick-reference.md`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/guidelines-quick-reference.md) | One-page reference sheet for marketing and design teams. |
| [`tokens.css`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/tokens.css) | Exported CSS design tokens (variables) ready for direct inclusion in web projects. |
| [`FONTS.md`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/FONTS.md) | Guidelines on obtaining General Sans and utilizing our open-source JetBrains Mono typography. |
| [`iqcrew-palette-card.png`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/iqcrew-palette-card.png) | Shareable, production-ready design colour palette card. |
| [`logos/svg/`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/logos/svg/) | **Masters.** Infinitely scalable, text converted to outlines (no fonts required). |
| [`logos/png/`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/logos/png/) | Transparent PNG lockups and monograms (horizontal, stacked, 4 colourways, up to 1600w). |
| [`logos/jpeg/`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/logos/jpeg/) | Flattened JPEG lockups pre-set on our exact `Paper` (#FAF7F1) or `Eucalypt` green backgrounds. |
| [`logos/gif/`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/logos/gif/) | Legacy GIF formats for compatibility across email clients and strict platform filters. |
| [`social/`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/social/) | Pre-sized profile avatars and our LinkedIn Banner (1584×396). |
| [`email/`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/email/) | Retina-ready HTML email signature logo lockups. |
| [`favicon/`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/favicon/) | Comprehensive favicon set (`favicon.svg`, 16/32 PNGs, and Apple Touch Icon 180x180). |
| [`stamp/`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/stamp/) | Vector and PNG versions of the **ON THE RECORD** stamp. *(Strictly quarantined).* |
| [`fonts/jetbrains-mono/`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/fonts/jetbrains-mono/) | SIL Open Font License files for JetBrains Mono (TTF and WOFF2). |
| [`CNAME`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/CNAME) | Apex domain mapping configuration routing to `iqcrew.com.au`. |
| [`.github/workflows/deploy.yml`](file:///Users/justyngreen/Repos/IQ%20Crew/iqcrew.github.io/.github/workflows/deploy.yml) | Automated GitOps GitHub Actions workflow enforcing Pages deployment on merge to `main`. |

---

## 01 — Foundations

When writing, designing, or planning, this matrix acts as the absolute tiebreaker for our tone:

| We are | We are not |
|:---|:---|
| **Rigorous** — every claim has a mechanism behind it | **Pedantic** — we do not bury stakeholders in acronyms |
| **Straight-talking** — prices published, limits clearly stated | **Blunt or salesy** — candour is never used as a pitch trick |
| **Calm** — risks are named exactly once, then capability follows | **Alarmist** — fear is a competitor's tool, not ours |
| **Warm** — a properly run crew | **Matey** — no slang, no exclamation marks |
| **Evidence-led** — all technical receipts are one click deep | **Boastful** — no superlatives, no "world-class" |
| **Australian** — spelling, idiom, hosting, and standards | **Nationalistic** — sovereignty is engineering, not flag-waving |

---

## 02 — Design Tokens & Typography

### Colour Palette
Target page weight ratio: **~70% Paper, ~15% Fills, ~10% Ink, ~5% Eucalypt**. *If a page looks green, the balance is wrong.*

| Token | HEX | RGB | CMYK (approx.*) | Application Use | Contrast Ratio |
|---|---|---|---|---|---|
| **Paper** | `#FAF7F1` | `250 247 241` | `0/1/4/2` | Page Backgrounds | Default |
| **Ink** | `#1C201E` | `28 32 30` | `13/0/6/87` | Primary & Body Text | 15:1 (AA+) |
| **Eucalypt** | `#3F6C58` | `63 108 88` | `42/0/19/58` | Accents, Line work | 5.6:1 (AA) |
| **Eucalypt Deep**| `#2C5243` | `44 82 67` | `46/0/18/68` | Buttons, the Wordmark | 7.5:1 (AA+) |
| **Sandstone** | `#D8C4A4` | `216 196 164` | `0/9/24/15` | Structural Fills ONLY | Never text |
| **Sage Tint** | `#E7EDE6` | `231 237 230` | `3/0/3/7` | Section background fills | Fills ONLY |
| **Line** | `#E4DED2` | `228 222 210` | `0/3/8/11` | Rules, Borders, Spacers | Rules ONLY |
| **Record Red** | `#D9531E` | `217 83 30` | `0/62/86/15` | **Quarantined inside the Stamp** | Stamp ONLY |

\* *Always verify with your commercial printer before generating packaging or physical print runs.*

#### Portal (Dark Mode) Variants — Apps/Portal ONLY
*Note: The marketing site is always light. Dark tokens are reserved exclusively for product/dashboard states.*
*   **Portal Ink:** `#151815` (Backgrounds)
*   **Surface:** `#1E2420` (Cards, panels)
*   **Text:** `#EDEBE3` (Primary body text — 13:1 AA+)
*   **Eucalypt Bright:** `#7CAE95` (Action accents, states — 6.4:1 AA)
*   **Line:** `#2C332E` (Structural rules)

### Typography

| Role | Typography Specification | Notes & Constraints |
|:---|:---|:---|
| **Display** | General Sans Bold (700) · 44–56px · -0.028em · lh 1.05 | Sentence case. Exactly **one** display line per screen. |
| **Heading** | General Sans Bold (700) · 26–32px · -0.02em | Sentence case. Never Title Case. |
| **Body** | General Sans Medium (500) · 15–17px · lh 1.6 | Max measure 70ch. |
| **Receipts / Figures** | JetBrains Mono (400–500) · 11–13px | Tabular numerals. Evidence lines, regions, ABN, timestamps. |

> [!IMPORTANT]
> **Production Fonts Constraints**: Live deployments self-host all fonts directly from the repo. External Font CDNs are strictly banned in production to maintain security, privacy, and speed.
> **Language Standards**: Australian English everywhere (organise, colour, licence as noun). En dashes with spaces for asides.

---

## 03 — Voice, Words & Taglines

### Context Matrix (How our Tone Flexes)
*   **Homepage:** Formality: Medium · Energy: Medium · Tech Depth: Low (Receipts 1 click deep).
*   **Trust Centre:** Formality: High · Energy: Low · Tech Depth: High.
*   **Scorecard Report:** Formality: High · Energy: Low · Tech Depth: Medium.
*   **LinkedIn (Kyle):** Formality: Low · Energy: High · Tech Depth: Low-medium.
*   **Proposals / SOW:** Formality: High · Energy: Low · Tech Depth: High. (Plain clauses only).
*   **Errors / Empty States:** Formality: Medium · Energy: Low · Tech Depth: Low.

### Explicit Word Controls

| **Words We Own (Always Use)** | **Words We Ban (Never Use)** |
|:---|:---|
| control, visibility, hardened, standards, evidence | solutions, synergy, "cyber" (standalone noun), world-class |
| on the record, dedicated, properly run | cutting-edge, best-in-class, seamless, unlock, empower |
| *Note: "Sovereign" appears on technical pages/Trust Centre only.* | leverage, peace of mind, military-grade, **guaranteed**, revolutionary, game-changing |
| | Social proof facades ("trusted by thousands" / made-up metrics) |

**Golden Rule for Word Bans**: Never use emojis, exclamation marks, ALL CAPS body copy, or fear-based messaging anywhere, including on external social platforms like LinkedIn.

#### Ratified Rewrites
*   **NEVER:** *Unlock seamless offshore productivity with cutting-edge, world-class security solutions.*
*   **ALWAYS:** *Your offshore team gets managed laptops, locked-down accounts, and a desktop that lives in Sydney.*
*   **NEVER:** *We take security seriously. Your peace of mind is our top priority!*
*   **ALWAYS:** *MFA on every account. Application control on every machine. Every session logged.*
*   **NEVER:** *Submit · Learn more · Get started today!*
*   **ALWAYS:** *Get your Scorecard · See how it works · Book a call*

### Ratified Taglines

1.  **Extend your team, not your risk.** — *MASTER (Heros, everywhere)*
2.  Offshore capability. Onshore control. — *(Decks, one-pagers)*
3.  Your people offshore. Your data onshore. — *(Trust Centre, ads)*
4.  Grow the crew. Keep the controls. — *(LinkedIn, social)*
5.  The safe way to staff offshore. — *(Referral partners, plain-English intros)*
6.  More capability, not more exposure. — *(Email subject lines)*
7.  Your offshore team, properly run. — *(How-it-works headers)*
8.  Offshore staff, on the record. — *(Monitoring contexts, pairs with the stamp)*
9.  Every seat secured. — *(Pricing pages)*
10. Built like it's audited. Because it is. — *(Trust Centre)*
11. Global team. Australian standards. — *(About / Brand pages)*
12. Add people, not attack surface. — *(Technical audiences / Justyn's publications)*

---

## 04 — Signature Devices & Design Doctrine

### 1. The Boundary Motif
All imagery and illustration is derived from real deployment architecture: A person outside, a bordered dedicated environment inside, and a governed secure path connecting them. 
*   Drawn with **Eucalypt line-work on Paper or Sage Tint** backgrounds.
*   Banned: 3D renders, generic flat-people illustrations, icon-chip rows as visual fillers.

### 2. The Receipt Device
Making the voice slider "technical receipts one click deep" literal via interactive `<details>` elements.
*   **Rules**: Under 5 lines, mono font, sentence fragments, stating EXACTLY: *Mechanism*, *Enforcement point*, *Verification cadence*, and *Claims Register row*.
*   **Privacy Guard**: Receipts never expose actual script names, repo paths, exact vendor product names, or infrastructure IDs.
*   **Live Example**:
    ```
    MECHANISM  — tenant provisioned per client at onboarding; no shared subscriptions
    ENFORCED   — isolation boundary set at deployment; cannot be disabled per-user
    VERIFIED   — automated audit, monthly · evidence pack available under NDA
    REGISTER   — claim A2 · status PRINT NOW
    ```

### 3. The ON THE RECORD Stamp
Adopted directly as a visual verification device, not a decoration.
*   **Usage constraints**: May ONLY appear on verified artefacts: Scorecard reports, live assessments, published case studies, Trust Centre, and NDA evidence packs. 
*   **Graphic requirements**: Rotation **must be -6° to -12°** (never straight). `Record Red` (#D9531E) lives **strictly inside the stamp**; it is quarantined from the rest of the site stylesheet.
*   **Forbidden**: Never place on ads, homepage heroes, or marketing fluff. Stamping unverified material kills the device permanently.

### Design Doctrine (Build Constraints)
*   **Banned Tells**: Scroll-triggered fade-ups, Terracotta/warm-clay accents (#D97757 family), glassmorphism, floating 3D shapes, dark-mode-with-acid-green, and testimonial carousels.
*   **Replacement Grammar**: Left-aligned asymmetrical grid layouts (7/5 and 8/4 column splits), real tables with explicit pricing and mono figures, and real specificity (`australiaeast` instead of "the cloud").
*   **Honesty Devices**: Every page MUST terminate in a Colophon declaring ABN, Australian hosting states, privacy details, and real 404/empty states.

---

## 05 — Governance

*   **Which Logo When**: `-primary` on light backgrounds; `-reverse` on dark/green backgrounds; `-mono-ink` on single-colour light reproduction; `-mono-paper` on single-colour dark reproduction. Use monograms for square slots (<90 px) and social avatars.
*   **Two Core Rules Before Anything Ships**:
    1.  **Record Red exists only inside the stamp**, and the stamp goes ONLY on verified artefacts.
    2.  **Every public claim must be a PRINT NOW row in the claims register.** Copy does not get to invent data points.
*   **Changes & Drift Checks**: Edits ship as versioned updates (e.g., v1.1, v2.0) signed off by both founders. Never perform silent stylesheet edits. A quarterly drift check must be executed by comparing the live domain with this Brand Book.
