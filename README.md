# Novita AI (novita-ai)

Novita AI is an AI inference cloud offering serverless LLM, image, video, and audio generation APIs alongside on-demand GPU rentals and serverless GPU endpoints. Hosts open-source models with both native and OpenAI-compatible chat surfaces, plus an agent sandbox and an MCP server for tool-using agents.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/novita-ai/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=novita-ai-api-evangelist&utm_content=repo)

## Type
- **x-type:** company

## Tags
- AI, LLM, Inference, GPU, OpenAI Compatible, Image Generation, Video Generation, Audio, Embeddings, Sandbox, MCP

## APIs

### Novita AI Platform API
LLM chat completions (OpenAI-compatible at `https://api.novita.ai/openai`; native at `https://api.novita.ai`), completions, embeddings, reranking, files, batch, image generation (FLUX.1, Seedream 3.0 / 4.0, Qwen Image), image editing (upscale, background removal/replacement, inpaint, reimagine, image-to-prompt), video generation (Hunyuan, Kling V2.1, Vidu Q1, MiniMax Hailuo 02), audio (MiniMax Speech 02 HD TTS, GLM ASR), authentication, balance/billing, and budget management.

**Human URL:** [https://novita.ai/docs/api-reference/api-reference-overview](https://novita.ai/docs/api-reference/api-reference-overview)

- [Documentation](https://novita.ai/docs/)
- [API Reference](https://novita.ai/docs/api-reference/api-reference-overview)
- [OpenAPI Discovery](openapi/novita-ai-openapi.json) (mirrored from `https://novita.ai/.well-known/openapi.json`)
- [OpenAI-Compatible Base URL](https://api.novita.ai/openai)
- [Authentication](https://novita.ai/docs/api-reference/basic-authentication)
- [Error Codes](https://novita.ai/docs/api-reference/basic-error-code)
- [Model Catalog](https://novita.ai/models)
- [Sign Up](https://novita.ai/)
- [Pricing](https://novita.ai/pricing)

### Novita AI GPU API
On-demand GPU instance management and templates plus serverless GPU endpoints. Create, start, stop, and delete instances; list products and templates; query usage-based and fixed-term billing.

**Human URL:** [https://novita.ai/docs/api-reference/gpu-instance-create-instance](https://novita.ai/docs/api-reference/gpu-instance-create-instance)

- [GPU Product Page](https://novita.ai/gpus)
- [Serverless Product Page](https://novita.ai/serverless)
- [API Reference](https://novita.ai/docs/api-reference/gpu-instance-create-instance)

## Plans, Rate Limits, FinOps
- [Plans](plans/novita-ai-plans-pricing.yml) — Pay-as-you-go and fixed-term GPU billing.
- [Rate Limits](rate-limits/novita-ai-rate-limits.yml)
- [FinOps](finops/novita-ai-finops.yml)

## SDKs, CLI, and Integrations
- [Python SDK](https://github.com/novitalabs/python-sdk)
- [JavaScript / TypeScript SDK](https://github.com/novitalabs/javascript-sdk)
- [Go SDK](https://github.com/novitalabs/golang-sdk)
- [LangChain Integration](https://github.com/novitalabs/langchain-novita)
- [Novita CLI](https://github.com/novitalabs/novita-cli)
- [Novita MCP Server](https://github.com/novitalabs/novita-mcp-server)

## Common Properties
- [Website](https://novita.ai/)
- [Documentation](https://novita.ai/docs/)
- [Guides](https://novita.ai/docs/guides/introduction)
- [Blog](https://novita.ai/blog)
- [Status](https://status.novita.ai)
- [Terms of Service](https://novita.ai/legal/terms-of-service)
- [Privacy Policy](https://novita.ai/legal/privacy-policy)
- [GitHub Organization](https://github.com/novitalabs)
- [LinkedIn](https://www.linkedin.com/company/novita-ai-labs)
- [X / Twitter](https://x.com/novitalabs)
- [Discord](https://discord.com/invite/Mqx7nWYzDF)
- [llms.txt](https://novita.ai/llms.txt)

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-25

## Notes
- Novita publishes a small discovery OpenAPI at `https://novita.ai/.well-known/openapi.json` covering the OpenAI-compatible `chat/completions`, `completions`, `embeddings`, and `models` paths; the full REST surface (image, video, audio, GPU, billing, budget) is documented only as HTML reference pages.
- The OpenAI-compatible surface lives under `https://api.novita.ai/openai`; the native Novita surface lives under `https://api.novita.ai` and is what the platform's image, video, audio, GPU, and billing endpoints use.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
