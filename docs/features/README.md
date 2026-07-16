# SastraPDF Feature Documentation

SastraPDF is documented here as a document intelligence, collaborative editing and governed workflow platform, not as a basic PDF utility. These pages describe public-safe capability areas verified from current product evidence.

## Feature Sections

- [Feature catalogue](feature-catalogue.md)
- [Document ingestion](document-ingestion.md)
- [Viewing and navigation](viewing-and-navigation.md)
- [Page organization](page-organization.md)
- [Document editing](document-editing.md)
- [Annotations and review](annotations-and-review.md)
- [Conversion and export](conversion-and-export.md)
- [Extraction and OCR](extraction-and-ocr.md)
- [Forms and structured content](forms-and-structured-content.md)
- [Security and protection](security-and-protection.md)
- [Redaction and sensitive data](redaction-and-sensitive-data.md)
- [Comparison and quality review](comparison-and-quality-review.md)
- [Batch processing](batch-processing.md)
- [Workflow automation](workflow-automation.md)
- [API and integrations](api-and-integrations.md)

## Counting Method

The operation count in this repository is calculated from [Feature Catalogue](feature-catalogue.md). A row is counted as a document operation only when it is a distinct user-facing document operation and its status is `Implemented` or `Implemented; validation pending`.

The count does not include aliases, input formats, duplicate UI/API access paths, AI-only capabilities, collaboration-only capabilities, platform administration or planned capabilities.

## Product Boundaries

- SastraPDF owns document ingestion, viewing, editing, extraction, transformation, collaboration and document-workflow execution.
- Medha owns reasoning, retrieval, context, model selection and intelligent recommendations.
- MedhaOS owns identity, RBAC, tenant isolation, policies, model/provider boundaries, approvals, auditability and controlled execution.
- External enterprise systems remain authoritative for records and business actions.

## Status Use

Feature status is intentionally conservative. A feature marked `Implemented; validation pending` should not be read as a completed enterprise deployment or validation in regulated operating environments.
