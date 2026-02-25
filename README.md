# Deliverum One Homepage (MVP)

This folder contains a minimal static homepage.

## Local preview

```bash
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080).

## Deploy option A (recommended): Cloudflare Pages + GitHub

1. Create a new GitHub repository.
2. Push this folder to that repository.
3. In Cloudflare dashboard: `Workers & Pages` -> `Create application` -> `Pages` -> `Connect to Git`.
4. Select your repository.
5. Build settings:
   - Framework preset: `None`
   - Build command: *(empty)*
   - Build output directory: `/`
6. Deploy.
7. In the Pages project: `Custom domains` -> add `deliverumone.com`.
8. Follow DNS prompts in Cloudflare until status is active.

## Deploy option B: Cloudflare Pages Direct Upload

1. In Cloudflare dashboard: `Workers & Pages` -> `Create application` -> `Pages` -> `Upload assets`.
2. Upload this folder (or drag `index.html`).
3. After first deploy, open project `Custom domains` and add `deliverumone.com`.
4. Confirm DNS records are active.

## Notes

- Keep homepage content in `index.html`.
- Next version can add a scheduling link or embedded booking widget.
