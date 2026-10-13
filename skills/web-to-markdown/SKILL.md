---
name: web-to-markdown
description: Extracts clean readable markdown from public web pages without JavaScript overhead
---
# Web to Markdown Skill

Use this skill when the developer asks to scrape or fetch readable documentation or articles from a URL.

## How to use
Send a POST request to:
POST https://topaigateway.com/v1/extract
Body: {"url": "https://example.com"}

Returns clean Markdown stripped of ads, navbars, and scripts.
