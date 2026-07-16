# Collaborative Editor

The SastraPDF collaborative editor combines document viewing, editing, annotation, comments, review tasks, version context and workspace organization. It is a core product area, not a minor utility feature.

## Verified Capabilities

| Capability | Status | Notes |
| --- | --- | --- |
| Document and page editing | Implemented | Uses the document-editing and page-organization operations described in the feature catalogue. |
| Annotation | Implemented | Supports document review marks and note-style review. |
| Comments and replies | Implemented | Supports discussion threads around document context. |
| Shared review | Implemented; validation pending | Uses shared workspaces and review surfaces. |
| Reviewer assignment | Implemented; validation pending | Assigns review tasks in collaborative workflows. |
| Role-based editing permissions | Implemented; validation pending | Requires enterprise validation for specific tenant and role models. |
| Version history | Implemented; validation pending | Shows version context and change history. |
| Presence indicators | Founder verification required | UI-visible evidence is insufficient to claim implemented real-time cursor presence. |
| Concurrent editing | Founder verification required | Do not assume enterprise-validated real-time co-editing. |
| Conflict handling | Implemented; validation pending | Supported as a controlled workflow concept; enterprise validation required. |

## Editing Boundary

Collaborative editing should preserve document permissions, reviewer accountability and output review. A shared editing surface does not automatically mean every user can make every edit.

Related pages: [roles and permissions](roles-and-permissions.md), [versioning and change history](versioning-and-change-history.md).
