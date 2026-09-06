# Edgecase Wait landing page

Separate static site for Edgecase Wait. It contains no Worker, API, payment, wallet, database, analytics, or secret code.

Canonical site: https://wait.edgecasesystems.com/
API: https://wait.edgecasesystems.workers.dev/

Preview with python3 -m http.server 8080. Cloudflare Pages should use GitHub main, an empty build command, and the repository root as publish directory. Attach the custom domain only through the Pages custom-domain flow after reviewing DNS separately.
