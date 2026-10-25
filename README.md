# CERIN Recovery Lab website

Static, public-facing homepage and privacy policy for the operator-controlled Google Drive recovery laboratory. No backend, analytics, tracking scripts, credentials, or production configuration.

## Publishing

1. Create a **public** repository `cerincontrol/cerin-recovery-lab` (separate from the private `cerincontrol/CERIN-Control`).
2. Upload these files to its `main` branch at repository root, preserving filenames.
3. Under **Settings → Pages**, set **Deploy from a branch** → `main` → `/ (root)` → Save.
4. Visit `https://cerincontrol.github.io/cerin-recovery-lab/` and `https://cerincontrol.github.io/cerin-recovery-lab/privacy.html` after publishing. These addresses are **predicted for the stated account and repo**, not verified until GitHub Pages publishes them.
5. Before using for Google OAuth branding, review all privacy claims. Google OAuth production verification commonly requires a verified domain you control. A github.io URL alone may not satisfy this requirement; point a custom, owned domain at GitHub Pages if Google requires ownership verification.

## Audit

- `index.html` — homepage and navigable link to privacy policy.
- `privacy.html` — description of intended Google Drive OAuth, local credential storage, retention and revocation.
- `style.css` — local responsive stylesheet, no remote assets.
- `.nojekyll` — static GitHub Pages publishing.

All site information is designed for a **lab-only** utility. No production backup, PLC, acquisition, or research data is embedded.