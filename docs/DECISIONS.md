# Architecture decision log

## ADR-001 — One canonical catalog
Accepted: catalog holds each resource once; other repositories refer to resource IDs.

## ADR-002 — No GitHub Actions
Accepted: no GitHub-hosted background automation. Use controlled local workflows and explicit commits for verification and publishing.

## ADR-003 — Candidate by default
Accepted: repository API metadata proves repository identity, not legal clearance, project safety or fitness.

## ADR-004 — Static website
Accepted: zero-dependency public directory with generated local JSON snapshot, resilient to raw GitHub outages.
