---
document_id: EPG-TPL-001
title: Artifact and Metadata Conventions
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

# Artifact and Metadata Conventions

**PROPOSED — pending formal review.** This directory is intended for reusable
artifact structures. A future governance documentation owner would maintain
templates with input from domain owners; no owner is assigned.

Use the following metadata for new governance documents. YAML front matter
is preferred; existing content may retain its original position and include
the same metadata in a clearly labelled YAML block. Use `null` for unknown or
unassigned values and ISO 8601 dates (`YYYY-MM-DD`) only when known.

```yaml
document_id: null
title: null
document_type: null
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
```

`document_id` is stable and unique; `document_type` uses the
[governance classifications](../GOVERNANCE.md#artifact-classification)
when applicable, or a descriptive type for supporting material.
`related_documents` contains document IDs or relative references when known.
An approval record should identify the decision, authority, scope, date, and
evidence location; metadata alone does not establish approval.

Proposed lifecycle: draft or proposed, review, formally approved and
effective, then deprecated or superseded as appropriate. These are candidate
states and transitions, not an authorized process. Owners and approvers,
review cadence, transition criteria, and retention need human decisions.
See [contribution conventions](../CONTRIBUTING.md) for versioning,
traceability, and change history.
