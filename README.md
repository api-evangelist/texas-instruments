# Texas Instruments (texas-instruments)

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

Texas Instruments is an American technology company that designs and manufactures semiconductors and various integrated circuits for industrial, automotive, personal electronics, communications equipment, and enterprise systems markets. TI provides a developer API portal at api-portal.ti.com offering Store APIs for inventory, ordering, and shipment tracking, as well as Product Information APIs for accessing parametric data, quality, and reliability information on TI's extensive semiconductor catalog.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/texas-instruments/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/texas-instruments/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Electronics
- Ordering
- Semiconductors
- Supply Chain

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-19

## APIs

### Texas Instruments Store API

The TI Store API enables enterprise customers to integrate with TI's ordering platform. It provides real-time inventory and pricing data, order creation and retrieval, advanced ship notice (ASN) tracking, and financial document retrieval. OAuth 2.0 client credentials authentication against transact.ti.com. Production base URL: https://transact.ti.com/v2/store

- **Human URL:** [https://www.ti.com/developer-api/store-api/getting-started.html](https://www.ti.com/developer-api/store-api/getting-started.html)
- **Base URL:** `https://transact.ti.com/v2/store`

#### Tags

- Inventory
- Ordering
- Semiconductors
- Supply Chain

#### Properties

- [Documentation](https://www.ti.com/developer-api/store-api/getting-started.html)
- [OpenAPI](openapi/texas-instruments-store-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/texas-instruments-store.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/texas-instruments-store.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Portal](https://api-portal.ti.com/)

### Texas Instruments Product Information API

The TI Product Information API suite provides access to TI's semiconductor product catalog including parametric data, quality and reliability information. Available as standard (multiple calls, 3,000/day limit) and orchestrated (single call, 1,500/day limit) variants. Base URL: https://transact.ti.com/v1

- **Human URL:** [https://www.ti.com/developer-api/product-information-api-suite/getting-started.html](https://www.ti.com/developer-api/product-information-api-suite/getting-started.html)
- **Base URL:** `https://transact.ti.com/v1`

#### Tags

- Electronics
- Product Data
- Semiconductors

#### Properties

- [Documentation](https://www.ti.com/developer-api/product-information-api-suite/getting-started.html)
- [OpenAPI](openapi/texas-instruments-product-information-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/texas-instruments-product-information.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/texas-instruments-product-information.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Portal](https://api-portal.ti.com/)

## Common Properties

- [GitHub Organization](https://github.com/TexasInstruments)
- [LinkedIn](https://www.linkedin.com/company/texas-instruments)
- [Website](https://www.texas-instruments.com)
- [Developer  Portal](https://api-portal.ti.com/)
- [Documentation](https://www.ti.com/developer-api/overview.html)
- [Getting Started](https://api-portal.ti.com/store-api-getstarted)
- [Support](https://api-portal.ti.com/support)
- [F A Q](https://api-portal.ti.com/faq)
- [OpenAPI](openapi/texas-instruments-store-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/texas-instruments-product-information-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/ti-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/texas-instruments-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/texas-instruments-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
