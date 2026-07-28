# CDF-0001 — Course Definition Framework Core Specification

| Field | Value |
|-------|-------|
| Standard | CDF-0001 |
| Title | Course Definition Framework Core Specification |
| Version | 0.1.0 |
| Status | Draft |
| Steward | eGovernment.ai Standards Program |
| License | Creative Commons Attribution 4.0 International (CC BY 4.0) |
| Repository | https://github.com/leonidas-esquire/egovernment-ai-standards |

---

# Abstract

This specification defines the normative object model of the Course Definition Framework (CDF).

It establishes the required structure, relationships, and minimum requirements for all CDF-compliant learning content.

All CDF implementations SHALL conform to this specification.

---

# 1. Scope

This specification defines:

- Course structure
- Learning object hierarchy
- Required metadata
- Object relationships
- Validation requirements
- Publishing independence

This specification does not define export formats or LMS-specific implementations.

---

# 2. Design Goals

CDF SHALL:

- Be platform independent.
- Be human readable.
- Be machine readable.
- Be version controlled.
- Be AI authorable.
- Be AI verifiable.
- Be exportable to multiple delivery systems.
- Support accessibility by design.
- Preserve authoritative citations.
- Support long-term interoperability.

---

# 3. Core Object Hierarchy

Every CDF learning package SHALL follow the hierarchy below.



---

# 4. Core Objects

CDF defines the following first-class objects.

## Course

Represents an entire educational experience.

A Course SHALL contain one or more Modules.

---

## Module

Represents a logical grouping of lessons.

A Module SHALL belong to exactly one Course.

---

## Lesson

Represents an instructional unit.

A Lesson SHALL belong to exactly one Module.

---

## Topic

Represents a specific instructional subject.

A Topic SHALL belong to exactly one Lesson.

---

## Learning Object

Represents an instructional component.

Examples include:

- Text
- Video
- Diagram
- Exercise
- Activity
- Demonstration
- Discussion
- Reading

---

## Assessment

Represents evidence that learning occurred.

Examples include:

- Quiz
- Assignment
- Practical Exercise
- Reflection
- Observation
- Peer Review

Every Assessment SHALL map to one or more Learning Objectives.

---

## Citation

Represents an authoritative supporting reference.

Citations SHOULD reference:

- OKF Knowledge Bundles
- Government publications
- Standards
- Regulations
- Policies
- Academic references

---

## Resource

Represents supplemental material.

Examples include:

- PDF
- Website
- Download
- Video
- Template
- Checklist
- Worksheet

---

# 5. Required Metadata

Every Course SHALL define:

- Identifier
- Title
- Version
- Description
- Language
- Author
- Steward
- License
- Created Date
- Last Updated
- Target Audience
- Estimated Duration
- Accessibility Statement

---

# 6. Learning Objectives

Every Lesson SHALL define one or more measurable Learning Objectives.

Learning Objectives SHOULD use observable verbs.

---

# 7. Assessment Alignment

Every Assessment SHALL reference at least one Learning Objective.

Learning Objectives MAY have multiple Assessments.

---

# 8. Citation Requirements

Normative instructional content SHOULD provide authoritative citations where appropriate.

Citation identifiers SHOULD remain stable across versions.

---

# 9. Platform Independence

CDF SHALL remain independent of:

- Moodle
- Canvas
- Blackboard
- SCORM
- xAPI
- HTML

These platforms are publication targets, not authoring formats.

---

# 10. Validation

A CDF validator SHALL verify:

- Required metadata
- Object hierarchy
- Learning objective references
- Assessment mappings
- Citation integrity
- Version information

---

# 11. Future Specifications

Subsequent CDF specifications extend this document.

Examples include:

- Metadata Specification
- Learning Object Model
- Assessment Specification
- Citation Specification
- Accessibility Specification
- Publishing Specification

