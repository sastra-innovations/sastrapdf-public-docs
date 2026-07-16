# Batch Processing

Batch processing helps users apply repeatable document operations to multiple files. It is useful for conversion, optimization, OCR, extraction, validation and workflow pipelines when controls are defined.

## Verified Batch-Oriented Capabilities

| Capability | Status | Notes |
| --- | --- | --- |
| Batch conversion | Implemented; validation pending | Converts multiple supported files through one workflow. |
| OCR searchable PDF | Implemented; validation pending | Can be used in batch-oriented workflows when configured. |
| Compress PDF | Implemented | Can be applied across multiple files. |
| Optimize PDF | Implemented | Supports repeatable optimization workflows. |
| Sanitize PDF | Implemented; validation pending | Requires policy and output review. |
| Text extraction | Implemented | Supports downstream indexing and processing. |
| Validation profile or preflight check | Implemented; validation pending | Supports repeatable quality review. |
| Scan cleanup | Implemented; validation pending | Can support repeatable scanned-document cleanup. |
| PDF/X preflight | Implemented; validation pending | Can be used in repeatable print-preflight workflows. |

## Operational Considerations

Batch workflows require job status, error handling, retry behavior, file permissions and output ownership. Public documentation does not expose queue design, internal job orchestration, private worker topology or retry internals.

Related page: [workflow automation](workflow-automation.md).
