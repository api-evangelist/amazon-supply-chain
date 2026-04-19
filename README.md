# Amazon Supply Chain (amazon-supply-chain)

AWS Supply Chain is a cloud-based application that works with your existing enterprise resource planning (ERP) and supply chain management systems to help you manage supply chain risks. It provides ML-powered insights and recommended actions to help mitigate supply chain disruptions.

**URL:** [https://aws.amazon.com/supply-chain/](https://aws.amazon.com/supply-chain/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, ERP Integration, Logistics, Machine Learning, Supply Chain

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### AWS Supply Chain API

The AWS Supply Chain API provides programmatic access to create and manage supply chain instances, data lakes, data integrations, and bills of materials for supply chain visibility and risk management.

**Human URL:** [https://aws.amazon.com/supply-chain/](https://aws.amazon.com/supply-chain/)

#### Tags:

 - Logistics, Machine Learning, Supply Chain

#### Properties

- [Documentation](https://docs.aws.amazon.com/aws-supply-chain/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-supply-chain.yaml)
- [GettingStarted](https://aws.amazon.com/supply-chain/)
- [Pricing](https://aws.amazon.com/supply-chain/pricing/)
- [FAQ](https://aws.amazon.com/supply-chain/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/supply-chain/)
- [Documentation](https://docs.aws.amazon.com/aws-supply-chain/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/industries/supply-chain/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/scn/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| ML-Powered Insights | Machine learning models provide risk visibility and recommended actions for supply chain disruptions. |
| ERP Integration | Connects with existing ERP and supply chain management systems via data integration flows. |
| Data Lake | Centralized data lake for supply chain data with namespace and dataset management. |
| Bill of Materials Import | Import bill of materials data from S3 for inventory and component tracking. |
| Data Integration Events | Event-driven data ingestion for real-time supply chain data updates. |
| Multi-instance | Create and manage multiple supply chain instances for different business units. |

## Use Cases

| Name | Description |
|------|-------------|
| Supply Chain Risk Management | Identify and mitigate supply chain disruptions with ML-powered risk insights. |
| Inventory Visibility | Unified view of inventory across suppliers, warehouses, and distribution centers. |
| ERP Data Integration | Integrate ERP data with AWS Supply Chain for unified supply chain visibility. |
| Demand Forecasting | Use ML models to forecast demand and optimize inventory levels. |

## Integrations

| Name | Description |
|------|-------------|
| SAP ERP | Connect SAP ERP data to AWS Supply Chain via data integration flows. |
| Oracle ERP | Integrate Oracle ERP supply chain data for unified visibility. |
| Amazon S3 | Import and export supply chain data via S3 for batch processing. |
| Amazon EventBridge | Send supply chain events to EventBridge for downstream processing. |
| AWS IoT | Integrate IoT sensor data for real-time supply chain monitoring. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-supply-chain.yaml](openapi/amazon-supply-chain.yaml)

### JSON Schema

- [amazon-supply-chain-bill-of-materials-import-job-schema.json](json-schema/amazon-supply-chain-bill-of-materials-import-job-schema.json)
- [amazon-supply-chain-data-integration-event-schema.json](json-schema/amazon-supply-chain-data-integration-event-schema.json)
- [amazon-supply-chain-data-integration-flow-schema.json](json-schema/amazon-supply-chain-data-integration-flow-schema.json)
- [amazon-supply-chain-data-lake-dataset-schema.json](json-schema/amazon-supply-chain-data-lake-dataset-schema.json)
- [amazon-supply-chain-data-lake-namespace-schema.json](json-schema/amazon-supply-chain-data-lake-namespace-schema.json)
- ... and 1 more

### JSON Structure

- [amazon-supply-chain-bill-of-materials-import-job-structure.json](json-structure/amazon-supply-chain-bill-of-materials-import-job-structure.json)
- [amazon-supply-chain-data-integration-event-structure.json](json-structure/amazon-supply-chain-data-integration-event-structure.json)
- [amazon-supply-chain-data-integration-flow-structure.json](json-structure/amazon-supply-chain-data-integration-flow-structure.json)
- [amazon-supply-chain-data-lake-dataset-structure.json](json-structure/amazon-supply-chain-data-lake-dataset-structure.json)
- [amazon-supply-chain-data-lake-namespace-structure.json](json-structure/amazon-supply-chain-data-lake-namespace-structure.json)

### JSON-LD

- [amazon-supply-chain-context.jsonld](json-ld/amazon-supply-chain-context.jsonld)

### Examples

- [amazon-supply-chain-bill-of-materials-import-job-example.json](examples/amazon-supply-chain-bill-of-materials-import-job-example.json)
- [amazon-supply-chain-data-integration-event-example.json](examples/amazon-supply-chain-data-integration-event-example.json)
- [amazon-supply-chain-data-integration-flow-example.json](examples/amazon-supply-chain-data-integration-flow-example.json)
- [amazon-supply-chain-data-lake-dataset-example.json](examples/amazon-supply-chain-data-lake-dataset-example.json)
- [amazon-supply-chain-data-lake-namespace-example.json](examples/amazon-supply-chain-data-lake-namespace-example.json)
- ... and 1 more

## Capabilities

Naftiko capabilities organized as shared per-API definitions.

### Shared Per-API Definitions

- [amazon-supply-chain.yaml](capabilities/shared/amazon-supply-chain.yaml) — AWS Supply Chain operations for supply chain management

## Vocabulary

- [Amazon Supply Chain Vocabulary](vocabulary/amazon-supply-chain-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 6 actions, 1 workflow, and 2 personas

## Rules

- [Amazon Supply Chain Spectral Rules](rules/amazon-supply-chain-spectral-rules.yml) — 18 rules enforcing AWS Supply Chain API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
