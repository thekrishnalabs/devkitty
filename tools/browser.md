# Browser Tools

Browser tools help inspect session state, browser environment details, and local data workflows.
They are useful for debugging web apps, understanding client state, and supporting frontend development.

---

## Purpose

The browser family covers session inspection, storage helpers, user-agent parsing, viewport testing, and related utilities.
These tools must stay simple, clear, and trustworthy.

---

## Included Tools

### Cookie Inspector
Shows cookies visible in the current browser context.

### Local Storage Viewer
Displays local storage entries in a readable format.

### Session Storage Viewer
Displays session storage entries in a readable format.

### Browser Info
Shows browser environment details exposed by the current session.

### User Agent Viewer
Parses and displays the current or supplied user-agent string.

### Feature Detection Helper
Shows which browser features are available in the current environment.

### Viewport Tester
Helps inspect responsive behaviour across viewport sizes.

### Theme Detector
Detects system or site theme state where available.

### Clipboard Helper
Supports clipboard-aware browser workflows where permissions allow.

---

## Interaction Standards

Browser tools must support:

- Clear read-only inspection flows where appropriate
- Safe display of session data
- Copy actions for values when useful
- Clear labels for each data group
- Mobile-safe layout

---

## Output Standards

Browser data must be presented cleanly and without ambiguity.
Sensitive values must be handled carefully and displayed only when appropriate.

---

## Common Use Cases

- Debugging frontend state
- Inspecting cookies or storage
- Testing responsive layout
- Checking browser support
- Parsing user-agent strings
- Supporting local development workflows

---

## Safety Rules

Browser tools must not expose sensitive state carelessly.
The user must understand what is visible, what is local, and what is context-dependent.

---

## Future Expansion

This family may later include:

- IndexedDB viewer
- Cache storage helper
- Permissions inspector
- Browser capability matrix
- Device profile helper
