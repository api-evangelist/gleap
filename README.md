# Gleap

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
