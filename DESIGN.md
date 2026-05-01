<!-- SEED — built fresh for Minter agency. Run /impeccable document in scan mode once there's live code. -->
---
name: Minter Agency Website
description: High-converting done-for-you web agency landing page for US local businesses.
colors:
  green: "#06BB60"
  green-light: "#d4fae8"
  green-deep: "#0fa76e"
  gold: "#D4A853"
  gold-light: "#fef3d4"
  dark: "#0d0d0d"
  dark-soft: "#1a1a1a"
  gray-700: "#333333"
  gray-500: "#666666"
  gray-400: "#888888"
  gray-200: "#e5e5e5"
  gray-100: "#f5f5f5"
  gray-50: "#fafafa"
  white: "#ffffff"
typography:
  display:
    fontFamily: "'Sora', system-ui, sans-serif"
    fontSize: "clamp(3rem, 7vw, 5.5rem)"
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "'Sora', system-ui, sans-serif"
    fontSize: "clamp(2rem, 4vw, 3rem)"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.02em"
  title:
    fontFamily: "'Sora', system-ui, sans-serif"
    fontSize: "clamp(1.25rem, 2.5vw, 1.75rem)"
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: "-0.01em"
  body:
    fontFamily: "'Manrope', system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: "0"
  label:
    fontFamily: "'Manrope', system-ui, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 600
    letterSpacing: "0.08em"
    textTransform: "uppercase"
rounded:
  sm: "6px"
  md: "12px"
  lg: "20px"
  full: "9999px"
spacing:
  xs: "8px"
  sm: "16px"
  md: "24px"
  lg: "40px"
  xl: "64px"
  2xl: "96px"
components:
  btn-primary:
    backgroundColor: "{colors.green}"
    textColor: "{colors.white}"
    rounded: "{rounded.full}"
    padding: "14px 32px"
  btn-primary-hover:
    backgroundColor: "{colors.green-deep}"
  btn-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.dark}"
    border: "1.5px solid {colors.gray-200}"
    rounded: "{rounded.full}"
    padding: "13px 32px"
  btn-ghost-white:
    backgroundColor: "transparent"
    textColor: "{colors.white}"
    border: "1.5px solid rgba(255,255,255,0.3)"
    rounded: "{rounded.full}"
    padding: "13px 32px"
  card:
    backgroundColor: "{colors.white}"
    borderRadius: "{rounded.lg}"
    border: "1px solid {colors.gray-200}"
    padding: "32px"
  nav:
    backgroundColor: "rgba(255,255,255,0.92)"
    backdropFilter: "blur(16px)"
    borderBottom: "1px solid {colors.gray-200}"
    height: "68px"
---

# Design System: Minter Agency Website

## 1. Overview

**Creative North Star: "The Quiet Confidence of a Expert Who Shows Up"**

Minter is the agency that busy business owners actually want to talk to — not the flashy tech-bro agency, not the slow-moving enterprise shop. The design should feel like a well-tailored shirt: present, composed, confident, and quietly impressive. No gimmicks. No noise. Just a clear signal that someone competent is in charge.

The personality is **warm authority**: the kind of confidence that doesn't need to shout. It speaks to owners of home services, salons, and restaurants — people who are good at what they do and suspicious of anyone who isn't. The design earns trust through restraint, not through excitement.

**Key Characteristics:**
- Typography-forward: large, punchy headlines anchored by a geometric sans (Sora) with Manrope body text for warmth and readability
- Color strategy: **Committed** — the brand green is the dominant voice, not a shy accent. Gold is the accent that signals premium, not the brand color
- Layout: asymmetric compositions break the centered-stack template habit. Hero pulls left. Sections breathe with intentional variation in density
- Motion: entrance stagger on scroll reveals; micro-interactions on buttons; ambient gradient pulse on hero. Nothing bounces or elastic
- Dark hero section anchors the page; white sections create rhythm and breathing room between denser content areas

---

## 2. Colors

The palette is built on two voices: a confident green that owns the page, and a restrained warm-gold that marks the important things.

### Primary
- **Minter Green** (`#06BB60`): The dominant brand voice. Used on hero backgrounds, primary CTAs, active nav states, feature icons, and section accents. Deep variant `#0fa76e` used for hover states. Light tint `#d4fae8` used for subtle backgrounds and badges.
- **The Committed Rule.** Green must own at least 40% of any marketing surface. Its presence is the brand's presence. Shrinking it to a 10% accent would un-brand the page.

### Secondary
- **Warm Gold** (`#D4A853`): The accent that marks importance. Used on the logo's `E`, badge callouts ("MOST POPULAR"), the audit CTA card background, the gold accent bar in the footer, and hover states on gold-themed CTAs. Tints to `#fef3d4` for subtle warm accents.
- **The Gold Signal Rule.** Gold appears where we want the eye to stop: the most important price, the premium tier, the footer border. Never decorative.

### Neutral
- **Near Black** (`#0d0d0d`): Primary dark backgrounds — hero and audit CTA card. Softer variant `#1a1a1a` for layered dark surfaces.
- **Charcoal** (`#333333`): Body text on light backgrounds.
- **Mid Gray** (`#666666`): Secondary text, captions, meta information.
- **Light Gray** (`#e5e5e5`): Borders and dividers on light surfaces.
- **Off White** (`#fafafa`): Section backgrounds for contrast areas.
- **Pure White** (`#ffffff`): Primary background, cards.

---

## 3. Typography

**Display Font:** Sora (Google Fonts) — geometric, engineered, confident. Pairs technical precision with enough personality to feel designed, not generic.

**Body Font:** Manrope (Google Fonts) — humanist geometric sans with slightly warmer curves than pure geometric faces. Excellent readability at body sizes; adds warmth Inter lacks.

**Character:** The pairing is "engineer + strategist." Sora brings the confident, structured headline energy. Manrope brings the readable, approachable body copy. Together they feel like a competent person wrote the headline and a thoughtful person wrote the details.

### Hierarchy
- **Display** (Sora, 700, `clamp(3rem, 7vw, 5.5rem)`, line-height 1.0, tracking -0.03em): Hero headline only. Commands attention.
- **Headline** (Sora, 700, `clamp(2rem, 4vw, 3rem)`, line-height 1.1, tracking -0.02em): Section headings, card titles. Asserts structure.
- **Title** (Sora, 600, `clamp(1.25rem, 2.5vw, 1.75rem)`, line-height 1.25): Sub-headings, nav logo, form labels.
- **Body** (Manrope, 400, 1rem, line-height 1.65): All body copy. Max 65ch line length.
- **Label** (Manrope, 600, 0.8125rem, tracking 0.08em, uppercase): Section labels, badge text, button labels.

**The Weight Contrast Rule.** Headlines are always 700. Body is always 400. Never a 500-weight headline next to a 400-weight body — the hierarchy collapses.

---

## 4. Elevation

The system uses **layered tonal elevation**: surfaces are primarily distinguished by background color, not by shadows. Shadows are reserved for interactive feedback (hover lift on cards) and the chat widget's floating state.

### Shadow Vocabulary
- **Card Hover** (`0 8px 32px rgba(6,187,96,0.12)`): Subtle green-tinted lift on card hover. Appears only on interactive cards.
- **Chat Widget** (`0 8px 40px rgba(0,0,0,0.15)`): The chat widget floats above content with a clean, neutral shadow.
- **Nav Blur** (`backdrop-filter: blur(16px)`): Sticky nav uses blur over content scrolling beneath, not shadow.

**The Flat-By-Default Rule.** Cards sit flat at rest. Buttons are flat. Shadows appear only as a response to interaction or to indicate a floating element. The restraint makes the hover shadows meaningful.

---

## 5. Components

### Buttons
- **Shape:** Full-round (9999px radius) — pill shape. Signaled by `border-radius: 9999px`.
- **Primary (Green):** Green background, white text, 14px/32px padding. Hover: deep green (`#0fa76e`) + subtle `translateY(-1px)`. Active: slight scale-down.
- **Secondary (Ghost):** Transparent background, dark text, 1.5px light border. Hover: border darkens to charcoal, slight lift.
- **Ghost White:** For CTAs on dark backgrounds. White text, transparent background, 1.5px white-30% border. Hover: border becomes white-60%.
- **Gold CTA:** Gold background, dark text. Used only on the audit form submit button.

### Navigation
- **Style:** Sticky, blurred glass (backdrop-filter). Floats above content. White/92% opacity background.
- **Logo:** "MINTER" wordmark in Sora Bold, dark text. The `I` is the letter `I` in the sequence, not a stand-in. Gold accent on the `E` only — a typographic signature.
- **Links:** Manrope 500, dark gray, no underline. Hover: transitions to green.
- **CTA Button:** Dark pill button, always visible. "Free Audit" in nav triggers scroll to audit section.

### Cards
- **Corner Style:** Large radius (20px) — approachable, modern, not sharp.
- **Background:** White with light border (`#e5e5e5`). Featured card (Full Retainer) has green border and a subtle green-tinted gradient background.
- **Badge:** "MOST POPULAR" — green background, white text, full-pill, centered above the card.
- **Icon:** 48px square, 12px radius, green-light background, emoji or SVG icon centered.
- **Price:** 36px Sora Bold in green (featured) or dark (others). `/mo` in 20px.
- **Hover:** Border shifts to green, subtle green-tinted shadow lifts the card.

### Service Pills
- **Style:** Horizontal scrollable strip of pills. Each pill: light gray background, rounded (12px), 14px Manrope 500, green icon on left.
- **Hover:** Border turns green, background shifts to green-light.
- **Purpose:** Quick visual scan of capabilities — website setup, hosting, AI chat, SEO, edits.

### Hero
- **Background:** Dark (`#0d0d0d`) with an ambient radial gradient in green (subtle, 8% opacity at center). Full viewport-width.
- **Headline:** Display size, white text, "MINTER" in the logo has the gold `E` as signature. In hero headline, the gold letter signals premium without explaining it.
- **Sub-headline:** Manrope 400, gray-400 (`#888888`). Not white — softer to not compete with headline.
- **CTA Pair:** Primary green pill + Ghost white pill. Stacked or side-by-side depending on space.
- **Layout:** Text left-aligned on desktop, centered on mobile. Not a centered column stack — asymmetric and confident.

### Audit CTA
- **Background:** Dark card (`#0d0d0d`) centered on a page with warm radial gradient in gold.
- **Large Gold E:** 56px Sora Bold in gold. The typographic signature, large and confident.
- **Headline:** 32px white, with "money" in gold to signal the value hook.
- **Form:** Dark glass inputs (white 8% background, white 15% border). Gold submit button.
- **Note:** "No sales pitch" in small muted text beneath the form — trust signal.

### Footer
- **Background:** Dark (`#0d0d0d`) with a 3px gold top border. This is the only gold border on the site — deliberate.
- **Logo:** White wordmark, gold `E`.
- **Links:** White-70% text, transitions to green on hover.
- **Bottom:** Divider with white-8% opacity, copyright left, socials right.

### Chat Widget
- **Toggle:** 60px green circle, white chat icon. Fixed bottom-right. Gold notification badge (18px circle, gold background, dark "1").
- **Box:** White card, rounded-lg (20px), chat-header in green with white text.
- **Messages:** Bot messages: gray-100 bubble, dark text. User messages: green bubble, white text.
- **Quick Replies:** Green-light background, green-deep text, full-pill. Hover: green fill, white text.
- **Typing Indicator:** Three gray dots animating in sequence.

---

## 6. Do's and Don'ts

### Do:
- **Do** use the full-width dark hero — it anchors the page and signals confidence
- **Do** left-align the hero text — asymmetric layouts read as designed, centered stacks read as template
- **Do** keep the green dominant — it is the brand voice, not a shy accent
- **Do** use gold only where we want the eye to stop — the `E` in MINTER, the featured card badge, the audit CTA headline word "money"
- **Do** stagger button hover with `translateY(-1px)` — micro-lift signals interactivity without drama
- **Do** use the ambient radial gradient in the hero — it adds depth without being garish
- **Do** keep body copy at max 65ch — readability over density
- **Do** use scroll-triggered entrance animations — staggered fade-up on sections as they enter viewport

### Don't:
- **Don't** center-align everything — the centered-stack hero is the most recognizable AI-slop template
- **Don't** use green as a 10% accent — that shrinks the brand into invisibility
- **Don't** use gold decoratively — it must always signal a specific important element
- **Don't** use bounce or elastic easing — `ease-out` or `cubic-bezier(0.4, 0, 0.2, 1)` only
- **Don't** animate layout properties (width, height, padding) — only opacity and transform
- **Don't** use Inter, DM Sans, Plus Jakarta Sans, or Outfit — they're in the reflex-reject list for looking generic
- **Don't** add large rounded-corner icons above headings — they read as template
- **Don't** use gradient text for emphasis — solid color only
- **Don't** use side-stripe borders (border-left > 1px as a colored accent) — full borders or background tints only
- **Don't** animate the background gradient in the hero — static radial gradient only, no continuous animation
