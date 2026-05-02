# Rancher (rancher)

Rancher is an open source container management platform built by SUSE that provides a complete software stack for teams adopting containers. It simplifies Kubernetes cluster deployment and management across any infrastructure, providing unified security, policy, and user management across all clusters. The Rancher Management API exposes these capabilities as Kubernetes-style REST resources for automation and platform engineering.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/rancher/refs/heads/main/apis.yml)

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
- **Modified:** 2026-04-28

## APIs

### Rancher Management API

The Rancher Management API exposes Rancher's multi-cluster Kubernetes management capabilities as Kubernetes-style REST resources. It supports automation of cluster lifecycle, project and namespace management, user and access control, catalog and app management, and integration of Rancher into CI/CD and platform engineering workflows. Authentication is via bearer tokens generated from the Rancher UI or via the login endpoint, and the API is reached through the Rancher server URL.

**Human URL:** [https://ranchermanager.docs.rancher.com/api/quickstart](https://ranchermanager.docs.rancher.com/api/quickstart)

**Base URL:** `https://{rancher_host}/v3`

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
- [API Quick Start](https://ranchermanager.docs.rancher.com/api/quickstart)
- [OpenAPI](openapi/rancher-management-api-openapi.yml)
- [JSONSchema](json-schema/rancher-cluster.json)
- [JSONSchema](json-schema/rancher-project.json)
- [JSONSchema](json-schema/rancher-node.json)
- [JSONLD](json-ld/rancher-context.jsonld)

## Common Properties

- [Website](https://www.rancher.com/)
- [Documentation](https://ranchermanager.docs.rancher.com/)
- [GitHub Organization](https://github.com/rancher)
- [GitHub Repository](https://github.com/rancher/rancher)
- [Blog](https://www.suse.com/c/rancher/)
- [Pricing](https://www.rancher.com/pricing)
- [Sign Up](https://www.rancher.com/quick-start)
- [Support](https://www.rancher.com/support-maintenance-terms)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
