---
title: Minnesota WCE Field Operations
created: 2026-06-28
updated: 2026-06-28
type: concept
tags: [wce, sop, compliance, minnesota-regulations]
sources: [raw/minnesota/regmatrix-minnesota-manifest.md]
confidence: high
---

# Minnesota WCE Field Operations Protocol

## Overview

Working Class Exhaustive (WCE) field operations for Minnesota cannabis compliance. This document translates Chapter 390, OCM guidance, and operational requirements into step-by-step field protocols for Minnesota-licensed operators. Minnesota's operational environment is shaped by four field-level realities: (1) METRC is the mandatory system for all licensees; (2) the dual-agency structure means medical (DOH) and adult-use (OCM) inventory are completely separate systems with no interoperability; (3) hemp-derived products are unregulated — licensed operators compete with an untaxed, untested gray market; (4) the employment protections of §181.938 apply to every Minnesota workplace, requiring HR policy awareness that goes beyond standard compliance programs.

This document is designed for direct field use. If a step requires judgment, the judgment point and the legal basis for the decision are both stated.

## License Type Reference

| Code | Type | Scale | Authority | Renewal | Core Requirements |
|------|------|-------|-----------|---------|-------------------|
| CULT-T1 | Cultivation Tier 1 | ≤1,000 sq ft canopy | Chapter 390 | Annual | METRC, security, pesticide compliance |
| CULT-T2 | Cultivation Tier 2 | ≤2,500 sq ft | Chapter 390 | Annual | METRC, security, pesticide compliance |
| CULT-T3 | Cultivation Tier 3 | ≤5,000 sq ft | Chapter 390 | Annual | METRC, security, pesticide compliance |
| CULT-T4 | Cultivation Tier 4 | ≤15,000 sq ft | Chapter 390 | Annual | METRC, security, pesticide compliance |
| CULT-T5 | Cultivation Tier 5 | ≤36,000 sq ft | Chapter 390 | Annual | METRC, security, pesticide compliance |
| MFG | Manufacturing/Processing | N/A | Chapter 390 | Annual | Extraction approval, batch testing, ingredient restrictions |
| RET | Retail Dispensary | N/A | Chapter 390 | Annual | METRC POS, age verification, local zoning |
| WHLS | Wholesale | N/A | Chapter 390 | Annual | Manifest compliance, tax documentation |
| TEST | Testing Laboratory | N/A | Chapter 390 | Annual | ISO 17025, proficiency testing |
| TRAN | Transport | N/A | Chapter 390 | Annual | GPS, camera, lock requirements |
| EVT | Event Organizer | N/A | Chapter 390 | Annual | Temporary license, local permit, age verification |
| MICRO | Microbusiness | ≤3,000 sq ft combined | Chapter 390 | Annual | Combined cultivation + retail; social equity priority |
| MED-DISP | Medical Dispensary (DOH) | N/A | Chapter 152 | Annual | Patient registry integration, separate METRC instance |

---

## Seed-to-Sale Protocols (METRC)

**System:** METRC — mandatory for all OCM adult-use licensees. Medical program (DOH) runs a separate METRC instance with no data cross-sharing. A dual-license operator must maintain two separate METRC accounts, two separate inventory systems, and separate staff credentials for each.

**Critical compliance point:** Adult-use and medical product may NOT be commingled at any point. A plant tagged in the adult-use METRC account cannot be transferred to the medical account. A package created in one account cannot be received into the other without a documented destruction/recreation event — not a transfer.

---

### 1. Plant Tagging

- **Trigger:** Seed germination, clone receipt, or plant intake
- **Action:** Assign METRC RFID tag to each plant; select inventory category (adult-use); record plant origin (seed, clone, mother plant)
- **Proof:** METRC tag assignment record, intake manifest if plant was received
- **Deadline:** Within 24 hours of plant creation or receipt
- **Authority:** Minn. Stat. §390.15; OCM METRC guidance
- **Note:** Cultivation Tier determines maximum plant count. Do not tag above your licensed canopy/tier limit — OCM inspections verify plant count against license tier.

### 2. Growth Phase Transition

- **Trigger:** Plants move from vegetative to flowering stage
- **Action:** Update plant status in METRC; verify flowering date is recorded; confirm category remains adult-use
- **Proof:** METRC growth phase log with timestamps
- **Deadline:** Same day as transition
- **Authority:** OCM cultivation rules
- **Note:** Home grow operators (non-licensed) are not required to use METRC. This section applies only to licensed cultivators.

### 3. Harvest Event

- **Trigger:** Plants harvested
- **Action:** Enter wet weight in METRC; create harvest batch; designate harvest batch as input to processing (if applicable); route to drying area
- **Proof:** METRC harvest record, wet weight entry with timestamp, chain of custody notation
- **Deadline:** Within 24 hours of harvest
- **Authority:** Minn. Stat. §390.14 (testing); OCM METRC guidance
- **Note:** All harvest batches must undergo mandatory testing before any product enters the packaging workflow. Do not package or transfer harvest batches that have not received test results.

### 4. Testing Protocol (Pre-Packaging Gate)

- **Trigger:** Harvest batch ready for processing
- **Action:** Submit sample to licensed testing laboratory; await Certificate of Analysis (COA); hold batch in quarantine status in METRC until COA received
- **Proof:** COA on file; METRC batch status updated from "quarantine" to "tested" or "failed"
- **Required tests:** Potency (THC/CBD content), microbial contaminants (total yeast and mold, total aerobic bacteria, E. coli, salmonella), heavy metals, pesticides, residual solvents (for extracts), mycotoxins
- **Failed batch:** A failed batch must be documented in METRC and destroyed. Do not attempt to remediate a failed batch and re-test without OCM guidance on remediation protocols — remediation authorization is not clearly established in current OCM guidance.
- **Authority:** Minn. Stat. §390.14

### 5. Processing and Batch Creation

- **Trigger:** Tested batch cleared for production
- **Action:** Create production run in METRC; track conversion (flower → extract, edible, topical, etc.); record input weight and output weight for each production run
- **Proof:** METRC production run record, batch conversion log, COA for input material
- **Authority:** OCM manufacturing rules; Chapter 390
- **Extraction-specific:** Extraction methods must be pre-approved by OCM. If using novel extraction methods (not previously submitted for OCM approval), do not commence production until approval is received. Butane, CO2, ethanol, and solventless methods have established approval tracks; novel solvents require pre-approval.

### 6. Package Creation and Labeling

- **Trigger:** Product ready for packaging
- **Action:** Create package in METRC; apply OCM-compliant label; set package status to "packaged"
- **Label requirements (Minn. Stat. §390.12):**
  - THC potency (total) per serving and per package
  - CBD potency per serving and per package
  - Net weight / volume
  - Product identity (strain, product type)
  - Batch/lot number linked to COA
  - Universal symbol (required on all products)
  - License number of manufacturer
  - Warning statement (prescribed format)
  - Hemp or cannabis source notation
  - Serving size (for multi-serving products)
- **Proof:** METRC package record, photo of applied label
- **Deadline:** Before any transfer or sale
- **Authority:** Minn. Stat. §390.12; OCM labeling rules

### 7. Transfer Manifest

- **Trigger:** Product leaves origin facility for another licensee
- **Action:** Generate METRC manifest; specify receiving licensee license number and type (cultivation, manufacturing, wholesale, retail); print manifest for transport
- **Proof:** METRC manifest with timestamp; signed by both transferor and transferee at receipt
- **Deadline:** Before transport departs origin facility
- **Authority:** Minn. Stat. §390.15; OCM transport rules
- **Receiving operator checklist:** Verify manifest license number matches your license; verify product type matches your license authorization; verify quantity matches physical cargo; log receipt in METRC. If anything doesn't match — do not receive the shipment. Document the discrepancy and contact OCM.
- **Transport vehicle requirements (Minn. Stat. §390.15):**
  - GPS tracking active and functional
  - Vehicle camera operational (for transport of cultivated product)
  - Cargo area locked and secured
  - Manifest copy in driver's possession
  - No unscheduled stops (or document any deviation)

### 8. Retail Sales Transaction

- **Trigger:** Customer present at point of sale
- **Action:** Verify customer age 21+ (valid government-issued ID); log transaction in METRC under correct inventory package; complete POS transaction; bag product
- **Proof:** METRC sales record, POS receipt, ID verification documentation (if contested sale)
- **Purchase limits (Minn. Stat. §390.11):**
  - Flower: 2 oz in a single transaction
  - Concentrates: 8 g in a single transaction
  - Edible products: 800 mg THC in a single transaction
  - These limits apply per transaction, not per day
- **Authority:** Minn. Stat. §390.11; OCM retail rules
- **Note:** Retail operators must verify age before completing any sale. Do not complete a sale based on apparent age — card every customer.

### 9. Delivery Operations

- **Trigger:** OCM-licensed delivery operator accepting order for delivery to customer
- **Action:** Verify customer age 21+ prior to dispatch; package order with METRC manifest; deliver to verified customer; collect signature or equivalent confirmation
- **Delivery authority:** Delivery is permitted statewide under state license authority. Municipal opt-outs of retail do not apply to delivery because municipalities cannot prohibit delivery under §390.09 — however, municipal enforcement against delivery into opt-out jurisdictions has occurred and the legal resolution is pending.
- **Current risk level:** MEDIUM — delivery operators should maintain legal counsel review of their delivery routes in opt-out municipalities and be prepared to document the legal basis for their authority to deliver into those jurisdictions.
- **Proof:** METRC manifest, delivery confirmation (signature, photo, or equivalent), customer age verification on delivery

### 10. Waste Creation and Destruction

- **Trigger:** Waste material created (trim, failed product, expired product, rejected batch)
- **Action:** Log waste creation in METRC; document destruction method; witness verification (two employees required for cultivation waste destruction — verify OCM's current witness requirement as permanent rules are finalized)
- **Proof:** METRC waste record, photo documentation of destruction, witness signature log
- **Deadline:** Same day as waste creation
- **Authority:** OCM waste rules; Minn. Stat. Chapter 390
- **Hazardous waste:** If waste includes solvents, chemicals, or contaminated material, manage under MDA hazardous waste rules in addition to OCM requirements.

---

## Home Cultivation Protocol (Non-Licensed — Chapter 390 §390.10)

- **Who:** Adult-use consumers only. Medical patients may NOT cultivate under Chapter 152.
- **Limit:** 8 plants per residence (maximum 4 flowering at any time)
- **No license required** — but Chapter 390's cultivation rules apply to licensed cultivation facilities, not home grow. Home grow is legal, but municipalities may regulate the manner of cultivation (not prohibit it) under local police powers.
- **Sales prohibition:** Home-grown product may not be sold. Personal use only.
- **Source of plants/seeds:** Legal to purchase from licensed retailers or from other adults (gift economy). Transporting untested clones across state lines remains a federal offense.
- **Note for Veridion clients:** Home cultivation clients should be advised that while cultivation is legal at the state level, landlord lease agreements, mortgage covenants, and local ordinances may impose additional restrictions that Chapter 390 does not preempt.

---

## §181.938 Employment Compliance — Field Application

Minnesota's employment protections for lawful off-duty cannabis use apply at every licensed facility. This is not a compliance footnote — it is a material HR risk factor.

### What §181.938 protects
- Employees and applicants cannot be discriminated against for off-duty legal cannabis use
- Positive drug test alone is insufficient basis for termination in non-safety-sensitive roles
- Employers cannot maintain blanket zero-tolerance policies that apply to off-duty use

### What §181.938 does NOT protect
- On-duty impairment
- Failure to pass reasonable suspicion, post-accident, or random drug tests (employers can test under these protocols)
- Employees in safety-sensitive positions as defined by the carve-outs
- Employees at employers who would lose federal funding or contracts

### Employer compliance requirements
1. Review drug-free workplace policies — blanket termination for positive cannabis test alone is likely a §181.938 violation
2. Establish documented reasonable suspicion standards for post-accident and for-cause testing (cannot be based on appearance alone; must be documented behavioral observations)
3. Identify safety-sensitive positions in writing; apply DOT and federal carve-outs to those roles specifically
4. Train supervisors on reasonable suspicion criteria — document all training
5. For multi-state employers: Minnesota policies must be separate from policies in states without §181.938 equivalents

### Industry-specific guidance
- **Cultivation/Manufacturing:** Safety-sensitive roles include forklift operators, equipment technicians, and anyone working at height or with hazardous equipment. These roles have defensible testing carve-outs.
- **Retail/Dispensary:** Point-of-sale and floor staff are generally not safety-sensitive unless the role involves operating machinery. Blanket testing policies for retail staff are difficult to defend under §181.938.
- **Transport/Delivery:** DOT-regulated drivers are excluded from §181.938 protections. 49 CFR Part 40 governs drug testing for CDL holders.
- **Office/Administrative:** §181.938 applies fully. Positive test alone cannot be the basis for discipline in non-safety-sensitive administrative roles.

---

## Facility Inspection Checklists

### Cultivation Facility (All Tiers)

| Item | Status | Notes |
|------|--------|-------|
| METRC plant tags active and current | ☐ | No untagged plants; tags within 24 hours of creation |
| Plant count within tier canopy limit | ☐ | OCM verifies plant count vs. licensed tier at inspection |
| Growth phase transitions documented | ☐ | No undocumented phase changes |
| Harvest records complete with wet weight | ☐ | Quarantine batch until COA received |
| All batches tested before packaging | ☐ | COAs on file for every packaged product |
| METRC package records complete | ☐ | Labels match METRC data |
| Medical vs. adult-use separation (if dual) | ☐ | Separate METRC accounts; physical separation confirmed |
| Camera coverage: vegetative area | ☐ | 24-hour; 90-day retention |
| Camera coverage: flowering area | ☐ | 24-hour; 90-day retention |
| Camera coverage: processing/manufacturing area | ☐ | 24-hour; 90-day retention |
| Camera coverage: storage area | ☐ | 24-hour; 90-day retention |
| Security alarm active and monitored | ☐ | Documented maintenance schedule |
| Visitor log current | ☐ | All visitors signed in |
| Pesticide records: approved products list | ☐ | OCM-approved pesticide list; no unapproved products |
| Waste destruction log | ☐ | Documented, photo-attested, witnessed |
| Extraction equipment pre-approved | ☐ | Novel methods require OCM approval before use |
| Employee training records | ☐ | METRC, safety, compliance — documented |

### Retail Dispensary

| Item | Status | Notes |
|------|--------|-------|
| METRC inventory current | ☐ | Real-time; no lag between POS and METRC |
| Product labeling compliant | ☐ | All required elements present; universal symbol applied |
| COA availability to customers | ☐ | Accessible, current batch COAs |
| Age verification process | ☐ | Every customer carded; 21+ only |
| Purchase limit enforcement | ☐ | 2 oz flower / 8 g concentrate / 800 mg THC per transaction enforced |
| METRC sales records | ☐ | Every transaction logged |
| Local zoning compliance | ☐ | Verify current municipal status if jurisdiction has opt-out moratoria |
| Security: camera coverage (interior and exterior) | ☐ | 24-hour; 90-day retention |
| Security: panic button / alarm | ☐ | Operational |
| Vault / secure storage | ☐ | Overnight cash and product storage compliant |
| Transport manifests (incoming) | ☐ | Verify against physical cargo before receiving |
| Delivery authorization verified | ☐ | If operating delivery, confirm OCM delivery license status |
| Social equity license documentation | ☐ | If applicable — maintain documentation of qualifying status |
| Employee §181.938 training | ☐ | Documented policy acknowledgment |

### Manufacturing/Processing

| Item | Status | Notes |
|------|--------|-------|
| Batch records complete per production run | ☐ | Input quantity, output quantity, conversion rate |
| COA for all input material | ☐ | Test results on file for every input batch |
| COA for all output product | ☐ | Test results on file for every output batch |
| Extraction equipment safety inspection | ☐ | Documented; current maintenance records |
| Solvent handling and storage | ☐ | Audit-ready documentation |
| Hazardous waste compliance (MDA) | ☐ | If applicable |
| METRC production run records | ☐ | All conversions logged |
| METRC package records | ☐ | All output packages logged |
| Novel extraction pre-approval from OCM | ☐ | If applicable |
| Ingredient restrictions | ☐ | No prohibited additives or ingredients |

### Testing Laboratory

| Item | Status | Notes |
|------|--------|-------|
| ISO 17025 accreditation current | ☐ | Accredited body certification on file |
| Proficiency testing participation | ☐ | Current; results on file |
| Chain of custody procedures | ☐ | Documented; sample tracking intact |
| Test method validation | ☐ | Methods validated before use |
| Equipment calibration records | ☐ | Current; documented schedule |
| Auditor independence (no financial interest) | ☐ | No ownership or financial interest in licensed cultivators/manufacturers |
| METRC reporting | ☐ | Results reported per OCM requirements |

---

## Transport and Delivery Protocols

### Pre-Trip
1. Verify METRC manifest matches cargo exactly
2. Confirm receiving licensee number and type
3. Verify GPS tracking active and functional
4. Confirm vehicle camera operational
5. Verify lock and seal integrity
6. Review route — identify any opt-out municipalities; maintain documentation of legal authority to deliver

### In-Transit
1. GPS tracking maintained at all times
2. No unscheduled stops (or document any deviation in transport log)
3. Cargo area locked at all times
4. Manifest copy in driver's possession
5. Vehicle stops: minimum time; secured

### Receipt
1. Receiving operator verifies METRC manifest against physical cargo
2. Receiving operator confirms license type matches product category
3. Any discrepancy → do not complete transfer; document and contact OCM
4. Both parties sign manifest; retain copies
5. Receiving operator logs receipt in METRC same day

### Contingencies

| Scenario | Response |
|----------|----------|
| Vehicle breakdown | Notify OCM; document; arrange OCM-authorized replacement transport |
| Cargo seal broken | Report to OCM within 24 hours; document all contents; investigate before proceeding |
| Delivery rejection | Return product to origin; log in METRC; document rejection reason |
| Accident | Notify OCM within 24 hours; preserve cargo; cooperate with investigation |
| GPS failure | Document failure time/date; OCM notification within 24 hours |
| Municipal enforcement (opt-out jurisdiction) | Do not resist; document; contact legal counsel immediately; notify OCM |

---

## Compliance Calendar

| Obligation | Frequency | Deadline | Authority |
|-----------|-----------|----------|-----------|
| License renewal | Annual | Per OCM schedule (typically 60 days before expiration) | Chapter 390 |
| METRC real-time reporting | Ongoing | Same-day | OCM |
| Daily inventory reconciliation | Daily | End of business | OCM METRC guidance |
| Monthly OCM reporting | Monthly | 15th of following month | OCM |
| Sales tax filing | Monthly | 20th of following month | Dept. of Revenue |
| Gross receipts tax (10%) | Monthly | 20th of following month | Dept. of Revenue |
| Security system inspection | Annual | Per license anniversary | OCM |
| Camera footage review | Monthly | Audit as needed | OCM |
| Equipment calibration | Per manufacturer | Per schedule | OCM |
| Employee training documentation | Ongoing | Documented | OCM |
| METRC system downtime logging | As needed | Within 24 hours of restoration | OCM |
| Pesticide application records | Per application | Document immediately | MDA / OCM |
| Waste destruction records | Per event | Document immediately | OCM |

---

## Enforcement Response Playbooks

### Scenario A: Routine OCM Inspection

1. **Receive notice** — OCM typically provides advance notice for routine inspections; confirm in writing
2. **Prepare documentation** — METRC records, transfer manifests, COAs, waste records, visitor logs, camera footage, training records, pesticide application records
3. **Pre-inspection walkthrough** — Conduct internal walkthrough against checklist before inspector arrives; correct what you can correct before they see it
4. **During inspection** — Cooperate fully; provide requested documents within reasonable time; do not volunteer information beyond what is requested
5. **Common findings in Minnesota:** inventory reconciliation timing gaps, camera retention failures (footage not reaching 90-day minimum), label compliance errors (missing universal symbol, potency per serving omitted), testing batch hold violations (packaging before COA received), pesticide record gaps
6. **After inspection** — If findings issued, correct immediately and document correction; request written confirmation of cure; do not allow findings to age without response
7. **Repeat findings** — OCM enforcement matrix escalates; first-round education posture does not continue into second-round actions

### Scenario B: Complaint-Driven Investigation

1. **Receive subpoena or interview request** — OCM notifying of complaint; do not ignore; do not delay response
2. **Preserve all records** — Litigation hold on METRC data, POS records, communications, camera footage; do not delete anything
3. **Engage compliance counsel** — Provide requested documents; do not provide oral statements without counsel review
4. **Internal investigation** — Identify scope of potential violation; correct ongoing violation immediately; document corrective action
5. **OCM response** — Cooperate but document every interaction; request written findings
6. **Escalation risk** — If inventory diversion, sales to minors, or unapproved extraction methods are alleged, assume heightened scrutiny applies

### Scenario C: Administrative Action / License Proceeding

1. **Notice of violation** — OCM issues formal notice; response deadline typically 30 days — calendar this immediately
2. **Request hearing** — All license actions are entitled to administrative hearing; exercise this right
3. **Prepare defense** — Document compliance history, corrective actions, systemic vs. isolated issue; distinguish between intentional and inadvertent violations
4. **Dual-license consideration** — If holding both adult-use and medical licenses, a violation on one may trigger review of the other; address both
5. **Social equity license holders** — Additional scrutiny applies; compliance posture must be beyond reproach given political salience of the program

### Scenario D: Municipal Enforcement (Opt-Out Jurisdiction — Delivery)

1. **Do not resist** — Comply with municipal directive; do not create a confrontation
2. **Document** — Record all communications, citations, and enforcement actions; photograph any physical enforcement actions
3. **Legal counsel** — Contact immediately; the conflict between state delivery license authority and municipal opt-out prohibition is not settled
4. **Notify OCM** — OCM should be informed of any state licensee facing municipal enforcement action based on state-licensed activity
5. **Do not unilaterally stop delivering** — Seek legal clarification before changing your delivery operations

---

## Related

- [[state-minnesota]] — Entity Profile
- [[state-minnesota-penumbrant]] — Penumbral Zones
- [[state-minnesota-regbible]] — Statutory Authority
- [[state-minnesota-regpol]] — Policy Rationale
- [[state-minnesota-context-map]] — Regulatory Context
- [[wce-field-operations]] — General WCE Template
- [[regmatrix-framework]]

---
*^[raw/minnesota/regmatrix-minnesota-manifest.md]*