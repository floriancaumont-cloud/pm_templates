# SIRVEC — Evidence Tracking & Chain of Custody Platform

## Context
- **Product:** SIRVEC
- **Client:** Guardia Civil
- **Market / Industry:** Law Enforcement, Justice, Public Sector
- **Product Type:** Web platform + Mobile App
- **Product Stage:** Delivery (MVP)

---

## Problem Statement

The Guardia Civil needed a secure and reliable way to **register crime scenes, track evidence, and guarantee the chain of custody** from the moment evidence is collected until it is presented in court.

While technology could clearly improve accuracy and traceability, the **core risk was not technical**.

The real problem was:
> If judges and the justice system do not legally accept the platform and its technology, the product has no value.

In particular, the use of **blockchain for evidence tracking** raised strong concerns in a system historically based on **paper documentation and manual signatures**.

---

## Goals & Success Criteria

### User Outcomes
- Officers can register crime scenes digitally
- Evidence can be tracked end-to-end with full traceability
- Chain of custody is clear, immutable, and auditable

### Legal & Institutional Outcomes
- Evidence registered through the platform is legally admissible
- Judges can trust the integrity of the custody chain
- Compliance with Ministry of Justice guidelines

### Business Outcomes
- MVP accepted by the client
- Platform positioned as a reliable foundation for future expansion

---

## Constraints

### Legal & Regulatory
- Blockchain adoption in justice systems is still emerging
- Strong legal scrutiny from judges and prosecutors
- Strict compliance with Spanish and European law
- Ministry of Justice acceptance was mandatory

### Institutional
- Evidence handling is the **core mission** of criminal investigation
- Zero tolerance for legal ambiguity
- High reputational and operational risk

### Product
- MVP already in delivery
- Limited room for experimentation in production
- Technology choices had to be justified, not just implemented

---

## Discovery & Validation Work

### Key Insight
The biggest risk was **legal legitimacy**, not usability or performance.

Without legal acceptance:
- Officers would not use the platform
- Evidence could be challenged in court
- The entire system would be invalidated

### Validation Approach
Instead of user discovery, the focus was on **legal discovery**:
- Understanding how evidence is evaluated by judges
- Mapping existing legal precedents
- Translating technical guarantees into legal language

---

## Options Considered

### Option A: Traditional Digital System (No Blockchain)
- Pros: Easier legal acceptance
- Cons: Lower guarantees of immutability and traceability

### Option B: Blockchain Without Legal Backing
- Pros: Strong technical guarantees
- Cons: High risk of rejection in court

### Option C: Blockchain + Formal Legal Justification
- Pros: Strong technical and legal foundation
- Cons: Longer validation process

---

## Decision & Rationale

We chose **Option C**:  
Using blockchain **only after proving its legal admissibility**.

The decision was based on:
- Long-term trust over short-term delivery
- Legal certainty as a core product requirement
- Alignment with existing European and Spanish precedents

---

## Legal Validation Strategy

### Actions Taken
- Engaged a **legal specialist (lawyer)** with expertise in:
  - European law
  - Spanish case law
  - Blockchain-related legal precedents
- Produced a **formal legal report** addressing:
  - Blockchain as a valid mechanism for evidence integrity
  - Compliance with European regulations
  - Spanish judicial cases where blockchain was accepted

### Outcome
- Demonstrated that blockchain can be legally used to:
  - Guarantee integrity
  - Ensure immutability
  - Strengthen chain-of-custody evidence

This report became a **key artifact** for client and institutional approval.

---

## Delivery Summary

### What Was Built
- Web platform for evidence registration
- Mobile app for on-site crime scene usage
- Blockchain-based custody chain tracking
- Audit-ready evidence history

### What Was Critical Beyond Code
- Legal documentation
- Clear explanation of technology to non-technical stakeholders
- Alignment between technical design and legal language

---

## Results

### Qualitative
- Increased client confidence in the platform
- Reduced resistance to blockchain usage
- Stronger trust in the integrity of the custody chain

### Strategic
- MVP positioned as legally viable
- Foundation established for broader institutional adoption

---

## What Worked Well
- Treating legal validation as a product requirement
- Early involvement of legal expertise
- Translating technical concepts into judicial language

---

## What Didn’t Work
- Initial underestimation of legal resistance
- Complexity of aligning legal and technical timelines
- Need for deeper early engagement with judicial perspectives

---

## Key Learnings
- In regulated environments, **legality is a feature**
- Technical truth is not enough without institutional trust
- Blockchain value must be explained in legal, not technical, terms

---

## What I’d Do Differently
- Involve legal experts even earlier
- Formalize legal discovery as part of product discovery
- Create legal-facing documentation in parallel with development

---

## Final Takeaway

In justice systems, **trust is the product**.

Technology only creates value when it is legally accepted, institutionally trusted, and clearly understood by those who ultimately decide its validity: the judges.
