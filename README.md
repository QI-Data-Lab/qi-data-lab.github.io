# QI Data Lab

**Three research pillars toward Agentic QI: digital documents and vocabularies, infrastructure, and AI.**

[**Website**](https://qi-data-lab.github.io/) · [**All repositories**](https://github.com/orgs/QI-Data-Lab/repositories) · [**QI-Digital at BAM**](https://bam.de/en/topics/digital-materials-research/qi-digital) · [QI-Digital platform](https://www.qi-digital.de/)

## Who we are

QI Data Lab develops research software, data models and demonstrators for digital **quality infrastructure (QI)** in the context of the **Bundesanstalt für Materialforschung und -prüfung (BAM)** and Germany's **QI-Digital** initiative.

Quality infrastructure connects measurements, testing, standards, conformity assessment and accreditation. We explore how the information behind those activities can move beyond static documents to become **machine-readable, traceable, interoperable and verifiable**. Our long-term goal is **Agentic QI**: software agents able to work with quality evidence across systems while preserving validation, provenance, trust decisions and accountable human oversight.

## Start here: two featured projects

These are direct links to our code and tools. You do not need to visit the website first.

| Project | What it offers | Explore |
| --- | --- | --- |
| **DRMD** — Digital Reference Material Document | XML schema, examples, rendering, validation and editor tooling for structured reference-material information. | [DRMD repository](https://github.com/QI-Data-Lab/DRMD) |
| **VC4QI** — Verifiable Credentials for Quality Infrastructure | Research framework and demonstrator for examining issuer authority, credential status, trust chains and verification decisions. | [VC4QI repository](https://github.com/QI-Data-Lab/VC4QI) · [Live browser demo](https://qi-data-lab.github.io/VC4QI/demo/) |

### Also explore

| Project | What it offers | Explore |
| --- | --- | --- |
| **Evidence Tracer** | Local-first workbench for exploring PDF collections, following references and locating reviewable source evidence. | [Repository](https://github.com/QI-Data-Lab/Evidence-Tracer) |

These are **research prototypes and outputs, not certified production services**. Check each repository for its maturity, documentation, limitations, license and contribution guidance.

## Our research: three pillars, one goal

| Pillar | Focus | Open work and reference points |
| --- | --- | --- |
| **1 · Digital documents & vocabularies** | Machine-readable certificates and reference-material documents, metrology vocabularies, units, semantics, validation and machine-actionable standards. | [DRMD](https://github.com/QI-Data-Lab/DRMD) · [Smart Standards](https://www.qi-digital.de/en/smart-standards) |
| **2 · Infrastructure** | Asset Administration Shells (AAS), digital product and material passports (DPP), federated data spaces such as Quality-X, and verifiable credentials for exchanging and checking evidence. | [VC4QI](https://github.com/QI-Data-Lab/VC4QI) · [Quality-X context](https://netzwerke.bam.de/Netzwerke/Content/EN/Standard-Articles/Networks/QI-Digital/quality-x.html) |
| **3 · AI** | Document understanding, information extraction, evidence-grounded retrieval, source tracing, agent orchestration, schema checks and human review. | [Evidence Tracer](https://github.com/QI-Data-Lab/Evidence-Tracer) |

**Research goal — Agentic QI:** connect these pillars so software agents can discover, interpret, verify and exchange quality evidence across trusted systems. This is a research direction, **not a claim that an autonomous production service has been deployed**.

## Research and publications

Selected public outputs, newest first. We distinguish journal publications, conference papers and conference abstracts.

1. **2026 · Journal article:** Johannes van de Kreeke, Michael Melzer, Mehran Monavari and Silke Richter. *The digital reference material document (DRMD): a new member of the DCC-based family of quality documents.* **Accreditation and Quality Assurance.** [DOI: 10.1007/s00769-026-01730-9](https://doi.org/10.1007/s00769-026-01730-9).
2. **2025 · Conference paper:** Matthias Prellwitz, Claudia Koch, Silke Richter, Johannes van de Kreeke, Michael Melzer and Mehran Monavari. *The Digital Reference Material Document: From Paper Certificates to Interoperable Data Objects in Digital Quality Infrastructure.* **IMEKO TC6 / M4DConf 2025.** [Full paper (PDF)](https://www.imeko.org/publications/tc6-2025/IMEKO-TC6-2025-067.pdf).
3. **2024 · Conference abstract:** Mehran Monavari (presenting author), Matthias Prellwitz and Claudia Koch. *Quality-X MVD: A Minimal Viable Dataspace for Quality Infrastructure.* **4th International DCC Conference proceedings.** [Abstract in proceedings (PDF)](https://oar.ptb.de/files/download/681c53eb53218de84f08e929).

Further reading: [QI-Digital Roadmap (2025)](https://www.qi-digital.de/fileadmin/user_upload/website/Roadmap/QID_Roadmap_V1.0_20251008_en.pdf), a collaborative initiative-wide report.

## Where this work matters

Our research is motivated by quality challenges across several application contexts:

- **Additive manufacturing:** linking process and inspection data with digital evidence of quality.
- **Hydrogen technology and technical assets:** making sensor information, condition monitoring and documentation traceable.
- **Materials and digital product passports:** exchanging measured material properties, technical data and quality evidence across lifecycles.

These are examples from the wider BAM and QI-Digital context; they do not imply that the lab runs every pilot in those areas.

## Explore and contribute

- **Want to try something?** Start with the [VC4QI browser demo](https://qi-data-lab.github.io/VC4QI/demo/) or explore the [DRMD repository](https://github.com/QI-Data-Lab/DRMD).
- **Want to inspect or contribute code?** Read the documentation, issues and contribution guidance in the [individual repositories](https://github.com/orgs/QI-Data-Lab/repositories).
- **Looking for institutional context?** See [QI-Digital at BAM](https://bam.de/en/topics/digital-materials-research/qi-digital) and the [QI-Digital platform](https://www.qi-digital.de/).

---

## About this website repository

This repository contains the source of [qi-data-lab.github.io](https://qi-data-lab.github.io/), the QI Data Lab's public landing page.

| File | Role |
| --- | --- |
| `index.html` | Entire website: semantic HTML, responsive CSS, and a small mobile-navigation script |
| `.nojekyll` | Disables the default Jekyll processing of GitHub Pages |
| `README.md` | Group overview and website maintenance guidance |

The website is **buildless**. It does not require Node.js, a static-site generator, a database, external fonts or client-side tracking.

### Update and publish

The GitHub Pages publishing source is **`main` / `(root)`**. Every push to `main` triggers a new deployment.

```bash
git clone https://github.com/QI-Data-Lab/qi-data-lab.github.io.git
cd qi-data-lab.github.io
# Edit index.html or README.md
git add index.html README.md
git commit -m "Update QI Data Lab site"
git push origin main
```

To review publishing progress, visit **Settings → Pages** in this repository or inspect its Pages build activity. A failed build or stale deployed version should be checked before assuming the live website has updated.

### Design

The site uses a **BAM-inspired palette** of dark blue (`#001F33`), cyan (`#009EE3`) and red (`#D40F14`) for a recognizable research context while retaining an independent QI Data Lab identity. **No BAM logo is used.** The illustrative diagrams are original web elements, not institutional marks.

## Contributing and contact

- For a project-specific issue, use that project's GitHub issue tracker and contribution guidance.
- For a correction to this website, open an issue or propose a pull request in this repository.
- For institutional information and official statements, consult [BAM](https://bam.de/en/topics/digital-materials-research/qi-digital) and the [QI-Digital platform](https://www.qi-digital.de/).

This landing page introduces research work in BAM's QI-Digital context; it is **not a substitute for BAM's official institutional website**.
