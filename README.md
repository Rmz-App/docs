# RMZ Developer Docs

Developer documentation for the RMZ platform — the leading digital products marketplace for the MENA region.

Built with [Mintlify](https://mintlify.com). Published at [docs.rmz.gg](https://docs.rmz.gg).

## What's Covered

- **Merchant API** — manage stores, orders, products, categories, and subscriptions
- **Storefront API** — build custom storefronts with product browsing, cart, checkout, and OTP auth
- **Embed API** — embed quick-purchase checkout widgets on external sites
- **License Verification API** — verify software license keys with HWID/IP lock and E2EE
- **Webhooks** — receive real-time notifications for order events
- **Storefront SDK** — TypeScript SDK for the Storefront API
- **FiveM Integration** — sell and deliver FiveM server products automatically

## Development

Install the Mintlify CLI:

```bash
npm i -g mint
```

Preview locally:

```bash
mint dev
```

Open `http://localhost:3000` to view the docs.

## Check for Broken Links

```bash
mint broken-links
```

## Publishing

Changes pushed to the default branch are deployed automatically via the Mintlify GitHub app.

## Project Structure

```
docs-repo/
  docs.json              # Mintlify configuration and navigation
  index.mdx              # Landing page
  getting-started/       # Introduction, quickstart, auth, errors
  merchant-api/          # Merchant API reference
  storefront-api/        # Storefront API reference
  embed-api/             # Embed API reference
  webhooks/              # Webhook documentation
  licensing/             # License verification docs
  storefront-sdk/        # Storefront SDK docs
  fivem/                 # FiveM integration docs
  guides/                # How-to guides
  snippets/              # Reusable MDX snippets
  images/                # Static images
  logo/                  # Brand logos
```
