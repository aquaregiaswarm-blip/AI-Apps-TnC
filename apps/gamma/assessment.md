# App Name: Gamma

**Assessment Date:** 2026-04-02  
**Assessed By:** Aqua Regia  
**App Version/Plan:** Free/Plus/Pro/Enterprise (AI-Powered Presentation Platform)  

---

## Document Sources

- **Terms of Service:** Unable to access (403 error) (Accessed: 2026-04-02)
- **Privacy Policy:** Unable to access (403 error) (Accessed: 2026-04-02)
- **Pricing:** Unable to access (403 error) (Accessed: 2026-04-02)
- **Website:** https://gamma.app

---

## ⚠️ ASSESSMENT PENDING - AUTOMATED ACCESS BLOCKED

**Issue:** Gamma's website is blocking automated access (403 errors on all pages).

**To Complete This Assessment:**

1. Visit https://gamma.app manually in a browser
2. Navigate to:
   - Terms of Service (usually in footer)
   - Privacy Policy (usually in footer)
   - Pricing page
3. Download or copy the documents
4. Save to `apps/gamma/legal-docs/`
5. Complete the assessment rubric below

---

## Known Information (From Public Sources)

### Product Overview
- AI-powered presentation and document creation platform
- Creates interactive presentations, documents, and webpages
- AI-generated content from prompts
- Free tier available
- Plus/Pro/Enterprise paid plans

### Key Areas to Research

#### Data Training (Critical)
- Does Gamma train AI on user presentations?
- Can users opt out of AI training?
- What happens to uploaded content?

#### IP Ownership
- Who owns AI-generated presentations?
- Can Gamma use content for marketing?
- Commercial usage rights?

#### Security
- SSO availability
- Data encryption
- Compliance certifications

#### Export/Portability
- Export formats available
- API access
- Vendor lock-in risk

---

## Assessment Rubric (Template - To Be Completed)

### 1. Data Training & Model Ingestion

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 1.1 | Whether your code, designs, or prompts are used to train the vendor's AI models — often buried in the free tier ToS but opted out on paid/enterprise plans | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Check ToS for AI training clauses |
| 1.2 | Whether inputs are shared across tenants or used to improve shared models | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Look for data sharing provisions |
| 1.3 | Residual data retention after account deletion | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Check data retention policies |

### 2. Data Residency & Sovereignty

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 2.1 | Where data is stored and processed (US, EU, etc.) — critical for GDPR, Quebec Bill 25, and clients in regulated industries | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Check for data location info |
| 2.2 | Whether the vendor can move data across regions without notice | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Look for data transfer clauses |
| 2.3 | Lack of contractual guarantees on data location in free tiers | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Check DPA availability |

### 3. Intellectual Property Ownership

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 3.1 | Who owns outputs — generated code, UI designs, prototypes | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Check IP ownership clauses |
| 3.2 | Whether the vendor claims a license to use your outputs for any purpose | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Look for license grants |
| 3.3 | IP indemnification gaps: if the AI generates code or design assets that infringe on a third party's copyright, who is liable? Most free tiers offer zero indemnification | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Check indemnification section |
| 3.4 | Work-for-hire ambiguity when outputs are produced inside a client engagement | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Clarify ownership for client work |

### 4. Security & Access Controls

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 4.1 | Free tiers typically have no SSO, MFA enforcement, or SCIM provisioning — a shadow IT red flag | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Check pricing page for SSO |
| 4.2 | No audit logs or access review capabilities, which breaks CMMC and SOC 2 requirements | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Look for security features |
| 4.3 | Shared infrastructure with no tenant isolation guarantees | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Check for isolation info |

### 5. Compliance & Certifications

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 5.1 | Free tiers rarely come with BAAs (Business Associate Agreements) — a hard blocker for HIPAA-covered work | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Check for healthcare compliance |
| 5.2 | No SOC 2 Type II, ISO 27001, or FedRAMP coverage on free plans | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Look for certification badges |
| 5.3 | Inability to sign a DPA (Data Processing Agreement) required under GDPR and similar frameworks | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Check for DPA availability |

### 6. Contractual & SLA Gaps

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 6.1 | No uptime SLA or liability cap on free tiers — enterprise risk and legal teams won't sign off on mission-critical usage | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Check for SLA guarantees |
| 6.2 | Unilateral right to change ToS with short or no notice | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Look for modification clauses |
| 6.3 | No data breach notification obligations contractually specified | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Check breach notification terms |

### 7. Vendor Lock-in & Portability

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 7.1 | Export limitations that make it hard to move data or designs out | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Check export formats |
| 7.2 | Proprietary file formats with no open standard equivalent | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Look for format lock-in |
| 7.3 | API access gated behind paid tiers, preventing integration into enterprise toolchains | **RESEARCH REQUIRED** | ⚠️ | **MANUAL REVIEW** | Check for API availability |

---

## Summary

| Risk Category | Risk Items | Status |
|---------------|-----------|--------|
| Data Training & Model Ingestion | 3 | ⚪ Pending |
| Data Residency & Sovereignty | 3 | ⚪ Pending |
| Intellectual Property Ownership | 4 | ⚪ Pending |
| Security & Access Controls | 3 | ⚪ Pending |
| Compliance & Certifications | 3 | ⚪ Pending |
| Contractual & SLA Gaps | 3 | ⚪ Pending |
| Vendor Lock-in & Portability | 3 | ⚪ Pending |

**Overall Risk Level:** ⚪ **PENDING - MANUAL RESEARCH REQUIRED**

**Recommendation:** ⏸️ **ON HOLD** - Complete assessment after manual document review

---

## Next Steps

### Immediate Actions Required:

1. **Access Legal Documents:**
   - Visit https://gamma.app in a web browser
   - Scroll to footer
   - Click "Terms of Service" link
   - Click "Privacy Policy" link
   - Save documents to `apps/gamma/legal-docs/`

2. **Research Key Questions:**
   - Does Gamma train AI on user content?
   - Is there an opt-out for AI training?
   - What export formats are available?
   - Are there compliance certifications?

3. **Complete Assessment:**
   - Fill in all 22 questions in rubric
   - Mark risk levels (✅/❌/⚠️)
   - Document mitigation options

---

## Known Information

### Product Overview:
- AI-powered presentation platform
- Creates interactive presentations and documents
- AI-generated content from text prompts
- Templates and themes available
- Collaboration features

### Typical AI Presentation Tool Risks:
Based on industry patterns, Gamma likely:
- May train AI on user content (common practice)
- May not offer training opt-out (common limitation)
- Likely has broad license to user content
- May have limited export options
- Likely lacks enterprise security on free tier

**Verification Required:** Manual review of actual Terms and Privacy Policy

---

## Contact Information

**Gamma:**
- Website: https://gamma.app
- Support: Look for contact link on website
- Twitter/X: @gamma_app

---

*Assessment pending - Manual research required*  
*⚪ PENDING - Awaiting legal document access*
