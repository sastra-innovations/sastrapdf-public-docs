# Semantic Search and Retrieval

Semantic search and retrieval help users find relevant documents or passages by meaning rather than exact keyword match. These features support document intelligence and knowledge workflows when access boundaries are enforced.

## Capabilities

| Capability | Status | Notes |
| --- | --- | --- |
| Semantic search | Implemented; validation pending | Retrieves relevant documents or passages from permitted content. |
| Cross-document retrieval | Implemented; validation pending | Searches across a workspace or collection when permitted. |
| In-document text search | Implemented | Supports exact or text-layer search as a document operation. |

## Permission Scope

Search results should be scoped to the user's authorized documents, workspace and tenant. MedhaOS owns permission and tenant-isolation controls when integrated.

## Limitations

Relevance depends on indexed content, OCR quality, document structure and access controls. Public documentation does not disclose embedding configurations, ranking algorithms or index schemas.
