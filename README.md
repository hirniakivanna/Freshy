# Freshy

Source repository for the Freshy freshness-sticker concept website and its technical infrastructure.

- Website: https://freshy-three.vercel.app
- Alternate production alias: https://freshy-freshy3.vercel.app
- `public/`: deployable static HTML, image and robots policy.
- `vercel.json`: output directory and security headers.
- `docs/infrastructure.md`: deployment inventory and maintenance workflow.
- `AGENTS.md`: persistent instructions for future project work.

## Run locally

From the repository root, run `python3 -m http.server 8000 --directory public` and open http://localhost:8000. This serves the page; Vercel applies the headers in vercel.json in deployment.

## Publication rules

Save technical work in this repository. Publish website changes after validation as part of each authorized task. If the founder says **GitHub only**, use a separate branch for deployable changes and hold publication until explicitly requested. Internal docs and design exploration stay outside `public/`.

The repository is public. Never commit secrets, environment values, private business plans, or customer information. The site remains a product concept and uses a Stripe test checkout.
