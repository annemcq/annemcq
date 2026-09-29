# Hi, I'm Anne 👋

MSc Physics student at Freie Universität Berlin, working as a Research Assistant in the
Clementi group (computational biophysics / machine learning for molecular simulation).
Finishing a thesis on machine-learned coarse-grained models for TCR–pMHC complexes.

Looking for entry-level **Research Engineer / Machine Learning Engineer** roles (and
adjacent Project Coordinator / Operations roles) at biotech/tech companies in Berlin.

---

## 🧪 Featured projects

Every project below has automated tests (see the ✅ badge on each repo) and an honest
write-up of what worked and what didn't.

**[tcr-peptide-ranking](https://github.com/annemcq/tcr-peptide-ranking)**
Ranking candidate peptides for a given TCR using sequence features and the TCRen
structural potential — grouped repeated evaluation across 7 models, paired statistical
significance testing (Wilcoxon signed-rank, Holm-Bonferroni corrected), and a genuinely
held-out inference demo.

**[free-energy-mbar-zwanzig](https://github.com/annemcq/free-energy-mbar-zwanzig)**
Free energy estimation (MBAR and Zwanzig perturbation) validated against an analytical
solution, then applied to real umbrella-sampling data — with an honest comparison of
where single-step Zwanzig chaining diverges from a true multistate estimator.

**[protein-simulation-stability-analysis](https://github.com/annemcq/protein-simulation-stability-analysis)**
Interpretable machine learning for protein simulation stability, using structure- and
energy-based features — with repeated-evaluation significance testing (which overturned
the original single-split result: the real signal turned out to come from logistic
regression, not Random Forest) and real SHAP-based feature importance.

**[mlcg-gnn-alanine](https://github.com/annemcq/mlcg-gnn-alanine)**
A graph neural network trained by force matching to learn a coarse-grained force field
for alanine dipeptide (harmonic bonded prior + SchNet-style GNN correction) — including
an honestly-documented failure mode (a GNN with no physical prior diverges when
simulated) and what fixed it.

**[cgnet-api](https://github.com/annemcq/cgnet-api)**
Deploying the coarse-grained force field above as an interactive FastAPI + Streamlit
application — pick backbone phi/psi angles and explore the model's learned energy
landscape live.

---

## 🤝 Collaborative work

**[ADK-project](https://github.com/annemcq/ADK-project)**
A dual-basin structure-based (Gō-like) coarse-grained model of Adenylate Kinase's
open↔closed conformational transition, developed jointly with a course partner.

---

## 🛠️ Technologies

Python · PyTorch · scikit-learn · FastAPI · Streamlit · Docker · OpenMM · pymbar

## 📫 Get in touch

annemcquaid@live.com
