# Randy AI Field Kit

Static, Cloudflare-ready portfolio hub for Randy Noxon.

## Purpose

One live portfolio link for remote AI evaluator / prompt tester / AI workflow roles.

Front-door identity:

**AI Response Evaluator · Prompt Systems Tester · AI Workflow Builder**

Core line:

> I test AI systems, find where they fail, repair the workflow, and document the fix.

## What is included

- `index.html` — homepage / portfolio hub
- `demos/ai-response-triage.html` — interactive evaluator demo
- `demos/prompt-repair-card.html` — interactive repair prompt generator
- `demos/artifact-compass-lite.html` — interactive artifact registry demo
- `case-studies/` — job-facing project case studies
- `resume/index.html` — printable resume page
- `portfolio/index.html` — printable about/portfolio copy
- `style.css` — shared responsive styling
- `_headers` — basic Cloudflare/static-site hardening
- `404.html` — clean fallback page
- `robots.txt` — simple crawl permission file

## Cloudflare Pages settings

Framework preset: **None**

Build command: **leave blank**

Output directory: **/**

No Workers, KV, D1, API keys, Node install, or build step are required.

## Deployment path

1. In Cloudflare Pages, choose **Create a project**.
2. Connect this GitHub repo: `Karmicmurphy/clean-static-portfolio`.
3. Use the settings above.
4. Deploy.
5. Use the Cloudflare Pages URL as the main job-application portfolio link.

## Why static demos

The demos are interactive browser tools, not API wrappers. That keeps them reliable for job applications: no login, no paid API, no model downtime, no rate-limit surprise.

## Mobile / desktop notes

The layout uses responsive CSS breakpoints for phone, tablet, and desktop:

- Mobile stacks all cards and buttons vertically.
- Buttons and form controls meet a minimum tap target size.
- Text areas and output boxes wrap long text.
- Tablet widths collapse the hero into one column before it gets cramped.
- Print styles are included for resume/portfolio pages.

## Next polish pass

- Add screenshots from Twis Holo Workshop.
- Replace placeholder screenshot folder with real images if/when desired.
- Save `resume/index.html` as PDF from the browser.
- Save `portfolio/index.html` as PDF from the browser.
- Optionally pin this repo and `Ollie_Twis_Holo_workshop` on GitHub.

## Audit note

This package is intentionally static and low-risk for job applications. It does not require Workers, KV, D1, a build command, API keys, or paid services.
