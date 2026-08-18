# Deliverum One

Minimal static website for [deliverumone.com](https://deliverumone.com).

## Positioning

**We turn complex initiatives into delivered outcomes.**

Deliverum One takes clear ownership of execution and helps teams work together to get important work delivered.

The website is intentionally minimal: one hero message, one supporting sentence, and direct contact details.

## Repository structure

```text
index.html   # Production homepage
README.md    # Repository documentation
```

There is no framework, package manager, build step, or dependency stack. The site is a single static HTML file.

## Updating the website

The production source is `index.html` on the `main` branch.

To update it manually through GitHub:

1. Open `index.html`.
2. Select **Edit this file**.
3. Replace the existing contents with the new version.
4. Select **Commit changes**.
5. Commit directly to `main`.

If the repository is connected to Cloudflare Pages, Cloudflare should detect the new commit and deploy it.

## Local preview

If you have the repository locally, run:

```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## Design principles

Keep the site:

- minimal;
- fast;
- responsive;
- typography-led;
- free of unnecessary dependencies;
- focused on the proposition rather than detailed service descriptions.

Current visual direction:

- warm off-white background;
- near-black typography;
- muted green accent;
- generous whitespace;
- oversized hero typography.

## Contact

hello@deliverumone.com

© Deliverum One
