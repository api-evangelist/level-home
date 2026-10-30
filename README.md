# Level Home

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

Level Home is the Redwood City, California maker of the "invisible" Level smart lock family — Level Lock, Level Lock Pro, Level Bolt and Level Keypad — which hide the motor, radios and battery inside a standard-looking deadbolt. The locks speak Bluetooth LE, Thread and Matter, and work with Apple Home (including Apple Home Key), Google Home, Amazon Alexa and SmartThings rather than through a published third-party developer API. In September 2024 ASSA ABLOY acquired the Level Lock hardware business, brand and IP, which continues to operate as Level at level.co; the remaining Level Home, Inc. entity — the Level M multifamily software business, which also absorbed Dwelo — renamed itself Ambient Property Technologies and now sells smart access, apartment automation and building intelligence to multifamily owners with integrations into RealPage, Yardi, Entrata, ResMan and ButterflyMX. Level publishes no developer portal, no OpenAPI and no partner API documentation; the only publicly reachable machine-readable contracts are the Craft CMS GraphQL content endpoint behind level.co/api and the mobile application backend at api.level.co, which is undocumented and account-gated. Third-party developer access to Level devices is brokered by Seam, and local control is available through Matter/Thread.

**Areas:** Smart Lock · Smart Home · Home Automation · IoT · Access Control · Matter · Threads · Bluetooth LE · apple-home-key · Consumer Hardware · Multifamily · PropTech

## Level Home on APIs.io

Everything profiled for Level Home is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/level-home/](https://apis.io/providers/level-home/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [Level Website Content GraphQL API](https://apis.io/apis/level-home/level-website-content-graphql-api/) — Publicly reachable GraphQL endpoint served by the Craft CMS instance behind level.co. Introspection is enabled anonymously, but the published public schema…
- [Level Mobile Application Backend](https://apis.io/apis/level-home/level-mobile-application-backend/) — The undocumented HTTPS backend the Level Home iOS and Android applications talk to. It is an AWS API Gateway fronted service that returns a `{"message":…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Level Home Authentication](https://apis.io/security/level-home/level-home-authentication/)
- [Level Home Domain Security](https://apis.io/security/level-home/level-home-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://level.co/)
- [Documentation](https://level.co/support/)
- [Pricing](https://level.co/all-products/)
- [Sign up](https://level.co/account/)
- [Support](https://level.co/support/)
- [Blog](https://level.co/stories/)
- [Terms of service](https://level.co/terms-of-service/)
- [Privacy policy](https://www.privacy.assaabloydss.com/en)
- [GitHub](https://github.com/LevelHome)

## API Evangelist rating

**Kin Score 29.9** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 74.1 |
| Contract quality | 35.1 |
| Contract governance | 4.5 |
| Operational transparency | 2.6 |
| Developer ergonomics | 16.7 |
| Access clarity | 44.7 |

**Agent readiness 15.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
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

**Regulatory alignment 18.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/level-home/](https://apis.io/providers/level-home/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Level Home: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/level-home/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
