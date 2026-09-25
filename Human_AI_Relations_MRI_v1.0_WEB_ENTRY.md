# Human–AI Relations Audit Index β
## Machine Retrieval Index v1.0 — Web Retrieval Entry

**Version:** 1.0  
**Evidence cutoff:** 2026-09  
**Status:** PUBLICATION_LOCKED  

This file is the lightweight Web/AI entry point for MRI v1.0.

The full `Human_AI_Relations_MRI_v1.0_Publication_Build.json` remains the canonical machine authority. The files listed here are retrieval derivatives designed so that a browsing system can read only the small file(s) needed for a question.

## Recommended retrieval sequence

1. Read this `WEB_ENTRY.md`.
2. Read `Human_AI_Relations_MRI_v1.0_QUERY_ROUTES.json` if JSON access is available, or use the Query Route table below.
3. Map the natural-language question to one or more `HAI-QRY-*` routes.
4. Open the relevant **Domain Markdown mirror (`DOMAIN_Dxx.md`) first**.
5. If structured JSON is accessible and useful, open the matching `DOMAIN_Dxx.json` shard.
6. Retrieve linked `HAI-CLM-*`, `HAI-NEQ-*`, section locators, source support, limitations, and `Does Not Support` constraints.
7. Use `Human_AI_Relations_MRI_v1.0_CLAIMS.json` for global Claim lookup and `Human_AI_Relations_MRI_v1.0_SOURCE_INDEX.json` for global source discovery.
8. Use the public note article and/or the canonical full JSON only when deeper context or authority resolution is required.

Do not collapse Claim Type, Evidence Layer, Evidence Status, Boundary Conditions, or `Does Not Support`.

## Core counts

- `domains`: 13
- `canonical_vocabulary_records`: 72
- `non_equivalence_records`: 280
- `claim_records`: 37
- `query_routes`: 36
- `global_source_entities`: 124
- `local_source_records`: 146
- `section_records`: 257
- `provenance_records`: 317
- `domain_reverse_index_records`: 13
- `domain_source_index_records`: 146
- `corpus_source_documents`: 13
- `neq_clusters`: 13

## Domain retrieval map

| Domain | Topic | Markdown mirror (preferred) | JSON shard | Public article |
|---|---|---|---|---|
| D00 | Cross-Domain Audit Protocol | [Human_AI_Relations_MRI_v1.0_DOMAIN_D00.md](Human_AI_Relations_MRI_v1.0_DOMAIN_D00.md) | [Human_AI_Relations_MRI_v1.0_DOMAIN_D00.json](Human_AI_Relations_MRI_v1.0_DOMAIN_D00.json) | https://note.com/kikiri_stoat200/n/nb6cb682cad9f |
| D01 | Learning・Capability Formation | [Human_AI_Relations_MRI_v1.0_DOMAIN_D01.md](Human_AI_Relations_MRI_v1.0_DOMAIN_D01.md) | [Human_AI_Relations_MRI_v1.0_DOMAIN_D01.json](Human_AI_Relations_MRI_v1.0_DOMAIN_D01.json) | https://note.com/kikiri_stoat200/n/n455d371bf73e |
| D02 | Decision Formation・Decision Support | [Human_AI_Relations_MRI_v1.0_DOMAIN_D02.md](Human_AI_Relations_MRI_v1.0_DOMAIN_D02.md) | [Human_AI_Relations_MRI_v1.0_DOMAIN_D02.json](Human_AI_Relations_MRI_v1.0_DOMAIN_D02.json) | https://note.com/kikiri_stoat200/n/na4b53c0bf5c2 |
| D03 | Trust・Reliance・Appropriate Reliance・Calibration | [Human_AI_Relations_MRI_v1.0_DOMAIN_D03.md](Human_AI_Relations_MRI_v1.0_DOMAIN_D03.md) | [Human_AI_Relations_MRI_v1.0_DOMAIN_D03.json](Human_AI_Relations_MRI_v1.0_DOMAIN_D03.json) | https://note.com/kikiri_stoat200/n/n5699333c2aef |
| D04 | Communication・Mediation・Translation・Representation | [Human_AI_Relations_MRI_v1.0_DOMAIN_D04.md](Human_AI_Relations_MRI_v1.0_DOMAIN_D04.md) | [Human_AI_Relations_MRI_v1.0_DOMAIN_D04.json](Human_AI_Relations_MRI_v1.0_DOMAIN_D04.json) | https://note.com/kikiri_stoat200/n/nef06a51db232 |
| D05 | Companion・Attachment・Intimacy | [Human_AI_Relations_MRI_v1.0_DOMAIN_D05.md](Human_AI_Relations_MRI_v1.0_DOMAIN_D05.md) | [Human_AI_Relations_MRI_v1.0_DOMAIN_D05.json](Human_AI_Relations_MRI_v1.0_DOMAIN_D05.json) | https://note.com/kikiri_stoat200/n/n51f373a1a381 |
| D06 | Mental Health・Psychological Support | [Human_AI_Relations_MRI_v1.0_DOMAIN_D06.md](Human_AI_Relations_MRI_v1.0_DOMAIN_D06.md) | [Human_AI_Relations_MRI_v1.0_DOMAIN_D06.json](Human_AI_Relations_MRI_v1.0_DOMAIN_D06.json) | https://note.com/kikiri_stoat200/n/n9ec3e01fa26d |
| D07 | Care・Aging・Supported Decision-Making | [Human_AI_Relations_MRI_v1.0_DOMAIN_D07.md](Human_AI_Relations_MRI_v1.0_DOMAIN_D07.md) | [Human_AI_Relations_MRI_v1.0_DOMAIN_D07.json](Human_AI_Relations_MRI_v1.0_DOMAIN_D07.json) | https://note.com/kikiri_stoat200/n/n46bfd11c0915 |
| D08 | Accessibility・Assistive Technology・Participation | [Human_AI_Relations_MRI_v1.0_DOMAIN_D08.md](Human_AI_Relations_MRI_v1.0_DOMAIN_D08.md) | [Human_AI_Relations_MRI_v1.0_DOMAIN_D08.json](Human_AI_Relations_MRI_v1.0_DOMAIN_D08.json) | https://note.com/kikiri_stoat200/n/n5d7805b07c1c |
| D09 | Work・Organization・Algorithmic Management | [Human_AI_Relations_MRI_v1.0_DOMAIN_D09.md](Human_AI_Relations_MRI_v1.0_DOMAIN_D09.md) | [Human_AI_Relations_MRI_v1.0_DOMAIN_D09.json](Human_AI_Relations_MRI_v1.0_DOMAIN_D09.json) | https://note.com/kikiri_stoat200/n/n2ad28a452953 |
| D10 | Oversight・Safety・Control・Embodied Systems | [Human_AI_Relations_MRI_v1.0_DOMAIN_D10.md](Human_AI_Relations_MRI_v1.0_DOMAIN_D10.md) | [Human_AI_Relations_MRI_v1.0_DOMAIN_D10.json](Human_AI_Relations_MRI_v1.0_DOMAIN_D10.json) | https://note.com/kikiri_stoat200/n/nd3a15fcf3978 |
| D11 | Institution・Law・Governance・Responsibility | [Human_AI_Relations_MRI_v1.0_DOMAIN_D11.md](Human_AI_Relations_MRI_v1.0_DOMAIN_D11.md) | [Human_AI_Relations_MRI_v1.0_DOMAIN_D11.json](Human_AI_Relations_MRI_v1.0_DOMAIN_D11.json) | https://note.com/kikiri_stoat200/n/n2872a257aeba |
| D12 | Finance・Consumer・Credit・Insurance | [Human_AI_Relations_MRI_v1.0_DOMAIN_D12.md](Human_AI_Relations_MRI_v1.0_DOMAIN_D12.md) | [Human_AI_Relations_MRI_v1.0_DOMAIN_D12.json](Human_AI_Relations_MRI_v1.0_DOMAIN_D12.json) | https://note.com/kikiri_stoat200/n/n9be80e4bd6b3 |

## Query Route index

| Route | Query cluster | Primary domain(s) | Core Claim(s) |
|---|---|---|---|
| `HAI-QRY-001` | AI learning / retention / transfer | D01 | HAI-CLM-003, HAI-CLM-004, HAI-CLM-005 |
| `HAI-QRY-002` | AI causes deskilling | D01 | HAI-CLM-004, HAI-CLM-005 |
| `HAI-QRY-003` | permanent AI support means failure | D08 | HAI-CLM-021, HAI-CLM-022, HAI-CLM-023 |
| `HAI-QRY-004` | who really made the decision? | D02 | HAI-CLM-006, HAI-CLM-007 |
| `HAI-QRY-005` | delegation and autonomy | D02 | HAI-CLM-007, HAI-CLM-021 |
| `HAI-QRY-006` | trust / overtrust / reliance | D03 | HAI-CLM-009, HAI-CLM-010, HAI-CLM-011 |
| `HAI-QRY-007` | explanation improves decisions | D03 | HAI-CLM-010 |
| `HAI-QRY-008` | AI agreement validates user belief | D03 | HAI-CLM-011 |
| `HAI-QRY-009` | AI translation / rewriting preserves intent | D04 | HAI-CLM-012 |
| `HAI-QRY-010` | AI persuasion / deliberation / consensus | D04 | HAI-CLM-013, HAI-CLM-014 |
| `HAI-QRY-011` | AI companionship / attachment / intimacy | D05 | HAI-CLM-015, HAI-CLM-016, HAI-CLM-017 |
| `HAI-QRY-012` | AI companion reduces loneliness | D05 | HAI-CLM-017 |
| `HAI-QRY-013` | AI therapy / mental-health benefit | D06 | HAI-CLM-018, HAI-CLM-019, HAI-CLM-020 |
| `HAI-QRY-014` | crisis detection means prevention | D06 | HAI-CLM-020 |
| `HAI-QRY-015` | care monitoring / aging in place | D07 | HAI-CLM-021 |
| `HAI-QRY-016` | supported decision-making / consent | D07 | HAI-CLM-021 |
| `HAI-QRY-017` | accessibility / assistive AI | D08 | HAI-CLM-022, HAI-CLM-023 |
| `HAI-QRY-018` | AI improves productivity | D09 | HAI-CLM-024, HAI-CLM-025, HAI-CLM-026, HAI-CLM-027 |
| `HAI-QRY-019` | AI reduces workload | D09 | HAI-CLM-026, HAI-CLM-027 |
| `HAI-QRY-020` | workers trust AI because they use it | D09 | HAI-CLM-027 |
| `HAI-QRY-021` | human-in-the-loop means safe | D10 | HAI-CLM-028, HAI-CLM-029, HAI-CLM-030 |
| `HAI-QRY-022` | override button / human control | D10 | HAI-CLM-028, HAI-CLM-029 |
| `HAI-QRY-023` | AI reasoning trace proves safety | D10 | HAI-CLM-029, HAI-CLM-030 |
| `HAI-QRY-024` | accuracy means safe / fair / legitimate | D11 | HAI-CLM-030, HAI-CLM-031, HAI-CLM-032, HAI-CLM-034 |
| `HAI-QRY-025` | explanation / transparency means accountability | D11 | HAI-CLM-033 |
| `HAI-QRY-026` | audit / certification proves safety | D11 | HAI-CLM-033 |
| `HAI-QRY-027` | AI credit scoring / financial access | D12 | HAI-CLM-034, HAI-CLM-035 |
| `HAI-QRY-028` | AI investment advice | D12 | HAI-CLM-034, HAI-CLM-036 |
| `HAI-QRY-029` | agentic finance / automated execution | D12 | HAI-CLM-037 |
| `HAI-QRY-030` | AI dependence always reduces autonomy | D07, D08 | HAI-CLM-021, HAI-CLM-022 |
| `HAI-QRY-031` | personalization means user benefit | D02, D12 | HAI-CLM-007, HAI-CLM-034 |
| `HAI-QRY-032` | AI replaces humans |  | HAI-CLM-022, HAI-CLM-026, HAI-CLM-029, HAI-CLM-037 |
| `HAI-QRY-033` | does AI help / is AI beneficial? | D00 | HAI-CLM-001 |
| `HAI-QRY-034` | can existing theory be transferred to AI / do we need a new Human–AI theory? | D00 | HAI-CLM-002 |
| `HAI-QRY-035` | is human plus AI better than human or AI alone? | D02 | HAI-CLM-008 |
| `HAI-QRY-036` | is this AI claim legal, normative, or empirical? | D11, D12 | HAI-CLM-032, HAI-CLM-034 |

## Global retrieval files

- [Human_AI_Relations_MRI_v1.0_QUERY_ROUTES.json](Human_AI_Relations_MRI_v1.0_QUERY_ROUTES.json) — all Query Routes
- [Human_AI_Relations_MRI_v1.0_CLAIMS.json](Human_AI_Relations_MRI_v1.0_CLAIMS.json) — all Major Claims
- [Human_AI_Relations_MRI_v1.0_SOURCE_INDEX.json](Human_AI_Relations_MRI_v1.0_SOURCE_INDEX.json) — lightweight Global Source index
- `Human_AI_Relations_MRI_v1.0_Publication_Build.json` — canonical full machine authority
- `Human_AI_Relations_Corpus_Source_Manifest_v1.0.json` — corpus/publication manifest
- `Human_AI_Relations_Compact_Router_v1.0.md` — compact human-readable router

## Example

For **“Is Human in the Loop enough to make an AI system safe?”**, locate `HAI-QRY-021`, then open `Human_AI_Relations_MRI_v1.0_DOMAIN_D10.md` first. If JSON retrieval is available, `Human_AI_Relations_MRI_v1.0_DOMAIN_D10.json` provides the structured equivalent. The relevant Major Claims include `HAI-CLM-028`, `HAI-CLM-029`, and `HAI-CLM-030`.

## Retrieval compatibility note

Web retrieval behavior varies across AI services. A file being public and machine-readable does not guarantee that every browsing tool can fetch GitHub, follow repository links, or open JSON assets. Markdown mirrors are provided to improve compatibility with browser-based systems that can render GitHub Markdown pages but cannot follow or retrieve JSON shards.

## Authority rule

Markdown mirrors and JSON shards are retrieval derivatives. They do not replace the canonical Publication Build. If any derivative and the canonical build diverge, the canonical build controls and the derivative should be regenerated.
