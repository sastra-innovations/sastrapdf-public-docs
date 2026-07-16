# AI-Assisted Workflows

AI-assisted workflows use document context to recommend, summarize or prepare next steps. They are documented as assistive workflows, not unrestricted autonomous processing.

## Capabilities

| Capability | Status | Notes |
| --- | --- | --- |
| Workflow recommendation | Beta preparation | Recommends next steps from document and workflow context. |
| Medha-powered reasoning | Beta preparation | Uses Medha for reasoning over permission-scoped document context when integrated. |
| MedhaOS-governed AI action | Beta preparation | Applies governance boundaries to AI-assisted actions when integrated. |
| Workflow pipelines | Implemented; validation pending | Coordinates repeatable document processing. |

## Controlled-Execution Principle

Medha may recommend or propose a document action. MedhaOS evaluates identity, role, tenant, policy and approval requirements. SastraPDF or a connected system performs the actual document operation only when permitted.

## Limitations

This repository does not claim unreviewed autonomous document processing, validation in regulated operating environments or unrestricted AI agents.
