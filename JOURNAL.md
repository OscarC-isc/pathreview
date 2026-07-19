## Week 7 — Issue selection

**Issue link:** [https://github.com/ascherj/pathreview/issues/70](https://github.com/ascherj/pathreview/issues/70)

**Issue title:** [Add rate limiting per IP address in addition to per user #70]

**Tier:** [ ] Tier 1  [X] Tier 2  [ ] Tier 3

**Problem summary:**
Currently unauthenticated/public API requests are not rate limited at all. The current rate limiter limits requests only for authenticated user ids. This results in vulnerabilities against attacks. To fix this we add a per ip address rate limiter.
relevant files: 
- safety/rate_limiter.py
- api/middleware/

**Branch name:** feat/70-ip-rate-limit

**Setup confirmation:** [X] App runs locally at localhost:5173

**Cohort ledger:** [X] Issue added to cohort ledger