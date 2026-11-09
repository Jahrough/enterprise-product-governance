---
document_id: EPG-LIF-001
title: Proposed Product Lifecycle
document_type: lifecycle model
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

# Proposed Product Lifecycle

**PROPOSED — pending formal review.** This directory is intended for lifecycle
standards and stage expectations. A future product lifecycle governance
function, working with engineering and domain owners, would maintain it.
No stage, role, or approval is currently authorized by this document.

| Sequence | Stage | Intended outcome |
| --- | --- | --- |
| 1 | Product Discovery | Identify problem, stakeholders, opportunities, and initial risks |
| 2 | Requirements Engineering | Define and trace functional and nonfunctional requirements; obtain requirements approval |
| 3 | Architecture and Design | Assess alternatives, domain impacts, and architecture decisions; obtain architecture decision approval |
| 4 | Planning and Authorization | Plan scope, dependencies, risk treatment, and resources; obtain implementation authorization |
| 5 | Implementation | Build and document changes against authorized scope |
| 6 | Verification and Validation | Verify requirements and controls, validate outcomes, and record results |
| 7 | Release Readiness and Approval | Assess evidence, residual risk, support readiness, and obtain release authorization |
| 8 | Deployment and Production Acceptance | Obtain production deployment authorization, deploy, and record production acceptance |
| 9 | Operations and Monitoring | Monitor service, risks, incidents, and operational controls |
| 10 | Maintenance and Continuous Improvement | Assess and deliver changes and improvements through the change workflow |
| 11 | Product Retirement | Plan and record decommissioning, customer transition, data disposition, and closure |

Stages may iterate or overlap, but proposed decision boundaries remain
distinct. Requirements approval accepts the requirements baseline;
architecture decision approval accepts a design decision and its trade-offs;
implementation authorization permits work on an assessed scope; release
authorization accepts a candidate for release; production deployment
authorization permits deployment to a specified environment and window.
Production acceptance records the outcome after deployment. None implies
the others. The [decision authority matrix](../09-registers/README.md)
should record who may make each decision and its evidence and scope.

Trace requirements through decisions, implementation, verification, release,
deployment, and operations. Route changes and exceptions through the
[proposed workflow](../05-workflows/README.md).
