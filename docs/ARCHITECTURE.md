# Architecture: canonical records and derived outputs

- catalog/data/resources.json: **canonical** metadata and candidate status.
- catalog/data/taxonomy.json: category labels used by all consumers.
- skills/: reusable agent instructions, not arbitrary execution scripts.
- mcp-servers/: assessments and installation guidance, not endorsed binaries.
- workflows/: documented procedures linking IDs in catalog and skills.
- knowledgebase/: research, comparisons, architecture decisions and evidence.
- design-system/: cross-project tokens and interaction patterns.
- website/data/resources.json: **generated mirror**. Update only using website/scripts/sync_catalog.py in an authorized local environment.
- .github/: organization governance and agent safety.

No GitHub Actions are deployed. Changes are reviewed and pushed explicitly from controlled devices.
