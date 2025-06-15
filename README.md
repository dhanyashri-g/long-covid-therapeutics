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


---

## 🧬 Key Findings

- **21 GPCR-associated genes** identified, including _HRAS_, _KRAS_, _GNAQ_, _GNA11_
- **Top-ranked therapeutic candidates** included drugs like:
  - ✅ Naltrexone  
  - ✅ Tipifarnib  
  - ✅ Cabozantinib  
  - ✅ Sotorasib  
- **Network analysis** with Cytoscape highlighted critical GPCRs via Maximal Clique Centrality (MCC).
- **Docking simulations** revealed high-affinity interactions supporting therapeutic potential.

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

 The work is original and solely belongs to the author (Dhanyashri) and MSU. All materials and results are intended for academic and non-commercial research purposes only.


