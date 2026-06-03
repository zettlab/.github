# zettlab/.github

Org-wide GitHub configuration for `zettlab/*` repositories.

## Workflow templates

Available at **New repository → Actions → from workflow template → By zettlab**:

| Template | Purpose | Use when |
|---|---|---|
| [`shared-library-go.yml`](./workflow-templates/shared-library-go.yml) | CI (vet + build + race tests + tidy idempotency) + release-on-tag with auto-generated notes | Creating a new private Go shared library under `zettlab/` per [RFC-0001](https://github.com/zettlab/zettlab-product-dev/blob/main/docs/rfc/0001-shared-library-repo-pattern.md) |

## Onboarding

New engineer? Read [`zettlab-product-dev/docs/getting-started-go-shared-libs.md`](https://github.com/zettlab/zettlab-product-dev/blob/main/docs/getting-started-go-shared-libs.md) before your first `go build` of a Zettlab private repo.

## Governance

This repo is governed by RFC-0001 §A4 (CI templates) and RFC-0001 §A6 (onboarding docs). Changes here affect every Zettlab repo's "create new workflow" suggestions — review accordingly.
