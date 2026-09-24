# Kimi K2.7 Code API (kimi-k2.7-code / kimik2.7code) — llm guide with published pricing

> **input $0.7429; output $3.083** — flat per-unit billing through the OpenAI-compatible APIMart gateway, $1 minimum top-up.

**[Live pricing](https://go.apimart.ai/k-b3df96)** · **[Get an API key](https://go.apimart.ai/k-771402)**

Everything here refers to **kimi-k2.7-code** — also written **kimik2.7code** or **kimi k2.7 code**.

## Pricing (observed, snapshot 2026-09-24)

| Tier | Price |
| --- | --- |
| `input` | $0.7429 |
| `output` | $3.083 |

## Cost at scale

| Volume | Cost |
| --- | --- |
| 100 | $74.288 |
| 1,000 | $742.88 |

## How to call it

```bash
curl --request POST --url https://api.apimart.ai/v1/images/generations \
  --header "Authorization: Bearer $APIMART_API_KEY" --header 'Content-Type: application/json' \
  --data '{"model":"kimi-k2.7-code","prompt":"a modern cliffside villa at dusk","size":"16:9","n":1}'
```

Submit, keep the `task_id`, poll `GET /v1/tasks/{id}` until `completed`; the response carries the URL and the exact amount charged.

## Disclosure

Documents access through APIMart, a third-party API gateway; not affiliated with the model vendor.
