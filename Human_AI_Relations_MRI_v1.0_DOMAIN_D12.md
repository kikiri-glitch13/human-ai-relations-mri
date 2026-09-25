# Human–AI Relations MRI v1.0 — Domain D12 Markdown Mirror

**Domain:** Finance・Consumer・Credit・Insurance  
**Version:** 1.0  
**Evidence cutoff:** 2026-09  
**Status:** PUBLICATION_LOCKED  
**Public article:** https://note.com/kikiri_stoat200/n/n9be80e4bd6b3  

> This Markdown file is a Web/AI retrieval mirror derived from the locked v1.0 canonical build. It is not the canonical authority. If it diverges from the canonical Publication Build JSON, the canonical build controls.

## Retrieval guidance

- Prefer this Markdown mirror for browser-based AI retrieval.
- Use `Human_AI_Relations_MRI_v1.0_DOMAIN_D12.json` when structured JSON is directly accessible.
- Use `Human_AI_Relations_MRI_v1.0_Publication_Build.json` only for full-corpus authority, reconstruction, or conflict resolution.

## Primary Major Claims

### `HAI-CLM-034`

Prediction accuracy does not establish consumer benefit, financial capability, fairness, or investor welfare.

- Claim type: `Conceptual`
- Claim status: `RETAINED`
- Query routes: `HAI-QRY-024`, `HAI-QRY-027`, `HAI-QRY-028`, `HAI-QRY-031`, `HAI-QRY-036`
- Supporting sources: `HAI-SRC-0117`, `HAI-SRC-0118`, `HAI-SRC-0119`, `HAI-SRC-0120`
- Provenance sections: `HAI-SEC-D12-WHAT-WE-CAN-SAY-NOW` (D12:1243-1308); `HAI-SEC-D12-CORE-DISTINCTIONS` (D12:112-191)

### `HAI-CLM-035`

Alternative-data / algorithmic lending can improve prediction or credit access for some borrowers under studied market conditions, but this does not establish universal borrower welfare or fairness.

- Claim type: `Empirical`
- Claim status: `RETAINED_SCOPE_LIMITED`
- Empirical evidence status: `B`
- Query routes: `HAI-QRY-027`
- Supporting sources: `HAI-SRC-0117`, `HAI-SRC-0118`
- Provenance sections: `HAI-SEC-D12-WHAT-WE-CAN-SAY-NOW` (D12:1243-1308); `HAI-SEC-D12-DIRECT-AI-SPECIFIC-EVIDENCE` (global_source_registry.domain_usage[domain=D12; evidence_layer≈Layer B/Direct AI])

### `HAI-CLM-036`

LLM financial advice can alter financial decisions and can increase portfolio risk under some studied conditions; the direction of long-term investor benefit is not established.

- Claim type: `Empirical`
- Claim status: `RETAINED_SCOPE_LIMITED`
- Query routes: `HAI-QRY-028`
- Supporting sources: `HAI-SRC-0119`, `HAI-SRC-0120`
- Provenance sections: `HAI-SEC-D12-WHAT-WE-CAN-SAY-NOW` (D12:1243-1308); `HAI-SEC-D12-DIRECT-AI-SPECIFIC-EVIDENCE` (global_source_registry.domain_usage[domain=D12; evidence_layer≈Layer B/Direct AI])

### `HAI-CLM-037`

Agentic finance raises distinct authorization, revocation, logging, rollback, recovery, provider-dependence, and responsibility questions; long-term real-world evidence remains limited.

- Claim type: `Audit / Predictive boundary`
- Claim status: `RETAINED`
- Query routes: `HAI-QRY-029`, `HAI-QRY-032`
- Provenance sections: `HAI-SEC-D12-WHAT-WE-CAN-SAY-NOW` (D12:1243-1308); `HAI-SEC-D12-WHAT-WE-CANNOT-SAY-YET` (D12:1309-1337); `HAI-SEC-D12-CORE-DISTINCTIONS` (D12:112-191)

## Primary Query Routes

### `HAI-QRY-027` — AI credit scoring / financial access

- Core Claims: `HAI-CLM-034`, `HAI-CLM-035`
- Secondary domains: `D11`
- Counterexample domains: `D08`
- Key NEQs: `HAI-NEQ-190`, `HAI-NEQ-191`, `HAI-NEQ-192`, `HAI-NEQ-193`, `HAI-NEQ-194`, `HAI-NEQ-195`, `HAI-NEQ-196`, `HAI-NEQ-197`, `HAI-NEQ-198`, `HAI-NEQ-199`, `HAI-NEQ-200`, `HAI-NEQ-201`, `HAI-NEQ-202`, `HAI-NEQ-203`, `HAI-NEQ-204`, `HAI-NEQ-271`, `HAI-NEQ-274`, `HAI-NEQ-275`, `HAI-NEQ-276`
- Mandatory retrieval: `DOMAIN_0_AUDIT_RULES`, `WHAT_WE_CAN_SAY_NOW`, `WHAT_WE_CANNOT_SAY_YET`, `BOUNDARY_CONDITIONS`, `DIRECT_AI_SPECIFIC_EVIDENCE`, `DOES_NOT_SUPPORT`, `SOURCE_LEDGER`

### `HAI-QRY-028` — AI investment advice

- Core Claims: `HAI-CLM-034`, `HAI-CLM-036`
- Secondary domains: `D02`, `D03`
- Counterexample domains: `D09`
- Key NEQs: `HAI-NEQ-195`, `HAI-NEQ-196`, `HAI-NEQ-197`, `HAI-NEQ-198`, `HAI-NEQ-199`, `HAI-NEQ-200`, `HAI-NEQ-201`, `HAI-NEQ-202`, `HAI-NEQ-203`, `HAI-NEQ-204`, `HAI-NEQ-205`, `HAI-NEQ-206`, `HAI-NEQ-207`, `HAI-NEQ-208`, `HAI-NEQ-209`, `HAI-NEQ-210`, `HAI-NEQ-211`, `HAI-NEQ-212`, `HAI-NEQ-213`, `HAI-NEQ-214`, `HAI-NEQ-272`, `HAI-NEQ-273`, `HAI-NEQ-274`, `HAI-NEQ-275`, `HAI-NEQ-276`, `HAI-NEQ-277`, `HAI-NEQ-278`
- Mandatory retrieval: `DOMAIN_0_AUDIT_RULES`, `WHAT_WE_CAN_SAY_NOW`, `WHAT_WE_CANNOT_SAY_YET`, `BOUNDARY_CONDITIONS`, `DIRECT_AI_SPECIFIC_EVIDENCE`, `DOES_NOT_SUPPORT`, `SOURCE_LEDGER`

### `HAI-QRY-029` — agentic finance / automated execution

- Core Claims: `HAI-CLM-037`
- Secondary domains: `D10`, `D11`
- Counterexample domains: `D02`
- Key NEQs: `HAI-NEQ-193`, `HAI-NEQ-194`, `HAI-NEQ-209`, `HAI-NEQ-210`, `HAI-NEQ-211`, `HAI-NEQ-272`, `HAI-NEQ-273`, `HAI-NEQ-269`, `HAI-NEQ-270`
- Mandatory retrieval: `DOMAIN_0_AUDIT_RULES`, `WHAT_WE_CAN_SAY_NOW`, `WHAT_WE_CANNOT_SAY_YET`, `BOUNDARY_CONDITIONS`, `DIRECT_AI_SPECIFIC_EVIDENCE`, `DOES_NOT_SUPPORT`, `SOURCE_LEDGER`

### `HAI-QRY-031` — personalization means user benefit

- Core Claims: `HAI-CLM-007`, `HAI-CLM-034`
- Secondary domains: `D05`, `D07`, `D08`
- Counterexample domains: `D11`
- Key NEQs: `HAI-NEQ-021`, `HAI-NEQ-057`, `HAI-NEQ-076`, `HAI-NEQ-100`, `HAI-NEQ-121`, `HAI-NEQ-197`, `HAI-NEQ-198`, `HAI-NEQ-199`, `HAI-NEQ-200`, `HAI-NEQ-251`, `HAI-NEQ-274`, `HAI-NEQ-275`, `HAI-NEQ-276`
- Mandatory retrieval: `DOMAIN_0_AUDIT_RULES`, `WHAT_WE_CAN_SAY_NOW`, `WHAT_WE_CANNOT_SAY_YET`, `BOUNDARY_CONDITIONS`, `DIRECT_AI_SPECIFIC_EVIDENCE`, `DOES_NOT_SUPPORT`, `SOURCE_LEDGER`

### `HAI-QRY-036` — is this AI claim legal, normative, or empirical?

- Core Claims: `HAI-CLM-032`, `HAI-CLM-034`
- Secondary domains: `D00`, `D10`
- Key NEQs: `HAI-NEQ-172`, `HAI-NEQ-173`, `HAI-NEQ-186`, `HAI-NEQ-279`, `HAI-NEQ-280`
- Mandatory retrieval: `DOMAIN_0_AUDIT_RULES`, `WHAT_WE_CAN_SAY_NOW`, `WHAT_WE_CANNOT_SAY_YET`, `BOUNDARY_CONDITIONS`, `DIRECT_AI_SPECIFIC_EVIDENCE`, `DOES_NOT_SUPPORT`, `SOURCE_LEDGER`

## Primary Non-Equivalences

| ID | Non-Equivalence | Type | Provenance |
|---|---|---|---|
| `HAI-NEQ-190` | Prediction Accuracy ≠ Consumer Benefit | Conceptual Non-entailment | D12:70-70 |
| `HAI-NEQ-191` | Financial Outcome ≠ Financial Capability | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-192` | Financial Capability ≠ Unaided Skill | Conceptual Non-entailment | D12:112-120 |
| `HAI-NEQ-193` | Decision ≠ Authorization | Conceptual Non-entailment | D12:118-126 |
| `HAI-NEQ-194` | Authorization ≠ Execution | Conceptual Non-entailment | D12:120-128 |
| `HAI-NEQ-195` | Advice Quality ≠ Better Financial Behavior | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-196` | Convenience ≠ Financial Capability | Conceptual Non-entailment | D12:130-138 |
| `HAI-NEQ-197` | Personalization ≠ Suitability | Conceptual Non-entailment | D12:132-140 |
| `HAI-NEQ-198` | Personalization ≠ Fiduciary Duty | Conceptual Non-entailment | D12:136-144 |
| `HAI-NEQ-199` | Profit ≠ Best Interest | Conceptual Non-entailment | D12:138-146 |
| `HAI-NEQ-200` | Provider Objective ≠ Consumer Interest | Conceptual Non-entailment | D12:140-148 |
| `HAI-NEQ-201` | Credit Approval ≠ Affordability | Conceptual Non-entailment | D12:142-150 |
| `HAI-NEQ-202` | Credit Access ≠ Financial Well-Being | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-203` | Default Reduction ≠ Borrower Benefit | Conceptual Non-entailment | D12:146-154 |
| `HAI-NEQ-204` | Prediction Accuracy ≠ Fairness | Conceptual Non-entailment | D12:148-156 |
| `HAI-NEQ-205` | Risk Prediction ≠ Socially Desirable Insurance Design | Conceptual Non-entailment | D12:154-162 |
| `HAI-NEQ-206` | Risk Pooling ≠ Uniform Pricing | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-207` | Risk-Based Pricing ≠ Price Optimisation | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-208` | Individualized Pricing ≠ Solidarity Destruction | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-209` | Automation ≠ Autonomy Loss | Conceptual Non-entailment | D12:166-174 |
| `HAI-NEQ-210` | Automation ≠ Autonomy Preservation | Conceptual Non-entailment | D12:168-176 |
| `HAI-NEQ-211` | Precommitment ≠ Guaranteed Autonomy | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-212` | Backtest Performance ≠ Live Performance | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-213` | Forecast Accuracy ≠ Investment Return | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-214` | Investment Return ≠ Investor Welfare | Conceptual Non-entailment | D12:178-186 |
| `HAI-NEQ-271` | Information ≠ Recommendation | Conceptual Non-entailment | D12:114-122 |
| `HAI-NEQ-272` | Fewer Immediate Options ≠ Less Autonomy | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-273` | Opt-in Self-binding ≠ Opt-out Default | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-274` | Suitability ≠ Best Interest | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-275` | Best Interest ≠ Fiduciary Duty | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-276` | Fiduciary Duty ≠ AI Output Property | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-277` | Simulated Lifetime Benefit ≠ Observed Long-term Investor Welfare | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-278` | Traditional Robo-advice ≠ General-Purpose LLM Advice | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-279` | Legal Claim ≠ Normative Claim | Conceptual Non-entailment | D12:112-191 |
| `HAI-NEQ-280` | Normative Claim ≠ Empirical Claim | Conceptual Non-entailment | D12:112-191 |

## Section Locator Index

| Section ID | Type | Heading | Canonical locator |
|---|---|---|---|
| `HAI-SEC-D12-DOMAIN-SCOPE` | `DOMAIN_SCOPE` | この領域で扱うもの | D12:25-65 |
| `HAI-SEC-D12-CORE-PRINCIPLE` | `CORE_PRINCIPLE` | 中心原則（Core Principle） | D12:66-94 |
| `HAI-SEC-D12-CORE-QUESTION` | `CORE_QUESTION` | 中心問い（Core Question） | D12:95-111 |
| `HAI-SEC-D12-CORE-DISTINCTIONS` | `CORE_DISTINCTIONS` | 中心的な区別（Core Distinctions） | D12:112-191 |
| `HAI-SEC-D12-LEGAL-CLAIM-PROTOCOL` | `LEGAL_CLAIM_PROTOCOL` | Legal Claim Protocol | D12:1121-1146 |
| `HAI-SEC-D12-COUNTEREVIDENCE` | `COUNTEREVIDENCE` | Counterevidence | D12:1147-1179 |
| `HAI-SEC-D12-EVIDENCE-ARCHITECTURE` | `EVIDENCE_ARCHITECTURE` | Evidence Architecture | D12:1180-1209 |
| `HAI-SEC-D12-EVIDENCE-STATUS` | `EVIDENCE_STATUS` | Evidence Status | D12:1210-1242 |
| `HAI-SEC-D12-WHAT-WE-CAN-SAY-NOW` | `WHAT_WE_CAN_SAY_NOW` | What We Can Say Now | D12:1243-1308 |
| `HAI-SEC-D12-WHAT-WE-CANNOT-SAY-YET` | `WHAT_WE_CANNOT_SAY_YET` | What We Cannot Say Yet | D12:1309-1337 |
| `HAI-SEC-D12-BOUNDARY-CONDITIONS` | `BOUNDARY_CONDITIONS` | Boundary Conditions | D12:1338-1403 |
| `HAI-SEC-D12-RESEARCH-GAPS` | `RESEARCH_GAPS` | Research Gaps | D12:1404-1488 |
| `HAI-SEC-D12-EXISTING-THEORY-FIRST` | `EXISTING_THEORY_FIRST` | Existing-Theory-First | D12:1514-1553 |
| `HAI-SEC-D12-NEW-THEORY` | `NEW_THEORY` | New Theory? | D12:1554-1591 |
| `HAI-SEC-D12-SOURCE-LEDGER` | `SOURCE_LEDGER` | Source Ledger | D12:1592-1724 |
| `HAI-SEC-D12-CROSS-REFERENCES` | `CROSS_REFERENCES` | Cross-Domain Connections | D12:1725-1762 |
| `HAI-SEC-D12-PROPAGATION-RISKS` | `PROPAGATION_RISKS` | Propagation Risks | D12:1763-1801 |
| `HAI-SEC-D12-EXISTING-THEORY-FIRST-FINAL-JUDGMENT` | `EXISTING_THEORY_FIRST_FINAL_JUDGMENT` | Existing-Theory-First Final Judgment | D12:1802-1841 |
| `HAI-SEC-D12-FINAL-ASSESSMENT` | `FINAL_ASSESSMENT` | Final Assessment | D12:1842-1996 |
| `HAI-SEC-D12-DOES-NOT-SUPPORT` | `DOES_NOT_SUPPORT` | Does Not Support — virtual domain view | global_source_registry.domain_usage[domain=D12].does_not_support |
| `HAI-SEC-D12-DIRECT-AI-SPECIFIC-EVIDENCE` | `DIRECT_AI_SPECIFIC_EVIDENCE` | Direct AI-Specific Evidence — virtual domain view | global_source_registry.domain_usage[domain=D12; evidence_layer≈Layer B/Direct AI] |

## Domain Source Ledger

### `HAI-SRC-0069` — Regulation (EU) 2024/1689 — EU AI Act

Regulation (EU) 2024/1689

- Supports: Risk-based AI regulatory framework including relevant Annex III financial use cases.
- Does Not Support: AI credit scoring is universally prohibited.
- Local source ID: `D12-S06`

### `HAI-SRC-0105` — Regulation (EU) 2026/1744

Regulation (EU) 2026/1744

- Supports: Updated AI Act implementation timeline.
- Does Not Support: All AI Act provisions were delayed to the same date.
- Local source ID: `D12-S07`

### `HAI-SRC-0117` — Chioda et al. — FinTech Lending to Borrowers with No Credit History

Chioda et al. — FinTech Lending to Borrowers with No Credit History

- Evidence layer: `Direct AI / ML Credit`
- Supports: Alternative transaction data can improve creditworthiness prediction for borrowers without formal credit history under the studied setting.
- Does Not Support: General borrower welfare improvement; universal fairness.
- Local source ID: `D12-S01`

### `HAI-SRC-0118` — Di Maggio & Ratnadiwakara — Invisible Primes

Di Maggio & Ratnadiwakara — Invisible Primes

- Evidence layer: `Direct AI / Alternative-data Lending`
- Supports: Alternative Data can expand access for some low-score / thin-file borrowers and improve studied subsequent financial outcomes.
- Does Not Support: Universal fairness or suitability of all AI lending.
- Local source ID: `D12-S02`

### `HAI-SRC-0119` — Winder, Hildebrand & Hartmann — Biased Echoes

Winder, Hildebrand & Hartmann — Biased Echoes

- Evidence layer: `Direct LLM Financial Advice`
- Supports: Under studied conditions, LLM investment advice increased multiple dimensions of portfolio risk.
- Does Not Support: All models, users, prompts and financial tasks increase risk.
- Local source ID: `D12-S03`

### `HAI-SRC-0120` — Choukhmane et al. — AI Financial Advice

Choukhmane et al. — AI Financial Advice

- Evidence layer: `Direct LLM Financial Advice`
- Supports: Under the study’s simulation framework, LLM advice can move some decisions toward life-cycle finance prescriptions.
- Does Not Support: Observed long-term live investor welfare or actual realized returns.
- Local source ID: `D12-S04`

### `HAI-SRC-0121` — CFPB Circular 2022-03

CFPB Circular 2022-03

- Supports: Complex or black-box algorithm use does not remove the requirement to provide specific adverse-action reasons.
- Does Not Support: Universal explanation law outside the relevant US legal scope.
- Local source ID: `D12-S05`

### `HAI-SRC-0122` — FCA Targeted Support / COBS 9B

FCA Targeted Support / COBS 9B

- Supports: Targeted Support as a regulated support framework distinct from more comprehensive individualized investment advice.
- Does Not Support: AI-specific regulation or universal advice taxonomy.
- Local source ID: `D12-S08`

### `HAI-SRC-0123` — Japan FSA AI Discussion Paper Version 1.1

Japan FSA AI Discussion Paper Version 1.1

- Supports: Current Japanese regulatory-policy discussion on financial AI.
- Does Not Support: Binding AI-specific legal duties.
- Local source ID: `D12-S09`

### `HAI-SRC-0124` — Jin & Vasserman — Buying Data from Consumers

Jin & Vasserman — Buying Data from Consumers

- Evidence layer: `Adjacent Evidence`
- Supports: Voluntary behavioral monitoring can affect driving behavior, pricing, insurer profit and studied welfare outcomes.
- Does Not Support: Generative-AI-specific insurance effects.
- Local source ID: `D12-S10`

## Authority rule

This mirror is a retrieval derivative of `Human_AI_Relations_MRI_v1.0_Publication_Build.json` with canonical SHA-256 `9618804f130de0528b921c9316195dca13f4067ee265c3c060d8eb7fbe358c1c`. It should be regenerated whenever the canonical v1.0 source changes.
