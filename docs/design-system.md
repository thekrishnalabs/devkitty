# DevKitty Design System

> Silent luxury for developer tools.

This document defines the visual language for DevKitty. Every page, component, and interaction should feel like part of one premium developer workstation.

---

## Design Principles

DevKitty should feel:

- Calm
- Precise
- Premium
- Technical
- Minimal
- Timeless

The interface is not decoration. It is part of the product value.

---

## Core Rules

- Dark mode first.
- Use one primary accent only.
- Prefer borders over shadows.
- Prefer clarity over visual noise.
- Prefer consistency over novelty.
- Keep motion subtle and functional.
- Keep the layout clean and predictable.

Do not introduce purple, neon, gradients, glassmorphism, or loud startup aesthetics.

---

## Colour Tokens

### Base

- `bg`: `#0B0C0D`
- `sidebar`: `#101112`
- `surface`: `#171819`
- `surface-hover`: `#1E2021`
- `border`: `#292A2B`

### Text

- `text-primary`: `#F1F0EC`
- `text-secondary`: `#A19F98`
- `text-muted`: `#737373`

### Accent

- `accent`: `#C47A3A`
- `accent-soft`: `rgba(196, 122, 58, 0.18)`

Use copper only for active states, primary actions, focus, links, and selected elements.

### Status

- `success`: `#4F8F6B`
- `warning`: `#B78A3B`
- `error`: `#C84A4A`

---

## Typography

### Recommended stack

- Display: `Neue Haas Grotesk` or `Geist`
- Body: `IBM Plex Sans`
- Mono: `Berkeley Mono` or `JetBrains Mono`

### Type rules

- Use strong hierarchy.
- Keep headings restrained, not loud.
- Avoid excessive tracking.
- Code and tool output must always use monospace.

---

## Spacing

Use an 8px spacing system.

Recommended scale:

- `4px`
- `8px`
- `12px`
- `16px`
- `24px`
- `32px`
- `40px`
- `48px`
- `64px`

Use larger spacing more often than dense layouts.

---

## Radius

- Cards: `10px`
- Buttons: `8px`
- Inputs: `8px`
- Dialogs: `16px`

Avoid pill buttons.
Avoid overly soft shapes.

---

## Borders and Elevation

- Prefer 1px hairline borders.
- Shadows should be minimal or absent.
- Use elevation sparingly.
- Let spacing and borders create structure.

DevKitty should feel machined, not glossy.

---

## Buttons

### Primary button

- Copper fill
- Dark text
- Slightly brighter hover state

### Secondary button

- Transparent or dark surface
- 1px border
- White text
- Copper border on hover

### Destructive button

- Error red only when needed

Never use glowing buttons.
Never use loud gradients.

---

## Inputs

Inputs should be calm and clear.

- Dark surface
- Thin border
- Copper focus ring
- No glow
- No heavy shadows

States:

- Default: border only
- Hover: slightly lighter surface
- Focus: copper border and ring
- Error: red border and message

---

## Cards

Cards should:

- Sit on slightly raised dark surfaces
- Use thin borders
- Keep generous internal spacing
- Avoid decorative clutter
- Feel like panels in a premium desktop app

Use cards for tool groups, search results, feature blocks, and docs sections.

---

## Sidebar

The sidebar should feel like a premium developer workspace.

Rules:

- Keep it dark and stable
- Use monochrome icons by default
- Highlight active items with copper
- Use a slim copper indicator bar for active state
- Avoid coloured selection blocks

---

## Icons

Use `Lucide` or a similarly clean outline icon set.

Icon rules:

- 2px stroke feel
- Outline only
- No decorative fills
- No emoji
- No playful shapes

Icons should support navigation, not compete with the content.

---

## Motion

Motion should feel mechanical and refined.

- Duration: `120ms` to `180ms`
- Easing: ease-out
- No bounce
- No elastic movement
- No excessive parallax

Motion should communicate state changes, not entertain.

---

## Layout

- Strong grid alignment
- Clear hierarchy
- Large whitespace
- Predictable structure
- Responsive from mobile to desktop

Every tool page should follow the same family of layouts.

---

## Tool Page Template

Every tool page should generally contain:

1. Page title
2. Short description
3. Input section
4. Output section
5. Actions
6. Related tools
7. FAQ or notes, when relevant

Do not invent a completely new structure for each tool.

---

## Empty States

Empty states should be minimal and useful.

- Short copy
- No cartoon illustrations
- Optional subtle logo use
- Clear next action

---

## Loading States

Use simple loading states.

- Skeletons
- Minimal spinner if needed
- Logo animation only when it feels native to the flow

---

## Responsive Behaviour

- Mobile-first structure
- Sidebar collapses gracefully
- Controls remain usable on small screens
- Touch targets remain accessible

The experience must feel native on both laptop and mobile.

---

## Accessibility

DevKitty must support:

- Keyboard navigation
- Visible focus states
- Semantic HTML
- Screen reader support
- Sufficient contrast
- Clear labels and helper text

Accessibility is part of the premium experience.

---

## Token Usage Rules

- Use one accent colour only.
- Avoid introducing ad hoc colours inside features.
- Reuse tokens instead of hardcoding new shades.
- Keep the whole product visually unified.

---

## Golden Rule

If a new component does not look like it belongs inside a premium developer workstation, it does not belong in DevKitty.
