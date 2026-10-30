# Instabug (Luciq)

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

Instabug — now rebranded as Luciq — is an agentic mobile observability platform covering bug reporting, crash reporting, application performance monitoring, session replay, surveys, feature flags, rollout management, and AI agents (Detect, Resolve, Release). Public agent-facing surface is the Luciq MCP Server at api.luciq.ai/api/mcp; data export, webhooks, and per-platform SDKs (iOS, Android, React Native, Flutter, KMP) round out the API footprint.

**Areas:** AI Agents · APM · Application Performance Monitoring · Bug Reporting · Crash Reporting · MCP · Mobile · Mobile Observability · Observability · Session Replay

## Instabug (Luciq) on APIs.io

Everything profiled for Instabug (Luciq) is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/instabug/](https://apis.io/providers/instabug/)** — or go straight to one of the APIs or properties below.

### APIs (13)

- [Luciq App Health Metrics Export API](https://apis.io/apis/instabug/export-api/) — Enterprise-only REST API for exporting App Health metrics (crash-free sessions, cold/hot app launches, OOMs, ANRs) for ingest into Grafana, Datadog, or…
- [Luciq Webhooks](https://apis.io/apis/instabug/webhooks/) — Outbound HTTP POST webhooks deliver Bugs, Crashes, and APM events to a customer-configured callback URL. Requests are signed with HMAC-SHA256 using a…
- [Luciq iOS SDK (formerly Instabug-iOS)](https://apis.io/apis/instabug/ios-sdk/) — Native iOS SDK distributed via CocoaPods and Swift Package Manager covering bug reporting, crash reporting, APM (app launch, network, screen rendering,…
- [Luciq Android SDK (formerly Instabug-Android)](https://apis.io/apis/instabug/android-sdk/) — Native Android SDK covering bug reporting, crash reporting (including ANR capture and deobfuscation), APM (app launch, network, screen rendering, screen…
- [Luciq React Native SDK (formerly Instabug-React-Native)](https://apis.io/apis/instabug/react-native-sdk/) — React Native plugin wrapping the native iOS and Android Luciq SDKs. Adds Expo integration, CodePush / Over-The-Air update support, plus bug reporting, crash…
- [Luciq Flutter SDK (formerly Instabug-Flutter)](https://apis.io/apis/instabug/flutter-sdk/) — Flutter plugin wrapping the native iOS and Android Luciq SDKs to deliver bug reporting, crash reporting (with crash-free sessions), APM (app launch,…
- [Luciq Kotlin Multiplatform SDK](https://apis.io/apis/instabug/kmp-sdk/) — Kotlin Multiplatform SDK that ships the Luciq mobile observability surface (bug reporting, crash reporting, APM with Ktor network logging, session replay,…
- [Instabug (Luciq) App Hangs API](https://apis.io/apis/instabug/instabug-app-hangs-api/) — Inspect grouped UI freeze (hang) events for a Luciq application, filterable by date, status, app version, device, OS, and current view.
- [Instabug (Luciq) Applications API](https://apis.io/apis/instabug/instabug-applications-api/) — Enumerate the mobile applications accessible to the authenticated account. Applications are the root scoping primitive for every other MCP tool in this surface.
- [Instabug (Luciq) Bugs API](https://apis.io/apis/instabug/instabug-bugs-api/) — Read user-reported bugs submitted via the Luciq SDK report flow, filterable by status, priority, and app version, with full detail including logs, user…
- [Instabug (Luciq) Crashes API](https://apis.io/apis/instabug/instabug-crashes-api/) — Inspect grouped crashes for a Luciq application, including occurrence frequency, affected users, root cause hints, and aggregation patterns by device, OS,…
- [Instabug (Luciq) Occurrences API](https://apis.io/apis/instabug/instabug-occurrences-api/) — Drill down from a crash group into individual occurrence ULIDs and the full per-occurrence context: device, OS, memory, storage, app status, user identity,…
- [Instabug (Luciq) Reviews API](https://apis.io/apis/instabug/instabug-reviews-api/) — Read app store, native-prompt, and custom-prompt reviews captured through the Luciq SDK, with filters for rating, version, country, device, prompt type, and OS.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Luciq Webhook Events](https://apis.io/asyncapis/instabug/instabug-webhooks-asyncapi/)

#### Event channels (1)

Individual events and webhooks the provider emits.

- [/webhook](https://apis.io/channels/instabug/webhook/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Instabug Agentic Access](https://apis.io/agentic-access/instabug/instabug-agentic-access/)

#### JSON Schema (7)

The data models the API reads and writes.

- [Luciq App Hang](https://apis.io/schemas/instabug/instabug-app-hang/)
- [Luciq Application](https://apis.io/schemas/instabug/instabug-application/)
- [Luciq Bug Report](https://apis.io/schemas/instabug/instabug-bug/)
- [Luciq Crash](https://apis.io/schemas/instabug/instabug-crash/)
- [Luciq Crash Occurrence](https://apis.io/schemas/instabug/instabug-occurrence/)
- [Luciq App Review](https://apis.io/schemas/instabug/instabug-review/)
- [Luciq Webhook Payload](https://apis.io/schemas/instabug/instabug-webhook-payload/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Instabug Structure](https://apis.io/json-structure/instabug/instabug-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Instabug Context](https://apis.io/jsonld/instabug/instabug-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Luciq (Instabug) Domain Vocabulary](https://apis.io/vocabularies/instabug/instabug-vocabulary/)

#### Examples (6)

Example requests and responses.

- [Instabug Get Occurrence Details Example](https://apis.io/examples/instabug/instabug-get-occurrence-details-example/)
- [Instabug List Applications Example](https://apis.io/examples/instabug/instabug-list-applications-example/)
- [Instabug List Bugs Example](https://apis.io/examples/instabug/instabug-list-bugs-example/)
- [Instabug List Crashes Example](https://apis.io/examples/instabug/instabug-list-crashes-example/)
- [Instabug List Reviews Example](https://apis.io/examples/instabug/instabug-list-reviews-example/)
- [Instabug Webhook Crash Example](https://apis.io/examples/instabug/instabug-webhook-crash-example/)

#### Collections (6)

Postman and Open Collection request collections.

- [Luciq MCP Server App Hangs API](https://apis.io/collections/instabug/open-instabug-app-hangs-api/)
- [Luciq MCP Server App Hangs Applications API](https://apis.io/collections/instabug/open-instabug-applications-api/)
- [Luciq MCP Server App Hangs Bugs API](https://apis.io/collections/instabug/open-instabug-bugs-api/)
- [Luciq MCP Server App Hangs Crashes API](https://apis.io/collections/instabug/open-instabug-crashes-api/)
- [Luciq MCP Server](https://apis.io/collections/instabug/open-instabug-mcp-server/)
- [Luciq MCP Server App Hangs Occurrences API](https://apis.io/collections/instabug/open-instabug-occurrences-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Instabug (Luciq) — asyncapi rules](https://apis.io/rules/instabug/instabug-asyncapi-spectral-rules/)
- [Instabug (Luciq) — jsonschema rules](https://apis.io/rules/instabug/instabug-jsonschema-spectral-rules/)
- [Instabug (Luciq) API Rules](https://apis.io/rules/instabug/instabug-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Instabug Authentication](https://apis.io/security/instabug/instabug-authentication/)
- [Instabug Domain Security](https://apis.io/security/instabug/instabug-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Instabug Scopes](https://apis.io/scopes/instabug/instabug-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Instabug Plans Pricing](https://apis.io/plans/instabug/instabug-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Instabug Rate Limits](https://apis.io/rate-limits/instabug/instabug-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Instabug Finops](https://apis.io/finops/instabug/instabug-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.luciq.ai/)
- [Documentation](https://docs.luciq.ai/)
- [Pricing](https://luciq.ai/pricing)
- [Changelog](https://docs.luciq.ai/changelog/readme)
- [Blog](https://luciq.ai/blog)
- [GitHub](https://github.com/Instabug)

## API Evangelist rating

**Kin Score 42.9** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 51.8 |
| Contract quality | 56.4 |
| Contract governance | 27.3 |
| Operational transparency | 26.3 |
| Developer ergonomics | 51.2 |
| Access clarity | 25.0 |

**Agent readiness 29.6** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | derived (partial credit) |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 26.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/instabug/](https://apis.io/providers/instabug/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Instabug (Luciq): the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/instabug/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
