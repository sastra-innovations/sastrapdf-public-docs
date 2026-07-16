# SastraPDF Public Documentation

SastraPDF is Sastra Innovations' document intelligence, collaborative editing and workflow platform for document-heavy enterprise processes.

This repository provides public feature documentation for evaluators, users, architects, design partners and search engines. It explains document operations, AI-assisted capabilities, collaborative review workflows and governance boundaries without exposing source code, internal architecture, proprietary algorithms, private endpoints or security-sensitive implementation details.

## Product Role

SastraPDF owns document ingestion, viewing, editing, extraction, transformation, document operations, collaboration and document-workflow execution. It can work with [Medha](https://github.com/sastra-innovations/medha-public-docs) for reasoning, retrieval, context and recommendations, and with [MedhaOS](https://github.com/sastra-innovations/medha-os-public-docs) for identity, RBAC, tenant isolation, policies, approvals, auditability, observability and controlled execution.

External enterprise systems remain authoritative for their own records and business actions.

## Feature Catalogue

The current public catalogue identifies **105 distinct document operations** from verified private-alpha evidence. The count includes user-facing document operations with `Implemented` or `Implemented; validation pending` status. It excludes aliases, duplicate API/UI access paths, AI-only capabilities, collaboration-only capabilities, workflow/platform controls and planned items.

See [Feature Catalogue](docs/features/feature-catalogue.md) for the complete counting method and status model.

## Documentation

### Feature Documentation

- [Feature documentation overview](docs/features/README.md)
- [Feature catalogue](docs/features/feature-catalogue.md)
- [Document ingestion](docs/features/document-ingestion.md)
- [Viewing and navigation](docs/features/viewing-and-navigation.md)
- [Page organization](docs/features/page-organization.md)
- [Document editing](docs/features/document-editing.md)
- [Annotations and review](docs/features/annotations-and-review.md)
- [Conversion and export](docs/features/conversion-and-export.md)
- [Extraction and OCR](docs/features/extraction-and-ocr.md)
- [Forms and structured content](docs/features/forms-and-structured-content.md)
- [Security and protection](docs/features/security-and-protection.md)
- [Redaction and sensitive data](docs/features/redaction-and-sensitive-data.md)
- [Comparison and quality review](docs/features/comparison-and-quality-review.md)
- [Batch processing](docs/features/batch-processing.md)
- [Workflow automation](docs/features/workflow-automation.md)
- [API and integrations](docs/features/api-and-integrations.md)

### AI Documentation

- [AI documentation overview](docs/ai/README.md)
- [AI feature catalogue](docs/ai/ai-feature-catalogue.md)
- [Document understanding](docs/ai/document-understanding.md)
- [Intelligent extraction](docs/ai/intelligent-extraction.md)
- [Document classification](docs/ai/document-classification.md)
- [Summarization and question answering](docs/ai/summarization-and-question-answering.md)
- [Semantic search and retrieval](docs/ai/semantic-search-and-retrieval.md)
- [Document comparison and review](docs/ai/document-comparison-and-review.md)
- [AI-assisted redaction](docs/ai/ai-assisted-redaction.md)
- [AI-assisted workflows](docs/ai/ai-assisted-workflows.md)
- [Medha integration](docs/ai/medha-integration.md)
- [Governance with MedhaOS](docs/ai/governance-with-medhaos.md)

### Collaboration Documentation

- [Collaboration overview](docs/collaboration/README.md)
- [Collaborative editor](docs/collaboration/collaborative-editor.md)
- [Comments and review](docs/collaboration/comments-and-review.md)
- [Roles and permissions](docs/collaboration/roles-and-permissions.md)
- [Approvals and accountability](docs/collaboration/approvals-and-accountability.md)
- [Versioning and change history](docs/collaboration/versioning-and-change-history.md)

## Status Model

Every documented feature uses one of these statuses:

- `Implemented` - present in the current private-alpha product.
- `Implemented; validation pending` - built but requiring additional workflow or enterprise validation.
- `Beta preparation` - intended for the resumed beta but not currently presented as validated.
- `Planned` - not currently implemented and clearly separated from available capabilities.
- `Founder verification required` - evidence is incomplete or inconsistent.

## Official Links

- [Sastra Innovations](https://sastra.io)
- [SastraPDF](https://sastra.io/products/sastrapdf)
- [Medha](https://sastra.io/products/medha)
- [MedhaOS](https://sastra.io/products/medhaos)
- [Platform architecture](https://sastra.io/platform/architecture)
- [Umbrella documentation](https://github.com/sastra-innovations/sastra-public-docs)

## Disclosure Boundary

This repository documents public product capabilities and reference-safe feature boundaries. It deliberately excludes source code, internal infrastructure topology, credentials, private hostnames, ports, proprietary schemas, internal endpoint paths, policy-engine internals, Edge Guard internals and exploitable security configuration.

No open-source software license is included. This repository documents a proprietary Sastra Innovations product unless a documentation license is approved later.

## Identity Clarification

Sastra Innovations (OPC) Private Limited is an independent software and enterprise AI company based in Hyderabad, India. It is not affiliated with SASTRA Deemed University or Sastra Robotics.

© 2026 Sastra Innovations (OPC) Private Limited. All rights reserved.
