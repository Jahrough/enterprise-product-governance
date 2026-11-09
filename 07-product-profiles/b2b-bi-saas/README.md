---
document_id: EPG-BI-001
title: B2B BI SaaS Product Governance Profile
document_type: product profile
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

# B2B BI SaaS Product Governance Profile

**PROPOSED — pending formal review.** This profile identifies assessment
topics, not implemented product capabilities or mandatory requirements.
A future product owner and relevant domain owners would determine
applicability, establish requirements, and maintain the profile.

| Area | Proposed assessment and decisions |
| --- | --- |
| Tenancy | Decide multi-tenant, single-tenant, or hybrid deployment; define and verify isolation of data, compute, configuration, access, and operational processes. |
| Enterprise identity and access | Define identity federation, authentication, authorization, provisioning, privileged access, and periodic access review as applicable. |
| Data governance | Assess ingestion sources and permissions, lineage, quality, classification, retention, deletion, and data ownership. |
| Analytics | Govern semantic models, metric definitions, dashboards, data provenance, consistency, and changes to analytical outputs. |
| Integration | Define API and event contracts, compatibility, versioning, access, and deprecation expectations. |
| AI-assisted analytics | Assess model and data provenance, intended use, evaluation, monitoring, human oversight, security, privacy, and model changes. |
| Customer lifecycle | Plan onboarding, tenant setup, migration, access, offboarding, data export or deletion, and confirmation. |
| Security, privacy, and compliance | Identify applicable obligations, risks, controls, evidence, and contractual requirements with qualified stakeholders. |
| Service assurance | Define and verify availability, performance, resilience, incident response, backup, recovery, and disaster recovery objectives. |
| Customer commitments | Inventory customer-specific configurations and contractual commitments, their owners, impact on shared services, and change and support processes. |

SOC 2, ISO 27001, GDPR, HIPAA, and PCI DSS are conditional references for
assessment, not assertions of applicability, certification, or compliance.
Determine applicability from the product, data, customers, contracts,
jurisdictions, and authoritative advice; record the decision and evidence in
the [standards and regulatory reference register](../../09-registers/README.md).
Trace agreed product requirements to lifecycle decisions, controls, and
evidence; record exceptions and customer-specific dependencies.
