# Document Editing

SastraPDF includes document editing capabilities for text, images, visual objects, links, layers, tables, metadata and page presentation. These features are intended for practical enterprise document preparation and review, not only simple PDF utility actions.

## Verified Capabilities

| Capability | Status | Notes |
| --- | --- | --- |
| Insert text | Implemented | Adds text to a document. |
| Edit text | Implemented | Modifies existing text where the document permits reliable editing. |
| Find and replace text | Implemented; validation pending | Supports repeated text replacement with human review. |
| Typography and font controls | Implemented; validation pending | Adjusts styling where font support allows. |
| Add image | Implemented | Places an image in a document. |
| Replace image | Implemented | Swaps an existing image. |
| Image or object transform | Implemented; validation pending | Moves, resizes or rotates selected page objects. |
| Vector or object editing | Implemented; validation pending | Supports advanced page-object edits with validation needs. |
| Link management | Implemented; validation pending | Inspects and edits document links. |
| Layer management | Implemented; validation pending | Manages optional content groups or layers. |
| Table editing | Implemented; validation pending | Creates or adjusts table structures. |
| XMP and document info synchronization | Implemented; validation pending | Aligns metadata stores. |
| Initial view preferences | Implemented; validation pending | Sets viewer-opening behavior where supported. |
| Color profile and output-intent management | Implemented; validation pending | Supports output-oriented color settings. |
| Transparency flattening | Implemented; validation pending | Prepares transparency-heavy content for compatibility workflows. |
| Font analysis | Implemented; validation pending | Reviews font resources and text behavior. |
| Structure tree and role-map inspection | Implemented; validation pending | Reviews tagged PDF structure. |
| Template and master page management | Implemented; validation pending | Supports reusable page structures. |

## Product Boundary

SastraPDF performs document editing. Medha may assist with recommendations or interpretation when integrated, and MedhaOS may govern whether a sensitive edit requires approval. External systems remain authoritative for business records.

## Limitations

PDFs are not always authored for reversible editing. Complex embedded fonts, vector artwork, scanned pages, signatures and layered content can require visual review or additional validation after edits.
