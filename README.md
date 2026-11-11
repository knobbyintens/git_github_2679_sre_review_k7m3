# Atlas Platform Service Catalog

This repository is the source of truth for the Atlas platform service catalog.
The SRE team reviews every service manifest once a month.

Repository layout:
- `services/` - one JSON manifest per service
- `reports/` - monthly SLO review reports produced by the review workflow
- `docs/` - operational reference material

Never edit manifests by hand outside of the monthly review workflow.
