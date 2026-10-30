# Exabeam

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

Exabeam is a cybersecurity company that delivers faster, more accurate threat detection, investigation, and response (TDIR) through its AI-driven security operations platform. The platform combines cloud-native SIEM (security information and event management), user and entity behavioral analytics (UEBA), log management and collection, correlation and detection rules, and automated investigation workflows so security operations center (SOC) teams can monitor, triage, and respond to threats at scale. Exabeam exposes a REST API surface through its developer hub (developers.exabeam.com, hosted on ReadMe) covering access control, audit, authentication, cloud and site log collectors, context management, correlation rules, detection management, MITRE ATT&CK mappings, search, service health and consumption, threat center, and use cases. APIs are served from eight regional gateway hosts on the exabeam.cloud domain and secured with OAuth2 (API key and secret issued in the console). Exabeam also publishes an MCP server for agent-based access.

**Areas:** Company · Cybersecurity · Security · SIEM · UEBA · Threat Detection · Security Operations · SOC · Log Management · Incident Response

## Exabeam on APIs.io

Everything profiled for Exabeam is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/exabeam/](https://apis.io/providers/exabeam/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [Exabeam Access Control API](https://apis.io/apis/exabeam/exabeam-access-control-api/) — Manage users, roles, and permissions within the Exabeam platform.
- [Exabeam Audit API](https://apis.io/apis/exabeam/exabeam-audit-api/) — Retrieve audit-trail and activity-log records from the platform.
- [Exabeam Authentication API](https://apis.io/apis/exabeam/exabeam-authentication-api/) — OAuth2 token issuance and API key / secret authentication for the Exabeam API surface.
- [Exabeam Cloud Collectors API](https://apis.io/apis/exabeam/exabeam-cloud-collectors-api/) — Configure and manage cloud-based log collectors.
- [Exabeam Context Management API](https://apis.io/apis/exabeam/exabeam-context-management-api/) — Manage context tables and enrichment data used for detection and investigation.
- [Exabeam Correlation Rules API](https://apis.io/apis/exabeam/exabeam-correlation-rules-api/) — Create and manage correlation rules for threat detection.
- [Exabeam Detection Management API](https://apis.io/apis/exabeam/exabeam-detection-management-api/) — Manage detection rules and security content.
- [Exabeam MITRE ATT&CK API](https://apis.io/apis/exabeam/exabeam-mitre-attck-api/) — Access MITRE ATT&CK technique and tactic mappings within the platform.
- [Exabeam Search API](https://apis.io/apis/exabeam/exabeam-search-api/) — Search ingested log and event data across the platform.
- [Exabeam Service Health and Consumption API](https://apis.io/apis/exabeam/exabeam-service-health-and-consumption-api/) — Retrieve service-health status and data-consumption metrics.
- [Exabeam Site Collectors API](https://apis.io/apis/exabeam/exabeam-site-collectors-api/) — Configure and manage on-premises / site log collectors.
- [Exabeam Threat Center API](https://apis.io/apis/exabeam/exabeam-threat-center-api/) — Manage cases, alerts, and investigations in Exabeam Threat Center.
- [Exabeam Use Cases API](https://apis.io/apis/exabeam/exabeam-use-cases-api/) — Manage security use cases and their associated detection content.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [exabeam](https://apis.io/servers/exabeam/exabeam/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Exabeam Authentication](https://apis.io/security/exabeam/exabeam-authentication/)
- [Exabeam Domain Security](https://apis.io/security/exabeam/exabeam-domain-security/)
- [Exabeam Trust Center](https://apis.io/security/exabeam/exabeam-trust-center/)
- [Exabeam Vulnerability Disclosure](https://apis.io/security/exabeam/exabeam-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Exabeam Scopes](https://apis.io/scopes/exabeam/exabeam-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://exabeam.com)
- [Documentation](https://developers.exabeam.com/exabeam/docs)
- [Getting started](https://developers.exabeam.com/exabeam/docs/api-keys)
- [API reference](https://developers.exabeam.com/exabeam/reference)
- [Support](https://mycommunity.exabeam.com/category/forums)
- [Changelog](https://developers.exabeam.com/changelog)
- [Blog](https://www.exabeam.com/blog/)
- [Security](https://www.exabeam.com/responsible-disclosure/)
- [Compliance](https://exabeam.securitypal.com/)
- [Trust centre](https://exabeam.securitypal.com/)
- [Terms of service](https://www.exabeam.com/legal/terms-and-conditions/)
- [Privacy policy](https://www.exabeam.com/legal/privacy-policy/)
- [GitHub](https://github.com/Exabeam)
- [Status](https://exabeam.statuspage.io/)

## API Evangelist rating

**Kin Score 34.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 76.7 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 36.8 |
| Developer ergonomics | 32.1 |
| Access clarity | 43.4 |

**Agent readiness 14.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 45.1** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/exabeam/](https://apis.io/providers/exabeam/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Exabeam: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/exabeam/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
