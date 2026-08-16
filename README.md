# renosly.com + 8secur.com — Setup Documentation

Domain and hosting setup documentation for **renosly.com** and **8secur.com** (Hostinger).
Everything here was verified against public DNS and by loading the live sites on **16 August 2026**.

## Status at time of writing

| Check | renosly.com | 8secur.com |
|---|---|---|
| Nameservers point to Hostinger | OK | OK |
| Resolves worldwide | OK | OK |
| Website loads | OK | OK (http only) |
| HTTPS / SSL certificate | OK — valid to 14 Nov 2026 | **MISSING** |
| www redirects to main address | OK | Fails on https |
| Email routing (MX) | OK — Hostinger | OK — Hostinger |
| SPF | Present | Present |
| DKIM | Not published | Not published |
| Website content | Default WordPress | Default WordPress |

## Outstanding

1. **Install SSL on 8secur.com** — hPanel → Websites → 8secur.com → Security → SSL → Install SSL, then enable Force HTTPS.
2. Publish DKIM for both domains — hPanel → Emails → domain → DNS / DKIM.
3. Set a site title on both WordPress installs — Settings → General.

## Contents

| File | Contents |
|---|---|
| `Renosly-8secur-Setup-Documentation.pdf` | Full report (EN with French summaries) |
| `CHECKLIST.txt` | Outstanding items as a short to-do list |
| `dns/*.txt` | Full DNS record exports, one per domain |
| `screenshots/` | Both sites, desktop and mobile |
| `renosly-8secur-setup-docs.zip` | All of the above as a single download |
