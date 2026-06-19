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
- `style.css` — shared styling

## Cloudflare Pages settings

Framework preset: **None**

Build command: **leave blank**

Output directory: **/**

## Deployment path

1. Create a GitHub repo, suggested name: `randy-ai-field-kit`.
2. Upload these files.
3. In Cloudflare Pages, connect the repo.
4. Use the settings above.
5. Deploy.

## Why static demos

The demos are interactive browser tools, not API wrappers. That keeps them reliable for job applications: no login, no paid API, no model downtime, no rate-limit surprise.

## Next polish pass

- Add screenshots from Twis Holo Workshop.
- GitHub profile currently points to https://github.com/Karmicmurphy; change if you want a different public profile.
- Replace placeholder screenshot folder with real images.
- Save `resume/index.html` as PDF from the browser.
- Save `portfolio/index.html` as PDF from the browser.

## Audit note

This package includes a Cloudflare `_headers` file for basic static-site hardening. It does not require Workers, KV, D1, a build command, API keys, or paid services.
