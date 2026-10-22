# Hi there, I'm Burak Bulut, Ph.D. 👋

**Bioinformatics Scientist & Computational Biologist**  
📍 *Wiesbaden / Frankfurt Rhine-Main, Germany*

[![Website](https://img.shields.io/badge/Portfolio-burakbulut--sh.github.io-0284c7?style=flat&logo=googlechrome&logoColor=white)](https://burakbulut-sh.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-burak--bulut-0077b5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/burak-bulut-2765a934a)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-Citations-4285f4?style=flat&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=FEsH8RAAAAAJ&hl=en)
[![Email](https://img.shields.io/badge/Email-burak.buluut%40outlook.com-blue?style=flat&logo=microsoftoutlook&logoColor=white)](mailto:burak.buluut@outlook.com)

---

## 🔬 About Me

I am a Computational Biologist and Bioinformatics Scientist with **6+ years of expertise** spanning high-throughput Whole-Genome Sequencing (WGS), RNA-Seq, high-performance computing (HPC / SLURM), reproducible workflow engineering (Snakemake / Docker), and applied AI/LLM agent development for genomics.

- 🎓 **Ph.D. in Molecular Ecology & Bioinformatics** from **Johannes Gutenberg University Mainz** & **Senckenberg Biodiversity and Climate Research Centre (SBiK-F)**, Frankfurt, Germany.
  - *Dissertation:* [*Deconstructing the proximate drivers of the germline mutation rate in Chironomus riparius*](https://openscience.ub.uni-mainz.de/items/6da17349-cbd0-445d-aed8-746095f729f1)
- 🧪 **Interdisciplinary Foundation:** Combined high-throughput computational pipeline engineering with experimental wet-lab assays (*in vivo* ROS quantification, confocal/fluorescence microscopy, multi-generational mutation accumulation lines).
- 🤖 **AI in Bioinformatics:** Engineering local LLM and RAG-based bioinformatics agents for QC telemetry, automated variant annotation, and reproducible pipeline reasoning.

---

## 🛠️ Technical Competencies

| Domain | Technologies & Frameworks |
|---|---|
| **Programming & Scripting** | Python (NumPy, Pandas, Typer, Pydantic, PySAM), R (tidyverse, DESeq2, limma, WGCNA), Bash, SQL |
| **Workflow & HPC** | Snakemake, SLURM, Docker, Nextflow, Git, CI/CD (GitHub Actions) |
| **Genomics & Variant Calling** | BWA-MEM, SAMtools, GATK4 (HaplotypeCaller gVCF), Picard, bcftools, Trimmomatic, PEAR, accuMUlate |
| **Transcriptomics & Omics** | HISAT2, Subread (featureCounts), DESeq2, limma, biomaRt, Pathview, Meta-Analysis |
| **AI & Bio-Agents** | Local LLMs (llama.cpp, HuggingFace, Hermes Agent), LangChain, LlamaIndex, RAG, Agentic Tool Use, Vector DBs |

---

## 🚀 Featured Open Source Tools & Pipelines

### 📚 [BioReader](https://github.com/BurakBulut-sh/BioReader)
> *Intelligent scientific PDF reader and literature workspace for bioinformatics researchers.*  
- High-fidelity PDF rendering with visual monograph layout, precision coordinate navigation, and reading comfort modes (Paper, Sepia, Dark).
- Semantic research notes linked to exact manuscript coordinates with offline biological glossary (2,000+ terms) and multi-format exports.

### 🔍 [SampleSheriff](https://github.com/BurakBulut-sh/samplesheriff)
> *A fast, strict, nf-core-style sample sheet and metadata validator for bioinformatics pipelines.*  
- Enforces pre-flight validation on FASTQ pairing, BAM headers, VCF integrity, and custom YAML schemas.
- Prevents expensive multi-day HPC pipeline crashes through instant fail-fast diagnostics.

### ⏱️ [PipeWatch](https://github.com/BurakBulut-sh/pipewatch)
> *Lightweight pipeline observability and resource telemetry for legacy SLURM/HPC workflows.*  
- Zero-dependency Bash wrapper (`obsrun`) emitting structured NDJSON telemetry.
- Python reporting engine generating interactive HTML dashboards, memory peaks, and runtime bottleneck analyses.

### 🧬 [SNP-analysis](https://github.com/BurakBulut-sh/SNP-analysis)
> *WGS variant discovery, GATK HaplotypeCaller gVCF cohort array, and Bayesian mutation rate modeling.*  
- Powers spontaneous germline mutation discovery published in *Evolution Letters (2026)* and *Molecular Ecology (2026)*.

### 📊 [Transcriptome-Study](https://github.com/BurakBulut-sh/Transcriptome-Study)
> *RNA-Seq processing and statistical modeling of oxidative stress & thermal gradient responses.*  
- Scalable HISAT2 + featureCounts pipeline with DESeq2/limma contrast modeling (*Ecology and Evolution 2025*).

### 🌿 [Meta-Transcriptome-Analysis](https://github.com/BurakBulut-sh/Meta-Transcriptome-Analysis)
> *Cross-study RNA-Seq meta-analysis & KEGG pathway mapping in Beta vulgaris under biotic/abiotic stress.*  
- Integrates multi-factor GLM differential expression with Fisher combined probability tests (*Tropical Plant Biology 2023*).

---

## 📚 Selected Publications

1. **Bulut, B.**, & Pfenninger, M. (2026). Developmental speed and chronological time exert opposing effects on the spontaneous mutation rate in *Chironomus riparius*. ***Evolution Letters***, 10(3), 283-293. [DOI: 10.1093/evlett/qrag010](https://doi.org/10.1093/evlett/qrag010)
2. Pfenninger, M., Nieto-Blazquez, M. E., & **Bulut, B.** (2026). Divergent Thermal Reaction Norms of the Spontaneous Mutation Rate Among Populations of *Chironomus riparius*. ***Molecular Ecology***, 35(15), e70503. [DOI: 10.1111/mec.70503](https://doi.org/10.1111/mec.70503)
3. **Bulut, B.**, Geiss, M., Bernard, M., Doria, H. B., Feldmeyer, B., & Pfenninger, M. (2025). Dissecting Oxidative Stress and Organismic Response to a Temperature Gradient in the Midge *Chironomus riparius*. ***Ecology and Evolution***, 15(12), e72625. [DOI: 10.1002/ece3.72625](https://doi.org/10.1002/ece3.72625)
4. Eberhardt, L., Doria, H. B., **Bulut, B.**, Feldmeyer, B., & Pfenninger, M. (2025). Transcriptomics predicts artificial light at night's (ALAN) negative fitness effects and altered gene expression patterns in the midge *Chironomus riparius* (Diptera: Chironomidae). ***Environmental Pollution***, 369, 125827. [DOI: 10.1016/j.envpol.2025.125827](https://doi.org/10.1016/j.envpol.2025.125827)
5. **Bulut, B.**, Rigano, L., Doria, H. B., Gemüth, G., & Pfenninger, M. (2024). A multigenerational study can detect the evolutionary response to BaP exposure in the non-biting freshwater midge *Chironomus riparius*. ***Chemosphere***, 358, 142242. [DOI: 10.1016/j.chemosphere.2024.142242](https://doi.org/10.1016/j.chemosphere.2024.142242)
6. **Bulut, B.**, Gürel, S., Ünüvar, Ö. C., Gürel, E., Şahin, Y., Çabuk, U., & Ünlü, E. S. (2023). Meta Analysis of Sugar Beet (*Beta vulgaris* L.) Transcriptome Profiles Under Different Biotic and Abiotic Stress Conditions. ***Tropical Plant Biology***, 16(3), 199-207. [DOI: 10.1007/s12042-023-09344-y](https://doi.org/10.1007/s12042-023-09344-y)

---

## 🌐 Connect with Me

- 💻 **Portfolio & Interactive CV:** [burakbulut-sh.github.io](https://burakbulut-sh.github.io)
- 💼 **LinkedIn:** [linkedin.com/in/burak-bulut-2765a934a](https://www.linkedin.com/in/burak-bulut-2765a934a)
- 📬 **Email:** [burak.buluut@outlook.com](mailto:burak.buluut@outlook.com)
- 🎓 **Google Scholar:** [Burak Bulut](https://scholar.google.com/citations?user=FEsH8RAAAAAJ&hl=en)
