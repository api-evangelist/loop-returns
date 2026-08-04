# Loop Returns (loop-returns)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
