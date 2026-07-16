# Forms and Structured Content

SastraPDF supports form creation, field detection, validation, tab order, templates and submission review. These capabilities help teams build document workflows around structured inputs while keeping publication and approval boundaries explicit.

## Verified Capabilities

| Capability | Status | Notes |
| --- | --- | --- |
| Create or edit form fields | Implemented | Builds fillable PDF forms. |
| Automatic form-field detection | Implemented; validation pending | Suggests fields from document layout and requires review. |
| Form validation | Implemented; validation pending | Validates designed or submitted values. |
| Field calculation rules | Implemented; validation pending | Supports calculated form values with workflow validation needs. |
| Field mapping | Implemented; validation pending | Maps form fields to structured records. |
| Tab order editing | Implemented; validation pending | Controls keyboard navigation order. |
| Form template creation | Implemented; validation pending | Reuses form structures. |
| Form appearance management | Implemented; validation pending | Controls field presentation and appearance. |
| XFA detection and conversion | Implemented; validation pending | Handles XFA-bearing documents where supported. |
| Form action and event inspection | Implemented; validation pending | Reviews form actions or event behavior. |
| Form publishing | Implemented; validation pending | Prepares a form for use under workflow policy. |
| Form submission review | Implemented; validation pending | Reviews received submissions and exports where configured. |

## Boundaries

SastraPDF owns document form design and form workflow execution. External enterprise systems remain authoritative for records created from those forms. MedhaOS governs identity, permissions and approvals when integrated.
