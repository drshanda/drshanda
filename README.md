#  **Hi, I'm LaShanda R. Williams, PhD**

### **AI/ML Bioinformatics Scientist | Deep Learning | Interpretable ML | MLOps**

I’m a scientist–engineer with 10+ years of multi-omic analytics experience, specializing in **interpretable deep learning**, **biological transformers**, and **production-grade MLOps**. My work bridges computational biology and AI to produce **transparent, clinically relevant**, and **deployable** machine learning systems.

Across academia, industry, and applied AI instruction, I’ve built pipelines and models that turn complex biological data—metagenomics, RNA-seq, scRNA-seq, and medical imaging—into tools that drive mechanistic insight and translational decision-making.

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

# **What’s Coming Next: Projects 2–5 (High-Level Roadmap)**

Spanning single-cell analysis, clinical imaging, MLOps, and transformer-based modeling, these projects together demonstrate a comprehensive, end-to-end mastery of AI/ML Bioinformatics.

---

## ** AtlasCell — Single-Cell Classifier for Automated Annotation**

A deep learning model for scRNA-seq cell type prediction with full preprocessing (QC, HVGs, PCA/UMAP).
**SHAP** will reveal gene markers aligned with canonical cell types.
Built with **MLflow** and **DVC** for fully reproducible workflows.

---

## ** BioLLM — Transformer for Predicting Cancer Regulatory Programs (TCGA-BRCA)**

An interpretable biological language model predicting hallmark oncogenic programs (proliferation, EMT, estrogen response, etc.).
Includes:

* **Integrated Gradients**
* **Attention analysis**
* **SHAP gene attributions**
* A compact transformer encoder optimized for biological structure

---

## ** Pathogenicity Risk Score Predictor (Full MLOps Pipeline)**

An **AWS SageMaker** end-to-end pipeline processing wastewater metagenomic features to predict continuous pathogenicity risk.
Features:

* Dockerized feature engineering container
* Modular SageMaker pipeline (processing → training → evaluation → registry)
* ONNX model export
* MLflow tracking and model lineage
* Drift monitoring and schema validation

---

## ** Multi-Class Chest X-ray Diagnostic Model**

A medical imaging classifier (Normal, Bacterial/Viral Pneumonia, COVID-19, TB, Emphysema) built using **EfficientNet**.
Includes:

* Full DICOM → tensor preprocessing
* **Grad-CAM** & **Integrated Gradients** for clinical interpretability
* Class-balanced training and augmentation workflow

---

# **Tech Stack**

**Python**, PyTorch, TensorFlow, scikit-learn
**R**, tidyverse, Shiny
**Bioinformatics:** RNA-seq, scRNA-seq, metagenomics, NGS
**MLOps:** AWS SageMaker, MLflow, DVC, Docker, ONNX
**Explainability:** SHAP, Grad-CAM, Integrated Gradients
**Pipelines:** Nextflow, nf-core

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

📧 **[williams.lashandar@gmail.com](mailto:williams.lashandar@gmail.com)**
🌐 **https://www.linkedin.com/in/lashanda-williams-ph-d/**
🌐 **github.com/drshanda**

