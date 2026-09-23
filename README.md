# University of Groningen (university-of-groningen)

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

The University of Groningen (Rijksuniversiteit Groningen, RUG/UG) is a public research university in
Groningen, the Netherlands, founded in 1614. This repository catalogs its public, machine-readable
footprint as an APIs.json profile.

Re-profiled 2026-08-30 under the API Evangelist **university pipeline**, which settles *who operates
a surface* before saving any contract. The previous profile credited this University with 73 OpenAPI
specifications; every one of them was a split of two vendor contracts — Elsevier Pure and the
DataverseNL installation DANS and SURF operate — and all 73 carried the same wrong base URL. They
have been removed, along with 145 collections and every schema, example, ruleset, vocabulary,
JSON-LD context and agentic-access file derived from them: 235 files in total.

What replaced them is smaller and actually the University's own.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-groningen/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-groningen-api-evangelist&utm_content=repo

## Type

- Index / university (Public Research University)
- Consumer
- Public

## Tags

Education, Higher Education, University, Netherlands, Europe, Research, Research Data, Course
Catalog, Identity Federation, OAI-PMH, Library, Metadata, Open Data

## Surfaces the institution operates

- **Ocasys Course Catalog API** (`x-operator: institution`) — the JSON backend behind the
  University's own course and degree-programme catalog. Keyless course search, full course records,
  programme search, faculties and option lists, verified live 2026-08-30; RFC 9457 problem details
  on error; enrollment and course-offering paths gated at 403 behind institutional SSO. Undocumented
  by the University and, before this run, uncatalogued anywhere. Endpoint: https://ocasys.rug.nl/api
- **UG Research Database OAI-PMH** (`x-operator: institution`) — keyless OAI-PMH 2.0 over 1,521,703
  identifiers, six metadata profiles including OpenAIRE CERIF 1.2 with resolvable ORCID iDs.
  Endpoint: https://pure.rug.nl/ws/oai
- **Identity Provider (SURFconext / eduGAIN)** (`x-operator: institution`) — the University's own
  SAML 2.0 federation metadata, registered in eduGAIN via SURFconext.
  Endpoint: https://signon.rug.nl/nidp/saml2/metadata

Both OpenAPIs in this repository are **derived by API Evangelist from live probes**. The University
publishes neither.

## Tenant relationships (their data, someone else's contract)

- **Research Portal (Pure) REST API** — Elsevier's contract on the University's host; its
  documentation canonicalises to api.elsevierpure.com. https://pure.rug.nl/ws/api
- **Research data on DataverseNL** — a collection inside the shared national installation DANS and
  SURF run at dataverse.nl.
- **Library discovery (OCLC WorldCat)** — https://rug.on.worldcat.org/discovery

## Artifacts

- [openapi/](openapi/) — two derived contracts, with pristine copies in `openapi/_original/`
- [json-schema/](json-schema/), [json-ld/](json-ld/), [examples/](examples/), [rules/](rules/),
  [vocabulary/](vocabulary/) — all derived from the course-catalog probes
- [conformance/](conformance/) — education-regime standards: OAI-PMH, SAML, eduGAIN federation and
  ORCID met with evidence; SCIM, LTI, OneRoster, Ed-Fi, Caliper, QTI, DataCite and Crossref recorded
  as not observed, with reasons
- [errors/](errors/) — error behaviour captured live, including OAI-PMH's 200-with-an-error-body
- [authentication/](authentication/), [plans/](plans/), [rate-limits/](rate-limits/),
  [finops/](finops/), [security/](security/), [review.yml](review.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-30

## Common Properties

- Website: https://www.rug.nl/
- Course catalog: https://ocasys.rug.nl/
- Identity federation: https://signon.rug.nl/nidp/saml2/metadata
- Research portal: https://research.rug.nl/
- Research computing (Hábrók): https://www.rug.nl/society-business/center-for-information-technology/research/services/hpc/habrok
- AI policy: https://www.rug.nl/cit/services/ai-office/beleid-en-regelgeving/
- AI tooling: https://www.rug.nl/cit/services/ai-office/ai-oplossingen/
- GitHub: https://github.com/rijksuniversiteit-groningen
- LinkedIn: https://www.linkedin.com/school/rijksuniversiteit-groningen/
- Twitter/X: https://twitter.com/univgroningen

## Notes

- `api.rug.nl`, `data.rug.nl`, `developer.rug.nl` and `status.rug.nl` do not resolve. There is no
  developer portal, no key issuance, no status page and no published versioning or deprecation
  policy. That absence is a measurement, not an omission in this profile.
- The University's institutional AI posture is published only in Dutch, on the CIT AI Office pages.
- Its GitHub organization is mostly forks of upstream tooling (iBridges, python-irodsclient, davrods,
  an LTI 1.3 library); the 2026-06 profile credited one of those forks to the University as an API.
- A correct re-profile of a vendor-attributed institution lowers its score. That is the pipeline
  working.

## Maintainers

- Kin Lane — kin@apievangelist.com
