# Avail Earn — Brand Identity & Usage Guide

> Internal reference for design, marketing, and development teams.
> Source: [Figma — Branding Concepts](https://www.figma.com/design/hhotG5KLlXdu2tJBPTTxtE/Branding-Concepts?node-id=124-129&m=dev)

---

## 1. Brand Overview

**Avail Earn** is a product under the Avail parent brand. It serves as the unified earning layer for cross-chain DeFi, integrating other Avail products (Nexus Opportunities, FastBridge) to let users deploy capital across chains in a single step.

### Logo

- **Composition:** Avail icon (circular mark) + **"earn"** wordmark
- **Typeface:** Delight Semi Bold
- **Primary color:** Science Blue `#0B4FD4` on green backgrounds; Praxeti White `#F6F7ED` on blue backgrounds
- **Wordmark tracking:** 0.75px letter-spacing

### Logo Usage Rules

| Rule | Guideline |
|------|-----------|
| Clear space | Minimum 1x icon height on all sides |
| Minimum size | 24px icon height for digital; 10mm for print |
| Placement | Top-left corner of compositions, 42px inset from edges |
| On green backgrounds | Blue logo `#0B4FD4` |
| On blue backgrounds | Light logo `#F7FDE3` / `#F6F7ED` |
| Don'ts | No rotating, no stretching, no drop shadows, no placing on busy photography without a solid color block behind it |

---

## 2. Color System

### Primary Palette

| Name | Hex | Role |
|------|-----|------|
| **Spring Green** | `#C5FF59` | Primary accent. Energy, growth, action. Use for backgrounds, CTAs, highlights |
| **Matte Blue** | `#005AAE` | Primary trust color. Depth, stability. Use for backgrounds, headers, anchoring elements |

### Secondary Palette

| Name | Hex | Role |
|------|-----|------|
| Inch Worm | `#A1E220` / `#A3E221` | Saturated green variant. Card backgrounds, hero sections |
| Science Blue | `#0A50D3` / `#0B4FD4` | Deep action blue. Text on green, buttons, interactive elements |
| Light Blue | `#C7D7F6` | Soft blue. Background panels, light-mode surfaces |
| Medium Blue | `#6D96E6` | Mid-range blue. Secondary panels, transitions between light and deep blue |
| Soft Green | `#D2F291` | Muted green. Alternate card backgrounds, softer compositions |

### Extended Palette

| Name | Hex | Contrast Ratio | Use |
|------|-----|----------------|-----|
| Praxeti White | `#F6F7ED` | 19.45:1 | Light backgrounds, text on dark |
| First Colors of Spring | `#DBE64C` | 15.44:1 | Accent highlights, badges |
| Midnight Mirage | `#001F3F` | 16.56:1 | Deep dark backgrounds |
| Mantis | `#74C365` | 9.74:1 | Supporting green, illustrations |
| Picture Book Green | `#00804C` | 5.01:1 | Supporting green, secondary icons |
| Nuit Blanche | `#1E488F` | 8.83:1 | Deep blue variant, dark UI elements |
| Spring Sun | `#F6FFE4` | — | Ultra-light green tint, backgrounds at 80% opacity |
| Manz | `#DBEE7E` | — | Warm yellow-green, highlights at 90% opacity |

### Neutrals

| Name | Hex | Use |
|------|-----|-----|
| Dark Steel | `#0B0B0B` | Body text on light, dark mode base |
| White | `#F0F0F0` | Backgrounds, cards, UI surfaces |
| Grey | `#5D5D5D` | Secondary text, captions, borders |

### Color Pairing Rules

**Do:**
- Spring Green background + Science Blue text (primary brand combination)
- Matte Blue background + Praxeti White text (trust-forward compositions)
- Three-column split: Inch Worm | Light Blue | Science Blue
- Gradient transitions within the same color family (light → dark green or light → dark blue)

**Don't:**
- Green text on blue background (low readability)
- Manz on Praxeti White (insufficient contrast)
- More than one extended palette color per composition
- Full black `#000000` as a background (use Dark Steel `#0B0B0B` or Midnight Mirage `#001F3F`)

---

## 3. Typography

### Display / Headings

- **Typeface:** Delight Semi Bold
- **Usage:** Product name, hero text, section headers, marketing headlines
- **Display size:** 120px (large hero), letter-spacing 2.4px
- **Wordmark size:** 37.5px, letter-spacing 0.75px
- **Line height:** 1.1x font size (133px at 120px)

### Body / UI

- **Typeface:** System sans-serif stack (Inter, SF Pro, or equivalent)
- **Usage:** Paragraphs, UI labels, descriptions, captions
- **Recommended scale:**
  - H1: 48px
  - H2: 36px
  - H3: 24px
  - Body: 16px
  - Caption: 14px
  - Small: 12px

### Type Rules

- Headings always in Delight Semi Bold — never in regular weight
- Body text in Dark Steel `#0B0B0B` on light backgrounds; Praxeti White `#F6F7ED` on dark
- No all-caps except for very short labels (max 2 words)
- Minimum body text size: 14px digital, 9pt print

---

## 4. Visual Motif: Pixel Dispersion

The signature visual treatment for Avail Earn. Real-world objects dissolve into scattered pixel blocks at their edges — representing the transformation of physical value into digital infrastructure.

### What It Communicates

- Physical value (cash, coins, organic growth) being transformed through technology
- The bridging of real-world assets into cross-chain DeFi
- Growth and movement — value doesn't disappear, it disperses and reassembles

### How to Apply

| Parameter | Guideline |
|-----------|-----------|
| **Subject matter** | Financial objects (cash, coins, currency) or organic growth (flowers, plants) |
| **Pixel block size** | Vary from large (near the object) to small (at the dispersion edge) |
| **Dispersion direction** | Outward from the object, typically upper-right or trailing edge |
| **Color extraction** | Pixel blocks sample colors from the source object — pinks from flowers, greens from leaves, golds from coins |
| **Background** | Clean white or solid brand color blocks — never busy |
| **Blending** | Object transitions smoothly from photorealistic → grid-aligned pixels → scattered single pixels |
| **Coverage** | Dispersion should affect 20–40% of the object. The object must remain recognizable |

### Subject Categories

1. **Organic growth** — Flowers, plants, leaves. Use when communicating yield, growth, earning potential
2. **Currency / Cash** — Dollar bills, hands holding money. Use when communicating deposits, capital deployment, financial action
3. **Crypto assets** — Bitcoin coins, tokens. Use when communicating cross-chain, crypto-native context

### Don'ts

- No pixel dispersion on the logo itself
- No dispersion on UI screenshots or product interfaces
- No dispersion without a clear real-world source object
- No random pixel scatter without the gradient from solid → dispersed

---

## 5. Layout System

### Three-Column Color Block

The foundational layout for Avail Earn compositions. Derived from the card designs in Figma.

```
┌──────────────┬──────────────┬──────────────┐
│              │              │              │
│   Column 1   │   Column 2   │   Column 3   │
│   (Primary)  │  (Transition) │   (Anchor)   │
│              │              │              │
│   ~42%       │   ~29%       │   ~29%       │
│              │              │              │
└──────────────┴──────────────┴──────────────┘
```

Column 2 is split vertically into two blocks (upper lighter, lower darker) to create a four-panel effect.

### Light Mode (Green-Dominant)

| Column | Color |
|--------|-------|
| 1 (Primary) | Inch Worm `#A3E221` or Spring Green `#C5FF59` |
| 2 Upper | Light Blue `#C7D7F6` |
| 2 Lower | Medium Blue `#6D96E6` |
| 3 (Anchor) | Science Blue `#0B4FD4` |
| Text | Science Blue `#0B4FD4` |

### Dark Mode (Blue-Dominant)

| Column | Color |
|--------|-------|
| 1 (Primary) | Science Blue `#0B4FD4` |
| 2 Upper | Spring Sun `#F7FDE3` |
| 2 Lower | Soft Green `#D2F291` |
| 3 (Anchor) | Inch Worm `#A3E221` |
| Text | Praxeti White `#F7FDE3` |

### Softer Green Variant

| Column | Color |
|--------|-------|
| 1 (Primary) | Soft Green `#D2F291` |
| 2 Upper | Medium Blue `#6D96E6` |
| 2 Lower | Science Blue `#3574EF` |
| 3 (Anchor) | Science Blue `#0B4FD4` |
| Text | Science Blue `#0B4FD4` |

### Composition Rules

- Logo and product name always in Column 1 (the primary panel)
- Pixel-dispersion imagery spans Columns 2–3, overlapping the color boundaries
- Product UI screenshots sit within a white card container, placed in Columns 2–3
- Minimum padding: 42px from edges for text content

---

## 6. Application Guidelines

### Marketing Collaterals

#### Social Media Cards & Banners

- Use the three-column layout as the base
- Product name ("Avail Earn") in Column 1 with logo above
- Pixel-dispersion imagery in Columns 2–3
- Aspect ratios:
  - Twitter/X banner: 1500x500 — use horizontal three-column
  - Instagram post: 1080x1080 — stack Column 1 on top, Columns 2–3 below
  - LinkedIn: 1200x627 — horizontal three-column
  - Story/Reel: 1080x1920 — vertical stack with color blocks

#### Presentation Slides

- **Title slides:** Three-column layout with product name
- **Content slides:** White or Praxeti White `#F6F7ED` background, Dark Steel text
- **Section dividers:** Full-bleed single color (Spring Green or Matte Blue) with white text
- **Data slides:** White background, use Spring Green and Matte Blue for chart colors
- **Accent bar:** 4px Spring Green line at top or left edge of content slides

#### Print Materials

- Business cards: Blue front (logo in white), Spring Green back (contact in blue)
- Letterhead: White with Spring Green accent bar, logo top-left
- Brochures: Three-column layout maps directly to tri-fold
- Merchandise: Spring Green + Blue two-tone; pixel-dispersion artwork for hero surfaces

### Website

#### Color Mapping

| Element | Light Theme | Dark Theme |
|---------|-------------|------------|
| Page background | `#F6F7ED` (Praxeti White) | `#001F3F` (Midnight Mirage) |
| Card surfaces | `#F0F0F0` (White) | `#0B0B0B` (Dark Steel) |
| Primary CTA | `#C5FF59` (Spring Green) bg + `#0B4FD4` text | `#C5FF59` bg + `#0B0B0B` text |
| Secondary CTA | `#0B4FD4` (Science Blue) bg + `#F6F7ED` text | `#0A50D3` bg + `#F6F7ED` text |
| Body text | `#0B0B0B` | `#F6F7ED` |
| Secondary text | `#5D5D5D` | `#6D96E6` |
| Links | `#0B4FD4` | `#C5FF59` |
| Borders | `#DBEE7E` at 30% opacity | `#1E488F` at 50% opacity |

#### Hero Section

- Three-column color block background at full viewport width
- "Avail Earn" in Delight Semi Bold, 72–120px
- Pixel-dispersion key visual anchored right
- CTA button: Spring Green with blue text, rounded corners

#### Component Styling

- **Buttons:** 12px border-radius, Delight Semi Bold for labels, 48px min height
- **Cards:** 16px border-radius, subtle shadow (`0 2px 8px rgba(0,0,0,0.08)`), white background
- **Inputs:** 8px border-radius, 1px border in Grey `#5D5D5D`, 48px height
- **Tags/Badges:** Spring Green bg + Science Blue text, pill shape, 6px vertical padding

### Animations & Motion Graphics

#### Pixel Dispersion Animation

The core animation principle — objects assemble from scattered pixels or disassemble into them.

| Type | Behavior | Duration | Easing |
|------|----------|----------|--------|
| **Assembly** (page load, reveal) | Pixels converge from scattered positions into the source object | 800–1200ms | `cubic-bezier(0.16, 1, 0.3, 1)` (ease-out expo) |
| **Disassembly** (exit, transition) | Object breaks apart into pixels that scatter outward | 600–900ms | `cubic-bezier(0.7, 0, 0.84, 0)` (ease-in expo) |
| **Hover/Idle** | Subtle pixel drift at object edges, 2–4px movement | Continuous, 3–5s loop | `ease-in-out` |

#### Color Transitions

- Transition between green ↔ blue palette on scroll or state changes
- Duration: 400–600ms
- Use opacity crossfade, not hue interpolation (avoids muddy mid-tones)

#### Logo Animation

- Icon appears first (scale up from 0 with slight bounce)
- "earn" wordmark slides in from left, 200ms delay after icon
- Total duration: 800ms
- Use on splash screens, video intros, loading states

#### Micro-Interactions

- **Button hover:** Background shifts from Spring Green to Inch Worm (subtle darken), 150ms
- **Card hover:** Lift 4px with shadow deepening, 200ms
- **Loading spinner:** Pixel blocks rotating in a circular pattern, using primary palette colors
- **Success state:** Green pulse outward from center, 400ms
- **Number counters:** Count-up animation for yield/APY values, 1200ms with easing

#### Motion Principles

- **Speed:** Fast and responsive. Nothing over 1200ms except continuous loops
- **Easing:** Always ease-out for entrances, ease-in for exits. Never linear
- **Direction:** Left-to-right for progress. Upward for positive values/growth
- **Pixel motif:** Reserve pixel assembly/disassembly for key moments (page load, major transitions). Don't overuse

### Photography & Imagery

#### Style Guide

- Real-world objects shot on clean, neutral backgrounds (white or very light grey)
- High-key lighting, minimal shadows
- Objects should be isolated — no environmental context or lifestyle settings
- Pixel-dispersion overlay applied in post-production

#### Subject Matter

| Category | Examples | When to Use |
|----------|----------|-------------|
| Organic growth | Flowers, single stems with leaves, botanical elements | Yield narratives, growth stories, long-term earning |
| Currency | Dollar bills (fanned), hands holding cash | Capital deployment, deposits, financial action |
| Crypto assets | Gold bitcoin coins, ethereum tokens | Cross-chain context, crypto-native audiences |

#### Color Grading

- Saturation should complement the brand palette — greens lean toward Spring Green, blues lean toward Matte Blue
- Avoid warm tones (oranges, reds) in photography unless the subject inherently has them (like gold coins)
- Pink/magenta in flowers is acceptable and creates strong contrast with the green palette

#### Do's and Don'ts

**Do:**
- Use single objects on clean backgrounds
- Apply pixel dispersion consistently (20–40% coverage)
- Let dispersion pixels extend beyond the composition boundaries for dynamism
- Match pixel block colors to the source object

**Don't:**
- Use lifestyle/people photography
- Apply brand color overlays or duotones to photographs
- Use stock photography without pixel dispersion treatment
- Mix multiple pixel-dispersion objects in one composition

---

## 7. Brand Modes

Four established card variants, each suited to a different communication context.

### Variant 1: Organic Growth

- **Background:** Inch Worm `#A3E221` + blue panels
- **Imagery:** Flower with pixel dispersion
- **Text:** Science Blue `#0B4FD4`
- **Use when:** Communicating yield, returns, earning potential, growth narratives
- **Best for:** Social media, blog headers, educational content

### Variant 2: Crypto Value

- **Background:** Soft Green `#D2F291` + blue panels
- **Imagery:** Bitcoin coin with pixel dispersion
- **Text:** Science Blue `#0B4FD4`
- **Use when:** Talking about crypto assets, cross-chain functionality, token support
- **Best for:** Product announcements, chain integration reveals, Twitter threads

### Variant 3: Financial Action

- **Background:** Science Blue `#0B4FD4` + green panels
- **Imagery:** Cash/currency with pixel dispersion
- **Text:** Praxeti White `#F7FDE3`
- **Use when:** Emphasizing capital movement, deposits, financial trust, security
- **Best for:** Institutional-facing materials, partnership announcements, trust-building content

### Variant 4: Product Showcase

- **Background:** Inch Worm `#A3E221` + blue panels
- **Imagery:** White card with product UI screenshot (MegaETH bridge, deposit flow)
- **Text:** Science Blue `#0B4FD4`
- **Use when:** Demonstrating the actual product, showing UI, launch announcements
- **Best for:** Product launches, feature demos, app store listings, landing page hero

### Choosing the Right Variant

| Context | Recommended Variant |
|---------|-------------------|
| "We launched on a new chain" | Variant 2 (Crypto Value) |
| "Earn 6% APY on your USDC" | Variant 1 (Organic Growth) |
| "Your capital, secured by five audits" | Variant 3 (Financial Action) |
| "See how one-click deposit works" | Variant 4 (Product Showcase) |
| General brand awareness | Variant 1 (Organic Growth) — default |

---

*Last updated: April 2026*
*Figma source: Branding Concepts / Section 1 (node 124:129)*
