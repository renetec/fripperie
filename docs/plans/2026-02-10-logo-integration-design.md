# Friperie 222 Logo Integration & Color Redesign

**Date:** 2026-02-10
**Status:** Approved
**Goal:** Redesign website to match new Friperie 222 logo colors and integrate logo throughout the page

---

## Design Overview

Transform the current vibrant coral/yellow/purple color scheme to match the new logo's green, blue, and teal palette while maintaining a caring, community-focused aesthetic.

---

## Color Palette Strategy

### Primary Colors (from logo)
- **Forest Green**: `#2D5016` to `#3A6B1E` - Primary brand color for text, buttons, navigation
- **Sky Blue**: `#A5C8D4` to `#B8D8E8` - Soft, caring color for hearts and secondary elements
- **Teal**: `#5FA8A8` to `#4D9999` - Accent color for clothes hanger elements

### Supporting Colors
- **Warm Coral/Peach**: `#FF8B7B` - CTAs, maintains welcoming energy
- **Soft Yellow**: `#FFE5A0` - Badges and highlights, less vibrant than current
- **Cream/Ivory**: `#FFF9F5` - Backgrounds, soft and warm
- **Deep Charcoal**: `#2D3748` - Body text for readability

### Usage Strategy
- Green: primary buttons, headings, navigation, hero overlays
- Sky blue: hover states, secondary elements, backgrounds, gradients
- Teal: accents, borders, decorative elements
- Coral: call-to-action buttons for urgency
- Yellow: badges, highlights, special notices
- Cream: page backgrounds
- Charcoal: body text

---

## Logo Placement

### 1. Header/Navigation Area
- Logo in top-left corner, 80-100px height desktop
- Sticky header on scroll with 60px logo
- Mobile: centered or left-aligned, 60px height

### 2. Hero Section
- Large logo (200-300px width) above main headline
- Animated entrance: gentle fade-in and scale-up
- Replaces or enhances current badge element

### 3. Footer
- Logo at 80-100px in footer brand section
- Standard color or slightly reduced opacity

### 4. Decorative Elements
- **Heart icon**: Floating decorative elements (replace current blobs)
- **Hands motif**: Subtle watermark in mission/impact sections
- **Hanger icon**: Accent in gallery or as bullet points
- **"222" number**: Featured in address/location sections

### 5. Favicon
- Heart with "222" as favicon
- Simplified version for mobile

---

## Section-by-Section Changes

### Hero Section
**Background:**
- Gradient overlay: `linear-gradient(135deg, rgba(45, 80, 22, 0.75) 0%, rgba(165, 200, 212, 0.70) 100%)`
- Replace colorful blobs with floating hearts (light blue) and hand silhouettes (green)

**Elements:**
- Logo: 250px centered above title
- Badge: Cream background (`#FFF9F5`) with forest green text
- Title: "Saint-Pacôme" with green gradient
- Primary CTA: Forest green background
- Secondary CTA: Sky blue border

### Info Cards (Hours & Location)
- Card 1 (Hours): Forest green accents (replace coral)
- Card 2 (Location): Keep teal (matches logo hanger)
- Icon backgrounds: Update to match new palette

### Mission Section
**Section Header:**
- Label: Forest green to teal gradient
- Title: Forest green text

**Cards:**
1. Chauffage: Forest green border, light green icon background
2. Réparations: Sky blue border, light blue icon background
3. Solidarité: Teal border, light teal icon background

**Background:**
- Subtle hand silhouettes as watermark (opacity 0.03-0.05, green)

### Impact Stats
**Background:**
- Green-to-teal gradient: `linear-gradient(135deg, #3A6B1E 0%, #A5C8D4 50%, #5FA8A8 100%)`

**Pattern:**
- Heart pattern SVG in white at 8-12% opacity
- Alternative: Large "222" watermark at center (opacity 0.08-0.10)

**Stats:**
- Keep emoji icons
- White text with subtle shadow
- Labels: White, 95% opacity

### Gallery Section
- Update hover overlays to use green gradient
- Consider logo watermark on one gallery item

### CTA Section
**Background:**
- Deep forest green: `linear-gradient(135deg, #1a3d0a 0%, #2D5016 100%)`

**Elements:**
- Decorations: Heart and hands from logo (replace emoji)
- Title highlight "préservons": Sky blue
- Primary button: Sky blue background
- Secondary button: Green border

### Footer
**Background:**
- Deep green gradient: `linear-gradient(135deg, #1a3d0a 0%, #2D5016 100%)`

**Elements:**
- Logo: 80px, possibly white version
- Brand name: White
- Tagline: Sky blue (`#A5C8D4`)
- Body text: White 70% opacity
- Accent highlights: Soft yellow
- Heart emoji: Replace 💛 with 💚

---

## Typography Updates

### Font Weights
- Main hero title: 700 (reduced from 800)
- Section titles: 700 (reduced from 800)
- Keep Poppins for headings, Inter for body

### Color Applications
- Main headlines: Forest green
- Body text: Dark charcoal
- Subheadings: Teal or medium green
- Links/CTAs: Green with blue hover
- Highlights: Soft yellow background with green text

### Special Elements
- Feature "222" as decorative number
- Use heart symbol (♥) in certain headings
- Section labels inspired by logo's "FRIPPERIE" style

---

## Additional Logo Touches

- **Scroll indicator**: Arrow in heart shape
- **Section dividers**: Thin green lines or heart/hanger icons
- **Loading states**: Heart animation
- **Favicons**: Heart with "222"

---

## Accessibility

- Ensure WCAG AA contrast standards
- Green on white: ✓ Excellent
- Blue on white: Verify darkness
- White on green: Test and adjust

---

## Implementation Notes

1. Extract exact logo colors from `/home/rene/fripperie/picture/friperie.jpg`
2. Update CSS :root variables
3. Replace gradients and color references throughout
4. Add logo HTML elements
5. Update decorative blob elements with heart/hand SVGs
6. Test responsive behavior
7. Verify accessibility contrast ratios

---

## Brand Feeling

**Target emotion:** Caring, community-focused, warm, welcoming
**Visual style:** Nature-inspired, soft, nurturing, trustworthy
**Energy level:** Calm but friendly, grounded but optimistic
