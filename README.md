# Zally (zally)

Zally is an open source API linter from Zalando that validates OpenAPI 2 and 3 specifications against configurable rule sets for API design consistency. It exposes a REST API, command-line interface, and web UI for checking API designs against Zalando's RESTful API Guidelines or custom rule sets.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- API Design
- API Linting
- API Quality
- Open Source
- OpenAPI
- Zalando

## Timestamps

- **Created:** 2026-03-25
- **Modified:** 2026-05-19

## APIs

### Zally API

The Zally REST API performs linting of OpenAPI specifications against configurable rule sets. It returns violations grouped by rule severity (MUST, SHOULD, COULD, MAY, HINT), tracks linting statistics, and lists supported rules. Authentication is via Bearer JWT.

- **Human URL:** [https://opensource.zalando.com/zally/](https://opensource.zalando.com/zally/)
- **Base URL:** `https://zally.on.inter.net`

#### Tags

- API Linting
- API Quality
- OpenAPI

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/openapi/zally-api.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://opensource.zalando.com/zally/)
- [API Reference](https://github.com/zalando/zally/blob/main/server/zally-server/src/main/resources/api/zally-api.yaml)
- [Authentication](https://github.com/zalando/zally/tree/main/server#authentication)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/json-schema/) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/json-structure/)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/json-ld/zally-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/examples/)
- [Postman Collection](collections/zally-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/zally-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://opensource.zalando.com/zally/)
- [Documentation](https://github.com/zalando/zally#readme)
- [GitHub Repository](https://github.com/zalando/zally)
- [GitHub Organization](https://github.com/zalando)
- [License](https://github.com/zalando/zally/blob/main/LICENSE)
- [Issues](https://github.com/zalando/zally/issues)
- [Changelog](https://github.com/zalando/zally/releases)
- [C L I](https://github.com/zalando/zally/tree/main/cli)
- [SDK](https://github.com/zalando/zally/tree/main/web-ui)
- [Specification](https://opensource.zalando.com/restful-api-guidelines/)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/rules/zally-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/vocabulary/zally-vocabulary.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
