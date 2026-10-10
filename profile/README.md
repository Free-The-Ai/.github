<p align="center">
  <a href="https://freetheai.org"><img src="https://raw.githubusercontent.com/Free-The-Ai/.github/main/profile/github.jpg" alt="FreeTheAI: free OpenAI-compatible AI API, SDKs, free stock widgets" width="100%"></a>
</p>

# FreeTheAI

FreeTheAI is a free, OpenAI-compatible AI API. One key and one base URL give you dozens of chat models with streaming, tool calling, web search with sourced answers, and image and video generation. Official SDKs are available for Python, JavaScript and TypeScript, and Go.

## Products

| Product | What it is |
| --- | --- |
| [Free AI API](https://freetheai.org) | The OpenAI-compatible API, the model catalog, and the docs |
| [Chat](https://chat.freetheai.org) | A web chat for the models on your account |
| [Stocks](https://stocks.freetheai.org) | Free market news, live price cards, and charts. Prices can be delayed; nothing here is financial advice. |
| [Prompts](https://prompts.freetheai.org) | A library of prompts to share and reuse |

## Quickstart

The API is OpenAI-compatible, so any client with a base URL setting works. Create a key at [freetheai.org](https://freetheai.org/dashboard/api-keys), do the [daily check-in](https://freetheai.org/checkin) for free models, then:

```text
Base URL   https://api.freetheai.org/v1
Auth       Authorization: Bearer YOUR_API_KEY
Models     fta/<provider>/<model>, for example fta/zai/glm-5.3
```

```bash
curl https://api.freetheai.org/v1/chat/completions \
  -H "Authorization: Bearer $FREETHEAI_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"model": "fta/zai/glm-5.3", "messages": [{"role": "user", "content": "Hello!"}]}'
```

The free tier is 50 requests a day, reset at 00:00 UTC. Paid plans are coming soon.

## Repositories

| Repository | What it is |
| --- | --- |
| [freetheai-python](https://github.com/Free-The-Ai/freetheai-python) | Official Python SDK (`pip install freetheai`) · [docs](https://free-the-ai.github.io/freetheai-python/) |
| [freetheai-js](https://github.com/Free-The-Ai/freetheai-js) | Official JavaScript and TypeScript SDK (`npm install freetheai`) · [docs](https://free-the-ai.github.io/freetheai-js/) |
| [freetheai-go](https://github.com/Free-The-Ai/freetheai-go) | Official Go SDK (`go get github.com/Free-The-Ai/freetheai-go`) · [docs](https://free-the-ai.github.io/freetheai-go/) |
| [free-stock-widgets](https://github.com/Free-The-Ai/free-stock-widgets) | How to embed FreeTheAI Stocks price cards, charts, and news feeds · [docs](https://free-the-ai.github.io/free-stock-widgets/) |
| [freetheai-cookbook](https://github.com/Free-The-Ai/freetheai-cookbook) | Runnable examples for the SDKs, OpenAI clients, LangChain, LlamaIndex, the Vercel AI SDK, RAG, and more · [docs](https://free-the-ai.github.io/freetheai-cookbook/) |
| [free-ai](https://github.com/Free-The-Ai/free-ai) | The public website source, setup guides, and examples |

## Links

- Docs: [freetheai.org/docs](https://freetheai.org/docs)
- Models: [freetheai.org/models](https://freetheai.org/models)
- Status: [freetheai.org/status](https://freetheai.org/status)
- Setup guides for apps and coding agents: [freetheai.org/setup](https://freetheai.org/setup)
- Discord: [discord.gg/secrets](https://discord.gg/secrets)
- Contact: vibheksoni@engineer.com · [@ImVibhek](https://x.com/ImVibhek)

FreeTheAI is built by [Vibhek Soni](https://vibheksoni.com).
