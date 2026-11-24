# QI Data Lab

**Research software for trustworthy, machine-readable quality infrastructure**

[Website](https://qi-data-lab.github.io/) · [GitHub organization](https://github.com/QI-Data-Lab) · [QI-Digital at BAM](https://bam.de/en/topics/digital-materials-research/qi-digital) · [QI-Digital platform](https://www.qi-digital.de/)

## Who we are

QI Data Lab develops and explores digital tools for the **quality infrastructure (QI)** in the context of the Bundesanstalt für Materialforschung und -prüfung (**BAM**) and the German **QI-Digital** initiative.

Quality infrastructure makes measurements, testing, standards, conformity assessment and accreditation reliable. As industrial and regulatory processes become digital, their evidence must be more than a PDF: it should be machine-readable, traceable to its source, interoperable across systems and verifiable by its recipient.

Our focus is on turning those ideas into inspectable research software, data models and demonstrators.

## Research areas

| Area | What we investigate |
| --- | --- |
| **Digital quality documents** | Structured certificates and reference-material documents, validation, semantic data models and machine-actionable results. |
| **Verifiable trust** | Verifiable Credentials and the rules by which a verifier assesses issuer authority, scope, status and supporting evidence. |
| **Interoperability and data ecosystems** | Asset Administration Shells (AAS), federated exchange concepts such as Quality-X, and quality evidence for Digital Product Passports (DPPs). |
| **Evidence-grounded AI** | Extraction from technical documents, provenance-aware retrieval, and review workflows that let people inspect the evidence behind an answer. |

## Public projects

| Project | Purpose | Explore |
| --- | --- | --- |
| **VC4QI — Verifiable Credentials for Quality Infrastructure** | Research framework and browser demonstrator for evaluating reliance on digital quality credentials and trust chains. | [Repository](https://github.com/QI-Data-Lab/VC4QI) · [Demo](https://qi-data-lab.github.io/VC4QI/demo/) |
| **DRMD — Digital Reference Material Document** | XML schema, examples, validation, rendering and authoring tools for machine-readable reference-material information. | [Repository](https://github.com/QI-Data-Lab/drmd) |
| **Evidence Tracer** | Local-first research workbench for exploring PDF corpora, following citations, and finding source-located evidence for and against a query. | [Repository](https://github.com/QI-Data-Lab/Evidence-Tracer) |

These are **research outputs**, not certified production services. Each repository contains its own implementation status, documentation, limitations and license.

## Application context

BAM and the QI-Digital platform develop and demonstrate digital quality tools in application settings such as:

- **Additive manufacturing:** joining process and inspection data with digital evidence of quality.
- **Hydrogen technology and technical assets:** bringing sensor, condition-monitoring and documentation data into traceable evaluation processes.
- **Materials and product passports:** making measured properties, material information and quality evidence available across organizations and product lifecycles.

These settings motivate the work of QI Data Lab; this list does not mean the lab operates every BAM/QI-Digital pilot.

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
