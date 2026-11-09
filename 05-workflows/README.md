---
document_id: EPG-WFL-001
title: Proposed Change and GitHub Workflow
document_type: workflow
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

# Proposed Change and GitHub Workflow

**PROPOSED — pending formal review.** This directory is intended for
repeatable governance workflows. Future governance and repository
maintainers would jointly own this workflow; neither roles nor permissions
are assigned here.

## Change process

1. **Classify:** identify the affected artifacts, product, domains, and
   lifecycle stage; propose a change category and significance based on
   scope, risk, and reversibility. Category thresholds require approval.
2. **Assess:** record requirements, architecture, security, privacy, data,
   AI, customer, regulatory, operational, and cross-repository impacts as
   applicable, plus dependencies, risks, controls, and evidence.
3. **Approve:** obtain the relevant independent decision(s) recorded in the
   [decision authority matrix](../09-registers/README.md). Requirements,
   architecture, implementation, release, and deployment authorizations
   are separate; an approval is limited to its recorded scope.
4. **Implement and verify:** implement the authorized scope, link changes
   and tests or reviews to requirements, and record results and unresolved
   risks. Reassess material scope changes.
5. **Release and trace:** evaluate readiness, obtain release and production
   deployment authorizations separately where applicable, record deployment
   and acceptance, and link the decision and evidence trail.

## Proposed GitHub practices

Use short-lived feature branches and pull requests for substantive governance
changes. Link each pull request to affected artifact IDs, assessment,
decisions, and evidence references. Request review from designated
CODEOWNERS and other relevant domain reviewers; an authorized decision
maker must set the required approval count and independent review rules.
The current [CODEOWNERS](../CODEOWNERS) has no active assignments.

After authorization, protect the primary branch, require applicable reviews
and automated documentation validation, and preserve version-controlled
change, approval, and merge history. These are proposals, not configured
controls. A GitHub review or merge alone does not establish formal approval
unless a designated authority and approved process say so. No branch
protection, rulesets, secrets, or permissions are configured here.

## Exceptions and waivers

Before deviating from an applicable approved requirement, propose an
exception with scope, rationale, risk, compensating controls, owner, expiry,
review date, and decision evidence. A designated authority must approve or
reject it before use; record the outcome in the
[exception register](../09-registers/README.md). Review, renew through a new
decision, remediate, or close by expiry; an expired exception is not
automatically renewed. Emergency paths require separately approved authority
and must not be inferred from this proposal.
