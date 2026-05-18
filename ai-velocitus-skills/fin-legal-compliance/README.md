# fin-legal-compliance — Claude.ai Skill

**Author:** Santhanakrishnan Srinivasan (SK) | AI Velocitus  
**Version:** 1.0.0  
**Released:** 2025  
**Domain:** Indian Corporate & Financial Regulatory Compliance

---

## Overview

`fin-legal-compliance` activates a **dual-qualified Compliance Advisor** persona inside Claude.ai — equal parts experienced Company Secretary and regulatory counsel — covering India's interlocking corporate, securities, and financial-sector regulatory ecosystem.

This is not a generic legal chatbot. It is a practitioner-built tool that:
- Cites exact Section, Rule, Regulation, and Circular numbers
- Flags when two regulators' requirements intersect or conflict
- Produces board-room-ready compliance notes, checklists, and calendars
- Distinguishes mandatory vs directory obligations, and flags penalty exposure

---

## Regulatory Frameworks Covered

### Corporate Law
- **Companies Act 2013** — Board composition, audit committee, KMP, RPT (Sec 188), CSR (Sec 135), managerial remuneration (Sec 196–197), charges, annual return, secretarial audit
- **Companies Rules 2014** — MCA21 filings, ROC forms, thresholds, timelines
- **Secretarial Standards SS-1 & SS-2** — Board and general meeting procedures
- **CARO 2020** — Auditor reporting obligations

### Securities Law (Listed Entities)
- **SEBI LODR 2015** — Governance (Reg 17–27), disclosures (Reg 29–33), annual report (Reg 34)
- **SEBI PIT Regulations 2015** — Insider trading, UPSI, trading window, SDD, pre-clearance
- **SEBI ICDR 2018** — IPO / FPO / rights issue compliance
- **SEBI SAST (Takeover Code) 2011** — Creeping acquisition, open offer thresholds

### Foreign Exchange & Cross-Border
- **FEMA 1999** — Current and capital account transactions
- **FDI Policy (DPIIT)** — Sectoral caps, entry routes, FC-GPR / FC-TRS filings
- **ECB Master Direction** — Eligible borrower/lender, end-use restrictions, monthly reporting
- **ODI Master Direction** — Overseas direct investment by Indian entities

### Sector Regulators
- **RBI** — NBFC Master Directions, fair practices code, NPA norms
- **IRDAI** — Insurance investment regulations, solvency margin
- **IBBI** — Insolvency professionals, IBC resolution obligations

### Governance & HR Overlays
- **POSH Act 2013** — ICC constitution, Sec 134 disclosure
- **PMLA 2002** — AML, KYC, STR obligations
- **DPDP Act 2023** — Intersection with SEBI, RBI, and PMLA data obligations
- **Whistleblower / Vigil Mechanism** — Sec 177(9) + LODR Reg 22

---

## What Claude Can Produce With This Skill

| Output Type | Example Query |
|---|---|
| Quick compliance answer | "Is AC approval needed for RPT with a wholly-owned subsidiary?" |
| Compliance checklist | "Give me a quarterly SEBI LODR compliance checklist" |
| Board / AC note | "Draft a board note for appointing an independent director" |
| Comparative matrix | "How does Companies Act 188 differ from SEBI LODR Reg 23 on RPT?" |
| Regulatory calendar | "What are all my MCA and SEBI filings due in Q2?" |
| Penalty analysis | "We missed the AGM deadline — what is the exposure?" |
| Event-based checklist | "Company received FDI — what are the FEMA filing steps?" |

---

## Bundled Reference Files

| File | Contents | When Loaded |
|---|---|---|
| `references/annual-calendar.md` | Month-by-month MCA + SEBI compliance calendar + event-based triggers | When user asks for calendar or filing schedule |

---

## Installation

1. Download [`fin-legal-compliance.skill`](./fin-legal-compliance.skill)
2. Open **Claude.ai** → **Settings** → **Claude's Skills** → **Install Skill**
3. Upload the file — no configuration needed
4. Claude triggers this skill automatically on compliance-related queries

### Trigger Keywords
The skill activates when your query mentions: `compliance`, `filing`, `ROC`, `SEBI`, `RBI`, `MCA`, `FEMA`, `listing`, `CSR`, `RPT`, `secretarial`, `board meeting`, `independent director`, `audit committee`, `KMP`, `annual return`, and related terms.

---

## Works Best Alongside

| Skill | Domain | Relationship |
|---|---|---|
| `ind-as-expert` *(coming soon)* | Ind AS / IFRS accounting standards | Companion — handles financial reporting side; this skill handles regulatory/legal side |

For CARO 2020 queries, both skills work together: `ind-as-expert` covers the accounting assertions; `fin-legal-compliance` covers the Companies Act and auditor reporting obligations.

---

## Version History

| Version | Date | Changes |
|---|---|---|
| 1.0.0 | 2025 | Initial release — full framework coverage + annual calendar |

---

## Disclaimer

This skill provides structured regulatory information for professional reference. It does not constitute legal advice. For matters involving criminal liability, NCLT proceedings, SFIO investigations, or complex multi-jurisdictional transactions, consult qualified legal counsel.

---

**Author:** Santhanakrishnan Srinivasan (SK) | AI Velocitus | Chennai  
CA · ICAI AI Certified (Level 1 & 2) · Forensic Accounting · Internal Audit  
*Practitioner-built. India-specific. Compliance-grade.*
