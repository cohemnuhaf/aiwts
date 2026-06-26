# AIwts.com — Enterprise AI API Gateway

> **90% OFF Official Pricing** · 50+ AI Models · OpenAI-Compatible API

[![Website](https://img.shields.io/badge/Website-aiwts.com-blue)](https://www.aiwts.com)
[![API](https://img.shields.io/badge/API-api.aiwts.com-green)](https://api.aiwts.com)
[![Docs](https://img.shields.io/badge/Docs-docs.aiwts.com-orange)](https://docs.aiwts.com)
[![Status](https://img.shields.io/badge/Status-Operational-brightgreen)](https://www.aiwts.com)

AIwts.com is a high-performance AI API gateway that provides enterprise-grade access to the world's leading large language models. One API key, one OpenAI-compatible endpoint, all the models you need — at **90% OFF** official pricing.

## Why AIwts?

| Feature | Details |
|---------|---------|
| **Models** | 50+ cutting-edge models from OpenAI, Anthropic, Google, DeepSeek, Meta & more |
| **Pricing** | Up to 90% OFF compared to official API pricing |
| **Compatibility** | 100% OpenAI API compatible — just swap `base_url` |
| **Latency** | Global multi-node deployment, average response under 80ms |
| **Reliability** | 99.9% uptime SLA with automatic failover |
| **Support** | 24/7 technical support |

## Supported Models

- **OpenAI**: GPT-5.1, GPT-4.1, o4-mini, GPT-4.1-mini
- **Anthropic**: Claude Opus 4, Claude Sonnet 4, Claude Haiku 3.5
- **Google**: Gemini 2.5 Pro, Gemini 2.5 Flash
- **DeepSeek**: DeepSeek-V4, DeepSeek-R1
- **Alibaba**: Qwen 3.7 Max
- **Meta**: Llama 4 Maverick
- **Mistral**: Mistral Large 3
- And many more...

## Quick Start

```python
from openai import OpenAI

# Just change base_url
client = OpenAI(
    api_key="sk-your-aiwts-key",
    base_url="https://api.aiwts.com/v1"
)

response = client.chat.completions.create(
    model="gpt-4.1",
    messages=[{"role": "user", "content": "Hello, AI!"}]
)

print(response.choices[0].message.content)
```

```javascript
import OpenAI from 'openai';

// Just change baseURL
const client = new OpenAI({
    apiKey: 'sk-your-aiwts-key',
    baseURL: 'https://api.aiwts.com/v1'
});

const res = await client.chat.completions.create({
    model: 'gpt-4.1',
    messages: [{ role: 'user', content: 'Hello, AI!' }]
});

console.log(res.choices[0].message.content);
```

```bash
curl https://api.aiwts.com/v1/chat/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer sk-your-aiwts-key" \
  -d '{
    "model": "gpt-4.1",
    "messages": [{"role": "user", "content": "Hello, AI!"}]
  }'
```

## Pricing

| Tier | Price | Features |
|------|-------|----------|
| **Free** | $0 | Daily quota, basic models, community support |
| **Pro** | Pay-as-you-go | Full model access, 90% OFF, no limits, priority support |
| **Enterprise** | Custom | Dedicated deployment, on-premise, SLA, custom features |

## Links

- **Website**: [www.aiwts.com](https://www.aiwts.com)
- **API Endpoint**: `https://api.aiwts.com/v1`
- **Documentation**: [docs.aiwts.com](https://docs.aiwts.com)
- **Business Contact**: [business@aiwts.com](mailto:business@aiwts.com)

---

&copy; 2024 AIwts.com — Enterprise AI API Gateway
