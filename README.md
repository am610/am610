<p align="center">
  <a href="https://github.com/am610">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=2F80ED&center=true&vCenter=true&width=800&lines=Applied+ML+%2F+Scientific+ML+Researcher;Time-Series+ML+%C2%B7+Uncertainty+Quantification+%C2%B7+Simulation-Based+Inference;PyTorch+%7C+TensorFlow+%7C+JAX+%7C+Python" alt="Typing SVG" />
  </a>
</p>

# Ayan Mitra

Applied machine-learning scientist and research software engineer. I build and evaluate neural
models for noisy, high-dimensional scientific time series and imaging data — with a focus on
**distribution shift, uncertainty quantification, and simulation-based inference** — and ship them
as reproducible pipelines, not just notebooks.

Background: PhD in astrophysics (supernova cosmology, LSST/DESC pipelines). Currently applying
that research experience to general applied-ML problems: time-series classification, computer
vision, and probabilistic ML.

- 📄 Publications: [arXiv listing](https://arxiv.org/search/?searchtype=author&query=Mitra%2C+A) · [ADS library](https://ui.adsabs.harvard.edu/user/libraries/LiNzugQqT8O3JaIcS3XMeQ)
- 💼 [LinkedIn](https://www.linkedin.com/in/ayan-mitra-supernova/)
- ✉️ ayan@illinois.edu
- 🔭 Currently: LSST Time-Domain Pipeline (NCSA / DESC), open to applied-ML / ML-engineering roles

---

## Major open-source contribution — SNANA

[**SNANA**](https://github.com/RickKessler/SNANA) is the supernova simulation, light-curve fitting,
and time-domain analysis package used across the Rubin Observatory LSST Dark Energy Science
Collaboration and prior DES/SDSS-era SN cosmology surveys — facility software, not a personal
project, used and validated by a large external collaboration. I'm its **2nd-largest contributor by code volume**, 

| | Lines changed (all-time) | Merged PRs | Rank |
|---|---|---|---|
| **am610** | **181,032** | **74** | **#2 of 28 contributors** |
| Lead maintainer (RickKessler) | 2,693,737 | — | #1 |
| #3 contributor | 60,808 | — | #3 |

Representative contributions:
- Generalized spline-interpolation library, wired into photo-z quantile and log-mass-vs-redshift
  estimation — [#1664](https://github.com/RickKessler/SNANA/pull/1664), [#1669](https://github.com/RickKessler/SNANA/pull/1669)
- Data-driven host-galaxy weighting (`WGTMAP`) modes for simulation realism — [#1632](https://github.com/RickKessler/SNANA/pull/1632)
- DiffSky host-galaxy catalog integration pipeline (magnitude joins, dedup, HDF5→pandas conversion) — [#1640](https://github.com/RickKessler/SNANA/pull/1640), [#1704](https://github.com/RickKessler/SNANA/pull/1704), [#1728](https://github.com/RickKessler/SNANA/pull/1728)
- Core-collapse-supernova contamination prior implementation — [#1524](https://github.com/RickKessler/SNANA/pull/1524), [#1534](https://github.com/RickKessler/SNANA/pull/1534)

[**Full contribution history →**](https://github.com/RickKessler/SNANA/pulls?q=is%3Apr+author%3Aam610) · [**Contributor graph →**](https://github.com/RickKessler/SNANA/graphs/contributors)

---

## Flagship projects

| Project | What it shows | Stack |
|---|---|---|
| [**GWCCSN_EOS_Ye**](https://github.com/am610/GWCCSN_EOS_Ye) 🟢 *(live demo)* | 1D-CNN classifying nuclear equation-of-state from gravitational-wave time series — real dataset included, `python train.py && python app.py` gets you a working local demo (86.5% held-out accuracy, honestly reported) ([arXiv:2310.15649](https://arxiv.org/abs/2310.15649)) | TensorFlow, scikit-learn, Gradio |
| [**Firecrown_wrapper_TD**](https://github.com/am610/Firecrown_wrapper_TD) | Production-style Python pipeline orchestrating Firecrown + CosmoSIS for supernova time-domain cosmology inference — CLI, tests, SACC I/O, MIT-licensed | Python, pytest, SACC |
| [**scone_tools**](https://github.com/am610/scone_tools) | Data-product and heatmap generation utilities supporting neural supernova classification (SCONE) | Python |
| [**DeepFake**](https://github.com/am610/DeepFake) | End-to-end deep-learning video-classification pipeline (face extraction → Inception-ResNet-v2 classifier) — being audited for split leakage and video-level metrics | PyTorch/Keras, OpenCV, dlib |
| [**nnogada**](https://github.com/am610/nnogada) *(fork, with I. Gómez-Vargas)* | Genetic-algorithm hyperparameter search used to train the uncertainty-aware neural regressor in my first-author dark-energy paper ([arXiv:2402.18124](https://arxiv.org/abs/2402.18124)) | Python, TensorFlow/PyTorch, DEAP |

---

## Selected publications (ML-relevant)

- **[arXiv:2310.15649](https://arxiv.org/abs/2310.15649)** *(first author)* — 1D CNN classification of nuclear equation-of-state from core-collapse-supernova gravitational-wave time series; robustness across sampling rate, signal window, and physical nuisance parameters.
- **[arXiv:2402.18124](https://arxiv.org/abs/2402.18124)** *(first author)* — Neural regression with genetic-algorithm hyperparameter search ([nnogada](https://github.com/am610/nnogada)) and Monte Carlo dropout for uncertainty-aware reconstruction of cosmological observables from simulated Rubin/LSST data.
- **[arXiv:2409.14508](https://arxiv.org/abs/2409.14508)** — Benchmarked CNNs, RNNs, and six classical ML methods (random forest, SVM, XGBoost, etc.) on gravitational-wave time-series classification; quantified performance drop under simulation-domain mismatch.
- **[arXiv:2603.11165](https://arxiv.org/abs/2603.11165)** — Simulation-based inference with conditional normalising flows + hierarchical Bayesian modelling to correct survey-selection effects in supernova cosmology (JAX / NumPyro).

*(Full list: [arXiv search](https://arxiv.org/search/?searchtype=author&query=Mitra%2C+A))*

---

## Core skills

**ML / DL:** PyTorch, TensorFlow, scikit-learn, uncertainty quantification (MC dropout, ensembles), genetic-algorithm hyperparameter optimization, simulation-based inference, normalising flows, CNNs, time-series classification
**Scientific computing:** JAX, NumPyro, HPC / batch pipelines, SNANA, CosmoSIS, Firecrown
**Engineering:** Python, Git, Docker, pytest, LaTeX, R, C#

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,pytorch,tensorflow,r,cs,docker,git,latex&theme=dark" />
  </a>
</p>
