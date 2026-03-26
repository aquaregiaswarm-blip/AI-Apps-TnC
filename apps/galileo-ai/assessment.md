# App Name: Galileo AI

**Assessment Date:** 2026-03-26  
**Assessed By:** Aqua Regia  
**App Version/Plan:** Free/Pro/Enterprise (AI Observability Platform)  

---

## Document Sources

- **Terms of Service:** https://galileo.ai/terms-of-service (Accessed: 2026-03-26)
- **Privacy Policy:** https://galileo.ai/privacy-policy (Accessed: 2026-03-26)
- **Pricing:** https://galileo.ai/pricing (Accessed: 2026-03-26)
- **Last Updated:** November 1st, 2024

---

## Assessment Rubric

### 1. Data Training & Model Ingestion

| # | Question | Answer | Risk Level | Notes |
|---|----------|--------|------------|-------|
| 1.1 | Whether your code, designs, or prompts are used to train the vendor's AI models — often buried in the free tier ToS but opted out on paid/enterprise plans | **YES - Customer Data used to train algorithms** | ❌ | ToS Section 2.4: "Customer agrees that Galileo is hereby granted the right to use (during and after the term hereof) Customer Data to train its algorithms internally through machine learning techniques" |
| 1.2 | Whether inputs are shared across tenants or used to improve shared models | **YES - Aggregated data used for improvements** | ❌ | ToS Section 2.5: "Galileo has the right to aggregate, collect and analyze data... to improve Galileo's products and services" |
| 1.3 | Residual data retention after account deletion | **NOT SPECIFIED** | ⚠️ | No explicit mention of data deletion timelines in ToS or Privacy Policy |

### 2. Data Residency & Sovereignty

| # | Question | Answer | Risk Level | Notes |
|---|----------|--------|------------|-------|
| 2.1 | Where data is stored and processed (US, EU, etc.) — critical for GDPR, Quebec Bill 25, and clients in regulated industries | **NOT SPECIFIED** | ⚠️ | No explicit mention of data residency locations in documents |
| 2.2 | Whether the vendor can move data across regions without notice | **NOT SPECIFIED** | ⚠️ | No contractual guarantees found |
| 2.3 | Lack of contractual guarantees on data location in free tiers | **YES - No guarantees** | ❌ | Enterprise offers "Deploy: Hosted, VPC, or on-prem" but free tier has no location guarantees |

### 3. Intellectual Property Ownership

| # | Question | Answer | Risk Level | Notes |
|---|----------|--------|------------|-------|
| 3.1 | Who owns outputs — generated code, UI designs, prototypes | **Customer retains ownership of Customer Data** | ✅ | ToS Section 2.1: "Customer retains all right, title and interest in and to the Customer Data" |
| 3.2 | Whether the vendor claims a license to use your outputs for any purpose | **YES - Broad license granted** | ❌ | ToS Section 2.2: "non-exclusive, worldwide, royalty-free, fully paid up, sublicenseable, transferable right and license to copy, distribute, display and create derivative works" |
| 3.3 | IP indemnification gaps: if the AI generates code or design assets that infringe on a third party's copyright, who is liable? Most free tiers offer zero indemnification | **NOT SPECIFIED** | ⚠️ | No explicit IP indemnification clause found in ToS |
| 3.4 | Work-for-hire ambiguity when outputs are produced inside a client engagement | **NOT SPECIFIED** | ⚠️ | No specific work-for-hire provisions |

### 4. Security & Access Controls

| # | Question | Answer | Risk Level | Notes |
|---|----------|--------|------------|-------|
| 4.1 | Free tiers typically have no SSO, MFA enforcement, or SCIM provisioning — a shadow IT red flag | **YES - SSO/RBAC only in Pro/Enterprise** | ❌ | Free: "Unlimited users" (no SSO); Pro: "Standard RBAC"; Enterprise: "Enterprise-grade security RBAC, SSO" |
| 4.2 | No audit logs or access review capabilities, which breaks CMMC and SOC 2 requirements | **NOT SPECIFIED for Free** | ⚠️ | Enterprise mentions "24/7 Support" but no explicit audit log mention |
| 4.3 | Shared infrastructure with no tenant isolation guarantees | **YES - Shared in Free/Pro** | ❌ | Enterprise offers "VPC, or on-prem" for isolation |

### 5. Compliance & Certifications

| # | Question | Answer | Risk Level | Notes |
|---|----------|--------|------------|-------|
| 5.1 | Free tiers rarely come with BAAs (Business Associate Agreements) — a hard blocker for HIPAA-covered work | **NO BAA mentioned** | ❌ | No mention of HIPAA BAA in any tier |
| 5.2 | No SOC 2 Type II, ISO 27001, or FedRAMP coverage on free plans | **NOT SPECIFIED** | ⚠️ | ToS mentions "security program materially in accordance with industry standards" but no specific certifications listed |
| 5.3 | Inability to sign a DPA (Data Processing Agreement) required under GDPR and similar frameworks | **NOT SPECIFIED** | ⚠️ | No explicit DPA mentioned; Privacy Policy last updated Nov 2024 |

### 6. Contractual & SLA Gaps

| # | Question | Answer | Risk Level | Notes |
|---|----------|--------|------------|-------|
| 6.1 | No uptime SLA or liability cap on free tiers — enterprise risk and legal teams won't sign off on mission-critical usage | **NO SLA in Free** | ❌ | Free: No SLA mentioned; Pro/Enterprise: "Dedicated support" but no explicit uptime SLA |
| 6.2 | Unilateral right to change ToS with short or no notice | **NOT SPECIFIED** | ⚠️ | No explicit change notification clause found |
| 6.3 | No data breach notification obligations contractually specified | **NOT SPECIFIED** | ⚠️ | Privacy Policy mentions security but no specific breach notification timeline |

### 7. Vendor Lock-in & Portability

| # | Question | Answer | Risk Level | Notes |
|---|----------|--------|------------|-------|
| 7.1 | Export limitations that make it hard to move data or designs out | **NOT SPECIFIED** | ⚠️ | No explicit data export provisions found |
| 7.2 | Proprietary file formats with no open standard equivalent | **N/A** | N/A | This is an observability platform, not a design tool with file formats |
| 7.3 | API access gated behind paid tiers, preventing integration into enterprise toolchains | **API available in all tiers** | ✅ | Platform is API-based; free tier includes API access (5,000 traces/month) |

---

## Summary

| Risk Category | Risk Items | Status |
|---------------|-----------|--------|
| Data Training & Model Ingestion | 3 | 🔴 High Risk |
| Data Residency & Sovereignty | 3 | 🔴 High Risk |
| Intellectual Property Ownership | 4 | 🟡 Medium Risk |
| Security & Access Controls | 3 | 🔴 High Risk |
| Compliance & Certifications | 3 | 🔴 High Risk |
| Contractual & SLA Gaps | 3 | 🔴 High Risk |
| Vendor Lock-in & Portability | 3 | 🟡 Medium Risk |

**Overall Risk Level:** 🔴 **HIGH RISK**

**Recommendation:** ⚠️ **Requires Legal Review** - Do not use for sensitive client data without Enterprise plan and negotiated DPA

---

## Key Findings

### Critical Issues (❌)
1. **Customer Data used for AI training** (Section 2.4) - Cannot opt out in any tier
2. **Broad license to Customer Data** (Section 2.2) - Galileo can create derivative works
3. **No SSO/MFA in Free tier** - Shadow IT risk
4. **No data residency guarantees** - GDPR/compliance risk
5. **No HIPAA BAA** - Healthcare data blocker
6. **No uptime SLA** - Mission-critical usage risk

### Warnings (⚠️)
1. No explicit data deletion timelines
2. No IP indemnification
3. No SOC 2/ISO 27001 certifications listed
4. No explicit DPA for GDPR
5. No breach notification obligations specified

### Positive Findings (✅)
1. Customer retains ownership of Customer Data
2. API access available in all tiers
3. Enterprise offers VPC/on-prem deployment
4. Security program mentioned (industry standards)

---

## Critical Concern: AI Training on Customer Data

**ToS Section 2.4 explicitly states:**
> "Customer agrees that Galileo is hereby granted the right to use (during and after the term hereof) Customer Data to train its algorithms internally through machine learning techniques"

**This applies to ALL tiers including Free and Pro.**

**Implications:**
- Any data you upload (prompts, traces, evaluations) can be used to train Galileo's AI
- This continues even after you cancel your account
- No opt-out mechanism mentioned
- Enterprise plan does not appear to offer training opt-out

---

## Next Steps

- [ ] **URGENT:** Negotiate DPA with explicit training opt-out before using for client data
- [ ] Verify SOC 2/ISO 27001 certifications
- [ ] Confirm data residency options for Enterprise
- [ ] Request IP indemnification clause
- [ ] Obtain explicit data deletion procedures
- [ ] Legal review of Section 2.2 (broad license) and 2.4 (training)

---

*Assessment completed using AI Apps TnC Framework*  
*⚠️ HIGH RISK - Legal review strongly recommended*
