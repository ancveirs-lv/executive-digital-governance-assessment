# Executive Digital Governance Self-Assessment

> This project measures governance evidence and decision readiness. It is not an official EDIH/EC assessment, legal opinion, audit or certification.

## Response states

- `UNKNOWN` — Unknown / not evidenced: The current state cannot be established with reliable information or evidence.
- `CLAIMED` — Claimed: The practice or control is asserted, but no durable artefact or operating evidence is available.
- `DOCUMENTED` — Documented: A policy, process or record exists, but operation in practice has not been demonstrated.
- `IMPLEMENTED` — Implemented: The practice or control operates in practice and execution evidence exists.
- `VERIFIED` — Verified: Recent direct testing, review or reproducible evidence supports the implementation.
- `NOT_APPLICABLE` — Not applicable: The item is genuinely outside the assessment context; a rationale is required.

## Assessment

### Strategy and value

#### E01

Critical services, digital dependencies and acceptable interruption are explicitly defined.

**Recommended action:** Map critical services, their digital dependencies and maximum tolerable interruption.

**Sources:** `open_dmat`, `nist_csf20`

#### E02

Digital investments are tied to measurable business outcomes and explicit risks.

**Recommended action:** Require each material investment to state outcomes, risks and an accountable owner.

**Sources:** `open_dmat`

#### E03

A target-state digital roadmap exists with owners, dependencies and review dates.

**Recommended action:** Create a dated roadmap linking gaps to owners and milestones.

**Sources:** `open_dmat`

#### E04

Benefits and risks are reviewed after major digital changes, not only before approval.

**Recommended action:** Add post-implementation review with benefit evidence, failure modes and residual risk.

**Sources:** `open_dmat`, `nist_csf20`

### Accountability and decision rights

#### E05

Decision rights for technology, data, AI and cybersecurity are documented.

**Recommended action:** Document who may decide, approve, accept risk and stop a change.

**Sources:** `nist_csf20`, `nis2`

#### E06

Critical systems and critical data have named accountable owners.

**Recommended action:** Assign accountable owners, including lifecycle duties.

**Sources:** `nist_csf20`

#### E07

Executive escalation thresholds are defined for cyber incidents, outages and material data failures.

**Recommended action:** Define objective triggers for executive notification and decision.

**Sources:** `nist_csf20`, `nis2`

#### E08

Leadership receives evidence-based digital-risk reporting rather than only activity metrics.

**Recommended action:** Report exposure, control performance, incidents and unresolved gaps.

**Sources:** `nist_csf20`

### Data and AI governance

#### E09

Critical data has ownership, quality expectations and handling rules.

**Recommended action:** Define data owners, minimum quality criteria and handling rules.

**Sources:** `open_dmat`, `nist_csf20`

#### E10

Consequential data can be traced to its origin and material transformations.

**Recommended action:** Introduce provenance records for consequential data.

**Sources:** `open_dmat`

#### E11

The organisation maintains an inventory of material AI uses and who approved them.

**Recommended action:** Create an AI-use register with purpose, owner, data, supplier, impact and approval.

**Sources:** `nist_ai_rmf`

#### E12

Consequential AI-assisted outputs have explicit human authority and validation boundaries.

**Recommended action:** Define which AI-assisted outputs require human verification and approval.

**Sources:** `nist_ai_rmf`

### Architecture and suppliers

#### E13

Critical third-party, cloud and platform dependencies are inventoried.

**Recommended action:** Maintain a dependency register linked to critical services and data.

**Sources:** `nist_csf20`, `nis2`

#### E14

Concentration, portability and exit risks are considered before strategic platform adoption.

**Recommended action:** Require an exit and portability view for strategic suppliers.

**Sources:** `open_dmat`, `nist_csf20`

#### E15

End-of-life technology and material technical debt are visible to leadership.

**Recommended action:** Maintain an executive view of unsupported technology and technical debt.

**Sources:** `open_dmat`, `nist_csf20`

#### E16

Material architecture changes are reviewed for security, resilience and interoperability.

**Recommended action:** Create a lightweight architecture review gate for material changes.

**Sources:** `nist_csf20`

### Resilience and assurance

#### E17

Degraded-operation expectations are defined for critical processes.

**Recommended action:** Define what must still work, at what minimum level and for how long.

**Sources:** `nist_csf20`

#### E18

Recovery evidence includes tested restoration, not only the existence of backups.

**Recommended action:** Require periodic restore tests and retain results.

**Sources:** `nist_csf20`

#### E19

Exercises include executive decisions, communications and cross-functional dependencies.

**Recommended action:** Run scenarios that force executive decisions and test suppliers and fallback processes.

**Sources:** `nist_csf20`, `nis2`

#### E20

Critical control claims are periodically supported by independent or reproducible evidence.

**Recommended action:** Select critical controls and require testable evidence rather than policy statements alone.

**Sources:** `nist_csf20`

### People and obligations

#### E21

Digital capability gaps are identified for leadership and key roles.

**Recommended action:** Assess role-specific capability gaps and attach learning or hiring actions.

**Sources:** `open_dmat`

#### E22

Supplier responsibilities for security, data, continuity and incident cooperation are explicit.

**Recommended action:** Review strategic contracts for security, incident, recovery, data and exit duties.

**Sources:** `nist_csf20`, `nis2`

#### E23

Material legal, regulatory and contractual digital obligations are mapped to owners and controls.

**Recommended action:** Create an obligation-to-owner-to-control map.

**Sources:** `nist_csf20`, `nis2`

#### E24

Assessment findings and lessons are converted into owned actions and reassessed.

**Recommended action:** Track each material gap to an owner, date, evidence requirement and reassessment date.

**Sources:** `open_dmat`, `nist_csf20`
