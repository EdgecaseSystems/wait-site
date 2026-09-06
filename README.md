# Edgecase Wait landing page

Separate static site for Edgecase Wait. It contains no Worker, API, payment, wallet, database, analytics, or secret code.

Canonical site: https://wait-site.edgecasesystems.workers.dev/
API: https://wait.edgecasesystems.workers.dev/

Preview with python3 -m http.server 8080. Cloudflare Workers Builds / Workers Static Assets use GitHub `main` as the
production/public branch, with the repository root as the static asset directory. A push or merge to `main` may
automatically deploy the public site. The canonical public URL is
https://wait-site.edgecasesystems.workers.dev/. No custom domain is currently used.
