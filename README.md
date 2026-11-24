# QI Data Lab

**Open research tools for trustworthy, machine-readable quality infrastructure.**

[**Website**](https://qi-data-lab.github.io/) · [**All repositories**](https://github.com/orgs/QI-Data-Lab/repositories) · [**QI-Digital at BAM**](https://bam.de/en/topics/digital-materials-research/qi-digital) · [QI-Digital platform](https://www.qi-digital.de/)

## Who we are

QI Data Lab develops research software, data models and demonstrators for digital **quality infrastructure (QI)** in the context of the **Bundesanstalt für Materialforschung und -prüfung (BAM)** and Germany's **QI-Digital** initiative.

Quality infrastructure connects measurements, testing, standards, conformity assessment and accreditation. We explore how the information behind those activities can move beyond static documents to become **machine-readable, traceable, interoperable and verifiable**. The aim is to let quality evidence retain its meaning and trust context as it moves between people, organizations and software systems.

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

## What we investigate

| Research area | Questions and approaches |
| --- | --- |
| **Machine-readable quality documents** | How can certificates, reference-material data, units and uncertainty become structured, validated and reusable? |
| **Verifiable credentials and trust** | How can a verifier inspect issuer authority, scope, status, provenance and supporting evidence? |
| **Interoperability and data ecosystems** | How can quality evidence connect through Asset Administration Shells, concepts such as Quality-X and digital product passports? |
| **Evidence-grounded AI** | How can document extraction, retrieval and AI-assisted review retain inspectable links to their sources? |

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
