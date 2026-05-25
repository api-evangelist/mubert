# Mubert (mubert)

Mubert is a generative AI music platform that composes royalty-free, DMCA-free music in real time from millions of artist-contributed loops, samples, and stems. The B2B Mubert AI Music API (v3) powers track generation, continuous HTTP / WebRTC streaming, browse access to a pre-generated music library, and service-tier customer + license + Stripe subscription administration. Mubert is used by apps, games, video tools, health and fitness products, and AI-content pipelines (including integrations with Picsart, Canva, and Restream) to embed adaptive generative music inside their experiences.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/mubert/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- AI Music, Generative, Royalty-Free, Streaming, Text-to-Music, Image-to-Music, Stems, B2B

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-25

## Plans

| Plan | Price (USD / month) | Generated Tracks | Streaming Minutes | Notes |
|---|---|---|---|---|
| Trial | $49 | 100 | 100 | Evaluation / prototyping |
| Startup | $199 | 5,000 | 5,000 | Production for early-stage apps |
| Startup+ | $499 | 30,000 | 30,000 | Lossless audio, dedicated support |
| Enterprise | Contact sales | Custom | Custom | Sub-licensing, SLA, custom quotas |

All output is royalty-free, DMCA-free, and cleared for commercial use across apps, games, videos, podcasts, and social media.

## APIs

### Mubert AI Music API
Mubert AI Music API v3 — the unified B2B surface for generating royalty-free AI music tracks, streaming continuous generative music (HTTP / WebRTC), browsing the pre-generated music library and playlist taxonomy, and (service tier) administering customers, licenses, prices, and Stripe subscriptions. Authentication uses `customer-id` + `access-token` headers for public endpoints and `company-id` + `license-token` headers for service endpoints. Ships AI-optimized `llms.txt` / `llms-full.txt` docs alongside Swagger UI.

**Human URL:** [https://mubert.com/api](https://mubert.com/api)
**Base URL:** `https://music-api.mubert.com`

- [Documentation](https://mubert.com/api)
- [Swagger UI](https://music-api.mubert.com/api/v3/swagger)
- [AI Documentation — llms.txt](https://music-api.mubert.com/swagger-doc/llms.txt)
- [AI Documentation — llms-full.txt](https://music-api.mubert.com/swagger-doc/llms-full.txt)
- [OpenAPI](openapi/mubert-music-api-openapi.yml)
- [JSON Schema — Track](json-schema/mubert-track-schema.json)
- [JSON Schema — Customer](json-schema/mubert-customer-schema.json)
- [JSON Schema — License](json-schema/mubert-license-schema.json)
- [JSON Schema — Playlist](json-schema/mubert-playlist-schema.json)
- [JSON Schema — Streaming Link](json-schema/mubert-streaming-link-schema.json)
- [JSON Structure — Track](json-structure/mubert-track-structure.json)
- [JSON Structure — License](json-structure/mubert-license-structure.json)
- [JSON-LD Context](json-ld/mubert-context.jsonld)
- [Example — Create Track](examples/mubert-create-track-example.json)
- [Example — Edit Track](examples/mubert-edit-track-example.json)
- [Example — Get Streaming Link](examples/mubert-get-streaming-link-example.json)
- [Example — Create Customer](examples/mubert-create-customer-example.json)
- [Vocabulary](vocabulary/mubert-vocabulary.yml)
- [Spectral Rules](rules/mubert-rules.yml)
- [Naftiko Capability — Tracks](capabilities/tracks-tracks.yaml)
- [Naftiko Capability — Streaming](capabilities/streaming-streaming.yaml)
- [Naftiko Capability — Music Library](capabilities/music-library-music-library.yaml)
- [Naftiko Capability — Customers](capabilities/customers-customers.yaml)
- [Naftiko Capability — Licenses](capabilities/licenses-licenses.yaml)
- [Naftiko Capability — Subscriptions](capabilities/subscriptions-subscriptions.yaml)

## API Surface

| Group | Endpoints |
|---|---|
| Tracks | `POST /api/v3/public/tracks`, `GET /api/v3/public/tracks`, `GET /api/v3/public/tracks/{track}`, `POST /api/v3/public/tracks/{track}/edit`, `POST /api/v3/public/tracks/{track}/similar`, `POST /api/v3/public/tracks/stored`, `POST /api/v3/public/tracks/record`, `GET /api/v3/public/tracks/session/{session_id}` |
| Streaming | `GET /api/v3/public/streaming/get-link`, `POST /api/v3/public/streaming/restart`, `POST /api/v3/public/streaming/set-intensity`, `POST /api/v3/public/streaming/set-loop-state` |
| Music Library | `GET /api/v3/public/music-library/params`, `GET /api/v3/public/music-library/tracks`, `GET /api/v3/public/playlists` |
| Subscriptions (Public) | `GET /api/v3/public/prices`, `GET /api/v3/public/prices/{price}`, `POST /api/v3/public/subscriptions/buy`, `POST /api/v3/public/subscriptions/cancel`, `POST /api/v3/public/stripe/webhook` |
| Customers (Service) | `GET /api/v3/service/customers`, `POST /api/v3/service/customers`, `GET /api/v3/service/customers/{customer}`, `PUT /api/v3/service/customers/{customer}`, `DELETE /api/v3/service/customers/{customer}`, `GET /api/v3/service/customers/custom-id/{customId}` |
| Licenses (Service) | `GET /api/v3/service/licenses`, `GET /api/v3/service/licenses/{license}`, `PUT /api/v3/service/licenses/{license}` |
| Billing (Service) | `POST /api/v3/service/stripe/billing-portal`, `POST /api/v3/service/stripe/subscriptions/buy`, `POST /api/v3/service/stripe/subscriptions/cancel` |

## Authentication

| Tier | Headers |
|---|---|
| Public (end-customer) | `customer-id` + `access-token` |
| Service (company) | `company-id` + `license-token` |

## Common Properties

- [Website — mubert.com](https://mubert.com/)
- [ProductPage — Mubert API](https://mubert.com/api)
- [ProductPage — Mubert Render](https://mubert.com/render)
- [ProductPage — Mubert Play](https://mubert.com/play)
- [ProductPage — Mubert Business](https://mubert.com/business)
- [ProductPage — Mubert Studio](https://mubert.com/studio)
- [Documentation — API Docs](https://mubert.com/api)
- [Swagger UI](https://music-api.mubert.com/api/v3/swagger)
- [AIDocumentation — llms.txt](https://music-api.mubert.com/swagger-doc/llms.txt)
- [AIDocumentation — llms-full.txt](https://music-api.mubert.com/swagger-doc/llms-full.txt)
- [GitHubOrganization — MubertAI](https://github.com/MubertAI)
- [Samples — Mubert Text-to-Music notebook](https://github.com/MubertAI/Mubert-Text-to-Music)
- [AgentSkills — MubertAI/skills](https://github.com/MubertAI/skills)
- [UseCases — Developers](https://mubert.com/use-cases/developers)
- [Blog](https://mubert.com/blog)
- [TermsOfService](https://mubert.com/legal/terms-of-use)
- [PrivacyPolicy](https://mubert.com/legal/privacy-policy)
- [Contact](https://mubert.com/contact)
- [Plans](plans/mubert-plans-pricing.yml)
- [RateLimits](rate-limits/mubert-rate-limits.yml)
- [FinOps](finops/mubert-finops.yml)

## Features

- Generative track creation from text prompts, image prompts, or playlist taxonomy
- Live streaming over HTTP and WebRTC with sub-second latency
- Continuous stream control — restart, set-intensity, set-loop-state
- 150+ genres, 50+ moods, 200+ million unique tracks per the provider
- Stem-level editing (drums, bass, leads, vocals) and 12+ part replacement
- Track durations 15-1500 seconds; modes `track` or `loop`; intensities low / medium / high
- Pre-generated music library browsable by genre, mood, BPM range, key, activity
- Track-store cache for re-issuing previously generated tracks
- "Generate similar" endpoint to create variations of an existing track
- Record a live stream session into a fixed track asset
- Service-tier customer CRUD with `custom_id` mapping to your end-users
- Service-tier license management exposing features, bitrates, intensities, formats, modes, and per-customer quotas
- Stripe-backed subscription buy / cancel / billing portal flows
- License-level webhooks for billing and generation lifecycle events
- All output is royalty-free, DMCA-free, and cleared for commercial monetization
- AI-optimized documentation: `llms.txt` and `llms-full.txt` published alongside Swagger UI
- Official `MubertAI/skills` repo of Agent Skills (setup, generate, streaming, library, manage)

## Integrations

- Picsart — generative music in UGC content tooling
- Canva — music inside the design surface
- Restream — live-stream background music
- Stripe — subscription billing

## Use Cases

- Apps embedding adaptive background music
- Games with dynamic, progression-aware soundscapes
- Health, fitness, and wellness apps with BPM / heart-rate mapped music
- Video editors and podcast tools needing royalty-free score generation
- AI content pipelines pairing image / text generation with matching music
- User-generated content platforms offering safe-to-publish music
- Marketing, advertising, and brand audio for retail and OOH

## Artifacts

### OpenAPI

- [Mubert AI Music API](openapi/mubert-music-api-openapi.yml)

### JSON Schema

- [Track](json-schema/mubert-track-schema.json)
- [Customer](json-schema/mubert-customer-schema.json)
- [License](json-schema/mubert-license-schema.json)
- [Playlist](json-schema/mubert-playlist-schema.json)
- [Streaming Link](json-schema/mubert-streaming-link-schema.json)

### JSON Structure

- [Track](json-structure/mubert-track-structure.json)
- [License](json-structure/mubert-license-structure.json)

### JSON-LD

- [Mubert Context](json-ld/mubert-context.jsonld)

### Examples

- [Create Track](examples/mubert-create-track-example.json)
- [Edit Track](examples/mubert-edit-track-example.json)
- [Get Streaming Link](examples/mubert-get-streaming-link-example.json)
- [Create Customer](examples/mubert-create-customer-example.json)

### Vocabulary

- [Mubert Vocabulary](vocabulary/mubert-vocabulary.yml)

### Spectral Rules

- [Mubert Rules](rules/mubert-rules.yml)

### Naftiko Capabilities

- [Tracks](capabilities/tracks-tracks.yaml)
- [Streaming](capabilities/streaming-streaming.yaml)
- [Music Library](capabilities/music-library-music-library.yaml)
- [Customers](capabilities/customers-customers.yaml)
- [Licenses](capabilities/licenses-licenses.yaml)
- [Subscriptions](capabilities/subscriptions-subscriptions.yaml)

### Plans

- [Mubert Plans and Pricing](plans/mubert-plans-pricing.yml)

### Rate Limits

- [Mubert Rate Limits](rate-limits/mubert-rate-limits.yml)

### FinOps

- [Mubert FinOps](finops/mubert-finops.yml)

## Maintainers

- **Kin Lane** — kin@apievangelist.com — [@apievangelist](https://x.com/apievangelist) — [apievangelist.com](https://apievangelist.com)
