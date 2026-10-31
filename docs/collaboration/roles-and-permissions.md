# Roles and Permissions

Roles and permissions determine who can view, comment, edit, assign, approve or export documents. SastraPDF includes role-aware collaboration surfaces. Identity owns principal and assurance, Accounts owns organisation/workspace membership, Tenancy owns placement, Action Access owns the current may-act decision, Policy owns applicable role/profile rules, and MedhaOS governs controlled execution when integrated.

## Capability Status

| Capability | Status | Notes |
| --- | --- | --- |
| Shared workspace membership | Implemented; validation pending | Supports member-based document collaboration. |
| Role-based editing permissions | Implemented; validation pending | Requires enterprise validation for specific role models. |
| Reviewer assignment | Implemented; validation pending | Assigns document review tasks. |
| File sharing permissions | Implemented; validation pending | Scopes access to shared documents or collections. |
| Tenant-aware collaboration | Implemented; validation pending | Depends on deployment and MedhaOS governance validation. |

## Product Boundary

SastraPDF composes document collaboration behaviour without replacing the named service owners. MedhaOS governs controlled execution; Decision owns approval disposition and Audit owns platform proof when those effects are required.

## Limitations

This page does not claim validation in regulated operating environments, absolute tenant isolation or certification. Specific enterprise role models require implementation review and validation.
