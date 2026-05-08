# Hume AI (hume-ai)

Hume AI builds empathic voice and emotional AI models. The platform exposes four published APIs: Voices, Octave Text-to-Speech, Empathic Voice Interface (EVI / speech-to-speech), and Expression Measurement (multimodal emotion analysis). REST + WebSocket interfaces are documented with public OpenAPI and AsyncAPI specifications.

**APIs.json:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/hume-ai/refs/heads/main/apis.yml)

## Type
- **x-type:** company

## Tags
- AI, Voice, Empathic, Emotion, Multimodal

## APIs
1. **Hume Voices API** — voice management. OpenAPI: [`openapi/hume-ai-voices-openapi.yml`](openapi/hume-ai-voices-openapi.yml)
2. **Hume Octave Text-to-Speech API** — expressive TTS with streaming. OpenAPI: [`openapi/hume-ai-tts-openapi.yml`](openapi/hume-ai-tts-openapi.yml)
3. **Hume Empathic Voice Interface (EVI) API** — real-time speech-to-speech via WebSocket plus REST config/prompts/tools/chats. OpenAPI: [`openapi/hume-ai-evi-openapi.yml`](openapi/hume-ai-evi-openapi.yml). AsyncAPI also published.
4. **Hume Expression Measurement API** — multimodal emotion analysis (face, voice, language, burst). OpenAPI: [`openapi/hume-ai-expression-openapi.yml`](openapi/hume-ai-expression-openapi.yml)

## Common Properties
- [Website](https://www.hume.ai/)
- [Documentation](https://dev.hume.ai/)
- [Plans](plans/hume-ai-plans-pricing.yml) — reconciled
- [RateLimits](rate-limits/hume-ai-rate-limits.yml) — partial (plan quotas documented; HTTP RPS not public)
- [FinOps](finops/hume-ai-finops.yml) — reconciled

## Pricing Snapshot
- Free: $0, 10K TTS chars + 5 EVI minutes, 1 concurrent connection
- Starter: $3/mo / Creator: $7/mo / Pro: $70/mo / Scale: $200/mo / Business: $500/mo
- TTS overage: $0.05–$0.15 per 1,000 chars (varies by tier)
- EVI overage: $0.04–$0.06/min
- Expression Measurement (PAYG): video-with-audio $0.0828/min, audio-only $0.0639/min, images $0.00204 ea, words $0.00024 ea
- Enterprise: custom

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
