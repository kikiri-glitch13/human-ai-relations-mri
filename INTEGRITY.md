# Research Integrity and Interpretation Guide

## Human–AI Relations Audit Index β

## Machine Retrieval Index v1.0

Version: 1.0
Evidence cutoff: 2026-09
Status: Publication Locked

This document provides interpretation guidance for citing, reading, analyzing, and machine-processing the Human–AI Relations Machine Retrieval Index (MRI).

MRI v1.0 is an experimental snapshot rather than a completed or validated research infrastructure.

The purpose of this document is therefore not to impose a separate legal license or contractual use policy.

Instead, it explains how the research structure is intended to be read so that individual Claims, Sources, or records are not detached from the evidential limits built into the MRI.

No separate public license for redistribution or adaptation is granted by this repository.

Questions concerning copying, redistribution, adaptation, quotation, or other reuse remain subject to applicable copyright law, other legal rights, and any separately granted permission.

---

## 1. Core principle

The MRI is not designed as a collection of isolated conclusions.

Its basic unit of interpretation includes, where applicable:

* Claim;
* Evidence Status;
* Evidence Layer;
* Claim Type;
* Non-Equivalence;
* What We Can Say Now;
* What We Cannot Say Yet;
* Boundary Conditions;
* Does Not Support;
* Source Ledger;
* provenance information.

A statement extracted from the MRI may become misleading if the surrounding limitations are removed.

Therefore:

**A retrieved Claim should not automatically be treated as the conclusion of the entire MRI.**

MRI v1.0 should also not be treated as a final or comprehensive account of Human–AI relations.

It represents a versioned audit snapshot with known limitations.

---

## 2. Do not collapse distinct claims

The MRI intentionally preserves distinctions such as:

* Performance ≠ Learning
* Learning ≠ Retention
* Retention ≠ Transfer
* Trust ≠ Reliance
* Reliance ≠ Appropriate Reliance
* Dependence ≠ Autonomy Loss
* Human Presence ≠ Effective Oversight
* Detection ≠ Prevention
* Prediction ≠ Decision
* Explanation ≠ Accountability
* Accessibility ≠ Participation
* Productivity ≠ Worker Benefit
* Legal Claim ≠ Normative Claim
* Normative Claim ≠ Empirical Claim

These distinctions are part of the retrieval structure.

Interpretations should avoid merging them into stronger propositions than the underlying evidence supports.

---

## 3. Preserve evidence boundaries

The MRI distinguishes among:

* Direct AI-Specific Evidence;
* Adjacent Evidence;
* Existing Research Tradition;
* Interpretive Inference.

Adjacent evidence should not be represented as direct evidence for a new AI configuration merely because the findings appear relevant.

Likewise, an AI-specific result should not automatically be generalized:

* from short-term to long-term;
* from adults to children;
* from one model to AI generally;
* from one task to general capability;
* from subjective outcome to functional outcome;
* from detection to prevention;
* from explanation to understanding;
* from human presence to effective control.

These boundaries are especially important because MRI v1.0 combines evidence from research traditions with different histories, methods, populations, and levels of direct relevance to current AI systems.

---

## 4. Preserve “Does Not Support”

Where a Source, Claim, or Domain includes a “Does Not Support” field, that field is part of the intended interpretation.

A Source should not be summarized as supporting a proposition that the corresponding MRI record explicitly identifies as unsupported by that Source.

“Does Not Support” does not necessarily mean that the proposition is false.

It means that the cited Source should not be used as evidence for that stronger proposition.

---

## 5. Preserve Boundary Conditions

Boundary Conditions identify the scope within which a Claim may reasonably be interpreted.

They may concern, for example:

* population;
* task;
* model;
* setting;
* duration;
* outcome measure;
* institutional context;
* evidence type;
* time period.

If a Claim is applied outside its stated scope, that change of scope should be made explicit.

Boundary Conditions should not be treated as optional detail when their omission would materially strengthen the Claim.

---

## 6. Do not convert uncertainty into certainty

The MRI uses evidence distinctions including:

A — Established within stated scope
B — Direct empirical support
C — Indirect / theory-consistent
D — Plausible / untested
E — Insufficient / indeterminate
F — Contradicted

These categories are not intended as a simple ranking of research quality.

They describe the relationship between a specific Claim and the evidence available within the stated scope.

In particular:

* insufficient evidence does not mean false;
* absence of evidence does not mean contradiction;
* plausible does not mean demonstrated;
* theory-consistent does not mean directly tested;
* direct support in one scope does not establish universal validity;
* one negative result does not necessarily establish general contradiction.

Conceptual, Normative, and Legal Claims should not automatically be forced into an empirical A–F scale where that classification would be inappropriate.

---

## 7. Preserve Claim Type

The MRI distinguishes:

* Conceptual;
* Descriptive;
* Causal;
* Predictive;
* Normative;
* Legal.

These Claim Types answer different kinds of questions.

For example:

A Legal Claim should not be represented as an empirical finding merely because it appears in the same Domain.

A Normative Claim should not be represented as a factual causal conclusion.

An empirical association should not be rewritten as a legal or moral requirement.

A predictive result should not automatically be treated as an observed long-term outcome.

Where more than one Claim Type is relevant, the distinctions should remain visible.

---

## 8. Selective quotation and downstream interpretation

The MRI may be quoted, discussed, criticized, analyzed, or referenced subject to applicable law and other relevant rights.

When doing so, selectively extracted material should not be presented as the overall conclusion of the MRI where relevant information has been omitted, including:

* Evidence Status;
* Does Not Support;
* Boundary Conditions;
* counterevidence;
* Claim Type;
* Evidence Layer;
* scope limitations.

This applies regardless of whether the downstream context is:

* academic;
* journalistic;
* commercial;
* institutional;
* political;
* advocacy-oriented;
* educational;
* technical.

Citation of the MRI does not imply endorsement by the author of the downstream interpretation, position, product, policy, or argument.

---

## 9. Modified or reconstructed versions

The canonical MRI should not be confused with independently modified, transformed, summarized, reconstructed, or machine-generated versions.

This repository does not grant a separate general permission to redistribute or publicly publish adapted versions of the MRI.

Any such use must rely on applicable law, other independent legal rights, or separate permission from the relevant rights holder.

Private analysis or machine processing may produce transformed representations for technical purposes.

Such representations do not automatically become part of the canonical MRI.

No independently modified or reconstructed version should be presented as:

* official MRI;
* canonical MRI;
* MRI v1.0;
* publication-locked MRI;

unless it actually corresponds to the canonical published version.

---

## 10. Machine processing and AI systems

The MRI was designed in part to explore whether AI systems can retrieve structured research information without losing important evidential boundaries.

AI systems may encounter the MRI through different retrieval paths, including:

* ordinary web search;
* GitHub pages or repository views;
* raw files;
* Markdown mirrors;
* JSON shards;
* connectors;
* plugins;
* other machine retrieval tools.

Retrieval success may differ across systems.

Machine-readable therefore does not mean universally retrievable.

Where technically possible, retrieval systems should preserve a path such as:

Query
→ Primary Domain
→ Core Claim
→ Relevant Non-Equivalence
→ What We Can Say Now
→ What We Cannot Say Yet
→ Boundary Conditions
→ Direct AI-Specific Evidence
→ Does Not Support
→ Source Ledger

rather than returning isolated Claims without qualification.

AI-generated summaries, interpretations, classifications, or answers are not automatically part of the canonical MRI.

---

## 11. Canonical version and retrieval derivatives

For v1.0, the canonical machine-readable publication build is:

Human_AI_Relations_MRI_v1.0_Publication_Build.json

Other files may exist to support retrieval, navigation, validation, or machine access.

These include, for example:

* WEB_ENTRY;
* Domain Markdown mirrors;
* Domain JSON shards;
* Query Route files;
* Claim indexes;
* Source indexes;
* manifests;
* validation records.

These retrieval files are intended to improve access to the canonical structure.

They should not be treated as independent authorities when they conflict with the canonical Publication Build.

The public note articles serve as publication and navigation references.

Line-based provenance locators refer to the canonical preservation files rather than to rendered line positions on a web platform.

---

## 12. Version integrity

The published v1.0 snapshot can be identified through elements such as:

* version number;
* canonical filename;
* manifest records;
* SHA-256 hash;
* evidence cutoff;
* publication status.

“Publication Locked” does not mean that the content has been externally certified, validated, or proven correct.

It means that the published historical snapshot is intended to remain identifiable rather than being silently rewritten.

This distinction is important because the project itself remains experimental.

---

## 13. Source updates

Research evidence, laws, regulations, standards, AI systems, and institutional practices may change after the evidence cutoff.

MRI v1.0 records the state of the audit at:

**Evidence cutoff: 2026-09**

A later change in law, evidence, technology, or research consensus does not retroactively change what v1.0 documented at that time.

For current or high-stakes use, users should verify the latest relevant primary sources.

The MRI should not substitute for current professional, legal, medical, financial, regulatory, or technical verification where such verification is required.

---

## 14. Corrections

MRI v1.0 is experimental and may contain:

* factual errors;
* bibliographic errors;
* outdated legal or regulatory status;
* provenance errors;
* routing errors;
* classification errors;
* structural inconsistencies;
* incomplete coverage.

If an error is discovered, the preferred approach is to document the correction or address it in a later version rather than silently changing the historical meaning of the published snapshot.

The purpose of versioning is to preserve the audit trail, not to imply that a version is error-free.

---

## 15. Interpretation rule

When two interpretations are possible, the MRI generally favors the interpretation that preserves:

* narrower evidential scope;
* explicit uncertainty;
* stated Boundary Conditions;
* original Claim Type;
* Source limitations;
* distinction between direct and adjacent evidence;
* relevant counterevidence;
* relevant “Does Not Support” constraints.

A stronger conclusion should not be inferred merely because it is simpler to communicate.

At the same time, these interpretation rules are themselves part of an experimental retrieval design and may be revised in future versions.

---

## 16. Relationship to original Sources

The MRI does not replace the research papers, laws, regulations, standards, institutional documents, or other external materials from which its records are derived.

Where a substantive proposition depends on an external Source, the original Source remains the primary reference.

MRI Source records are intended to document:

* why the Source was included;
* which Claim or Domain it supports;
* what it does not support;
* where it fits in the retrieval structure.

They should not be treated as substitutes for reading the underlying Source when exact interpretation matters.

Rights in third-party materials remain with their respective rights holders.

---

## 17. Experimental status

MRI v1.0 should be understood as a practical prototype.

It was built after the 13-domain Human–AI Relations Audit Index had already been developed.

As a result, several parts of the retrieval architecture were added later, including:

* Stable IDs;
* Query Routes;
* machine-readable registries;
* Web Retrieval files;
* JSON shards;
* Markdown mirrors.

The current system was therefore not designed from the beginning as a fully integrated publication and retrieval infrastructure.

This is a known limitation.

A future version may redesign the relationship among:

Human-readable publication
→ Stable IDs
→ Query Routes
→ Domain retrieval layers
→ structured data
→ Source provenance

from the beginning rather than extending the existing v1.0 structure.

---

## 18. Responsibility

The author is responsible for the published canonical version as released.

Third-party interpretations, quotations, machine-generated summaries, analyses, applications, and downstream uses are the responsibility of those making them.

Citation or technical use of the MRI does not imply endorsement by the author.

The existence of this integrity guide should not be interpreted as a claim that MRI v1.0 is complete, authoritative, or externally validated.

Its purpose is narrower:

**to make the intended evidential boundaries of this experimental snapshot easier to preserve when the material is read or retrieved.**
