# Gleap

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

Gleap is an in-app customer feedback and bug reporting platform with AI agents that automates the loop from user feedback through code deployment. The platform integrates support, product management, and engineering workflows into a single system used by 4,500+ teams globally.

## Overview

Gleap provides a REST API for managing feedback tickets, user identification, event tracking, help center content, outbound messaging, sessions, contacts, and AI-powered support workflows. The API uses Bearer token authentication with a project-scoped API key.

- **Base URL:** `https://api.gleap.io`
- **API Version:** v3
- **OpenAPI Spec:** `https://api.gleap.io/api-docs.json`
- **Documentation:** `https://docs.gleap.io/documentation/server/rest-api`
- **Authentication:** Bearer token (`Authorization: Bearer YOUR_API_KEY`) + `Project: YOUR_PROJECT_ID` header

## Links

- **Website:** https://gleap.io
- **Documentation:** https://docs.gleap.io
- **Blog:** https://gleap.io/blog
- **Pricing:** https://gleap.io/pricing
- **Status Page:** https://status.gleap.io
- **GitHub:** https://github.com/GleapSDK
- **LinkedIn:** https://www.linkedin.com/company/gleap/
- **X:** https://x.com/gleapsdk

## APIs.json

This repository contains the APIs.json catalog entry for Gleap, including:

- `apis.yml` — Main APIs.json provider index
- `plans/gleap-plans-pricing.yml` — API Commons Plans 0.1 pricing details
- `rate-limits/gleap-rate-limits.yml` — API Commons Rate Limits 0.1
- `finops/gleap-finops.yml` — FinOps Framework 1.0 FOCUS-aligned cost guidance
