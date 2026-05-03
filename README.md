# Texas Instruments

Texas Instruments is an American technology company that designs and manufactures semiconductors and integrated circuits for industrial, automotive, personal electronics, and enterprise systems markets. TI provides a developer API portal at api-portal.ti.com offering Store APIs for inventory, ordering, and shipment tracking, as well as Product Information APIs for parametric data and quality certifications.

**Website:** https://www.texas-instruments.com
**Developer Portal:** https://api-portal.ti.com/

## APIs

### [Texas Instruments Store API](https://www.ti.com/developer-api/store-api/getting-started.html)
Enterprise ordering and inventory API. Real-time inventory/pricing, order creation, ASN shipment tracking, and invoice retrieval. Base URL: `https://transact.ti.com/v2/store`

**Tags:** Inventory, Ordering, Semiconductors, Supply Chain

**Properties:**
- [Documentation](https://www.ti.com/developer-api/store-api/getting-started.html)
- [OpenAPI](openapi/texas-instruments-store-openapi.yml)
- [Portal](https://api-portal.ti.com/)

### [Texas Instruments Product Information API](https://www.ti.com/developer-api/product-information-api-suite/getting-started.html)
Product catalog, parametric data, quality, and reliability information. Two variants: standard (3,000/day) and orchestrated (1,500/day). Base URL: `https://transact.ti.com/v1`

**Tags:** Electronics, Product Data, Semiconductors

**Properties:**
- [Documentation](https://www.ti.com/developer-api/product-information-api-suite/getting-started.html)
- [OpenAPI](openapi/texas-instruments-product-information-openapi.yml)
- [Portal](https://api-portal.ti.com/)

## Artifacts

### OpenAPI Specifications

- [openapi/texas-instruments-store-openapi.yml](openapi/texas-instruments-store-openapi.yml) — TI Store API (inventory, orders, ASN, invoices)
- [openapi/texas-instruments-product-information-openapi.yml](openapi/texas-instruments-product-information-openapi.yml) — TI Product Information API

### Spectral Rules

- [rules/texas-instruments-rules.yml](rules/texas-instruments-rules.yml) — Spectral ruleset enforcing TI API conventions

### Naftiko Capabilities

**Shared Definitions:**
- [capabilities/shared/ti-store.yaml](capabilities/shared/ti-store.yaml) — TI Store API consumed definition
- [capabilities/shared/ti-product-information.yaml](capabilities/shared/ti-product-information.yaml) — TI Product Information API consumed definition

**Workflow Capabilities:**
- [capabilities/semiconductor-procurement.yaml](capabilities/semiconductor-procurement.yaml) — Unified semiconductor procurement workflow (7 MCP tools, REST on :8080)

### JSON Schema

- [json-schema/ti-product-schema.json](json-schema/ti-product-schema.json) — Schema for TI semiconductor products with pricing, parametric, and quality data

### JSON Structure

- [json-structure/ti-product-structure.json](json-structure/ti-product-structure.json) — TI API resource structure documentation

### JSON-LD Context

- [json-ld/texas-instruments-context.jsonld](json-ld/texas-instruments-context.jsonld) — Linked data context mapping TI vocabulary to schema.org

### Vocabulary

- [vocabulary/texas-instruments-vocabulary.yml](vocabulary/texas-instruments-vocabulary.yml) — TI domain vocabulary (15 terms covering products, ordering, compliance)

### Examples

- [examples/texas-instruments-store-get-product-example.json](examples/texas-instruments-store-get-product-example.json)
- [examples/texas-instruments-store-create-order-example.json](examples/texas-instruments-store-create-order-example.json)

## Common Properties

- [Website](https://www.texas-instruments.com)
- [Developer Portal](https://api-portal.ti.com/)
- [Documentation](https://www.ti.com/developer-api/overview.html)
- [Getting Started](https://api-portal.ti.com/store-api-getstarted)
- [Support](https://api-portal.ti.com/support)
- [FAQ](https://api-portal.ti.com/faq)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
