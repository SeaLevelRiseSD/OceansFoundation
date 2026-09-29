---
name: Sea Level Rise San Diego
description: A clear, coastal editorial system for understanding and acting on local sea level rise.
colors:
  ink: "hsl(0 0% 4%)"
  ink-soft: "hsl(0 0% 34%)"
  coastal-teal: "hsl(186 83% 26%)"
  deep-harbor: "hsl(186 82% 15%)"
  sea-mist: "hsl(185 40% 94%)"
  civic-coral: "hsl(15 87% 66%)"
  coral-on-light: "hsl(15 72% 42%)"
  coral-on-dark: "hsl(15 90% 82%)"
  tide-line: "hsl(185 43% 85%)"
  white: "hsl(0 0% 100%)"
typography:
  display:
    fontFamily: '"DM Serif Display", Georgia, serif'
    fontSize: "clamp(3.1rem, 5vw, 4.5rem)"
    fontWeight: 400
    lineHeight: 1.08
  headline:
    fontFamily: '"DM Serif Display", Georgia, serif'
    fontSize: "clamp(2rem, 3.4vw, 2.65rem)"
    fontWeight: 400
    lineHeight: 1.08
  title:
    fontFamily: '"DM Serif Display", Georgia, serif'
    fontSize: "clamp(1.8rem, 3vw, 2.25rem)"
    fontWeight: 400
    lineHeight: 1.08
  body:
    fontFamily: '"Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif'
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: '"Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif'
    fontSize: "0.75rem"
    fontWeight: 700
    lineHeight: 1.35
    letterSpacing: "0.14em"
rounded:
  tag: "5px"
  control: "6px"
  field: "7px"
  link: "8px"
  surface: "12px"
  pill: "99px"
spacing:
  xs: "0.5rem"
  sm: "0.75rem"
  md: "1rem"
  lg: "1.5rem"
  xl: "2rem"
  section-sm: "4.5rem"
  section-lg: "7rem"
components:
  button-primary:
    backgroundColor: "{colors.coastal-teal}"
    textColor: "{colors.white}"
    typography: "{typography.body}"
    rounded: "{rounded.control}"
    padding: "0.72rem 1.45rem"
    height: "44px"
  button-light:
    backgroundColor: "{colors.white}"
    textColor: "{colors.deep-harbor}"
    typography: "{typography.body}"
    rounded: "{rounded.control}"
    padding: "0.72rem 1.45rem"
    height: "54px"
  button-coral:
    backgroundColor: "{colors.civic-coral}"
    textColor: "{colors.deep-harbor}"
    typography: "{typography.body}"
    rounded: "{rounded.control}"
    padding: "0.72rem 1.45rem"
    height: "44px"
  card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.surface}"
    padding: "2rem"
  field:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "0.8rem 0.9rem"
---

# Design System: Sea Level Rise San Diego

## Overview

**Creative North Star: "The Civic Coastline"**

This system brings the authority of a public-interest editorial publication to the warmth and immediacy of San Diego's coast. Expansive documentary imagery and confident serif headlines establish place and consequence; restrained interface typography, clean data treatments, and generous white space make the science approachable rather than institutional.

The visual hierarchy is urgent without becoming alarmist. Deep coastal teal provides trust and continuity, while coral appears selectively around statistics, steps, and action moments. The result should feel locally grounded, scientifically credible, and ready for civic participation across all five core routes.

**Key Characteristics:**

- Documentary coastal photography with legible teal overlays
- Editorial serif headlines paired with highly readable sans-serif copy
- Deep teal civic surfaces and sparing coral emphasis
- Generous white space, thin borders, and calm content density
- Responsive, accessible interactions with clear focus states

## Colors

The palette translates San Diego's water, sun, and sand into high-contrast editorial roles rather than decorative coastal pastels.

### Primary

- **Coastal Teal:** The system's anchor for primary actions, navigation emphasis, data bands, page heroes, and footer surfaces.
- **Deep Harbor:** The dark support tone used for focus rings, high-contrast text on coral, and visual depth within teal moments.

### Secondary

- **Civic Coral:** A deliberately limited action and emphasis color for newsletter actions, small signature marks, selections, and important numeric cues.
- **Coral on Light:** The contrast-safe coral role for labels, links, data values, and numbered steps on white or pale surfaces.
- **Coral on Dark:** The softened coral role for large statistics and data callouts on teal surfaces.

### Neutral

- **Ink:** Near-black primary text for maximum clarity on white.
- **Soft Ink:** Secondary copy and supporting explanations, never primary headlines.
- **Sea Mist:** A pale teal section surface, mobile control background, tag fill, and quiet status layer.
- **Tide Line:** The cool border used to structure cards, fields, timelines, and dividers.
- **White:** The page canvas, card surface, and primary text on dark fields.

### Named Rules

**The Coral Is a Signal Rule.** Coral marks action, data, or a small editorial accent; it does not become a full-page background or compete with teal for structural dominance.

**The Contrast Has a Role Rule.** Use Coral on Light for small coral text on pale surfaces and Coral on Dark for coral text on teal; do not interchange the decorative base coral with these accessible text roles.

## Typography

**Display Font:** DM Serif Display (with Georgia fallback)  
**Body Font:** Inter (with system sans-serif fallbacks)

**Character:** DM Serif Display gives the project a humane, editorial voice that can carry scientific consequence without sounding bureaucratic. Inter keeps navigation, explanatory copy, labels, forms, and quantitative context direct and highly legible.

### Hierarchy

- **Display** (400, fluid 3.1rem–4.5rem, 1.08): Hero and page-defining statements; on small screens the home hero resolves to 2.65rem.
- **Headline** (400, fluid 2rem–2.65rem, 1.08): Major section introductions and long-form content headings.
- **Title** (400, fluid 1.8rem–2.25rem, 1.08): Impact stories, neighborhoods, and prominent card groups.
- **Body** (400, 1rem, 1.6): General copy; explanatory articles relax to 1.75 line-height and stay inside narrow reading columns.
- **Label** (700, 0.75rem, 0.14em, uppercase): Eyebrows and compact section signals; smaller card labels use the same uppercase logic at 0.7rem.

### Named Rules

**The Serif Carries Meaning Rule.** Reserve DM Serif Display for headings, statistics, step numbers, and initials; controls and paragraph copy remain Inter.

**The Editorial Measure Rule.** Long explanations live in the narrow 848px reading container or a narrower text column; never stretch prose across the full 1216px grid.

## Layout

The primary container is centered at a maximum width of 1216px with a 1rem gutter on each side. A secondary 848px container supports reading, newsletters, and internal hero copy. Sections use a generous fluid vertical rhythm, ranging from 5rem to 7rem on wide screens and resolving to 4.5rem on compact screens.

Desktop compositions alternate between balanced two-column editorial stories, three- or four-column data/card grids, and full-width teal bands. At 900px, global navigation becomes a menu and complex split layouts collapse; at 680px, story, card, form, and organization grids become single-column, while compact statistics may remain in two columns. Image-first stories preserve their intended reading order when stacked.

Hero imagery covers the full viewport region beneath a 160-degree teal-to-black overlay. The home hero is centered and nearly viewport-height; internal page heroes are more compact and left-aligned within the reading measure. Photography uses 4:3 editorial crops where possible and must retain an informative alt description.

**The One Clear Measure Rule.** Every surface chooses either the broad 1216px editorial grid or the 848px reading measure; avoid arbitrary intermediate widths.

**The Collapse with Intent Rule.** Responsive layouts reorder images only when required to restore image-then-copy reading flow; DOM meaning and focus order remain stable.

## Elevation & Depth

The system is flat by default. White cards are defined primarily by cool 1px borders against pale or white fields. Shadows are reserved for interactive lift, the open mobile navigation, and the centered confirmation card; photographic depth comes from crops and overlays rather than stacked decoration.

### Shadow Vocabulary

- **Ambient Lift** (`0 6px 18px hsl(186 60% 12% / 0.09)`): Button hover and the open mobile navigation.
- **Confirmation Lift** (`0 18px 45px hsl(186 60% 12% / 0.16)`): Singular floating confirmation or completion surfaces.

### Named Rules

**The Flat by Default Rule.** Borders establish resting structure; shadows communicate active lift or a genuinely floating layer.

## Shapes

The form language is gently softened rather than playful. Editorial cards, media frames, facts panels, and neighborhood features use the 12px surface radius. Buttons use a tighter 6px radius; inputs use 7px; compact links use 8px; tags sit between 5px and 6px. Fully round geometry is reserved for avatars, scrollbars, and short accent strokes.

Borders are consistently cool, thin, and structural. Media is clipped cleanly at the surface radius, and the system avoids decorative blobs, exaggerated pills, or nested rounded panels.

**The Radius Has Scale Rule.** Larger content surfaces use 12px, controls use 6–8px, and pills appear only when the content or silhouette is inherently compact and rounded.

## Components

### Buttons

Buttons are compact, confident, and clearly actionable.

- **Shape:** Gently squared controls (6px radius) with a 44px minimum touch target; large hero buttons rise to 54px.
- **Primary:** Coastal Teal with white text, bold Inter, and 0.72rem × 1.45rem padding.
- **Hover / Focus:** Hover darkens the teal, moves up 1px, and gains Ambient Lift. Focus uses a 3px white outline plus a 6px Deep Harbor outer ring so it remains visible on light, image, and teal backgrounds.
- **Light / Outline:** Hero actions may use solid white with Deep Harbor text or a transparent surface with a 2px white border.
- **Coral:** Coral buttons belong on teal action bands and use Deep Harbor text for contrast.

### Chips

- **Style:** Compact 5–6px-radius tags use Sea Mist with Coastal Teal or Soft Ink text.
- **State:** High-risk tags switch to a translucent coral fill and Coral on Light text; chips label risk and content, not general navigation.

### Cards / Containers

- **Corner Style:** Gently curved editorial surfaces (12px radius).
- **Background:** White by default, with teal reserved for facts and structural bands.
- **Shadow Strategy:** No resting shadow; use the Elevation rules for interaction or singular floating states.
- **Border:** One-pixel Tide Line.
- **Internal Padding:** 1.5rem for compact cards, 2rem for feature and action cards, and up to 3rem for large split-feature bodies.

### Inputs / Fields

- **Style:** White fields with a one-pixel Tide Line border, a 7px radius, and 0.8rem × 0.9rem internal padding.
- **Focus:** The global white-and-Deep-Harbor focus ring is mandatory and must not be removed.
- **Error / Disabled:** Preserve the same labeled form structure and introduce state messaging adjacent to the field; do not rely on color alone.

### Navigation

The 80px desktop header uses a white surface, a restrained 0.875rem medium-weight link row, and a teal Take Action button. Active and hovered text links turn Coastal Teal. Below 900px, navigation becomes an accessible menu; below 680px, the header compacts to 64px. The open menu remains white with a Tide Line divider and Ambient Lift.

### Editorial Impact Story

The signature story pattern pairs a clipped 4:3 documentary image with a serif title, concise explanatory copy, and a directional text link. Rows alternate image position on desktop, then return to image-first order on mobile. Image zoom is subtle and slow, while the arrow moves only 4px to reinforce direction without turning the story into a novelty interaction.

### Netlify Forms

Newsletter and contact forms use visible or screen-reader labels, native input semantics, and clear required states. The newsletter becomes stacked on compact screens; the contact form moves from two columns to one. Submit actions retain the shared button language and route to the dedicated confirmation surface.

## Do's and Don'ts

### Do:

- **Do** use documentary images as evidence of place, with crops that preserve recognizable coastal context.
- **Do** keep headlines concise enough to benefit from the display serif's large, calm shapes.
- **Do** use Teal for structure and Coral for selective action or data emphasis.
- **Do** preserve the global visible focus treatment and 44px minimum actionable height.
- **Do** honor reduced-motion preferences and keep reveal effects supplementary to comprehension.
- **Do** preserve descriptive alt text, semantic headings, form labels, and source attribution.

### Don't:

- **Don't** turn the palette into a generic beach theme with pale aquas, sandy gradients, or decorative coral everywhere.
- **Don't** place small base-coral text on white or pale backgrounds; use the contrast-safe Coral on Light role.
- **Don't** add shadows to every card or layer rounded containers inside rounded containers.
- **Don't** use DM Serif Display for paragraphs, navigation, form controls, or dense interface copy.
- **Don't** stretch long-form text to the full editorial grid or preserve desktop columns past their useful reading width.
- **Don't** let animation delay access to information or remain active when reduced motion is requested.
