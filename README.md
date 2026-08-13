# awesome-vdj with stars

[Antigen] presentation and recognition is central to immunology. [HLA genes] encode the proteins that present antigens. [VDJ genes][vdj] encode the receptors: T cell receptors (TCRs) in T cells and the repertoires of antibodies/immunoglobulins in B cells.

Here, researchers can find links to tools and resources for computational analysis of HLA and VDJ data.

[Contributions are welcome!](https://github.com/slowkow/awesome-vdj/blob/master/CONTRIBUTING.md) ⭐ 243 | 🐛 0 | 📅 2026-02-12

[Antigen]: https://en.wikipedia.org/wiki/Antigen

[vdj]: https://en.wikipedia.org/wiki/V\(D\)J_recombination

[HLA genes]: https://en.wikipedia.org/wiki/Human_leukocyte_antigen

[![CI](https://github.com/slowkow/awesome-vdj/workflows/CI/badge.svg)](https://github.com/slowkow/awesome-vdj/actions) ⭐ 243 | 🐛 0 | 📅 2026-02-12

**Table of Contents**

* [📚 Literature](#literature)
* [🗄️ VDJ Databases](#vdj-databases)
* [🔬 VDJ Analysis](#vdj-analysis)
* [🗃️ HLA Databases](#hla-databases)
* [🧬 HLA Analysis](#hla-analysis)

**Related Work**

* Ming Tang's list: [TCR-BCR-seq-analysis](https://github.com/crazyhottommy/TCR-BCR-seq-analysis) ⭐ 280 | 🐛 0 | 📅 2024-12-01

***

## 📚 Literature

* [**Why must T cells be cross-reactive?**](https://pubmed.ncbi.nlm.nih.gov/22918468/) — This perspective article discusses the immunological necessity of T cell cross-reactivity, explaining why each T cell must be capable of recognizing multiple different peptide-MHC complexes to prov...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/22918468/) · 🪝 [499](https://www.semanticscholar.org/paper/09322c7a1bebd9d48fa41ee1c7b85660b381bec1)

* [**Mechanisms of central tolerance for B cells**](https://pubmed.ncbi.nlm.nih.gov/28368006/) — An in-depth review of the mechanisms by which developing B cells are tolerized to self-antigens in the bone marrow, including receptor editing, clonal deletion, and anergy, and how failures in thes...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/28368006/) · 🪝 [418](https://www.semanticscholar.org/paper/8942bac84eab2aaf30a15c28f68c40af880e0477)

* [**Understanding the drivers of MHC restriction of T cell receptors**](https://pubmed.ncbi.nlm.nih.gov/29636542/) — A comprehensive review examining how T cell receptors (TCRs) are restricted to recognizing peptide antigens presented by major histocompatibility complex (MHC) molecules, exploring the evolutionary...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/29636542/) · 🪝 [254](https://www.semanticscholar.org/paper/b3b63f41169bef73eb8d34b911526d4f88d93752)

* [**High-Throughput and Single-Cell T Cell Receptor Sequencing Technologies**](https://doi.org/10.1038/s41592-021-01201-8) — A comprehensive review of current technologies for T cell receptor sequencing, covering both bulk and single-cell approaches, their applications in immunology research, and future directions in the...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/34282327/) · 🪝 [208](https://www.semanticscholar.org/paper/471eba65c98c464da909d699c05a3998033e204f)

* [**Mining adaptive immune receptor repertoires for biological and clinical information using machine learning**](http://dx.doi.org/10.1016/j.coisb.2020.10.010) — A review of machine learning approaches for analyzing adaptive immune receptor repertoire data, discussing how these methods can extract biological insights and clinical information from large-scal...<br>[Paper](http://dx.doi.org/10.1016/j.coisb.2020.10.010) · 🪝 [72](https://www.semanticscholar.org/paper/b1606c027b9224972cbb4d25a6c36cb03f573099)

* [**HLA and kidney disease: from associations to mechanisms**](https://pubmed.ncbi.nlm.nih.gov/30206339/) — This review explores the associations between HLA genes and kidney diseases, discussing how advances in understanding HLA biology are revealing the mechanisms underlying these genetic associations ...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/30206339/) · 🪝 [69](https://www.semanticscholar.org/paper/8a6ca498d44b884d163b3de4a6c3466658840c4a)

* [**SweHLA: the high confidence HLA typing bio-resource drawn from 1000 Swedish genomes**](https://www.nature.com/articles/s41431-019-0559-2) — This paper presents SweHLA, a high-confidence HLA typing resource derived from whole-genome sequencing of 1000 Swedish individuals, providing a valuable reference for HLA research and clinical appl...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/31844174/) · 🪝 [16](https://www.semanticscholar.org/paper/d8bc4828bd344a35e19221e1001d01dc156f1e1d)

***

## 🗄️ VDJ Databases

### Structure Databases

* [**STCRDab: The Structural T-Cell Receptor Database**](http://opig.stats.ox.ac.uk/webapps/stcrdab/) — An automated, curated set of T-Cell Receptor structural data from the PDB.<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/29087479/) · 🪝 [102](https://www.semanticscholar.org/paper/c64329d5e91e3d2fd4d2cc564a09ae1b5301f57c) · [Homepage](http://opig.stats.ox.ac.uk/webapps/stcrdab/)

* [**TCR3d: T cell receptor structural repertoire database**](https://tcr3d.ibbr.umd.edu/) — Welcome to the T cell receptor (TCR) structural repertoire database. Here we provide an easy-to-use interface to view all experimentally determined T cell receptor structures and their complexes. T...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/32124321/) · 🪝 [3](https://www.semanticscholar.org/paper/8e0ccc15dd5550c762e62da5f8e3c04449f87d8f) · [Homepage](https://tcr3d.ibbr.umd.edu/)

* [**Coronavirus-Binding Antibody Sequences & Structures**](http://opig.stats.ox.ac.uk/webapps/covabdab/) — The Oxford Protein Informatics Group (Dept. of Statistics, University of Oxford) is collaborating in efforts to understand the immune response to SARS-CoV2 infection and vaccination. As part of our...<br>[Homepage](http://opig.stats.ox.ac.uk/webapps/covabdab/)

### Specificity Databases

* [**VDJDB: A curated database of T-cell receptor sequences of known antigen specificity**](https://github.com/antigenomics/vdjdb-db) ⭐ 155 | 🐛 124 | 🌐 Python | 📅 2026-06-11 — The primary goal of VDJdb is to facilitate access to existing information on T-cell receptor antigen specificities, i.e. the ability to recognize certain epitopes in certain MHC contexts. > Our mis...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/28977646/) · 🪝 [491](https://www.semanticscholar.org/paper/cfd86d8ddd03ccacd18343d091ac93745e4187d6) · ⭐ [149](https://github.com/antigenomics/vdjdb-db/stargazers) ⭐ 155 | 🐛 124 | 🌐 Python | 📅 2026-06-11 · [Homepage](https://vdjdb.cdr3.net)

* [**vdjmatch**](https://github.com/antigenomics/vdjmatch) ⭐ 39 | 🐛 7 | 🌐 Python | 📅 2026-07-30 — Matching T-cell repertoire against a database of TCR antigen specificities<br>⭐ [39](https://github.com/antigenomics/vdjmatch/stargazers) ⭐ 39 | 🐛 7 | 🌐 Python | 📅 2026-07-30 · [Homepage](https://vdjdb.cdr3.net) · `Groovy`

* [**McPAS-TCR: A manually curated catalogue of pathology associated T-cell receptor sequences**](https://friedmanlab.weizmann.ac.il/McPAS-TCR/) — McPAS-TCR is a manually curated catalogue of T cell receptor (TCR) sequences that were found in T cells associated with various pathological conditions in humans and in mice. It is meant to link TC...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/28481982/) · 🪝 [449](https://www.semanticscholar.org/paper/af8ef665e0cd44a7cf69b811626519a3fcf323b4) · [Homepage](https://friedmanlab.weizmann.ac.il/McPAS-TCR/)

### Sequence Repositories

* [**iReceptor**](https://gateway.ireceptor.org/home) — iReceptor facilitates the curation, analysis and sharing of antibody/B-cell and T-cell receptor repertoires (Adaptive Immune Receptor Repertoire or AIRR-seq data) from multiple labs and institution...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/29944754/) · 🪝 [133](https://www.semanticscholar.org/paper/5d764e3cb11d09a8f2ec8bdce3b390d6e42d3f8a) · [Homepage](https://gateway.ireceptor.org/home)

* [**A Public Database of Memory and Naive B-Cell Receptor Sequences**](https://datadryad.org/stash/dataset/doi:10.5061/dryad.35ks2) — We present a public database of more than 37 million unique BCR sequences from three healthy adult donors that is many fold deeper than any existing resource, together with a set of online tools de...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/27513338/) · 🪝 [104](https://www.semanticscholar.org/paper/0296d2dce034afee35366908584f9daa81ea7319) · [Homepage](https://datadryad.org/stash/dataset/doi:10.5061/dryad.35ks2)

* [**immuneACCESS**](https://clients.adaptivebiotech.com/immuneaccess) — Dive into the world’s largest collection of TCR and BCR sequences. Easily incorporate millions of sequences worth of public data into your next papers and projects using immunoSEQ Analyzer. Constru...<br>[Docs](https://github.com/slowkow/awesome-vdj/blob/master/download-from-immuneaccess.md) ⭐ 243 | 🐛 0 | 📅 2026-02-12 · [Homepage](https://clients.adaptivebiotech.com/immuneaccess)

* [**PIRD: Pan immune repertoire database**](https://db.cngb.org/pird/) — Pan immune repertoire database (PIRD) collects raw and processed sequences of immunoglobulins (IGs) and T cell receptors (TCRs) of human and other vertebrate species with different phenotypes. You ...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/31373607/) · [Homepage](https://db.cngb.org/pird/)

### Standards & Resources

* [**Adaptive Immune Receptor Repertoire (AIRR) Community**](https://github.com/airr-community) — The Adaptive Immune Receptor Repertoire (AIRR) Community of The Antibody Society is a research-driven group that is organizing and coordinating stakeholders in the use of next-generation sequencing...<br>[Docs](https://docs.airr-community.org/en/stable/index.html) · [Homepage](http://airr-community.org)

* [**Human Vaccines Project (Human Immunome Program)**](https://trace.ncbi.nlm.nih.gov/Traces/sra/?study=SRP174305) — The Human Immunome Program (HIP) is open-source effort with the goal sequencing all of the adaptive receptors on the surface of human B and T cells. Under a targeted 7-to-10-year effort, the progra...<br>[Homepage](https://trace.ncbi.nlm.nih.gov/Traces/sra/?study=SRP174305)

***

## 🔬 VDJ Analysis

### Single-Cell

* [**scRepertoire: A toolkit for single-cell immune profiling**](https://github.com/BorchLab/scRepertoire) ⭐ 374 | 🐛 1 | 🌐 R | 📅 2026-07-09 — R package for analyzing and visualizing single-cell immune receptor data. This new version introduces an array of features designed to enhance both the depth and breadth of immune receptor analysis...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/40577285/) · 🪝 [9](https://www.semanticscholar.org/paper/1a0dc99021ccfd16d1d3a19f75068de450bc25f6) · ⭐ [358](https://github.com/BorchLab/scRepertoire/stargazers) ⭐ 374 | 🐛 1 | 🌐 R | 📅 2026-07-09 · `R`

* [**TRUST4: TCR and BCR assembly from RNA-seq data**](https://github.com/liulab-dfci/TRUST4) ⭐ 360 | 🐛 125 | 🌐 C | 📅 2026-08-03 — Tcr Receptor Utilities for Solid Tissue (TRUST) is a computational tool to analyze TCR and BCR sequences using unselected RNA sequencing data, profiled from solid tissues, including tumors. TRUST4 ...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/33986545/) · 🪝 [227](https://www.semanticscholar.org/paper/7564c0e07f7135c0ec2eddb4009e6a51febdc991) · ⭐ [337](https://github.com/liulab-dfci/TRUST4/stargazers) ⭐ 360 | 🐛 125 | 🌐 C | 📅 2026-08-03 · `C` `C++` `Perl`

* [**Scirpy: a Scanpy extension for analyzing single-cell T-cell receptor-sequencing data**](https://github.com/scverse/scirpy) ⭐ 264 | 🐛 49 | 🌐 Python | 📅 2026-08-10 — A scalable Python toolkit that provides simplified access to the analysis and visualization of immune repertoires from single cells and seamless integration with transcriptomic data.<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/32614448/) · 🪝 [212](https://www.semanticscholar.org/paper/fcd27b7bd7ba5b02c64910cf80c2b5b7fabd12e4) · ⭐ [243](https://github.com/scverse/scirpy/stargazers) ⭐ 264 | 🐛 49 | 🌐 Python | 📅 2026-08-10 · [Homepage](https://scirpy.scverse.org/en/latest/) · `Python`

* [**STARTRAC**](https://github.com/Japrin/STARTRAC) ⭐ 124 | 🐛 10 | 🌐 HTML | 📅 2025-04-26 — STARTRAC(Single T-cell Analysis by Rna-seq and Tcr TRACking)<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/33900375/) · 🪝 [27](https://www.semanticscholar.org/paper/11c92257f87b515bc46af2b874ff14890120fadd) · ⭐ [114](https://github.com/Japrin/STARTRAC/stargazers) ⭐ 124 | 🐛 10 | 🌐 HTML | 📅 2025-04-26 · `HTML`

* [**DeepTCR: Deep Learning Methods for Parsing T-Cell Receptor Sequencing (TCRSeq) Data**](https://github.com/sidhomj/DeepTCR) ⭐ 122 | 🐛 15 | 🌐 Jupyter Notebook | 📅 2025-09-16 — DeepTCR is a python package that has a collection of unsupervised and supervised deep learning methods to parse TCRSeq data. It has the added functionality of being able to analyze paired alpha/bet...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/33707415/) · 🪝 [217](https://www.semanticscholar.org/paper/a1a242bdb47b7fe9e8d519aacb41157bb78842fb) · ⭐ [123](https://github.com/sidhomj/DeepTCR/stargazers) ⭐ 122 | 🐛 15 | 🌐 Jupyter Notebook | 📅 2025-09-16 · `Python`

* [**CONGA: Clonotype Neighbor Graph Analysis**](https://github.com/phbradley/conga) ⭐ 100 | 🐛 28 | 🌐 Jupyter Notebook | 📅 2026-06-15 — CONGA was developed to detect correlation between T cell gene expression profile and TCR sequence in single-cell datasets.<br>[Paper](https://doi.org/10.1101/2020.06.04.134536) · 🪝 [9](https://www.semanticscholar.org/paper/d0a9125325f851f69dbc486e2b2e75f9ba63d4f5) · ⭐ [93](https://github.com/phbradley/conga/stargazers) ⭐ 100 | 🐛 28 | 🌐 Jupyter Notebook | 📅 2026-06-15 · `Python`

* [**airrflow**](https://github.com/nf-core/airrflow) ⭐ 78 | 🐛 48 | 🌐 Nextflow | 📅 2026-07-30 — B-cell and T-cell Adaptive Immune Receptor Repertoire (AIRR) sequencing analysis pipeline using the Immcantation framework<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/38293151/) · 🪝 [10](https://www.semanticscholar.org/paper/https://www.semanticscholar.org/paper/04c2e0be97ba6d6035506595694eb22e2093037b) · ⭐ [73](https://github.com/nf-core/airrflow/stargazers) ⭐ 78 | 🐛 48 | 🌐 Nextflow | 📅 2026-07-30 · [Homepage](https://nf-co.re/airrflow) · `Nextflow`

* [**mvTCR**](https://github.com/SchubertLab/mvTCR) ⭐ 59 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2024-11-01 — A multi-view Variational Autoencoder (mvTCR) to jointly embed transcriptomic and TCR sequence information at a single-cell level to better capture the phenotypic behavior of T cells.<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/38956082/) · 🪝 [17](https://www.semanticscholar.org/paper/62559a2f08e304d5a6149f4605e45529ac2c150e) · ⭐ [56](https://github.com/SchubertLab/mvTCR/stargazers) ⭐ 59 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2024-11-01 · [Homepage](https://zenodo.org/record/5006839) · `Python`

* [**enclone**](https://github.com/10XGenomics/enclone) ⭐ 50 | 🐛 4 | 🌐 Rust | 📅 2025-03-07 — enclone is standalone software (primarily written in Rust) developed by 10x Genomics for analysis of single cell TCR and BCR sequences. enclone performs SHM-aware clonotyping, phylogenetic/lineage ...<br>⭐ [50](https://github.com/10XGenomics/enclone/stargazers) ⭐ 50 | 🐛 4 | 🌐 Rust | 📅 2025-03-07 · [Homepage](https://10xgenomics.github.io/enclone/) · `Rust`

* [**covid19**](https://github.com/immunomind/covid19) ⭐ 46 | 🐛 1 | 📅 2020-05-21 — Regularly updated list of publicly available datasets with single-cell (scRNAseq) and T-cell/antibody immune repertoire (AIRR / RepSeq / immunosequencing) data of COVID-19 patients with SARS-CoV-2.<br>⭐ [46](https://github.com/immunomind/covid19/stargazers) ⭐ 46 | 🐛 1 | 📅 2020-05-21

* [**Platypus**](https://github.com/alexyermanos/Platypus) ⭐ 45 | 🐛 21 | 🌐 R | 📅 2025-02-07 — R package for the analysis of single-cell immune repertoires<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/33884369/) · 🪝 [40](https://www.semanticscholar.org/paper/309e51a1d8ff5c00c98dc3ea8e102292a30dfba7) · ⭐ [43](https://github.com/alexyermanos/Platypus/stargazers) ⭐ 45 | 🐛 21 | 🌐 R | 📅 2025-02-07 · `R`

* [**TCRGP**](https://github.com/emmijokinen/TCRGP) ⭐ 30 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2023-01-31 — TCRGP is a novel Gaussian process method that can predict if TCRs recognize certain epitopes. This method can utilize different CDR sequences from both TCRα and TCRβ chains from single-cell data an...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/33764977/) · 🪝 [109](https://www.semanticscholar.org/paper/ee044c6c9cbe0cbf79bfcc41d1e4c5c601d25ed1) · ⭐ [30](https://github.com/emmijokinen/TCRGP/stargazers) ⭐ 30 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2023-01-31 · `Python`

* [**TCRconvert**](https://github.com/seshadrilab/tcrconvert) ⭐ 15 | 🐛 6 | 🌐 Python | 📅 2025-12-26 — TCRconvert converts T cell receptor (TCR) gene names between the 10X, Adaptive, and IMGT naming conventions. It supports alpha-beta and gamma-delta TCRs for human, mouse, and rhesus macaque.<br>⭐ [15](https://github.com/seshadrilab/tcrconvert/stargazers) ⭐ 15 | 🐛 6 | 🌐 Python | 📅 2025-12-26 · `Python`

* [**TCRconvertR**](https://github.com/seshadrilab/tcrconvertr) ⭐ 6 | 🐛 6 | 🌐 R | 📅 2026-05-28 — TCRconvertR converts T cell receptor (TCR) gene names between the 10X, Adaptive, and IMGT naming conventions. It supports alpha-beta and gamma-delta TCRs for human, mouse, and rhesus macaque.<br>⭐ [6](https://github.com/seshadrilab/tcrconvertr/stargazers) ⭐ 6 | 🐛 6 | 🌐 R | 📅 2026-05-28 · `R`

* [**dandelion**](https://github.com/zktuong/dandelion) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-03-02 — dandelion - A single cell BCR/TCR V(D)J-seq analysis package for 10X Chromium 5' data<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/37055623/) · 🪝 [44](https://www.semanticscholar.org/paper/a3773c9b4d58198f7195df8f54a8c58ca892abce) · ⭐ [122](https://github.com/zktuong/dandelion/stargazers) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-03-02 · [Homepage](https://sc-dandelion.readthedocs.io/) · `Python`

### Repertoire Analysis

* [**immunarch: An R Package for Painless Bioinformatics Analysis of T-cell and B-cell Immune Repertoire Data**](https://github.com/immunomind/immunarch) ⭐ 341 | 🐛 13 | 🌐 R | 📅 2026-08-12 — immunarch is an R package designed to analyse T-cell receptor (TCR) and B-cell receptor (BCR) repertoires, aimed at medical scientists and bioinformaticians. The mission of immunarch is to make imm...<br>⭐ [334](https://github.com/immunomind/immunarch/stargazers) ⭐ 341 | 🐛 13 | 🌐 R | 📅 2026-08-12 · `R`

* [**msm: Max Snippet Model**](https://github.com/jostmey/msm) ⭐ 177 | 🐛 0 | 🌐 Python | 📅 2023-05-01 — Improved statistical classifier for immune repertoires<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/33868241/) · 🪝 [8](https://www.semanticscholar.org/paper/77b6920d6e016f551c73c7d6eb5ac385128772f5) · ⭐ [177](https://github.com/jostmey/msm/stargazers) ⭐ 177 | 🐛 0 | 🌐 Python | 📅 2023-05-01 · `Python`

* [**VDJtools**](https://github.com/mikessh/vdjtools) ⭐ 145 | 🐛 0 | 🌐 Python | 📅 2026-08-13 — A comprehensive analysis framework for T-cell and B-cell repertoire sequencing data<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/26606115/) · 🪝 [529](https://www.semanticscholar.org/paper/c5994d9f6ed808f510cb95a3225c9f8ab0d6b460) · ⭐ [142](https://github.com/mikessh/vdjtools/stargazers) ⭐ 145 | 🐛 0 | 🌐 Python | 📅 2026-08-13 · `Java` `Groovy`

* [**DeepRC**](https://github.com/ml-jku/DeepRC) ⭐ 128 | 🐛 4 | 🌐 Python | 📅 2023-09-12 — DeepRC: Immune repertoire classification with attention-based deep massive multiple instance learning<br>⭐ [124](https://github.com/ml-jku/DeepRC/stargazers) ⭐ 128 | 🐛 4 | 🌐 Python | 📅 2023-09-12 · `Python`

* [**dkm: Dynamic Kernel Matching**](https://github.com/jostmey/dkm) ⭐ 94 | 🐛 0 | 🌐 HTML | 📅 2023-05-16 — DKM is analogous to a convolutional network, but for sequences. Consider the problem of classifying a sequence. Because some sequences are longer than others, the number of features is irregular. G...<br>⭐ [94](https://github.com/jostmey/dkm/stargazers) ⭐ 94 | 🐛 0 | 🌐 HTML | 📅 2023-05-16 · `Python`

* [**immuneML**](https://github.com/uio-bmi/immuneML) ⭐ 76 | 🐛 1 | 🌐 Python | 📅 2026-08-07 — immuneML is a platform for machine learning analysis of adaptive immune receptor repertoire data.<br>⭐ [73](https://github.com/uio-bmi/immuneML/stargazers) ⭐ 76 | 🐛 1 | 🌐 Python | 📅 2026-08-07 · [Homepage](https://immuneml.uio.no) · `Python`

* [**abstar**](https://github.com/brineylab/abstar) ⭐ 44 | 🐛 6 | 🌐 Pkl | 📅 2026-03-30 — VDJ assignment and antibody sequence annotation. Scalable from a single sequence to billions of sequences.<br>⭐ [44](https://github.com/brineylab/abstar/stargazers) ⭐ 44 | 🐛 6 | 🌐 Pkl | 📅 2026-03-30 · `Pkl`

* [**vdjer**](https://github.com/mozack/vdjer) ⭐ 29 | 🐛 8 | 🌐 C | 📅 2022-08-09 — V'DJer -  B Cell Receptor Repertoire Reconstruction from short read mRNA-Seq data<br>⭐ [29](https://github.com/mozack/vdjer/stargazers) ⭐ 29 | 🐛 8 | 🌐 C | 📅 2022-08-09 · `C`

* [**CATT**](https://github.com/GuoBioinfoLab/CATT) ⭐ 21 | 🐛 16 | 🌐 Julia | 📅 2025-11-19 — An ultra-sensitive and precise tool for characterizing T cell CDR3 sequences in TCR-seq and RNA-seq data.<br>⭐ [21](https://github.com/GuoBioinfoLab/CATT/stargazers) ⭐ 21 | 🐛 16 | 🌐 Julia | 📅 2025-11-19 · `Julia`

* [**epitopefindr**](https://github.com/brandonsie/epitopefindr) ⭐ 17 | 🐛 0 | 🌐 R | 📅 2025-08-26 — R package to BLAST peptide sequences against each other and identify the minimal overlap of aligning regions.<br>⭐ [16](https://github.com/brandonsie/epitopefindr/stargazers) ⭐ 17 | 🐛 0 | 🌐 R | 📅 2025-08-26 · [Homepage](https://brandonsie.github.io/epitopefindr/) · `R`

* [**Recon: Reconstruction of Estimated Communities from Observed Numbers**](https://github.com/ArnaoutLab/Recon) ⭐ 14 | 🐛 8 | 🌐 Python | 📅 2025-12-16 — Recon uses the distribution of species counts in a sample to estimate the distribution of species counts in the population from which the sample was drawn.<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/27302887/) · 🪝 [91](https://www.semanticscholar.org/paper/42674800f3ce4fc5230fbb08afd3cbfb72a47e02) · ⭐ [14](https://github.com/ArnaoutLab/Recon/stargazers) ⭐ 14 | 🐛 8 | 🌐 Python | 📅 2025-12-16 · `Python` `R`

### Sequence Processing

* [**MiXCR: a universal tool for fast and accurate analysis of T- and B- cell receptor repertoire sequencing data**](https://github.com/milaboratory/mixcr) ⭐ 399 | 🐛 126 | 🌐 Kotlin | 📅 2026-07-10 — MiXCR is a universal framework that processes big immunome data from raw sequences to quantitated clonotypes. MiXCR efficiently handles paired- and single-end reads, considers sequence quality, cor...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/39433438/) · 🪝 [4](https://www.semanticscholar.org/paper/0eaa429866419cf0a165ccae340447d6f2a4c925) · ⭐ [380](https://github.com/milaboratory/mixcr/stargazers) ⭐ 399 | 🐛 126 | 🌐 Kotlin | 📅 2026-07-10 · `Java`

* [**stitchr**](https://github.com/JamieHeather/stitchr) ⭐ 69 | 🐛 4 | 🌐 Python | 📅 2026-03-12 — Stitchr - a Python script to stitch together coding TCR nucleotide sequences from V, J, and CDR3 info<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/35325179/) · 🪝 [22](https://www.semanticscholar.org/paper/aeaf4f3d97ca02f2b25cf040d6ad39a62db41a1e) · ⭐ [64](https://github.com/JamieHeather/stitchr/stargazers) ⭐ 69 | 🐛 4 | 🌐 Python | 📅 2026-03-12 · [Homepage](https://jamieheather.github.io/stitchr/) · `Python`

* [**MiGMAP: mapper for full-length T- and B-cell repertoire sequencing**](https://github.com/mikessh/migmap) ⭐ 56 | 🐛 1 | 🌐 Python | 📅 2026-08-12 — In a nutshell, this software is a smart wrapper for IgBlast V-(D)-J mapping tool designed to facilitate analysis immune receptor libraries profiled using high-throughput sequencing. This package in...<br>⭐ [53](https://github.com/mikessh/migmap/stargazers) ⭐ 56 | 🐛 1 | 🌐 Python | 📅 2026-08-12 · `Java` `Groovy`

* [**pyIR: An IgBLAST wrapper and parser**](https://github.com/crowelab/PyIR) ⭐ 52 | 🐛 5 | 🌐 Python | 📅 2026-01-09 — PyIR is a minimally-dependent high-speed wrapper for the IgBLAST immunoglobulin and T-cell analyzer. This is achieved through chunking the input data set and running IgBLAST single-core in parallel...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/32677886/) · 🪝 [29](https://www.semanticscholar.org/paper/4c463450d5f5f6d9e1c1f5a21b3b33cbd4ed141c) · ⭐ [50](https://github.com/crowelab/PyIR/stargazers) ⭐ 52 | 🐛 5 | 🌐 Python | 📅 2026-01-09 · `Python`

* [**vidjil**](https://github.com/vidjil/vidjil) ⭐ 32 | 🐛 3 | 🌐 JavaScript | 📅 2026-06-29 — Vidjil -- High-throughput Analysis of V(D)J Immune Repertoire (mirror, please go to <http://gitlab.vidjil.org>)<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/27835690/) · 🪝 [81](https://www.semanticscholar.org/paper/03f774017c20e5297317851016bb37be66c35291) · ⭐ [31](https://github.com/vidjil/vidjil/stargazers) ⭐ 32 | 🐛 3 | 🌐 JavaScript | 📅 2026-06-29 · [Homepage](http://gitlab.vidjil.org) · `JavaScript`

* [**vdjviz**](https://github.com/antigenomics/vdjviz) ⭐ 28 | 🐛 12 | 🌐 JavaScript | 📅 2019-12-10 — A lightweight immune repertoire browser<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/27297497/) · 🪝 [33](https://www.semanticscholar.org/paper/f7da52e1bc9aabf2f08b78dd976bb7c39f2388c6) · ⭐ [27](https://github.com/antigenomics/vdjviz/stargazers) ⭐ 28 | 🐛 12 | 🌐 JavaScript | 📅 2019-12-10 · [Homepage](https://vdjviz.cdr3.net) · `JavaScript`

* [**BepiPred-3.0**](https://github.com/UberClifford/BepiPred-3.0) ⭐ 25 | 🐛 1 | 🌐 HTML | 📅 2026-01-02 — BepiPred3.0 predicts B-cell epitopes from proteins sequences in fasta format.<br>⭐ [17](https://github.com/UberClifford/BepiPred-3.0/stargazers) ⭐ 25 | 🐛 1 | 🌐 HTML | 📅 2026-01-02 · `HTML`

* [**IMSEQ: IMmunogenetic SEQuence Analysis**](https://github.com/lkuchenb/imseq) ⭐ 15 | 🐛 2 | 🌐 C++ | 📅 2018-08-10 — IMSEQ is a fast, PCR and sequencing error aware tool to analyze high throughput data from recombined T-cell receptor or immunoglobolin gene sequencing experiments. It derives immune repertoires fro...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/25987567/) · 🪝 [98](https://www.semanticscholar.org/paper/0b738ce3da3d79cefd8c1460687878f60bd05183) · ⭐ [15](https://github.com/lkuchenb/imseq/stargazers) ⭐ 15 | 🐛 2 | 🌐 C++ | 📅 2018-08-10

* [**PRESTO: The REpertoire Sequencing TOolkit**](https://github.com/immcantation/presto) ⭐ 0 | 🐛 10 | 🌐 Python | 📅 2026-04-14 — pRESTO is a toolkit for processing raw reads from high-throughput sequencing of B cell and T cell repertoires. > The REpertoire Sequencing TOolkit (pRESTO) is composed of a suite of utilities to ha...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/24618469/) · 🪝 [424](https://www.semanticscholar.org/paper/ca321103129928fcc5522d2a314fdd167bf8805e) · [Docs](https://presto.readthedocs.io/en/stable) · `Python`

### Clustering & Similarity

* [**tcr-dist**](https://github.com/phbradley/tcr-dist) ⭐ 87 | 🐛 17 | 🌐 Python | 📅 2021-10-06 — Software tools for the analysis of epitope-specific T cell receptor (TCR) repertoires<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/28636592/) · 🪝 [815](https://www.semanticscholar.org/paper/b3e8d6f21fbdcd58888af31e791b5a8d24a1c592) · ⭐ [86](https://github.com/phbradley/tcr-dist/stargazers) ⭐ 87 | 🐛 17 | 🌐 Python | 📅 2021-10-06 · `Python`

* [**GIANA: Geometry Isometry based TCR AligNment Algorithm**](https://github.com/s175573/GIANA) ⭐ 76 | 🐛 20 | 🌐 HTML | 📅 2024-10-16 — Geometric Isometry- based TCR AligNment Algorithm (GIANA), a mathematical framework to transform the CDR3 sequences, which converted the sequence alignment and clustering problem into a classic nea...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/34349111/) · 🪝 [102](https://www.semanticscholar.org/paper/6488fe7fe980684b1ae8cbe4ed3623977b2b6628) · ⭐ [71](https://github.com/s175573/GIANA/stargazers) ⭐ 76 | 🐛 20 | 🌐 HTML | 📅 2024-10-16 · `Python`

* [**tcrdist3**](https://github.com/kmayerb/tcrdist3) ⭐ 75 | 🐛 48 | 🌐 Python | 📅 2025-12-16 — tcrdist3 is a Python API-enabled toolkit for analyzing T-cell receptor repertoires. Some of the functionality and code is adapted from the original tcr-dist package.<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/34845983/) · 🪝 [126](https://www.semanticscholar.org/paper/fe7c08b0dae5d9fc6f667a9f222559ff976c5217) · ⭐ [69](https://github.com/kmayerb/tcrdist3/stargazers) ⭐ 75 | 🐛 48 | 🌐 Python | 📅 2025-12-16 · `Python`

* [**ClusTCR: a Python interface for rapid clustering of large sets of CDR3 sequences with unknown antigen specificity**](https://github.com/svalkiers/clusTCR) ⭐ 57 | 🐛 13 | 🌐 Python | 📅 2024-04-03 — CDR3 clustering module providing a new method for fast and accurate clustering of large data sets of CDR3 amino acid sequences, and offering functionalities for downstream analysis of clustering re...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/34132766/) · 🪝 [58](https://www.semanticscholar.org/paper/d8937080ab6f1d2fcbcce7c49937d29bc027ee8b) · ⭐ [54](https://github.com/svalkiers/clusTCR/stargazers) ⭐ 57 | 🐛 13 | 🌐 Python | 📅 2024-04-03 · `Python`

* [**immuneSIM: Tunable Simulation of B- And T-Cell Receptor Repertoires**](https://github.com/GreiffLab/immuneSIM) ⭐ 38 | 🐛 2 | 🌐 R | 📅 2023-11-27 — Simulate full B-cell and T-cell receptor repertoires using an in silico recombination process that includes a wide variety of tunable parameters to introduce noise and biases. Additional post-simul...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/32154832/) · 🪝 [63](https://www.semanticscholar.org/paper/https://www.semanticscholar.org/paper/530b5f57cc806f6ee93c66c3db94df8875693c73) · ⭐ [38](https://github.com/GreiffLab/immuneSIM/stargazers) ⭐ 38 | 🐛 2 | 🌐 R | 📅 2023-11-27 · `R`

* [**ALICE: Antigen-specific Lymphocyte Identification by Clustering of Expanded sequences**](https://github.com/pogorely/ALICE) ⭐ 28 | 🐛 14 | 🌐 R | 📅 2019-06-17 — Detecting TCR involved in immune responses from single RepSeq datasets.<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/31194732/) · ⭐ [27](https://github.com/pogorely/ALICE/stargazers) ⭐ 28 | 🐛 14 | 🌐 R | 📅 2019-06-17 · `R`

* [**ImReP: Rapid and accurate profiling of the adaptive immune repertoires from regular RNA-Seq data**](https://github.com/Mangul-Lab-USC/imrep) ⭐ 11 | 🐛 0 | 🌐 C | 📅 2024-04-11 — ImReP is a method to quantify individual immune response based on a recombination landscape of genes encoding B and T cell receptors (BCR and TCR). ImReP is able to efficiently extract TCR and BCR ...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/32561710/) · ⭐ [11](https://github.com/Mangul-Lab-USC/imrep/stargazers) ⭐ 11 | 🐛 0 | 🌐 C | 📅 2024-04-11 · `Python`

### Epitope Prediction

* [**epitopepredict**](https://github.com/dmnfarrell/epitopepredict) ⭐ 54 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2024-08-02 — Python package and command line tool for epitope prediction<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/36824339/) · 🪝 [6](https://www.semanticscholar.org/paper/073554e81b4370b4f409fa7bdedaa9c36e78d83f) · ⭐ [52](https://github.com/dmnfarrell/epitopepredict/stargazers) ⭐ 54 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2024-08-02 · `Jupyter Notebook`

* [**epitopeprediction**](https://github.com/nf-core/epitopeprediction) ⭐ 54 | 🐛 28 | 🌐 Nextflow | 📅 2026-08-07 — A bioinformatics best-practice analysis pipeline for epitope prediction and annotation<br>⭐ [49](https://github.com/nf-core/epitopeprediction/stargazers) ⭐ 54 | 🐛 28 | 🌐 Nextflow | 📅 2026-08-07 · [Homepage](https://nf-co.re/epitopeprediction) · `Nextflow`

* [**MuPeXI**](https://github.com/ambj/MuPeXI) ⭐ 52 | 🐛 19 | 🌐 Python | 📅 2019-09-12 — MuPeXI: the mutant peptide extractor and informer, a tool for predicting neo-epitopes from tumor sequencing data.<br>⭐ [52](https://github.com/ambj/MuPeXI/stargazers) ⭐ 52 | 🐛 19 | 🌐 Python | 📅 2019-09-12 · `Python`

* [**neoantigens**](https://github.com/umccr/neoantigens) ⚠️ Archived — Exploring novel tumor epitope identification<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/36604431/) · 🪝 [624](https://www.semanticscholar.org/paper/327da2a2b6bdbb3eea81e8a11b832c1955dd33d7) · ⭐ [37](https://github.com/umccr/neoantigens/stargazers) ⚠️ Archived · `Python`

* [**MixTCRpred**](https://github.com/GfellerLab/MixTCRpred) ⭐ 38 | 🐛 1 | 🌐 Python | 📅 2025-09-09 — Predictor of TCR-epitope interactions<br>⭐ [34](https://github.com/GfellerLab/MixTCRpred/stargazers) ⭐ 38 | 🐛 1 | 🌐 Python | 📅 2025-09-09 · `Python`

* [**AsEP-dataset**](https://github.com/biochunan/AsEP-dataset) ⭐ 34 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-08-12 — NeurIPS 2024 Dataset and Benchmark Submission "AsEP: Benchmarking Deep Learning Methods for Antibody-specific Epitope Prediction"<br>⭐ [30](https://github.com/biochunan/AsEP-dataset/stargazers) ⭐ 34 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-08-12 · `Jupyter Notebook`

* [**topiary**](https://github.com/openvax/topiary) ⭐ 30 | 🐛 4 | 🌐 Python | 📅 2026-05-18 — Predict mutated T-cell epitopes from sequencing data<br>⭐ [30](https://github.com/openvax/topiary/stargazers) ⭐ 30 | 🐛 4 | 🌐 Python | 📅 2026-05-18 · `Python`

* [**Repitope**](https://github.com/masato-ogishi/Repitope) ⭐ 24 | 🐛 2 | 🌐 R | 📅 2023-11-17 — Epitope immunogenicity prediction through in silico TCR-peptide contact potential profiling.<br>⭐ [25](https://github.com/masato-ogishi/Repitope/stargazers) ⭐ 24 | 🐛 2 | 🌐 R | 📅 2023-11-17 · `R`

* [**EpiDope**](https://github.com/rnajena/EpiDope) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2022-09-07 — Prediction of B-cell epitopes from amino acid sequences using deep neural networks.<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/34109374/) · 🪝 [11](https://www.semanticscholar.org/paper/73df19c2feb455fb3df7aaec1c6ebde0c85305c6) · ⭐ [18](https://github.com/rnajena/EpiDope/stargazers) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2022-09-07 · `Python`

* [**pyrepseq**](https://github.com/andim/pyrepseq) ⭐ 17 | 🐛 10 | 🌐 Python | 📅 2026-08-06 — Python library for immune repertoire analysis<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/36649423/) · 🪝 29 · ⭐ [17](https://github.com/andim/pyrepseq/stargazers) ⭐ 17 | 🐛 10 | 🌐 Python | 📅 2026-08-06 · `Python`

* [**ImRex**](https://github.com/pmoris/ImRex) ⭐ 17 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2023-05-22 — Generic TCR-epitope recognition prediction using CNN approach on both known and novel epitopes<br>⭐ [17](https://github.com/pmoris/ImRex/stargazers) ⭐ 17 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2023-05-22 · `Jupyter Notebook`

### Structure & Modeling

* [**Absolut: Unconstrained lattice antibody-antigen bindings generator - One tool to simulate them all!**](https://github.com/csi-greifflab/Absolut) ⭐ 114 | 🐛 7 | 🌐 Jupyter Notebook | 📅 2026-05-23 — Absolut! is a database and C++ user interface that allows the high-throughput computation for the 3D-lattice binding of any CDRH3 sequence to any antigen, enabling the custom generation of new anti...<br>[Paper](https://doi.org/10.1101/2021.07.06.451258) · 🪝 [20](https://www.semanticscholar.org/paper/77e244e5e7df68c8afeebababc8774a07290964a) · ⭐ [111](https://github.com/csi-greifflab/Absolut/stargazers) ⭐ 114 | 🐛 7 | 🌐 Jupyter Notebook | 📅 2026-05-23 · `C++`

* [**TCRdock**](https://github.com/phbradley/TCRdock) ⭐ 97 | 🐛 17 | 🌐 Python | 📅 2026-06-26 — Python tools for TCR:peptide-MHC modeling and analysis: - Set up and run TCR-specialized AlphaFold simulations starting from a TSV file with TCR, peptide, and MHC information. - Parse a TCR:peptide...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/36661395/) · 🪝 [93](https://www.semanticscholar.org/paper/daa04b1951a9f7d7390754ea48144ab18ccb9b0c) · ⭐ [86](https://github.com/phbradley/TCRdock/stargazers) ⭐ 97 | 🐛 17 | 🌐 Python | 📅 2026-06-26 · `Python`

* [**tcr-bert**](https://github.com/wukevin/tcr-bert) ⭐ 61 | 🐛 10 | 🌐 Jupyter Notebook | 📅 2022-05-04 — TCR-BERT is a large language model trained on T-cell receptor sequences, built using a lightly modified BERT architecture with tweaked pre-training objectives.<br>[Paper](http://dx.doi.org/10.1101/2021.11.18.469186) · 🪝 [74](https://www.semanticscholar.org/paper/7ef95e6164999fe9fc6d30ce2b64e8f0cabaf225) · ⭐ [57](https://github.com/wukevin/tcr-bert/stargazers) ⭐ 61 | 🐛 10 | 🌐 Jupyter Notebook | 📅 2022-05-04 · `Python`

* [**TEIM**](https://github.com/pengxingang/TEIM) ⭐ 60 | 🐛 4 | 🌐 Python | 📅 2023-07-26 — TEIM: TCR-Epitope Interaction Modeling<br>⭐ [55](https://github.com/pengxingang/TEIM/stargazers) ⭐ 60 | 🐛 4 | 🌐 Python | 📅 2023-07-26 · `Python`

* [**TCRmodel2: high-resolution modeling of T cell receptor recognition using deep learning**](https://github.com/piercelab/tcrmodel2) ⭐ 51 | 🐛 1 | 🌐 Python | 📅 2026-03-30 — This method, named TCRmodel2, allows users to submit sequences through an easy-to-use interface and shows similar or greater accuracy than AlphaFold and other methods to model TCR–peptide–MHC compl...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/37140040/) · 🪝 [70](https://www.semanticscholar.org/paper/ae85735476489e8e49f3dac80dd9bc27bf9d6b52) · ⭐ [45](https://github.com/piercelab/tcrmodel2/stargazers) ⭐ 51 | 🐛 1 | 🌐 Python | 📅 2026-03-30 · `Python` `R`

* [**TITAN - Tcr epITope bimodal Attention Networks**](https://github.com/PaccMann/TITAN) ⭐ 31 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-07-12 — a bimodal neural network that explicitly encodes both TCR sequences and epitopes to enable the independent study of generalization capabilities to unseen TCRs and/or epitopes.<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/34252922/) · 🪝 [150](https://www.semanticscholar.org/paper/a732443cae8cd2d6a76f4f3cf785a562baf41137) · ⭐ [30](https://github.com/PaccMann/TITAN/stargazers) ⭐ 31 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-07-12 · `Python`

* [**compairr**](https://github.com/uio-bmi/compairr) ⭐ 30 | 🐛 11 | 🌐 C++ | 📅 2025-01-29 — Comparison of Adaptive Immune Receptor Repertoires<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/35852318/) · 🪝 [15](https://www.semanticscholar.org/paper/d01242ad2ed3bd695117f33a02773fc20f8c0c4d) · ⭐ [28](https://github.com/uio-bmi/compairr/stargazers) ⭐ 30 | 🐛 11 | 🌐 C++ | 📅 2025-01-29 · `C++`

* [**TCRconv**](https://github.com/emmijokinen/TCRconv) ⭐ 27 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2022-10-18 — TCRconv is a deep learning model for predicting recognition between T cell receptors and epitopes. It uses protBERT embeddings for the TCRs and convolutional neural networks for the prediction.<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/36477794/) · 🪝 [20](https://www.semanticscholar.org/paper/e7408fe04e2819eecccfe2a2425d7cdfe40145ff) · ⭐ [26](https://github.com/emmijokinen/TCRconv/stargazers) ⭐ 27 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2022-10-18 · `Python` `R`

* [**vampire: Deep generative models for TCR sequences**](https://github.com/matsengrp/vampire/) ⭐ 17 | 🐛 8 | 🌐 Python | 📅 2022-04-04 — Fit and test variational autoencoder (VAE) models for T cell receptor sequences.<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/31487240/) · 🪝 [66](https://www.semanticscholar.org/paper/6597f693534cafff625af2122f929ff8a2577e80) · ⭐ [17](https://github.com/matsengrp/vampire/stargazers) ⭐ 17 | 🐛 8 | 🌐 Python | 📅 2022-04-04 · `Python`

* [**TEINet**](https://github.com/jiangdada1221/TEINet) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2023-06-30 — TEINet: a deep learning framework for prediction of TCR-epitope binding specificity<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/36907658/) · 🪝 [55](https://www.semanticscholar.org/paper/f7d928737a616310666da93d023f1477a6e709d9) · ⭐ [16](https://github.com/jiangdada1221/TEINet/stargazers) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2023-06-30 · `Python`

***

## 🗃️ HLA Databases

* [**Nomenclature of HLA Alleles**](https://hla.alleles.org/nomenclature/index.html) — A Nomenclature Committee composed of geneticists and immunologists, including specialists in tissue typing, has met after each of the Histocompatibility Workshops beginning with the Third Workshop ...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/26760826/) · 🪝 [2605](https://www.semanticscholar.org/paper/8836289f268cbbbdf879e54ff8a519f12ba80a8d) · [Homepage](https://hla.alleles.org/nomenclature/index.html)

* [**IEDB: Immune Epitope Database and Analysis Resource**](https://www.iedb.org/) — The Immune Epitope Database (IEDB) is a freely available resource funded by NIAID. It catalogs experimental data on antibody and T cell epitopes studied in humans, non-human primates, and other ani...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/30357391/) · 🪝 [1835](https://www.semanticscholar.org/paper/288b317e427c6bf4c94d455049bd1368ff2071eb) · [Homepage](https://www.iedb.org/)

* [**Allele Frequency Net Database**](http://www.allelefrequencies.net/collaborators.asp) — AFND is a public resource that collects information on allele, genotype and haplotype frequencies from different polymorphic areas in the human genome such as human leukocyte antigens (HLA), killer...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/31722398/) · 🪝 [641](https://www.semanticscholar.org/paper/3ee580308b6c1e1f3fadc00690fe871587a70885) · [Homepage](http://www.allelefrequencies.net/collaborators.asp)

* [**IMGTHLA**](https://github.com/ANHIG/IMGTHLA) ⭐ 265 | 🐛 5 | 🌐 Parrot | 📅 2026-07-14 — The IPD-IMGT/HLA Database provides a specialist database for sequences of the human major histocompatibility complex (MHC) and includes the official sequences named by the WHO Nomenclature Committe...<br>⭐ [246](https://github.com/ANHIG/IMGTHLA/stargazers) ⭐ 265 | 🐛 5 | 🌐 Parrot | 📅 2026-07-14 · [Homepage](https://www.ebi.ac.uk/ipd/imgt/hla/)

* [**pHLA3D: An online database of predicted three-dimensional structures of HLA molecules**](https://www.phla3d.com.br/) — The limited number of solved HLA structures available in the literature led our research group to develop, in 2019, the pHLA3D, an online database of predicted three-dimensional structures of HLA m...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/31239187/) · 🪝 [98](https://www.semanticscholar.org/paper/810def2f2bb6693affa9a449255555ea71fdc064) · [Homepage](https://www.phla3d.com.br/)

***

## 🧬 HLA Analysis

### Association Studies

* [**HLA\_analyses\_tutorial**](https://github.com/immunogenomics/HLA_analyses_tutorial) ⭐ 74 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-10-10 — A thorough tutorial on HLA imputation and association, accompanying our manuscript "Tutorial: A statistical genetics guide to identifying HLA alleles driving complex disease"<br>⭐ [70](https://github.com/immunogenomics/HLA_analyses_tutorial/stargazers) ⭐ 74 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-10-10 · `Jupyter Notebook`

* [**HLA-TAPAS: HLA-Typing At Protein for Association Studies**](https://github.com/immunogenomics/HLA-TAPAS) ⭐ 57 | 🐛 20 | 🌐 Jupyter Notebook | 📅 2023-12-19 — An HLA-focused pipeline that can handle HLA reference panel construction (MakeReference), HLA imputation (SNP2HLA), and HLA association (HLAassoc). It is an updated version of the SNP2HLA.<br>⭐ [54](https://github.com/immunogenomics/HLA-TAPAS/stargazers) ⭐ 57 | 🐛 20 | 🌐 Jupyter Notebook | 📅 2023-12-19 · `Python` `R`

* [**PyHLA**](https://github.com/felixfan/PyHLA) ⭐ 37 | 🐛 3 | 🌐 Python | 📅 2026-04-08 — Python for HLA analysis: summary, association analysis, zygosity test and interaction test<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/28166716/) · ⭐ [38](https://github.com/felixfan/PyHLA/stargazers) ⭐ 37 | 🐛 3 | 🌐 Python | 📅 2026-04-08 · `Python`

* [**HATK: HLA Analysis Toolkit**](https://github.com/WansonChoi/HATK) ⭐ 29 | 🐛 12 | 🌐 Parrot | 📅 2022-12-18 — HATK(HLA Analysis Tool-Kit) is a collection of tools and modules to perform HLA fine-mapping analysis, which is to identify which HLA allele or amino acid position of the HLA gene is driving the di...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/32735319/) · 🪝 [15](https://www.semanticscholar.org/paper/55a244823d8fd8527819dbd02ffafdc4e661a795) · ⭐ [28](https://github.com/WansonChoi/HATK/stargazers) ⭐ 29 | 🐛 12 | 🌐 Parrot | 📅 2022-12-18 · `Python`

* [**cdr3-QTL**](https://github.com/immunogenomics/cdr3-QTL) ⭐ 19 | 🐛 0 | 🌐 HTML | 📅 2023-03-29 — Trans-association between HLA and TCR-CDR3<br>⭐ [19](https://github.com/immunogenomics/cdr3-QTL/stargazers) ⭐ 19 | 🐛 0 | 🌐 HTML | 📅 2023-03-29 · `HTML`

* [**hlabud: HLA genotype analysis in R**](https://github.com/slowkow/hlabud) ⭐ 19 | 🐛 3 | 🌐 R | 📅 2025-04-11 — hlabud provides methods to retrieve sequence alignment data from IMGTHLA and convert the data into convenient R matrices ready for downstream analysis. See the usage examples to learn how to use th...<br>⭐ [17](https://github.com/slowkow/hlabud/stargazers) ⭐ 19 | 🐛 3 | 🌐 R | 📅 2025-04-11 · `R`

* [**MATER: Minimizer RNAseq HLA typer**](https://github.com/genentech/midasHLA) ⭐ 14 | 🐛 11 | 🌐 R | 📅 2024-01-31 — MATER is a minimizer-based HLA typer for RNAseq read dataset. In a typical RNAseq dataset, the reads sampled from HLA genes are less uniform and may miss regions that makes assembly or variant call...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/34228721/) · 🪝 [24](https://www.semanticscholar.org/paper/16f5a5d9b7119ea85eab9aae4650445770a03b3b) · ⭐ [14](https://github.com/genentech/midasHLA/stargazers) ⭐ 14 | 🐛 11 | 🌐 R | 📅 2024-01-31 · `Python` `R` `C`

* [**BIGDAWG: Case-Control Analysis of Multi-Allelic Loci**](https://github.com/IgDAWG/BIGDAWG) ⭐ 4 | 🐛 4 | 🌐 R | 📅 2026-05-04 — Data sets and functions for chi-squared Hardy-Weinberg and case-control association tests of highly polymorphic genetic data \[e.g., human leukocyte antigen (HLA) data]. Performs association tests a...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/26708359/) · 🪝 [82](https://www.semanticscholar.org/paper/8e4c6ba503b7d729681e09f60b22782fd36b3ad4) · ⭐ [3](https://github.com/IgDAWG/BIGDAWG/stargazers) ⭐ 4 | 🐛 4 | 🌐 R | 📅 2026-05-04 · `R`

* [**HLA Electrostatic Potential**](https://pubmed.ncbi.nlm.nih.gov/30429288/) — A method for predicting humoral alloimmunity from differences in donor and recipient HLA surface electrostatic potential, enabling assessment of immunological compatibility in transplantation.<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/30429288/) · 🪝 [53](https://www.semanticscholar.org/paper/1c38ce8e6f0a43a1c806a8cd65d105879459bdb4)

### HLA Typing

* [**OptiType: Precision HLA typing from next-generation sequencing data**](https://github.com/FRED-2/OptiType) ⭐ 223 | 🐛 51 | 🌐 Python | 📅 2026-05-20 — OptiType is a novel HLA genotyping algorithm based on integer linear programming, capable of producing accurate 4-digit HLA genotyping predictions from NGS data by simultaneously selecting all majo...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/25143287/) · 🪝 [643](https://www.semanticscholar.org/paper/1d4162253d3e32a2b3a62d0f8faab4fba3386c10) · ⭐ [205](https://github.com/FRED-2/OptiType/stargazers) ⭐ 223 | 🐛 51 | 🌐 Python | 📅 2026-05-20 · `Python`

* [**arcasHLA: Fast and accurate in silico inference of HLA genotypes from RNA-seq**](https://github.com/RabadanLab/arcasHLA) ⭐ 161 | 🐛 52 | 🌐 Python | 📅 2024-08-20 — arcasHLA performs high resolution genotyping for HLA class I and class II genes from RNA sequencing, supporting both paired and single-end samples.<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/31173059/) · 🪝 [157](https://www.semanticscholar.org/paper/9fccbea05592fb2c8d0cf8ff0fe330729ad81db8) · ⭐ [152](https://github.com/RabadanLab/arcasHLA/stargazers) ⭐ 161 | 🐛 52 | 🌐 Python | 📅 2024-08-20 · `Python`

* [**HLA-LA: Fast HLA type inference from whole-genome data**](https://github.com/DiltheyLab/HLA-LA) ⭐ 146 | 🐛 57 | 🌐 C++ | 📅 2025-04-03 — HLA typing based on a population reference graph and employs a new linear projection method to align reads to the graph.<br>⭐ [141](https://github.com/DiltheyLab/HLA-LA/stargazers) ⭐ 146 | 🐛 57 | 🌐 C++ | 📅 2025-04-03 · `Perl`

* [**xHLA: Fast and accurate HLA typing from short read sequence data**](https://github.com/humanlongevity/HLA) ⭐ 117 | 🐛 47 | 🌐 Jupyter Notebook | 📅 2023-10-13 — xHLA iteratively refines the mapping results at the amino acid level to achieve 99 to 100% 4-digit typing accuracy for both class I and II HLA genes, taking only about 3 minutes to process a 30X wh...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/28674023/) · 🪝 [125](https://www.semanticscholar.org/paper/0e7b3c0eb32913f710c93bfe149610bc2d2ce8e3) · ⭐ [113](https://github.com/humanlongevity/HLA/stargazers) ⭐ 117 | 🐛 47 | 🌐 Jupyter Notebook | 📅 2023-10-13 · [Homepage](https://pubmed.ncbi.nlm.nih.gov/28674023) · `Python` `R` `Perl` `Bash`

* [**T1K: efficient and accurate inference of KIR or HLA alleles from RNA-seq, whole-genome sequencing, or whole-exome sequencing data**](https://github.com/mourisl/T1K) ⭐ 108 | 🐛 3 | 🌐 C | 📅 2026-07-31 — T1K (The ONE genotyper for Kir and HLA) is a computational tool to infer the alleles for the polymorphic genes such as KIR and HLA. T1K calculates the allele abundances based on the RNA-seq/WES/WGS...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/37169596/) · 🪝 [25](https://www.semanticscholar.org/paper/c8ff85a07e0dc87973ba73daccc10731f225a914) · ⭐ [94](https://github.com/mourisl/T1K/stargazers) ⭐ 108 | 🐛 3 | 🌐 C | 📅 2026-07-31 · `C` `C++` `Python` `Perl`

* [**hlatyping**](https://github.com/nf-core/hlatyping) ⭐ 81 | 🐛 13 | 🌐 Nextflow | 📅 2026-07-31 — Precision HLA typing from next-generation sequencing data<br>⭐ [76](https://github.com/nf-core/hlatyping/stargazers) ⭐ 81 | 🐛 13 | 🌐 Nextflow | 📅 2026-07-31 · [Homepage](https://nf-co.re/hlatyping) · `Nextflow`

* [**scHLAcount**](https://github.com/10XGenomics/scHLAcount) ⭐ 64 | 🐛 15 | 🌐 TeX | 📅 2021-11-05 — Count HLA alleles in single-cell RNA-seq data<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/32330223/) · 🪝 [20](https://www.semanticscholar.org/paper/f38834e9b0845e743e8e41604c0ee9d327d3fe48) · ⭐ [63](https://github.com/10XGenomics/scHLAcount/stargazers) ⭐ 64 | 🐛 15 | 🌐 TeX | 📅 2021-11-05 · `TeX`

* [**SpecHLA**](https://github.com/deepomicslab/SpecHLA) ⭐ 60 | 🐛 8 | 🌐 C++ | 📅 2026-07-27 — SpecHLA reconstructs entire diploid sequences of HLA genes and infers LOH events. It supports HLA-A, -B, -C, -DPA1, -DPB1, -DQA1, -DQB1, and -DRB1 genes. Also, it supports both short- and long-read...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/37714157/) · 🪝 [11](https://www.semanticscholar.org/paper/78feeabf537fe7503ff5fe2421b2668f635fa504) · ⭐ [53](https://github.com/deepomicslab/SpecHLA/stargazers) ⭐ 60 | 🐛 8 | 🌐 C++ | 📅 2026-07-27 · `C++`

* [**seq2HLA: HLA typing from RNA-Seq sequence reads**](https://github.com/TRON-Bioinformatics/seq2HLA) ⭐ 52 | 🐛 17 | 🌐 Python | 📅 2025-08-09 — In-silico method written in Python and R to determine HLA genotypes of a sample. seq2HLA takes standard RNA-Seq sequence reads in fastq format as input, uses a bowtie index comprising all HLA allel...<br>⭐ [50](https://github.com/TRON-Bioinformatics/seq2HLA/stargazers) ⭐ 52 | 🐛 17 | 🌐 Python | 📅 2025-08-09 · `Python` `R`

* [**Kourami: Graph-guided assembly for HLA alleles**](https://github.com/Kingsford-Group/kourami) ⭐ 42 | 🐛 19 | 🌐 Java | 📅 2019-05-21 — Kourami is a graph-guided assembler for HLA haplotypes covering typing exons (exons 2 and 3 for Class I and exon 3 for Class II) using high-coverage whole genome sequencing data. Kourami constructs...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/29415772/) · 🪝 [82](https://www.semanticscholar.org/paper/42b1d2f74a6fcdd9e45b64a4acabddafb43d7426) · ⭐ [38](https://github.com/Kingsford-Group/kourami/stargazers) ⭐ 42 | 🐛 19 | 🌐 Java | 📅 2019-05-21 · `Java` `Bash`

* [**HLAProfiler: Using k-mers to call HLA alleles in RNA sequencing data**](https://github.com/ExpressionAnalysis/HLAProfiler) ⭐ 23 | 🐛 3 | 🌐 Perl | 📅 2018-07-26 — HLAProfiler uses the k-mer content of next generation sequencing reads to call HLA types in a sample. Based on the k-mer content each each read pair is assigned to an HLA gene and the aggregate k-m...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/28954626/) · 🪝 [44](https://www.semanticscholar.org/paper/9781ba0fad5a5841a506d25b8e3a9328996ebe52) · ⭐ [23](https://github.com/ExpressionAnalysis/HLAProfiler/stargazers) ⭐ 23 | 🐛 3 | 🌐 Perl | 📅 2018-07-26 · `Perl`

* [**MultiHLA: WES HLA Typing based on multiple alternative tools**](https://github.com/lkuchenb/MultiHLA) ⭐ 18 | 🐛 3 | 🌐 Python | 📅 2021-03-08 — This workflow enables the concurrent analysis of WES or WGS data using publicly available software to derive HLA haplotypes from this type of data. It includes automated Snakemake workflows for the...<br>⭐ [18](https://github.com/lkuchenb/MultiHLA/stargazers) ⭐ 18 | 🐛 3 | 🌐 Python | 📅 2021-03-08 · `Snakemake`

* [**hla3: weight of evidence of HLA allele expression based on bulk TCR beta-chain repertoires**](https://github.com/kmayerb/hla3) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2022-02-23 — This repository contains Python functions for inferring HLA-alleles from bulk TCR beta chain data using a simple weight of evidence predictor.<br>⭐ [3](https://github.com/kmayerb/hla3/stargazers) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2022-02-23 · `Python`

* [**PHLAT: Inference of High Resolution HLA Types**](https://sites.google.com/site/phlatfortype/home) — PHLAT is a bioinformatics algorithm that offers HLA typing at four-digit resolution (or higher) using genome-wide transcriptome and exome sequencing data over a wide range of read lengths and seque...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/29858810/) · 🪝 [46](https://www.semanticscholar.org/paper/6d09c67998833e831897289ba1ea08efd0b81fee) · [Homepage](https://sites.google.com/site/phlatfortype/home) · `Python`

* [**SNP2HLA: Imputation of Amino Acid Polymorphisms in Human Leukocyte Antigens**](http://software.broadinstitute.org/mpg/snp2hla/) — SNP2HLA is a tool to impute amino acid polymorphisms and single nucleotide polymorphisms in human luekocyte antigenes (HLA) within the major histocompatibility complex (MHC) region in chromosome 6.<br>[Homepage](http://software.broadinstitute.org/mpg/snp2hla/)

### Peptide Prediction

* [**NeoBert**](https://github.com/CHB-learner/NeoBert) ⭐ 139 | 🐛 2 | 🌐 Python | 📅 2024-12-21 — NeoBERT is an advanced model designed specifically for predicting the binding affinity between neoantigens and HLA. It is a variant of the original BERT model, enhanced to integrate biological feat...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/41224698/) · ⭐ [155](https://github.com/CHB-learner/NeoBert/stargazers) ⭐ 139 | 🐛 2 | 🌐 Python | 📅 2024-12-21 · `Python`

* [**bigmhc**](https://github.com/KarchinLab/bigmhc) ⭐ 69 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2025-12-17 — BigMHC predicts MHC-I (neo)epitope presentation and immunogenicity<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/37829001/) · 🪝 [60](https://www.semanticscholar.org/paper/ef7763384b5f987dc546cdd9ece14b3e81b89190) · ⭐ [59](https://github.com/KarchinLab/bigmhc/stargazers) ⭐ 69 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2025-12-17 · `Jupyter Notebook`

* [**MixMHC2pred**](https://github.com/GfellerLab/MixMHC2pred) ⭐ 51 | 🐛 0 | 🌐 C++ | 📅 2026-07-17 — HLA-II ligand predictor.<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/38907900/) · 🪝 [4](https://www.semanticscholar.org/paper/951c39da3e761004836a22ef928c3ff7a8772542) · ⭐ [46](https://github.com/GfellerLab/MixMHC2pred/stargazers) ⭐ 51 | 🐛 0 | 🌐 C++ | 📅 2026-07-17 · `C++`

* [**MixMHCpred**](https://github.com/GfellerLab/MixMHCpred) ⭐ 47 | 🐛 1 | 🌐 Python | 📅 2026-03-19 — HLA-I ligand predictor<br>⭐ [43](https://github.com/GfellerLab/MixMHCpred/stargazers) ⭐ 47 | 🐛 1 | 🌐 Python | 📅 2026-03-19 · `Python`

* [**High-Throughput Prediction of MHC Class I and II Neoantigens with MHCnuggets**](https://github.com/KarchinLab/mhcnuggets) ⭐ 37 | 🐛 9 | 🌐 Python | 📅 2025-07-23 — MHC Class I and Class II neoantigen binding prediction<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/31871119/) · 🪝 [131](https://www.semanticscholar.org/paper/33d23cc483e4b077b1f637444b10e98cb1f6bab7) · ⭐ [33](https://github.com/KarchinLab/mhcnuggets/stargazers) ⭐ 37 | 🐛 9 | 🌐 Python | 📅 2025-07-23 · `Python`

* [**MHCAttnNet**](https://github.com/gopuvenkat/MHCAttnNet) ⭐ 30 | 🐛 1 | 🌐 Python | 📅 2021-02-14 — MHCAttnNet: Allele-Peptide predictions for class I & class II MHC alleles<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/32657386/) · 🪝 [39](https://www.semanticscholar.org/paper/64fd328e9f126c6277e2ab50f4a4b86be9bfda94) · ⭐ [30](https://github.com/gopuvenkat/MHCAttnNet/stargazers) ⭐ 30 | 🐛 1 | 🌐 Python | 📅 2021-02-14 · `Python`

* [**immunogenetr**](https://github.com/k96nb01/immunogenetr_package) ⭐ 6 | 🐛 2 | 🌐 R | 📅 2026-07-07 — immunogenetr is a comprehensive toolkit for clinical HLA informatics. It is built on tidyverse principles and makes use of genotype list string (GL string, <https://glstring.org/>) for storing and us...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/41344288/) · ⭐ [6](https://github.com/k96nb01/immunogenetr_package/stargazers) ⭐ 6 | 🐛 2 | 🌐 R | 📅 2026-07-07 · [Homepage](https://glstring.org/) · `R`

* [**HLAMatchmaker**](https://pubmed.ncbi.nlm.nih.gov/11975978/) — A molecularly based algorithm for histocompatibility determination that identifies acceptable HLA antigens for highly alloimmunized patients based on amino acid triplets (eplets) on exposed parts o...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/11975978/) · 🪝 [267](https://www.semanticscholar.org/paper/7a00824f5126ab1433ac8fdcfba4dab4854ab3b2)

* [**HLA-EMMA**](https://pubmed.ncbi.nlm.nih.gov/32227681/) — A user-friendly tool to analyze HLA class I and class II compatibility on the amino acid level, facilitating the assessment of donor-recipient compatibility in transplantation.<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/32227681/) · 🪝 [82](https://www.semanticscholar.org/paper/2739806ab693e3eab964e75041527569045cb62c)

* [**PIRCHE-II**](https://www.pirche.com) — An algorithm to predict indirectly recognizable HLA epitopes in solid organ transplantation, helping to evaluate immunological compatibility between donors and recipients.<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/31741009/) · 🪝 [81](https://www.semanticscholar.org/paper/75defe0480b1dbd3c64501d05370a69ea3a6b260) · [Homepage](https://www.pirche.com)

* [**EpVix: epitope reactivity analysis and epitope virtual crossmatching**](https://pubmed.ncbi.nlm.nih.gov/26531328/) — Performs automated epitope virtual crossmatching at the initiation of the organ donation process. EpViX is a free, web-based application developed for use over the internet on a tablet, smartphone ...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/26531328/) · 🪝 [12](https://www.semanticscholar.org/paper/f87da5d55ad244c92cacc84804775bd1e5df2fd0) · `Ruby`

### Data & Nomenclature

* [**MHC-PRG**](https://github.com/AlexanderDilthey/MHC-PRG) ⭐ 35 | 🐛 4 | 🌐 C++ | 📅 2018-12-18 — Population Reference Graphs for the HLA and MHC.<br>⭐ [35](https://github.com/AlexanderDilthey/MHC-PRG/stargazers) ⭐ 35 | 🐛 4 | 🌐 C++ | 📅 2018-12-18 · `C++`

* [**py-ard**](https://github.com/nmdp-bioinformatics/py-ard) ⭐ 19 | 🐛 15 | 🌐 Python | 📅 2026-08-06 — HLA ARD Reduction in Python. Although HLA nomenclature has not always conformed to the same standard, it is now defined by The WHO Nomenclature Committee for Factors of the HLA System. py-ard is aw\...<br>⭐ [19](https://github.com/nmdp-bioinformatics/py-ard/stargazers) ⭐ 19 | 🐛 15 | 🌐 Python | 📅 2026-08-06 · `Python`

* [**HLAtools: Functions and Datasets for HLA Informatics**](https://github.com/sjmack/HLAtools) ⭐ 4 | 🐛 1 | 🌐 R | 📅 2026-07-28 — We have developed HLAtools, an R package that automates the consumption of IPD-IMGT/HLA resources, renders them computable, and makes them available alongside tools for data analysis, visualization...<br>[PubMed](https://pubmed.ncbi.nlm.nih.gov/40947766/) · 🪝 [1](https://www.semanticscholar.org/paper/a47f89a247c3149305dba16cfcbbd94b66810d49) · ⭐ [4](https://github.com/sjmack/HLAtools/stargazers) ⭐ 4 | 🐛 1 | 🌐 R | 📅 2026-07-28 · `R`

***

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
