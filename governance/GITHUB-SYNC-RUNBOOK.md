# GitHub sync runbook
1. Open Lovable project Settings → Git; record repository and selected branch in a private operational register.
2. For unconnected projects use native connection UI; do not create duplicate code repositories. Obtain approval before connecting.
3. Compare both commit SHAs and record timestamp; classify verified, divergent, unconnected or unknown.
4. Baseline code and test independent rebuild. Separately inventory database backup, secrets, auth and storage; never publish secrets.
5. Pilot feature branch and pull request; verify sync before rolling out protection or deployment changes.
6. Report divergence, never auto-overwrite. No Lovable AI prompt is necessary for this runbook.