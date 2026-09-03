# createacal-www

Public marketing and legal pages for **CreateACal** / **CaleMarley**.

This repository is intentionally **public** and contains **only** static Coming Soon + legal/SMS pages.
It does **not** include the private calendar application (`Marleyku/calendar` stays private).

## Live hosts

| Host | Notes |
|------|--------|
| https://createacal.com/ | Primary |
| https://www.createacal.com/ | Same site |
| https://calemarley.com/ | Same public pages |
| https://www.calemarley.com/ | Same public pages |

**Routes:** `/` · `/coming-soon` · `/sms-opt-in` · `/privacy` · `/terms`

## Deploy

Static files live in `public/`. Deploy with:

```bash
npx wrangler deploy
```

Hosted on Cloudflare Workers Assets. Source of truth: this GitHub repo.
