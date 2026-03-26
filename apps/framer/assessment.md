# App Name: Framer

**Assessment Date:** 2026-03-26  
**Assessed By:** Aqua Regia  
**App Version/Plan:** Free/Mini/Basic/Pro/Enterprise (Web Design & Prototyping)  

---

## Document Sources

- **Terms of Service:** https://www.framer.com/legal/terms-of-service/ (Accessed: 2026-03-26)
- **Privacy Statement:** https://www.framer.com/legal/privacy-statement/ (Accessed: 2026-03-26)
- **Data Processing Addendum:** https://www.framer.com/legal/data-processing-addendum/ (Accessed: 2026-03-26)
- **Last Updated:** May 24, 2022 (ToS), January 11, 2021 (Privacy)

---

## Assessment Rubric

### 1. Data Training & Model Ingestion

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 1.1 | Whether your code, designs, or prompts are used to train the vendor's AI models — often buried in the free tier ToS but opted out on paid/enterprise plans | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - Framer's ToS does not explicitly address AI training on user content. Contact Framer for clarification on AI features and training practices. | ToS Section 2.4 mentions "automated systems may analyze your Content using techniques such as machine learning in order to improve our Services" but does not specify AI model training. |
| 1.2 | Whether inputs are shared across tenants or used to improve shared models | **NOT SPECIFIED** | ⚠️ | **RESEARCH REQUIRED** - No explicit statement about cross-tenant data sharing for AI. Contact Framer for details. | Privacy Statement mentions "machine learning in order to improve our Services and Software" but scope unclear. |
| 1.3 | Residual data retention after account deletion | **NOT SPECIFIED** | ⚠️ | **REQUEST DELETION** - No explicit data retention timeline. Contact support@framer.com for deletion requests. | Privacy Statement does not specify retention periods post-account deletion. |

### 2. Data Residency & Sovereignty

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 2.1 | Where data is stored and processed (US, EU, etc.) — critical for GDPR, Quebec Bill 25, and clients in regulated industries | **EU/US** | ⚠️ | **DPA AVAILABLE** - Framer B.V. (Netherlands) and Framer Inc. (US). DPA includes Standard Contractual Clauses for EU data transfers. | Privacy Statement: "Framer B.V., Framer Inc. and its respective affiliates". DPA available for EU compliance. |
| 2.2 | Whether the vendor can move data across regions without notice | **NOT SPECIFIED** | ⚠️ | **MONITOR TERMS** - No explicit restriction found. DPA may include data location commitments. | Review DPA for specific data location guarantees. |
| 2.3 | Lack of contractual guarantees on data location in free tiers | **DPA AVAILABLE TO ALL** | ✅ | **SIGN DPA** - Framer offers Data Processing Addendum for all customers, not just Enterprise. | DPA available at https://www.framer.com/legal/data-processing-addendum/ |

### 3. Intellectual Property Ownership

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 3.1 | Who owns outputs — generated code, UI designs, prototypes | **CUSTOMER OWNS CONTENT** | ✅ | **N/A - Clear ownership** | ToS Section 3.3: "As between the Parties, Customer shall own all rights in and Framer disclaims any rights in Customer's Content." |
| 3.2 | Whether the vendor claims a license to use your outputs for any purpose | **LIMITED LICENSE FOR SERVICE OPERATION** | ⚠️ | **STANDARD SaaS LICENSE** - Framer claims license only to operate the service, not for other purposes. | ToS Section 4.1: License granted "solely to provide the Services to Customer". Limited to service operation. |
| 3.3 | IP indemnification gaps: if the AI generates code or design assets that infringe on a third party's copyright, who is liable? Most free tiers offer zero indemnification | **NOT SPECIFIED** | ⚠️ | **LEGAL REVIEW** - No explicit IP indemnification clause found. Customer indemnifies Framer for Content. | ToS Section 5.2: Customer indemnifies Framer. No reciprocal IP indemnification found. |
| 3.4 | Work-for-hire ambiguity when outputs are produced inside a client engagement | **NOT SPECIFIED** | ⚠️ | **CLIENT CONTRACT CLARITY** - Customer owns Content, but clarify work-for-hire in client contracts. | Customer ownership clear, but specific work-for-hire language not present. |

### 4. Security & Access Controls

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 4.1 | Free tiers typically have no SSO, MFA enforcement, or SCIM provisioning — a shadow IT red flag | **SSO ON PRO+** | ⚠️ | **UPGRADE TO PRO/ENTERPRISE** - Free/Mini/Basic: No SSO. Pro: Google SSO. Enterprise: Advanced SSO/SAML. | Pricing: Free/Mini/Basic (no SSO), Pro (Google SSO), Enterprise (Advanced SSO/SAML). |
| 4.2 | No audit logs or access review capabilities, which breaks CMMC and SOC 2 requirements | **NOT SPECIFIED** | ⚠️ | **ENTERPRISE REQUIRED** - No explicit audit log mention. Enterprise likely includes advanced features. | Contact Framer for Enterprise audit capabilities. |
| 4.3 | Shared infrastructure with no tenant isolation guarantees | **SHARED SAAS** | ⚠️ | **ENTERPRISE NEGOTIATION** - Standard multi-tenant SaaS. Enterprise may offer dedicated options. | Typical SaaS architecture. No specific tenant isolation guarantees in public docs. |

### 5. Compliance & Certifications

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 5.1 | Free tiers rarely come with BAAs (Business Associate Agreements) — a hard blocker for HIPAA-covered work | **NOT SPECIFIED** | ⚠️ | **CONTACT FRAMER** - No explicit BAA mention. Contact Framer for healthcare compliance options. | ToS Section 2.4(i): Prohibits storing "sensitive" PII. Likely not HIPAA-ready. |
| 5.2 | No SOC 2 Type II, ISO 27001, or FedRAMP coverage on free plans | **NOT SPECIFIED** | ⚠️ | **REQUEST DOCUMENTATION** - No certifications listed in public documents. Contact Framer for compliance reports. | Check Framer Security page or contact for SOC 2/ISO 27001 status. |
| 5.3 | Inability to sign a DPA (Data Processing Agreement) required under GDPR and similar frameworks | **DPA AVAILABLE** | ✅ | **SIGN DPA** - Framer provides DPA for GDPR compliance. Available to all customers. | DPA: https://www.framer.com/legal/data-processing-addendum/ |

### 6. Contractual & SLA Gaps

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 6.1 | No uptime SLA or liability cap on free tiers — enterprise risk and legal teams won't sign off on mission-critical usage | **NO SLA IN FREE** | ❌ | **UPGRADE TO ENTERPRISE** - Free/Mini/Basic/Pro: No SLA. Enterprise: Custom SLA available. | ToS Section 2.7: Standard support only (email, business hours). Enterprise for SLA. |
| 6.2 | Unilateral right to change ToS with short or no notice | **MODIFICATION CLAUSE** | ⚠️ | **MONITOR TERMS** - ToS Section 13.4: Framer may modify with notice. Monitor for changes. | ToS Section 13.4: "Framer may modify this Agreement from time to time". |
| 6.3 | No data breach notification obligations contractually specified | **NOT SPECIFIED** | ⚠️ | **DPA REVIEW** - DPA may include breach notification. Review DPA Section on security incidents. | Privacy Statement mentions "accidental or unauthorized access" notification in DPA context. |

### 7. Vendor Lock-in & Portability

| # | Question | Answer | Risk Level | Mitigation/Opt-Out | Notes |
|---|----------|--------|------------|-------------------|-------|
| 7.1 | Export limitations that make it hard to move data or designs out | **STANDARD EXPORT** | ✅ | **USE EXPORT FEATURES** - Framer allows export of code, designs, and prototypes. No proprietary lock-in. | Framer exports to standard web formats (HTML, CSS, React). Can self-host or export code. |
| 7.2 | Proprietary file formats with no open standard equivalent | **WEB STANDARDS** | ✅ | **N/A - Open formats** | Framer uses standard web technologies (HTML, CSS, React). No proprietary file format lock-in. |
| 7.3 | API access gated behind paid tiers, preventing integration into enterprise toolchains | **API NOT MENTIONED** | ⚠️ | **RESEARCH REQUIRED** - No explicit API documentation found. Check Framer Developers documentation. | Visit https://www.framer.com/developers/ for API availability. |

---

## Summary

| Risk Category | Risk Items | Status |
|---------------|-----------|--------|
| Data Training & Model Ingestion | 3 | 🟡 Medium Risk |
| Data Residency & Sovereignty | 3 | 🟡 Medium Risk |
| Intellectual Property Ownership | 4 | 🟡 Medium Risk |
| Security & Access Controls | 3 | 🟡 Medium Risk |
| Compliance & Certifications | 3 | 🟡 Medium Risk |
| Contractual & SLA Gaps | 3 | 🟡 Medium Risk |
| Vendor Lock-in & Portability | 3 | 🟢 Low Risk |

**Overall Risk Level:** 🟡 **MEDIUM RISK**

**Recommendation:** ⚠️ **APPROVED WITH CONDITIONS** - Suitable for most use cases with Enterprise upgrade for sensitive projects

---

## Key Findings

### Positive Findings (✅)
1. **Customer owns all Content** - Clear ownership in ToS Section 3.3
2. **DPA available** - GDPR compliance support for all tiers
3. **EU/US data handling** - SCCs for EU data transfers
4. **Standard export formats** - HTML, CSS, React (no lock-in)
5. **No proprietary formats** - Uses open web standards

### Warnings (⚠️)
1. **AI training not specified** - Unclear if Framer trains AI on user content
2. **No explicit certifications** - SOC 2/ISO 27001 status unclear
3. **SSO only on Pro+** - Free/Basic lack SSO
4. **No SLA on lower tiers** - Enterprise required for uptime guarantees
5. **IP indemnification unclear** - No explicit vendor indemnification

### Critical Issues (❌)
- **NONE IDENTIFIED**

---

## Comparison to Similar Tools

| Feature | Framer | Webflow | Figma |
|---------|--------|---------|-------|
| **Code Export** | ✅ React/HTML | ✅ HTML/CSS | ❌ Limited |
| **DPA Available** | ✅ Yes | ✅ Yes | ✅ Yes |
| **SSO** | ✅ Pro+ | ✅ Enterprise | ✅ Enterprise |
| **AI Training Clear** | ⚠️ Unclear | ⚠️ Unclear | ⚠️ Unclear |

---

## Mitigation Strategies

### Immediate Actions
1. **Contact Framer** to clarify AI training practices
2. **Sign DPA** for GDPR compliance
3. **Review Security** documentation for certifications

### Enterprise Upgrade For:
1. **SSO/SAML** - Pro/Enterprise required
2. **SLA** - Enterprise only
3. **Audit logs** - Likely Enterprise only
4. **HIPAA/BAA** - Contact Framer

### Workarounds
1. **Use Pro tier** for Google SSO
2. **Export code regularly** for backup
3. **Self-host** published sites for control

---

## Next Steps

- [ ] Contact Framer (support@framer.com) to clarify:
  - AI training on user content
  - SOC 2/ISO 27001 certifications
  - API availability
- [ ] Sign DPA for GDPR compliance
- [ ] Evaluate Enterprise tier for:
  - Advanced SSO
  - SLA requirements
  - Audit capabilities
- [ ] Monitor ToS changes (Section 13.4)

---

*Assessment completed using AI Apps TnC Framework*  
*🟡 MEDIUM RISK - Clarify AI training practices before sensitive use*
