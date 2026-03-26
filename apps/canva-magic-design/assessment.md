# App Name: Canva Magic Design

**Assessment Date:** 2026-03-26  
**Assessed By:** Aqua Regia  
**App Version/Plan:** Free/Pro/Teams/Enterprise (AI-Powered Design Platform)  

---

## Document Sources

- **Terms of Use:** Unable to access (403 error) (Accessed: 2026-03-26)
- **Privacy Policy:** https://www.canva.com/policies/privacy-policy/ (Accessed: 2026-03-26)
- **AI Terms:** Unable to access (403 error) (Accessed: 2026-03-26)
- **Last Updated:** March 16, 2026 (Privacy Policy)

---

## ⚠️ PARTIAL ASSESSMENT - DOCUMENT ACCESS LIMITED

**Issue:** Canva's Terms of Use and AI Terms are blocking automated access (403 errors).

**Available:** Privacy Policy (March 16, 2026)

**To Complete This Assessment:**

1. Visit https://www.canva.com/policies/terms-of-use/
2. Visit https://www.canva.com/policies/ai-terms/
3. Download or copy the documents
4. Save to `apps/canva-magic-design/legal-docs/`
5. Complete the assessment rubric below

---

## Assessment Based on Available Information

### 1. Data Training & Model Ingestion

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 1.1 | Whether your code, designs, or prompts are used to train the vendor's AI models — often buried in the free tier ToS but opted out on paid/enterprise plans | **LIKELY YES** | ⚠️ | **RESEARCH REQUIRED** - Privacy Policy Section 2 mentions "train our algorithms, models and AI products and services using machine learning". Full scope in AI Terms. | Privacy Policy: "We may analyze your activity, content, media uploads and related data in your account to provide and customize the Service, and to train our algorithms, models and AI products and services using machine learning to develop, improve and provide our Service." |
| 1.2 | Whether inputs are shared across tenants or used to improve shared models | **LIKELY YES** | ⚠️ | **RESEARCH REQUIRED** - Privacy Policy indicates aggregated analysis for service improvement. Check AI Terms for specifics. | Privacy Policy mentions using data to "improve and provide our Service" which suggests shared model improvements. |
| 1.3 | Residual data retention after account deletion | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Privacy Policy does not specify deletion timelines. Check Terms of Use for retention periods. | No explicit data retention timeline found in Privacy Policy. |

### 2. Data Residency & Sovereignty

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 2.1 | Where data is stored and processed (US, EU, etc.) — critical for GDPR, Quebec Bill 25, and clients in regulated industries | **GLOBAL** | ⚠️ | **RESEARCH REQUIRED** - Canva operates globally. Check Terms for specific data center locations and EU data handling. | Privacy Policy mentions Canva Contracting Entity and affiliates. Specific locations not detailed. |
| 2.2 | Whether the vendor can move data across regions without notice | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - No explicit data location guarantees found. Check Terms of Use. | Canva may process data in multiple jurisdictions. |
| 2.3 | Lack of contractual guarantees on data location in free tiers | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - DPA availability unclear for free tier. Check Enterprise options. | Enterprise likely offers more data location controls. |

### 3. Intellectual Property Ownership

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 3.1 | Who owns outputs — generated code, UI designs, prototypes | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Ownership terms in ToS. Canva typically allows commercial use but verify. | Check Terms of Use Section on Content ownership. |
| 3.2 | Whether the vendor claims a license to use your outputs for any purpose | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - License terms in ToS. Canva typically has broad license for service operation. | Check Terms of Use for license grants. |
| 3.3 | IP indemnification gaps: if the AI generates code or design assets that infringe on a third party's copyright, who is liable? Most free tiers offer zero indemnification | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - IP indemnification in ToS or AI Terms. | Check AI Terms for indemnification provisions. |
| 3.4 | Work-for-hire ambiguity when outputs are produced inside a client engagement | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Clarify ownership in client contracts. | Customer should verify ownership rights for client work. |

### 4. Security & Access Controls

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 4.1 | Free tiers typically have no SSO, MFA enforcement, or SCIM provisioning — a shadow IT red flag | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Check Canva pricing page for SSO availability. | Canva Pro/Teams/Enterprise likely offer SSO. Free tier probably does not. |
| 4.2 | No audit logs or access review capabilities, which breaks CMMC and SOC 2 requirements | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Enterprise features may include audit logs. | Check Enterprise plan for compliance features. |
| 4.3 | Shared infrastructure with no tenant isolation guarantees | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Standard SaaS architecture. Enterprise may offer isolation. | Typical multi-tenant SaaS. |

### 5. Compliance & Certifications

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 5.1 | Free tiers rarely come with BAAs (Business Associate Agreements) — a hard blocker for HIPAA-covered work | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Check Canva Enterprise for BAA availability. | Canva Education mentioned - no advertising to students. |
| 5.2 | No SOC 2 Type II, ISO 27001, or FedRAMP coverage on free plans | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Check Canva Trust Center or Enterprise for certifications. | No certifications mentioned in Privacy Policy. |
| 5.3 | Inability to sign a DPA (Data Processing Agreement) required under GDPR and similar frameworks | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Check Canva Enterprise for DPA availability. | Canva operates under GDPR but specific DPA terms in ToS. |

### 6. Contractual & SLA Gaps

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 6.1 | No uptime SLA or liability cap on free tiers — enterprise risk and legal teams won't sign off on mission-critical usage | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Check Canva Enterprise for SLA. | Free tier unlikely to have SLA. |
| 6.2 | Unilateral right to change ToS with short or no notice | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Modification clause in ToS. | Check Terms of Use for change notification. |
| 6.3 | No data breach notification obligations contractually specified | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Breach notification in ToS or DPA. | Check Terms for breach notification terms. |

### 7. Vendor Lock-in & Portability

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 7.1 | Export limitations that make it hard to move data or designs out | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Canva allows exports in various formats. Check for limitations. | Canva supports PNG, PDF, MP4 exports. |
| 7.2 | Proprietary file formats with no open standard equivalent | **PARTIAL** | ⚠️ | **USE EXPORT FEATURES** - Canva uses proprietary .canva format but exports to standard formats. | Export to PNG, PDF, SVG available. |
| 7.3 | API access gated behind paid tiers, preventing integration into enterprise toolchains | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Check Canva Developers for API availability. | Canva has API for integrations. |

---

## Summary

| Risk Category | Risk Items | Status |
|---------------|-----------|--------|
| Data Training & Model Ingestion | 3 | ⚠️ High Concern |
| Data Residency & Sovereignty | 3 | ⚪ Pending |
| Intellectual Property Ownership | 4 | ⚪ Pending |
| Security & Access Controls | 3 | ⚪ Pending |
| Compliance & Certifications | 3 | ⚪ Pending |
| Contractual & SLA Gaps | 3 | ⚪ Pending |
| Vendor Lock-in & Portability | 3 | ⚠️ Medium Concern |

**Overall Risk Level:** ⚠️ **HIGH CONCERN - DOCUMENTS INCOMPLETE**

**Recommendation:** ⏸️ **ON HOLD** - Complete assessment after accessing full Terms of Use and AI Terms

---

## Critical Finding from Privacy Policy

**AI Training on User Content (Privacy Policy Section 2):**
> "We may analyze your activity, content, media uploads and related data in your account to provide and customize the Service, and to **train our algorithms, models and AI products and services using machine learning** to develop, improve and provide our Service."

**Implications:**
- Canva explicitly states they train AI models on user content
- This includes "activity, content, media uploads"
- Applies to Magic Design and other AI features
- Opt-out mechanism unclear from Privacy Policy alone

---

## Next Steps

### Immediate Actions Required:

1. **Access Full Terms:**
   - Visit https://www.canva.com/policies/terms-of-use/
   - Visit https://www.canva.com/policies/ai-terms/
   - Save documents to `apps/canva-magic-design/legal-docs/`

2. **Research AI Training Opt-Out:**
   - Check if Canva offers AI training opt-out
   - Verify if Enterprise plan excludes content from training
   - Look for "Magic Design" specific terms

3. **Complete Assessment:**
   - Fill in all 22 questions in rubric
   - Mark risk levels (✅/❌/⚠️)
   - Document mitigation options

### Key Questions to Answer:

1. Can users opt out of AI training?
2. Does Enterprise plan offer training exclusion?
3. What is Canva's IP indemnification policy?
4. Are there data residency options?
5. What certifications does Canva hold?

---

## Known Information

### Canva Plans:
- **Free:** Basic features, limited exports
- **Pro:** $12.99/month, premium features, brand kit
- **Teams:** $14.99/user/month, collaboration
- **Enterprise:** Custom pricing, advanced security

### Magic Design Features:
- AI-generated presentations
- Social media content
- Video creation
- Brand-consistent designs

### Data Collection (from Privacy Policy):
- User-provided information
- Third-party app data
- Automatically collected data (cookies, logs, device info)
- **Content within account (designs, uploads)**
- **Used for AI training**

---

## Contact Information

**Canva Support:**
- Website: https://www.canva.com/
- Help Center: https://www.canva.com/help/
- Privacy: privacy@canva.com

---

*Assessment partially complete - Full Terms of Use and AI Terms required*  
*⚠️ HIGH CONCERN - AI training on user content confirmed in Privacy Policy*
