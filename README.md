<h1 align="center">Mallikarjuna Thippana, PhD</h1>
<p align="center"><b>Computational Biologist</b> · Cancer Gene Regulation · 3D Genomics · Cancer WGS &amp; ecDNA · Single-Cell · Computational Methods</p>

<p align="center">
  <a href="https://arjunbioinfo.github.io/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-arjunbioinfo.github.io-2b7a78?logo=githubpages&logoColor=white"></a>
  <a href="https://scholar.google.com/citations?user=NpLUj68AAAAJ&hl=en"><img alt="Google Scholar" src="https://img.shields.io/badge/Google%20Scholar-4285F4?logo=googlescholar&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/mallikarjun-thippana/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white"></a>
  <a href="https://www.researchgate.net/profile/Mallikarjuna-Thippana"><img alt="ResearchGate" src="https://img.shields.io/badge/ResearchGate-00CCBB?logo=researchgate&logoColor=white"></a>
  <a href="https://orcid.org/0000-0001-8485-8626"><img alt="ORCID" src="https://img.shields.io/badge/ORCID-0000--0001--8485--8626-A6CE39?logo=orcid&logoColor=white"></a>
  <a href="https://arjunbioinfo.github.io/CV_Thippana_2026.pdf"><img alt="CV" src="https://img.shields.io/badge/CV-PDF-555?logo=adobeacrobatreader&logoColor=white"></a>
</p>

Postdoctoral researcher in the Department of Oncology-Pathology at **Karolinska Institutet**, Stockholm. I study how distal regulatory elements control cancer genes such as **MYC**, integrating GRO-seq, ATAC-seq, CUT&RUN, 4C-seq and RNA-seq, and I analyse single-nucleus RNA-seq cohorts and patient-tumour whole genomes for focal amplifications and ecDNA.

- 🔬 **Now:** MYC/CTCF enhancer regulation (co-author, under revision at *Nucleic Acids Research*) · a 17-donor clinical snRNA-seq cohort · cancer WGS / ecDNA
- 🧮 **PhD work:** two original, peer-reviewed gene-prioritisation algorithms, released here as tested, citable software
- 📄 **Output:** 8 peer-reviewed articles + 3 preprints. See the [full list](https://arjunbioinfo.github.io/#publications)
- 🤝 **Open to:** computational biology / bioinformatics scientist roles and collaborations

### 🧬 Published methods

| Method | Paper | Code | Software DOI |
|---|---|---|---|
| **Chaos game + 2D multifractal cross-correlation** for alignment-free gene prioritisation | *Theory in Biosciences* 2024 · [doi](https://doi.org/10.1007/s12064-024-00418-3) | [cgr-mfxdfa-gene-prioritization](https://github.com/arjunbioinfo/cgr-mfxdfa-gene-prioritization) | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21167708.svg)](https://doi.org/10.5281/zenodo.21167708) |
| **Moment-of-inertia tensor** protein descriptors for gene prioritisation | *Proteins* 2022 · [doi](https://doi.org/10.1002/prot.26226) | [moment-of-inertia-tensor-gene-prioritization](https://github.com/arjunbioinfo/moment-of-inertia-tensor-gene-prioritization) | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21157912.svg)](https://doi.org/10.5281/zenodo.21157912) |

### ⚙️ Reproducible pipelines & tools

| Project | What it does | Stack | Software DOI |
|---|---|---|---|
| [ecDNA-WGS-circdna](https://github.com/arjunbioinfo/ecDNA-WGS-circdna) | Version-pinned, config-driven wrapper around nf-core/circdna for detecting ecDNA from whole-genome sequencing (AmpliconArchitect + Circle-Map branches) | Nextflow · nf-core · AmpliconSuite | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24392071.svg)](https://doi.org/10.5281/zenodo.24392071) |
| [ampliconsuite-2026-reproducibility](https://github.com/arjunbioinfo/ampliconsuite-2026-reproducibility) | Independent reproduction of the AmpliconClassifier FISH validation ([Luebeck et al., *Nature Methods* 2026](https://doi.org/10.1038/s41592-026-03264-x)): Figure 1d–e rebuilt from deposited data across 175 gene probes in 72 cell lines | Python · ecDNA | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24392033.svg)](https://doi.org/10.5281/zenodo.24392033) |
| [enhancer-gene-atac-rna-ctcf](https://github.com/arjunbioinfo/enhancer-gene-atac-rna-ctcf) | Snakemake workflow integrating ENCODE ATAC-seq, RNA-seq and CTCF ChIP-seq to link distal enhancers to genes and test CTCF occupancy with peak-level statistics | Snakemake · Python · ENCODE | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24392024.svg)](https://doi.org/10.5281/zenodo.24392024) |
| [scRNA-seq-reproducible](https://github.com/arjunbioinfo/scRNA-seq-reproducible) | Deterministic Scanpy/scverse pipeline from a GEO accession or 10x file to QC, clusters and marker genes | Python · Scanpy · scverse | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24392077.svg)](https://doi.org/10.5281/zenodo.24392077) |
| [scrna-multidonor-pseudobulk](https://github.com/arjunbioinfo/scrna-multidonor-pseudobulk) | Multi-donor scRNA-seq: Harmony integration, donor-level pseudobulk PyDESeq2, compared with single-cell DE calls (Kang 2018 PBMC) | Snakemake · Scanpy · PyDESeq2 | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24392039.svg)](https://doi.org/10.5281/zenodo.24392039) |
| [cancer-cohort-wgcna-survival](https://github.com/arjunbioinfo/cancer-cohort-wgcna-survival) | TCGA-CESC cohort analysis: limma DE, fgsea, signed WGCNA modules and Cox / Kaplan–Meier survival | R · Bioconductor · WGCNA | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24392053.svg)](https://doi.org/10.5281/zenodo.24392053) |
| [multiomics-cancer-biomarker-ml](https://github.com/arjunbioinfo/multiomics-cancer-biomarker-ml) | Leak-free cross-validated RNA vs copy-number vs combined models on TCGA-LUSC, with SHAP attribution and out-of-fold Cox survival | Python · scikit-learn · SHAP | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24392063.svg)](https://doi.org/10.5281/zenodo.24392063) |
| [efficiency-corrected-rt-qpcr](https://github.com/arjunbioinfo/efficiency-corrected-rt-qpcr) | Pfaffl-style amplification-efficiency correction for RT-qPCR, with a [live report](https://arjunbioinfo.github.io/efficiency-corrected-rt-qpcr/) | R · Excel | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24392084.svg)](https://doi.org/10.5281/zenodo.24392084) |

Most code is MIT-licensed, and the methods and pipelines are tested with GitHub Actions.

### 🛠️ Toolkit

<p>
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
<img alt="R" src="https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white">
<img alt="Bash" src="https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white">
<img alt="Nextflow" src="https://img.shields.io/badge/Nextflow-0DC09D?logo=nextflow&logoColor=white">
<img alt="Snakemake" src="https://img.shields.io/badge/Snakemake-039475">
<img alt="Docker" src="https://img.shields.io/badge/Docker%20%2F%20Apptainer-2496ED?logo=docker&logoColor=white">
<img alt="Linux HPC" src="https://img.shields.io/badge/Linux%20HPC%20%2F%20SLURM-FCC624?logo=linux&logoColor=black">
<img alt="Scanpy" src="https://img.shields.io/badge/Scanpy%20%2F%20scverse-1f6feb">
<img alt="Bioconductor" src="https://img.shields.io/badge/Bioconductor-1a81c2">
</p>

**Assays:** GRO-seq · ATAC-seq · CUT&RUN · ChIP-seq · 4C-seq · RNA-seq · sc/snRNA-seq · WGS

<sub>📫 arjun.ins@gmail.com · Stockholm, Sweden</sub>
