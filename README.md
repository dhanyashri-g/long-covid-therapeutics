# 🧬 GPCR-Targeted Therapeutics for Long COVID  
_A Comprehensive Bioinformatics Study_

---

## 🧠 Project Overview

Long COVID, or post-acute sequelae of SARS-CoV-2 infection (PASC), is a chronic condition with lingering symptoms such as fatigue, neurological impairments, and respiratory issues. Current treatment options are limited. This study explores the role of **GPCRs**, a major class of druggable cell-surface receptors, as potential therapeutic targets. The project integrates multiple bioinformatics approaches to:

- Identify GPCRs associated with long COVID genes
- Analyze sequence/function/network relationships
- Simulate molecular interactions
- Suggest possible FDA-approved or repurposed drugs

---

## 🎯 Research Objectives

- **Functional Mapping**: Identify long COVID-related genes with GPCR involvement
- **Network Analysis**: Prioritize key GPCR targets using Cytoscape & STRING
- **Docking Simulations**: Perform ligand–receptor docking for interaction affinity
- **Drug Repurposing**: Highlight potential treatments from known drugs

---

## 🧪 Tools & Platforms Used

| Tool/Database        | Purpose                                         |
|----------------------|-------------------------------------------------|
| **ToppGene / DAVID** | Functional enrichment, similarity analysis     |
| **EMBOSS / BLAST**   | Sequence alignment and comparison              |
| **STRING**           | Protein-protein interaction network generation |
| **Cytoscape + CytoHubba** | Network ranking & hub identification     |
| **PPA-Pred**         | Protein-protein affinity docking               |
| **PyRx**             | Ligand-receptor docking simulation             |
| **Swiss-Model / PDB**| Structure modeling and retrieval               |
| **UCSF Chimera**     | 3D visualization of structures                 |
| **DrugBank / PubChem** | Drug annotation and repurposing info         |

![ToppGene](https://img.shields.io/badge/ToppGene-Enrichment-blue)
![DAVID](https://img.shields.io/badge/DAVID-Annotation-success)
![EMBOSS](https://img.shields.io/badge/EMBOSS-BioTools-orange)
![BLAST](https://img.shields.io/badge/BLAST-Alignment-lightblue)
![STRING](https://img.shields.io/badge/STRING-PPI-yellow)
![Cytoscape](https://img.shields.io/badge/Cytoscape-Network-green)
![CytoHubba](https://img.shields.io/badge/CytoHubba-HubFinder-lightgrey)
![PPA-Pred](https://img.shields.io/badge/PPA--Pred-Docking-purple)
![PyRx](https://img.shields.io/badge/PyRx-VirtualDocking-lightblue)
![SwissModel](https://img.shields.io/badge/Swiss--Model-HomologyModeling-pink)
![PDB](https://img.shields.io/badge/PDB-Structures-darkgreen)
![Chimera](https://img.shields.io/badge/Chimera-3DViewer-blue)
![DrugBank](https://img.shields.io/badge/DrugBank-Database-red)
![PubChem](https://img.shields.io/badge/PubChem-ChemicalDB-lightgrey)

---

## 🔬 Key Findings

This study led to the identification of **21 GPCR-associated genes** through functional enrichment, sequence alignment, protein-protein affinity prediction, and docking simulations. These genes were analyzed in connection to long COVID symptoms and their potential as therapeutic targets.

### 🧠 1. Top Candidate Genes

- **HRAS, KRAS, GNAQ, and GNA11** were consistently identified across multiple analyses.
- These genes are involved in immune signaling, neurological processes, and cellular communication—core systems disrupted in Long COVID.

### 💊 2. Repurposed FDA-Approved Drugs Identified

| Gene     | Associated Symptoms                         | Suggested Drugs                     |
|----------|----------------------------------------------|--------------------------------------|
| **GNAQ** | Venous thrombosis, pulmonary embolism        | Verteporfin, Selumetinib             |
| **GNA11**| Ocular pain, alopecia                        | Binimetinib, Cabozantinib, Selumetinib |
| **KRAS** | Fatigue, GI issues, autoimmunity             | Panitumumab, Cetuximab, Adagrasib, Sotorasib |
| **PRKACA** | Memory impairment, mania, alopecia        | (Limited repurposing data)           |

- Additional promising candidates: **Naltrexone**, **Tipifarnib**

### 🔬 3. Docking Results

- Strong binding affinities (e.g., –9.6 kcal/mol for GNAQ–CAMKK1)
- RMSD values of **0.0** suggest highly stable receptor-ligand complexes
- High-confidence docking pairs:
  - GNAQ – CAMKK1
  - PRKACA – PRKACB
  - CAMK2A – CAMK2B

### 🧬 4. Gene-Symptom Mapping

- 12 of the 21 genes were mapped to Long COVID symptoms
  - **HRAS**: Sleep apnea, reflux, alopecia  
  - **KRAS**: Fatigue, edema, abdominal pain  
  - **PRKAR1A**: Irregular menstruation, neuropsychiatric impairment

### 🌐 5. Network & Enrichment Analysis

- Cytoscape MCC analysis ranked GNA11 and GNAQ as key hub genes
- Functional pathways enriched include:
  - GPCR signaling
  - Immune regulation
  - Neurological pathways

### 🧩 6. Novel Targets

- Genes like GNA15, GNAT3, PRKCA lack known symptom/drug links—suggesting novel research opportunities

---

## ✅ Conclusion & Future Work

This research project offers a comprehensive investigation into the therapeutic potential of G Protein-Coupled Receptors (GPCRs) in managing Long COVID. Through integrated computational approaches, it identified and prioritized 21 GPCR genes as potential therapeutic targets.

### 🎯 Key Conclusions

- GPCR genes including **HRAS, KRAS, GNAQ, GNA11** were consistently highlighted
- Repurposed drugs such as **Naltrexone**, **Tipifarnib**, **Sotorasib**, and **Cabozantinib** showed strong therapeutic relevance
- The role of GPCRs in immune, neurological, and vascular systems underscores their importance in long COVID

### 🧪 Challenges and Limitations

- Reliance on in silico methods; experimental confirmation is pending
- Default parameter limitations may have excluded borderline results
- Correlation ≠ causation; findings are hypothesis-generating

### 🔭 Future Work

- **Experimental validation** via in vitro/in vivo studies
- **Biased ligand design** for selective GPCR targeting
- Exploration of **autoantibody neutralization** strategies
- Incorporating **patient-specific genetic data** for personalized therapy
- Initiating **clinical trials** for top drug candidates

---

## 📸 Visuals & Figures

- **Protein interaction networks**
- **Top docking poses and 3D binding visualizations**
- **Affinity score charts and heatmaps**

> All figures are available in the `/Figures/` directory.

---

## 📘 Reference

> **Title**: Exploring G-Protein Coupled Receptor (GPCR) as Therapeutic Application of Long COVID  
> **Author**: Dhanyashri A/P Guruparan  
> **Institution**: Management & Science University (MSU), Malaysia  
> **Submitted**: 2024

📄 Full Report: [`manuscript_LongCovid_Therapeutics.pdf`]

---

## 📌 How to Use

1. Browse the folders to explore materials by category (network, docking, simulation).
2. Open any `.pdb` or `.pdbqt` files in **UCSF Chimera** or **PyRx** to view 3D structures.
3. View CSV/Excel files in `Docking_PPA-Pred` or `Docking_Simulation` for result summaries.
4. Use the README to understand the logic behind each experiment.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE). For academic use only.

---

## 💡 Future Work

- Validation of docking predictions via **wet-lab experiments**
- Expansion to other receptor families (e.g., kinases)
- Multi-drug synergy simulations for combination therapy

---

| This work is original and solely belongs to the author (Dhanyashri) and MSU. All materials and results are intended for academic and non-commercial research purposes only.


