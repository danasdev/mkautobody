---
name: MK Auto Body
description: Independent collision and paint shop in Nepean since 1997; the site is a car in the paint booth, masked, taped on the logo's 48° shear, and peeled back to the finish.
colors:
  basecoat-red: "#d40a0a"
  basecoat-red-deep: "#a90606"
  booth-black: "#0b0b0b"
  booth-black-lift: "#2a2a28"
  graphite: "#3b3b37"
  primer-grey: "#6b6b65"
  masking-paper: "#f6f5f1"
  paper-shade: "#ecebe5"
  tape-rule: "#d6d5cd"
  field-white: "#ffffff"
  smoke: "#cfcfca"
  ash: "#a9a9a3"
typography:
  display:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "clamp(2.85rem, 6.6vw, 6rem)"
    fontWeight: 900
    lineHeight: 0.92
    letterSpacing: "-0.035em"
    fontVariation: "'wdth' 125"
  numeral:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "clamp(6rem, 17vw, 15rem)"
    fontWeight: 900
    lineHeight: 0.8
    letterSpacing: "-0.04em"
    fontFeature: "'tnum'"
    fontVariation: "'wdth' 125"
  headline:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "clamp(2.25rem, 4.6vw, 4.25rem)"
    fontWeight: 900
    lineHeight: 0.92
    letterSpacing: "-0.035em"
    fontVariation: "'wdth' 125"
  title:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "clamp(1.5rem, 2.4vw, 2.125rem)"
    fontWeight: 800
    lineHeight: 1.1
    letterSpacing: "-0.01em"
    fontVariation: "'wdth' 112"
  lede:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "clamp(1.0625rem, 1.35vw, 1.25rem)"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.55
    fontVariation: "'wdth' 100"
  button:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "0.005em"
    fontVariation: "'wdth' 112"
  label:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 700
    letterSpacing: "0.01em"
  label-caps:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 800
    letterSpacing: "0.06em"
rounded:
  none: "0px"
spacing:
  gutter: "clamp(16px, 4vw, 56px)"
  section: "clamp(88px, 11vw, 168px)"
  wrap: "1280px"
  gap: "12px"
  control-x: "26px"
components:
  button-red:
    backgroundColor: "{colors.basecoat-red}"
    textColor: "{colors.field-white}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: "0 26px"
    height: "56px"
  button-red-hover:
    backgroundColor: "{colors.basecoat-red-deep}"
  button-ink:
    backgroundColor: "{colors.booth-black}"
    textColor: "{colors.field-white}"
    typography: "{typography.button}"
    rounded: "{rounded.none}"
    padding: "0 26px"
    height: "56px"
  button-ink-hover:
    backgroundColor: "{colors.booth-black-lift}"
  input-field:
    backgroundColor: "{colors.field-white}"
    textColor: "{colors.booth-black}"
    rounded: "{rounded.none}"
    padding: "0 16px"
    height: "54px"
  tape:
    backgroundColor: "{colors.booth-black}"
    height: "12px"
    width: "min(220px, 40%)"
  peel-tag-before:
    backgroundColor: "{colors.masking-paper}"
    textColor: "{colors.booth-black}"
    typography: "{typography.label-caps}"
    padding: "7px 12px"
  peel-tag-after:
    backgroundColor: "{colors.basecoat-red}"
    textColor: "{colors.field-white}"
    typography: "{typography.label-caps}"
    padding: "7px 12px"
  peel-grip:
    backgroundColor: "{colors.booth-black}"
    textColor: "{colors.field-white}"
    size: "56px"
  photo-caption-chip:
    backgroundColor: "{colors.masking-paper}"
    textColor: "{colors.booth-black}"
    typography: "{typography.label}"
    padding: "8px 12px"
---

# Design System: MK Auto Body

## Overview

**Creative North Star: "The Masked Booth"**

The site is a car inside MK's paint booth. The ground is masking paper, the structure is black tape, and the only colour is the basecoat red that ends up on the car. Every cut edge takes the 48° shear from the MK wordmark: tape ends, photo chamfers, and the diagonal you drag in the before/after viewer. Corners are square or chamfered at 48°, never rounded.

Density is editorial rather than dashboard. Sections sit on a wide vertical rhythm, content runs along hairline and 1.5px ink rules instead of in boxes, and the type does the heavy lifting: Archivo pushed to 125% width and weight 900 so headlines carry the wordmark's wide, heavy cut. Real shop photographs carry the proof. Decoration is limited to what a body shop actually uses: paper, tape, paint.

Motion follows the craft. On first view a tape strip lays down along its own axis and the hero photo is unmasked; after that nothing moves unless the visitor moves it.

**Key Characteristics:**
- Masking-paper ground, booth-black type and tape, basecoat red reserved for paint and the call.
- Archivo variable: 125% width / 900 for display, 112% / 800 for titles and buttons, 100% / 400 for text.
- One angle, 48°, for every cut edge; square corners everywhere else.
- Flat surfaces; depth comes from the ink/paper contrast and the dark visit band, not shadows.
- Hairline-ruled lists in place of cards.
- One authored motion moment: tape lays in, hero unmasks.

## Colors

A near-monochrome booth palette (warm paper, booth black, three greys) with a single saturated basecoat red.

### Primary
- **Basecoat Red**: The paint and the call. Used for the call-to-action buttons (header call strip, "Call now"), the red K of the logo, the red sliver under the hero chamfer, the "After" tag in the peel viewer, the 6px underline beneath the large phone number, text selection, the caret, and the error state on form fields.
- **Basecoat Red Deep**: Hover state of red buttons and the text colour of field error messages, where the brighter red would fall short on paper.

### Neutral
- **Booth Black**: All type, the tape strips, the secondary (submit) button, the 1.5px structural rules, focus outlines, the peel viewer's strip and grip, and the ground of the visit band and footer.
- **Booth Black Lift**: Hover state of the ink button and the footer's top hairline on the dark ground.
- **Graphite**: Secondary text on paper: ledes, section intros, row descriptions.
- **Primer Grey**: Tertiary text: captions, form notes, optional markers, fact-strip icons.
- **Masking Paper**: The page ground; also the chip behind photo captions and the "Before" tag.
- **Paper Shade**: Scrollbar track; the one tonal step below the ground.
- **Tape Rule**: 1px hairlines between list rows and the header's stuck-state border.
- **Field White**: Input backgrounds and text on booth black. Fields sit whiter than the paper so they read as places to write.
- **Smoke**: Lede and body text on the dark visit band.
- **Ash**: Column headings, closed hours and footer text on the dark band.

### Named Rules
**The Red Is Paint Rule.** Basecoat red only appears where paint or action would: the call to act, the logo's K, the finished "After" state, the red cut under a chamfer, and field errors. It never fills a section background, never colours a heading, and never decorates a neutral list.

**The Two-Weight Rule Line.** Structure uses exactly two rules: a 1.5px booth-black rule to open a block and a 1px tape-rule hairline between its rows.

## Typography

**Display Font:** Archivo, self-hosted variable (weight 100–900, width 62–125%), with system-ui, sans-serif fallback
**Body Font:** Archivo at normal width
**Label/Mono Font:** none distinct; labels are Archivo at heavier weights

**Character:** One family stretched across its width axis. Display type at 125% width and 900 weight echoes the MK wordmark; text at 100% width stays plain and readable. The width axis carries the hierarchy, the family stays the same.

### Hierarchy
- **Display** (900, 125% width, clamp(2.85rem, 6.6vw, 6rem), line-height 0.92, -0.035em, balanced): The hero headline only.
- **Numeral** (900, 125% width, clamp(6rem, 17vw, 15rem), line-height 0.8, -0.04em, tabular): A single monumental figure per page, such as "$500". A related phone-number size (clamp(2.4rem, 5.6vw, 4.75rem), line-height 1) sets the call in the dark band.
- **Headline** (900, 125% width, clamp(2.25rem, 4.6vw, 4.25rem), line-height 0.92): Section headings.
- **Title** (800, 112% width, clamp(1.5rem, 2.4vw, 2.125rem), line-height 1.1): Row headings in ruled lists.
- **Lede** (400, clamp(1.0625rem, 1.35vw, 1.25rem), line-height 1.5, max 34em): The opening paragraph of the hero and the visit band.
- **Body** (400, 1.0625rem, line-height 1.55, max 34–36em): Running text, usually in graphite.
- **Label** (700, 0.8125rem, 0.01em): Form labels, photo caption chips. Captions and notes use the same size at 400–500 in primer grey.
- **Label Caps** (800, 0.8125–0.875rem, 0.06em, uppercase): Short functional tags only: the "Before"/"After" tags and column heads in the dark band ("Shop", "Hours").

### Named Rules
**The Wordmark Width Rule.** Anything display-sized is set at 125% width and 900 weight. Never set a headline at normal width; that is how it stops sounding like MK.

**The Middle Width Rule.** Buttons, titles, the service run and finish names sit at 110–112% width, between display and text. Keep it there.

## Layout

A centred 1280px wrap with a fluid gutter (clamp(16px, 4vw, 56px)) and a fluid section rhythm (clamp(88px, 11vw, 168px)) of top padding per section. Section heads use a two-column grid: a short tape strip over the headline on the left, the intro paragraph aligned to the baseline on the right. Content grids are asymmetric (1.08fr / 1fr hero, 0.9fr / 1.1fr insurance, 1.15fr / 1fr paint, a 12-column photo mosaic spanning 7+5 then 4+4+4). Gaps between controls and tiles are 12px.

Responsive behaviour: at 900px and below, all two-column grids collapse to one, the hero photo moves above the headline and goes full-bleed, the nav links hide and the header keeps only the logo and the red call strip, and the peel viewer's picker becomes a three-across thumbnail grid. At 760px the mosaic goes single-column at 16:9. On short desktop viewports (901px+ wide, 960px or less tall) the hero tightens its type, margins and field heights so the form and facts strip land in the first viewport. The header is sticky at 76px with a paper-tinted backdrop blur.

## Elevation & Depth

The system is flat. No surface casts a shadow. Depth comes from contrast: booth-black tape and type on masking paper, field-white inputs one step above the paper, and the full-width booth-black visit band at the end of the page. The only blur is the sticky header's backdrop. Focus on inputs uses a soft 3px ink halo (18% booth black) plus an inset 1.5px ink stroke; that halo is a focus state, not elevation.

### Named Rules
**The Flat Booth Rule.** Surfaces never lift. Distinguish layers by ink against paper, never by shadow.

## Shapes

The form language is the logo's shear. All corners are square (0 radius). Where an edge is cut, it is cut at 48°:
- **Tape strips**: 12px tall booth-black bars whose right end is cut by a 10.8px horizontal offset (48°).
- **Chamfered photos**: the hero plate loses its lower-left corner to a 48° cut (30% × 33.3% on the square plate, 20% × 39.5% on the 16:9 mobile plate), with a basecoat-red sliver parallel to the cut beneath it. The paint photo loses its lower-right corner, and the visit-band photo loses its upper-left corner (180px × 200px).
- **Peel edge**: the before/after boundary is a diagonal tape strip, 16px wide, on the same shear.

Inline icons are stroked SVG (2.2 stroke, square caps, miter joins) so they share the cut, mechanical edge of the letterforms.

### Named Rules
**The 48° Rule.** There is one angle. If an edge is diagonal, it is 48° from horizontal; if it is not diagonal, it is square.

## Components

### Buttons
Heavy, flat, rectangular. They look like a strip of tape with a word on it.
- **Shape:** square corners (0), min-height 56px (48px in the header), 26px horizontal padding (20px in the header), icon gap 0.6em.
- **Red (call):** basecoat red with white 800-weight, 112%-width text. Used for every phone action.
- **Ink (submit):** booth black with white text. Used for the form submit, next to the red call.
- **Hover / Active / Focus:** red deepens to basecoat red deep; ink lifts to booth black lift (0.2s, expo-out ease). Active nudges down 1px. Focus is a 2.5px booth-black outline at 3px offset (white on dark grounds). Disabled drops to 55% opacity.

### Inputs / Fields
- **Style:** field-white background, 1.5px booth-black border, square corners, 54px tall (50px on short desktops), 16px horizontal padding, Archivo 500 at 1rem. Selects use a stroked square-cap chevron.
- **Label:** above the field in label style; optional markers in primer grey.
- **Focus:** inset 1.5px ink stroke plus a 3px 18% ink halo; no colour change.
- **Error:** border and inset stroke turn basecoat red; a 600-weight message in basecoat red deep sits under the field. Validation runs on blur and clears on input.

### Navigation
Header: logo symbol (30px) with "AUTO BODY" at 125% width / 800 on the left, text links (600, 0.95rem) pushed right, red call button last. Links have no underline at rest; on hover a 2px ink bar draws in from the left (0.35s). Once the page scrolls, a tape-rule hairline appears under the header. On mobile only the logo and call button remain.

### Ruled Lists
The system's alternative to cards. A list opens with a 1.5px ink rule and separates rows with 1px tape-rule hairlines. Rows carry a title-weight heading, a graphite description and, optionally, a bold arrow link; promise rows lead with a stroked check icon. The fact strip under the hero is the same idea run horizontally, and the finish names run inline separated by vertical hairlines.

### Photo Caption Chip
A masking-paper chip (8px 12px, label style) anchored flush to the lower-left of a photo, square corners. On hover the photo inside its frame scales to 1.03 over 0.9s.

### Peel Viewer (signature)
A before/after viewer where the boundary is a strip of tape. The after photo is clipped by a 48° diagonal; a 16px booth-black strip lies along that diagonal with a 56px square ink grip carrying a stroked double chevron at its centre. Dragging anywhere on the viewer (pointer capture, horizontal only, vertical scroll allowed) moves the diagonal; a full-size invisible range input provides keyboard and screen-reader control with spoken percentages, and focus outlines the whole viewer. A "Before" tag sits on paper top-left and an "After" tag sits on red top-right. A picker of 2:1 thumbnails sits beside it: greyscale at 70% opacity at rest, full colour on hover or when pressed, with the selected name underlined.

### Tape Strip
A 12px booth-black bar, min(220px, 40%) wide, with its right end cut at 48°. It sits above every section headline. With motion allowed it lays down along its own axis (scaleX from the left, 1s, expo-out) the first time it scrolls into view.

### Motion
One authored moment. Tape strips lay in once; on desktop the hero plate unmasks from left to right (1.1s) and its red sliver rises after it (0.8s, 0.65s delay). Everything uses one ease, cubic-bezier(.16, 1, .3, 1). With reduced motion nothing animates. Hover transitions are the only other movement, and they only run when the visitor triggers them.

## Do's and Don'ts

### Do:
- **Do** set every headline at Archivo 125% width, weight 900, line-height 0.92, tracking -0.035em.
- **Do** cut diagonal edges at 48° and keep every other corner square (0).
- **Do** reserve basecoat red (#d40a0a) for calls to act, the logo's K, the "After"/finished state, the sliver under a chamfer, and field errors.
- **Do** open blocks with a 1.5px booth-black rule and divide rows with 1px tape-rule hairlines.
- **Do** put a tape strip above a section headline, and let it lay in once along its axis.
- **Do** keep every section one tap from calling: a red call button or the large phone number.
- **Do** use real shop photographs; caption them with a masking-paper chip.

### Don't:
- **Don't** round corners or use pill shapes on any surface, control or photo; the only curves are inside the stroked icons.
- **Don't** use diagonals at any angle other than 48°.
- **Don't** add shadows to lift surfaces; the system is flat.
- **Don't** put content in bordered or shadowed cards; use ruled lists.
- **Don't** use red for headings, section grounds, or decoration with no paint or action meaning.
- **Don't** animate anything on its own beyond the tape lay-in and hero unmask.
- **Don't** set display type at normal width or below weight 900.
