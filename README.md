# ohdsi-ai-survey
A pre-registered, cross-sectional survey of the OHDSI community examining (1) how the community positions itself on data standardization under foundation-model pressure, and (2) how it perceives OHDSI infrastructure's capacity to mitigate known medical-AI failure modes.

Joint the survey! → [https://docs.google.com/forms/d/e/1FAIpQLSffujd8hZDtpTIoDb3RkFOn3_FsPzMtSdxYwZDFSGWqiigvZQ/viewform?usp=header] 

> **Status:** Pre-data-collection. This repository contains the study
> protocol, instrument, and analysis plan. No data have been collected yet.

---

## Overview

| | |
|---|---|
| **Study type** | Cross-sectional online survey (pre-registered) |
| **Primary question** | Does data standardization still matter in the era of foundation models? How does the OHDSI community position itself — and where is it internally divided? |
| **Secondary question** | Across four medical-AI failure modes within OHDSI's structural scope, which does the community perceive its infrastructure as best positioned to mitigate? |
| **Target sample** | N = 300 (minimum analyzable N = 200) |
| **Population** | Active or recent OHDSI community members |
| **Status** | Protocol & instrument finalized; recruitment not yet started |
| **Pre-registration** | OSF — [link TBD] |
| **Contact** | Jiwon Um (jiwonum126@yuhs.ac), Yonsei University College of Medicine |

---

## Repository structure

```
.
├── protocol/
│   └── OHDSI_AI_Survey_Protocol_v1.0.docx     # Study protocol
├── instrument/
│   └── OHDSI_AI_Survey_Instrument_v1.0.docx   # Survey instrument
├── CHANGELOG.md                               # Version history
└── README.md
```

---

## Versioning

Semantic versioning (`MAJOR.MINOR`):

- **MAJOR** — substantive changes to research questions, hypotheses, or analysis plan (anything affecting pre-registration integrity)
- **MINOR** — wording, formatting, clarification, or instrument trimming that does not alter measured constructs

All changes are logged in [`CHANGELOG.md`](CHANGELOG.md). The version submitted to OSF for pre-registration is tagged as a GitHub Release and treated as the frozen reference.

| Version | Date | Summary |
|---|---|---|
| v1.0 | 2026-05 | Initial public release: protocol, instrument, and analysis plan |

---

## Key design decisions

- **Standardization tension is the primary inquiry.** The study asks whether OMOP-style data standardization remains a trust mechanism or becomes a legacy cost under foundation-model pressure (LLMs processing unstructured notes, multimodal data, schema-flexible learning). Medical-AI failure modes (drawing on Müller et al., 2026) serve as a complementary lens.

- **Descriptive-first analysis.** Response distributions are reported in full to retain shape information. Subgroup comparisons (by AI-integration level, region, role, tenure) use standard non-parametric tests where cell sizes permit (n ≥ 30); we report effect sizes and confidence intervals rather than relying on multiplicity correction.

- **Within-community divergence over aggregate endorsement.** Because the OHDSI community is, by definition, committed to standardization, aggregate pro-standardization results are expected and are not treated as independent evidence for the value of standardization. The analytic focus is on *where the community is divided*.

- **Positioned among prior community surveys.** This study extends prior measurement of clinical-community AI sentiment (e.g., AMA Augmented Intelligence Research) and global expert AI failure-mode assessments (Müller et al., 2026) into a community that has not been similarly examined: the technical builders and maintainers of the data infrastructure underlying medical AI.

- **Selection bias acknowledged by design.** Acknowledged explicitly as the first pre-specified limitation.

---

## How to cite

> Um J, You SC. OHDSI in the Era of Medical AI: A Global Community Survey
> (Study Protocol, v1.0). 2026. [OSF/repo link]

---

## License

- Protocol, instrument, supplementary materials, and documentation: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- Any analysis code (added later): [MIT](https://opensource.org/licenses/MIT)

---

## Acknowledgements

We thank the OHDSI community. This study draws on Müller et al. (2026) for its medical-AI failure-mode taxonomy and on the AMA Augmented Intelligence Research (2024) for the precedent of community-scale AI-sentiment measurement. It builds on community-wide reflections shared in the OHDSI 2025 Year-in-Review by Patrick Ryan.
