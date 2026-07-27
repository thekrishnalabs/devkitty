# DevKitty Design System

> Silent luxury for developer tools.

This document defines the visual language for DevKitty. Every page, component, and interaction must behave like part of one premium developer workstation.

---

## Design Principles

DevKitty feels:

- Calm
- Precise
- Premium
- Technical
- Minimal
- Timeless

The interface is not decoration. It is part of the product.

---

## Core Rules

- Dark mode first.
- One accent colour only.
- Borders create structure.
- Spacing creates hierarchy.
- Typography creates personality.
- Motion stays subtle and functional.
- Layout stays clean and predictable.

Purple, neon, gradients, glassmorphism, and loud startup styling are not used.

---

## Stack

### Application

- React
- TypeScript
- Vite
- Tailwind CSS
- shadcn/ui
- Lucide React

### Fonts

- Display: Geist
- Body: IBM Plex Sans
- Mono: JetBrains Mono

### Deployment and tooling

- GitHub
- Lovable
- Netlify or Vercel for deployment when needed
- GitHub Actions for repository automation

### Browser support

- Chrome
- Edge
- Firefox
- Safari

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

Copper is used for active states, primary actions, focus, links, selected elements, and key highlights.

### Status

- `success`: `#4F8F6B`
- `warning`: `#B78A3B`
- `error`: `#C84A4A`

---

## Typography

### Font roles

- Display: Geist
- Body: IBM Plex Sans
- Mono: JetBrains Mono

### Type rules

- Headings stay restrained.
- Body copy stays readable.
- Code and tool output use monospace.
- No excessive tracking.
- No decorative type effects.

### Hierarchy

- H1: large, confident, compact
- H2: clear section headings
- H3: supporting labels
- Body: readable at small and large sizes
- Mono: for code, values, hashes, JSON, and outputs

---

## Spacing

DevKitty uses an 8px spacing system.

### Scale

- `4px`
- `8px`
- `12px`
- `16px`
- `24px`
- `32px`
- `40px`
- `48px`
- `64px`

Large whitespace is part of the brand.
Dense layouts are avoided.

---

## Radius

- Cards: `10px`
- Buttons: `8px`
- Inputs: `8px`
- Dialogs: `16px`

Pill buttons are not used.
Excessively soft shapes are not used.

---

## Borders and Elevation

- Use 1px hairline borders.
- Keep shadows minimal or absent.
- Do not use glow for structural hierarchy.
- Let spacing and borders create depth.

DevKitty feels machined, not glossy.

---

## Buttons

### Primary button

- Copper fill
- Dark text
- Brighter hover state
- Clear focus state

### Secondary button

- Transparent or dark surface
- 1px border
- White text
- Copper border on hover

### Destructive button

- Error red only when needed

Glowing buttons are not used.
Loud gradients are not used.

---

## Inputs

Inputs are calm and clear.

- Dark surface
- Thin border
- Copper focus ring
- No glow
- No heavy shadow

### Input states

- Default: border only
- Hover: slightly lighter surface
- Focus: copper border and ring
- Error: red border and message

---

## Cards

Cards sit on dark surfaces with thin borders and generous internal spacing.

Cards avoid decorative clutter.
Cards feel like panels in a premium desktop app.

Cards are used for:

- Tool groups
- Search results
- Feature blocks
- Docs sections
- Empty state containers

---

## Sidebar

The sidebar feels like a premium developer workspace.

### Sidebar rules

- Dark and stable background
- Monochrome icons by default
- Copper for active items
- Slim copper indicator bar for active state
- No coloured selection blocks

---

## Icons

Icon library:

- Lucide React

Icon rules:

- Outline only
- 2px stroke feel
- No decorative fills
- No emoji
- No playful shapes

Icons support navigation and utility.
They do not compete with content.

---

## Motion

Motion is mechanical and refined.

- Duration: `120ms` to `180ms`
- Easing: ease-out
- No bounce
- No elastic movement
- No excessive parallax

Motion communicates state changes.
Motion is never decorative.

---

## Layout

- Strong grid alignment
- Clear hierarchy
- Large whitespace
- Predictable structure
- Responsive from mobile to desktop

Every tool page follows the same family of layouts.

---

## Tool Page Template

Every tool page contains:

1. Page title
2. Short description
3. Input section
4. Output section
5. Actions
6. Related tools
7. FAQ or notes, when relevant

Each tool stays within this structure.

---

## Empty States

Empty states stay minimal and useful.

- Short copy
- No cartoon illustrations
- Optional subtle logo use
- Clear next action

---

## Loading States

Loading states stay simple.

- Skeletons
- Minimal spinner if needed
- Logo animation only when it fits the flow

---

## Responsive Behaviour

- Mobile-first structure
- Sidebar collapses cleanly
- Controls remain usable on small screens
- Touch targets remain accessible

The experience stays native on laptop and mobile.

---

## Accessibility

DevKitty supports:

- Keyboard navigation
- Visible focus states
- Semantic HTML
- Screen reader support
- Sufficient contrast
- Clear labels and helper text

Accessibility is part of the premium experience.

---

## Token Usage Rules

- One accent colour only.
- No ad hoc colours inside features.
- Reuse tokens instead of hardcoding new shades.
- Keep the product visually unified.

---

## Implementation Standard

New components, pages, and tool screens must follow this system.

If a component does not look like it belongs inside a premium developer workstation, it does not belong in DevKitty.
