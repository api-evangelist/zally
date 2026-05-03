# Zally (zally)
Zally is an open source API linter from Zalando that validates OpenAPI 2 and 3 specifications against configurable rule sets for API design consistency. It exposes a REST API, command-line interface, and web UI for checking API designs against Zalando's RESTful API Guidelines or custom rule sets.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Design, API Linting, API Quality, Open Source, OpenAPI, Zalando

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-05-03

## APIs

### Zally API
The Zally REST API performs linting of OpenAPI specifications against configurable rule sets. It returns violations grouped by rule severity (MUST, SHOULD, COULD, MAY, HINT), tracks linting statistics, and lists supported rules. Authentication is via Bearer JWT.

**Human URL:** [https://opensource.zalando.com/zally/](https://opensource.zalando.com/zally/)

#### Tags:

 - API Linting, API Quality, OpenAPI

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/openapi/zally-api.yml)
- [Documentation](https://opensource.zalando.com/zally/)
- [APIReference](https://github.com/zalando/zally/blob/main/server/zally-server/src/main/resources/api/zally-api.yaml)
- [Authentication](https://github.com/zalando/zally/tree/main/server#authentication)
- [JSONSchema](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/json-schema/)
- [JSONStructure](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/json-structure/)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/json-ld/zally-context.jsonld)
- [Example](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/examples/)

## Common Properties

- [Website](https://opensource.zalando.com/zally/)
- [Documentation](https://github.com/zalando/zally#readme)
- [GitHubRepository](https://github.com/zalando/zally)
- [GitHubOrganization](https://github.com/zalando)
- [License](https://github.com/zalando/zally/blob/main/LICENSE)
- [Issues](https://github.com/zalando/zally/issues)
- [ChangeLog](https://github.com/zalando/zally/releases)
- [CLI](https://github.com/zalando/zally/tree/main/cli)
- [SDK](https://github.com/zalando/zally/tree/main/web-ui)
- [Specification](https://opensource.zalando.com/restful-api-guidelines/)
- [SpectralRules](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/rules/zally-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/vocabulary/zally-vocabulary.yml)
- [NaftikoCapability](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/capabilities/zally-workflow.yaml)

## Features

| Name | Description |
|------|-------------|
| API Linting | Validate OpenAPI 2/3 specifications against rule sets to enforce design consistency. |
| Configurable Rules | Customize default Zalando RESTful API Guidelines rules or define custom rule sets. |
| Multiple Interfaces | REST API for programmatic access, CLI for local checking, and Web UI for visual review. |
| Ignore Extension | Use x-zally-ignore extension in specs to selectively bypass rules. |
| Rule Severity Levels | Rules categorized as MUST, SHOULD, COULD, MAY, and HINT for graduated enforcement. |
| Linting Statistics | Track linting requests and aggregate review statistics over time. |

## Use Cases

| Name | Description |
|------|-------------|
| API Design Review | Review OpenAPI specs in pull requests to enforce design standards before merge. |
| API Governance | Enforce organizational API guidelines across teams via shared rule sets. |
| API Quality Gate | Block API releases that violate critical MUST rules in CI/CD pipelines. |
| Style Guide Enforcement | Encode an API style guide as executable rules and apply consistently. |

## Integrations

| Name | Description |
|------|-------------|
| GitHub Actions | Run Zally linting in GitHub Actions workflows on PRs. |
| Spectral | Translate Zally rule sets to Spectral rulesets for OpenAPI 3 alignment. |
| Zalando RESTful API Guidelines | Default rule set ships with rules from Zalando's public API guidelines. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [zally-api.yml](openapi/zally-api.yml)

### JSON Schema

- [zally-api-linting-request-schema.json](json-schema/zally-api-linting-request-schema.json)
- [zally-api-linting-response-schema.json](json-schema/zally-api-linting-response-schema.json)
- [zally-api-review-statistics-response-schema.json](json-schema/zally-api-review-statistics-response-schema.json)
- [zally-api-rule-schema.json](json-schema/zally-api-rule-schema.json)
- [zally-api-rule-type-schema.json](json-schema/zally-api-rule-type-schema.json)
- [zally-api-supported-rules-response-schema.json](json-schema/zally-api-supported-rules-response-schema.json)
- [zally-api-violation-schema.json](json-schema/zally-api-violation-schema.json)
- [zally-api-violations-count-schema.json](json-schema/zally-api-violations-count-schema.json)

### JSON Structure

- [zally-api-linting-request-structure.json](json-structure/zally-api-linting-request-structure.json)
- [zally-api-linting-response-structure.json](json-structure/zally-api-linting-response-structure.json)
- [zally-api-review-statistics-response-structure.json](json-structure/zally-api-review-statistics-response-structure.json)
- [zally-api-rule-structure.json](json-structure/zally-api-rule-structure.json)
- [zally-api-rule-type-structure.json](json-structure/zally-api-rule-type-structure.json)
- [zally-api-supported-rules-response-structure.json](json-structure/zally-api-supported-rules-response-structure.json)
- [zally-api-violation-structure.json](json-structure/zally-api-violation-structure.json)
- [zally-api-violations-count-structure.json](json-structure/zally-api-violations-count-structure.json)

### JSON-LD

- [zally-context.jsonld](json-ld/zally-context.jsonld)

### Examples

- [zally-api-linting-request-example.json](examples/zally-api-linting-request-example.json)
- [zally-api-linting-response-example.json](examples/zally-api-linting-response-example.json)
- [zally-api-review-statistics-response-example.json](examples/zally-api-review-statistics-response-example.json)
- [zally-api-rule-example.json](examples/zally-api-rule-example.json)
- [zally-api-rule-type-example.json](examples/zally-api-rule-type-example.json)
- [zally-api-supported-rules-response-example.json](examples/zally-api-supported-rules-response-example.json)
- [zally-api-violation-example.json](examples/zally-api-violation-example.json)
- [zally-api-violations-count-example.json](examples/zally-api-violations-count-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Zally - Zalando's API Linter](capabilities/shared/zally-api.yaml) — 4 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Zally Workflow](capabilities/zally-workflow.yaml) | 1 | 4 | Developer |

## Vocabulary

- [Zally Vocabulary](vocabulary/zally-vocabulary.yml) — Unified taxonomy mapping 3 resources, 2 actions, 1 workflows, and 1 personas

## Rules

- [zally-rules.yml](rules/zally-rules.yml) — 18 rules enforcing Zally API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
