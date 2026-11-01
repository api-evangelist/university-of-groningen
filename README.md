# University of Groningen

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The University of Groningen (Rijksuniversiteit Groningen, RUG/UG) is a public research university in Groningen, the Netherlands, founded in 1614. Measured honestly, it runs no API programme: there is no developer portal, no api.rug.nl, no status page, no published versioning or deprecation policy, and no first-party OpenAPI anywhere on its estate — api.rug.nl, data.rug.nl, developer.rug.nl and status.rug.nl do not resolve at all. What it does operate, on its own domain, is a small set of real programmable surfaces: the Ocasys course and degree-programme catalog, whose JSON backend at ocasys.rug.nl/api answers unauthenticated course search, full course records, programme search, faculties and controlled option lists, and emits RFC 9457 problem details on error; a keyless OAI-PMH 2.0 endpoint at pure.rug.nl/ws/oai serving 1,521,703 identifiers across six metadata profiles including OpenAIRE CERIF 1.2 with resolvable ORCID iDs; and its own SAML 2.0 identity provider at signon.rug.nl, registered in eduGAIN through SURFconext. Everything else that looks like a University of Groningen API is a purchase. The CRIS is Elsevier Pure, research data lives in a collection inside the shared national DataverseNL installation that DANS and SURF operate, and library discovery is OCLC WorldCat. Those are recorded here as tenant relationships, not as the University's engineering.

**Areas:** Education · Higher Education · University · Netherlands · Europe · Research · Research Data · Course Catalog · Identity Federation · OAI-PMH · Library · Metadata

## University of Groningen on APIs.io

Everything profiled for University of Groningen is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-groningen/](https://apis.io/providers/university-of-groningen/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [University of Groningen Identity Provider (SURFconext / eduGAIN)](https://apis.io/apis/university-of-groningen/identity-provider/) — The University runs its own SAML 2.0 identity provider and publishes signed federation metadata at signon.rug.nl for entityID…
- [University of Groningen Research Portal (Pure) REST API](https://apis.io/apis/university-of-groningen/pure-ws-api/) — The Elsevier Pure web service deployed on the University's CRIS host. Probed 2026-08-30: pure.rug.nl/ws/api redirects to /ws/api/documentation/index.html,…
- [University of Groningen research data collection on DataverseNL](https://apis.io/apis/university-of-groningen/dataversenl-collection/) — The University's default repository for research data and software is a collection inside DataverseNL, the shared national Dataverse installation that DANS…
- [University of Groningen Library discovery (OCLC WorldCat)](https://apis.io/apis/university-of-groningen/worldcat-discovery/) — Library discovery runs on OCLC WorldCat Discovery at rug.on.worldcat.org, a tenant instance on OCLC's platform rather than a catalog interface the…
- [University of Groningen Academic Years API](https://apis.io/apis/university-of-groningen/university-of-groningen-academic-years-api/) — Which academic years the catalog holds and when the next one starts.
- [University of Groningen Courses API](https://apis.io/apis/university-of-groningen/university-of-groningen-courses-api/) — Course search and full course descriptions.
- [University of Groningen OAI PMH API](https://apis.io/apis/university-of-groningen/university-of-groningen-oai-pmh-api/) — The six verbs of the Open Archives Initiative Protocol for Metadata Harvesting 2.0.
- [University of Groningen Option Lists API](https://apis.io/apis/university-of-groningen/university-of-groningen-option-lists-api/) — Controlled vocabularies used by course and programme records.
- [University of Groningen Organization API](https://apis.io/apis/university-of-groningen/university-of-groningen-organization-api/) — Faculties and departments used to scope courses and programmes.
- [University of Groningen Programmes API](https://apis.io/apis/university-of-groningen/university-of-groningen-programmes-api/) — Degree-programme search.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (2)

The data models the API reads and writes.

- [Ocasys Course](https://apis.io/schemas/university-of-groningen/university-of-groningen-ocasys-course/)
- [Ocasys Degree Programme](https://apis.io/schemas/university-of-groningen/university-of-groningen-ocasys-program/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [University Of Groningen Course Context](https://apis.io/jsonld/university-of-groningen/university-of-groningen-course-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [University of Groningen Research API Vocabulary](https://apis.io/vocabularies/university-of-groningen/university-of-groningen-vocabulary/)

#### Examples (5)

Example requests and responses.

- [University Of Groningen Ocasys Course Search Example](https://apis.io/examples/university-of-groningen/university-of-groningen-ocasys-course-search-example/)
- [University Of Groningen Ocasys Faculties Example](https://apis.io/examples/university-of-groningen/university-of-groningen-ocasys-faculties-example/)
- [University Of Groningen Ocasys Get Course Example](https://apis.io/examples/university-of-groningen/university-of-groningen-ocasys-get-course-example/)
- [University Of Groningen Ocasys Problem Detail Example](https://apis.io/examples/university-of-groningen/university-of-groningen-ocasys-problem-detail-example/)
- [University Of Groningen Ocasys Program Search Example](https://apis.io/examples/university-of-groningen/university-of-groningen-ocasys-program-search-example/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [University of Groningen — course catalog rules](https://apis.io/rules/university-of-groningen/university-of-groningen-course-catalog-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Groningen Authentication](https://apis.io/security/university-of-groningen/university-of-groningen-authentication/)
- [University Of Groningen Domain Security](https://apis.io/security/university-of-groningen/university-of-groningen-domain-security/)
- [University Of Groningen Vulnerability Disclosure](https://apis.io/security/university-of-groningen/university-of-groningen-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Groningen Plans Pricing](https://apis.io/plans/university-of-groningen/university-of-groningen-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Groningen Rate Limits](https://apis.io/rate-limits/university-of-groningen/university-of-groningen-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Groningen Finops](https://apis.io/finops/university-of-groningen/university-of-groningen-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.rug.nl/)
- [Documentation](https://wiki.hpc.rug.nl/)
- [Support](https://www.rug.nl/society-business/center-for-information-technology/support/)
- [Blog](https://www.rug.nl/about-ug/latest-news/news/latest-rug-news!rss)
- [Terms of service](https://www.rug.nl/info/disclaimer-copyright)
- [Privacy policy](https://www.rug.nl/privacy)
- [GitHub](https://github.com/rijksuniversiteit-groningen)

## API Evangelist rating

**Kin Score 36.0** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 48.7 |
| Contract governance | 21.2 |
| Operational transparency | 10.5 |
| Developer ergonomics | 28.6 |
| Access clarity | 26.3 |

**Agent readiness 21.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 30.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-groningen/](https://apis.io/providers/university-of-groningen/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Groningen: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-groningen/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
