# Novita AI (novita-ai)

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

Novita AI is an AI inference cloud offering serverless LLM, image, video, and audio generation APIs alongside on-demand GPU rentals and serverless GPU endpoints. Hosts open-source models with both native and OpenAI-compatible chat surfaces, plus an agent sandbox and MCP server for tool-using agents.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/novita-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/novita-ai/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Inference
- GPU
- OpenAI Compatible
- Image Generation
- Video Generation
- Audio
- Embeddings
- Sandbox
- MCP

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-30

## APIs

### Novita AI Platform API

LLM chat completions (OpenAI-compatible), embeddings, reranking, batch, image generation (FLUX.1, Seedream 3.0/4.0, Qwen), image editing (upscale, background removal/replacement, inpaint, reimagine), video (Hunyuan, Kling V2.1, Vidu Q1, MiniMax Hailuo), audio (MiniMax Speech 02 HD TTS and GLM ASR), authentication, billing, and account management. Native base URL https://api.novita.ai; OpenAI-compatible https://api.novita.ai/openai.

- **Human URL:** [https://novita.ai/docs/api-reference/api-reference-overview](https://novita.ai/docs/api-reference/api-reference-overview)
- **Base URL:** `https://api.novita.ai`

#### Tags

- AI
- LLM
- Chat Completions
- Embeddings
- Reranking
- Image Generation
- Image Editing
- Video Generation
- Audio
- Batch
- Files
- Budget

#### Properties

- [Documentation](https://novita.ai/docs/)
- [API Reference](https://novita.ai/docs/api-reference/api-reference-overview)
- [OpenAPI](openapi/novita-ai-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/novita-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novita-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Open A P I Discovery](https://novita.ai/.well-known/openapi.json)
- [AsyncAPI](asyncapi/novita-ai-asyncapi.yaml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Open A I Compatible Base U R L](https://api.novita.ai/openai)
- [Authentication](https://novita.ai/docs/api-reference/basic-authentication)
- [Error Codes](https://novita.ai/docs/api-reference/basic-error-code)
- [Model Catalog](https://novita.ai/models)
- [Sign Up](https://novita.ai/)
- [Pricing](https://novita.ai/pricing)

### Novita AI GPU API

On-demand GPU instance management and templates plus serverless GPU endpoints. Create, start, stop, and delete instances; list products and templates; query usage-based and fixed-term billing.

- **Human URL:** [https://novita.ai/docs/api-reference/gpu-instance-create-instance](https://novita.ai/docs/api-reference/gpu-instance-create-instance)
- **Base URL:** `https://api.novita.ai`

#### Tags

- GPU
- Compute
- Serverless
- Instances
- Templates
- Billing

#### Properties

- [Documentation](https://novita.ai/docs/)
- [API Reference](https://novita.ai/docs/api-reference/gpu-instance-create-instance)
- [Product Page](https://novita.ai/gpus)
- [Serverless Product Page](https://novita.ai/serverless)
- [Postman Collection](collections/novita-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/novita-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://novita.ai/)
- [Documentation](https://novita.ai/docs/)
- [API Reference](https://novita.ai/docs/api-reference/api-reference-overview)
- [Guides](https://novita.ai/docs/guides/introduction)
- [Pricing](https://novita.ai/pricing)
- [Sign Up](https://novita.ai/)
- [Blog](https://novita.ai/blog)
- [Status Page](https://status.novita.ai)
- [Terms of Service](https://novita.ai/legal/terms-of-service)
- [Privacy Policy](https://novita.ai/legal/privacy-policy)
- [GitHub Organization](https://github.com/novitalabs)
- [LinkedIn](https://www.linkedin.com/company/novita-ai-labs)
- [Twitter](https://x.com/novitalabs)
- [Discord](https://discord.com/invite/Mqx7nWYzDF)
- [L L Ms Txt](https://novita.ai/llms.txt)
- [SDK](https://github.com/novitalabs/python-sdk)
- [SDK](https://github.com/novitalabs/javascript-sdk)
- [SDK](https://github.com/novitalabs/golang-sdk)
- [SDK](https://github.com/novitalabs/langchain-novita)
- [C L I](https://github.com/novitalabs/novita-cli)
- [M C P Server](https://github.com/novitalabs/novita-mcp-server)
- [Plans](plans/novita-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/novita-ai-rate-limits.yml)
- [Fin Ops](finops/novita-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
