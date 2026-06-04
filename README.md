# University of Ottawa (university-of-ottawa)

The University of Ottawa (uOttawa) is a public bilingual research university in Ottawa, Ontario, Canada, and the largest English-French bilingual university in the world. It is ranked #189 in the QS World University Rankings 2025. This repository catalogs uOttawa's public, machine-readable developer/API footprint as an APIs.json profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-ottawa/refs/heads/main/apis.yml
- Naftiko Run: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-ottawa-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Canada, Bilingual, Library, Institutional Repository, DSpace, OAI-PMH, Open Access

## APIs

- **uO Research DSpace REST API** — Public DSpace 7.6.5 REST/HATEOAS API for the uO Research institutional repository. Docs: https://ruor.uottawa.ca/server/api (base URL: https://ruor.uottawa.ca/server/api)
- **uO Research OAI-PMH** — OAI-PMH 2.0 metadata-harvesting endpoint for uO Research. Docs: https://ruor.uottawa.ca/server/oai/request?verb=Identify (base URL: https://ruor.uottawa.ca/server/oai/request)

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-ottawa-plans-pricing.yml](plans/university-of-ottawa-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-ottawa-rate-limits.yml](rate-limits/university-of-ottawa-rate-limits.yml)
- FinOps: [finops/university-of-ottawa-finops.yml](finops/university-of-ottawa-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.uottawa.ca/
- GitHub: https://github.com/uottawa-wcms
- LinkedIn: https://ca.linkedin.com/school/uottawa/
- Review: [review.yml](review.yml)

## Notes

All entries were verified live on 2026-06-03. The uO Research repository (Recherche uO Research) self-reports DSpace 7.6.5 and exposes both a public DSpace REST API and an OAI-PMH 2.0 endpoint (both HTTP 200). uOttawa does not operate a single unified public developer portal, and no documented open-data, course/catalog/SIS, or mobile-backend API was found publicly; enterprise and student systems appear gated behind institutional SSO. The LinkedIn page returns HTTP 999 (LinkedIn's standard bot block) but exists. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
