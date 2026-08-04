# Hume AI (hume-ai)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Hume AI builds empathic voice and emotional AI models. The platform exposes four published APIs: Voices, Octave Text-to-Speech, Empathic Voice Interface (EVI / speech-to-speech), and Expression Measurement (multimodal emotion analysis). REST + WebSocket interfaces are documented with public OpenAPI and AsyncAPI specifications at https://dev.hume.ai/.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hume-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hume-ai/refs/heads/main/apis.yml)

## Tags

- AI
- Voice
- Empathic
- Emotion
- Multimodal

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-29

## APIs

### Hume Voices API

REST API for managing custom voices used by Hume's TTS and EVI products. Supports voice creation, listing, and deletion. Bearer token auth.

- **Human URL:** [https://dev.hume.ai/reference](https://dev.hume.ai/reference)
- **Base URL:** `https://api.hume.ai`

#### Tags

- Voices
- Voice Cloning
- TTS

#### Properties

- [Documentation](https://dev.hume.ai/reference)
- [OpenAPI](openapi/hume-ai-voices-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hume-ai-voices.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hume-ai-voices.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hume Octave Text-to-Speech API

REST API for synthesizing expressive speech using Octave. Supports streamed JSON/file and standard JSON/file responses, plus voice conversion endpoints.

- **Human URL:** [https://dev.hume.ai/docs/text-to-speech-tts](https://dev.hume.ai/docs/text-to-speech-tts)
- **Base URL:** `https://api.hume.ai`

#### Tags

- TTS
- Speech Synthesis
- Streaming
- Octave

#### Properties

- [Documentation](https://dev.hume.ai/docs/text-to-speech-tts)
- [OpenAPI](openapi/hume-ai-tts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hume-ai-tts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hume-ai-tts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Pricing](https://www.hume.ai/pricing)

### Hume Empathic Voice Interface (EVI) API

Real-time emotionally intelligent speech-to-speech voice interface delivered over WebSockets. Includes configuration, prompt, and tool management plus chat history, chat group operations, and webhook events for tool calls and chat lifecycle.

- **Human URL:** [https://dev.hume.ai/docs/speech-to-speech-evi](https://dev.hume.ai/docs/speech-to-speech-evi)
- **Base URL:** `https://api.hume.ai`

#### Tags

- EVI
- Speech-to-Speech
- WebSocket
- Realtime
- Empathic

#### Properties

- [Documentation](https://dev.hume.ai/docs/speech-to-speech-evi)
- [OpenAPI](openapi/hume-ai-evi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hume-ai-evi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hume-ai-evi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](https://dev.hume.ai/asyncapi.yaml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [AsyncAPI](asyncapi/hume-ai-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Hume Expression Measurement API

Multimodal emotion analysis API for face, voice, language, and burst expression. Offers batch inference jobs over images/audio/video/text, and streaming inference.

- **Human URL:** [https://dev.hume.ai/docs/expression-measurement](https://dev.hume.ai/docs/expression-measurement)
- **Base URL:** `https://api.hume.ai`

#### Tags

- Expression Measurement
- Emotion
- Multimodal
- Batch
- Streaming

#### Properties

- [Documentation](https://dev.hume.ai/docs/expression-measurement)
- [OpenAPI](openapi/hume-ai-expression-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hume-ai-expression.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hume-ai-expression.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/hume-ai-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

## Common Properties

- [GitHub Organization](https://github.com/HumeAI)
- [LinkedIn](https://www.linkedin.com/company/hume-ai)
- [Website](https://www.hume.ai/)
- [Documentation](https://dev.hume.ai/)
- [Plans](plans/hume-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/hume-ai-rate-limits.yml)
- [Fin Ops](finops/hume-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
