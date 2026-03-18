# MiCA ART/EMT Compliance Checklist

Compliance checklist for **asset-referenced token (ART)** and **e-money token (EMT)** issuers under the EU Markets in Crypto-Assets Regulation (MiCA). Full enforcement began December 30, 2024.

This checklist is for legal, compliance, and product teams working on token issuance in the EU or targeting EU investors.

> **Disclaimer**: This is a practitioner reference tool — not legal advice. Engage qualified EU regulatory counsel before submitting authorization applications.

## Contents

- [Stage 1: Pre-Authorization Assessment](#stage-1-pre-authorization-assessment)
- [Stage 2: Whitepaper Requirements](#stage-2-whitepaper-requirements)
- [Stage 3: Authorization Application](#stage-3-authorization-application)
- [Stage 4: Reserve Management](#stage-4-reserve-management)
- [Stage 5: Marketing and Offering Rules](#stage-5-marketing-and-offering-rules)
- [Stage 6: Ongoing Obligations](#stage-6-ongoing-obligations)
- [Stage 7: Cross-Border Operations](#stage-7-cross-border-operations)
- [ART vs EMT Reference Table](#art-vs-emt-reference-table)
- [Significant Token Thresholds](#significant-token-thresholds)
- [Key MiCA Articles](#key-mica-articles)

---

## Stage 1: Pre-Authorization Assessment

### Token Classification

- [ ] Determine whether your token is an **ART** (references multiple assets, a basket, or commodities) or **EMT** (references a single official currency)
- [ ] Confirm the token does not qualify as a financial instrument under MiFID II — if it does, different rules apply
- [ ] Confirm the token is not an e-money token issued under the E-Money Directive — scope overlap resolved per MiCA Art. 2(4)
- [ ] Identify the **home member state** for authorization (where the legal entity is incorporated)
- [ ] Assess whether the token will exceed **significant token thresholds** — triggers enhanced obligations (see below)

### Entity Structure

- [ ] Legal entity must be incorporated in an EU member state — non-EU issuers cannot issue ARTs or EMTs to EU residents
- [ ] For ARTs: legal form must be a legal entity (not a natural person)
- [ ] For EMTs: issuer must be a **credit institution** or **electronic money institution (EMI)** — cannot be issued by other entity types
- [ ] Identify whether a **group structure** is involved — group-level requirements apply if parent is non-EU

---

## Stage 2: Whitepaper Requirements

MiCA requires a **crypto-asset whitepaper** before any public offering. The whitepaper is not pre-approved but must be notified to the competent authority.

### Mandatory Whitepaper Content (Art. 19 / Art. 51)

- [ ] Identity and contact details of the issuer
- [ ] Description of the issuer's project and the token
- [ ] Rights and obligations attached to the token
- [ ] Underlying technology description
- [ ] Risks specific to the issuer, the token, and the project
- [ ] **For ARTs**: description of the reference asset basket and stabilization mechanism
- [ ] **For EMTs**: reference to the official currency and redemption rights
- [ ] Summary section (max 2 pages, plain language, non-technical audience)
- [ ] Statement that the whitepaper has not been approved by any competent authority

### Whitepaper Process

- [ ] Notify competent authority **at least 20 working days** before publication
- [ ] Publish whitepaper on issuer's website before offering commences
- [ ] Keep whitepaper updated — material changes require revised whitepaper and re-notification
- [ ] Whitepaper must be available for **10 years** after the token ceases to be offered

---

## Stage 3: Authorization Application

### ART Authorization (Art. 21)

- [ ] Submit authorization application to home member state's **competent authority (NCA)**
- [ ] Application must include: business plan, legal documentation, whitepaper, governance arrangements, AML/CFT policies, reserve asset policy, recovery plan
- [ ] NCA has **60 working days** to assess application completeness, then **60 working days** to approve or reject
- [ ] Minimum own funds: higher of €350,000 or 2% of average reserve assets
- [ ] Recovery plan must cover: scenarios for wind-down, redemption procedures, communication protocols

### EMT Authorization (Art. 54)

- [ ] EMT issuers must already hold a **credit institution license** or **EMI license** under existing EU financial regulation
- [ ] Submit notification to home NCA **at least 40 working days** before issuance begins
- [ ] Notification includes: whitepaper, AML/CFT policies, governance arrangements for the EMT program
- [ ] No separate MiCA authorization required — existing EMI/credit institution license is sufficient

---

## Stage 4: Reserve Management

Reserve management is the core operational obligation for ART issuers. Failure here is the primary enforcement risk.

### Reserve Asset Requirements (Art. 36)

- [ ] Reserve assets must be **legally segregated** from the issuer's own assets at all times
- [ ] Reserve assets must be held with **EU credit institutions** or, where permitted, other secure custodians
- [ ] Reserve composition must match the reference basket — reviewed and rebalanced regularly
- [ ] Reserve portfolio managed to **preserve value and liquidity** — no speculative investment of reserves
- [ ] Custody arrangements documented with custodians; custodian must be authorized under EU law

### Reserve Audit and Reporting

- [ ] Reserve assets audited by an **independent auditor** at least annually
- [ ] Audit results disclosed to competent authority and token holders
- [ ] Monthly reporting to NCA on reserve asset composition and value
- [ ] Stress testing of reserve liquidity under adverse market conditions

### Redemption Rights

- [ ] Token holders have a **right of redemption** at par value at any time — cannot be waived
- [ ] Redemption must be completed within **10 working days** of request under normal conditions
- [ ] Redemption procedures must be documented and published in the whitepaper
- [ ] No redemption fees permitted that would deter exercise of redemption rights

---

## Stage 5: Marketing and Offering Rules

### Marketing Communications

- [ ] All marketing communications must be **fair, clear, and not misleading**
- [ ] Marketing must be clearly identified as marketing — not confused with the whitepaper
- [ ] Marketing must reference the whitepaper and how to obtain it
- [ ] No marketing claims that imply capital guarantee unless the reserve structure genuinely provides one
- [ ] Marketing to retail investors must use **plain language** — no technical jargon without explanation

### Offering Restrictions

- [ ] **ARTs**: exempt from full authorization if total consideration across EU is less than **€5 million** over 12 months, or offered exclusively to qualified investors — but whitepaper still required
- [ ] **EMTs**: no offering cap exemption — EMI/credit institution authorization required regardless of size
- [ ] Cross-border offerings via passporting available once authorized in home member state
- [ ] Third-country issuers cannot offer ARTs or EMTs in the EU — must establish EU entity

---

## Stage 6: Ongoing Obligations

### Governance and Controls

- [ ] Robust governance arrangements — clear roles for board, management, and compliance function
- [ ] **At least two senior managers** with sufficient experience and good repute
- [ ] Conflicts of interest policy documented and applied
- [ ] Whistleblowing procedures in place
- [ ] Business continuity plan covering IT systems, key personnel, third-party dependencies

### Continuous Disclosure

- [ ] Publish **annual report** on the token program: outstanding supply, reserve composition, number of holders, transaction volumes
- [ ] Notify NCA immediately of any **material changes**: new markets, senior management changes, significant incidents, reserve asset problems
- [ ] Notify token holders of any material changes that affect their rights

### AML/CFT Obligations

- [ ] AML/CFT policy covering token issuance and redemption flows
- [ ] Customer due diligence (CDD) for token holders — enhanced due diligence for high-risk relationships
- [ ] Transaction monitoring for suspicious activity
- [ ] Suspicious transaction reports (STRs) to FIU as required
- [ ] FATF Travel Rule compliance for transfers above €1,000

### Operational Resilience

- [ ] IT and cybersecurity risk management framework
- [ ] Smart contract audit by independent third party before token launch
- [ ] Incident response procedure: classify, contain, notify NCA within **4 hours** of major operational incident
- [ ] Penetration testing at least annually

---

## Stage 7: Cross-Border Operations

### EU Passporting

- [ ] Once authorized in home member state, file **passporting notification** to offer in other EU states
- [ ] NCA notifies host member state authorities within **10 working days**
- [ ] Maintain list of all member states where token is offered
- [ ] Local language requirements for marketing materials in each host member state

### Third-Country Considerations

- [ ] MiCA does not provide a passporting mechanism for non-EU jurisdictions — each jurisdiction requires separate analysis
- [ ] UK: FCA has its own cryptoasset regime (not MiCA-equivalent) — separate authorization required for UK offering
- [ ] Switzerland: FINMA rules apply — not covered by MiCA despite EU proximity
- [ ] US: SEC/FinCEN/state money transmitter rules apply independently

---

## ART vs EMT Reference Table

| Dimension | ART (Title III) | EMT (Title IV) |
|-----------|-----------------|----------------|
| What it references | Basket of currencies, commodities, or crypto | Single official currency (EUR, GBP, USD) |
| Issuer type | Any EU legal entity | Credit institution or EMI only |
| Authorization | MiCA authorization from NCA | Notification only (existing license required) |
| Whitepaper | Required, notify NCA 20 days before | Required, notify NCA 40 days before |
| Reserve requirement | Yes — segregated, custodied, audited | Yes — equivalent to EMI safeguarding rules |
| Redemption right | Yes — at par, within 10 working days | Yes — at par, at any time |
| Significant token rules | Yes — if >1M holders or >€5B reserve | Yes — if >1M holders or >€5B outstanding |
| Offering cap exemption | Yes — below €5M to retail | No — requires license regardless of size |

---

## Significant Token Thresholds

A token becomes **significant** and triggers enhanced obligations (Art. 43) if it meets two or more of:

- More than **10 million token holders**
- Reserve assets or market cap exceeding **€5 billion**
- More than **2.5 million transactions per day** or **€500 million daily value**
- Significant cross-border use
- Systemic importance designation by EBA

Significant token issuers face direct supervision by the **European Banking Authority (EBA)** rather than national NCAs.

---

## Key MiCA Articles

| Article | Topic |
|---------|-------|
| Art. 2 | Scope and definitions |
| Art. 4 | Crypto-asset whitepaper requirements (general) |
| Art. 17 | ART whitepaper requirements |
| Art. 19 | ART whitepaper content |
| Art. 21 | ART authorization procedure |
| Art. 35 | ART obligations of issuers |
| Art. 36 | Reserve asset requirements |
| Art. 37 | Reserve custody requirements |
| Art. 40 | Redemption rights |
| Art. 43 | Significant ART designation |
| Art. 51 | EMT whitepaper requirements |
| Art. 54 | EMT issuance — credit institution and EMI rules |
| Art. 58 | EMT redemption rights |
| Art. 88 | Market abuse prohibition |
| Art. 94 | Competent authority powers |

---

## Related Resources

- [MiCA Full Text](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32023R1114) — Official EU regulation
- [EBA MiCA Guidelines](https://www.eba.europa.eu/regulation-and-policy/crypto-assets) — EBA technical standards and guidance
- [ESMA MiCA Guidelines](https://www.esma.europa.eu/esmas-activities/digital-finance-and-innovation/markets-crypto-assets-regulation-mica) — ESMA technical standards
- [rwa-compliance-checklist](https://github.com/dahlinomine/rwa-compliance-checklist) — Broader RWA token issuance compliance checklist
- [erc3643-compliance-toolkit](https://github.com/dahlinomine/erc3643-compliance-toolkit) — ERC-3643 compliance agents and regulatory templates

## License

CC0 — public domain. Use freely without attribution.