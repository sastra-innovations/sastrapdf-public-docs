# Document Ingestion

SastraPDF supports document intake patterns for individual files, large uploads, external-source imports and web-content capture. These ingestion capabilities are the entry point for viewing, editing, extraction, review and workflow automation.

## Verified Capabilities

| Capability | Status | Notes |
| --- | --- | --- |
| PDF upload and import | Implemented | Brings supported documents into a SastraPDF workspace. |
| Multipart upload | Implemented | Supports large-file upload flows without documenting upload internals. |
| External-source import | Implemented; validation pending | Connector-specific behavior depends on the deployment and configured authorization. |
| URL or HTML capture to PDF | Implemented; validation pending | Useful for workflow capture, with review required for dynamic or restricted content. |
| Password-protected PDF unlock | Implemented | Requires an authorized user-supplied password and does not bypass document-owner restrictions. |

See the [feature catalogue](feature-catalogue.md) for the required fields for each operation.

## Governance Considerations

Ingestion should be scoped by file ownership, workspace membership and tenant boundaries. When MedhaOS is integrated, identity, RBAC, policy and audit controls belong to MedhaOS; SastraPDF performs the document intake and processing operation.

## Limitations

Public documentation does not describe storage internals, upload protocols, connector endpoint paths, credential handling or private infrastructure details. Enterprise storage, connector and tenant-boundary validation remains deployment-specific.
