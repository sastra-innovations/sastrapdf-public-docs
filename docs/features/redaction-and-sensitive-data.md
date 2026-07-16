# Redaction and Sensitive Data

SastraPDF includes manual redaction and sensitive-data redaction assistance for document workflows where disclosure control matters. These features require careful human review before a document is shared or published.

## Verified Capabilities

| Capability | Status | AI-assisted | Notes |
| --- | --- | --- | --- |
| Manual redaction | Implemented; validation pending | No | Applies selected redactions and exports a redacted document. |
| Sensitive-data redaction assistance | Implemented; validation pending | Yes | Suggests content that may require redaction. |
| Sanitize PDF | Implemented; validation pending | No | Removes unsafe or unwanted active content where supported. |
| Permission analysis | Implemented; validation pending | No | Helps inspect protection settings before sharing. |

## Human Review Requirement

AI-assisted redaction suggestions may be incomplete. Users must review both suggested marks and final redacted output, especially for legal, regulated, financial, HR, healthcare or customer data workflows.

## Product Boundary

SastraPDF performs the document redaction operation. Medha may assist with reasoning over document context. MedhaOS governs policy, approval, audit and controlled execution boundaries when integrated.
