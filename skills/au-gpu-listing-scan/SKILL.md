---
name: au-gpu-listing-scan
description: "Use when query au marketplace listings for gpu deals and keep a ledger of deals already reported."
---

# AU GPU Listing Scan

Query AU marketplace listings for GPU deals and keep a ledger of deals already reported.

## Tools

- `listing_search` — Search AU marketplace listings through the local searxng backend and return ranked title, url and snippet hits.
- `listing_ledger` — Read or write the plugin own JSON ledger of GPU deals already reported, so a weekly brief does not re-pitch them.

## How to use

Call the tool with the arguments listed in its schema. Configuration (`argv`, `url`, `path`) is set
in the plugin's config block, not in the call.
