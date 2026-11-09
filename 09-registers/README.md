---
document_id: EPG-REG-001
title: Governance Register Schemas
document_type: register schema
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

# Governance Register Schemas

**PROPOSED — pending formal review.** This directory is intended for
governance inventory and traceability. The roles below are intended custodians,
not actual assignments or approval authorities. No register entries or
organizational decisions are asserted here.

All fields listed below are required in each future record. Use a stable
unique ID, an explicit `unknown` or `not applicable` with rationale where
necessary, and references rather than sensitive evidence itself. The
designated custodian should create or update records when changes or decisions
occur, review them on an agreed schedule, retain decision history, and link
to related records. Review cadence, storage, access, retention, and actual
owners require approval.

## Governance Domain Register

- **Purpose:** inventory governance domains, scope, accountability, and relationships.
- **Intended custodian:** governance function with domain owners.
- **Required fields:** domain ID; name; scope and boundaries; accountable owner;
  status; related domains; applicable artifacts and controls; dependencies;
  last reviewed; next review.
- **Maintenance:** update on domain or ownership changes and review coverage
  and overlaps on the agreed schedule.

## Governance Artifact Register

- **Purpose:** inventory governance documents and their lifecycle.
- **Intended custodian:** governance documentation owner with artifact owners.
- **Required fields:** artifact ID; title; type; location; version; status;
  owner; approver; approval record; effective date; scope; related domains,
  requirements and controls; supersedes; last reviewed; next review.
- **Maintenance:** update on creation, approval, revision, or retirement;
  reconcile links, version, status, and review dates with the artifact.

## Governance Control Register

- **Purpose:** trace controls from requirements and risks to execution and evidence.
- **Intended custodian:** assurance function with control owners.
- **Required fields:** control ID; name and description; scope; linked
  requirements and risks; control owner; performer; frequency or trigger;
  verification method; evidence location and retention; status; exceptions;
  last reviewed; next review.
- **Maintenance:** update on control design, execution approach, or scope
  changes; review effectiveness and evidence on the agreed schedule.

## Decision Authority Matrix

- **Purpose:** define who may make which decisions and under what conditions.
- **Intended custodian:** governance sponsor or delegated governance function.
- **Required fields:** decision ID and type; scope and lifecycle stage;
  accountable decision role; required reviewers; delegation or escalation;
  prerequisites and evidence; decision record location; status; last reviewed;
  next review.
- **Maintenance:** update when authority, delegation, or process changes;
  periodically confirm assignments with authorized stakeholders. Include
  distinct requirements, architecture, implementation, release, and production
  deployment decisions.

## Repository Ownership Register

- **Purpose:** identify repository and path stewardship and review coverage.
- **Intended custodian:** repository governance function or maintainers.
- **Required fields:** ownership ID; repository and path; purpose; accountable
  owner; maintainer and reviewer roles; CODEOWNERS mapping; escalation;
  status; last reviewed; next review.
- **Maintenance:** update on repository, path, team, or ownership changes;
  reconcile approved mappings with CODEOWNERS.

## Standards and Regulatory Reference Register

- **Purpose:** track external and internal references and assessed applicability.
- **Intended custodian:** compliance or legal stakeholders with domain owners.
- **Required fields:** reference ID; name and version; source; scope;
  applicability decision and rationale; decision authority; assessment date;
  affected products and artifacts; evidence location; status; last reviewed;
  next review.
- **Maintenance:** reassess on reference, jurisdiction, contract, or product
  changes and on the agreed schedule. Listing a reference does not establish
  applicability, certification, or compliance.

## Governance Exception Register

- **Purpose:** track time-bounded deviations and their risk treatment.
- **Intended custodian:** governance or risk function with exception owners.
- **Required fields:** exception ID; requirement and scope; rationale; risk;
  compensating controls; owner; requested and approved dates; decision and
  authority; decision evidence; expiry; review date; remediation plan;
  status; closure evidence.
- **Maintenance:** update on request, decision, review, remediation, renewal,
  expiry, and closure; escalate expired or unapproved deviations.

## Cross-Repository Dependency Register

- **Purpose:** track dependencies and impact across repository boundaries.
- **Intended custodian:** architecture or repository governance function with
  dependency owners.
- **Required fields:** dependency ID; source and target repositories and
  artifacts; dependency description and version; owning parties; scope;
  change impact; linked decisions and controls; status; last reviewed; next review.
- **Maintenance:** update when repositories, versions, owners, or interfaces
  change; coordinate affected changes and periodically reconcile dependencies.
