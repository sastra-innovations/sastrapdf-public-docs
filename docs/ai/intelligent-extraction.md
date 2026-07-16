# Intelligent Extraction

Intelligent extraction turns document content into fields, tables, structured values and reviewable evidence. It is intended to support document intelligence workflows, not to eliminate human validation.

## Capabilities

| Capability | Status | Review expectation |
| --- | --- | --- |
| Structured data extraction | Implemented; validation pending | Verify extracted values before business use. |
| Table and field extraction | Implemented; validation pending | Correct complex tables where needed. |
| Form-field detection | Implemented; validation pending | Approve suggested fields before publication. |
| Document information extraction | Implemented; validation pending | Review key fields in critical workflows. |

## Product Boundary

SastraPDF performs extraction from documents. Medha may reason over extracted context when integrated. MedhaOS governs permission, policy and approval boundaries when extracted data triggers sensitive actions.
