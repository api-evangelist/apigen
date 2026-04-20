# APIGen (apigen)
ApiGen is an open source PHP API documentation generator that automatically produces smart and simple documentation from PHP source code. It supports PHP 7.1+ including all PHP 8.3 features like enums, union types, readonly classes, and intersection types. Maintained by the ApiGen GitHub organization.

**URL:** [https://github.com/ApiGen/ApiGen](https://github.com/ApiGen/ApiGen)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Code, Documentation, Generation, Open Source, PHP

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-19

## APIs

### APIGen
ApiGen automatically builds API documentation from PHP source code with full support for PHP 7.1+ features.

**Human URL:** [https://github.com/ApiGen/ApiGen](https://github.com/ApiGen/ApiGen)

#### Tags:

 - Documentation, Generation, PHP

#### Properties

- [GitHubRepository](https://github.com/ApiGen/ApiGen)
- [SDK - Composer Package](https://packagist.org/packages/apigen/apigen)
- [OpenAPI](openapi/apigen-apigen-openapi.yml)
- [JSONSchema](json-schema/apigen-project-schema.json)
- [JSONSchema](json-schema/apigen-api-schema.json)
- [JSONSchema](json-schema/apigen-endpoint-schema.json)
- [JSONSchema](json-schema/apigen-deployment-schema.json)
- [JSON-LD](json-ld/apigen-context.jsonld)

## Common Properties

- [GitHubOrganization](https://github.com/ApiGen/ApiGen)
- [SDK](https://packagist.org/packages/apigen/apigen)
- [Docker](https://hub.docker.com/r/apigen/apigen)

## Features

| Name | Description |
|------|-------------|
| PHP Documentation Generation | Automatically generates API documentation from PHP source code with phpDoc support. |
| Modern PHP Support | Full support for PHP 7.1+ including typed properties, enums, union types, readonly classes, and PHP 8.3 features. |
| Advanced Type Systems | Supports intersection types, disjunctive normal form types, constructor property promotion, and all PHPStan-supported types. |
| Flexible Installation | Available via Docker, Phar binary, or Composer for flexible integration into any PHP project workflow. |
| Template-Based Output | Uses Latte templating for customizable documentation output with built-in CommonMark support. |

## Use Cases

| Name | Description |
|------|-------------|
| PHP Library Documentation | Generate comprehensive API reference documentation for PHP libraries and packages. |
| CI/CD Documentation Pipeline | Automate API documentation generation as part of continuous integration workflows. |
| Open Source Project Docs | Create and maintain documentation for open source PHP projects. |

## Integrations

| Name | Description |
|------|-------------|
| Composer | Available as a Composer package for easy installation in PHP projects. |
| Docker | Official Docker image for containerized documentation generation. |
| GitHub Actions | Can be integrated into GitHub Actions workflows for automated documentation. |
| PHPStan | Built on phpstan/phpdoc-parser for comprehensive type system support. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [APIGen API](openapi/apigen-apigen-openapi.yml)

### JSON Schema

- [apigen-project-schema.json](json-schema/apigen-project-schema.json)
- [apigen-api-schema.json](json-schema/apigen-api-schema.json)
- [apigen-endpoint-schema.json](json-schema/apigen-endpoint-schema.json)
- [apigen-deployment-schema.json](json-schema/apigen-deployment-schema.json)

### JSON Structure

- [apigen-project-structure.json](json-structure/apigen-project-structure.json)
- [apigen-api-structure.json](json-structure/apigen-api-structure.json)
- [apigen-endpoint-structure.json](json-structure/apigen-endpoint-structure.json)
- [apigen-deployment-structure.json](json-structure/apigen-deployment-structure.json)

### JSON-LD

- [apigen-context.jsonld](json-ld/apigen-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [APIGen API](capabilities/shared/apigen.yaml) — 5 operations for project, API, and deployment management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [API Documentation Generation](capabilities/api-documentation-generation.yaml) | APIGen API | 3 | PHP Developer, Technical Writer |

## Vocabulary

- [APIGen Vocabulary](vocabulary/apigen-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 5 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [apigen-spectral-rules.yml](rules/apigen-spectral-rules.yml) — 7 rules across 5 categories enforcing APIGen API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
