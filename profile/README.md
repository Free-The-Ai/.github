# Free The AI

FreeTheAi is an OpenAI-compatible AI API for people who want to build, test, roleplay, and automate without getting stuck behind credit-card gates.

We keep the public surface simple:

- One API shape that works with OpenAI-compatible clients.
- A growing model catalog for chat, coding, roleplay, search, and tool-use workflows.
- Discord-based key access, usage visibility, and community support.
- Guides for wiring the API into coding agents, editors, roleplay clients, and custom apps.

## Start Here

| What you need | Link |
| --- | --- |
| Website | [freetheai.xyz](https://freetheai.xyz) |
| Docs | [freetheai.xyz/docs](https://freetheai.xyz/docs/) |
| Models | [freetheai.xyz/models](https://freetheai.xyz/models/) |
| Pricing | [freetheai.xyz/pricing](https://freetheai.xyz/pricing/) |
| Public API repo | [Free-The-Ai/free-ai](https://github.com/Free-The-Ai/free-ai) |
| Coding-agent resources | [Free-The-Ai/free-code](https://github.com/Free-The-Ai/free-code) |

## What We Build

FreeTheAi focuses on practical access layers around AI:

- API compatibility for common chat-completion workflows.
- Streaming responses for clients that expect SSE.
- Tool-call and structured-output compatibility where models support it.
- Roleplay-friendly routing and docs for long-context clients.
- Public catalog metadata so users can pick models without guessing.

## For Builders

Use the API like a standard OpenAI-compatible endpoint:

```bash
curl https://api.freetheai.xyz/v1/chat/completions \
  -H "Authorization: Bearer YOUR_FREETHEAI_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "MODEL_ALIAS",
    "messages": [
      { "role": "user", "content": "Say hi from FreeTheAi." }
    ],
    "stream": true
  }'
```

Check the docs and model catalog for current aliases, access rules, and client setup notes.

## Community

FreeTheAi is community-driven. If you use the API, build something with it, or want to help improve docs and client setup guides, start with the public repos above and the website.

Star the repos if the project helps you.
