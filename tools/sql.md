# SQL Tools

SQL tools support query formatting, inspection, comparison, and database workflow support.
They belong in DevKitty because SQL is part of everyday backend, analytics, and application work.

---

## Purpose

The SQL family covers formatting, minification, comparison, conversion, and query assistance.
These tools must stay readable and trustworthy.

---

## Included Tools

### SQL Formatter
Formats SQL into clean, readable structure.

### SQL Minifier
Removes unnecessary whitespace from SQL output.

### SQL Diff
Compares two SQL snippets and highlights differences.

### Query Builder
Helps construct structured SQL query examples.

### Schema Visualiser
Shows table and relationship structure in a readable form.

### EXPLAIN Helper
Helps interpret execution-plan-style output.

### SQL Beautifier
Produces a polished readable SQL layout.

### SQL to JSON
Converts SQL result-style rows into JSON structures where applicable.

### JSON to SQL
Helps generate SQL-like examples from structured data when useful.

### Database Snippet Helper
Generates small reusable query fragments for common tasks.

---

## Interaction Standards

SQL tools must support:

- Paste input
- Copy output
- Clear syntax errors
- Large query handling
- Monospace output
- Mobile-safe layout

---

## Output Standards

SQL output must remain valid and readable.
Formatting changes must preserve the original query meaning.

---

## Common Use Cases

- Query debugging
- Reporting work
- Analytics
- Backend development
- Database migration support
- Query optimisation checks

---

## Quality Rules

SQL tools must not hide query changes.
If a transformation changes structure or meaning, that change must be obvious.

---

## Future Expansion

This family may later include:

- Dialect selector
- Index suggestion helper
- Join visualiser
- Query linting helper
- Table definition generator
- Foreign key map view
