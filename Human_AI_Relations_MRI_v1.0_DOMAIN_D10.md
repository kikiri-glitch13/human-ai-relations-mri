# Human–AI Relations MRI v1.0 — Domain D10 Markdown Mirror

**Domain:** Oversight・Safety・Control・Embodied Systems  
**Version:** 1.0  
**Evidence cutoff:** 2026-09  
**Status:** PUBLICATION_LOCKED  
**Public article:** https://note.com/kikiri_stoat200/n/nd3a15fcf3978  

> This Markdown file is a Web/AI retrieval mirror derived from the locked v1.0 canonical build. It is not the canonical authority. If it diverges from the canonical Publication Build JSON, the canonical build controls.

## Retrieval guidance

- Prefer this Markdown mirror for browser-based AI retrieval.
- Use `Human_AI_Relations_MRI_v1.0_DOMAIN_D10.json` when structured JSON is directly accessible.
- Use `Human_AI_Relations_MRI_v1.0_Publication_Build.json` only for full-corpus authority, reconstruction, or conflict resolution.

## Primary Major Claims

### `HAI-CLM-028`

Human presence, formal approval, or a human-in-the-loop label does not establish effective oversight or control.

- Claim type: `Conceptual`
- Claim status: `RETAINED`
- Query routes: `HAI-QRY-021`, `HAI-QRY-022`
- Supporting sources: `HAI-SRC-0007`, `HAI-SRC-0002`, `HAI-SRC-0093`, `HAI-SRC-0112`
- Provenance sections: `HAI-SEC-D10-WHAT-WE-CAN-SAY-NOW` (D10:1443-1462); `HAI-SEC-D10-CORE-DISTINCTIONS` (D10:90-364)

### `HAI-CLM-029`

Effective oversight must be evaluated through context-specific factors including observability, interpretation, authority, time, action capability, system response, feedback, recovery, and organizational capacity.

- Claim type: `Audit claim`
- Claim status: `RETAINED`
- Query routes: `HAI-QRY-021`, `HAI-QRY-022`, `HAI-QRY-023`, `HAI-QRY-032`
- Supporting sources: `HAI-SRC-0007`, `HAI-SRC-0002`, `HAI-SRC-0093`, `HAI-SRC-0113`
- Provenance sections: `HAI-SEC-D10-WHAT-WE-CAN-SAY-NOW` (D10:1443-1462); `HAI-SEC-D10-CORE-DISTINCTIONS` (D10:90-364)

### `HAI-CLM-030`

Average accuracy alone does not establish system safety.

- Claim type: `Conceptual`
- Claim status: `RETAINED`
- Query routes: `HAI-QRY-021`, `HAI-QRY-023`, `HAI-QRY-024`
- Supporting sources: `HAI-SRC-0093`, `HAI-SRC-0098`
- Provenance sections: `HAI-SEC-D10-WHAT-WE-CAN-SAY-NOW` (D10:1443-1462); `HAI-SEC-D10-CORE-DISTINCTIONS` (D10:90-364)

## Primary Query Routes

### `HAI-QRY-021` — human-in-the-loop means safe

- Core Claims: `HAI-CLM-028`, `HAI-CLM-029`, `HAI-CLM-030`
- Secondary domains: `D02`, `D09`, `D11`
- Counterexample domains: `D03`
- Key NEQs: `HAI-NEQ-142`, `HAI-NEQ-143`, `HAI-NEQ-144`, `HAI-NEQ-145`, `HAI-NEQ-146`, `HAI-NEQ-147`, `HAI-NEQ-148`, `HAI-NEQ-149`, `HAI-NEQ-150`, `HAI-NEQ-151`, `HAI-NEQ-152`, `HAI-NEQ-153`, `HAI-NEQ-154`, `HAI-NEQ-155`, `HAI-NEQ-156`, `HAI-NEQ-157`, `HAI-NEQ-158`, `HAI-NEQ-159`, `HAI-NEQ-160`, `HAI-NEQ-161`, `HAI-NEQ-162`, `HAI-NEQ-163`, `HAI-NEQ-164`, `HAI-NEQ-165`, `HAI-NEQ-166`, `HAI-NEQ-167`, `HAI-NEQ-168`, `HAI-NEQ-169`, `HAI-NEQ-170`, `HAI-NEQ-260`
- Mandatory retrieval: `DOMAIN_0_AUDIT_RULES`, `WHAT_WE_CAN_SAY_NOW`, `WHAT_WE_CANNOT_SAY_YET`, `BOUNDARY_CONDITIONS`, `DIRECT_AI_SPECIFIC_EVIDENCE`, `DOES_NOT_SUPPORT`, `SOURCE_LEDGER`

### `HAI-QRY-022` — override button / human control

- Core Claims: `HAI-CLM-028`, `HAI-CLM-029`
- Secondary domains: `D07`, `D11`, `D12`
- Counterexample domains: `D02`
- Key NEQs: `HAI-NEQ-144`, `HAI-NEQ-145`, `HAI-NEQ-146`, `HAI-NEQ-147`, `HAI-NEQ-148`, `HAI-NEQ-149`, `HAI-NEQ-150`, `HAI-NEQ-159`, `HAI-NEQ-160`, `HAI-NEQ-161`, `HAI-NEQ-162`, `HAI-NEQ-260`, `HAI-NEQ-180`
- Mandatory retrieval: `DOMAIN_0_AUDIT_RULES`, `WHAT_WE_CAN_SAY_NOW`, `WHAT_WE_CANNOT_SAY_YET`, `BOUNDARY_CONDITIONS`, `DIRECT_AI_SPECIFIC_EVIDENCE`, `DOES_NOT_SUPPORT`, `SOURCE_LEDGER`

### `HAI-QRY-023` — AI reasoning trace proves safety

- Core Claims: `HAI-CLM-029`, `HAI-CLM-030`
- Secondary domains: `D11`
- Counterexample domains: `D03`
- Key NEQs: `HAI-NEQ-154`, `HAI-NEQ-155`, `HAI-NEQ-156`, `HAI-NEQ-164`, `HAI-NEQ-263`, `HAI-NEQ-264`
- Mandatory retrieval: `DOMAIN_0_AUDIT_RULES`, `WHAT_WE_CAN_SAY_NOW`, `WHAT_WE_CANNOT_SAY_YET`, `BOUNDARY_CONDITIONS`, `DIRECT_AI_SPECIFIC_EVIDENCE`, `DOES_NOT_SUPPORT`, `SOURCE_LEDGER`

## Primary Non-Equivalences

| ID | Non-Equivalence | Type | Provenance |
|---|---|---|---|
| `HAI-NEQ-142` | Human Presence ≠ Effective Oversight | Conceptual Non-entailment | D10:92-92 |
| `HAI-NEQ-143` | Human-in-the-loop ≠ Effective Human Control | Conceptual Non-entailment | D10:109-109 |
| `HAI-NEQ-144` | Override Button ≠ Effective Override | Conceptual Non-entailment | D10:139-139 |
| `HAI-NEQ-145` | Detection ≠ Interpretation | Conceptual Non-entailment | D10:157-157 |
| `HAI-NEQ-146` | Interpretation ≠ Correct Decision | Conceptual Non-entailment | D10:163-163 |
| `HAI-NEQ-147` | Correct Decision ≠ Successful Execution | Conceptual Non-entailment | D10:169-169 |
| `HAI-NEQ-148` | Successful Execution ≠ Recovery | Conceptual Non-entailment | D10:182-182 |
| `HAI-NEQ-149` | Stop ≠ Safe State | Conceptual Non-entailment | D10:188-188 |
| `HAI-NEQ-150` | Safe State ≠ Recovery | Conceptual Non-entailment | D10:188-188 |
| `HAI-NEQ-151` | Monitoring ≠ Control | Conceptual Non-entailment | D10:208-208 |
| `HAI-NEQ-152` | Monitoring ≠ Situation Awareness | Conceptual Non-entailment | D10:221-221 |
| `HAI-NEQ-153` | Data Availability ≠ Usable Observability | Conceptual Non-entailment | D10:227-227 |
| `HAI-NEQ-154` | Explanation ≠ Process Visibility | Conceptual Non-entailment | D10:233-233 |
| `HAI-NEQ-155` | Visible Reasoning ≠ Faithful Reasoning | Conceptual Non-entailment | D10:244-244 |
| `HAI-NEQ-156` | Faithful Reasoning ≠ Safe Reasoning | Conceptual Non-entailment | D10:250-250 |
| `HAI-NEQ-157` | Average Accuracy ≠ System Safety | Conceptual Non-entailment | D10:265-265 |
| `HAI-NEQ-158` | Reliable Automation ≠ Easy Human Takeover | Conceptual Non-entailment | D10:281-281 |
| `HAI-NEQ-159` | Formal Authority ≠ Practical Authority | Conceptual Non-entailment | D10:287-287 |
| `HAI-NEQ-160` | Authority ≠ Action Capability | Conceptual Non-entailment | D10:301-301 |
| `HAI-NEQ-161` | Action Issued ≠ Action Executed | Conceptual Non-entailment | D10:307-307 |
| `HAI-NEQ-162` | Action Executed ≠ Desired State Achieved | Conceptual Non-entailment | D10:313-313 |
| `HAI-NEQ-163` | Redundancy ≠ Independence | Conceptual Non-entailment | D10:320-320 |
| `HAI-NEQ-164` | AI Critic ≠ Independent Assurance | Conceptual Non-entailment | D10:326-326 |
| `HAI-NEQ-165` | Safety ≠ Reliability | Conceptual Non-entailment | D10:332-332 |
| `HAI-NEQ-166` | Reliability ≠ Continuity | Conceptual Non-entailment | D10:340-340 |
| `HAI-NEQ-167` | Reversibility ≠ Safety | Conceptual Non-entailment | D10:347-347 |
| `HAI-NEQ-168` | Human Responsibility ≠ Human Control | Conceptual Non-entailment | D10:359-359 |
| `HAI-NEQ-169` | Multiple AI Reviewers ≠ Independent Assurance | Conceptual Non-entailment | D10:90-364 |
| `HAI-NEQ-170` | Single-Agent Safety ≠ Multi-Agent Safety | Conceptual Non-entailment | D10:90-364 |
| `HAI-NEQ-260` | Formal Control ≠ Practical Control | Conceptual Non-entailment | D10:283-291 |

## Section Locator Index

| Section ID | Type | Heading | Canonical locator |
|---|---|---|---|
| `HAI-SEC-D10-DOCUMENT-STATUS` | `DOCUMENT_STATUS` | Document Status | D10:20-62 |
| `HAI-SEC-D10-CORE-QUESTION` | `CORE_QUESTION` | Core Question | D10:63-89 |
| `HAI-SEC-D10-CORE-DISTINCTIONS` | `CORE_DISTINCTIONS` | Core Distinctions | D10:90-364 |
| `HAI-SEC-D10-EXISTING-RESEARCH-TRADITIONS` | `EXISTING_RESEARCH_TRADITIONS` | Existing Research Traditions | D10:365-433 |
| `HAI-SEC-D10-EXISTING-THEORY-FIRST` | `EXISTING_THEORY_FIRST` | Existing-Theory-First | D10:434-457 |
| `HAI-SEC-D10-COUNTEREVIDENCE` | `COUNTEREVIDENCE` | Counterevidence | D10:1334-1351 |
| `HAI-SEC-D10-EVIDENCE-ARCHITECTURE` | `EVIDENCE_ARCHITECTURE` | Evidence Architecture | D10:1373-1395 |
| `HAI-SEC-D10-EVIDENCE-STATUS` | `EVIDENCE_STATUS` | Evidence Status | D10:1396-1442 |
| `HAI-SEC-D10-WHAT-WE-CAN-SAY-NOW` | `WHAT_WE_CAN_SAY_NOW` | What We Can Say Now / 現時点で言えること | D10:1443-1462 |
| `HAI-SEC-D10-WHAT-WE-CANNOT-SAY-YET` | `WHAT_WE_CANNOT_SAY_YET` | What We Cannot Say Yet / 現時点では言えないこと | D10:1463-1483 |
| `HAI-SEC-D10-BOUNDARY-CONDITIONS` | `BOUNDARY_CONDITIONS` | Boundary Conditions | D10:1484-1538 |
| `HAI-SEC-D10-RESEARCH-GAPS` | `RESEARCH_GAPS` | Research Gaps | D10:1585-1636 |
| `HAI-SEC-D10-SOURCE-LEDGER` | `SOURCE_LEDGER` | Source Ledger | D10:1637-1841 |
| `HAI-SEC-D10-CROSS-REFERENCES` | `CROSS_REFERENCES` | Cross-References | D10:1842-1885 |
| `HAI-SEC-D10-EXISTING-THEORY-FIRST-FINAL-JUDGMENT` | `EXISTING_THEORY_FIRST_FINAL_JUDGMENT` | Existing-Theory-First Final Judgment | D10:1886-1919 |
| `HAI-SEC-D10-FINAL-ASSESSMENT` | `FINAL_ASSESSMENT` | Final Assessment | D10:1920-2002 |
| `HAI-SEC-D10-DOES-NOT-SUPPORT` | `DOES_NOT_SUPPORT` | Does Not Support — virtual domain view | global_source_registry.domain_usage[domain=D10].does_not_support |
| `HAI-SEC-D10-DIRECT-AI-SPECIFIC-EVIDENCE` | `DIRECT_AI_SPECIFIC_EVIDENCE` | Direct AI-Specific Evidence — virtual domain view | global_source_registry.domain_usage[domain=D10; evidence_layer≈Layer B/Direct AI] |

## Domain Source Ledger

### `HAI-SRC-0002` — Parasuraman, Sheridan & Wickens (2000)

Parasuraman, R., Sheridan, T. B., & Wickens, C. D. (2000). A model for types and levels of human interaction with automation. IEEE Transactions on Systems, Man, and Cybernetics—Part A, 30(3), 286–297.

- Evidence layer: `Existing Research Tradition.`
- Supports: Automation should be analyzed function-by-function rather than as a single scalar.
- Does Not Support: One universally optimal automation level.
- Local source ID: `D10-S02`

### `HAI-SRC-0007` — Endsley & Kiris — Out-of-the-Loop

Endsley, M. R., & Kiris, E. O. (1995). The Out-of-the-Loop Performance Problem and Level of Control in Automation. Human Factors, 37(2), 381–394.

- Evidence layer: `Existing Human Factors Evidence`
- Evidence status: `A within studied scope.`
- Supports: Automation conditions can reduce Situation Awareness and impair failure takeover performance.
- Does Not Support: Universal deskilling; direct transfer to current Agentic AI.
- Local source ID: `D10-S01`

### `HAI-SRC-0069` — Regulation (EU) 2024/1689 — EU AI Act

Regulation (EU) 2024/1689

- Local source ID: `D10-S14`

### `HAI-SRC-0092` — Bainbridge (1983)

Bainbridge, L. Ironies of Automation.

- Evidence layer: `Existing Research Tradition.`
- Supports: Automation can leave humans responsible for difficult abnormal conditions.
- Does Not Support: Automation is inherently unsafe.
- Local source ID: `D10-S03`

### `HAI-SRC-0093` — Leveson — STAMP / Systems-Theoretic Safety

Leveson, N. Engineering a Safer World: Systems Thinking Applied to Safety.

- Evidence layer: `Existing Safety Research Tradition.`
- Supports: Safety analysis based on constraints, control structure, feedback and sociotechnical interaction rather than only linear component failures.
- Does Not Support: Every AI hazard requires STPA specifically.
- Local source ID: `D10-S04`

### `HAI-SRC-0094` — Weak-to-Strong Generalization

OpenAI research, 2023

- Evidence layer: `Direct AI-Specific Research`
- Supports: Scalable Oversight can be studied empirically through weak-supervisor / strong-model analogues.
- Does Not Support: Superhuman AI alignment or oversight is solved.
- Local source ID: `D10-S09`

### `HAI-SRC-0095` — Meier et al. (2026)

Meier, D., Francis, L. J., Kaiser, M. B., Ruas, T., Wahle, J. P., & Gipp, B. Risky Business: Measuring The Faithfulness-Safety Tension.

- Evidence layer: `Direct AI-Specific Evidence`
- Evidence status: `B with strong scope limitation.`
- Supports: Faithful Reasoning ≠ Safe Reasoning.
- Does Not Support: Faithfulness generally decreases safety across models and environments.
- Local source ID: `D10-S10`

### `HAI-SRC-0096` — Li, Naito & Shirado — HiddenBench

Li, Y., Naito, A., & Shirado, H. Systematic Failures in Collective Reasoning under Distributed Information in Multi-Agent LLMs.

- Evidence layer: `Direct AI-Specific Evidence`
- Evidence status: `B within studied setting.`
- Supports: Severe collective reasoning failure can occur in distributed-information Multi-Agent LLM settings.
- Does Not Support: All Multi-Agent Systems are unsafe or structurally inferior.
- Local source ID: `D10-S11`

### `HAI-SRC-0097` — ISO 18497-1:2024

Agricultural machinery and tractors — Safety of partially automated, semi-autonomous and autonomous machinery — Part 1: Machine design principles and vocabulary

- Supports: Agriculture-specific embodied safety boundary.
- Does Not Support: General Agentic AI safety claims.
- Local source ID: `D10-S12`

### `HAI-SRC-0098` — ISO 21448:2022

Road vehicles — Safety of the intended functionality

- Evidence layer: `Adjacent Sector Safety Standard.`
- Supports: Hazard can arise from specification / performance insufficiency without component failure.
- Does Not Support: Direct application to general-purpose AI agents.
- Local source ID: `D10-S13`

### `HAI-SRC-0099` — DoD Directive 3000.09

Autonomy in Weapon Systems

- Does Not Support: General civilian AI oversight requirement.
- Local source ID: `D10-S15`

## Authority rule

This mirror is a retrieval derivative of `Human_AI_Relations_MRI_v1.0_Publication_Build.json` with canonical SHA-256 `9618804f130de0528b921c9316195dca13f4067ee265c3c060d8eb7fbe358c1c`. It should be regenerated whenever the canonical v1.0 source changes.
