# Text Tools

Text tools support writing, editing, cleaning, comparing, and transforming plain text.
They are used constantly in development, content, and automation workflows.

---

## Purpose

The text family covers case conversion, line cleanup, counting, search-and-replace, and basic textual transformation.
These tools must stay fast and simple.

---

## Included Tools

### Case Converter
Switches text between uppercase, lowercase, title case, sentence case, and other formats.

### Word Counter
Counts words in text with clear totals.

### Character Counter
Counts characters with and without spaces.

### Line Counter
Counts total lines and non-empty lines.

### Remove Duplicate Lines
Removes repeated lines while preserving useful structure.

### Remove Empty Lines
Strips empty or blank lines from pasted text.

### Sort Lines
Sorts lines alphabetically or in another predictable order.

### Reverse Text
Reverses text content in a controlled way.

### Slug Generator
Converts phrases into clean URL-style slugs.

### Lorem Ipsum Generator
Generates placeholder text for layout and design work.

### Find and Replace
Searches text and replaces matching values.

### Escape and Unescape
Converts special characters into escaped or unescaped output.

### Unicode Converter
Shows Unicode-style representations of text where useful.

### ASCII Converter
Shows ASCII-style output where applicable.

### Text Diff
Highlights differences between two text inputs.

### ROT13
Applies a simple substitution transformation for legacy use cases.

### Trim Whitespace
Removes leading and trailing whitespace.

### Text to Binary
Converts text into binary-style output.

---

## Interaction Standards

Text tools must support:

- Paste input
- Copy output
- Clear actions
- Large text handling
- Mobile-safe layout
- Line-aware formatting

---

## Output Standards

Text output must remain readable and predictable.
Where a transformation changes meaning or structure, that must be obvious.

---

## Common Use Cases

- Editing notes
- Cleaning pasted text
- Writing content
- Preparing URLs
- Formatting documentation
- Comparing snippets
- Preparing data for scripts

---

## Quality Rules

Text tools must not silently change content in surprising ways.
If ordering, case, whitespace, or punctuation changes, that change must be easy to understand.

---

## Future Expansion

This family may later include:

- Title case variants
- Sentence normaliser
- Duplicate word detector
- Text statistics panel
- Reading time helper
- Text encoder chain helper
