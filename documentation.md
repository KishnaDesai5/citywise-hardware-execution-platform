# UX Documentation – Citywise Hardware Execution Platform

---

## 1. Problem Framing

This platform addresses a core execution gap faced by hardware startups:  
the inability to confidently convert ideas into real-world execution due to uncertainty around talent structure, coordination, trust, and risk.

Unlike software hiring or freelance marketplaces, hardware execution failures are expensive and irreversible.  
The UX is therefore designed to prioritize **decision correctness over speed**.

---

## 2. User Journey & Information Architecture

### Primary Flow
Intent → City Selection → Engagement Recommendation → Cluster Discovery → Trust Evaluation → Commitment

### Rationale
- Early stages reduce cognitive load
- High-commitment actions are delayed until trust is established
- Browsing is intentionally constrained to prevent structurally wrong decisions

This flow reflects how real hardware founders evaluate execution partners.

---

## 3. City-First Decision Model

City selection is introduced before talent discovery to:
- Reduce logistics and coordination risk
- Enable faster execution and physical collaboration
- Set realistic expectations around availability and capability

City availability indicators are used to prevent false confidence.

---

## 4. Engagement Model Recommendation (Cluster vs Freelancer)

The platform recommends an engagement model before exposing marketplace options.

### Cluster Teams
Recommended for:
- Multi-disciplinary hardware projects
- High dependency between PCB, mechanical, and QA work
- Tight timelines and quality constraints

### Individual Freelancers
Offered for:
- Isolated or low-complexity tasks
- Advisory or short-term needs

### UX Rationale
Users often misjudge execution complexity.  
Early recommendations prevent irreversible downstream mistakes.

---

## 5. Trust & Transparency Design

Trust is established through:
- Verified execution partners
- Specialization match indicators
- Clear deliverables and ownership boundaries
- Cost and timeline ranges instead of fixed pricing
- Explicit IP and NDA reassurance

Pricing is intentionally secondary to capability fit.

---

## 6. Marketplace & Cluster Discovery

Clusters are presented as execution units rather than individual profiles.

Each cluster surfaces:
- Core expertise
- Team composition
- Execution history
- Expected timelines and cost bands

This reduces comparison fatigue and supports confident decision-making.

---

## 7. Exception Handling & Assisted Matching

For projects with specialized requirements (certifications, cleanroom, high-precision processes):

- Automated matching is intentionally stopped
- Users are routed to an assisted expert review flow
- Manual sourcing ensures feasibility and correctness

### UX Rationale
It is better to slow the user down than to recommend an incorrect execution partner.

---

## 8. Microcopy Strategy

Microcopy is used to:
- Set expectations early
- Explain tradeoffs clearly
- Reduce anxiety in high-risk decisions

### Examples

City Selection:
“Select the hub where your hardware assembly will take place.”

Cluster Explanation:
“A managed group of specialists ideal for complex, high-stakes execution.”

Empty State:
“No verified clusters are available yet in this city. You can request expert assistance.”

Error State:
“We couldn’t match your requirements automatically. Our experts will help you source the right execution team.”

---

## 9. Key UX Decisions

### Decision 1: Recommendation before browsing  
Prevents users from choosing structurally incorrect engagement models.

### Decision 2: City-first filtering  
Reduces execution risk and improves coordination outcomes.

### Decision 3: Assisted fallback instead of hard failure  
Preserves trust in high-complexity scenarios.

---

## 10. Original vs AI-Assisted Work

### Original Work
- UX flow design
- Information architecture
- Engagement logic
- Trust modeling
- Edge-case handling

### AI-Assisted
- Competitor discovery
- Language refinement

All product and UX decisions are independently reasoned.

---

## 11. Closing Note

This design prioritizes execution correctness, trust, and accountability over speed and surface-level choice.

The goal is not to help users browse more options,  
but to help them make **fewer, better decisions**.
