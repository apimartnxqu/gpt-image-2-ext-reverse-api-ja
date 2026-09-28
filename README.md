# GPT-Image-2 Ext — リバース route (日本語)

> **1K $0.0085; 2K $0.014; 4K $0.021** · model ID `gpt-image-2` · **リバース/逆解析** route.

**[料金を見る](https://go.apimart.ai/k-da7b1a)** · **[APIキーを取得](https://go.apimart.ai/k-4cdc44)**

gpt-image-2-ext-reverse-api-ja は **リバース** の GPT-Image-2 Ext ルートです。呼び出し ID は `gpt-image-2`、公式ルート（`gpt-image-2-official`）と並行提供で単価が低くなります。

## Pricing (snapshot 2026-09-28)

| Tier | Price |
| --- | --- |
| `1K` | $0.0085 |
| `2K` | $0.014 |
| `4K` | $0.021 |

Prices are per delivered image; `n` in the request multiplies the total. Snapshot date **2026-09-28** — the live pricing page is authoritative.

## Quickstart

```bash
curl -X POST https://api.apimart.ai/v1/images/generations \
  -H 'Authorization: Bearer $APIMART_KEY' \
  -H 'Content-Type: application/json' \
  -d '{"model":"gpt-image-2","prompt":"cozy reading nook, warm lamp, cinematic","size":"1:1","resolution":"1K","n":1}'
```

Async: submit → get `task_id` → poll `GET https://api.apimart.ai/v1/tasks/<task_id>` → read `cost` / `credits_cost` from the result. Parameter tables, `version`/`resolution`/`size` options and idempotency headers are documented on the model page reachable from the pricing link above.

## Reverse vs official route

| Route | Callable ID | Price |
| --- | --- | --- |
| **リバース** | `gpt-image-2` | 1K $0.0085; 2K $0.014; 4K $0.021 |
| 公式転送 | `gpt-image-2-official` | official list price, billed at ×0.8 group ratio |


## Keywords

`gpt-image-2-ext` · `gpt-image-2` · `リバース` · `逆解析` · `AI API ゲートウェイ` · `API 中継` · `nano banana 2 api` · `gpt-image-2.5 api` · `ai api pricing` · `pay-as-you-go`

## Platform facts

- USD settlement, pay-as-you-go, **$1 minimum top-up**, no subscription.
- Operating since last year; ~100,000 registered users, mostly enterprise accounts.
- International invoices available on request.
- 307 models online (live `/v1/models`) as of 2026-09-28.

## Disclosure

This repository documents **APIMart**, a third-party API aggregator/gateway. It is **not affiliated with, endorsed by, or sponsored by** OpenAI, Google, Anthropic, xAI, ByteDance or any model vendor. Model names and trademarks belong to their owners. Prices are a point-in-time snapshot and may change; the vendor's console billing is authoritative.

