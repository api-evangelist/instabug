# Instabug (Luciq) (instabug)

Instabug — now rebranded as Luciq — is an agentic mobile observability platform covering bug reporting, crash reporting, application performance monitoring, session replay, surveys, feature flags, rollout management, and AI agents (Detect, Resolve, Release). Public agent-facing surface is the Luciq MCP Server at api.luciq.ai/api/mcp; data export, webhooks, and per-platform SDKs (iOS, Android, React Native, Flutter, KMP) round out the API footprint.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/instabug/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/instabug/refs/heads/main/apis.yml)

## Tags

- Agentic AI
- APM
- Application Performance Monitoring
- Bug Reporting
- Crash Reporting
- MCP
- Mobile
- Mobile Observability
- Observability
- Session Replay

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Luciq MCP Server

The Luciq MCP Server is a remote Model Context Protocol server hosted at api.luciq.ai/api/mcp that exposes mobile observability data (applications, crashes, crash patterns, occurrences, app hangs, bugs, reviews) as agent-callable tools. It uses Streamable HTTP transport over HTTPS (TLS 1.2+), OAuth 2.0 with Dynamic Client Registration for IDE/agent auth, and supports personal access tokens for CI and automation. Available on all Luciq plans with no extra setup.

- **Human URL:** [https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features/luciq-mcp-server](https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features/luciq-mcp-server)
- **Base URL:** `https://api.luciq.ai/api/mcp`

#### Tags

- Agentic AI
- Crashes
- MCP
- Mobile Observability

#### Properties

- [Documentation](https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features/luciq-mcp-server)
- [Getting Started](https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features/luciq-mcp-server/getting-started)
- [Authentication](https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features/luciq-mcp-server/authentication-and-security)
- [Tools Reference](https://docs.luciq.ai/product-guides-and-integrations/product-guides/ai-features/luciq-mcp-server/mcp-tools-reference)
- [OpenAPI](openapi/instabug-mcp-server-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/instabug-mcp-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/instabug-mcp-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Luciq App Health Metrics Export API

Enterprise-only REST API for exporting App Health metrics (crash-free sessions, cold/hot app launches, OOMs, ANRs) for ingest into Grafana, Datadog, or internal dashboards. Authentication and endpoint paths are gated; access provisioned by a Luciq Customer Success Manager. Listed here for inventory completeness — no public OpenAPI is published.

- **Human URL:** [https://docs.luciq.ai/product-guides-and-integrations/product-guides/export-apis](https://docs.luciq.ai/product-guides-and-integrations/product-guides/export-apis)
- **Base URL:** `https://api.luciq.ai`

#### Tags

- App Health
- Crash-Free Sessions
- Data Export
- Enterprise
- Metrics

#### Properties

- [Documentation](https://docs.luciq.ai/product-guides-and-integrations/product-guides/export-apis)
- [Access Request](mailto:support@luciq.ai)
- [Postman Collection](collections/instabug-mcp-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/instabug-mcp-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Luciq Webhooks

Outbound HTTP POST webhooks deliver Bugs, Crashes, and APM events to a customer-configured callback URL. Requests are signed with HMAC-SHA256 using a per-webhook secret and delivered with the x-ibg-signature-256 header. Configurable per product (Bugs & Crashes or APM) and toggleable on demand from the Luciq dashboard.

- **Human URL:** [https://docs.luciq.ai/product-guides-and-integrations/integrations/webhook](https://docs.luciq.ai/product-guides-and-integrations/integrations/webhook)

#### Tags

- APM Events
- Bugs
- Crashes
- Event-Driven
- Webhooks

#### Properties

- [Documentation](https://docs.luciq.ai/product-guides-and-integrations/integrations/webhook)
- [AsyncAPI](asyncapi/instabug-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/instabug-mcp-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/instabug-mcp-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Luciq iOS SDK (formerly Instabug-iOS)

Native iOS SDK distributed via CocoaPods and Swift Package Manager covering bug reporting, crash reporting, APM (app launch, network, screen rendering, screen loading, flows), session replay, in-app surveys, in-app replies, feature requests, and app ratings. Supports both UIKit and SwiftUI (including automatic SwiftUI screen-loading instrumentation).

- **Human URL:** [https://docs.luciq.ai/ios](https://docs.luciq.ai/ios)

#### Tags

- iOS
- Mobile SDK
- Swift
- SwiftUI
- UIKit

#### Properties

- [Documentation](https://docs.luciq.ai/ios)
- [GitHub Repository](https://github.com/Instabug/Instabug-iOS)
- [Swift Package](https://github.com/Instabug/Instabug-SP)
- [Postman Collection](collections/instabug-mcp-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/instabug-mcp-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Luciq Android SDK (formerly Instabug-Android)

Native Android SDK covering bug reporting, crash reporting (including ANR capture and deobfuscation), APM (app launch, network, screen rendering, screen loading, execution traces, flows, custom spans), session replay, surveys, in-app replies, feature requests, push notifications, app ratings, and Jetpack Compose integration.

- **Human URL:** [https://docs.luciq.ai/android](https://docs.luciq.ai/android)

#### Tags

- Android
- Jetpack Compose
- Kotlin
- Mobile SDK

#### Properties

- [Documentation](https://docs.luciq.ai/android)
- [GitHub Repository](https://github.com/Instabug/Instabug-Android)
- [Postman Collection](collections/instabug-mcp-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/instabug-mcp-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Luciq React Native SDK (formerly Instabug-React-Native)

React Native plugin wrapping the native iOS and Android Luciq SDKs. Adds Expo integration, CodePush / Over-The-Air update support, plus bug reporting, crash reporting, APM, session replay, surveys, in-app replies, and app ratings on the React Native runtime.

- **Human URL:** [https://docs.luciq.ai/react-native](https://docs.luciq.ai/react-native)

#### Tags

- Expo
- JavaScript
- Mobile SDK
- React Native
- TypeScript

#### Properties

- [Documentation](https://docs.luciq.ai/react-native)
- [GitHub Repository](https://github.com/Instabug/Instabug-React-Native)
- [Postman Collection](collections/instabug-mcp-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/instabug-mcp-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Luciq Flutter SDK (formerly Instabug-Flutter)

Flutter plugin wrapping the native iOS and Android Luciq SDKs to deliver bug reporting, crash reporting (with crash-free sessions), APM (app launch, network, screen loading, UI hangs, flows, custom spans), session replay, in-app surveys, in-app replies, and app ratings inside Dart/Flutter apps.

- **Human URL:** [https://docs.luciq.ai/flutter](https://docs.luciq.ai/flutter)

#### Tags

- Dart
- Flutter
- Mobile SDK

#### Properties

- [Documentation](https://docs.luciq.ai/flutter)
- [GitHub Repository](https://github.com/Instabug/Instabug-Flutter)
- [Postman Collection](collections/instabug-mcp-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/instabug-mcp-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Luciq Kotlin Multiplatform SDK

Kotlin Multiplatform SDK that ships the Luciq mobile observability surface (bug reporting, crash reporting, APM with Ktor network logging, session replay, surveys, in-app replies, feature requests, custom spans, repro steps, session profiler) across iOS and Android targets from shared Kotlin code.

- **Human URL:** [https://docs.luciq.ai/kmp](https://docs.luciq.ai/kmp)

#### Tags

- iOS
- Kotlin
- Kotlin Multiplatform
- Ktor
- Mobile SDK

#### Properties

- [Documentation](https://docs.luciq.ai/kmp)
- [Postman Collection](collections/instabug-mcp-server.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/instabug-mcp-server.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://luciq.ai)
- [Login](https://dashboard.luciq.ai/login)
- [Documentation](https://docs.luciq.ai/)
- [Help Center](https://help.luciq.ai/)
- [Pricing](https://luciq.ai/pricing)
- [Integrations](https://luciq.ai/integrations)
- [Platforms](https://luciq.ai/platforms)
- [Migration Hub](https://docs.luciq.ai/getting-started/luciq-migration-hub)
- [Changelog](https://docs.luciq.ai/changelog/readme)
- [Blog](https://luciq.ai/blog)
- [GitHub Organization](https://github.com/Instabug)
- [LinkedIn](https://www.linkedin.com/company/instabug)
- [Twitter](https://twitter.com/Instabug)
- [Sitemap](https://docs.luciq.ai/sitemap.md)
- [L L Ms Full Text](https://docs.luciq.ai/llms-full.txt)
- [Security S O C2](https://luciq.ai/pricing)
- [Sub Processors](https://docs.luciq.ai/organization-settings/others/sub-processors)
- [G D P R](https://docs.luciq.ai/organization-settings/gdpr)
- [Audit Notes](https://docs.luciq.ai/organization-settings/audit-notes)
- [S S O](https://docs.luciq.ai/organization-settings/user-management/sso-using-saml)
- [S C I M](https://docs.luciq.ai/organization-settings/user-management/scim-provisioning)
- [Plans](plans/instabug-plans-pricing.yml)
- [Rate Limits](rate-limits/instabug-rate-limits.yml)
- [Fin Ops](finops/instabug-finops.yml)
- [JSON Schema](json-schema/instabug-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/instabug-crash-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/instabug-occurrence-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/instabug-bug-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/instabug-review-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/instabug-app-hang-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/instabug-webhook-payload-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/instabug-structure.json)
- [JSON-LD](json-ld/instabug-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/instabug-vocabulary.yml)
- [Spectral Rules](rules/instabug-rules.yml)
- [Branding](undefined)
- [Customers](undefined)
- [Features](undefined)
- [Integrations](undefined)
- [M C P Capability](undefined)
- [Git Hub Organization Profile](undefined)
- [Billing Model](undefined)
