---
document_id: EPG-CON-001
title: Proposed Contribution and Documentation Conventions
document_type: guideline
status: proposed
version: 0.1.0
owner: null
approver: null
created_date: null
last_reviewed: null
next_review: null
effective_date: null
supersedes: null
related_documents: []
---

# Proposed Contribution and Documentation Conventions

**PROPOSED — pending formal review.** See the [change workflow](05-workflows/README.md)
for the proposed review and approval process. Do not treat merging as policy approval.

## Documents

- Use Markdown with a single descriptive top-level heading, meaningful headings,
  readable tables and lists, and relative links to repository artifacts.
- Give each governance document a unique stable `document_id`; use an
  `EPG-<scope>-<number>` identifier and do not reuse retired identifiers.
- Include the fields shown in the [metadata convention](06-templates/README.md).
  Until assigned or known, use `null`, not invented names or dates.
- Use `proposed` for unapproved material. A designated authority must approve
  any later lifecycle states and their transition rules. Record the approval,
  approver, and effective date only after they exist.
- Use semantic version numbers as a proposed convention: major for incompatible
  requirements, minor for additive changes, and patch for clarifications.
  Version and effective date are distinct; a version is not automatically effective.
- Link related requirements, decisions, controls, and evidence using stable
  IDs and relative links where possible. Record review dates and cadence only
  after an owner and schedule are agreed.
- Preserve history in Git and the relevant change log. Mark deprecated material
  clearly, link its successor and record supersession after approval; do not
  silently remove the historical record.

## Validation

Before proposing a change, check Markdown readability and formatting, local
link targets and anchors, metadata completeness and unique IDs, and consistency
between the repository map and directories. Check that approvals, ownership,
effective dates and compliance claims are supported. No automated checks or
branch protections are configured by this document.
