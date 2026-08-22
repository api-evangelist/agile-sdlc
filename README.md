# Agile SDLC (agile-sdlc)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

A collection of resources, tools, and APIs covering the Agile Software Development Life Cycle (SDLC) — an iterative and incremental approach to software development that integrates agile principles across every phase from requirements through deployment. Agile SDLC replaces the rigid waterfall model with continuous planning, development, testing, and delivery through short sprint cycles.

**URL:** [https://agilealliance.org/](https://agilealliance.org/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Iterative Development, Methodology, Project Management, Software Development, SDLC, DevOps, CI/CD

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## Common Properties

- [Portal](https://agilealliance.org/)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - SDLC Phase Schema](https://raw.githubusercontent.com/api-evangelist/agile-sdlc/refs/heads/main/json-schema/agile-sdlc-sdlc-phase-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/agile-sdlc/refs/heads/main/json-ld/agile-sdlc-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/agile-sdlc/refs/heads/main/vocabulary/agile-sdlc-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Requirements and Story Management | APIs for capturing, managing, and tracing requirements as user stories throughout the agile SDLC. |
| Continuous Integration | CI/CD pipeline APIs that enable frequent code integration and automated testing as part of agile SDLC. |
| Test Automation Integration | Testing platform APIs that integrate with agile sprints to validate working software after every iteration. |
| Release Management | APIs for coordinating software releases across agile teams, including feature flags, canary deployments, and rollback. |
| Observability and Feedback Loops | Monitoring and analytics APIs that close the feedback loop between deployment and planning in the agile SDLC. |

## Use Cases

| Name | Description |
|------|-------------|
| Sprint-Driven CI/CD | Trigger CI/CD pipelines at sprint completion to automatically build, test, and deploy working increments to staging or production. |
| Automated Test Coverage Reporting | Integrate testing APIs with sprint management to surface test coverage metrics during sprint reviews. |
| Feature Flag Management | Use feature flag APIs to enable trunk-based development within agile SDLC, decoupling deployment from feature release. |
| Agile SDLC Compliance | Track SDLC activities across sprints to demonstrate regulatory compliance for software development processes. |

## Integrations

| Name | Description |
|------|-------------|
| GitHub Actions | CI/CD automation platform integrated with GitHub repositories for agile SDLC pipeline automation. |
| Jenkins | Open-source CI/CD automation server widely used in agile SDLC pipelines with a REST API. |
| SonarQube | Code quality platform that integrates with agile SDLC to provide automated code review feedback during sprints. |
| Selenium | Browser automation framework used for end-to-end testing in agile SDLC pipelines. |
| LaunchDarkly | Feature flag management platform enabling safe, controlled feature releases in agile SDLC workflows. |

## Artifacts

### JSON Schema

- [SDLC Phase Schema](json-schema/agile-sdlc-sdlc-phase-schema.json)

### JSON Structure

- [SDLC Phase Structure](json-structure/agile-sdlc-sdlc-phase-structure.json)

### JSON-LD

- [Agile SDLC Context](json-ld/agile-sdlc-context.jsonld)

## Vocabulary

- [Agile SDLC Vocabulary](vocabulary/agile-sdlc-vocabulary.yaml) — Taxonomy for SDLC phases, CI pipelines, and test suites in agile development

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
