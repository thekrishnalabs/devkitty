# HTML Tools

HTML tools support markup editing, conversion, metadata generation, and browser-facing content work.
They belong in DevKitty because they are used constantly in frontend, content, and documentation workflows.

---

## Purpose

The HTML family covers formatting, minification, preview, conversion, and metadata helpers.
These tools must be clear, reliable, and easy to use.

---

## Included Tools

### HTML Formatter
Formats HTML into readable, indented structure.

### HTML Minifier
Removes unnecessary whitespace and comments from HTML output.

### HTML Preview
Renders HTML safely in a preview frame.

### Meta Tag Generator
Generates standard metadata for pages and content.

### Open Graph Generator
Creates Open Graph metadata for social sharing previews.

### robots.txt Generator
Builds robots.txt content for a site.

### Sitemap Generator
Creates sitemap-style output for a site or route set.

### Markdown to HTML
Converts Markdown into HTML markup.

### HTML to Markdown
Converts HTML into Markdown where a clean mapping is possible.

### HTML Entity Encoder
Encodes reserved HTML characters into entities.

### HTML Entity Decoder
Decodes HTML entities back into readable text.

### Favicons and Social Preview Helper
Builds markup guidance for favicon and social preview usage.

---

## Interaction Standards

HTML tools must support:

- Paste input
- File input where useful
- Copy output
- Download output
- Live preview where relevant
- Clear parsing errors
- Safe handling of untrusted markup

---

## Output Standards

HTML output must be readable and predictable.
Generated markup must be easy to copy into a project or content workflow without cleanup.

---

## Common Use Cases

- Web page markup work
- SEO metadata setup
- Social preview setup
- Documentation conversion
- Frontend debugging
- Content workflow support

---

## Safety Rules

HTML preview must avoid unsafe execution paths.
The tool should clearly separate raw markup, rendered preview, and generated metadata.

---

## Future Expansion

This family may later include:

- Accessibility checker helper
- DOM structure inspector
- Tag nesting validator
- Email-safe HTML helper
- Structured data generator
