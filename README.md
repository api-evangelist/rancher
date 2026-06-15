# Rancher (rancher)

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
