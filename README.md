# NASA Publications & Scientific Computing

**Artem (Art) Ponomarev, PhD**  
Space-radiation research · Monte Carlo simulation · DNA-damage modeling · Scientific software

A selected bibliography of my authored and coauthored research on radiation transport, chromosome structure, DNA damage and repair, and the interpretation of experimental measurements. The collection brings together NASA-related work, later coauthored publications, and earlier mathematical foundations developed with academic collaborators.

**This index contains 16 journal publications, two NASA technical briefs, and two conference abstracts.** An archived 2019 workshop poster is listed separately. It is a curated research portfolio, not a claim to be my complete publication record.

[Start here](#start-here) · [Journal publications](#journal-publications) · [Earlier foundations](#earlier-foundations-19992001) · [NASA software briefs](#nasa-software-and-technical-briefs) · [Conference contributions](#conference-contributions) · [Repository files](#files-in-this-repository) · [Related code](#related-code)

## Start here

| Interest | Suggested starting point | What it covers |
|---|---|---|
| Scientific-software architecture | [RITCARD (2019)](#ritcard-2019) | Chromosome geometry, radiation damage, repair, and aberration scoring in a simulation program. |
| Model–experiment comparison | [Mixed radiation fields and shielding (2020)](#mixed-fields-2020) | A multiscale modeling and experimental study of chromosome aberrations behind shielding. |
| Stochastic modeling | [Time-dependent aberration model (2014)](#time-dependent-model-2014) | DNA-repair kinetics and aberration formation in normal and repair-deficient cells. |
| Image analysis | [Image-based modeling (2007)](#image-based-modeling-2007) | Comparing simulated DNA-damage patterns with microscopy observations. |
| Radiation-transport software | [GERM technical brief (2013)](#germ-2013) | Event-based modeling of cosmic-ray and heavy-ion transport and energy deposition. |

## Research themes

The publications connect physical exposure models to biological observations through computational methods:

```text
Particle tracks and radiation transport
                  |
                  v
Chromatin geometry and DNA-damage distributions
                  |
                  v
Repair kinetics and chromosome aberrations
                  |
                  v
Experimental comparison, image analysis, and risk-model inputs
```

The portfolio includes numerical simulation, analytical benchmarking, stochastic background correction, scientific visualization, and collaborative experimental interpretation. Each publication defines its own methods and validation scope; a related software repository should not be assumed to reproduce every result in a paper.

## Journal publications

Entries retain the published author order. **Bold type identifies my name**, not sole authorship. DOI, PubMed, publisher, and institutional links provide the bibliographic sources. Years below follow the cited journal issue where available; an earlier online-publication date may differ.

### 2020–2011: chromosome aberrations, biomarkers, and tissue modeling

<a id="mixed-fields-2020"></a>
**1. Determination of Chromosome Aberrations in Human Fibroblasts Irradiated by Mixed Fields Generated with Shielding**  
Slaba TC, Plante I, **Ponomarev A**, Patel ZS, Hada M.  
*Radiation Research*. **2020**;194(3):246–258.  
[DOI: 10.1667/RR15366.1](https://doi.org/10.1667/RR15366.1) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/32942302/)

<a id="ritcard-2019"></a>
**2. RITCARD: Radiation-Induced Tracks, Chromosome Aberrations, Repair and Damage**  
Plante I, **Ponomarev A**, Patel Z, Slaba T, Hada M.  
*Radiation Research*. **2019**;192(3):282–298.  
[DOI: 10.1667/RR15250.1](https://doi.org/10.1667/RR15250.1) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/31295089/) · [Archived PDF](RR15250.1.pdf)

**3. Evaluating biomarkers to model cancer risk post cosmic ray exposure**  
Sridharan DM, Asaithamby A, Blattnig SR, Costes SV, Doetsch PW, Dynan WS, Hahnfeldt P, Hlatky L, Kidane Y, Kronenberg A, Naidu MD, Peterson LE, Plante I, **Ponomarev AL**, Saha J, Snijders AM, Srinivasan K, Tang J, Werner E, Pluth JM.  
*Life Sciences in Space Research*. **2016**;9:19–47. **Review article.**  
[DOI: 10.1016/j.lssr.2016.05.004](https://doi.org/10.1016/j.lssr.2016.05.004) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/27345199/) · [Institutional record](https://utsouthwestern.elsevierpure.com/en/publications/evaluating-biomarkers-to-model-cancer-risk-post-cosmic-ray-exposu) · [Archived PDF](EvaluatingBiomarkers2016.pdf)

<a id="time-dependent-model-2014"></a>
**4. Generalized Time-Dependent Model of Radiation-Induced Chromosomal Aberrations in Normal and Repair-Deficient Human Cells**  
**Ponomarev AL**, George K, Cucinotta FA.  
*Radiation Research*. **2014**;181(3):284–292.  
[DOI: 10.1667/RR13303.1](https://doi.org/10.1667/RR13303.1) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/24611656/)

**5. Computational Model of Chromosome Aberration Yield Induced by High- and Low-LET Radiation Exposures**  
**Ponomarev AL**, George K, Cucinotta FA.  
*Radiation Research*. **2012**;177(6):727–737.  
[DOI: 10.1667/RR2659.1](https://doi.org/10.1667/RR2659.1) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/22490019/)

**6. A model of the effects of heavy ion radiation on human tissue**  
**Ponomarev AL**, Sundaresan A, Vazquez ME, Guida P, Kim A, Cucinotta FA.  
*Advances in Space Research*. **2011**;47(1):37–48.  
[DOI: 10.1016/j.asr.2010.08.014](https://doi.org/10.1016/j.asr.2010.08.014) · [Institutional record](https://experts.llu.edu/en/publications/a-model-of-the-effects-of-heavy-ion-radiation-on-human-tissue/) · [NASA bibliography](https://taskbook.nasa.gov/tbp/spaceline/current2011/03-04/index.html)

### 2008–2006: spatial damage patterns, image analysis, and statistical correction

**7. Stochastic properties of radiation-induced DSB: DSB distributions in large scale chromatin loops, the HPRT gene and within the visible volumes of DNA repair foci**  
**Ponomarev AL**, Costes SV, Cucinotta FA.  
*International Journal of Radiation Biology*. **2008**;84(11):916–929.  
[DOI: 10.1080/09553000802499212](https://doi.org/10.1080/09553000802499212) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/19016140/)

<a id="image-based-modeling-2007"></a>
**8. Image-Based Modeling Reveals Dynamic Redistribution of DNA Damage into Nuclear Sub-Domains**  
Costes SV, **Ponomarev A**, Chen JL, Nguyen D, Cucinotta FA, Barcellos-Hoff MH.  
*PLoS Computational Biology*. **2007**;3(8):e155.  
[DOI: 10.1371/journal.pcbi.0030155](https://doi.org/10.1371/journal.pcbi.0030155) · [Open full text in PubMed Central](https://pmc.ncbi.nlm.nih.gov/articles/PMC1937017/)

**9. Subtraction of background damage in PFGE experiments on DNA fragment-size distributions**  
**Ponomarev AL**, Belli M, Hahnfeldt PJ, Hlatky L, Sachs RK, Cucinotta FA.  
*Radiation and Environmental Biophysics*. **2007**;46(2):155–160.  
[DOI: 10.1007/s00411-007-0098-z](https://doi.org/10.1007/s00411-007-0098-z) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/17406880/)

**10. A Robust Procedure for Removing Background Damage in Assays of Radiation-Induced DNA Fragment Distributions**  
**Ponomarev AL**, Belli M, Hahnfeldt PJ, Hlatky L, Sachs RK, Cucinotta FA.  
*Radiation Research*. **2006**;166(6):908–916.  
[DOI: 10.1667/RR0663.1](https://doi.org/10.1667/RR0663.1) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/17149980/)

**11. Chromatin loops are responsible for higher counts of small DNA fragments induced by high-LET radiation, while chromosomal domains do not affect the fragment sizes**  
**Ponomarev AL**, Cucinotta FA.  
*International Journal of Radiation Biology*. **2006**;82(4):293–305.  
[DOI: 10.1080/09553000600637716](https://doi.org/10.1080/09553000600637716) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/16690597/)

**12. Nuclear fragmentation and the number of particle tracks in tissue**  
**Ponomarev AL**, Cucinotta FA.  
*Radiation Protection Dosimetry*. **2006**;122(1–4):354–361.  
[DOI: 10.1093/rpd/ncl465](https://doi.org/10.1093/rpd/ncl465) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/17261538/)  
*Date note: the journal issue is dated 2006; PubMed also records electronic publication on January 29, 2007.*

## Earlier foundations, 1999–2001

These papers provide the mathematical and computational background to the later radiation-research models. They are listed separately rather than assigning all work to the same employer or period.

**13. Extrapolation of the DNA Fragment-Size Distribution after High-Dose Irradiation to Predict Effects at Low Doses**  
**Ponomarev AL**, Cucinotta FA, Sachs RK, Brenner DJ, Peterson LE.  
*Radiation Research*. **2001**;156(5 Pt 2):594–597.  
DOI: `10.1667/0033-7587(2001)156[0594:EOTDFS]2.0.CO;2` · [PubMed](https://pubmed.ncbi.nlm.nih.gov/11604078/) · [Columbia bibliography](https://www.crr.columbia.edu/raraf/our-research/raraf-publications)

**14. Radiation breakage of DNA: a model based on random-walk chromatin structure**  
**Ponomarev AL**, Sachs RK.  
*Journal of Mathematical Biology*. **2001**;43(4):356–376.  
[DOI: 10.1007/s002850100098](https://doi.org/10.1007/s002850100098) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/12120873/)

**15. A polymer, random walk model for the size-distribution of large DNA fragments after high linear energy transfer radiation**  
**Ponomarev AL**, Brenner D, Hlatky LR, Sachs RK.  
*Radiation and Environmental Biophysics*. **2000**;39(2):111–120.  
[DOI: 10.1007/s004119900040](https://doi.org/10.1007/s004119900040) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/10929379/)

**16. Polymer chromosome models and Monte Carlo simulations of radiation breaking DNA**  
**Ponomarev AL**, Sachs RK.  
*Bioinformatics*. **1999**;15(12):957–964.  
[DOI: 10.1093/bioinformatics/15.12.957](https://doi.org/10.1093/bioinformatics/15.12.957) · [PubMed](https://pubmed.ncbi.nlm.nih.gov/10745984/) · [UC Berkeley research page](https://math.berkeley.edu/~sachs/sachsresearch/papers9900/ponoab.html)

## NASA software and technical briefs

These are **NASA Tech Briefs**, not additional peer-reviewed journal articles or granted patents. The identifiers below are NASA report/new-technology identifiers.

<a id="germ-2013"></a>
### Galactic Cosmic Ray Event-Based Risk Model (GERM) Code — 2013

Cucinotta FA, Plante I, **Ponomarev AL**, Kim M-HY.  
*NASA Tech Briefs*, May 2013. **MSC-24760-1**.  
[NASA Technical Reports Server record 20130013580](https://ntrs.nasa.gov/citations/20130013580)

The public record describes event-based transport and energy-deposition calculations for cosmic rays and heavy-ion beams, including physical and biophysical outputs for radiation studies.

### GUI to Facilitate Research on Biological Damage from Radiation — 2010

Cucinotta FA, **Ponomarev AL**.  
*NASA Tech Briefs*, January 2010. **MSC-23853-1**.  
[NASA Technical Reports Server record 20100001341](https://ntrs.nasa.gov/citations/20100001341)

A graphical workspace connecting radiation-track calculations, DNA-damage modeling, pattern recognition, and visualization. Consult the source record for the historical implementation environment.

## Conference contributions

The following NASA records are classified as **abstracts**. They are retained separately from journal papers, even when the work is related.

### Simulation of DNA Damage in Human Cells from Space Radiation Using a Physical Model of Stochastic Particle Tracks and Chromosomes — 2015

**Ponomarev A**, Plante I, Hada M, George K, Wu H.  
International Congress of Radiation Research, Kyoto, Japan, May 25–29, 2015. **JSC-CN-32536**.  
[NASA NTRS record 20140017147](https://ntrs.nasa.gov/citations/20140017147)

*Date note: the identifier begins with 2014, but NTRS lists publication in 2015 and the ICRR 2015 meeting. The identifier is not the publication year.*

### A Monte-Carlo Model for the Formation of Radiation-induced Chromosomal Aberrations — 2009

**Ponomarev AL**, Cornforth MN, Loucas BD, Cucinotta FA.  
Radiation Research Society 55th Annual Meeting, October 4–7, 2009. **JSC-18143**.  
[NASA NTRS record 20090015900](https://ntrs.nasa.gov/citations/20090015900)

## Files in this repository

| Existing file | Description |
|---|---|
| [`RR15250.1.pdf`](RR15250.1.pdf) | Archived RITCARD paper; see journal entry 2 for the full citation and authoritative record. |
| [`EvaluatingBiomarkers2016.pdf`](EvaluatingBiomarkers2016.pdf) | Archived biomarkers review; see journal entry 3. |
| [`PosterHRP_IWS2019_ArtemPonomarev.pdf`](PosterHRP_IWS2019_ArtemPonomarev.pdf) | Archived 2019 HRP Investigators' Workshop poster; consult the poster for its full title, authors, and presentation details. |

Most additional works are indexed through DOI or official source links rather than duplicated as PDFs. A citation link does not imply that the full text is freely downloadable or that this repository includes a copy.

## Related code

[**Space-Radiation Modeling and Chromosome-Aberration Analysis — C# archive**](https://github.com/artemponomarevjetski/NASA-csharp-reinforcement-learning-for-space-particles)

The companion repository contains legacy C# source for chromosome/genome representations, radiation-damage calculations, rules-based aberration classification, visualization, and reporting. Its README describes the implementation and historical build requirements. The repository's name includes reinforcement learning, but that name alone does not establish a trained reinforcement-learning implementation.

RITCARD, NASARTI, and GERM are related research/software names, not interchangeable releases. The linked C# snapshot should not be described as the complete source distribution of every code or publication listed here.

## Citation and attribution

Cite the original paper, report, or abstract when discussing a scientific result. Preserve the full author list and use the DOI or NASA record to identify the work precisely. This repository is a personal research index, not an official NASA publication service.

Later work by other researchers may build on these methods, but it should be identified as related work rather than added to my authored-publication list without verified coauthorship. No citation counts or completeness claims are inferred from this selection.

## Corrections and availability

For a missing or corrected entry, open an issue or pull request with the exact title, author list, year, venue, DOI or official record, and document type. Prefer publisher records, PubMed/PMC, NASA NTRS, and institutional bibliographies over unverified profile summaries.

Existing PDFs retain their original notices. New full-text files should be added only when the relevant sharing permissions are established; this README does not grant additional rights to a publisher's work or introduce a new repository license.

*Bibliographic metadata reviewed November 17, 2026. Links and metadata were checked against public records; the review does not imply that every full text or experimental result was independently re-evaluated.*
