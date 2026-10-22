# Rift Lab – GitHub Pages site

Intended for a GitHub repo named **`<org>.github.io`** = `riftlabstudio` → repo `riftlabstudio.github.io`, published from the `main` branch root.

| Page | URL pattern | Likely final URL |
|---|---|---|
| Studio landing | `https://<org>.github.io/` | https://riftlabstudio.github.io/ |
| **Car Pocket privacy policy** (use in Play Console + in-game) | `https://<org>.github.io/carpocket/privacy/` | https://riftlabstudio.github.io/carpocket/privacy/ |
| Car Pocket terms | `https://<org>.github.io/carpocket/terms/` | https://riftlabstudio.github.io/carpocket/terms/ |
| `/carpocket/` | redirects to privacy | |

Pages use root-absolute links (`/style.css`), which only work for a user/org site (`<org>.github.io` repo), not a project site.

**Action needed in game code:** `scripts/links.gd` `PRIVACY_URL` currently is `https://riftlab.github.io/privacy/carpocket` — change to `https://riftlabstudio.github.io/carpocket/privacy/` (org confirmed: riftlabstudio).
Also confirm the in-app consent/privacy-options entry exists, as the policy refers to it "where available".
Effective date: Oct 22, 2026. Not published yet.
