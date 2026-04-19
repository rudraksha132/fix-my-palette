---
name: fix-my-palette
description: >
  Expert color palette system for web and brand designers. Use this skill whenever a user
  mentions color palettes, brand colors, color contrast, WCAG accessibility, color systems,
  design tokens, dark mode colors, or asks to "fix", "review", "improve", "audit", or "build"
  a color palette. Also triggers for: "what colors should I use", "does my palette work",
  "is this accessible", "help me pick brand colors", "my colors look off", color psychology
  questions, and any request referencing specific brand color strategies. Contains precise
  WCAG contrast ratios, brand color hex codes, shade scale formulas, token naming conventions,
  and the 60-30-10 rule. Always use this skill before answering any color-related design question.
---

# fix-my-palette

A complete color system reference for diagnosing, building, and shipping professional palettes.

## HOW TO USE THIS SKILL

1. Identify task type → find the matching section below
2. For auditing → go to **PART 4: CONTRAST & ACCESSIBILITY**
3. For building from scratch → go to **PART 2: BUILDING THE SYSTEM**
4. For brand inspiration → go to **PART 3: BRAND REFERENCE**
5. For shade scales / tokens → go to **PART 5: SHADE SCALES & TOKENS**
6. For dark mode → go to **PART 6: DARK MODE**
7. For diagnosing mistakes → go to **PART 7: COMMON MISTAKES**

Read `references/brand-hex-codes.md` when user needs exact hex codes for global brands.
Read `references/wcag-pairs.md` when user needs tested accessible color pair examples.

---

## PART 1: COLOR PSYCHOLOGY — WHAT EACH COLOR COMMUNICATES

| Color | Emotion / Signal | Best For | Avoid When |
|-------|-----------------|----------|------------|
| Red | Energy, urgency, appetite, passion | CTAs, food brands, entertainment, sales | Healthcare, finance, trust-first products |
| Blue | Trust, calm, professionalism, security | Finance, tech, healthcare, B2B SaaS | Food brands (suppresses appetite), very creative brands |
| Green | Growth, health, nature, money, freshness | Wellness, eco, fintech, food | Luxury (unless forest/dark green), urgency |
| Yellow | Optimism, attention, speed, cheerfulness | Fast food, retail, children, logistics | Text color (fails contrast), premium/luxury brands |
| Orange | Friendliness, energy, affordability, warmth | Consumer apps, food delivery, creative tools | Enterprise, legal, medical |
| Purple | Luxury, creativity, imagination, royalty | Beauty, education, entertainment, premium SaaS | Outdoors, sports, blue-collar industries |
| Pink | Youthfulness, femininity, boldness | Consumer brands, beauty, lifestyle | Heavy industry, security, finance |
| Black | Power, elegance, sophistication, simplicity | Luxury, fashion, premium tech | Children's brands, food brands, accessibility-heavy products |
| White | Purity, simplicity, space, neutrality | Tech (backgrounds), healthcare, minimalist brands | Standalone use without supporting palette |
| Brown | Earthy, organic, honest, grounded | Coffee, food, organic products, craft brands | Tech, entertainment |

### Key Rule
Color psychology sets direction. Appropriateness to brand context determines if it works. A 2006 study confirmed consumers ask "does this color fit this brand?" — not "what does this color mean?" Context always beats universal theory.

---

## PART 2: BUILDING A COLOR SYSTEM FROM SCRATCH

### Step 1 — Brand Personality Before Color
Write 5 adjectives describing the brand as a person. Then map to psychology. Never start with color.

### Step 2 — Audit Competitor Color Space
List competitors and their primary colors. Find the uncrowded hue. Owning a distinct color = automatic differentiation.

### Step 3 — Assign Roles (Do This BEFORE Picking Shades)

| Role | Usage | % of UI |
|------|-------|---------|
| Primary | Logo, primary buttons, key headers, main brand identity | — |
| Secondary | Section backgrounds, supporting illustrations, softer transitions | — |
| Accent | CTAs, links, badges, status indicators — used sparingly | — |
| Neutral | Text, backgrounds, borders, dividers, disabled states, surfaces | 80–90% |
| Semantic | Error, Warning, Success, Info states | as needed |

### Step 4 — Apply the 60-30-10 Rule

- **60%** → Primary/neutral color (dominant, sets tone)
- **30%** → Secondary color (supporting, softens layout)
- **10%** → Accent color (pops, draws attention, CTAs)

Never exceed 3–5 hue families. More = visual clutter.

### Step 5 — Color Harmony Types

| Type | Description | Use Case | Example Brands |
|------|-------------|----------|----------------|
| Monochromatic | Tints + shades of 1 hue | Clean, premium, minimal | PayPal, Shopify, Oreo |
| Analogous | 3 adjacent colors on wheel | Natural, harmonious, calm | Mastercard, BP |
| Complementary | 2 opposite colors | High contrast, energetic | Lakers, FedEx |
| Split-complementary | 1 base + 2 adjacent to its complement | Balanced contrast, softer than complementary | Many SaaS products |
| Triadic | 3 equidistant colors | Vibrant, playful, dynamic | Burger King, Google |

---

## PART 3: BRAND COLOR REFERENCE

→ For exact hex codes, see `references/brand-hex-codes.md`

### What Makes Brand Colors Iconic

| Brand | Color | Strategy | Why It Works |
|-------|-------|----------|-------------|
| Coca-Cola | Red (#F40009) | Appetite + energy | Red increases heart rate, stimulates impulse. So consistent since the 1890s it's called "Coca-Cola red" — owns the color in beverage category |
| McDonald's | Red + Yellow | Appetite + speed + joy | Red triggers hunger, yellow is the first color eye processes = fastest attention grab at distance |
| Apple | White + Black + Silver | Simplicity + premium + sophistication | Achromatic palette signals confidence. White space = luxury. Works across every medium without modification |
| Nike | Black | Power + elegance + performance | Black projects strength. Works as the simplest possible contrast against white swoosh. Universally premium |
| Spotify | Green (#1DB954) | Differentiation + growth | Chose green to stand out in a tech landscape of blues and reds. Signals innovation and freshness |
| Facebook/Meta | Blue (#1877F2) | Trust + reliability | Blue is most universally preferred color across cultures — ideal for global social platform needing trust |
| Tiffany & Co. | Robin's egg blue (#0ABAB5) | Exclusivity + recognizability | So ownable it's trademarked and called "Tiffany Blue." Luxury through specificity |
| FedEx | Purple + Orange | Reliability + energy | Purple = professional trust, orange = urgency/speed — communicates both simultaneously |
| Starbucks | Dark green (#00704A) | Calm + welcome + nature | Warm, welcoming atmosphere. Invites lingering — opposite of fast food red/yellow urgency |
| Cadbury | Purple (#4B0082 range) | Luxury + indulgence + creativity | Purple signals royalty and imagination — differentiates in a chocolate category full of reds/browns |
| T-Mobile | Magenta | Differentiation | Bright pink in sea of blue/red telecom competitors = instant brand ownership |
| Lyft | Pink | Youth + fun, differentiation | Starkly contrasts Uber's black/white. Positions as the more youthful, fun alternative |
| IBM | Blue (#006699) | Trust + dependability | B2B tech: customers need to feel safe. IBM's blue evokes security and competence |
| Netflix | Red (#E50914) | Excitement + passion + entertainment | Red = excitement of watching. Same psychological trigger as Coca-Cola — passion + energy |
| Barbie | Pink (#FF69B4 range) | Femininity + playfulness | Owns the pink color space so completely that "Barbie pink" became a cultural reference |

### The Differentiation Pattern
Spotify (green in red/blue tech), T-Mobile (pink in blue/red telecom), Lyft (pink in black ride-share) — all succeeded by finding uncrowded color territory. If your competitors all use blue: **do not use blue.**

---

## PART 4: CONTRAST & ACCESSIBILITY (WCAG 2.2)

### Contrast Ratios — The Numbers

| Content Type | AA Minimum | AAA (Enhanced) |
|-------------|-----------|----------------|
| Normal text (< 18px regular, < 14px bold) | **4.5:1** | 7:1 |
| Large text (≥ 18px regular, ≥ 14px bold) | **3:1** | 4.5:1 |
| UI components (borders, icons, inputs) | **3:1** | — |
| Decorative / logos / incidental text | none | — |

### Contrast Formula
`Ratio = (L1 + 0.05) / (L2 + 0.05)` where L1 = lighter luminance, L2 = darker luminance. Range: 1:1 (no contrast) → 21:1 (black on white).

### Quick Reference Pairs (tested)

| Text | Background | Ratio | Result |
|------|-----------|-------|--------|
| #000000 | #FFFFFF | 21:1 | ✅ AAA |
| #595959 | #FFFFFF | 7.0:1 | ✅ AAA |
| #767676 | #FFFFFF | 4.54:1 | ✅ AA |
| #949494 | #FFFFFF | 2.85:1 | ❌ Fails |
| #FFFFFF | #1D4ED8 | 7.2:1 | ✅ AAA |
| #FFFFFF | #0066CC | 7.0:1 | ✅ AAA |
| #FFFFFF | #006400 | 7.1:1 | ✅ AAA |
| #3B82F6 | #FFFFFF | 3.13:1 | ❌ Fails normal text |
| #9CA3AF | #FFFFFF | 1.87:1 | ❌ Fails |
| #6B7280 | #FFFFFF | 4.6:1 | ✅ AA |

### How to Fix a Failing Brand Color (Without Losing Brand Identity)

**Option A — Flip it**: Use brand color as background, put white text ON it.
- White on brand blue #1D4ED8 = 7.2:1 ✅ AAA. Brand color dominates, no violation.

**Option B — Darken the text variant**: Create a `--color-brand-on-light` token that is a darkened version of your brand hue, used only for text.
- Keep hue identical. Lower lightness in HSL until contrast ≥ 4.5:1.

**Option C — Scope the violation**: Use the failing color only on large text (needs only 3:1) or for decorative/icon use where no minimum applies.

**Option D — Add background plate**: Place text on a sufficiently dark/light container rather than directly on the vibrant brand color.

### Accessibility Tools
- **Stark** (Figma plugin + browser) — best for design workflow, WCAG pre-generation
- **WebAIM Contrast Checker** — webaim.org/resources/contrastchecker
- **axe DevTools** (browser extension) — checks rendered output on live pages
- **Adobe Color** — has built-in a11y contrast checker with color blindness simulation
- **Paletton** — vision simulation for protanopia, deuteranopia, tritanopia

### Critical Rule
83.6% of websites have contrast violations (WebAIM 2024). This is the #1 accessibility failure AND a legal liability (ADA, European Accessibility Act 2025). Always test every text/bg pair before shipping.

---

## PART 5: SHADE SCALES & COLOR TOKENS

### The 11-Stop Scale (Tailwind-style naming)

| Stop | Role |
|------|------|
| 50 | Page backgrounds, subtle tints |
| 100 | Hover backgrounds, subtle fills |
| 200 | Borders on light backgrounds, disabled fills |
| 300 | Placeholder text, subtle borders |
| 400 | Disabled text |
| **500** | **Base / brand primary** (sits at midpoint) |
| 600 | Hover state on primary buttons |
| 700 | Pressed/active states, text on light backgrounds |
| 800 | Dark text on light backgrounds |
| 900 | Headings, maximum emphasis |
| 950 | Darkest shade (optional, deep backgrounds) |

### How to Build Scales in HSL (Not HEX)

HSL = Hue, Saturation, Lightness. Use this model — not RGB or HEX — for systematic building.

1. Pick base hue (H). Keep fixed across all stops.
2. Vary Lightness (L): 50-stop = ~97%, 500 = ~50%, 900 = ~15%
3. Vary Saturation: increase S as you darken (dark shades need more saturation to keep hue visible). Decrease S slightly at extremes to avoid washed-out tints.
4. Never blend straight to black (muddy) or straight to white (washed). Adjust S on a curve.

**Squint test**: Convert palette to grayscale. Each stop should be visually distinct. If stops merge, fix step distribution.

### Neutral Scales — The Most Important Part

Neutrals do 80–90% of visible work in any UI. Minimum 9–11 stops required.

**Pro technique — tint neutrals with brand hue at ~5% saturation:**
- Brand is blue (H=215°) → Neutral = `HSL(215, 5%, L%)`
- Brand is amber (H=35°) → Neutral = `HSL(35, 5%, L%)`
- Users don't consciously notice → product feels cohesive, not generic gray

**Avoid medium grays (400–600 range)** — neither dark nor light text passes contrast on medium gray. Stick to light neutrals for backgrounds and dark neutrals for text.

### Semantic Color Tokens (Naming Convention)

Use role-based names. Never reference visual properties.

```
✅ --color-action-primary
✅ --color-text-secondary
✅ --color-surface-elevated
✅ --color-border-subtle
✅ --color-feedback-error
✅ --color-feedback-success

❌ --blue-500
❌ --gray-3
❌ #3B82F6 hardcoded in components
```

**Semantic token structure:**

```
--color-[category]-[variant]

Categories: action, text, surface, border, feedback, icon, overlay
Variants:   primary, secondary, tertiary, disabled, hover, active, inverse
```

**Feedback / Semantic colors (required in every system):**

| State | Token | Light Mode | Dark Mode |
|-------|-------|-----------|----------|
| Error | --color-feedback-error | #B91C1C (7.2:1 on white ✅) | #FCA5A5 |
| Warning | --color-feedback-warning | #92400E (7.0:1 on white ✅) | #FDE68A |
| Success | --color-feedback-success | #155724 (7.0:1 on white ✅) | #86EFAC |
| Info | --color-feedback-info | #1E40AF (8.6:1 on white ✅) | #93C5FD |

---

## PART 6: DARK MODE

### The #1 Dark Mode Mistake
Building dark mode by inverting light mode lightness values. Result always feels like a photographic negative. **Light mode and dark mode are two independent perceptual environments — design them separately.**

### Dark Mode Color Rules

| Rule | Why |
|------|-----|
| Never use pure black (#000000) | Causes halation effect — text "blooms" and hurts eyes, especially for users with astigmatism/dyslexia |
| Never use pure white (#FFFFFF) on dark | Same halation. Use #E2E8F0 or similar (still passes AA at 15:1+) |
| Target body text at 15:1–17:1, NOT 21:1 | Above 17:1 causes eye strain in dark environments |
| Re-test every color pair in dark mode | A link #2563EB that passes AA on white (5.7:1) fails on dark navy #0F172A (3.2:1 — fails) |
| Avoid neon/saturated accents on dark bg | They vibrate and fatigue eyes. Desaturate by 15–20% for dark mode variants |
| Don't invert blindly | Semantic colors (error red) look muddy or painfully saturated on dark surfaces. Validate each |

### Recommended Dark Mode Surface Stack

```
--color-surface-base:      #0F172A  (darkest — page background)
--color-surface-elevated:  #1E293B  (cards, modals)
--color-surface-overlay:   #334155  (dropdowns, tooltips)
--color-border-subtle:     #334155  (dividers)
--color-border-default:    #475569  (input borders)
--color-text-primary:      #E2E8F0  (body text — 15:1 on base ✅)
--color-text-secondary:    #94A3B8  (meta, captions — 4.7:1 on base ✅)
--color-text-disabled:     #475569  (disabled — decorative, no minimum)
```

### Dark Mode Token Pattern
Dark mode = redefine what each semantic slot resolves to. The component code never changes.

```css
:root {
  --color-surface-base: #FFFFFF;
  --color-text-primary: #0F172A;
}

[data-theme="dark"] {
  --color-surface-base: #0F172A;
  --color-text-primary: #E2E8F0;
}
```

---

## PART 7: COMMON PALETTE MISTAKES AND FIXES

| Mistake | Symptom | Fix |
|---------|---------|-----|
| Too many hues | Chaotic, unfocused | Max 3–5 hue families. Use tints/shades for variety, not new hues |
| No shade variation | Flat, one-dimensional | Build 9–11 stop scale. Use all of them |
| Overusing accent/primary | CTA loses power | Reserve saturated color for genuinely important actions only |
| Saturated colors everywhere | Overwhelming, chaotic | Bold saturated = 10% max. Neutrals do 80% of work |
| Medium gray in scale | Wireframe feel, contrast failures | Replace with light or dark grays. Avoid 400–600 neutral range |
| Pure black/white | Eye strain, halation | Use #0F172A or #1A1A1A for black. #F8FAFC or #E2E8F0 for white |
| Trend-chasing palette | Dated in 12 months | Trends in campaigns only. Core palette = timeless |
| Dark mode = inverted light | "Photographic negative" feel | Design both modes independently |
| No documentation | Inconsistent usage over time | Document HEX + RGB + CMYK + usage rules + approved pairs in style guide |
| Cultural blind spots | Offensive or off-tone globally | White = mourning in Asia. Red = luck in China, danger in West. Test with diverse groups |
| Gradients on text | Almost always fails WCAG | Never put gradient text over light/dark backgrounds without tested fallback |

---

## PART 8: COLOR SYSTEM AUDIT CHECKLIST

Run this checklist on any existing palette before shipping.

### Structure
- [ ] Primary, secondary, accent, neutral, semantic roles all defined
- [ ] 60-30-10 distribution planned
- [ ] Max 3–5 hue families
- [ ] Neutral scale has 9–11 stops, no medium-gray dead zone

### Accessibility
- [ ] All normal text pairs tested at ≥ 4.5:1
- [ ] All large text pairs tested at ≥ 3:1
- [ ] All UI components/borders tested at ≥ 3:1
- [ ] No information conveyed by color alone (icons + text labels for states)
- [ ] Error/warning/success states distinguishable without color
- [ ] Tested with color blindness simulator

### Dark Mode
- [ ] Designed independently (not inverted)
- [ ] No pure black or pure white
- [ ] All pairs re-tested in dark mode
- [ ] Semantic colors validated on dark surfaces
- [ ] Links still distinguishable (underlines, not just color)

### Tokens
- [ ] All values in semantic tokens, not hardcoded HEX
- [ ] Token names describe role, not appearance
- [ ] HEX, RGB, CMYK all documented
- [ ] Dark mode tokens structured as CSS variable overrides

### Cross-device
- [ ] Tested on Mac + PC (gamma differences shift saturation)
- [ ] Tested on mobile (different panel calibrations)
- [ ] Tested in bright light + low light
- [ ] Grayscale test passed (distinct steps visible)

---

## QUICK REFERENCE: COLOR ROLES AT A GLANCE

```
PALETTE ANATOMY

┌─────────────────────────────────────────────────┐
│  PRIMARY (60%)    → Brand hero color             │
│  SECONDARY (30%)  → Supports, doesn't compete    │
│  ACCENT (10%)     → CTAs, links, badges only     │
│  NEUTRALS         → Text, bg, borders, surfaces  │
│  SEMANTIC         → Error / Warning / Success / Info │
└─────────────────────────────────────────────────┘

SHADE SCALE ANATOMY

┌──────────────────────────────────────────┐
│  50   → Subtle background tints          │
│  100  → Hover fills                      │
│  200  → Borders on light                 │
│  300  → Placeholder text                 │
│  400  → Disabled                         │
│  500  → BASE / BRAND PRIMARY ← midpoint  │
│  600  → Hover states                     │
│  700  → Text on light (AA ✅)            │
│  800  → Emphasis text                    │
│  900  → Headings / max contrast          │
└──────────────────────────────────────────┘

WCAG IN ONE LINE

Normal text ≥ 4.5:1 | Large text ≥ 3:1 | UI ≥ 3:1
```
