#  **Hi, I'm LaShanda R. Williams, PhD**

I am an AI/ML bioinformatics scientist with a background in computational biology, microbial ecology, and infectious disease genomics, focused on building interpretable, biologically grounded machine learning models for high-stakes biological data.

My work sits at the intersection of:
- Machine learning rigor (leakage-aware validation, uncertainty, reproducibility)
- Biological realism (host–pathogen systems, microbiomes, immune dynamics)
- Interpretability by design (program-level features, pathway abstraction, SHAP)

Across academia, industry, and applied AI instruction, I’ve built pipelines and models that turn complex biological data into tools that drive mechanistic insight and translational decision-making.

---

# **Featured Projects**

## Interpretable Metagenomics Classifier (BV, VVC, Healthy)

This project builds a transparent, explainable machine learning classifier for distinguishing among bacterial vaginosis (BV), vulvovaginal candidiasis (VVC), and healthy vaginal microbiome states using CLR-transformed metagenomic features.

### Highlights

* 78.8% accuracy with BV precision/recall up to 1.00 using XGBoost
* PERMANOVA shows BV explains ~13% of community variance
* SHAP analysis identifies stability markers (CLR_1, CLR_17, CLR_3, CLR_43) and dysbiosis drivers (CLR_14)
* Statistically grounded workflow: CLR features, PERMANOVA, univariate tests, multivariate modeling
* Clinical relevance: interpretable model supports diagnostic triage and microbial state assessment

### Why This Matters

Bacterial vaginosis disrupts the vaginal microbiome, decreasing lactobacilli and increasing anaerobes such as *Gardnerella*, *Prevotella*, *Megasphaera*, and *Sneathia*. These patterns align with findings in major sequencing studies (e.g., Macklaim et al. 2015) showing BV-associated shifts and the importance of restoring lactobacilli-dominated profiles .

This classifier provides:

* A transparent computational tool for studying dysbiosis
* A foundation for **clinical decision support** models
* A reproducible, explainable pipeline aligned with real biological signals

📁 **Repository:** https://github.com/drshanda/Vaginal_Microbiome_ML_Classifier

---

## HostScope — Interpretable Immune Recovery Modeling from scRNA-seq

This project develops an interpretable, patient-level machine learning framework to model immune recovery following malaria infection using PBMC scRNA-seq data, prioritizing biological interpretability, patient-aware validation, and reproducibility.

### Highlights

- Balanced accuracy 0.70 under strict leave-one-patient-out (LOPO) validation
- Ordinal logistic regression achieves AUC = 0.86 with MAE < 0.3 stages, indicating strong recovery-stage ranking despite heterogeneous biology
- Misclassifications dominated by adjacent-stage errors, with minimal Day0 ↔ Day28 swaps
- SHAP analysis shows immune program features consistently outweigh cell-type composition in per-sample explanations (paired Wilcoxon p ≈ 8×10⁻⁶; permutation p ≈ 0.001)
- Functional enrichment (GSEA) reveals coordinated resolution of innate inflammatory programs, lymphocyte transcriptional reconstitution, platelet hemostatic normalization, and dynamic humoral remodeling


### Why This Matters

Immune recovery after infection is heterogeneous, asynchronous, and poorly captured by discrete labels or cell-level models. HostScope reframes recovery as a continuous functional process, showing that interpretable program-level modeling can capture meaningful immune trajectories while preserving uncertainty.

This project provides:

- A transparent framework for patient-level immune state modeling
- A template for interpretable scRNA-seq ML without patient leakage
- A reproducible, MLOps-aligned pipeline suitable for translational research

📁 **Repository**: https://github.com/drshanda/Immune_Recovery_Ordinal_Model_Malaria_scRNAseq

# **What’s Coming Next (High-Level Roadmap)**

## Pathway-Level Modeling of Antibiotic-Induced Functional Perturbation in the Gut Metatranscriptome

An interpretable ML framework for modeling antibiotic-specific functional responses in the gut microbiome using KEGG and GO pathway activity derived from metatranscriptomic data.

Focus
- Functional abstraction over taxonomy
- Program-level ML inputs
- SHAP-based attribution of disrupted microbial processes

  
---

## Interpretable Modeling of Host Translational and Cellular Stress Responses to Influenza Infection 

An interpretability-first framework for modeling host cellular stress and translational control during influenza infection using KEGG pathway–level features derived from integrated human bulk transcriptomic data.

Focus
- Host cellular machinery rather than immune signaling or clinical severity
- KEGG pathway–level abstraction of translation, ER stress, proteostasis, and metabolism
- Autoencoder-based learning of continuous host stress axes
- Mechanistic interpretation of latent dimensions via pathway contributions and decoder perturbation

---

## Interpretable Multi-View Modeling of Host Functional Execution in Omicron SARS-CoV-2 Infection

An interpretability-first deep learning framework for learning shared host execution-level representations from paired serum proteomics and metabolomics data during Omicron SARS-CoV-2 infection.

Focus
- Execution-level host response modeling across proteome and metabolome
- Multi-view contrastive representation learning to align molecular layers
- Disentangling virus-specific host biology from generic inflammatory responses
- Mechanistic interpretation of latent embeddings via pathway projection and linear probes

---

# **Tech Stack**

- **Python**, PyTorch, TensorFlow, scikit-learn  
- **R**, Bioconductor, tidyverse, Shiny  
- **Bioinformatics:** bulk RNAseq, microarray, scRNA-seq, metagenomics, metatranscriptomics, NGS  
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

* Usyk, M., et al. (2022). molBV reveals immune landscape of bacterial vaginosis and predicts human papillomavirus infection natural history. Nature Communications, 13(233): https://www.nature.com/articles/s41467-021-27628-3
* Williams, L., et al. (2020). Two nearly complete nosocomial pathogen genomes reconstructed from early-mid 20th-century dental calculus. Microbiology Resource Announcements, 9(43), e00850-20: https://journals.asm.org/doi/10.1128/mra.00850-20
* Austin, R., et al. (2019). To curate the molecular past, museums need a carefully considered set of best practices. Proceedings of the National Academy of Sciences, 116(5), 1471-1474: https://www.pnas.org/doi/10.1073/pnas.1822038116
* Amato, K., et al. (2016). Phylogenetic and ecological factors impact the gut microbiota of two Neotropical primate species. Oecologia, 180(3), 717-733: https://link.springer.com/article/10.1007/s00442-015-3507-z

---

# **Let’s Connect**

* 📧 **Email: [williams.lashandar@gmail.com](mailto:williams.lashandar@gmail.com)**  
* 🌐 **LinkedIn: https://www.linkedin.com/in/lashanda-williams-ph-d/**  
* 🌐 **GitHub: github.com/drshanda**  

