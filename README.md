# Overture Maps Foundation

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

Overture Maps Foundation is a Linux Foundation collaborative project that produces free, open, and interoperable map data. Overture publishes cloud-native GeoParquet datasets, on a regular release cadence, across six themes - Addresses, Base, Buildings, Divisions, Places, and Transportation - governed by a common conflation pipeline and an open schema. Rather than a hosted REST API, Overture distributes data through Amazon S3 and Microsoft Azure (and via partner mirrors on BigQuery, Snowflake, Databricks, Fused, Wherobots), and provides an open Python CLI, a tile generator, and an Explorer site for developers. Founding members include Amazon, Meta, Microsoft, and TomTom.

**Areas:** Maps · Geospatial · Open Data · GeoParquet · Open Source · Linux Foundation

## Overture Maps Foundation on APIs.io

Everything profiled for Overture Maps Foundation is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/overture-maps/](https://apis.io/providers/overture-maps/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [Overture Addresses Theme](https://apis.io/apis/overture-maps/addresses/) — Open dataset of global address points and ranges, released as cloud-native GeoParquet alongside the other Overture themes.
- [Overture Base Theme](https://apis.io/apis/overture-maps/base/) — Open dataset of base map features - land cover, water, land use, infra - released as cloud-native GeoParquet to serve as a foundation for map rendering.
- [Overture Buildings Theme](https://apis.io/apis/overture-maps/buildings/) — Open dataset of global building footprints with attributes (heights, classes, sources), released as cloud-native GeoParquet.
- [Overture Divisions Theme](https://apis.io/apis/overture-maps/divisions/) — Open dataset of administrative and statistical boundaries (countries, regions, counties, localities, neighborhoods) released as cloud-native GeoParquet.
- [Overture Places Theme](https://apis.io/apis/overture-maps/places/) — Open dataset of global points of interest - businesses, landmarks, and services - released as cloud-native GeoParquet with categories, addresses, and…
- [Overture Transportation Theme](https://apis.io/apis/overture-maps/transportation/) — Open dataset of the global road and transportation network (segments and connectors) released as cloud-native GeoParquet, suitable for routing and analytics.
- [Overture Schema](https://apis.io/apis/overture-maps/schema/) — Canonical open schema specification for all Overture themes, maintained in the OvertureMaps/schema GitHub repository and versioned with each data release.
- [Overture Data Releases](https://apis.io/apis/overture-maps/data/) — Repository of release notes, cloud paths (Amazon S3 and Microsoft Azure), and access scripts for every Overture data release. Datasets are distributed as…
- [Overture Maps Python CLI](https://apis.io/apis/overture-maps/cli/) — Open-source Python command-line tool and library for downloading and querying Overture data. Maintained at OvertureMaps/overturemaps-py.
- [Overture Explorer](https://apis.io/apis/overture-maps/explorer/) — Interactive web explorer for browsing and inspecting Overture features across themes and releases.
- [Overture Tiles](https://apis.io/apis/overture-maps/tiles/) — Open tile-generation tooling that builds vector tilesets from Overture data for rendering and downstream applications.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Overture Maps Domain Security](https://apis.io/security/overture-maps/overture-maps-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Overture Maps Plans Pricing](https://apis.io/plans/overture-maps/overture-maps-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Overture Maps Rate Limits](https://apis.io/rate-limits/overture-maps/overture-maps-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Overture Maps Finops](https://apis.io/finops/overture-maps/overture-maps-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://overturemaps.org/)
- [Documentation](https://docs.overturemaps.org/)
- [Blog](https://overturemaps.org/blog/)

## API Evangelist rating

**Kin Score 13.6** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 78.6 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 26.3 |
| Developer ergonomics | 11.9 |
| Access clarity | 5.3 |

**Agent readiness 0.6** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 5.9** — Government & Public Sector

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/overture-maps/](https://apis.io/providers/overture-maps/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Overture Maps Foundation: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/overture-maps/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
