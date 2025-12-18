#  **Hi, I'm LaShanda R. Williams, PhD**

### **AI/ML Bioinformatics Scientist | Deep Learning | Interpretable ML | MLOps**

I am an AI/ML bioinformatics scientist with a background in computational biology, microbial ecology, and infectious disease genomics, focused on building interpretable, biologically grounded machine learning models for high-stakes biological data.

My work sits at the intersection of:
- Machine learning rigor (leakage-aware validation, uncertainty, reproducibility)
- Biological realism (host–pathogen systems, microbiomes, immune dynamics)
- Interpretability by design (program-level features, pathway abstraction, SHAP)

Across academia, industry, and applied AI instruction, I’ve built pipelines and models that turn complex biological data— genomics, metagenomics, metatranscriptomics, scRNA-seq —into tools that drive mechanistic insight and translational decision-making.

---

# **Featured Project: Interpretable Metagenomics Classifier (BV, VVC, Healthy)**

This project builds a **transparent, explainable machine learning classifier** for distinguishing among **bacterial vaginosis (BV)**, **vulvovaginal candidiasis (VVC)**, and **healthy** vaginal microbiome states using CLR-transformed metagenomic features.

### **Highlights**

* **78.8% accuracy** with BV precision/recall up to **1.00** using XGBoost
* **PERMANOVA** shows BV explains ~13% of community variance
* **SHAP analysis** identifies stability markers (CLR_1, CLR_17, CLR_3, CLR_43) and dysbiosis drivers (CLR_14)
* **Statistically grounded workflow**: CLR features, PERMANOVA, univariate tests, multivariate modeling
* **Clinical relevance**: interpretable model supports diagnostic triage and microbial state assessment

### Why This Matters

Bacterial vaginosis disrupts the vaginal microbiome, decreasing lactobacilli and increasing anaerobes such as *Gardnerella*, *Prevotella*, *Megasphaera*, and *Sneathia*. These patterns align with findings in major sequencing studies (e.g., Macklaim et al. 2015) showing BV-associated shifts and the importance of restoring lactobacilli-dominated profiles .

This classifier provides:

* A transparent computational tool for studying dysbiosis
* A foundation for **clinical decision support** models
* A reproducible, explainable pipeline aligned with real biological signals

📁 **Repository:** https://github.com/drshanda/Vaginal_Microbiome_ML_Classifier

---

# **What’s Coming Next (High-Level Roadmap)**

## Interpretable Patient-Level Modeling of Malaria Progression from scRNA-seq

An interpretability-first framework for modeling ordered disease progression (Control → Day 0 → Day 7 → Day 28) from PBMC scRNA-seq data using immune program aggregation and strict leave-one-patient-out (LOPO) validation.

Focus

- Program-level (not gene-level) features
- Ordinal regression & ordinal random forests
- SHAP-based error analysis to diagnose immune ambiguity
- Biological validation via pseudobulk DE and pathway enrichment

---

## Phylogeny-Aware Transformer for Betacoronavirus Spike Evolution

A transformer model grounded in evolutionary theory, designed to learn how spike protein sequences evolve in relation to host switching and zoonotic emergence, while explicitly accounting for shared ancestry.

Focus

- Amino-acid–level sequence modeling
- Phylogenetic conditioning (clade embeddings, tree distance)
- Lineage-aware cross-validation
- Monte Carlo dropout for epistemic uncertainty
- Attention and mutation-level attribution

---
## Pathway-Level Modeling of Antibiotic-Induced Functional Perturbation in the Gut Metatranscriptome

An interpretable ML framework for modeling antibiotic-specific functional responses in the gut microbiome using KEGG and GO pathway activity derived from metatranscriptomic data.

Focus
- Functional abstraction over taxonomy
- Program-level ML inputs
- SHAP-based attribution of disrupted microbial processes

  
---
# **Tech Stack**

- **Python**, PyTorch, TensorFlow, scikit-learn  
- **R**, tidyverse, Shiny  
- **Bioinformatics:** genomics, scRNA-seq, metagenomics, metatranscriptomics, NGS  
- **MLOps:** MLflow, DVC, Docker
- **Explainability:** SHAP

---

# **Education**

- MS, Data Science, Eastern University — Expected August 2026
- PhD, Ecology & Evolution, Rutgers University
- MA, Anthropology, New York University
- BS, Anthropology & Sociology, Virginia Commonwealth University

---

# **Honors & Fellowships**

* **NSF Doctoral Dissertation Improvement Grant (DDIG)**
* **Smithsonian Predoctoral Fellowship**
* **NIH NRSA T32 Postdoctoral Fellowship**

---

# Publications

* *Nature Communications* — **molBV reveals immune landscape of bacterial vaginosis**
* *Microbiology Resource Announcements* — nosocomial pathogen genomes from metagenomics
* *PNAS* — molecular collections & museum standards
* *Oecologia* — primate microbiome evolution

---

# **Let’s Connect**

📧 **Email: [williams.lashandar@gmail.com](mailto:williams.lashandar@gmail.com)**  
🌐 **LinkedIn: https://www.linkedin.com/in/lashanda-williams-ph-d/**  
🌐 **GitHub: github.com/drshanda**  

