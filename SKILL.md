---
name: legal_analysis
description: "Legal analysis with strict source attribution"
version: 0.2.1
author: Sergey Popov
license: MIT
platform: [linux, macos, windows]
metadata:
  hermes:
    tags: [legal, analysis, citations]
    category: research
---

# Purpose / When to Use

Use this skill when analyzing a legal question, interpreting a rule, reviewing case law, or preparing a legal opinion. These are foundational principles of legal reasoning: they apply in any legal system and with any set of tools for finding and reading sources. This is not a repository of legal rules or an instruction manual for a specific platform.

# Core Principle

> Do not try to confirm the first plausible theory. Determine which conclusion withstands testing against the facts, the applicable legal regime, primary sources, and the strongest competing position.

> Never fill the gap between a verified source and a desired conclusion with a plausible synthesis. If a necessary link in the logical chain has not been established, it remains a question or hypothesis rather than becoming a fact.

# Legal Analysis Workflow

Facts → legally significant circumstances → legal characterization → applicable regime → verified sources → competing positions → legal conclusion → degree of confidence → practical consequences.

1. Establish the known facts.
2. Identify unknown decision-point facts (see Facts and Legal Qualification).
3. Determine the applicable legal regime, including general and special rules.
4. Actually obtain and read the decisive sources.
5. Formulate the legal conclusion from the verified sources.
6. Challenge your own conclusion (see Reasoning and Self-Challenge).
7. Calibrate confidence to the evidentiary basis.
8. State the practical consequences.
9. If the facts are insufficient, provide a branching analysis or ask a clarifying question.

# Facts and Legal Qualification

- **The user's characterization is not an established fact.** A question's wording ("this is void," "the party is not entitled") is the user's interpretation and may be wrong. Do not accept it as given.
- **Determine the applicable regime before consequences.** Check what the result depends on: the type of contract or relationship, the parties' status, the purpose of the acquisition, the method of formation or performance, and the existence of special regulation.
- **Decision-point facts may be decisive or secondary.** If the result depends on a circumstance capable of changing the legal regime (the contract term, a party's status, the type of object, or the occurrence of an event), establish it first instead of building a categorical conclusion on an unstated assumption. If a decisive fact is unknown, provide a structured branch—"if X → A; if Y → B"—identify which fact selects the branch, or ask a clarifying question. Do not choose a "main" branch without a factual basis.
- **A secondary unknown fact** (one that refines the analysis but does not change the regime or main conclusion) does not require a mandatory branch or question: provide a useful conditional or preliminary conclusion. Legal analysis is not a questionnaire.
- Respect the dependency on an event occurring: do not anticipate consequences before the event that the applicable rule establishes as a condition.

# Sources and Provenance

- **A source counts as researched** only if it was actually obtained and read. A search result, snippet, heading, summary by another source, or model memory does **not** qualify as having been read.
- **Prefer the most authoritative available primary source.** Verify that the rule is in force and identify the edition applicable at the legally relevant time. Do not present a secondary source as a primary source.
- Keep three categories separate:
  1. **Verified source** — actually read; it is possible to show precisely what it establishes.
  2. **Legal conclusion** — the logical application of verified sources to established facts. This is ordinary professional work. The strength of the conclusion cannot exceed the strength of its logical links.
  3. **Unverified hypothesis** — the remembered content of a rule, an assumed position, an analogy, or an unknown fact. Do not silently use it as an established premise of a conclusion.
- **An anchor quotation** is appropriate when the source directly resolves the question, its content is disputed, the exact wording affects the conclusion, or the model makes a claim about the content of a specific instrument. Check the quotation against the source. Derivative conclusions may refer to already established content without repeating the same quotation. A quotation does not replace an applicability analysis.
- **Verifying an instrument's existence and identifying details** is separate from verifying its content.

# Reasoning and Self-Challenge

Before the final conclusion, ask:

> What is the strongest legal basis capable of making my conclusion wrong or incomplete?

At a minimum, check: a special rule or exception; an alternative characterization; an unknown decision-point fact; a term of the contract or another document; a different time at which a right arises or ends; a competing interpretation; and a contrary judicial position where case law matters.

- Guard against confirmation bias: do not search only for sources that support the first theory.
- **Self-challenge must be proportionate to the question.** It tests the conclusion's resilience; it is not a duty to manufacture doubt. Do not mechanically research case law, exceptions, and alternative constructions for every simple question when a direct verified source resolves it unambiguously and there are no signs of a material competing position.
- If a serious competing position exists, research it or state expressly that it has not been verified and could change the conclusion.
- **Logical chain.** For a key conclusion, reconstruct: fact → characterization → applicable rule/source → legal consequence → conclusion. Do not conceal a missing link with smooth prose. The more intermediate characterizations there are, the more carefully the chain must be checked and the more cautiously confidence should be expressed.

# Interpretation and Competing Positions

If the text permits several reasonable interpretations:
1. Identify the competing interpretations.
2. Test each against the text, context, systemic relationship, and purpose.
3. Account for the legal function of each material element of the text (what each word, number, or condition does).
4. Do not choose a convenient interpretation merely because it supports the initial position.
5. Identify the strongest interpretation and explain why it is stronger.
6. Preserve the alternative if it cannot be reliably excluded.

Do not conceal ambiguity by choosing the convenient interpretation.

# Sufficiency of Research

The depth of research should match the question's complexity, uncertainty, and risk. Do not continue searching merely for completeness once the decisive facts are established, the applicable regime is determined, the key sources are verified, and no material competing position has been found. A simple question with a direct answer in a verified source should receive that answer first, without deliberate complication for the sake of displaying analysis. Additional research is justified if it could change the main conclusion, reveal a material exception, change the applicable regime or practical recommendation, or is necessary because the risk of error is high.

# Calibrated Confidence

The wording used to express confidence must match the evidentiary basis; determine the category by the reason for it, not by formulaic wording.

1. **High confidence** — a direct conclusion from verified sources with sufficiently established facts and no serious competing position.
2. **Working legal conclusion** — a well-supported position, but some elements of applicability or the case law for the specific construction have not been fully researched.
3. **Hypothesis / legal uncertainty** — a material link is unverified, or there is an analogy, competing characterization, competing position, or unknown fact.
4. **Insufficient basis** — a professional conclusion is not yet possible; state exactly what is missing.

- Do not use confidence percentages without an objective methodology. Explain confidence by its reason (whether the source and facts have been verified, and whether a competing position exists).
- Do not add "possibly" mechanically to every conclusion; do not artificially weaken a direct conclusion from a verified rule.
- **Confidence in the text of a rule is not confidence in the outcome of a case.** Accuracy in reading the source, applicability, characterization of facts, and dispute forecasting are different things.
- **A court forecast is not a legal conclusion, and neither is a party's position.** A correct rule does not automatically mean that a case will be won; a strong position does not guarantee a particular court outcome.
- Caution must not become a refusal to take a position: state the best-supported option first, then identify the boundary of confidence and what could change it.

# Practical Legal Outcome

After the legal conclusion, where appropriate, identify: legal consequences; available remedies; necessary actions; material risks; and the facts, documents, or sources capable of changing the recommendation. Do not give a categorical practical recommendation when its necessary legal premises have not been established.

# Supporting References

The infrastructure for Russian sources (codes, APIs, local corpora, and verification of Russian legal instruments) is placed in a separate skill, **`legal-analysis-rf-sources`**. The legal-reasoning rules above apply regardless of which tool is used to find and read sources.

