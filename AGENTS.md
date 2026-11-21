# Agent instructions

1. Read `LogarithmMedia/Progress-Memory` (`SESSION-START.md`, `CURRENT.md`, `ROUTER.md`) before material work.
2. This repo owns: Source code for the agency's own site. Do not put other repos' canonical facts here.
3. Update the owning (canonical) repo first, then record state in `Progress-Memory`.
4. Record only verified facts. Never invent approvals, prices, results, client data or completion.
5. Never commit passwords, API keys, tokens or client credentials.
6. Client-confidential material stays in `Client-Delivery` and is never copied into public repos.
7. Use the exact brand spelling **LogarithmMedia**.

## GitHub safety circuit breaker

All GitHub work follows `LogarithmMedia/core/docs/policies/GITHUB-SAFETY-GUARDRAILS.md`. On a 403/429 for
restriction, abuse controls or rate limiting: stop writes and retries, record the blocker, and wait for
human approval. New or changed GitHub Actions workflows need explicit human approval.
