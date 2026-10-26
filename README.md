# The Administration for Children and Families (the-administration-for-children-and-families)

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

The Administration for Children and Families (ACF) is a division of the U.S. Department of Health and Human Services dedicated to promoting the economic and social well-being of children, families, and communities. ACF administers programs including TANF (cash assistance), CCDF (child care), Head Start, LIHEAP (energy assistance), child welfare, and refugee assistance. ACF collects administrative data via systems including AFCARS (foster care and adoption), NCANDS (child abuse and neglect), NYTD (youth in transition), TANF data reporting, and CCDF data. ACF is pursuing interoperability standards using HL7 FHIR and USCDI+ for human services data exchange. The TANF Data Portal (tanfdata.acf.hhs.gov) provides state agencies with a data submission and analysis interface.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/the-administration-for-children-and-families/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/the-administration-for-children-and-families/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Children
- Families
- Federal Government
- Health And Human Services
- Human Services
- Social Safety Net

## Timestamps

- **Created:** 2024-11-20T00:00:00.000Z
- **Modified:** 2026-05-03

## APIs

### TANF Data Portal

The TANF Data Portal (TDP) is a secure, web-based data reporting system for state agencies to submit Temporary Assistance for Needy Families (TANF) program data to ACF. It provides data submission workflows, validation, and reporting capabilities. The system is built on a Django/React stack hosted on Cloud.gov.

- **Human URL:** [https://tanfdata.acf.hhs.gov/](https://tanfdata.acf.hhs.gov/)
- **Base URL:** `https://tanfdata.acf.hhs.gov/`

#### Tags

- Federal Government
- Human Services
- TANF

#### Properties

- [Documentation](https://tanfdata.acf.hhs.gov/)
- [GitHub Repository](https://github.com/HHS/TANF-app)
- [Postman Collection](collections/the-administration-for-children-and-families.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/the-administration-for-children-and-families.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)


#### Tags

- FHIR
- Federal Government
- Human Services
- Interoperability

#### Properties

- [Documentation](https://acf.gov/about/interoperability)
- [Postman Collection](collections/the-administration-for-children-and-families.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/the-administration-for-children-and-families.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### National Data Archive on Child Abuse and Neglect

NDACAN is the central repository for datasets related to child abuse, neglect, and child welfare at Cornell University, funded by ACF. Provides access to AFCARS (foster care/adoption), NCANDS (child abuse and neglect), and NYTD (youth in transition) datasets for research purposes. Includes data codebooks and user guides.

- **Human URL:** [https://www.ndacan.acf.hhs.gov/](https://www.ndacan.acf.hhs.gov/)
- **Base URL:** `https://www.ndacan.acf.hhs.gov/`

#### Tags

- Child Welfare
- Data Archive
- Federal Government
- Research

#### Properties

- [Documentation](https://www.ndacan.acf.hhs.gov/)
- [Postman Collection](collections/the-administration-for-children-and-families.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/the-administration-for-children-and-families.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ACF Data and Research Portal

ACF's primary data and research portal providing access to program data, statistical reports, and research findings across all ACF program offices. Includes TANF caseload data, CCDF data, Head Start program data, and child welfare statistics.

- **Human URL:** [https://acf.gov/acf-data-research](https://acf.gov/acf-data-research)
- **Base URL:** `https://acf.gov/`

#### Tags

- Data
- Federal Government
- Research
- Statistics

#### Properties

- [Documentation](https://acf.gov/acf-data-research)
- [Dataset](https://catalog.data.gov/organization/hhs-acf)
- [Postman Collection](collections/the-administration-for-children-and-families.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/the-administration-for-children-and-families.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/administration-for-children-and-families)
- [Website](https://www.acf.hhs.gov/)
- [Documentation](https://acf.gov/acf-data-research)
- [Data  Portal](https://tanfdata.acf.hhs.gov/)
- [GitHub Organization](https://github.com/HHS)
- [Data  Catalog](https://catalog.data.gov/organization/hhs-acf)
- [Interoperability](https://acf.gov/about/interoperability)
- [JSON Schema](json-schema/acf-child-welfare-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/acf-tanf-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/acf-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/acf-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
