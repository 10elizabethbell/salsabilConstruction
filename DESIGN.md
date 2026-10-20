---
name: Salsabil Construction
description: Calm paper and steel-navy bands carrying the logo's safety orange as the one accent fill.
colors:
  safety-orange: "#f8580a"
  safety-orange-bright: "#ff7a33"
  safety-orange-ink: "#a83c08"
  steel-navy: "#1b3358"
  deep-navy: "#10213b"
  paper: "#f4f6fb"
  card-white: "#ffffff"
  field-mist: "#e6ecf5"
  ink: "#10213b"
  body-slate: "#26344b"
  soft-slate: "#4b5870"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c8d4e8"
  hairline: "rgba(16,33,59,.12)"
  focus-blue: "#1f5fbf"
  error-red: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(42px, 12vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  title:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(22px, 6vw, 28px)"
    fontWeight: 400
    lineHeight: 1.15
  label-display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.2
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(16px, 4.4vw, 18px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.02em"
rounded:
  field: "10px"
  card: "24px"
  pill: "999px"
spacing:
  gutter-mobile: "20px"
  gutter-desktop: "40px"
  section-mobile: "64px"
  section-desktop: "96px"
  container: "1160px"
components:
  button-primary:
    backgroundColor: "{colors.safety-orange}"
    textColor: "{colors.ink}"
    typography: "{typography.label-display}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.safety-orange-bright}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.label-display}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-soft:
    backgroundColor: "{colors.field-mist}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 14px"
    height: "56px"
  eyebrow:
    backgroundColor: "rgba(16,33,59,.06)"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "9px 14px"
  eyebrow-on-dark:
    backgroundColor: "rgba(255,255,255,.12)"
    textColor: "{colors.on-dark}"
  chip:
    backgroundColor: "{colors.field-mist}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card-white}"
  input:
    backgroundColor: "{colors.field-mist}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  form-card:
    backgroundColor: "{colors.card-white}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  link-card:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.card}"
    padding: "16px 16px 16px 22px"
    height: "80px"
  service-row:
    textColor: "{colors.on-dark}"
    typography: "{typography.title}"
    padding: "12px 0"
    height: "76px"
  step-disc:
    backgroundColor: "{colors.safety-orange}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "48px"
  float-circle:
    backgroundColor: "{colors.safety-orange}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "60px"
---

# Design System: Salsabil Construction

## Overview

**Creative North Star: "The Job-Site Flyer, Calmed Down"**

The system is the contractor's own flyer translated into a quiet, phone-first page. The flyer's logo (black hammer and saw over an orange-roofed house) supplies everything: its orange becomes the single accent fill, and its black becomes two steel navies laid against an off-white paper ground. The page is a stack of full-bleed horizontal bands (paper, steel navy, deep navy) that alternate light and dark so each section reads as one plain statement, with no photography and no ornament beyond a faint diagonal line texture on the darkest bands.

Density is low and deliberate. Every band holds one heading, at most one supporting line, and one kind of action. Type does the heavy lifting: Cal Sans headings at a confident size, with the last word or phrase often picked out in orange, over a plain system body face. Motion is limited to three owner-chosen moves: the hero heading's letters bounce in once, content below the first screen fades up 12px as it arrives, and a single orange text circle slides up once the hero has scrolled away.

All three moves, the eyebrow pills and the band palette were chosen by the owner and are part of the system on purpose. They are not leftovers to clean up.

**Key Characteristics:**
- Full-bleed bands alternating paper, steel navy and deep navy; the ground is never black.
- One accent: the logo's safety orange, used as a fill, with ink-navy text on it.
- Cal Sans (weight 400) for every heading, button, label and number; system sans for running text.
- Pills and circles for anything you touch; 24px cards for containers; no hard corners on interactive elements.
- Flat surfaces; the only shadow belongs to the floating text circle.
- Every action ends in a call or text to one phone number.

## Colors

A cool, low-saturation navy-and-paper field with a single hot orange from the logo.

### Primary
- **Safety Orange** (safety-orange): The logo's orange. Used only as a fill: primary buttons, the How-it-works number discs, the floating text circle, the dot inside each eyebrow pill, text selection, and the arrow disc when a row or link card is hovered or focused. Text placed on it is always Ink.
- **Bright Orange** (safety-orange-bright): The hover state of orange fills, and orange as *text* on navy or deep navy (accent words in headings, the close-band phone icon, the Instagram icon, footer link hover). Also the focus-ring color on dark bands.
- **Orange Ink** (safety-orange-ink): Orange as *text* on light grounds (accent words on paper, the header phone icon and its hover), darkened to hold 5.9:1 on paper.

### Neutral
- **Steel Navy** (steel-navy): The hero, Services and closing bands. The main dark surface.
- **Deep Navy** (deep-navy): The How-it-works band and the footer, always paired with the line texture.
- **Paper** (paper): The page ground, header and light bands; also the browser theme color.
- **Card White** (card-white): The quote form card only, lifting it off paper without a shadow.
- **Field Mist** (field-mist): Text inputs, chips and soft buttons inside the white form card.
- **Ink** (ink): Headings on light grounds, text on orange, the selected chip fill and the Instagram link card. Same value as Deep Navy, different role.
- **Body Slate** (body-slate): Running text on light grounds.
- **Soft Slate** (soft-slate): Ledes, helper text, placeholders and "optional" hints on light grounds.
- **On Dark** (on-dark) and **On Dark Soft** (on-dark-soft): Headings and running text on navy bands respectively.
- **Hairline** (hairline): The faint navy rule on light grounds. On navy, service rows use a white rule at 14% instead.
- **Focus Blue** (focus-blue): Focus rings on light grounds and hover outlines on form controls. Deliberately not orange, so focus never reads as a fill.
- **Error Red** (error-red): Field error text and the invalid field border.

### Named Rules
**The One Orange Rule.** Safety Orange appears as a fill and nowhere else. When orange must be text, use Orange Ink on light grounds and Bright Orange on navy. Text on an orange fill is always Ink, never white.

**The Never-Black Rule.** No surface or text is pure black. The logo's black is translated into Steel Navy and Deep Navy; the logo artwork itself is used as supplied (full-color on paper, the white version on navy).

**The Separate Focus Rule.** Focus is blue (Focus Blue) on light grounds and Bright Orange on dark ones, always a 3px outline offset 3px, so keyboard focus is never mistaken for the accent fill.

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** the system sans stack (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** A round, geometric display face at a single regular weight, set tight and large, over the reader's own system font so body text loads instantly and reads like a text message.

### Hierarchy
- **Display** (400, clamp 42px to 80px, line-height 1.02): The hero heading only, in white, max 11ch on phones and 14ch on desktop.
- **Headline** (400, clamp 30px to 48px, line-height 1.08): One per band, balanced wrapping.
- **Title** (400, clamp 22px to 28px, line-height 1.15): Service rows and the Instagram link card; How-it-works step titles sit at 21px.
- **Label Display** (400, 18px): Buttons, form labels and legends, the header phone number (20px on desktop). Cal Sans is the voice of anything you act on.
- **Lede** (400, clamp 16px to 18px, line-height 1.7): One supporting sentence under a headline, max 40ch, Soft Slate on light.
- **Body** (400, 16px, line-height 1.7): Running text, inputs and chips.
- **Label** (500, 14px, letter-spacing 0.02em, sentence case): Eyebrow pills only. Helper text, errors and the "Opens your messages" note also sit at 14px, in regular weight.

### Named Rules
**The Single Weight Rule.** Cal Sans is only ever set at 400. Hierarchy comes from size, never from bolding the display face.

**The Accent Word Rule.** A headline may end on one orange word or short phrase ("NY & NJ.", "build.", "works."), kept on one line. One accent per headline, and not every headline gets one.

## Layout

A single centered column, 1160px max, with a 20px gutter on phones and 40px from 760px. Bands are full-bleed with 64px vertical padding on phones and 96px from 760px; the hero uses its own 56/68px (phone) and 104/120px (desktop) to sit taller than the others. Section headers stack eyebrow, headline and lede with a 16px gap, max 640px wide.

The layout is designed for phones first and stays single-column until 760px, where service rows split into two columns (48px column gap) and the hero buttons sit side by side at a 240px minimum width. At 1024px the trust band, quote band and closing band become two-column splits with a 64px gap: the quote band's header goes sticky beside the form, and the How-it-works steps go three across. Hover styles are applied only under `(hover: hover)`, so taps never leave a hover state stuck on.

Tap targets are at least 44px everywhere (56px for buttons, 48px for chips, 76px for service rows). The header and the floating circle respect the safe-area insets.

## Elevation & Depth

The system is flat. Depth comes from tone, not shadow: dark bands against paper, the white form card against paper, Field Mist controls inside the white card, and translucent white (10 to 12%) discs and pills on navy. The deep bands add the faint 135-degree line texture (a 1px white line at 3.5% every 23px) as their only surface material.

### Shadow Vocabulary
- **Float lift** (`box-shadow: 0 10px 28px rgba(8,20,40,.3)`): The floating text circle only, because it is the one element that sits above the page.

### Named Rules
**The One Lift Rule.** Nothing in the page flow casts a shadow. A shadow means "this floats over the content", and only the text circle does that.

## Shapes

Everything you touch is round: buttons, chips, eyebrows and the floating circle use a full pill radius, and arrow discs and step numbers are circles. Containers (the form card and the Instagram link card) use a generous 24px radius, and text fields a softer 10px. Borders are 2px and usually transparent, so they only appear for state (hover, focus, error). Service rows are separated by thin horizontal rules, not boxes. The only angular form is the line texture.

## Components

### Buttons
Confident pills set in Cal Sans.
- **Shape:** Full pill, 56px tall, 26px horizontal padding, 20px icon with a 10px gap.
- **Primary:** Safety Orange fill, Ink text. Used for "Get a quote" and the form submit button (full width inside the form).
- **Hover / Focus:** Primary brightens to Bright Orange over 0.2s. Inside the form, hover and focus add a 3px Focus Blue outline instead. Every button scales to 0.98 when pressed.
- **Ghost:** For navy grounds only: transparent with a 2px On Dark border at 70%, going to a solid white border over a 10% white wash on hover. Used for "Text Sam" beside the primary.
- **Soft:** Field Mist fill, Ink text, 16px, tighter padding. Used for the secondary actions after sending ("Open in Messages", "Copy message").

### Eyebrow pills (owner-chosen)
A small label above a key section heading.
- **Style:** Pill, 14px label weight 500, Ink at 6% navy wash on light, On Dark at 12% white wash on navy, with a 7px Safety Orange dot leading.
- **Use:** Owner-chosen and recorded as intentional. Used on a few key headings only (the hero, Services and the quote form), never on every band, never clickable, and never styled like a button.

### Chips
- **Style:** Field Mist pill, 48px tall, Ink body text, 2px transparent border. These are multi-select checkboxes for the type of job.
- **State:** Hover shows a Focus Blue border; selected fills Ink with white text; keyboard focus shows a 3px Focus Blue outline.

### Cards / Containers
- **Form card:** Card White, 24px radius, padding from 20 to 32px, 20px gap between fields, max 600px wide. No border, no shadow.
- **Instagram link card:** An Ink-filled 24px card, at least 80px tall, with an orange-bright icon, a Cal Sans title, a small On Dark Soft subline, and an arrow disc at the right end. Max 520px wide on desktop.

### Inputs / Fields
- **Style:** Field Mist fill, 10px radius, 2px transparent border, 52px minimum height (120px for the text area), 16px body text in Ink, Soft Slate placeholder, Steel Navy caret. Labels sit above in 18px Cal Sans, with an "(optional)" hint in 14px Soft Slate.
- **Focus:** Border turns Focus Blue; hover does the same where there is a pointer.
- **Error:** Border and 14px message in Error Red, cleared as soon as the person types.

### Navigation
There is no menu. The header is a paper strip with the logo on the left (58px tall, 68px on desktop) and a tap-to-call number on the right in Cal Sans with an Orange Ink phone icon. The footer is a deep-navy textured strip with the business line and a single Instagram link (44px tap height, Bright Orange on hover).

### Service rows (signature)
Each trade is one full-width link, 76px tall, in title-size Cal Sans on navy, separated by 14% white hairlines and ending in a 44px arrow disc. The whole row is the link; on hover or focus only the arrow disc changes (to a Safety Orange fill with Ink arrow, plus a Bright Orange focus ring). Tapping a row jumps to the quote form and ticks the matching chip.

**The Arrow-Only Rule.** Rows and the link card never change background on hover; the arrow disc carries all of the state.

### Step discs
How-it-works numbers are 48px Safety Orange circles with the counter in 20px Cal Sans Ink, set in a 48px column beside a 21px Cal Sans step title and a body line.

### Floating text circle (signature, owner-chosen)
One 60px Safety Orange circle with a chat icon, fixed bottom-right with a 16px inset (plus safe area). It opens a text to the phone number with a greeting already written. It slides up from 120px below over 0.35s (cubic-bezier(.2,.8,.2,1)) once the hero has scrolled away, and hides while the quote form is on screen or while a row or card arrow is in the bottom strip where the circle sits. It can be switched off with `CONFIG.FLOAT`.

**The One Circle Rule.** Mobile contact is one floating circle, never a sticky bottom bar and never a second floating button.

### Hero heading bounce-in (owner-chosen motion)
On load, each letter of the hero heading slides in from 50px to the right with a slight overshoot (1s, cubic-bezier(.34,1.56,.64,1)), 20ms apart. The split is done in JavaScript and the plain heading is restored when the last letter lands, so kerning, selection and the accessible name all come back. Without JavaScript, or with reduced motion, the heading is simply static.

### Fade-up (rise)
Content that starts below the first screen fades in and rises 12px over 0.4s (ease-out) as it enters. Everything above the fold is visible immediately, and nothing is hidden without JavaScript.

**The Visible-at-Rest Rule.** Motion only adds to content that is already there. Reduced motion turns off the letter bounce, the fade-up, smooth scrolling and all button and circle transitions.

### Contact wiring
Every action resolves to a single phone number held in `CONFIG.PHONE`: `tel:` links for calls, and `sms:` links with a greeting already written for texts. The quote form builds a sentence from the selected chips, name, town and job notes, opens Messages, and immediately shows the fallbacks (Open in Messages, Copy message, the number) because in-app browsers can block an `sms:` redirect.

## Do's and Don'ts

### Do:
- **Do** build new sections as full-bleed bands drawn from paper, steel navy and deep navy, with the line texture only on the hero and deep-navy surfaces.
- **Do** keep Safety Orange as a fill with Ink text on it; use Orange Ink or Bright Orange when orange has to be text.
- **Do** set every heading, button, label and number in Cal Sans at weight 400, and running text in the system stack at 16/1.7.
- **Do** make interactive elements pills or circles at least 44px (56px for buttons), with state shown by a 2px border, a 3px focus outline, or the arrow disc.
- **Do** route every new action to the phone number in `CONFIG.PHONE`, by call or by text.
- **Do** give any new motion a reduced-motion fallback and keep content visible at rest.

### Don't:
- **Don't** put white text on Safety Orange, or use Safety Orange itself as text on paper (it fails contrast; that is what Orange Ink is for).
- **Don't** use pure black for surfaces or text.
- **Don't** add shadows to cards, buttons or bands; the floating circle is the only lifted element.
- **Don't** add a sticky bottom contact bar or a second floating button.
- **Don't** put an eyebrow pill on every heading or make one look clickable.
- **Don't** bold Cal Sans or add a second display face.
- **Don't** use orange for focus rings on light grounds; use Focus Blue.
