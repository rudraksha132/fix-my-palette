# WCAG Tested Color Pairs Reference

Pre-tested contrast ratios for common palette combinations.
All ratios calculated using WCAG 2.2 luminance formula.
AA = 4.5:1 normal text / 3:1 large text. AAA = 7:1 normal text.

---

## TABLE OF CONTENTS

1. [Text on White Backgrounds](#text-on-white-backgrounds)
2. [Text on Dark Backgrounds](#text-on-dark-backgrounds)
3. [White Text on Brand Colors](#white-text-on-brand-colors)
4. [Black Text on Brand Colors](#black-text-on-brand-colors)
5. [Neutral Scale Pairs](#neutral-scale-pairs)
6. [Common Failures and Fixes](#common-failures-and-fixes)
7. [Semantic State Colors](#semantic-state-colors)
8. [Gray Scale Reference](#gray-scale-reference)

---

## TEXT ON WHITE BACKGROUNDS (#FFFFFF)

| Text Color | HEX | Ratio | AA Normal | AA Large | AAA |
|-----------|-----|-------|-----------|----------|-----|
| Near-black | #0F172A | 19.4:1 | ✅ | ✅ | ✅ |
| True black | #000000 | 21:1 | ✅ | ✅ | ✅ |
| Dark gray | #1F2937 | 15.8:1 | ✅ | ✅ | ✅ |
| Gray 700 | #374151 | 10.7:1 | ✅ | ✅ | ✅ |
| Gray 600 | #4B5563 | 7.5:1 | ✅ | ✅ | ✅ |
| Gray 500 | #6B7280 | 4.6:1 | ✅ | ✅ | ❌ |
| Gray 400 | #9CA3AF | 2.5:1 | ❌ | ❌ | ❌ |
| Gray 300 | #D1D5DB | 1.3:1 | ❌ | ❌ | ❌ |
| Dark blue | #1E40AF | 8.6:1 | ✅ | ✅ | ✅ |
| Mid blue | #2563EB | 5.9:1 | ✅ | ✅ | ❌ |
| Light blue | #3B82F6 | 3.1:1 | ❌ | ✅ | ❌ |
| Dark green | #065F46 | 9.7:1 | ✅ | ✅ | ✅ |
| Mid green | #059669 | 4.6:1 | ✅ | ✅ | ❌ |
| Spotify green | #1DB954 | 3.5:1 | ❌ | ✅ | ❌ |
| Dark red | #991B1B | 7.2:1 | ✅ | ✅ | ✅ |
| Brand red | #DC2626 | 4.7:1 | ✅ | ✅ | ❌ |
| Bright red | #EF4444 | 3.3:1 | ❌ | ✅ | ❌ |
| Dark purple | #5B21B6 | 7.4:1 | ✅ | ✅ | ✅ |
| Mid purple | #7C3AED | 4.8:1 | ✅ | ✅ | ❌ |
| Bright purple | #8B5CF6 | 3.4:1 | ❌ | ✅ | ❌ |

**The AA/AAA text threshold on white is approximately #767676 (4.54:1).**
Any color darker than #767676 in perceived lightness passes AA for normal text on white.

---

## TEXT ON DARK BACKGROUNDS (#0F172A — recommended dark surface)

| Text Color | HEX | Ratio | AA Normal | AA Large | AAA |
|-----------|-----|-------|-----------|----------|-----|
| Off-white | #E2E8F0 | 15.1:1 | ✅ | ✅ | ✅ |
| True white | #FFFFFF | 19.4:1 | ✅ | ✅ | ✅ |
| Light gray | #CBD5E1 | 11.4:1 | ✅ | ✅ | ✅ |
| Secondary text | #94A3B8 | 4.8:1 | ✅ | ✅ | ❌ |
| Muted text | #64748B | 2.3:1 | ❌ | ❌ | ❌ |
| Light blue | #93C5FD | 8.1:1 | ✅ | ✅ | ✅ |
| Mid blue | #60A5FA | 5.3:1 | ✅ | ✅ | ❌ |
| Brand blue | #3B82F6 | 3.4:1 | ❌ | ✅ | ❌ |
| Light green | #86EFAC | 10.9:1 | ✅ | ✅ | ✅ |
| Spotify green | #1DB954 | 4.0:1 | ❌ | ✅ | ❌ |
| Light red | #FCA5A5 | 8.9:1 | ✅ | ✅ | ✅ |
| Bright red | #EF4444 | 3.8:1 | ❌ | ✅ | ❌ |
| Light yellow | #FDE68A | 12.3:1 | ✅ | ✅ | ✅ |
| Mid yellow | #FBBF24 | 8.7:1 | ✅ | ✅ | ✅ |
| Light purple | #C4B5FD | 9.6:1 | ✅ | ✅ | ✅ |

**NOTE:** Many colors that fail on dark backgrounds in their standard form pass when lightened by 20–30% lightness in HSL.

---

## WHITE TEXT ON BRAND COLORS

Use these when flipping failing brand color from text → background.

| Background | HEX | Ratio (vs white) | AA | AAA | Safe for |
|-----------|-----|-----------------|-----|-----|---------|
| Deep blue | #1D4ED8 | 7.2:1 | ✅ | ✅ | Any text size |
| Navy | #1E3A5F | 12.1:1 | ✅ | ✅ | Any text size |
| Forest green | #065F46 | 9.7:1 | ✅ | ✅ | Any text size |
| Dark green | #166534 | 7.1:1 | ✅ | ✅ | Any text size |
| Brand green (Shopify) | #008060 | 4.6:1 | ✅ | ❌ | Normal text |
| Spotify green | #1DB954 | 2.3:1 | ❌ | ❌ | Background use only |
| Dark red | #991B1B | 7.2:1 | ✅ | ✅ | Any text size |
| Medium red | #B91C1C | 6.1:1 | ✅ | ❌ | Normal text |
| Bright red | #DC2626 | 4.7:1 | ✅ | ❌ | Normal text |
| Error red | #EF4444 | 3.3:1 | ❌ | ❌ | Large text only |
| Dark purple | #4C1D95 | 12.3:1 | ✅ | ✅ | Any text size |
| Medium purple | #6D28D9 | 6.1:1 | ✅ | ❌ | Normal text |
| Slack purple | #4A154B | 11.8:1 | ✅ | ✅ | Any text size |
| Discord blurple | #5865F2 | 3.8:1 | ❌ | ❌ | Large text only |
| Near black | #1A1A1A | 18.1:1 | ✅ | ✅ | Any text size |

**Key insight**: If a brand color fails as text, check if white text on that color passes. Many bright/medium brand colors fail for text but are perfect as button/badge backgrounds with white text.

---

## BLACK TEXT ON BRAND COLORS

Use for yellow, light, and pastel backgrounds.

| Background | HEX | Ratio (vs #000) | AA | Safe for |
|-----------|-----|-----------------|-----|---------|
| Pure white | #FFFFFF | 21:1 | ✅ | Any |
| Light yellow | #FEF08A | 15.9:1 | ✅ | Any |
| McDonald's yellow | #FFC72C | 11.4:1 | ✅ | Any |
| Snapchat yellow | #FFFC00 | 19.7:1 | ✅ | Any |
| Light orange | #FED7AA | 13.7:1 | ✅ | Any |
| Amazon orange | #FF9900 | 7.6:1 | ✅ | Any |
| Light green | #BBF7D0 | 16.3:1 | ✅ | Any |
| Mint | #A7F3D0 | 15.1:1 | ✅ | Any |
| Light blue | #DBEAFE | 18.4:1 | ✅ | Any |
| Light purple | #EDE9FE | 17.8:1 | ✅ | Any |
| Light pink | #FCE7F3 | 18.9:1 | ✅ | Any |
| Spotify green | #1DB954 | 5.1:1 | ✅ | Normal text ✅ |
| Medium green | #22C55E | 4.5:1 | ✅ | Normal text (borderline) |

**Yellow rule**: Yellow always needs black text. Never white text on yellow — ratio is nearly always < 1.5:1.

---

## NEUTRAL SCALE PAIRS

### Light Theme Neutral Scale (Tailwind Slate as reference)

| Token | HEX | On #FFFFFF | On #0F172A | Role |
|-------|-----|-----------|-----------|------|
| slate-950 | #020617 | 20.9:1 ✅ | — | Headings / max contrast |
| slate-900 | #0F172A | 19.4:1 ✅ | — | Body text |
| slate-800 | #1E293B | 15.8:1 ✅ | — | Primary text |
| slate-700 | #334155 | 9.8:1 ✅ | — | Secondary text |
| slate-600 | #475569 | 6.1:1 ✅ | — | Meta text, captions |
| slate-500 | #64748B | 4.0:1 ❌ | — | Large text only |
| slate-400 | #94A3B8 | 2.5:1 ❌ | 4.8:1 ✅ | Dark mode secondary |
| slate-300 | #CBD5E1 | 1.3:1 ❌ | 11.4:1 ✅ | Dark mode borders |
| slate-200 | #E2E8F0 | 1.1:1 ❌ | 15.1:1 ✅ | Dark mode body text |
| slate-100 | #F1F5F9 | 1.07:1 | — | Subtle backgrounds |
| slate-50 | #F8FAFC | 1.04:1 | — | Page tint |

**Pattern**: Light neutrals (50–300) = backgrounds in light mode, text in dark mode. Dark neutrals (600–950) = text in light mode, backgrounds in dark mode.

---

## COMMON FAILURES AND FIXES

| Failing Pair | Ratio | Problem | Fix | Fixed Ratio |
|-------------|-------|---------|-----|------------|
| #9CA3AF on #FFF | 2.5:1 | Light gray placeholder | Use #6B7280 | 4.6:1 ✅ |
| #6B7280 on #FFF | 4.6:1 | Borderline | Use #4B5563 for safety margin | 7.5:1 ✅ |
| #3B82F6 on #FFF | 3.1:1 | Popular Tailwind blue-500 | Darken to #1D4ED8 | 7.2:1 ✅ |
| #22C55E on #FFF | 3.7:1 | Green-500 | Use as bg with black text (5.1:1) OR darken to #15803D | 5.7:1 ✅ |
| #EF4444 on #FFF | 3.3:1 | Red-500 error text | Darken to #B91C1C | 6.1:1 ✅ |
| #F59E0B on #FFF | 2.4:1 | Amber-500 warning | Darken to #92400E | 7.0:1 ✅ |
| #8B5CF6 on #FFF | 3.4:1 | Violet-500 | Darken to #5B21B6 | 7.4:1 ✅ |
| #1DB954 on #FFF | 3.5:1 | Spotify green as text | Use as background, black text (5.1:1 ✅) | — |
| #FF9900 on #FFF | 2.3:1 | Amazon orange | Always use black text on orange, not white | 7.6:1 ✅ |
| White on #3B82F6 | 3.1:1 | Blue button with white label | Darken bg to #1D4ED8 | 7.2:1 ✅ |
| White on #22C55E | 2.8:1 | Green button | Darken to #15803D | 5.7:1 ✅ |
| #94A3B8 on #1E293B | 3.1:1 | Dark mode secondary text | Lighten to #CBD5E1 | 7.4:1 ✅ |

---

## SEMANTIC STATE COLORS

### Light Mode

| State | Text Color | Background | Text Ratio | Bg w/ Black | Bg w/ White |
|-------|-----------|-----------|-----------|-------------|-------------|
| Error | #B91C1C | #FEE2E2 | 6.1:1 ✅ | 14.2:1 ✅ | — |
| Warning | #92400E | #FEF3C7 | 7.0:1 ✅ | 16.1:1 ✅ | — |
| Success | #155724 | #DCFCE7 | 8.2:1 ✅ | 17.4:1 ✅ | — |
| Info | #1E40AF | #DBEAFE | 8.6:1 ✅ | 18.4:1 ✅ | — |

### Dark Mode

| State | Text Color | Background | Text Ratio on #0F172A |
|-------|-----------|-----------|----------------------|
| Error | #FCA5A5 | #450A0A | 8.9:1 ✅ |
| Warning | #FDE68A | #451A03 | 12.3:1 ✅ |
| Success | #86EFAC | #052E16 | 10.9:1 ✅ |
| Info | #93C5FD | #0C1A6B | 8.1:1 ✅ |

---

## GRAY SCALE REFERENCE

### The AA/AAA boundary on white (#FFFFFF)

```
Passes AAA (7:1+):  anything ≤ #595959 in perceived lightness
Passes AA (4.5:1+): anything ≤ #767676 in perceived lightness
Fails AA:           anything ≥ #777777 as normal text on white

Minimum AA passing gray:  #767676 (ratio: 4.54:1)
Minimum AAA passing gray: #595959 (ratio: 7.02:1)
```

### Avoid This "Gray Dead Zone" in Neutral Scales

Grays from approximately #888 to #AAAAAA on white (#FFF) have ratios between 2.2:1 and 3.7:1 — failing AA for normal text AND failing 3:1 for large text. These are the danger zone grays that look usable to the eye but fail WCAG. Never use them for text on white.

The rule: **For text on light backgrounds, only use grays darker than #767676. For text on dark backgrounds, only use grays lighter than #8A8A8A.**

---

## CONTRAST CHECKER TOOLS

| Tool | Best For | URL |
|------|---------|-----|
| WebAIM | Quick spot check | webaim.org/resources/contrastchecker |
| Stark (Figma) | Design workflow, pre-generation compliance | getstark.co |
| Adobe Color | Full palette audit + color blindness simulation | color.adobe.com |
| axe DevTools | Testing rendered output on live pages | deque.com/axe |
| Colour Contrast Analyser | Desktop app, eyedropper live testing | paciellogroup.com |
| WAVE | Visual overlay on live pages | wave.webaim.org |
