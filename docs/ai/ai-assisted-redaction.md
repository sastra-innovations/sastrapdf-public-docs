# AI-Assisted Redaction

AI-assisted redaction helps identify candidate sensitive content and prepare reviewable redaction marks. Final decisions and final output verification remain human responsibilities.

## Capabilities

| Capability | Status | Notes |
| --- | --- | --- |
| Sensitive-data identification | Implemented; validation pending | Suggests content that may require review. |
| AI-assisted redaction | Implemented; validation pending | Converts suggestions into reviewable redaction candidates. |
| Manual redaction | Implemented; validation pending | Applies selected redactions as a document operation. |

## Governance Boundary

SastraPDF performs redaction operations. Medha may assist with context when integrated. MedhaOS governs identity, policy, approval and audit controls for sensitive actions when integrated.

## Limitations

The product does not claim complete sensitive-data detection, assured prevention of disclosure or automatic legal compliance. Final redacted output must be reviewed.
