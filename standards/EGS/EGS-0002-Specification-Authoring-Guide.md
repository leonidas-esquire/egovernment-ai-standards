# EGS-0002 — Specification Authoring Guide

| Field | Value |
|-------|-------|
| Standard | EGS-0002 |
| Title | Specification Authoring Guide |
| Version | 0.1.0 |
| Status | Draft |
| Steward | eGovernment.ai Standards Program |
| License | Creative Commons Attribution 4.0 International (CC BY 4.0) |

---

# Abstract

This document defines the required structure, formatting, terminology, and editorial conventions for all specifications published by the eGovernment.ai Standards Program (EGS).

The objective is to ensure consistency, readability, interoperability, and long-term maintainability across all standards.

---

# 1. Purpose

Every specification SHALL follow a common organizational structure.

A consistent structure enables readers, implementers, reviewers, and software tools to navigate specifications predictably.

---

# 2. Standard Document Structure

Every normative specification SHOULD contain the following sections in this order:

1. Title Page
2. Document Metadata
3. Abstract
4. Purpose
5. Scope
6. Definitions
7. Normative Language
8. Requirements
9. Conformance
10. Security Considerations
11. Accessibility Considerations
12. Privacy Considerations
13. Implementation Notes
14. Examples
15. References
16. Version History
17. Appendices (optional)

---

# 3. Metadata Requirements

Every specification SHALL include:

- Standard Identifier
- Title
- Version
- Status
- Steward
- License
- Repository
- Publication Date
- Last Updated

---

# 4. Normative Language

Specifications SHALL use the following terms as defined by RFC 2119:

- MUST
- MUST NOT
- SHALL
- SHALL NOT
- SHOULD
- SHOULD NOT
- MAY
- RECOMMENDED

Normative requirements SHALL be clearly distinguishable from informative guidance.

---

# 5. Document Status

Each specification SHALL declare one of the following lifecycle states:

- Draft
- Review
- Candidate
- Approved
- Deprecated
- Archived

---

# 6. Versioning

Specifications SHALL follow Semantic Versioning:

- MAJOR — Breaking changes
- MINOR — Backward-compatible additions
- PATCH — Editorial corrections and clarifications

---

# 7. Cross References

Specifications SHOULD reference related standards using their permanent identifiers.

Examples:

- EGS-0000
- CDF-0001
- OKF-0000
- LEONIDAS-0000

Hyperlinks SHOULD be provided whenever practical.

---

# 8. Examples

Every technical specification SHOULD include practical examples illustrating compliant implementations.

Examples are informative unless explicitly identified as normative.

---

# 9. Accessibility

Specifications SHALL be written using accessible formatting.

Authors SHOULD:

- Use descriptive headings.
- Use semantic lists.
- Avoid color-dependent meaning.
- Prefer plain language.
- Include alternative text for diagrams when published electronically.

---

# 10. References

References SHOULD distinguish between:

- Normative References
- Informative References

---

# 11. Change History

Every specification SHALL maintain a version history documenting significant revisions.

---

# 12. Editorial Style

Specifications SHOULD:

- Prefer active voice.
- Use concise language.
- Define terms before use.
- Avoid unnecessary jargon.
- Be understandable by technical and non-technical audiences.

---

# 13. Future Automation

Specifications SHOULD be authored in a format suitable for automated validation, publication, indexing, and cross-referencing.

The eGovernment.ai Standards Program intends to support automated generation of HTML, PDF, Markdown, searchable documentation, and other publication formats from a single authoritative source.

