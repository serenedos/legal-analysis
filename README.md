# legal-analysis

An AI agent skill for rigorous legal reasoning and source-grounded legal analysis.

Version: `0.2.1`  
License: MIT  
Copyright: Sergey Popov

## What it does

`legal-analysis` provides a structured method for:

- separating established facts from legal characterizations and hypotheses;
- identifying the applicable legal regime and decisive decision-point facts;
- working from sources that have actually been obtained and read;
- distinguishing verified sources, legal conclusions, and unverified hypotheses;
- testing conclusions against exceptions, alternative characterizations, and competing interpretations;
- calibrating confidence to the evidentiary basis; and
- stating practical consequences without exceeding the established legal premises.

The method is designed to be independent of a particular jurisdiction or research platform. Infrastructure for Russian legal sources is referenced separately as `legal-analysis-rf-sources`.

## Files

- [`SKILL.md`](SKILL.md) — English version.
- [`SKILL.ru.md`](SKILL.ru.md) — Russian version.
- [`LICENSE`](LICENSE) — MIT License.

## Use

Place `SKILL.md` in the skills directory supported by your AI agent, or use its contents as the skill definition in an agent configuration. The skill describes a reasoning method; it does not replace applicable law, source verification, professional judgment, or jurisdiction-specific research.

## Version

This is the first public release, `0.2.1`. The version remains below `1.0.0` because the methodology may continue to evolve.

