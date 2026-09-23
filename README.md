# Executive Digital Governance Self-Assessment

[Latviski](README.lv.md) · **English**

**24-item bilingual self-assessment · global English baseline · Latvian edition**

This project measures governance evidence and decision readiness. It is not an official EDIH/EC assessment, legal opinion, audit or certification.

This repository is a **gap-to-action instrument**, not a quiz that declares a person or organisation “safe” from one overall score.

## Model

`framework → domain → question → response state → gap → recommended action → reassessment`

## Response model

`UNKNOWN → CLAIMED → DOCUMENTED → IMPLEMENTED → VERIFIED`

Unknown areas remain visible. The project intentionally does **not** produce a single overall safety, compliance or maturity score.

Response-state meanings are part of the machine-readable methodology contract in `data/assessment.en.json`; the states are not numerical scores.

`NOT_APPLICABLE` is reserved for genuinely irrelevant items and requires a rationale in structured assessment input.

AI inventory and oversight items use NIST AI RMF support; NIS2 references are scope-qualified.

## Quick start

```bash
python3 scripts/validate.py
python3 scripts/render.py --check
python3 -m unittest discover -s tests -v
python3 scripts/assess.py examples/answers.example.json
```

No assessment answers are transmitted by the repository tooling.

## Structure

- `data/assessment.en.json` — canonical global English assessment;
- `data/assessment.lv.json` — Latvian edition;
- `data/sources.json` — official source registry;
- `docs/` — deterministically generated questionnaires;
- `scripts/assess.py` — local gap/action report generator;
- `scripts/validate.py` and `scripts/render.py` — validation contracts;
- `tests/` — regression tests.

## Sources and adaptation

Assessment items are original project wording informed by registered sources. References indicate alignment or rationale, not official source wording or endorsement.

## Version status

`v0.1.1` is a **pilot baseline** for review and calibration before a stable 1.0 release.

## Author

**Zigmārs Ancveirs** — technology leader, software engineer and independent cybersecurity researcher.

## Licence

Documentation and assessment data: **CC BY 4.0**. Code and automation: **MIT**.
