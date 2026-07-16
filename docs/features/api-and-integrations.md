# API and Integrations

SastraPDF supports API and integration patterns for embedding document operations into enterprise workflows. Public documentation describes integration surfaces conceptually and does not publish internal endpoint paths, credentials, private hostnames or implementation configuration.

## Verified Capabilities

| Capability | Status | Notes |
| --- | --- | --- |
| API access | Implemented; validation pending | Enables authorized document and workflow operations. |
| Connectors and integrations | Implemented; validation pending | Supports connected document import, export or workflow updates where configured. |
| External-source import | Implemented; validation pending | Brings documents from authorized external sources. |
| Workflow pipelines | Implemented; validation pending | Coordinates repeatable document processes. |
| Batch conversion | Implemented; validation pending | Supports multi-file conversion workflows. |

## Integration Boundary

SastraPDF performs document operations and document workflow execution. External enterprise systems remain authoritative for records, approvals, transactions and business actions unless explicitly integrated under governance controls.

## Public Documentation Boundary

This repository does not document API endpoint paths, authentication secrets, schema internals, storage models, SDK availability claims or connector implementation details. Public-facing SDK or API availability beyond conceptual integration requires a separate publication decision.
