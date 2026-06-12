# Loop Returns (loop-returns)

Loop Returns is an AI-powered post-purchase operations platform built for e-commerce retention that unites tracking, returns, exchanges, fraud prevention, and shipping into a single platform. Originally built for Shopify, Loop now supports all e-commerce platforms and enables brands to transform returns into revenue-retaining exchanges. The platform provides a REST API for creating return authorizations, tracking return status, managing exchange workflows, generating labels, and triggering refunds, along with programmatic webhook support for real-time event notifications.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/loop-returns/refs/heads/main/apis.yml

**Naftiko Fleet:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=loop-returns-api-evangelist&utm_content=repo

## Tags

Returns, E-Commerce, Exchanges, Refunds, Shipping, Post-Purchase, Shopify, Fraud Prevention, Retail

## APIs

| Name | Description | Docs |
|------|-------------|------|
| Loop Returns API | REST API for managing returns, exchanges, labels, carts, destinations, allowlists, webhooks, and item grading | [Documentation](https://docs.loopreturns.com/api-reference/getting-started) |

## Plans / Rate Limits / FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/loop-returns-plans-pricing.yml](plans/loop-returns-plans-pricing.yml) |
| Rate Limits | [rate-limits/loop-returns-rate-limits.yml](rate-limits/loop-returns-rate-limits.yml) |
| FinOps | [finops/loop-returns-finops.yml](finops/loop-returns-finops.yml) |

**Plans summary:** Checkout+ (free, per-shipment label cost) | Essential ($155+/month) | Advanced ($340+/month)

**Rate limits:** 300 requests per minute per API key; HTTP 429 on breach. Authentication via `X-Authorization` header (API key) or OAuth 2.0 (Label and Webhooks APIs). OAuth tokens expire after 1 hour.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.loopreturns.com/ |
| Documentation | https://docs.loopreturns.com/ |
| Pricing | https://www.loopreturns.com/pricing |
| Blog | https://www.loopreturns.com/blog/ |
| Changelog | https://changelog.loopreturns.com/ |
| Status Page | https://status.loopreturns.com/ |
| Help Center | https://help.loopreturns.com/ |
| GitHub Organization | https://github.com/LoopReturns |
| LinkedIn | https://www.linkedin.com/company/loop-returns |
| X / Twitter | https://x.com/loop |

## Maintainers

**Kin Lane** — kin@apievangelist.com
