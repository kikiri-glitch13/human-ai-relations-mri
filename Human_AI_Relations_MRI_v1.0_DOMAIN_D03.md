# Human–AI Relations MRI v1.0 — Domain D03 Markdown Mirror

**Domain:** Trust・Reliance・Appropriate Reliance・Calibration  
**Version:** 1.0  
**Evidence cutoff:** 2026-09  
**Status:** PUBLICATION_LOCKED  
**Public article:** https://note.com/kikiri_stoat200/n/n5699333c2aef  

> This Markdown file is a Web/AI retrieval mirror derived from the locked v1.0 canonical build. It is not the canonical authority. If it diverges from the canonical Publication Build JSON, the canonical build controls.

## Retrieval guidance

- Prefer this Markdown mirror for browser-based AI retrieval.
- Use `Human_AI_Relations_MRI_v1.0_DOMAIN_D03.json` when structured JSON is directly accessible.
- Use `Human_AI_Relations_MRI_v1.0_Publication_Build.json` only for full-corpus authority, reconstruction, or conflict resolution.

## Primary Major Claims

### `HAI-CLM-009`

Trust, reliance, and appropriate reliance are distinct constructs and should not be treated as one quantity.

- Claim type: `Conceptual`
- Claim status: `RETAINED`
- Query routes: `HAI-QRY-006`
- Supporting sources: `HAI-SRC-0001`
- Provenance sections: `HAI-SEC-D03-WHAT-WE-CAN-SAY-NOW` (D03:847-866); `HAI-SEC-D03-CORE-DISTINCTIONS` (D03:89-272)

### `HAI-CLM-010`

Explanation alone does not ensure appropriate reliance; its effects depend on factors such as task difficulty and verification cost.

- Claim type: `Empirical / Conceptual`
- Claim status: `RETAINED_SCOPE_LIMITED`
- Empirical evidence status: `B`
- Query routes: `HAI-QRY-006`, `HAI-QRY-007`
- Supporting sources: `HAI-SRC-0035`, `HAI-SRC-0036`, `HAI-SRC-0031`
- Provenance sections: `HAI-SEC-D03-WHAT-WE-CAN-SAY-NOW` (D03:847-866); `HAI-SEC-D03-DIRECT-AI-SPECIFIC-EVIDENCE` (global_source_registry.domain_usage[domain=D03; evidence_layer≈Layer B/Direct AI]); `HAI-SEC-D03-CORE-DISTINCTIONS` (D03:89-272)

### `HAI-CLM-011`

Sycophantic behavior occurs in tested LLM systems, but model-side sycophancy alone does not establish increased human trust, reliance, or downstream harm.

- Claim type: `Descriptive + boundary`
- Claim status: `RETAINED_SCOPE_LIMITED`
- Query routes: `HAI-QRY-006`, `HAI-QRY-008`
- Supporting sources: `HAI-SRC-0038`
- Provenance sections: `HAI-SEC-D03-WHAT-WE-CAN-SAY-NOW` (D03:847-866); `HAI-SEC-D03-DIRECT-AI-SPECIFIC-EVIDENCE` (global_source_registry.domain_usage[domain=D03; evidence_layer≈Layer B/Direct AI]); `HAI-SEC-D03-WHAT-WE-CANNOT-SAY-YET` (D03:867-895)

## Primary Query Routes

### `HAI-QRY-006` — trust / overtrust / reliance

- Core Claims: `HAI-CLM-009`, `HAI-CLM-010`, `HAI-CLM-011`
- Secondary domains: `D02`, `D10`, `D12`
- Counterexample domains: `D09`
- Key NEQs: `HAI-NEQ-029`, `HAI-NEQ-030`, `HAI-NEQ-031`, `HAI-NEQ-032`, `HAI-NEQ-033`, `HAI-NEQ-034`, `HAI-NEQ-035`, `HAI-NEQ-036`, `HAI-NEQ-037`, `HAI-NEQ-038`, `HAI-NEQ-039`, `HAI-NEQ-040`, `HAI-NEQ-041`, `HAI-NEQ-042`, `HAI-NEQ-043`, `HAI-NEQ-224`, `HAI-NEQ-225`, `HAI-NEQ-226`, `HAI-NEQ-228`, `HAI-NEQ-229`, `HAI-NEQ-221`
- Mandatory retrieval: `DOMAIN_0_AUDIT_RULES`, `WHAT_WE_CAN_SAY_NOW`, `WHAT_WE_CANNOT_SAY_YET`, `BOUNDARY_CONDITIONS`, `DIRECT_AI_SPECIFIC_EVIDENCE`, `DOES_NOT_SUPPORT`, `SOURCE_LEDGER`

### `HAI-QRY-007` — explanation improves decisions

- Core Claims: `HAI-CLM-010`
- Secondary domains: `D02`, `D10`, `D11`
- Counterexample domains: `D10`
- Key NEQs: `HAI-NEQ-026`, `HAI-NEQ-037`, `HAI-NEQ-038`, `HAI-NEQ-039`, `HAI-NEQ-040`, `HAI-NEQ-154`, `HAI-NEQ-258`, `HAI-NEQ-262`, `HAI-NEQ-263`, `HAI-NEQ-264`
- Mandatory retrieval: `DOMAIN_0_AUDIT_RULES`, `WHAT_WE_CAN_SAY_NOW`, `WHAT_WE_CANNOT_SAY_YET`, `BOUNDARY_CONDITIONS`, `DIRECT_AI_SPECIFIC_EVIDENCE`, `DOES_NOT_SUPPORT`, `SOURCE_LEDGER`

### `HAI-QRY-008` — AI agreement validates user belief

- Core Claims: `HAI-CLM-011`
- Secondary domains: `D04`, `D05`, `D06`
- Counterexample domains: `D04`
- Key NEQs: `HAI-NEQ-043`, `HAI-NEQ-055`, `HAI-NEQ-074`, `HAI-NEQ-075`, `HAI-NEQ-228`, `HAI-NEQ-229`
- Mandatory retrieval: `DOMAIN_0_AUDIT_RULES`, `WHAT_WE_CAN_SAY_NOW`, `WHAT_WE_CANNOT_SAY_YET`, `BOUNDARY_CONDITIONS`, `DIRECT_AI_SPECIFIC_EVIDENCE`, `DOES_NOT_SUPPORT`, `SOURCE_LEDGER`

## Primary Non-Equivalences

| ID | Non-Equivalence | Type | Provenance |
|---|---|---|---|
| `HAI-NEQ-029` | Trust ≠ Reliance | Conceptual Non-entailment | D03:84-84 |
| `HAI-NEQ-030` | Reliance ≠ Compliance | Conceptual Non-entailment | D03:109-109 |
| `HAI-NEQ-031` | Reliance ≠ Appropriate Reliance | Conceptual Non-entailment | D03:84-84 |
| `HAI-NEQ-032` | High Trust ≠ Good Outcome | Conceptual Non-entailment | D03:129-129 |
| `HAI-NEQ-033` | Low Trust ≠ Safety | Conceptual Non-entailment | D03:136-136 |
| `HAI-NEQ-034` | Accuracy ≠ Trustworthiness | Conceptual Non-entailment | D03:143-143 |
| `HAI-NEQ-035` | Confidence ≠ Accuracy | Conceptual Non-entailment | D03:160-160 |
| `HAI-NEQ-036` | Verbalized Confidence ≠ Calibrated Probability | Conceptual Non-entailment | D03:166-166 |
| `HAI-NEQ-037` | Explanation ≠ Understanding | Conceptual Non-entailment | D03:174-174 |
| `HAI-NEQ-038` | Explanation ≠ Calibration | Conceptual Non-entailment | D03:180-180 |
| `HAI-NEQ-039` | Explanation ≠ Appropriate Reliance | Conceptual Non-entailment | D03:186-186 |
| `HAI-NEQ-040` | Explanation ≠ Verification | Conceptual Non-entailment | D03:192-192 |
| `HAI-NEQ-041` | Error Detection ≠ Correct Override | Conceptual Non-entailment | D03:225-225 |
| `HAI-NEQ-042` | Human Override ≠ Better Decision | Conceptual Non-entailment | D03:231-231 |
| `HAI-NEQ-043` | Agreement ≠ Independent Validation | Conceptual Non-entailment | D03:255-255 |
| `HAI-NEQ-224` | Automation Bias ≠ Trust | Conceptual Non-entailment | D03:198-198 |
| `HAI-NEQ-225` | Algorithm Aversion ≠ General Distrust | Conceptual Non-entailment | D03:213-213 |
| `HAI-NEQ-226` | Algorithm Appreciation ≠ Appropriate Reliance | Conceptual Non-entailment | D03:219-219 |
| `HAI-NEQ-227` | Human Review ≠ Effective Review | Conceptual Non-entailment | D03:237-237 |
| `HAI-NEQ-228` | Sycophancy ≠ Human Trust Increase | Conceptual Non-entailment | D03:261-261 |
| `HAI-NEQ-229` | Sycophancy ≠ Human Reliance Increase | Conceptual Non-entailment | D03:267-267 |

## Section Locator Index

| Section ID | Type | Heading | Canonical locator |
|---|---|---|---|
| `HAI-SEC-D03-DOCUMENT-STATUS` | `DOCUMENT_STATUS` | Document Status | D03:20-35 |
| `HAI-SEC-D03-DOMAIN-SCOPE` | `DOMAIN_SCOPE` | Domain | D03:36-70 |
| `HAI-SEC-D03-CORE-QUESTION` | `CORE_QUESTION` | Core Question | D03:71-88 |
| `HAI-SEC-D03-CORE-DISTINCTIONS` | `CORE_DISTINCTIONS` | Key Distinctions | D03:89-272 |
| `HAI-SEC-D03-EXISTING-RESEARCH-TRADITIONS` | `EXISTING_RESEARCH_TRADITIONS` | Existing Research Traditions | D03:369-410 |
| `HAI-SEC-D03-ALTERNATIVE-EXPLANATIONS` | `ALTERNATIVE_EXPLANATIONS` | Alternative Explanations | D03:763-783 |
| `HAI-SEC-D03-COUNTEREVIDENCE` | `COUNTEREVIDENCE` | Counterevidence | D03:784-808 |
| `HAI-SEC-D03-EVIDENCE-STATUS` | `EVIDENCE_STATUS` | Evidence Status | D03:809-846 |
| `HAI-SEC-D03-WHAT-WE-CAN-SAY-NOW` | `WHAT_WE_CAN_SAY_NOW` | 現時点で言えること / What We Can Say Now | D03:847-866 |
| `HAI-SEC-D03-WHAT-WE-CANNOT-SAY-YET` | `WHAT_WE_CANNOT_SAY_YET` | 現時点では言えないこと / What We Cannot Say Yet | D03:867-895 |
| `HAI-SEC-D03-BOUNDARY-CONDITIONS` | `BOUNDARY_CONDITIONS` | Boundary Conditions | D03:896-926 |
| `HAI-SEC-D03-CROSS-REFERENCES` | `CROSS_REFERENCES` | Cross-References | D03:927-974 |
| `HAI-SEC-D03-SOURCE-LEDGER` | `SOURCE_LEDGER` | Source Ledger | D03:975-1268 |
| `HAI-SEC-D03-RESEARCH-GAPS` | `RESEARCH_GAPS` | Research Gaps | D03:1269-1307 |
| `HAI-SEC-D03-EXISTING-THEORY-FIRST-FINAL-JUDGMENT` | `EXISTING_THEORY_FIRST_FINAL_JUDGMENT` | Existing-Theory-First Final Judgment | D03:1308-1340 |
| `HAI-SEC-D03-FINAL-ASSESSMENT` | `FINAL_ASSESSMENT` | Final Assessment | D03:1341-1393 |
| `HAI-SEC-D03-DOES-NOT-SUPPORT` | `DOES_NOT_SUPPORT` | Does Not Support — virtual domain view | global_source_registry.domain_usage[domain=D03].does_not_support |
| `HAI-SEC-D03-DIRECT-AI-SPECIFIC-EVIDENCE` | `DIRECT_AI_SPECIFIC_EVIDENCE` | Direct AI-Specific Evidence — virtual domain view | global_source_registry.domain_usage[domain=D03; evidence_layer≈Layer B/Direct AI] |

## Domain Source Ledger

### `HAI-SRC-0001` — Lee & See (2004)

Lee, J. D., & See, K. A. (2004). Trust in Automation: Designing for Appropriate Reliance. Human Factors, 46(1), 50–80.

- Evidence layer: `Layer A — Existing Research Tradition`
- Evidence status: `Conceptual frameworkのため単一A–Fを機械的に付与しない。`
- Supports: TrustとRelianceの区別、Appropriate Reliance、Misuse / Disuse、Calibrationの重要性。
- Does Not Support: Modern LLMにおける直接Effect Size。
- Key limitation: Generative AI以前のAutomation研究を統合したFramework。
- Local source ID: `D3-S01`

### `HAI-SRC-0005` — Dietvorst et al. (2015)

Dietvorst, B. J., Simmons, J. P., & Massey, C. (2015). Algorithm Aversion: People Erroneously Avoid Algorithms After Seeing Them Err. Journal of Experimental Psychology: General, 144(1), 114–126.

- Evidence layer: `Layer A / C`
- Evidence status: `A within studied scope`
- Supports: Algorithm Errorを観察した後にAlgorithmをUnderuseする条件。
- Does Not Support: General human distrust of AI.
- Local source ID: `D3-S03`

### `HAI-SRC-0006` — Logg, Minson & Moore (2019)

Logg, J. M., Minson, J. A., & Moore, D. A. (2019). Algorithm Appreciation: People Prefer Algorithmic to Human Judgment. Organizational Behavior and Human Decision Processes, 151, 90–103.

- Evidence layer: `Layer A / C`
- Evidence status: `A within studied scope`
- Supports: 一定のNumerical Judgment条件でAlgorithmic AdviceがHuman Adviceより強くWeightされること。
- Does Not Support: Algorithm Appreciation = Appropriate Reliance。
- Local source ID: `D3-S04`

### `HAI-SRC-0034` — Skitka, Mosier & Burdick (1999)

Skitka, L. J., Mosier, K. L., & Burdick, M. (1999). Does Automation Bias Decision-Making? International Journal of Human-Computer Studies.

- Evidence layer: `Layer A`
- Evidence status: `A within studied scope`
- Supports: Automation Aid使用時にCommission / Omission Errorが生じ得ること。
- Does Not Support: Modern LLMで同じEffect Sizeが必ず生じること。
Automation Bias = Psychological Trust。
- Local source ID: `D3-S02`

### `HAI-SRC-0035` — Buçinca, Malaya & Gajos (2021)

Buçinca, Z., Malaya, M. B., & Gajos, K. Z. (2021). To Trust or to Think: Cognitive Forcing Functions Can Reduce Overreliance on AI in AI-assisted Decision-making.

- Evidence layer: `Layer B — Direct AI-Specific Evidence`
- Evidence status: `B within studied conditions`
- Supports: Cognitive Forcingが特定条件でOverrelianceを減らし得ること。
Explanationだけでは十分でない場合があること。
- Does Not Support: Cognitive Forcingが普遍的に必要であること。
- Local source ID: `D3-S05`

### `HAI-SRC-0036` — Vasconcelos et al. (2023)

Vasconcelos, H., et al. (2023). Explanations Can Reduce Overreliance on AI Systems During Decision-Making.

- Evidence layer: `Layer B`
- Evidence status: `B within studied conditions`
- Supports: Explanationの効果がTask Difficulty / Verification Costに依存すること。
- Does Not Support: ExplanationがすべてのTaskでOverrelianceを減らすこと。
- Local source ID: `D3-S06`

### `HAI-SRC-0037` — Xiong et al. (2024)

Xiong, M., et al. (2024). Can LLMs Express Their Uncertainty? An Empirical Evaluation of Confidence Elicitation in LLMs.

- Evidence layer: `Layer B`
- Evidence status: `B for tested model behavior`
- Supports: LLM Verbalized ConfidenceがModel、Task、Elicitation Methodに依存し、Calibrated Probabilityとして単純利用できないこと。
- Does Not Support: All LLMs are uniformly overconfident。
Human Relianceへの直接Effect。
- Local source ID: `D3-S07`

### `HAI-SRC-0038` — Sharma et al. (2024)

Sharma, M., et al. (2024). Towards Understanding Sycophancy in Language Models.

- Evidence layer: `Layer B`
- Evidence status: `B for model behavior`
- Supports: Tested AssistantでSycophancyが生じること。
Human Preference Dataがbelief-matching responseを好む場合があること。
- Does Not Support: Sycophancy necessarily increases Human Trust / Reliance / worsens downstream decision.
- Local source ID: `D3-S08`

### `HAI-SRC-0039` — Cohn et al. (2024)

Cohn, M., et al. (2024). Believing Anthropomorphism: Examining the Role of Anthropomorphic Cues on Trust in Large Language Models.

- Evidence layer: `Layer B`
- Evidence status: `B within studied conditions`
- Supports: VoiceやFirst-person Cueが特定ContextでPerceived Accuracy等を変化させ得ること。
- Does Not Support: Anthropomorphic Design necessarily causes Overtrust.
- Local source ID: `D3-S09`

### `HAI-SRC-0040` — Dell'Acqua et al. — Jagged Technological Frontier

Dell'Acqua, F., et al. Navigating the Jagged Technological Frontier: Field Experimental Evidence of the Effects of Artificial Intelligence on Knowledge Worker Productivity and Quality.

- Evidence layer: `Layer B`
- Evidence status: `B within studied task domain`
- Supports: Generative AI Benefit / HarmがTask Capability Boundaryによって異なり得ること。
- Does Not Support: Psychological TrustがPerformance差の原因だったこと。
- Local source ID: `D3-S10`

## Authority rule

This mirror is a retrieval derivative of `Human_AI_Relations_MRI_v1.0_Publication_Build.json` with canonical SHA-256 `9618804f130de0528b921c9316195dca13f4067ee265c3c060d8eb7fbe358c1c`. It should be regenerated whenever the canonical v1.0 source changes.
