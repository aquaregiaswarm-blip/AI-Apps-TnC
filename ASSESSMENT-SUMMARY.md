# AI Apps TnC - Assessment Summary

**Date:** March 26, 2026  
**Status:** Framework Complete, Assessments Pending

---

## Apps to Assess (10 Total)

| # | App Name | Category | Status | Folder |
|---|----------|----------|--------|--------|
| 1 | **Figma** | UI/Prototyping | 🔲 Not Started | `apps/figma/` |
| 2 | **Canva Magic Design** | Graphic Design | 🔲 Not Started | `apps/canva-magic-design/` |
| 3 | **Uizard** | UI Mockups | 🔲 Not Started | `apps/uizard/` |
| 4 | **Google Stitch** | UI Design (Labs) | 🔲 Not Started | `apps/google-stitch/` |
| 5 | **Adobe Firefly** | Generative AI | 🔲 Not Started | `apps/adobe-firefly/` |
| 6 | **Framer** | Web Design | 🔲 Not Started | `apps/framer/` |
| 7 | **Locofy.ai** | Design-to-Code | 🔲 Not Started | `apps/locofy-ai/` |
| 8 | **Penpot** | Open Source Design | 🔲 Not Started | `apps/penpot/` |
| 9 | **Relume** | Sitemap/Wireframes | 🔲 Not Started | `apps/relume/` |
| 10 | **Galileo AI** | UI Generation | 🔲 Not Started | `apps/galileo-ai/` |

---

## Quick Reference: Legal Document URLs

### 1. Figma
- ToS: https://www.figma.com/legal/tos/
- Privacy: https://www.figma.com/legal/privacy/
- AI Terms: https://www.figma.com/legal/ai-terms/
- DPA: https://www.figma.com/legal/dpa/

### 2. Canva Magic Design
- ToS: https://www.canva.com/policies/terms-of-use/
- Privacy: https://www.canva.com/policies/privacy-policy/
- AI Terms: https://www.canva.com/policies/ai-terms/

### 3. Uizard
- ToS: https://uizard.io/terms-of-use/
- Privacy: https://uizard.io/privacy-policy/

### 4. Google Stitch
- Google Terms: https://policies.google.com/terms
- Privacy: https://policies.google.com/privacy
- AI Principles: https://ai.google/principles/

### 5. Adobe Firefly
- ToS: https://www.adobe.com/legal/terms.html
- Privacy: https://www.adobe.com/privacy/policy.html
- Firefly Terms: https://www.adobe.com/legal/licenses-terms/adobe-gen-ai-user-guidelines.html

### 6. Framer
- ToS: https://www.framer.com/terms/
- Privacy: https://www.framer.com/privacy/

### 7. Locofy.ai
- ToS: https://www.locofy.ai/terms-of-service
- Privacy: https://www.locofy.ai/privacy-policy

### 8. Penpot
- ToS: https://penpot.app/terms
- Privacy: https://penpot.app/privacy

### 9. Relume
- ToS: https://www.relume.io/terms
- Privacy: https://www.relume.io/privacy

### 10. Galileo AI
- ToS: https://www.usegalileo.ai/terms
- Privacy: https://www.usegalileo.ai/privacy

---

## Assessment Workflow

For each app:

1. **Download Legal Documents**
   ```bash
   cd apps/[app-name]/
   mkdir legal-docs
   # Save ToS, Privacy Policy, AI Terms, DPA
   ```

2. **Create Assessment File**
   ```bash
   cp ../../templates/assessment-template.md assessment.md
   # Edit with app-specific information
   ```

3. **Research & Answer Questions**
   - Read each legal document carefully
   - Answer all 22 questions in the rubric
   - Mark risk level: ✅, ❌, or ⚠️
   - Add notes for context

4. **Commit Progress**
   ```bash
   git add apps/[app-name]/
   git commit -m "Complete assessment for [App Name]"
   ```

---

## Key Risk Areas to Focus On

### High Priority (Likely Issues)
1. **Data Training (1.1-1.3)** - Most AI tools train on user content
2. **IP Ownership (3.1-3.4)** - Output ownership varies widely
3. **Compliance (5.1-5.3)** - Free tiers lack certifications
4. **SLAs (6.1-6.3)** - Free tiers have no uptime guarantees

### Medium Priority
5. **Data Residency (2.1-2.3)** - Important for GDPR compliance
6. **Security (4.1-4.3)** - SSO/MFA usually enterprise-only
7. **Lock-in (7.1-7.3)** - Export limitations common

---

## Expected Risk Patterns

### Free Tiers (High Risk)
- ❌ Data used for training
- ❌ No indemnification
- ❌ No SLA
- ❌ No SSO/MFA
- ❌ No DPA/BAA

### Enterprise/Paid (Lower Risk)
- ✅ Training opt-out available
- ✅ Some indemnification
- ✅ SLA included
- ✅ SSO/MFA available
- ✅ DPA available

### Open Source (Variable)
- ⚠️ Self-hosted = data control
- ⚠️ Community support only
- ⚠️ No vendor indemnification

---

## Next Steps

1. [ ] Download legal docs for each app
2. [ ] Complete assessment.md for each app
3. [ ] Mark risk levels (✅/❌/⚠️)
4. [ ] Create summary matrix
5. [ ] Push to GitHub

---

*Framework ready for assessments*  
*🜆 Aqua Regia*
