# Rancher (rancher)

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

Rancher is an open source container management platform built by SUSE that provides a complete software stack for teams adopting containers. It simplifies Kubernetes cluster deployment and management across any infrastructure, providing unified security, policy, and user management across all clusters. The Rancher Management API exposes these capabilities as Kubernetes-style REST resources for automation and platform engineering.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rancher/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rancher/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Cluster Management
- Containers
- Kubernetes
- Multi-Cluster
- Open Source
- SUSE
- Platform Engineering

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-05-19

## APIs

### Rancher Management API

The Rancher Management API exposes Rancher's multi-cluster Kubernetes management capabilities as Kubernetes-style REST resources. It supports automation of cluster lifecycle, project and namespace management, user and access control, catalog and app management, and integration of Rancher into CI/CD and platform engineering workflows. Authentication is via bearer tokens generated from the Rancher UI or via the login endpoint, and the API is reached through the Rancher server URL.

- **Human URL:** [https://ranchermanager.docs.rancher.com/api/quickstart](https://ranchermanager.docs.rancher.com/api/quickstart)
- **Base URL:** `https://{rancher_host}/v3`

#### Tags

- Cluster Management
- Containers
- Kubernetes
- Multi-Cluster
- Open Source
- SUSE

#### Properties

- [Documentation](https://ranchermanager.docs.rancher.com/)
- [Getting Started](https://ranchermanager.docs.rancher.com/getting-started/overview)
- [A P I  Quick  Start](https://ranchermanager.docs.rancher.com/api/quickstart)
- [OpenAPI](openapi/rancher-management-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rancher-management-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rancher-management-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/rancher-cluster.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/rancher-project.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/rancher-node.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/rancher-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Structure](json-structure/rancher-cluster-structure.json)
- [JSON Structure](json-structure/rancher-project-structure.json)
- [JSON Structure](json-structure/rancher-node-structure.json)
- [Example](examples/rancher-list-clusters-example.json)
- [Example](examples/rancher-create-cluster-example.json)
- [Example](examples/rancher-list-projects-example.json)
- [Spectral Rules](rules/rancher-rules.yml)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/rancher)
- [Website](https://www.rancher.com/)
- [Documentation](https://ranchermanager.docs.rancher.com/)
- [GitHub Organization](https://github.com/rancher)
- [GitHub Repository](https://github.com/rancher/rancher)
- [Blog](https://www.suse.com/c/rancher/)
- [Pricing](https://www.rancher.com/pricing)
- [Sign Up](https://www.rancher.com/quick-start)
- [Support](https://www.rancher.com/support-maintenance-terms)
- [Vocabulary](vocabulary/rancher-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
