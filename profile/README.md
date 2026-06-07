<div align="center">

<img src="https://raw.githubusercontent.com/Free-The-Ai/free-ai/master/freetheai-transparent-logo-responsive-same-colors.svg" alt="FreeTheAi" width="440" />

# FreeTheAi

### OpenAI-compatible AI access for builders, roleplayers, tinkerers, and coding agents.

FreeTheAi gives the community a simple API surface for using AI models without forcing every experiment through a credit-card gate.

<br>

[![Website](https://img.shields.io/badge/Website-freetheai.xyz-111111?style=for-the-badge)](https://freetheai.xyz)
[![Docs](https://img.shields.io/badge/Docs-Quickstart-0B5FFF?style=for-the-badge)](https://freetheai.xyz/docs/)
[![Models](https://img.shields.io/badge/Models-50%2B-00A86B?style=for-the-badge)](https://freetheai.xyz/models/)
[![Discord](https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/secrets)

[Website](https://freetheai.xyz) | [Quickstart](https://freetheai.xyz/quickstart/) | [Setup Guides](https://freetheai.xyz/setup/) | [Model Catalog](https://freetheai.xyz/models/) | [Pricing](https://freetheai.xyz/pricing/) | [Status](https://freetheai.xyz/status/)

</div>

---

## What This Is

FreeTheAi is a community AI API project built around a practical idea: one familiar OpenAI-compatible interface, many usable model routes, and setup docs that work with real clients.

It is made for:

| Use case | What FreeTheAi focuses on |
| --- | --- |
| Coding agents | OpenAI-compatible setup guides for editors, CLIs, and agent workflows |
| Roleplay clients | Roleplay-friendly docs, long-context guidance, and model notes |
| App builders | Chat completions, streaming, tool-call compatibility, and catalog metadata |
| Experimenters | A low-friction way to test model behavior without rebuilding every client |

## Public Repos

| Repo | Purpose |
| --- | --- |
| [Free-The-Ai/free-ai](https://github.com/Free-The-Ai/free-ai) | Public website, docs, quickstarts, setup guides, examples, and model catalog resources |
| [Free-The-Ai/free-code](https://github.com/Free-The-Ai/free-code) | Coding-agent resources for connecting FreeTheAi to developer tools and workflows |

## API Shape

If your client supports an OpenAI-compatible base URL, the setup is usually this simple:

```text
Base URL: https://api.freetheai.xyz/v1
Auth:     Bearer YOUR_FREETHEAI_KEY
```

```bash
curl https://api.freetheai.xyz/v1/chat/completions \
  -H "Authorization: Bearer YOUR_FREETHEAI_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "MODEL_ALIAS",
    "messages": [
      {
        "role": "user",
        "content": "Say hi from FreeTheAi."
      }
    ],
    "stream": true
  }'
```

## Core Links

| Need | Go here |
| --- | --- |
| Get started | [Quickstart](https://freetheai.xyz/quickstart/) |
| See available models | [Model Catalog](https://freetheai.xyz/models/) |
| Connect a coding tool | [Setup Guides](https://freetheai.xyz/setup/) |
| Read API docs | [Docs](https://freetheai.xyz/docs/) |
| Join the community | [Discord](https://discord.gg/secrets) |
| Check API status | [Status](https://freetheai.xyz/status/) |

## Project Direction

We care about access that is actually useful:

- Keep the API familiar for OpenAI-compatible clients.
- Keep public model metadata readable and current.
- Keep setup docs practical, not theoretical.
- Keep roleplay, coding, and app-builder workflows documented separately.
- Keep public-facing output clean and free of internal provider details.

---

<div align="center">

**Build with it. Break your setup less. Share what works.**

[Star `free-ai`](https://github.com/Free-The-Ai/free-ai) | [Join Discord](https://discord.gg/secrets) | [Open the docs](https://freetheai.xyz/docs/)

</div>
