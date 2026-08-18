# Deliverum One

Minimal static website for **Deliverum One**.

Deliverum One helps delivery and PMO teams do more with less through practical AI agents, automation and experienced experts in the loop.

## Website

Production: https://deliverumone.com

The site intentionally keeps the public proposition concise. The current positioning focuses on three things:

- **Delivery intelligence** — agents that evaluate project and programme health and surface what needs attention.
- **Delivery co-pilots** — practical support for programme managers, PMO teams and delivery leaders.
- **Experts in the loop** — Deliverum One SMEs provide judgement and delivery expertise where automation alone is not enough.

## Structure

```text
index.html   # Production homepage
README.md    # Repository documentation
```

There is no framework, build process or dependency stack. The homepage is deliberately implemented as a single static HTML file.

## Local preview

From the repository directory:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deployment

The repository is intended to deploy through **Cloudflare Pages** connected to GitHub.

Recommended settings:

- Framework preset: `None`
- Build command: leave empty
- Build output directory: `/`
- Production branch: `main`

With Git integration enabled, changes pushed to `main` can be deployed automatically by Cloudflare Pages.

## Updating the site

For normal content and design changes, edit `index.html` and push the change to `main`. Keep the site lightweight and avoid adding dependencies unless they provide a clear benefit.

## Contact

hello@deliverumone.com

© 2026 Deliverum One.