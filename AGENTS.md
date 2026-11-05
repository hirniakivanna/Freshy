# Freshy project instructions

## Source of truth and publication

- Use https://github.com/hirniakivanna/Freshy as the canonical repository for all Freshy code, design assets, frontend, backend, security configuration, tests, and technical documentation. Save meaningful work there as part of completing each task.
- Default: implement authorized website changes, validate, commit to GitHub, deploy the exact recorded source to the existing Vercel freshy project, and verify the result. Report commit and deployment status truthfully. Do not claim automatic deployment is configured unless verified.
- When the founder says **GitHub only**, **do not publish**, **not on the website**, or equivalent, keep deployable changes on a separate branch and do not merge to main, deploy, or promote until explicitly authorized. Label the branch/PR and record its status. Do not assume a main-branch commit is safe if deployment integrations exist.
- For internal-only documentation or design assets that must never be served, keep them outside public/ and verify the deployment output excludes them. Backend source belongs in the repository but must run server-side, never be copied into public/.
- Preserve existing website behavior and design unless the requested work calls for a change.
- Keep secrets, API keys, passwords, environment values, customer information and private business memory out of this public repository. Commit safe configuration and variable names only. Cybersecurity source/configuration belongs here; confidential findings and credentials do not.

## Current deployment

- Existing Vercel project: freshy; project ID prj_QAdwGaDfGFN4rEhqwvOrAETTvT73; team ID team_EX6roioBmDJDi82dmYk06ccw.
- Existing production aliases: https://freshy-three.vercel.app and https://freshy-freshy3.vercel.app.
- Static site files: public/. Vercel configuration: vercel.json; outputDirectory must remain public for this layout. No build or install is required.
- Never create a second Vercel project to work around missing repository access. Preserve existing audience/protection settings.
- Current checkout is Stripe test mode. Do not activate live payments without founder instruction.
- After HTML/CSS changes, recalculate the CSP inline-style hash when applicable and check local asset paths and checkout links.

## Continuity

Read and update the private Freshy Memory Bank through the connected Library when available. Its canonical identity is libfile_0d29500c77d881919d72affdeee0803d. Do not copy its business contents into this public repository. Record dated task outcomes, links, unchecked work, founder questions, and GitHub-only branch status there. Use Recommendation: for proposed answers to gaps, not invented facts.

## Customer profile and writing requirements

Before drafting any Freshy advice, copy, or customer-facing material, read the latest private Freshy-Customer-Profile.md from Library (libfile_5216b75fd11481918a5fb178a2860b23), or ask for it if unavailable. Do not invent its contents or assume every external AI has file access; provide the profile as project context when using another AI.

Use concise professional plain language with correct grammar and syntax. Use short labels and two-sentence bullets for profiles, prefer quantified evidence, quote founder answers where useful, and mark guesses with 🔎. Label proposed gap-fillers “🔎 Recommendation:” and omit unrelated business-model content. Separate founder targets from validated customer facts and achieved product outcomes. No fixed word limit has been supplied. Keep the private profile contents out of this public repository and website; this instruction file is outside public/.
