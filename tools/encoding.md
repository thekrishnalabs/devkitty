# Encoding Tools

Encoding tools form one of the core utility families in DevKitty.
They are used constantly during debugging, API work, automation, security checks, and data handling.

---

## Purpose

The encoding family covers transformations, hashing, decoding, and identity helpers.
These tools must be fast, deterministic, and easy to trust.

---

## Included Tools

### Base64 Encode / Decode
Converts text and binary-safe payloads to and from Base64.

### URL Encode / Decode
Encodes and decodes URL-safe values for query strings and request flows.

### HTML Encode / Decode
Converts unsafe or reserved HTML characters into safe entity output and back.

### JWT Decoder
Parses JWT headers, payloads, and signatures for inspection.

### JWT Generator
Builds signed token structures for development and testing.

### MD5 Generator
Produces MD5 hashes for non-security use cases.

### SHA-1 Generator
Produces SHA-1 hashes for legacy workflows.

### SHA-256 Generator
Produces SHA-256 hashes for common verification workflows.

### SHA-512 Generator
Produces SHA-512 hashes for stronger digest output.

### HMAC Generator
Generates keyed message authentication codes using selectable algorithms.

### BCrypt Hash
Creates BCrypt hashes for password-handling workflows.

### Password Generator
Generates secure passwords with configurable length and character rules.

### Password Strength Checker
Evaluates password strength and points out weak patterns.

### UUID Generator
Generates RFC-style UUID values for system identifiers and testing.

### UUID v7 Generator
Generates time-ordered UUID v7 values for modern identity workflows.

### NanoID Generator
Generates compact random identifiers for URLs, records, and client-side keys.

### Random String Generator
Creates opaque random strings for testing and placeholders.

### Hash Comparison
Compares two hashes and helps verify whether values match exactly.

---

## Interaction Standards

Encoding tools must support:

- Paste input
- Copy output
- Download output when appropriate
- Clear algorithm labels
- Explicit character-set handling where needed
- Clear success and error states
- Mobile-safe layout

---

## Output Standards

Encoding results must be predictable.
The user must see exactly which algorithm or transformation produced the output.

---

## Common Use Cases

- API debugging
- Authentication workflows
- Security checks
- Token inspection
- DevOps scripts
- Data transformation
- Testing and prototyping

---

## Trust Rules

Hash tools must clearly state whether an algorithm is suitable for security use.
Legacy or insecure algorithms must not be presented as modern best practice.

---

## Future Expansion

This family may later include:

- Caesar cipher helpers
- ROT13
- Encoding chain explorer
- Salting visualiser
- Token comparison view
- Secret validation helpers
