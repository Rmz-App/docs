# Documentation Project Instructions

## About This Project

- This is the RMZ developer documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration and navigation live in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "RMZ" (not "Dokan" or "rmz.sa") — the domain is **rmz.gg**
- Use "store" not "shop"
- Use "merchant" or "store owner" not "seller"
- Use "customer" not "buyer" or "user" when referring to end-users of a store
- Use "Merchant API" not "Shawarma API" in user-facing docs (Shawarma is the internal codename)
- Use "digital products" — RMZ does not handle physical goods
- Product types: `product`, `code`, `service`, `subscription`, `course`

## Style Preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, endpoints, and code references
- All content in English
- Use Mintlify components: `CodeGroup`, `Note`, `Warning`, `Tip`, `Card`, `CardGroup`, `Snippet`
- Every API endpoint page must include: method badge, auth snippet, headers table, parameters table, CodeGroup examples (cURL, JavaScript, Python, PHP), success response JSON, and error responses table

## Content Boundaries

- Document public APIs only — do not document internal admin/office endpoints
- Do not document the mobile app API (it is for internal use)
- Do not reference internal codenames (Shawarma, Hummus, Kebab) in user-facing content
- RMZ is a platform, not a seller — no refunds documentation; complaints are mediation only
