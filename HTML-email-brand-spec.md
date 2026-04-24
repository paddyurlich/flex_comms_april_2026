# HTML Email — Brand Spec & Prompt Reference

A standing reference for creating HTML email content for **Flex Energy** and **Blackcurrent**. It captures the variables that differ between the two brands, a condensed profile of each brand's visual identity (from the official guidelines), and the shared template, dark-mode wiring, and copy standards we've locked in.

---

## How to use this document

When starting a new email, tell Claude:

1. Which brand(s) the email is for — Flex, Blackcurrent, or both
2. The purpose of the email — product update, onboarding, feature announcement, etc.
3. The body copy or rough talking points
4. The CTA label and where it should link

Then ask Claude to "follow `HTML-email-brand-spec.md`" and produce the HTML. If you're making the same email for both brands, ask for them in parallel — body copy should be identical across the two versions, only the brand fields below should differ.

A paste-ready prompt template is at the bottom of this document.

---

## Brand variables (the things that must differ between versions)

| Field | Flex Energy | Blackcurrent |
|---|---|---|
| Logo filename | `farmlands-flex-logo-colour.svg` | `bc-logo-rust.svg` |
| Logo hosted URL | `https://paddyurlich.github.io/flex_comms_april_2026/farmlands-flex-logo-colour.svg` | `https://paddyurlich.github.io/flex_comms_april_2026/bc-logo-rust.svg` |
| Logo `alt` text | `Farmlands Flex` | `Blackcurrent` |
| Logo render width | 240 px | 240 px |
| App URL (CTA link) | `https://app.flexenergy.co.nz/` | `https://app.blackcurrent.io/` |
| Support email | `support@flexenergy.co.nz` | `support@blackcurrent.io` |
| Team sign-off | `The Farmlands Flex team` | `The Blackcurrent team` |
| Footer copyright | `© [year] Farmlands Flex.` | `© [year] Blackcurrent.` |

Product and dashboard names (e.g. "Flex Platform", "Flex Dashboard", "Energy Dashboard") stay the same across both brands — Blackcurrent hosts the same Flex product on its own domain.

---

## Brand profile — Flex Energy

Source: `Flex Brand Guidelines D03.pdf` (April 2025, V1.0).

### Positioning and voice
- **Proposition:** "Flex is the intelligent energy plug-in that unleashes a farm's potential."
- **Impact line:** "Intelligent energy makes farms work harder."
- **Audience:** NZ Farmers and Growers.
- **Personality pillars:** Empowering, Respectful, Tailored, Disruptive, Curious.
- **Brand truths:** Eases burdens (removes cost, uncertainty, effort); Adds value (optimises resources, opens new revenue streams).
- **Co-brand convention:** When paired with Farmlands, always say "Farmlands Flex" in both language and visual lock-ups.

### Typography
- **Brand typeface:** Söhne (Klim Type Foundry).
  - Headlines: **Söhne Breit Kräftig** (extended, bold). 90% leading, sentence case, left-aligned.
  - Body: **Söhne Kräftig / Buch** (bold and regular). 100% leading, sentence case, left-aligned.
  - Details / data / monospace accents: **Söhne Mono Buch** (regular). 100% leading, sentence case.
- **Type colour:** Black or white only.
- **Email fallback (Söhne not web-safe):** `Inter, Helvetica, Arial, sans-serif` — Inter matches the tone closely and is already imported via Google Fonts in the current template.

### Colour palette
Primary:

| Name | HEX | RGB | Notes |
|---|---|---|---|
| White | `#FFFFFF` | 255/255/255 | Background, negative space |
| Stone Grey | `#C8C8B7` | 200/200/183 | Warm neutral, accent bands |
| Black | `#000000` | 0/0/0 | Body text, frames, footer |

Secondary / accent (use sparingly to highlight data or break up black-and-white content):

| Name | HEX | RGB |
|---|---|---|
| Barn Red | `#EB5D44` | 235/93/68 |
| Hay Yellow | `#FACA6C` | 250/202/108 |
| Steel Blue | `#8296D1` | 130/150/209 |

40% tints of the secondary colours are permitted for infographic layering.

### Logo rules (Flex)
- Two colourways only — black or white. Never recoloured.
- Black logo: use on white, cream, or light imagery.
- White logo: use on black, stone grey, steel blue, barn red, hay yellow, or dark imagery.
- Clear space: three of the symbol's vertical bars.
- Minimum size: 20 mm print / 40 px digital (use the Small Usage variant below that).
- Never stroke, recolour, stretch, distort, redraw, or add effects/shadows.

### Visual devices
- **Graphic device:** derived from the Flex symbol — a square grid worked in three tiers (3×3 proportioning).
- **Shape language:** sharp corners, solid fills, square bullets, geometric, simple, reduced.
- **Photography:** top-down or perfectly straight-on to the horizon line; single focal point; warm natural grading (early morning / late afternoon light).

---

## Brand profile — Blackcurrent

Source: `Blackcurrent Brand Guidelines Oct 2025.pdf` (V2.0, Oct 2025).

### Positioning and voice
- **Mission:** "We are a team dedicated to changing the energy landscape. We innovate, we build, and we empower our customers with technology that is powerful, pragmatic, and human. Our mission is to put knowledge and control back into the hands of energy users."
- **Design ethos:** Brutalism — rawness and honesty, function over form, boldness. Strip away the unnecessary, reveal the essential.
- **Values:** Collaborative, Gutsy, Clear.
- **Tone:** Confident, direct, no filler. Bias to action. Challenge assumptions. Smart risks, plain language.

### Typography
- **Brand typeface:** Inter (Rasmus Andersson, rsms.me/inter). Chosen for on-screen clarity.
  - Main headings: **Inter ExtraBold** (800)
  - Secondary headings: **Inter Bold** (700)
  - Body / content: **Inter Medium** (500)
- **Web stack for email:** `'Inter', Helvetica, Arial, sans-serif`. Inter is free via Google Fonts / rsms.me — already imported in the current template.

### Colour palette
Primary / core:

| Name | HEX | RGB | Role |
|---|---|---|---|
| Rust | `#ec5f30` | 236/95/48 | Brand orange — CTAs, accents, headlines on dark |
| Charcoal | `#22201d` | 34/32/29 | Primary dark ground; body text on light |
| White | `#ffffff` | 255/255/255 | Light ground |
| Egg | `#fffaef` | 255/250/239 | Warm cream ground (softer than pure white) |

Accents (sparingly):

| Name | HEX | RGB | Role |
|---|---|---|---|
| Sapphire | `#5597d1` | 85/151/209 | Data / chart accent only — never a primary CTA |
| Steel | `#a2a09e` | 162/160/158 | Secondary grey |
| Lead | `#3a3a3a` | 58/58/58 | Deep grey for sub-frames |

### Logo rules (Blackcurrent)
- Four approved pairings: rust on dark, white on dark, black on light, rust on light.
- Clear space: the small square module at each corner of the mark (derived from the symbol's cap-height module).
- No stroking, stretching, distorting, or recolouring outside the brand palette.

### Visual devices
- **Rust Belt:** a signature vertical orange column used structurally (left-edge belt on decks, case studies, covers). Translates to an email as a sidebar stripe or left-aligned accent bar.
- **Shape language:** Brutalist — heavy type, high contrast, minimal ornamentation, confident blocks of colour.
- **Photography:** black and white only. Form, texture, light and shadow carry the image.

---

## Practical note on the shared email template

The current approved email template was developed in the Flex visual system. Its palette and CTA colour (`#EB5D44` Barn Red) sit very close to Blackcurrent's Rust (`#ec5f30`) — the two oranges read as effectively the same at email-client rendering. Because of that, the same template skin is used for both brands today, differing only in the brand variables at the top of this document.

If we ever want a pure Blackcurrent-skinned email (as opposed to shared-template), swap these values:

| Element | Shared template (Flex-skinned) | Pure Blackcurrent skin |
|---|---|---|
| CTA fill | `#EB5D44` (Flex Barn Red) | `#ec5f30` (BC Rust) |
| Outer frame / footer bg | `#000000` (Flex Black) | `#22201d` (BC Charcoal) |
| Cream / highlight bg | `#fffaef` | `#fffaef` (Egg — same) |
| Stone accent band | `#C8C8B7` (Flex Stone Grey) | remove, or use `#a2a09e` (BC Steel) sparingly |
| Body text on light | `#22201d` | `#22201d` (same) |

Call this out when briefing a Blackcurrent email if brand parity matters more than cross-brand template consistency.

---

## Image hosting

All images (logos and screenshots) are served from the GitHub Pages repo at:

```
https://paddyurlich.github.io/flex_comms_april_2026/
```

Before sending a new email, push any new asset (logo variant, screenshot, illustration) to that repo. Filenames with spaces must be URL-encoded in the `src` (`Screenshot%20Power%20Graph.png`).

Do **not** inline images as base64 in the approved/sendable version — hosted only. Keeps file size small and lets you update imagery post-send.

---

## Dark mode (must be included in every email)

Every email must adapt correctly across Apple Mail, iOS Mail, most webmail, and Outlook.com / Office 365. Wire all of the following.

Head meta:

```html
<meta name="color-scheme" content="light dark">
<meta name="supported-color-schemes" content="light dark">
```

CSS:

```css
:root { color-scheme: light dark; supported-color-schemes: light dark; }

/* Apple Mail, iOS Mail, most webmail */
@media (prefers-color-scheme: dark) {
  .dm-light-bg   { background-color: #1c1c1c !important; }
  .dm-stone-bg   { background-color: #2a2a28 !important; }
  .dm-dark-text  { color: #FFFFFF !important; }
  .dm-dark-text strong { color: #FFFFFF !important; }
  .dm-border-dark { border-top-color: #2a2a2a !important; }
}

/* Outlook.com / Office 365 webmail */
[data-ogsc] .dm-light-bg   { background-color: #1c1c1c !important; }
[data-ogsc] .dm-stone-bg   { background-color: #2a2a28 !important; }
[data-ogsc] .dm-dark-text  { color: #FFFFFF !important; }
[data-ogsc] .dm-dark-text strong { color: #FFFFFF !important; }
[data-ogsb] .dm-light-bg   { background-color: #1c1c1c !important; }
[data-ogsb] .dm-stone-bg   { background-color: #2a2a28 !important; }
```

Apply `dm-light-bg` / `dm-stone-bg` to every `<td>` with a white or cream/stone background, and `dm-dark-text` to every text block inside those sections. The header row holding the logo stays white in both modes so the logo keeps its colour fidelity.

For a pure Blackcurrent skin, the dark-mode overrides can be tuned to land on `#22201d` (Charcoal) instead of `#1c1c1c` for a slightly warmer dark, matching the BC palette.

---

## Typography & colours in the current shared template

- Font stack: `'Inter', Helvetica, Arial, sans-serif` (Inter imported from Google Fonts). Substitutes well for both Söhne (Flex) and Inter (Blackcurrent's native face) without additional licensing.
- Optional monospace accent: `'IBM Plex Mono'` (stands in for Söhne Mono).
- Body text: `#22201d` (works for both brands).
- Accent / CTA / link colour: `#EB5D44` (close match for both Flex Barn Red and BC Rust `#ec5f30`).
- Cream highlight: `#fffaef` (also the BC Egg value).
- Stone band (light mode): `#C8C8B7` (Flex Stone Grey — neutral enough to read cleanly in the BC version too).
- Outer frame / footer: `#000000` with white copy.

---

## Layout conventions

- Table-based layout (email-client safe), max content width 600 px.
- Alternating section rhythm: white → stone → white → stone, framed in black.
- Full-bleed screenshots in dedicated rows without side padding.
- Single primary CTA button per email — solid orange fill, white text, ~14 px padding all round, bold.
- Footer on black: copyright line, support email link, small legal disclaimer if needed.

---

## Copy style rules

- **No em dashes (—) or en dashes (–).** Replace with commas, colons, periods, or restructure.
- **Use contractions** ("it's", "you're", "we've") — conversational.
- **Lead with concrete benefit,** not marketing abstraction. "See how energy is flowing through your system" beats "Unlock powerful insights".
- **Copy is shared across both brands.** Only the brand fields in the table above should differ between the Flex and Blackcurrent versions.
- **Tone:** respectful and practical for Flex (farming audience); direct and gutsy for Blackcurrent (Brutalist voice). For shared-template emails, land somewhere in the middle — plain, confident, no fluff. That tone serves both.
- Preheader text should summarise the email in under ~110 characters — it's what previews in the inbox.
- Sentence case throughout. No Title Case Headlines (matches both brand guidelines).

---

## File naming convention

Final approved deliverables follow this pattern:

```
Flex-platform-update-email_<Month><Year>_approved.html
Blackcurrent-platform-update-email_<Month><Year>_approved.html
```

Example: `Flex-platform-update-email_April2026_approved.html`. Drafts in progress can use any working name; rename to `_approved` at sign-off.

---

## Paste-ready prompt template

> Create an HTML email for **[Flex Energy / Blackcurrent / both brands]** following `HTML-email-brand-spec.md` — hosted images, dark-mode wiring, shared template, no em dashes.
>
> **Subject:** [subject line]
> **Preheader:** [preview text, < 110 chars]
> **Purpose:** [one-sentence description of what this email is for]
> **Body talking points:**
> - [point 1]
> - [point 2]
> - [point 3]
>
> **CTA button:** "[button label]" linking to the brand's App URL.
>
> If both brands: produce two files in parallel with identical copy, differing only in logo, logo alt, app URL, support email, sign-off, and footer copyright per the brand table. Use the shared template skin unless I ask for a pure Blackcurrent-skinned variant.

---

## Reference files in this folder

- `Flex-platform-update-email_April2026_approved.html` — canonical Flex template (current shared skin)
- `Blackcurrent-platform-update-email_April2026_approved.html` — canonical Blackcurrent template (current shared skin)
- `farmlands-flex-logo-colour.svg` — source Flex logo
- `Blackcurrent Logo - bc-logo-rust.svg` — source Blackcurrent logo
- `Flex Brand Guidelines D03.pdf` — full Flex brand guidelines
- `Blackcurrent Brand Guidelines Oct 2025.pdf` — full Blackcurrent brand guidelines
