# Tratta

Tratta is a debt collection and payment experience platform that provides REST APIs and webhooks for integrating payment plans, billing, customer session management, and collections workflows into existing tech stacks.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/tratta/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Billing, Collections, Payments, Debt Collection, Fintech

## Timestamps

- **Created:** 2025-02-24
- **Modified:** 2026-05-03

## APIs

### Tratta API
REST API for debt collection and payment platform. Manages debt accounts, payment plans, transactions, charges, customers, and webhooks.

**Human URL:** [https://docs.tratta.io/](https://docs.tratta.io/)

**Base URL:** `https://{org-uuid}.production.tratta.io/api/v1`

#### Tags

Billing, Collections, Payments, Debt Collection, Fintech

#### Properties

- [Documentation](https://docs.tratta.io/api.html)
- [OpenAPI](openapi/tratta-openapi.yml)
- [JSON Schema - Payment Plan](json-schema/tratta-payment-plan-schema.json)
- [JSON Schema - Debt Account](json-schema/tratta-debt-account-schema.json)
- [JSON Structure](json-structure/tratta-payment-plan-structure.json)
- [JSON-LD Context](json-ld/tratta-context.jsonld)
- [Spectral Rules](rules/tratta-rules.yml)
- [Naftiko Capabilities](capabilities/debt-collection-workflow.yaml)
- [Vocabulary](vocabulary/tratta-vocabulary.yml)

## OpenAPI Specifications

| API | File |
|---|---|
| Tratta API | [openapi/tratta-openapi.yml](openapi/tratta-openapi.yml) |

## Capabilities

### Workflow Capabilities

| Workflow | Description |
|---|---|
| [Debt Collection Workflow](capabilities/debt-collection-workflow.yaml) | Full lifecycle collections: debt accounts, payment plans, charges, sessions, webhooks |

### Shared Definitions

| API | File |
|---|---|
| [Tratta](capabilities/shared/tratta.yaml) | Core Tratta API consumed definitions |

## Examples

| Example | Description |
|---|---|
| [Create Payment Plan](examples/tratta-create-payment-plan-example.json) | Create a monthly payment plan for a debt account |
| [Create Customer Session](examples/tratta-create-customer-session-example.json) | Generate a magic link for customer portal access |

## Rules

| Ruleset | Description |
|---|---|
| [tratta-rules.yml](rules/tratta-rules.yml) | Spectral ruleset for Tratta API conventions |

## JSON Schemas

| Schema | Description |
|---|---|
| [tratta-payment-plan-schema.json](json-schema/tratta-payment-plan-schema.json) | Payment plan |
| [tratta-debt-account-schema.json](json-schema/tratta-debt-account-schema.json) | Debt account |

## JSON Structures

| Structure | Description |
|---|---|
| [tratta-payment-plan-structure.json](json-structure/tratta-payment-plan-structure.json) | Payment plan fields |

## JSON-LD

| Context | Description |
|---|---|
| [tratta-context.jsonld](json-ld/tratta-context.jsonld) | Linked data context for debt collection |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [tratta-vocabulary.yml](vocabulary/tratta-vocabulary.yml) | Debt collection and payments domain vocabulary |

## Common Properties

- [Website](https://www.tratta.io/)
- [Documentation](https://docs.tratta.io/)
- [Sign Up](https://www.tratta.io/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
