# Nody Lab. — Brand Guidelines v1
**Issued:** April 2026 · **Status:** Draft — Pending Founder Approval

---

## 1. BRAND IDENTITY

### Name
**Nody Lab.**
Always written as shown — title case, with the lime period. The period is not punctuation. It is the mark. Never write "NodyLab", "nodylab", or "Nody Lab" without the period.

### Tagline
**"Your team. Always on."**
Communicates 24/7 autonomous execution — an AI team that never sleeps, never context-switches, never drops the ball.

### Mission
To make elite-calibre business operations accessible to any founder — by deploying AI agents that think, coordinate, and execute like a world-class team.

### Brand Personality
| Trait | What it means |
|-------|--------------|
| Friendly | The smiling face in the logo. We're not cold, robotic, or intimidating. |
| Precise | Everything is tight, intentional. No noise. No filler. |
| Fast | Like F1 energy — kinetic, urgent, always moving forward. |
| Confident | We don't hedge. We build, ship, and deliver. |
| Human | AI that feels like a great colleague, not a tool. |

---

## 2. COLOR SYSTEM

### Primary Palette
| Name | Hex | RGB | Usage |
|------|-----|-----|-------|
| **Void Black** | `#0A0A0A` | 10, 10, 10 | Primary background — all screens |
| **Electric Lime** | `#C5F000` | 197, 240, 0 | Primary accent — CTAs, highlights, the period, active states |
| **Pure White** | `#FFFFFF` | 255, 255, 255 | Primary text, logo outline, icon strokes |

### Secondary Palette
| Name | Hex | Usage |
|------|-----|-------|
| **Obsidian** | `#111111` | Card backgrounds, secondary surfaces |
| **Surface** | `#1A1A1A` | Input backgrounds, subtle containers |
| **Border** | `#2A2A2A` | Dividers, card borders |
| **Muted** | `#888888` | Secondary text, meta labels |
| **Dim** | `#555555` | Placeholder text, disabled states |

### Semantic Colors (UI only)
| Name | Hex | Usage |
|------|-----|-------|
| **Success** | `#22C97A` | Completed states, confirmations |
| **Warning** | `#F5A623` | Alerts, pending states |
| **Error** | `#F05C5C` | Errors, destructive actions |
| **Info** | `#4F8EF7` | Informational, links |

### Color Rules
- **Background is always Void Black.** Never white, never grey.
- **Lime is used sparingly.** One key element per composition. It should feel like a headlight in the dark, not a highlighter.
- **High contrast is non-negotiable.** White on Black = 21:1. Lime on Black = 14:1. Both pass WCAG AAA.
- **Never put lime on white.** Never put lime on lime.
- **The lime period** appears on any dark background. On white backgrounds (print only), the period is black.

---

## 3. TYPOGRAPHY

### Font Stack

#### Display — Outfit
Used for: headlines, hero text, wordmark, section titles
- **Weight:** SemiBold (600) for wordmark, Bold (700) for display headlines
- **Tracking:** -0.02em to -0.04em for large sizes
- **Case:** Title case preferred. Uppercase only for UI labels and badges.
- **Source:** Google Fonts (`Outfit`)

#### Body — Inter
Used for: paragraphs, descriptions, UI body copy
- **Weight:** Regular (400) for body, Medium (500) for emphasis
- **Tracking:** 0 (default)
- **Line height:** 1.6 for body, 1.4 for UI
- **Source:** Google Fonts (`Inter`)

#### Mono — JetBrains Mono
Used for: code, data, technical labels, the agent command center UI
- **Weight:** Regular (400), Medium (500)
- **Source:** Google Fonts (`JetBrains Mono`)

### Type Scale
| Name | Size | Weight | Font | Usage |
|------|------|--------|------|-------|
| Display XL | 64–96px | 700 | Outfit | Hero headlines |
| Display L | 48–64px | 700 | Outfit | Section heroes |
| Headline | 32–40px | 600 | Outfit | Section titles |
| Subhead | 20–24px | 600 | Outfit | Card titles, modal heads |
| Body L | 16–18px | 400 | Inter | Long-form body |
| Body | 14–15px | 400 | Inter | Standard body |
| Label | 12–13px | 500 | Inter | UI labels, uppercase, 0.06em tracking |
| Micro | 10–11px | 500 | Inter | Badges, timestamps, meta |
| Code | 12–13px | 400 | JetBrains Mono | All code/technical content |

---

## 4. LOGO SYSTEM

### Variants
| Variant | Usage |
|---------|-------|
| **Icon Mark** | App icons, favicons, avatars, social profile images (1:1 square) |
| **Horizontal Lockup** | Navigation bars, headers, email signatures, presentations |
| **Stacked Lockup** | Square formats, posters, splash screens |
| **Wordmark** | Minimal contexts — footnotes, co-branding, watermarks |

### Logo Construction — Icon Mark
The icon is a TV/monitor with a smiling face:
- **Monitor:** Rounded rectangle, white 5px stroke, 16px corner radius
- **Stand:** Centered horizontal line, white, thin (2-3px), 40% width of monitor
- **Eyes:** Two lime oval dots, vertically elongated (~16×24px at standard size)
- **Smile:** Lime curved arc, ~5px stroke, centered, open upward

### Clear Space
Minimum clear space = width of the capital "N" in the wordmark at the current logo size. Nothing enters this zone.

### Minimum Sizes
- Icon mark: 32×32px
- Horizontal lockup: 120px wide
- Stacked lockup: 100px wide
- Wordmark: 80px wide

### Background Rules
| Background | Correct version |
|------------|----------------|
| Void Black `#0A0A0A` | Full color (white outline + lime accents) |
| Dark surfaces `#111–#222` | Full color |
| White / light | Inverse: black monitor + black wordmark + lime period |
| Lime `#C5F000` | Black monitor + black wordmark + black period |
| Photography | Full color, ensure contrast — use black overlay if needed |

### What Never to Do
- ❌ Stretch or distort the logo
- ❌ Remove the lime period from the wordmark
- ❌ Recolor the lime elements to any other color
- ❌ Place on a busy background without overlay
- ❌ Use outline-only version (the lime fill is essential)
- ❌ Separate the icon from the wordmark in horizontal lockup

---

## 5. ICON LANGUAGE

### Style
All UI icons follow the same design language as the logo icon:
- **Stroke-first:** 2px stroke, rounded caps and joins
- **Corner radius:** 3–4px on geometric shapes
- **Grid:** 24×24px base, 2px padding (20px live area)
- **Weight:** Consistent 2px — never thicker, never thinner
- **Lime accent use:** 1 element per icon can use lime for semantic meaning (active state, notification dot, etc.)

### Core UI Icon Set (Phase 1)
```
Navigation:     menu (burger), close (×), arrow-left, arrow-right, chevron-down
Actions:        search, filter, settings, edit, trash, copy, share, download
Status:         check, check-circle, warning, info, error, loading (spinner)
Content:        document, image, link, code, calendar, clock
Communication:  message, inbox, bell, send
Brand:          logo-icon, agent-dot (animated)
```

### Burger Menu Icon — Nody Lab Style
3 horizontal lines with a twist:
- Lines 1 & 3: full width
- Line 2: 60% width, lime colored
- Gap: equal to line height
- Hover: line 2 extends to full width, lime
- Open state: morphs to × with lime center dot

---

## 6. UI COMPONENT LANGUAGE

### Buttons
```
PRIMARY (lime)
  Background: #C5F000
  Text: #0A0A0A (black)
  Border: none
  Radius: 8px
  Padding: 12px 24px
  Font: Inter Medium 14px
  Hover: #D4FF00 (brighter) + scale(1.02)
  Active: #AACF00 (darker)

SECONDARY (outline)
  Background: transparent
  Text: #FFFFFF
  Border: 1.5px solid #FFFFFF
  Radius: 8px
  Hover: background rgba(255,255,255,0.06)

GHOST
  Background: transparent
  Text: #888888
  Border: none
  Hover: text #FFFFFF

DANGER
  Background: rgba(240,92,92,0.12)
  Text: #F05C5C
  Border: 1px solid rgba(240,92,92,0.3)
  Radius: 8px
```

### Cards
```
Background: #111111
Border: 1px solid #2A2A2A
Radius: 14px
Padding: 20px
Hover: border-color #3A3A3A, subtle shadow
Active/Selected: border-color #C5F000 (lime), shadow: 0 0 0 1px #C5F000
```

### Inputs
```
Background: #1A1A1A
Border: 1px solid #2A2A2A
Radius: 8px
Padding: 10px 14px
Text: #FFFFFF
Placeholder: #555555
Focus: border-color #C5F000, outline: none
Font: Inter 14px / JetBrains Mono 13px (for code fields)
```

### Navigation
```
Background: #0A0A0A
Border-right: 1px solid #1A1A1A
Active item: left border 2px #C5F000, text #FFFFFF
Inactive item: text #888888
Icon color: matches text
```

---

## 7. MOTION & ANIMATION

### Philosophy
Motion communicates speed, precision, and intelligence. Inspired by F1 kinetic energy — sharp entry, smooth exit, nothing lazy.

### Easing
```
Primary:   cubic-bezier(0.65, 0.05, 0, 1)  — sharp in, smooth out (F1 acceleration)
Smooth:    cubic-bezier(0.4, 0, 0.2, 1)    — material standard
Bounce:    cubic-bezier(0.34, 1.56, 0.64, 1) — for confirmations only
```

### Duration Scale
| Name | Duration | Usage |
|------|----------|-------|
| Instant | 100ms | Hover states, color changes |
| Micro | 150ms | Button interactions |
| Standard | 250ms | Panel opens, card reveals |
| Modal | 350ms | Overlays, drawers |
| Hero | 600ms | Page transitions, splash |

### Signature Animations
- **Agent thinking:** 3-dot pulse — staggered 200ms, lime color, scale 0.6→1
- **Lime accent reveal:** clip-path horizontal wipe, 350ms
- **Task card enter:** translateY(8px)→0 + opacity 0→1, 250ms staggered
- **Burger → close:** rotate 45°/−45°, center dot scales up lime, 200ms

---

## 8. PHOTOGRAPHY & IMAGERY

### Style
- **Dark, high-contrast photography** — nighttime cityscapes, dark studio, close-up tech
- **Lime accent treatment:** selective color overlay, lime light leak on edges
- **People:** Confident, forward-looking — not smiling at screens, but commanding them
- **No stock photography clichés:** No handshakes, no lightbulb moments, no whiteboard sessions

### AI Visualization
- Abstract node networks, glowing lime connection lines
- Dark background with electric lime data streams
- Geometric, precise — NOT the purple cloud aesthetic

---

## 9. VOICE & TONE

### In One Line
**Sharp. Human. Confident.**

### Voice Traits
| Trait | We say | We don't say |
|-------|--------|--------------|
| Direct | "Your agents are running." | "Our system is currently processing your request." |
| Human | "The CEO drafted that. Check your inbox." | "An automated process has generated output." |
| Confident | "We ship. You grow." | "We hope to help you potentially improve..." |
| Precise | "3 tasks created. 1 decision pending." | "Several things were done, some decisions may be needed." |

### Copy Patterns
- **Short sentences.** Maximum 12 words for key messages.
- **Active voice always.** "Agents built this" not "This was built by agents."
- **Numbers over words.** "17 agents" not "many agents."
- **The period is a power move.** Use it deliberately in headlines.

---

## 10. BRAND SPRINT DELIVERABLES — PHASE 1

| # | Deliverable | Owner | Status |
|---|------------|-------|--------|
| 1 | Brand Guidelines v1 (this document) | CMO | ✅ Delivered |
| 2 | Color system — usage rules + dark/light variants | CMO + Art | 🔄 In Progress |
| 3 | Typography specimen — all weights + sizes | UX/UI | 🔄 In Progress |
| 4 | Logo usage guide — all variants + rules | Art | 📋 Backlog |
| 5 | Icon set Phase 1 — 30 core UI icons | Art | 📋 Backlog |
| 6 | Button + component spec (Figma-ready) | UX/UI | 📋 Backlog |
| 7 | LinkedIn brand templates (3 formats) | Art + Social | 📋 Backlog |
| 8 | Pitch deck template (12 slides) | Art + CMO | 📋 Backlog |
| 9 | Website hero section design concept | UX/UI | 📋 Backlog |
| 10 | Brand voice guide — examples + anti-patterns | Content | 📋 Backlog |

---

*Nody Lab. Brand Guidelines v1 — Confidential*
*Produced by NodyLab Agent Team · April 2026*
