# Hi, I'm Anne!

MSc Physics student at Freie Universität Berlin and Research Assistant in the Clementi group, working at the intersection of molecular simulation, machine learning, and computational biology.

My thesis focuses on machine-learned coarse-grained models for TCR–pMHC complexes. I build computational workflows that combine molecular simulation, statistical mechanics, and machine learning to study molecular systems.

Currently finishing my MSc and looking for opportunities in scientific machine learning, computational biology, and biotech in Berlin.

---

## Featured projects

**[TCR–Peptide Ranking](https://github.com/annemcq/tcr-peptide-ranking)**  

Machine learning for ranking candidate peptides for a given TCR using sequence features and the TCRen structural potential. The project uses grouped repeated evaluation across TCRs, ranking metrics, paired statistical comparisons, and a held-out inference demo. It also investigates dataset limitations and potential negative-sampling shortcuts.

**[Machine-Learned Coarse-Grained Force Field](https://github.com/annemcq/mlcg-gnn-alanine)**  

A SchNet-style graph neural network trained by force matching to learn a coarse-grained force field for alanine dipeptide. The model combines a harmonic bonded prior with a learned GNN correction and is validated through molecular dynamics simulations. It compares physical-prior and GNN-only dynamics, focusing on conformational distributions rather than an earlier instability claim that did not reproduce. The controlled, equal-training comparison is still in progress.

**[Free Energy: MBAR & Zwanzig](https://github.com/annemcq/free-energy-mbar-zwanzig)**  

Implementation and validation of free-energy estimators based on MBAR and Zwanzig perturbation. The methods are first validated against an analytical solution and then applied to umbrella-sampling data, including bootstrap uncertainty estimation and comparison of single-step Zwanzig estimates with a multistate MBAR reference.

**[Protein Simulation Stability Analysis](https://github.com/annemcq/protein-simulation-stability-analysis)**  

Interpretable machine learning for protein simulation stability using structure- and energy-based features. The project compares logistic regression and Random Forest models across repeated train/test splits, with statistical comparisons and SHAP-based feature importance. The analysis emphasizes reproducibility, model limitations, and cautious interpretation of small-data results.

**[CG Force Field API](https://github.com/annemcq/cgnet-api)**  

An interactive FastAPI + Streamlit application built around the coarse-grained force field from `mlcg-gnn-alanine`. Users can choose backbone φ/ψ angles, reconstruct a coarse-grained structure, evaluate the learned model, and explore its predicted energy landscape. [Live demo](https://annemcq-cgnet-api-streamlit-appapp-obnfhv.streamlit.app).

---

## Collaborative work



**[ADK-project](https://github.com/annemcq/ADK-project)**  

A dual-basin structure-based (Gō-like) coarse-grained model of Adenylate Kinase, developed jointly with a course partner. The stored simulation shows repeated LID closure, but does not reach full NMP closure.

---

## Technologies

**Scientific computing & simulation:**  
Python · OpenMM · MDTraj · pymbar

**Machine learning:**  
PyTorch · scikit-learn

**Scientific software:**  
FastAPI · Streamlit · Docker

---

## AI-assisted development

AI coding tools were used as part of the development process across some projects, with the resulting code, analyses, and documentation reviewed, tested, and validated.

## Get in touch

[LinkedIn](https://www.linkedin.com/in/anne-mc-quaid-bara%C3%B1ano-31a980230/) · [Email](mailto:annemcquaid@live.com)
