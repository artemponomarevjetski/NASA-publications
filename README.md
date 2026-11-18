# Publications & Scientific Computing

**Artem (Art) Ponomarev, PhD**  
Space radiation · Monte Carlo modeling · Scientific software · Image analysis · Reliability engineering

A research portfolio connecting computational physics, experimental data, and dependable engineering. The collection includes NASA-related radiation research, earlier work in neuroscience and mathematical physics, and later collaborations on electronics and complex-software-system reliability.

**Publication record indexed: 1994–2026.** The expanded catalog contains **33 identified journal articles**, **3 proceedings papers/chapters**, **3 NASA technical reports**, **2 NASA Tech Briefs**, and **1 doctoral dissertation**. Conference abstracts, posters, software disclosures, and unresolved manuscript versions are kept separate. Public-source and CV-derived records are explicitly distinguished.

**[Browse the publication catalog →](PUBLICATIONS.md)**  
[Conference abstracts & presentations](PRESENTATIONS.md) · [Research highlights](#research-highlights) · [Archived PDFs](#archived-pdfs) · [Related software](#related-software) · [Sources & verification](#sources-and-verification)

## Research highlights

| Year | Start here | Focus |
|---|---|---|
| **2026** | [Complex Software Systems: Two Non-Software Reliability Concerns](PUBLICATIONS.md#J01) | Collaboration with Ephraim Suhir, Zoran Stamenkovic, and Eugene Suhir on hardware reliability and human-in-the-loop performance. |
| **2024** | [DNA break clustering as a predictor of cell death](PUBLICATIONS.md#J02) | Radiation quality, cell geometry, and beam orientation in computational cell-death modeling. |
| **2020** | [Chromosome aberrations in mixed fields generated with shielding](PUBLICATIONS.md#J03) | Connecting radiation transport, shielding, and biological measurements. |
| **2019** | [RITCARD](PUBLICATIONS.md#J04) | Chromosome geometry, radiation-induced damage, repair, and aberration scoring in scientific simulation software. |
| **2019** | [Useful lifetime of aerospace electronics: BAZ model](PUBLICATIONS.md#J05) | Work with Ephraim Suhir on incorporating ionizing-radiation exposure into lifetime prediction. |
| **2014** | [Time-dependent chromosome-aberration model](PUBLICATIONS.md#J07) | Repair kinetics in normal and repair-deficient human cells. |
| **2007** | [Image-based modeling of DNA-damage redistribution](PUBLICATIONS.md#J16) | Comparing computational damage patterns with microscopy observations. |
| **2003** | [Adjustable-threshold 3D image segmentation](PUBLICATIONS.md#J23) | Automated identification and localization of objects in biological images. |

## Explore by research area

| Area | Representative records |
|---|---|
| **Radiation transport and shielding** | [Mixed fields](PUBLICATIONS.md#J03), [nanovolume energy deposition](PUBLICATIONS.md#J08), [nuclear interactions](PUBLICATIONS.md#J12), [NASA technical reports](PUBLICATIONS.md#nasa-technical-reports), [GERM](PUBLICATIONS.md#nasa-tech-briefs). |
| **DNA damage, repair, and chromosome aberrations** | [DNA clustering](PUBLICATIONS.md#J02), [RITCARD](PUBLICATIONS.md#J04), [repair kinetics](PUBLICATIONS.md#J07), [aberration yields](PUBLICATIONS.md#J09), [chromatin geometry](PUBLICATIONS.md#J25). |
| **Image analysis and neuroscience** | [DNA-damage imaging](PUBLICATIONS.md#J16), [olfactory memory](PUBLICATIONS.md#J22), [3D segmentation](PUBLICATIONS.md#J23). |
| **Stochastic methods and mathematical physics** | [DNA fragment distributions](PUBLICATIONS.md#J27), [polymer diffusion](PUBLICATIONS.md#J28), [polymer adsorption](PUBLICATIONS.md#J29), [stochastic cluster processes](PUBLICATIONS.md#J31), [plasma physics](PUBLICATIONS.md#J32). |
| **Reliability engineering** | [Complex software systems](PUBLICATIONS.md#J01), [radiation-exposed aerospace electronics](PUBLICATIONS.md#J05). |

Across the radiation-modeling work, the computational chain is:

```text
Particle tracks and energy deposition
                  ↓
Chromatin geometry and DNA-damage distributions
                  ↓
Repair kinetics and chromosome aberrations
                  ↓
Experimental comparison and biological interpretation
```

Each paper defines its own assumptions, implementation, and validation scope. A linked code archive should not be assumed to reproduce every result in the publication catalog.

## Conference and presentation history

[**Open the presentation register →**](PRESENTATIONS.md)

The register includes nine individually described NASA-source/CV-linked conference records, followed by a broader historical presentation register spanning **1997–2019**. Six 2018–2019 abstracts are cross-checked against NASA's Task Book bibliography, including the first-authored poster **Computer visualization of the experimental count of chromosomal aberrations**.

Related presentations are grouped where appropriate; a repeated talk, a poster, and a journal article are not treated as three journal publications. CV date or author-order discrepancies are called out rather than silently converted into confirmed facts.

## Archived PDFs

| File | Document |
|---|---|
| [`RR15250.1.pdf`](RR15250.1.pdf) | **RITCARD: Radiation-Induced Tracks, Chromosome Aberrations, Repair and Damage** — *Radiation Research*, 2019;192(3):282–298. [Full citation](PUBLICATIONS.md#J04). |
| [`EvaluatingBiomarkers2016.pdf`](EvaluatingBiomarkers2016.pdf) | **Evaluating biomarkers to model cancer risk post cosmic ray exposure** — *Life Sciences in Space Research*, 2016;9:19–47. [Full citation](PUBLICATIONS.md#J06). |
| [`PosterHRP_IWS2019_ArtemPonomarev.pdf`](PosterHRP_IWS2019_ArtemPonomarev.pdf) | **Computer visualization of the experimental count of chromosomal aberrations** — NASA HRP Investigators' Workshop, 2019. [Conference record](PRESENTATIONS.md#p01--computer-visualization-of-the-experimental-count-of-chromosomal-aberrations). |

Other publications are linked through their DOI, publisher, PubMed, NASA, or institutional record. An indexed citation does not imply that a full-text PDF is stored here or freely available.

## Related software

[**Space-radiation modeling and chromosome-aberration analysis — C# archive**](https://github.com/artemponomarevjetski/NASA-csharp-reinforcement-learning-for-space-particles)

The companion repository contains legacy scientific-software work associated with chromosome/genome representations, radiation-damage modeling, classification, visualization, and reporting. Its README is the starting point for implementation and historical build context.

**NASARTI, RITCARD, RITRACKS, and GERM are related but distinct software/model names.** The companion repository is not asserted to be the complete source distribution of all four systems. Its historical repository name includes “reinforcement learning”; that name alone is not evidence of a trained reinforcement-learning implementation.

## Sources and verification

The catalog was expanded from author-supplied CVs and publication artifacts, then reconciled with public bibliographic records where available. Private contact details, personal records, email threads, and unpublished manuscript full text have not been uploaded.

Primary discovery and verification sources include [NASA NTRS](https://ntrs.nasa.gov/), the [NASA Task Book report for task 12380](https://taskbook.nasaprs.com/tbp/tbpdf.cfm?id=12380), [NASA Langley's Space Radiation Group bibliography](https://spaceradiation.larc.nasa.gov/journalarticles.html), [PubMed](https://pubmed.ncbi.nlm.nih.gov/), journal publishers, and institutional research pages. Research profiles are discovery aids, not a substitute for checking the actual author list.

### Publication status matters

The published **2026 Suhir collaboration** is cataloged as J01. A related **2026 space-safety manuscript** is recorded separately under [manuscript history](PUBLICATIONS.md#manuscript-history-and-unresolved-records); it is **not counted as a second published paper** without a distinct final citation. Historical 2019 provisional manuscripts and an earlier DNA-clustering manuscript are handled the same way.

Papers by former collaborators that cite these models are **related work**, not automatically my coauthored publications. For example, the bookmarked [bi-exponential-repair poster](https://ntrs.nasa.gov/citations/20200001304) cites RITCARD and Ponomarev–Sachs work but does not list Ponomarev as an author.

### How to cite or suggest a correction

Cite the original paper, report, or abstract using its author list and persistent identifier. For corrections or additions, open an issue or pull request with the title, authors in published order, year, venue, document type, DOI or NASA identifier, and supporting source. CV-derived metadata and version relationships still awaiting reconciliation are marked in the catalog.

This is a **personal research portfolio**, not an official NASA publication service. The catalog is an expanded record, not a certified exhaustive career total. Existing PDFs retain their original notices; linking or indexing a work does not grant redistribution rights or introduce a new license.

---

**Last consolidated: November 17, 2026.**
