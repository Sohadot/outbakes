# OUTBAKES.com — Site Architecture (Layer 6 spec)

> Section-by-section blueprint, ready for HTML. Derived entirely from Layers 3–5.5. Five sections,
> one scroll, dark-dominant, no domain-sale language. Draft copy shown; hard facts bracketed.

**Global**
- One page, vertical scroll. Dark Carbon ground throughout; one contained ivory panel (Kitchen).
- Fixed/served minimal top bar: `OUTBAKES` (left) · a single quiet link `Enquire` (right). No nav menu.
- One primary action for the whole page — a private enquiry — surfaced only at the end (and the corner link).
- `It Outbakes.` budget for the page: **2** (Territories · The Verb).

---

## 1 — Hero
- **Purpose:** establish OUTBAKES as a performance brand in three seconds; kill any "domain for sale" read.
- **Visual intent:** full-height dark Systems scene — precision oven / controlled heat, Ember at optimum,
  Baked Gold as the single signal. Isolated subject, generous negative space.
- **Copy:**
  - Wordmark: `OUTBAKES`
  - Master line: `Built to Outbake.`
  - Support (one line): `A performance brand for better baking.`
- **CTA logic:** no button competing with the brand. Only the corner `Enquire` link + a quiet scroll cue.

## 2 — Brand Thesis
- **Purpose:** say what OUTBAKES is, by negation, in seconds. No defense, no verbal essay.
- **Visual intent:** dark, typographic, spacious. No imagery (or the faintest texture). Hairline in.
- **Copy:**
  - `OUTBAKES is not a bakery. Not a single product. Not one technology.`
  - `It is a brand position built around one outcome — better baking.`
  - Support: `Not defined by one oven, ingredient, or system — defined by the result they are all trying to improve.`
- **CTA logic:** none. This section only orients.

## 3 — Three Demonstration Territories
- **Purpose:** prove masterbrand range across three distant layers — as *proof environments*, not feature cards.
- **Visual intent:** three scenes lifted from the mockups, in the dark system.
  - **Systems** — the oven scene (dark). Label `Systems`. Line: `Control the variables. Improve the result.`
    → the page's **first** `It Outbakes.` sits here, as the demonstration moment.
  - **Intelligence** — the bake-profile scene (dark). Label `Intelligence`. Line: `Know what changes the bake before the bake changes.`
  - **Kitchen** — the product scene, **contained**: a single warm panel within the dark flow (not full-bleed ivory).
    Label `Kitchen`. Line: `Precision you can taste.` (the one permitted warm serif moment).
  - Each scene carries the concept disclaimer.
- **Copy intent:** one register line per territory; no paragraphs. Let the scenes carry it.
- **CTA logic:** none per scene — range is proof, not a pitch.
- **Containment check:** if Kitchen's panel starts out-shouting Systems/Intelligence, reduce ivory area and serif size.

## 4 — The Verb
- **Purpose:** reinforce the name's rare property — briefly. One linguistic nod, presented as evidence.
- **Visual intent:** stark, typographic, dark. Maximum restraint.
- **Copy:**
  - `Built to Outbake.`
  - `It Outbakes.`  ← the page's **second and final** proof line.
  - One quiet evidence line: `outbake (v.) — to surpass in baking.`  (appears once, small; never explained further.)
- **CTA logic:** none.

## 5 — Acquisition
- **Purpose:** close with authority. A strategic asset, not a listing.
- **Visual intent:** clean, commanding, dark. Wordmark + master-line sign-off.
- **Copy:**
  - `Strategic acquisition.`
  - `Outbakes.com is available for strategic acquisition by a single operator.`
  - `Price upon qualification.`
  - Action: `Begin a private enquiry →` → [contact route — default `agent@sohadot.com`; confirm].
- **Forbidden here:** any BIN/price number, "buy now", marketplace/escrow/fee language, countdown, trader tone.
- **CTA logic:** exactly one action — the private enquiry. Everything else is quiet.

## Footer
- `OUTBAKES` · `Built to Outbake.`
- One muted line: `Brand vision concepts shown are not currently marketed products.`
- No copyright bravado ("A Masterclass in Branding" etc. — removed).

---

## Build notes for HTML
- Rebuild replaces the current `index.html` (which is the domain-sale page to retire).
- Keep it a single static, responsive page; dark theme is the design, but respect the palette tokens.
- Reuse the mockup visual language (the `.dc.html` scenes) as the section visuals — the site should feel
  like the applications, because it was extracted from them.
- Honor the two guardrails at final review: Kitchen containment, verb scarcity (≤2).
