# Mubert (mubert)

Mubert is a generative AI music platform that composes royalty-free, DMCA-free music in real time from millions of artist-contributed loops, samples, and stems. The B2B Mubert AI Music API (v3) powers track generation, continuous HTTP / WebRTC streaming, browse access to a pre-generated music library, and service-tier customer + license + Stripe subscription administration. Mubert is used by apps, games, video tools, health and fitness products, and AI-content pipelines (including integrations with Picsart, Canva, and Restream) to embed adaptive generative music inside their experiences.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mubert/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mubert/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- AI Music
- Generative
- Royalty-Free
- Streaming
- Text-to-Music
- Image-to-Music
- Stems
- B2B

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-25

## APIs

### Mubert AI Music API

Mubert AI Music API v3 — the unified B2B surface for generating royalty-free AI music tracks, streaming continuous generative music (HTTP / WebRTC), browsing the pre-generated music library and playlist taxonomy, and (service tier) administering customers, licenses, prices, and Stripe subscriptions. Authentication uses customer-id + access-token headers for public endpoints and company-id + license-token headers for service endpoints. Ships AI-optimized llms.txt / llms-full.txt docs alongside Swagger UI.

- **Human URL:** [https://mubert.com/api](https://mubert.com/api)
- **Base URL:** `https://music-api.mubert.com`

#### Tags

- AI Music
- Generation
- Streaming
- Library
- Customers
- Licenses
- Subscriptions

#### Properties

- [Documentation](https://mubert.com/api)
- [Swagger U I](https://music-api.mubert.com/api/v3/swagger)
- [OpenAPI](openapi/mubert-music-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mubert-music-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mubert-music-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [A I Documentation](https://music-api.mubert.com/swagger-doc/llms.txt)
- [A I Documentation](https://music-api.mubert.com/swagger-doc/llms-full.txt)
- [JSON Schema](json-schema/mubert-track-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/mubert-customer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/mubert-license-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/mubert-playlist-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/mubert-streaming-link-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/mubert-track-structure.json)
- [JSON Structure](json-structure/mubert-license-structure.json)
- [JSON-LD](json-ld/mubert-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/mubert-create-track-example.json)
- [Example](examples/mubert-edit-track-example.json)
- [Example](examples/mubert-get-streaming-link-example.json)
- [Example](examples/mubert-create-customer-example.json)
- [Vocabulary](vocabulary/mubert-vocabulary.yml)
- [Spectral Rules](rules/mubert-rules.yml)

## Common Properties

- [Website](https://mubert.com/)
- [Product Page](https://mubert.com/api)
- [Product Page](https://mubert.com/render)
- [Product Page](https://mubert.com/play)
- [Product Page](https://mubert.com/business)
- [Product Page](https://mubert.com/studio)
- [Documentation](https://mubert.com/api)
- [Swagger U I](https://music-api.mubert.com/api/v3/swagger)
- [A I Documentation](https://music-api.mubert.com/swagger-doc/llms.txt)
- [A I Documentation](https://music-api.mubert.com/swagger-doc/llms-full.txt)
- [GitHub Organization](https://github.com/MubertAI)
- [Samples](https://github.com/MubertAI/Mubert-Text-to-Music)
- [Agent Skills](https://github.com/MubertAI/skills)
- [Use Cases](https://mubert.com/use-cases/developers)
- [Blog](https://mubert.com/blog)
- [Terms of Service](https://mubert.com/legal/terms-of-use)
- [Privacy Policy](https://mubert.com/legal/privacy-policy)
- [Contact](https://mubert.com/contact)
- [Plans](plans/mubert-plans-pricing.yml)
- [Rate Limits](rate-limits/mubert-rate-limits.yml)
- [Fin Ops](finops/mubert-finops.yml)
- [Features](undefined)
- [Integrations](undefined)
- [Use Cases](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
