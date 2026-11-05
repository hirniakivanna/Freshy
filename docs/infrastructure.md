# Infrastructure inventory

Verified 2026-11-04 (America/New_York).

## Recovered deployment

- Vercel team: team_EX6roioBmDJDi82dmYk06ccw.
- Vercel project: freshy (prj_QAdwGaDfGFN4rEhqwvOrAETTvT73).
- Recovered production deployment: dpl_CWvCwURDjZJxaeSqLq2gcXePmmiw (READY).
- Production aliases: freshy-three.vercel.app and freshy-freshy3.vercel.app.
- Platform reported Node.js 24.x; the current site is static and has no backend or runtime dependencies in the recovered source.
- No database, server application, or proprietary sensor implementation was present in the recovered deployment. This inventory does not assert that unrelated account resources do not exist.

Recovered files and original SHA-1 byte checksums (Vercel source file identifiers):

| Original file | SHA-1 |
| --- | --- |
| index.html | 6d84ee3524549f0d70ce4e736370b995be46e19a |
| assets/freshy.webp | 228efc94d49ea544b778bfc05c95d01574a44220 |
| robots.txt | 63657cbb7d7086c56b0cd4e5c6999bb683664868 |
| vercel.json | 3a169316d9784e1bfd70961faed517b9f545b518 |

The HTML, image and robots file were preserved byte-for-byte under public/. vercel.json preserves the original header values and changes outputDirectory from `.` to `public` so repository documentation is outside website output.

## Security and payment configuration

Configured headers include Content-Security-Policy, X-Content-Type-Options, Referrer-Policy, Permissions-Policy, X-Frame-Options, Strict-Transport-Security and X-Robots-Tag. The page and robots.txt request no indexing. This is an inventory, not a full security audit or legal clearance.

The recovered Buy link matches the founder's supplied Stripe test URL. No payment was submitted. Source recovery does not verify physical product performance, commercial readiness or image rights.

Vercel reported SSO protection enabled for all_except_custom_domains, password protection disabled and trusted IP restrictions disabled at inspection. Access settings are account-side configuration, not fully captured by vercel.json; preserve them unless the founder requests a change.

## Ongoing workflow

1. Read AGENTS.md; inspect current branch, deployment connection and source before editing.
2. Save code, design assets, frontend/backend and safe security configuration in GitHub.
3. For website changes, verify files and security configuration, commit, deploy the exact source to the existing project, then check deployment status and relevant behavior.
4. For GitHub-only work, keep deployable changes on a separate branch until publication is explicitly requested. Files outside public/ are excluded from this static website output.
5. Record commit, deployment URL, missing checks and held branches in the private memory bank.

Recommendation: use the existing project's Git connection once available and verified. If no push-to-deploy connection is configured, deploy explicitly during each website task and report that distinction. Do not create duplicate projects or pretend ongoing background deployment is configured.
