# Instabug / Luciq (instabug)

Instabug — rebranded as **Luciq** in 2025 — is the agentic mobile observability platform covering bug reporting, crash reporting, application performance monitoring, session replay, in-app surveys, feature flags, rollout management, and AI agents (Detect, Resolve, Release). The public agent-facing surface is the Luciq MCP Server at `api.luciq.ai/api/mcp`; data export, outbound webhooks, and per-platform SDKs (iOS, Android, React Native, Flutter, Kotlin Multiplatform) round out the API footprint.

> Quote: *"Luciq is the agentic observability platform built for mobile. Powered by intelligent agents that detect, diagnose, and resolve issues, before users feel them, so your team can ship confidently and your app just works."* — https://luciq.ai/platform

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/instabug/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Brand Note

In 2025 Instabug rebranded to Luciq. `instabug.com` 301-redirects to `luciq.ai`; `docs.instabug.com` redirects to `docs.luciq.ai`. The GitHub organization remains at [github.com/Instabug](https://github.com/Instabug) (44 public repos). This `instabug` repo retains the legacy provider ID for continuity in the API Evangelist network; all artifacts cite the current Luciq documentation.

## Tags

Agentic AI, APM, Application Performance Monitoring, Bug Reporting, Crash Reporting, MCP, Mobile, Mobile Observability, Observability, Session Replay

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Luciq MCP Server
Remote Model Context Protocol server at `api.luciq.ai/api/mcp` exposing mobile observability data (applications, crashes, crash patterns, occurrences, app hangs, bugs, reviews) as 10 agent-callable tools. Transport: Streamable HTTP over HTTPS (TLS 1.2+). Auth: OAuth 2.0 with Dynamic Client Registration or personal access tokens. Available on all Luciq plans, no extra setup.

**Human URL:** https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features/luciq-mcp-server

**Tags:** Agentic AI, Crashes, MCP, Mobile Observability

**Properties:**
- [Documentation](https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features/luciq-mcp-server)
- [Getting Started](https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features/luciq-mcp-server/getting-started)
- [Authentication & Security](https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features/luciq-mcp-server/authentication-and-security)
- [MCP Tools Reference](https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features/luciq-mcp-server/mcp-tools-reference)
- [OpenAPI](openapi/instabug-mcp-server-openapi.yml)
- [Naftiko Capability — Applications](capabilities/mcp-applications.yaml)
- [Naftiko Capability — Crashes](capabilities/mcp-crashes.yaml)
- [Naftiko Capability — Occurrences](capabilities/mcp-occurrences.yaml)
- [Naftiko Capability — App Hangs](capabilities/mcp-app-hangs.yaml)
- [Naftiko Capability — Bugs](capabilities/mcp-bugs.yaml)
- [Naftiko Capability — Reviews](capabilities/mcp-reviews.yaml)

### Luciq App Health Metrics Export API
Enterprise-only REST API for exporting App Health metrics (crash-free sessions, cold/hot app launches, OOMs, ANRs) for ingest into Grafana, Datadog, or internal dashboards. Authentication and endpoint paths are gated; access provisioned by a Luciq CSM. **No public OpenAPI is published** — listed here for inventory completeness.

**Human URL:** https://docs.luciq.ai/product-guides-and-integrations/product-guides/export-apis

**Tags:** App Health, Crash-Free Sessions, Data Export, Enterprise, Metrics

### Luciq Webhooks
Outbound HTTP POST webhooks deliver Bugs, Crashes, and APM events to a customer-configured callback URL. Requests are signed with HMAC-SHA256 (per-webhook secret, 16-64 char alphanumeric) and delivered with the `x-ibg-signature-256` header. Configurable per product from the Luciq dashboard.

**Human URL:** https://docs.luciq.ai/product-guides-and-integrations/integrations/webhook

**Tags:** APM Events, Bugs, Crashes, Event-Driven, Webhooks

**Properties:**
- [Documentation](https://docs.luciq.ai/product-guides-and-integrations/integrations/webhook)
- [AsyncAPI](asyncapi/instabug-webhooks-asyncapi.yml)

### Luciq iOS SDK (formerly Instabug-iOS)
Native iOS SDK via CocoaPods/SPM covering bug reporting, crash reporting, APM, session replay, surveys, replies, feature requests, app ratings; UIKit and SwiftUI (with automatic SwiftUI screen-loading instrumentation).

**Repo:** https://github.com/Instabug/Instabug-iOS

### Luciq Android SDK (formerly Instabug-Android)
Native Android SDK with ANR capture, deobfuscation, full APM (app launch, network, screen rendering, screen loading, execution traces, flows, custom spans), Jetpack Compose integration, push notifications.

**Repo:** https://github.com/Instabug/Instabug-Android

### Luciq React Native SDK (formerly Instabug-React-Native)
React Native plugin wrapping the native iOS/Android SDKs; Expo support; CodePush / Over-The-Air update integration.

**Repo:** https://github.com/Instabug/Instabug-React-Native

### Luciq Flutter SDK (formerly Instabug-Flutter)
Flutter plugin wrapping the native iOS/Android SDKs; crash-free sessions, APM (with UI hangs and flows), session replay, surveys, in-app replies.

**Repo:** https://github.com/Instabug/Instabug-Flutter

### Luciq Kotlin Multiplatform SDK
KMP SDK shipping the Luciq mobile observability surface across iOS and Android targets from shared Kotlin, with Ktor network logging.

**Docs:** https://docs.luciq.ai/kmp

## Generated Artifacts

| Type | Count | Folder |
|---|---|---|
| OpenAPI specs | 1 | `openapi/` |
| AsyncAPI specs | 1 | `asyncapi/` |
| Naftiko capabilities | 6 | `capabilities/` |
| JSON Schemas | 7 | `json-schema/` |
| JSON Structure | 1 | `json-structure/` |
| JSON-LD context | 1 | `json-ld/` |
| Example payloads | 6 | `examples/` |
| Spectral rules | 1 | `rules/` |
| Vocabulary | 1 | `vocabulary/` |
| Plans (API Commons) | 1 | `plans/` |
| Rate Limits (API Commons) | 1 | `rate-limits/` |
| FinOps (FOCUS) | 1 | `finops/` |

## Common Resources

- **Portal:** https://luciq.ai
- **Login:** https://dashboard.luciq.ai/login
- **Docs:** https://docs.luciq.ai/
- **Help Center:** https://help.luciq.ai/
- **Pricing:** https://luciq.ai/pricing
- **Integrations:** https://luciq.ai/integrations
- **Migration Hub:** https://docs.luciq.ai/getting-started/luciq-migration-hub
- **Changelog:** https://docs.luciq.ai/changelog/readme
- **Blog:** https://luciq.ai/blog
- **GitHub Organization:** https://github.com/Instabug
- **LLMs Full Text:** https://docs.luciq.ai/llms-full.txt
- **Sitemap:** https://docs.luciq.ai/sitemap.md

## Pricing Model (Verbatim)

> *"Priced on DAU and Seats. No hidden fees. No surprise overages."* — https://luciq.ai/pricing

- Daily Active Users (DAU) + member Seats are the only pricing dimensions.
- Per-DAU entitlement: 180 sessions/month.
- Plans surfaced: **Standard** (annual commitment), **Enterprise** (fully customized), **Enterprise Premier** (24/7 + dedicated Slack).
- 100 Observer seats included on Enterprise; more on request.
- Retention: Crash 180d, Bug 365d, APM 8 weeks, Session Replay 4 weeks, Surveys 365d.
- Security: SOC 2 Type II, SAML/OAuth SSO, SCIM provisioning, RBAC, regional data pinning.

## Customers Cited on luciq.ai

Figma · Lyft · DoorDash · Disney · General Motors · AB InBev · Decathlon · Dabble · Saturn · Included

## Notable Findings

- **Rebrand:** Instabug → Luciq in 2025. All `instabug.com` and `docs.instabug.com` URLs 301-redirect.
- **MCP-first agent surface:** 10 tools across applications, crashes, crash patterns, occurrences, app hangs, bugs, reviews. OAuth 2.0 Dynamic Client Registration or PAT.
- **No public REST API reference:** the historical Instabug REST API is being deprecated; the App Health Metrics Export API is Enterprise-gated.
- **AI features:** Detect Agent, Resolve Agent, Release Agent, AI Debugging Assistant, SmartResolve, Agent Skills (`luciq-debug`, `luciq-setup`, `luciq-migrate`).
- **GitHub:** 44 public repos, 5 active mobile SDKs (iOS, Android, React Native, Flutter, KMP) plus archived Cordova.

## Notable Absences

- No public OpenAPI for the Enterprise App Health Metrics Export API (gated; CSM-provisioned).
- No public RSS/Atom feed surfaced on the blog or changelog (sitemap available).
- No public dollar-amount pricing on the pricing page (book-a-demo / contact-sales flow).
- `status.luciq.ai` returns ECONNREFUSED — no discoverable status page.
- No Kubernetes CRDs (mobile observability provider, not infrastructure).
