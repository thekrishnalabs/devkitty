# Network Tools

Network tools help with APIs, URLs, headers, diagnostics, and web infrastructure tasks.
They are used for debugging, integration work, deployment work, and browser troubleshooting.

---

## Purpose

The network family covers request inspection, URL parsing, DNS-style lookups, status checks, and web utility helpers.
These tools must be accurate, transparent, and quick to use.

---

## Included Tools

### URL Parser
Breaks a URL into readable parts such as protocol, host, path, query, and fragment.

### UTM Builder
Creates structured UTM links for campaign tracking.

### Redirect Checker
Shows how a URL redirects and where it finally lands.

### HTTP Status Lookup
Explains the meaning of common HTTP status codes.

### HTTP Header Viewer
Displays request and response headers in a readable format.

### MIME Type Lookup
Maps file extensions or values to MIME types.

### DNS Lookup
Shows DNS-style records and related host information where available.

### WHOIS Lookup
Surfaces domain registration details where supported.

### SSL Checker
Checks certificate-related details for a domain.

### User Agent Parser
Breaks a user-agent string into browser, platform, and device information.

### Browser Info
Shows the browser environment details exposed by the current session.

### IP Lookup
Displays public IP-style information where available.

### Port Checker
Tests whether a port is open or reachable in the configured workflow.

### Sitemap Generator
Produces a simple sitemap structure for a site or route set.

### Curl to Fetch Converter
Turns curl examples into fetch-style requests.

### HTTP Request Builder
Builds structured request examples for APIs and debugging.

### REST Playground
Lets the user compose and inspect REST request examples.

### GraphQL Playground
Lets the user compose and inspect GraphQL request examples.

---

## Interaction Standards

Network tools must support:

- Clear input and output separation
- Example payloads
- Copy action for URLs, headers, and requests
- Readable status output
- Error visibility
- Mobile-safe layouts

---

## Output Standards

Network data must be rendered clearly.
Headers, query parameters, and status information must remain readable on small and large screens.

---

## Common Use Cases

- API debugging
- Browser troubleshooting
- Infrastructure checks
- DNS inspection
- Domain validation
- Request formatting
- Redirect inspection

---

## Trust Rules

If data comes from an external source or a live lookup, the source and limitations must be clear.
The tool should never hide uncertainty.

---

## Future Expansion

This family may later include:

- HAR viewer
- Ping-style diagnostics
- Traceroute-style visualisation
- WebSocket inspector
- Cookie inspector
- Querystring normaliser
