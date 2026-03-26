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

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 1.1 | Whether your code, designs, or prompts are used to train the vendor's AI models — often buried in the free tier ToS but opted out on paid/enterprise plans | **YES - Customer Data used to train algorithms** | ❌ | **NO OPT-OUT AVAILABLE** - Clause applies to ALL tiers including Enterprise. Must negotiate custom DPA or avoid uploading sensitive data. | ToS Section 2.4: "Customer agrees that Galileo is hereby granted the right to use (during and after the term hereof) Customer Data to train its algorithms internally through machine learning techniques" |
| 1.2 | Whether inputs are shared across tenants or used to improve shared models | **YES - Aggregated data used for improvements** | ❌ | **NO OPT-OUT** - Aggregated data usage is mandatory. ToS Section 2.5 allows use "during and after the term". | ToS Section 2.5: "Galileo has the right to aggregate, collect and analyze data... to improve Galileo's products and services" |
| 1.3 | Residual data retention after account deletion | **NOT SPECIFIED** | ⚠️ | **NO DOCUMENTED DELETION PROCESS** - Contact team@galileo.io to request data deletion. No automated self-service option found. | No explicit mention of data deletion timelines in ToS or Privacy Policy. Manual request required. |

### 2. Data Residency & Sovereignty

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 2.1 | Where data is stored and processed (US, EU, etc.) — critical for GDPR, Quebec Bill 25, and clients in regulated industries | **NOT SPECIFIED** | ⚠️ | **ENTERPRISE VPC/ON-PREM** - Enterprise tier offers "Deploy: Hosted, VPC, or on-prem" which allows data residency control. Free/Pro have no guarantees. | No explicit mention of data residency locations in documents. Enterprise deployment options provide control. |
| 2.2 | Whether the vendor can move data across regions without notice | **NOT SPECIFIED** | ⚠️ | **ENTERPRISE NEGOTIATION** - Enterprise customers can negotiate contractual guarantees. Free/Pro have no protections. | No contractual guarantees found. Enterprise DPA negotiation required. |
| 2.3 | Lack of contractual guarantees on data location in free tiers | **YES - No guarantees** | ❌ | **UPGRADE TO ENTERPRISE** - Only Enterprise tier offers VPC/on-prem deployment for data location control. | Enterprise offers "Deploy: Hosted, VPC, or on-prem" but no explicit data location guarantees in ToS. |

### 3. Intellectual Property Ownership

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 3.1 | Who owns outputs — generated code, UI designs, prototypes | **Customer retains ownership of Customer Data** | ✅ | N/A - Customer ownership is clear | ToS Section 2.1: "Customer retains all right, title and interest in and to the Customer Data" |
| 3.2 | Whether the vendor claims a license to use your outputs for any purpose | **YES - Broad license granted** | ❌ | **NO OPT-OUT** - License is mandatory. ToS Section 2.2 grants "non-exclusive, worldwide, royalty-free, fully paid up, sublicenseable, transferable" rights. | ToS Section 2.2: "non-exclusive, worldwide, royalty-free, fully paid up, sublicenseable (through multiple tiers), transferable right and license to copy, distribute, display and create derivative works" |
| 3.3 | IP indemnification gaps: if the AI generates code or design assets that infringe on a third party's copyright, who is liable? Most free tiers offer zero indemnification | **NOT SPECIFIED** | ⚠️ | **ENTERPRISE NEGOTIATION** - No explicit IP indemnification found. Must negotiate custom contract or rely on general liability clauses. | No explicit IP indemnification clause found in ToS. Section 7 (Indemnification) is general. |
| 3.4 | Work-for-hire ambiguity when outputs are produced inside a client engagement | **NOT SPECIFIED** | ⚠️ | **LEGAL REVIEW** - No specific work-for-hire provisions. Clarify ownership in client contracts. | No specific work-for-hire provisions. Recommend explicit client contract language. |

### 4. Security & Access Controls

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 4.1 | Free tiers typically have no SSO, MFA enforcement, or SCIM provisioning — a shadow IT red flag | **YES - SSO/RBAC only in Pro/Enterprise** | ❌ | **UPGRADE TO PRO/ENTERPRISE** - Pro: "Standard RBAC". Enterprise: "Enterprise-grade security RBAC, SSO". Free has no SSO. | Free: "Unlimited users" (no SSO); Pro: "Standard RBAC"; Enterprise: "Enterprise-grade security RBAC, SSO" |
| 4.2 | No audit logs or access review capabilities, which breaks CMMC and SOC 2 requirements | **NOT SPECIFIED for Free** | ⚠️ | **ENTERPRISE REQUIRED** - Enterprise offers "24/7 Support" and dedicated infrastructure. Audit logs not explicitly mentioned but likely available in Enterprise. | Enterprise mentions "24/7 Support" but no explicit audit log mention. Contact sales for audit capabilities. |
| 4.3 | Shared infrastructure with no tenant isolation guarantees | **YES - Shared in Free/Pro** | ❌ | **UPGRADE TO ENTERPRISE** - Enterprise offers "VPC, or on-prem" for tenant isolation. | Enterprise offers "VPC, or on-prem" for isolation. Free/Pro are multi-tenant. |

### 5. Compliance & Certifications

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 5.1 | Free tiers rarely come with BAAs (Business Associate Agreements) — a hard blocker for HIPAA-covered work | **NO BAA mentioned** | ❌ | **NOT AVAILABLE** - No mention of HIPAA BAA in any tier. Contact team@galileo.io to inquire about BAA availability for Enterprise. | No mention of HIPAA BAA in any tier. Likely not available. |
| 5.2 | No SOC 2 Type II, ISO 27001, or FedRAMP coverage on free plans | **NOT SPECIFIED** | ⚠️ | **REQUEST DOCUMENTATION** - ToS mentions "security program materially in accordance with industry standards". Contact team@galileo.io for SOC 2/ISO 27001 reports. | ToS mentions "security program materially in accordance with industry standards" but no specific certifications listed. |
| 5.3 | Inability to sign a DPA (Data Processing Agreement) required under GDPR and similar frameworks | **NOT SPECIFIED** | ⚠️ | **ENTERPRISE NEGOTIATION** - No explicit DPA mentioned. Privacy Policy last updated Nov 2024. Must negotiate DPA for GDPR compliance. | No explicit DPA mentioned. Enterprise customers should negotiate custom DPA. |

### 6. Contractual & SLA Gaps

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 6.1 | No uptime SLA or liability cap on free tiers — enterprise risk and legal teams won't sign off on mission-critical usage | **NO SLA in Free** | ❌ | **ENTERPRISE NEGOTIATION** - Free: No SLA; Pro: "Dedicated support: Slack"; Enterprise: "24/7 Support" + "Custom rate limits". SLA must be negotiated. | Free: No SLA mentioned; Pro/Enterprise: "Dedicated support" but no explicit uptime SLA. Contact sales for SLA. |
| 6.2 | Unilateral right to change ToS with short or no notice | **NOT SPECIFIED** | ⚠️ | **MONITOR TERMS** - No explicit change notification clause found. Monitor terms page for updates. | No explicit change notification clause found. Recommend monitoring ToS page. |
| 6.3 | No data breach notification obligations contractually specified | **NOT SPECIFIED** | ⚠️ | **REQUEST CLAUSE** - Privacy Policy mentions security but no specific breach notification timeline. Negotiate for Enterprise. | Privacy Policy mentions security but no specific breach notification timeline. Enterprise negotiation required. |

### 7. Vendor Lock-in & Portability

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 7.1 | Export limitations that make it hard to move data or designs out | **NOT SPECIFIED** | ⚠️ | **API ACCESS** - API available in all tiers. Can extract data via API. No explicit export feature mentioned. | No explicit data export provisions found. API access available for data extraction. |
| 7.2 | Proprietary file formats with no open standard equivalent | **N/A** | N/A | N/A | This is an observability platform, not a design tool with file formats |
| 7.3 | API access gated behind paid tiers, preventing integration into enterprise toolchains | **API available in all tiers** | ✅ | N/A - API access is available | Platform is API-based; free tier includes API access (5,000 traces/month) |

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
2. API access in all tiers
3. Enterprise offers VPC/on-prem deployment
4. Security program mentioned (industry standards)

---

## Mitigation Strategies

### Immediate Actions
1. **DO NOT upload sensitive client data** to Free/Pro tiers
2. **Contact team@galileo.io** to request:
   - SOC 2 Type II report
   - ISO 27001 certification
   - Custom DPA with training opt-out
   - BAA (if healthcare data)

### Enterprise Negotiation Points
1. **Custom DPA** with explicit:
   - AI training opt-out
   - Data deletion procedures
   - Breach notification timeline (24-72 hours)
   - Data residency guarantees
2. **IP Indemnification** clause
3. **Uptime SLA** (99.9% minimum)
4. **Audit rights** and audit log access
5. **ToS change notification** (30-day minimum)

### Workarounds
1. **Data Minimization** - Only upload non-sensitive, non-PII data
2. **Anonymization** - Strip identifying information before upload
3. **Hybrid Approach** - Use for non-sensitive projects only
4. **Alternative Tools** - Consider on-prem alternatives for sensitive data

---

## Critical Concern: AI Training on Customer Data

**ToS Section 2.4 explicitly states:**
> "Customer agrees that Galileo is hereby granted the right to use (during and after the term hereof) Customer Data to train its algorithms internally through machine learning techniques"

**This applies to ALL tiers including Free and Pro.**

**Implications:**
- Any data you upload (prompts, traces, evaluations) can be used to train Galileo's AI
- This continues even after you cancel your account
- **NO OPT-OUT MECHANISM** in any tier
- Enterprise plan does not appear to offer training opt-out

**Mitigation:**
- **Negotiate custom contract** with explicit training prohibition
- **Use only for non-sensitive data**
- **Consider alternative platforms** for sensitive client work

---

## Next Steps

- [ ] **URGENT:** Contact team@galileo.io to negotiate DPA with training opt-out
- [ ] Request SOC 2/ISO 27001 certifications
- [ ] Confirm data residency options for Enterprise
- [ ] Request IP indemnification clause
- [ ] Obtain explicit data deletion procedures
- [ ] Legal review of Section 2.2 (broad license) and 2.4 (training)
- [ ] Evaluate alternative AI observability platforms with better privacy terms

---

*Assessment completed using AI Apps TnC Framework*  
*⚠️ HIGH RISK - Legal review strongly recommended*
