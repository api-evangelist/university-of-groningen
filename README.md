# University of Groningen (university-of-groningen)

The University of Groningen (Rijksuniversiteit Groningen, RUG/UG) is a public research university in Groningen, Netherlands, founded in 1614 and ranked #75 in the QS World University Rankings 2025. This repository catalogs its public, machine-readable developer/API footprint as an APIs.json profile. That footprint is centered on research-output and research-data infrastructure (Pure CRIS OAI-PMH and REST, plus the shared DataverseNL repository) rather than a unified self-service developer portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-groningen/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-groningen-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, Open Data, Research Data, Library, Metadata, Netherlands, Europe

## APIs

- **UG Research Portal OAI-PMH (Pure)** — OAI-PMH metadata harvesting over the UG research portal (Elsevier Pure CRIS), OpenAIRE CERIF profile. Verified live. Docs: https://www.rug.nl/library/support/pure/ug-research-portal/?lang=en — Endpoint: https://pure.rug.nl/ws/oai
- **UG Pure Web Services REST API** — Elsevier Pure REST web-services API for research information; live but API-key gated (HTTP 401 without credentials). Docs: https://www.rug.nl/library/support/pure/?lang=en — Endpoint: https://pure.rug.nl/ws/api
- **DataverseNL Native REST API (UG Default Data Repository)** — Dataverse Native REST API for the DANS-operated DataverseNL repository, the UG default repository for research data and software (Dataverse v6.9, verified live). Docs: https://guides.dataverse.org/en/latest/api/native-api.html — Endpoint: https://dataverse.nl/api
- **iBridges / Python API for iRODS** — Open-source Python iRODS client libraries and tooling published by the official UG GitHub org (source-code SDKs, not a hosted API). Docs: https://github.com/rijksuniversiteit-groningen

## Plans

- [plans/university-of-groningen-plans-pricing.yml](plans/university-of-groningen-plans-pricing.yml)

## Rate Limits

- [rate-limits/university-of-groningen-rate-limits.yml](rate-limits/university-of-groningen-rate-limits.yml)

## FinOps

- [finops/university-of-groningen-finops.yml](finops/university-of-groningen-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.rug.nl/
- GitHub: https://github.com/rijksuniversiteit-groningen
- LinkedIn: https://www.linkedin.com/school/rijksuniversiteit-groningen/
- Twitter/X: https://twitter.com/univgroningen
- Plans: plans/university-of-groningen-plans-pricing.yml
- Rate Limits: rate-limits/university-of-groningen-rate-limits.yml
- FinOps: finops/university-of-groningen-finops.yml
- Review: review.yml

## Notes

- Verification caveats: the Pure OAI-PMH endpoint returned a valid OAI-PMH XML response for `ListMetadataFormats` (200); the `Identify` verb returned a 500 server error at probe time but the endpoint is live. The Pure REST API is live but returns HTTP 401 without an institution-issued API key (gated). DataverseNL is a shared, DANS-operated platform serving multiple Dutch institutions; UG designates it as its default data repository.
- No unified self-service public developer portal or public key-issuing program was found. SIS, timetable, and identity (SSO) APIs appear internal or gated. No endpoints were fabricated; gated and error states are reported honestly.

## Maintainers

- Kin Lane — kin@apievangelist.com
