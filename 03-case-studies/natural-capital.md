# Natural Capital — SaaS Platform for Green Deal Clients

## Context
- **Product:** Natural Capital
- **Company / Environment:** NTT Data
- **Market / Industry:** Sustainability, Environmental Consulting, Green Deal
- **Product Stage:** Discovery and Delivery (MVP)

---

## Problem Statement

Green Deal clients needed a tool to financially measure the impact of their activities on nature and translate complex regulatory and sustainability requirements into actionable digital workflows.

Specifically, they required:
- A clear way to define, create, and manage **geospatial (GIS) data**
- The ability to **generate shape files directly within the platform**
- Guidance through complex environmental and regulatory processes
- Guidance through measurements on impacts and ecosystem services

Before this product, much of this work was:
- Manual (Excel)
- Fragmented across tools
- Highly dependent on external GIS experts and shape files

---

## Goals & Success Criteria

### User Outcomes
- Users can create and manage shape files directly in the platform
- Users are guided step by step through complex sustainability workflows
- Reduced dependency on external GIS tools and experts

### Business Outcomes
- Increased value proposition for Green Deal clients
- Differentiation through integrated GIS capabilities
- Strong foundation for future sustainability-related products

---

## Constraints

### Technical
- No existing GIS capabilities in the platform
- Complex integration of geospatial logic into a SaaS product

### Business
- MVP needed to demonstrate clear value quickly
- High expectations due to strategic importance of sustainability

### Legal / Regulatory
- Limited internal knowledge of environmental regulations
- Green Deal compliance requirements

### Time / Team
- Development team based in Spain
- Newly created testing and development team in India
- Distributed teams across time zones

### Personal
- No prior experience in:
  - GIS systems
  - Nature-related business domains
  - Environmental regulations

---

## Discovery & Insights

### Key Insights
- GIS capabilities were not “nice to have” but **core to the product value**
- Users struggled most with **knowing what to do next**, not just with tools
- Existing GIS solutions were powerful but inaccessible to non-experts

### Invalidated Assumptions
- That users would prefer exporting data to external GIS tools
- That basic GIS visualization would be sufficient for an MVP

### Evidence Used
- Stakeholder interviews
- Early user discussions
- Workshops with domain experts
- Internal reviews with sustainability teams

---

## Options Considered

### Option A: External GIS Tool Integration
- Pros: Faster initial delivery
- Cons: Reduced control, fragmented user experience, high licence cost

### Option B: Minimal GIS Visualization Only
- Pros: Lower complexity
- Cons: Did not solve core user problem

### Option C: Native Shape File Creation and Guided GIS Workflow
- Pros: High value, strong differentiation
- Cons: High complexity and learning curve

---

## Decision & Rationale

We chose **Option C**: building native GIS capabilities into the platform.

Despite the complexity, this option:
- Delivered the highest user and business value
- Positioned the product as a true end-to-end solution
- Reduced long-term dependency on external tools

The decision required embracing uncertainty and learning rapidly.

---

## Delivery Summary

### What Was Built
- MVP with integrated GIS functionality
- Ability to create and manage shape files directly in the platform
- Guided user flows to support non-GIS experts
- Collaboration between Spain-based development and India-based testing teams

### What Was Intentionally Not Built
- Advanced GIS expert features
- Full regulatory automation
- Extensive customization options

---

## Results

### Quantitative
- MVP delivered with core GIS value demonstrated
- Positive internal and client feedback on differentiation

### Qualitative
- Stakeholders recognized the strategic importance of the solution
- Users valued guidance as much as functionality

---

## What Worked Well
- Close collaboration between distributed teams
- Continuous alignment between business and technical constraints
- Strong focus on MVP value rather than completeness

---

## What Didn’t Work
- Underestimated learning curve of GIS concepts
- Initial communication gaps between distributed teams (spanish vs english)
- Discovery required more time than initially planned

---

## Key Learnings
- Domain ignorance can be mitigated with strong discovery practices
- High-value features often sit at the intersection of complexity and differentiation
- Guidance and UX matter as much as technical capability

---

## What I’d Do Differently
- Invest earlier in GIS and regulatory domain learning
- Introduce domain experts earlier into discovery
- Formalize knowledge sharing between teams sooner

---

## Final Takeaway

When building in unfamiliar domains, **clarity of problem and focus on user value** matter more than prior expertise.
Strong discovery, intentional MVP scope, and continuous learning can turn complexity into competitive advantage.

## Architecture & Workflow Diagram

```mermaid
flowchart TD
    U["Green Deal User (Consultant / SME)"]
    P["Natural Capital SaaS Platform"]

    G["Guided Workflow Engine
    - Regulatory steps
    - User guidance"]

    GIS["GIS Integration Layer
    - Map visualization
    - Geometry validation"]

    SHP["Shape File Creation Engine
    - Polygon creation
    - Attribute mapping"]

    OUT["Sustainability Outputs
    - Reports
    - Compliance artifacts"]

    U --> P
    P --> G
    G --> GIS
    GIS --> SHP
    SHP --> OUT
