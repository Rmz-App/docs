# Contributing to RMZ Developer Docs

Thank you for your interest in contributing to the RMZ developer documentation.

## How to Contribute

### Option 1: Edit on GitHub

1. Navigate to the page you want to edit
2. Click the pencil icon to edit
3. Make your changes and submit a pull request

### Option 2: Local Development

1. Fork and clone this repository
2. Install the Mintlify CLI: `npm i -g mint`
3. Create a branch for your changes
4. Make your edits
5. Run `mint dev` and preview at `http://localhost:3000`
6. Run `mint broken-links` to verify no links are broken
7. Commit and submit a pull request

## Writing Guidelines

- **Use active voice**: "Run the command" not "The command should be run"
- **Address the reader directly**: Use "you" instead of "the user"
- **Keep sentences concise**: One idea per sentence
- **Lead with the goal**: Start instructions with what the reader wants to accomplish
- **Use consistent terminology**: See `AGENTS.md` for the term glossary
- **Include examples**: Every API endpoint needs cURL, JavaScript, Python, and PHP examples
- **Use Mintlify components**: `CodeGroup`, `Note`, `Warning`, `Tip`, `Card`, `CardGroup`

## Page Structure for API Endpoints

Every API endpoint page should follow this structure:

1. Frontmatter (title, description)
2. Heading with method badge
3. Description
4. RMZ+ plan callout (if applicable)
5. Authentication section (use snippet)
6. Headers table
7. Parameters table (query or body)
8. Example requests in CodeGroup (cURL, JavaScript, Python, PHP)
9. Success response JSON
10. Response fields table
11. Error responses table

## Domain

The RMZ domain is `rmz.gg`. Never use `rmz.sa` in any documentation.
