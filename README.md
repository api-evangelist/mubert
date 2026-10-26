# Mubert (mubert)

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
