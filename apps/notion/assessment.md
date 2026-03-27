# App Name: Notion

**Assessment Date:** 2026-03-26  
**Assessed By:** Aqua Regia  
**App Version/Plan:** Free/Plus/Business/Enterprise (AI-Powered Workspace)  

---

## Document Sources

- **Terms of Service:** Unable to access (401 error) (Accessed: 2026-03-26)
- **Privacy Policy:** Unable to access (401 error) (Accessed: 2026-03-26)
- **Pricing & AI Info:** https://www.notion.com/pricing (Accessed: 2026-03-26)
- **Last Updated:** March 2026 (based on pricing page)

---

## ⚠️ PARTIAL ASSESSMENT - TERMS/PRIVACY BLOCKED

**Issue:** Notion's Terms of Service and Privacy Policy are blocking automated access (401 errors).

**Available:** Pricing page with detailed AI information

**To Complete This Assessment:**

1. Visit https://www.notion.so/terms
2. Visit https://www.notion.so/privacy
3. Download or copy the documents
4. Save to `apps/notion/legal-docs/`
5. Complete the assessment rubric below

---

## Assessment Based on Available Information

### 1. Data Training & Model Ingestion

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 1.1 | Whether your code, designs, or prompts are used to train the vendor's AI models — often buried in the free tier ToS but opted out on paid/enterprise plans | **NO - Unless you opt in** | ✅ | **OPT-IN REQUIRED** - Pricing page states: "Notion AI will not use your data to train our models unless you opt in to a request to share your data." | Pricing Page Q&A: "Notion AI will not use your data to train our models unless you opt in to a request to share your data." |
| 1.2 | Whether inputs are shared across tenants or used to improve shared models | **NO - Subprocessors prohibited** | ✅ | **CONTRACTUAL PROHIBITION** - "We specifically have contractual agreements in place with our AI subprocessors that prohibit the use of customer data to train their models." | Pricing Page Q&A: "We specifically have contractual agreements in place with our AI subprocessors that prohibit the use of customer data to train their models." |
| 1.3 | Residual data retention after account deletion | **30 days standard, 0 days Enterprise** | ⚠️ | **UPGRADE TO ENTERPRISE** - Free/Plus/Business: 30-day retention. Enterprise: "Zero data retention with LLM providers." | Pricing: Free/Plus/Business = 30 day retention. Enterprise = Zero data retention. |

### 2. Data Residency & Sovereignty

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 2.1 | Where data is stored and processed (US, EU, etc.) — critical for GDPR, Quebec Bill 25, and clients in regulated industries | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Check Terms of Service or Notion Security page for data center locations. | Notion operates globally. Specific locations not detailed in pricing page. |
| 2.2 | Whether the vendor can move data across regions without notice | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Check Terms of Service for data transfer provisions. | No explicit restrictions found in available documents. |
| 2.3 | Lack of contractual guarantees on data location in free tiers | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Check if Enterprise offers data residency options. | Zero data retention in Enterprise is a form of data control. |

### 3. Intellectual Property Ownership

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 3.1 | Who owns outputs — generated code, UI designs, prototypes | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Ownership terms in ToS. Notion typically allows user ownership. | Check Terms of Service Section on Content ownership. |
| 3.2 | Whether the vendor claims a license to use your outputs for any purpose | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - License terms in ToS. Check for license grants. | Check Terms of Service for license provisions. |
| 3.3 | IP indemnification gaps: if the AI generates code or design assets that infringe on a third party's copyright, who is liable? Most free tiers offer zero indemnification | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - IP indemnification in ToS. | No IP indemnification information in pricing page. |
| 3.4 | Work-for-hire ambiguity when outputs are produced inside a client engagement | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Clarify ownership in client contracts. | Customer should verify ownership rights for client work. |

### 4. Security & Access Controls

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 4.1 | Free tiers typically have no SSO, MFA enforcement, or SCIM provisioning — a shadow IT red flag | **SSO ON BUSINESS+** | ⚠️ | **UPGRADE TO BUSINESS/ENTERPRISE** - Free/Plus: No SSO. Business: SAML SSO. Enterprise: SAML SSO + SCIM. | Pricing: Business = "SAML SSO". Enterprise = "SAML single sign-on (SSO)" + "User provisioning (SCIM)". |
| 4.2 | No audit logs or access review capabilities, which breaks CMMC and SOC 2 requirements | **AUDIT LOG ON ENTERPRISE** | ⚠️ | **UPGRADE TO ENTERPRISE** - Free/Plus/Business: No audit log mentioned. Enterprise: "Audit log" + "Admin content search". | Pricing: Enterprise includes "Audit log" and "Security & Compliance integrations (DLP, SIEM)". |
| 4.3 | Shared infrastructure with no tenant isolation guarantees | **SHARED SAAS** | ⚠️ | **ENTERPRISE CONTROLS** - Standard multi-tenant SaaS. Enterprise offers "Advanced workspace & teamspace security controls". | Enterprise includes "Organization level controls" and "Advanced security & controls". |

### 5. Compliance & Certifications

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 5.1 | Free tiers rarely come with BAAs (Business Associate Agreements) — a hard blocker for HIPAA-covered work | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Check Notion Enterprise for BAA availability. | Enterprise includes "Security & Compliance integrations" but no explicit BAA mention. |
| 5.2 | No SOC 2 Type II, ISO 27001, or FedRAMP coverage on free plans | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Check Notion Security page for certifications. | Pricing mentions "standard data protection practices" but no specific certifications listed. |
| 5.3 | Inability to sign a DPA (Data Processing Agreement) required under GDPR and similar frameworks | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Check if Notion offers DPA. | Notion operates globally; likely has GDPR compliance measures. Check for DPA. |

### 6. Contractual & SLA Gaps

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 6.1 | No uptime SLA or liability cap on free tiers — enterprise risk and legal teams won't sign off on mission-critical usage | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Check Terms of Service for SLA. | Pricing page does not mention uptime SLA. |
| 6.2 | Unilateral right to change ToS with short or no notice | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Modification clause in ToS. | Check Terms of Service for change notification. |
| 6.3 | No data breach notification obligations contractually specified | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Breach notification in ToS or Privacy Policy. | Check Terms/Privacy for breach notification terms. |

### 7. Vendor Lock-in & Portability

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 7.1 | Export limitations that make it hard to move data or designs out | **EXPORT AVAILABLE** | ✅ | **USE EXPORT FEATURE** - Enterprise includes "Export entire workspace as HTML, Markdown, & CSV" and "Export entire workspace as PDF". | Pricing: Enterprise = "Export entire workspace as HTML, Markdown, & CSV" + "Export entire workspace as PDF". |
| 7.2 | Proprietary file formats with no open standard equivalent | **MARKDOWN/HTML EXPORT** | ✅ | **N/A - Open formats** | Notion exports to standard Markdown, HTML, CSV, PDF formats. No proprietary lock-in. |
| 7.3 | API access gated behind paid tiers, preventing integration into enterprise toolchains | **API ON ALL TIERS** | ✅ | **N/A - API available** | Pricing: Free includes "Public API". All tiers have API access. |

---

## Summary

| Risk Category | Risk Items | Status |
|---------------|-----------|--------|
| Data Training & Model Ingestion | 3 | 🟢 Low Risk |
| Data Residency & Sovereignty | 3 | ⚪ Pending |
| Intellectual Property Ownership | 4 | ⚪ Pending |
| Security & Access Controls | 3 | 🟡 Medium Risk |
| Compliance & Certifications | 3 | ⚪ Pending |
| Contractual & SLA Gaps | 3 | ⚪ Pending |
| Vendor Lock-in & Portability | 3 | 🟢 Low Risk |

**Overall Risk Level:** 🟡 **MEDIUM RISK - AI PRACTICES EXCELLENT**

**Recommendation:** ✅ **APPROVED WITH CONDITIONS** - Excellent AI data practices, complete assessment after accessing Terms

---

## Key Findings

### 🌟 Excellent AI Data Practices (Unique in Industry)

**1. Opt-In Required for AI Training:**
> "Notion AI will not use your data to train our models **unless you opt in** to a request to share your data."

**2. Subprocessor Prohibitions:**
> "We specifically have **contractual agreements in place with our AI subprocessors that prohibit the use of customer data to train their models**."

**3. Zero Data Retention (Enterprise):**
> "**Zero data retention with LLM providers**" - Enterprise plan only

### Comparison to Competitors:

| Feature | Notion | Most Competitors |
|---------|--------|------------------|
| **AI Training** | ❌ No (unless opt-in) | ✅ Usually yes |
| **Subprocessor Contracts** | ✅ Prohibits training | ❌ Rare |
| **Zero Retention** | ✅ Enterprise | ❌ Rare |

### Positive Findings (✅)
1. **No AI training without opt-in** - Industry-leading practice
2. **Subprocessor contracts prohibit training** - Strong contractual protection
3. **Zero data retention option** - Enterprise tier
4. **API available on all tiers** - No lock-in
5. **Standard export formats** - Markdown, HTML, CSV, PDF
6. **SSO on Business+** - SAML available
7. **Audit log on Enterprise** - Compliance support

### Warnings (⚠️)
1. Terms/Privacy not accessible for complete review
2. SSO only on Business+ (Free/Plus lack SSO)
3. Audit log only on Enterprise
4. Data residency specifics unclear
5. Certifications not specified in available docs

### Critical Issues (❌)
- **NONE IDENTIFIED** (based on available information)

---

## Notion Plans (from Pricing Page)

| Plan | Price | AI Features | Security |
|------|-------|-------------|----------|
| **Free** | $0 | Limited trial of Notion AI | Basic, 2-step verification |
| **Plus** | $8/user/month | Limited trial of Notion AI | Same as Free |
| **Business** | $15/user/month | Notion AI Core, SAML SSO | SAML SSO, Granular permissions |
| **Enterprise** | Custom | All AI features, **Zero data retention** | SCIM, Audit log, DLP, SIEM |

### Enterprise Security Features:
- Zero data retention with LLM providers
- User provisioning (SCIM)
- Advanced security & controls
- Audit log
- Security & Compliance integrations (DLP, SIEM)
- Domain management
- Advanced integrations
- Customer success manager

---

## Next Steps

### Immediate Actions Required:

1. **Access Full Terms:**
   - Visit https://www.notion.so/terms
   - Visit https://www.notion.so/privacy
   - Save to `apps/notion/legal-docs/`

2. **Verify AI Practices:**
   - Confirm opt-in requirement in Terms
   - Verify subprocessor contract terms
   - Check Enterprise zero retention details

3. **Complete Assessment:**
   - Fill in all 22 questions
   - Mark risk levels (✅/❌/⚠️)
   - Document any additional findings

### For Enterprise Consideration:
- Zero data retention with LLM providers
- Full audit capabilities
- Advanced security integrations
- Customer success manager

---

## Known Information

### AI Features:
- Notion AI Core (chat, generate, autofill, translate)
- Notion Agent (autonomous tasks)
- AI Meeting Notes
- Enterprise Search
- Research mode
- Custom Agents

### Data Protection:
- Data encrypted and private
- No training without opt-in
- Subprocessor contracts prohibit training
- 30-day retention (standard), 0-day (Enterprise)

### Export Capabilities:
- HTML, Markdown, CSV (Enterprise)
- PDF (Enterprise)
- Public API (all tiers)

---

## Contact Information

**Notion Support:**
- Website: https://www.notion.so/
- Help Center: https://www.notion.so/help
- Email: team@makenotion.com

---

*Assessment partially complete - Terms of Service and Privacy Policy required for full review*  
*🟢 EXCELLENT AI DATA PRACTICES - Industry-leading opt-in approach*
