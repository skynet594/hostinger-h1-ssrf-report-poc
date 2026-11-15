# Hostinger H1 SSRF — PoC repo

Non-destructive proof-of-concept for an authorized HackerOne engagement
(Hostinger bug bounty program, researcher Eli-dort).

This repo exists solely so the Hostinger git-deploy endpoint fetches its
.gitmodules under an authorized SSRF test against the researcher's own
hosting account. No other systems are targeted.
