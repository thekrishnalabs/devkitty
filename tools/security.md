# Security Tools

Security tools support inspection, verification, and everyday security workflow helpers.
They are useful for authentication debugging, credential hygiene, and web safety checks.

---

## Purpose

The security family covers token inspection, hashing, password workflows, certificate-style checks, and basic secret hygiene.
These tools must be accurate and careful.

---

## Included Tools

### JWT Decoder
Parses JWT headers, payloads, and signature structure for inspection.

### JWT Generator
Builds token structures for development and testing.

### Hash Generator
Creates hash values using supported algorithms.

### HMAC Generator
Creates keyed message authentication codes.

### Password Generator
Creates strong passwords with configurable rules.

### Password Strength Checker
Evaluates password quality and reveals weak patterns.

### Secret Detector
Highlights content that looks like secrets, keys, or tokens.

### SSL Checker
Surfaces certificate-related details for a domain where available.

### BCrypt Hash
Creates BCrypt hashes for secure password storage workflows.

### Hash Comparison
Checks whether two hash values match exactly.

### Token Structure Viewer
Displays the structural parts of common security tokens.

### Base64 Secret Helper
Helps inspect whether encoded text may represent sensitive content.

---

## Interaction Standards

Security tools must support:

- Clear labels for algorithms and workflows
- Copyable output
- Validation feedback
- Mobile-safe layout
- Explicit security disclaimers where needed
- Readable error states

---

## Output Standards

Security output must be clear and direct.
The user must understand whether a value is safe, legacy, or unsuitable for production use.

---

## Common Use Cases

- Authentication debugging
- Password checks
- Token inspection
- Hash verification
- Security hygiene checks
- Secret scanning assistance
- Domain certificate checks

---

## Trust Rules

Security tools must not imply false guarantees.
If a tool is for inspection or development support only, that must be obvious.

---

## Future Expansion

This family may later include:

- Secret masker
- Token expiry viewer
- OAuth helper
- Password policy analyser
- Certificate timeline view
- Security header inspector
