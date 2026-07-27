# Use AI to Run Your Job Search

A public, single-page playbook for running a job search with AI: define your version of good, build a grounding document and a career blueprint, set up a daily search that finds roles by fit rather than title, then tailor and prep honestly.

Made by Jenny Cotie Kangas (applied AI builder). Free to adapt.

## What's here
- `index.html` — the entire site. Self-contained: inline CSS and a few lines of JS for the copy buttons. No build step, no dependencies.
- `templates/` — fill-in skeletons for the files the playbook builds: `grounding-document.md`, `career-blueprint.md`, `search-spec.md`, `seen-list.csv`, and `application-pack.md` (the per-role bundle). The search spec and seen list use the exact field labels the daily search agent reads, so keep those intact.

## Fastest way to use it
Paste the starter prompt near the top of the page into an AI that can read a web page (dial the model and thinking level up first, the work is reasoning-heavy). It reads the playbook, interviews you, and hands back each file ready to save. If your AI cannot open links, start from the templates instead.

## Publish it on GitHub Pages
1. Create a new repo, e.g. `ai-job-search`.
2. Add `index.html` (and this `README.md`) to the repo root and push.
3. In the repo, go to **Settings → Pages**, set **Source** to *Deploy from a branch*, branch `main`, folder `/ (root)`, and save.
4. It goes live at `https://<your-username>.github.io/ai-job-search/` in a minute or two. For Jenny: `https://jennycotiekangas.github.io/ai-job-search/`.

To serve it at the domain root instead, put `index.html` in a repo named `<your-username>.github.io`.

## Editing
Everything is in `index.html`. The prompts live inside `<pre>` blocks; edit them there and the copy buttons pick up the new text automatically. Section anchors (`#quickstart`, `#good`, `#grounding`, `#blueprint`, `#automation`, `#tailor`, `#prep`, `#teach`, `#templates`) drive the top nav.

## House style (keep the voice consistent)
- No em dashes. Use periods, commas, colons, or parentheses. En dashes only in number and date ranges.
- Avoid buzzwords (seamlessly, robust, leverage as a verb, elevate, unlock, cutting-edge, best-in-class). The only place they appear on purpose is inside the "scrub the AI tells" prompt, which lists them as words to avoid.
- Read it out loud. It should sound like a person teaching, not a landing page.

## Privacy
This site is generic on purpose. It contains no private career data, no employer or client names tied to confidential work, and no compensation numbers. It teaches the NDA-safe move directly: record the shape of confidential work, never the protected specifics.
