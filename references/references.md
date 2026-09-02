# Scholarly References

This section contains verified scholarly references related to
AI Copilot explanations, Explainable AI, SHAP, LIME, and
comparative evaluation of explanation methods.

## 1. SHAP — Foundational Work

### 1. A Unified Approach to Interpreting Model Predictions

**Authors:** Scott M. Lundberg and Su-In Lee  
**Year:** 2017  
**Venue:** Advances in Neural Information Processing Systems (NeurIPS 2017)  
**Topic:** SHAP / Explainable AI  

**Relevance:** This is the foundational SHAP paper. It introduces
SHAP (SHapley Additive exPlanations) as a unified framework for
assigning feature-importance values to individual predictions.

**Link:** https://papers.neurips.cc/paper_files/paper/2017/hash/8a20a8621978632d76c43dfd28b67767-Abstract.html

---

## 2. LIME — Foundational Work

### 2. "Why Should I Trust You?" Explaining the Predictions of Any Classifier

**Authors:** Marco Tulio Ribeiro, Sameer Singh, and Carlos Guestrin  
**Year:** 2016  
**Venue:** Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining  
**Topic:** LIME / Explainable AI  

**Relevance:** This is the foundational LIME paper. It introduces
Local Interpretable Model-agnostic Explanations (LIME), which explains
individual predictions by learning an interpretable model locally
around the prediction.

**DOI:** https://doi.org/10.1145/2939672.2939778

---

## 3. SHAP for Tree-Based Models

### 3. Consistent Feature Attribution for Tree Ensembles

**Authors:** Scott M. Lundberg and Su-In Lee  
**Year:** 2017  
**Topic:** SHAP / Feature Attribution / Tree Models  

**Relevance:** This work develops efficient SHAP-based feature
attribution methods for tree ensemble models and addresses
inconsistencies in existing feature-importance approaches.

**Link:** https://arxiv.org/abs/1706.06060

---

## 4. Evaluating Explainable AI

### 4. From Anecdotal Evidence to Quantitative Evaluation Methods: A Systematic Review on Evaluating Explainable AI

**Authors:** Menno Nauta et al.  
**Year:** 2023  
**Venue:** ACM Computing Surveys  
**Topic:** XAI Evaluation  

**Relevance:** This systematic review is important for this project
because our research compares different explanation outputs. It
provides a broader view of how explainability methods can be
quantitatively evaluated.

**DOI:** https://doi.org/10.1145/3583558

---

## 5. A Unified Framework for Model Explanations

### 5. Explaining by Removing: A Unified Framework for Model Explanation

**Authors:** S. M. Lundberg, G. Erion, H. Chen, A. DeGrave, J. M. Prutkin, B. Nair, R. Katz, J. Himmelfarb, N. Bansal, and S.-I. Lee  
**Year:** 2020  
**Topic:** Model Explanation / Feature Attribution / XAI  

**Relevance:** This work provides a framework for understanding
different model-explanation methods through feature removal and
helps place methods such as LIME and SHAP within a common
explanation framework.

**Link:** https://jmlr.csail.mit.edu/papers/volume22/20-1316/20-1316.pdf
---

## 6. SHAP and LIME Comparison

### 6. A Perspective on Explainable Artificial Intelligence Methods: SHAP and LIME

**Authors:** Ahmed Salih, Zahra Raisi-Estabragh, Ilaria Boscolo Galazzo, Petia Radeva, Steffen E. Petersen, Gloria Menegaz, and Karim Lekadir  
**Year:** 2023  
**Topic:** SHAP vs. LIME / Explainable AI  

**Relevance:** This paper directly compares SHAP and LIME and discusses
how their explanation outputs are affected by model dependency and
feature collinearity. It is highly relevant to comparing different
explanation approaches.

**Link:** https://arxiv.org/abs/2305.02012

---

## 7. Bias and Variance of LIME and SHAP

### 7. On the Bias-Variance Characteristics of LIME and SHAP in High Sparsity Movie Recommendation Explanation Tasks

**Authors:** Claudia V. Roberts, Ehtsham Elahi, and Ashok Chandrashekar  
**Year:** 2022  
**Topic:** LIME vs. SHAP / Explanation Stability  

**Relevance:** This study evaluates LIME and SHAP on a movie
recommendation task and examines how the two methods behave under
different data sparsity conditions. It is useful for understanding
differences in the stability and reliability of their outputs.

**Link:** https://arxiv.org/abs/2206.04784

---

## 8. Unified Framework for Model Explanation

### 8. Explaining by Removing: A Unified Framework for Model Explanation

**Authors:** Ian Covert, Scott Lundberg, and Su-In Lee  
**Year:** 2021  
**Venue:** Journal of Machine Learning Research, Volume 22  
**Topic:** Model Explanation / SHAP / LIME  

**Relevance:** This work develops a unified framework for
removal-based explanations and relates multiple explanation
approaches, including SHAP and LIME. It is useful for understanding
the theoretical differences between explanation methods.

**Link:** https://www.jmlr.org/beta/papers/v22/20-1316.html

---

## 9. Disagreement Between Explainability Methods

### 9. Order in the Court: Explainable AI Methods Prone to Disagreement

**Authors:** Michael Neely, Stefan F. Schouten, Maurits J. R. Bleeker, and Ana Lucic  
**Year:** 2021  
**Topic:** Explanation Comparison / Explanation Agreement  

**Relevance:** This paper compares several explanation methods,
including LIME and SHAP-based approaches, and investigates how much
different explanation techniques agree with one another. This is
directly relevant to evaluating and comparing explanation outputs.

**Link:** https://arxiv.org/abs/2105.03287

---

## 10. Causal Shapley Values

### 10. Causal Shapley Values: Exploiting Causal Knowledge to Explain Individual Predictions of Complex Models

**Authors:** Tom Heskes, Evi Sijben, Ioan Gabriel Bucur, and Tom Claassen  
**Year:** 2020  
**Venue:** Advances in Neural Information Processing Systems 33 (NeurIPS 2020)  
**Topic:** SHAP / Causal Explainability  

**Relevance:** This paper extends Shapley-based explanations by
incorporating causal knowledge. It demonstrates an important
limitation of standard feature-attribution explanations when
features are not independent.

**Link:** https://proceedings.neurips.cc/paper_files/paper/2020/hash/32e54441e6382a7fbacbbbaf3c450059-Abstract.html
### 11. A Survey of Methods for Explaining Black Box Models

* **Authors:** Riccardo Guidotti, Anna Monreale, Salvatore Ruggieri, Franco Turini, Fosca Giannotti, Dino Pedreschi
* **Year:** 2018
* **Venue:** ACM Computing Surveys
* **Topic:** Explainable AI / Black-box Models
* **Relevance:** Provides a comprehensive survey of techniques for explaining predictions made by black-box machine-learning models. It is useful for understanding the broader explainability landscape in which methods such as LIME and SHAP are used.
* **DOI:** https://doi.org/10.1145/3236009

---

### 12. Explainable Artificial Intelligence (XAI): Concepts, Taxonomies, Opportunities and Challenges toward Responsible AI

* **Authors:** Alejandro Barredo Arrieta et al.
* **Year:** 2020
* **Venue:** Information Fusion
* **Topic:** Explainable AI / XAI Taxonomy
* **Relevance:** Presents a broad taxonomy of explainable AI methods and discusses interpretability, explainability, evaluation, and challenges associated with responsible AI.
* **DOI:** https://doi.org/10.1016/j.inffus.2019.12.012

---

### 13. A Comprehensive Taxonomy for Explainable Artificial Intelligence: A Systematic Survey of Surveys on Methods and Concepts

* **Authors:** Oliver Schwalbe and Nina Finzel
* **Year:** 2023
* **Venue:** Data Mining and Knowledge Discovery
* **Topic:** XAI Taxonomy / Explainability
* **Relevance:** Systematically organizes existing explainable-AI methods and concepts. This provides useful background for categorizing and comparing different explanation approaches.
* **DOI:** https://doi.org/10.1007/s10618-022-00867-8

---

### 14. Benchmarking and Survey of Explanation Methods for Black Box Models

* **Authors:** Various authors
* **Year:** 2023
* **Venue:** Data Mining and Knowledge Discovery
* **Topic:** Explanation Methods / Benchmarking
* **Relevance:** Examines and benchmarks explanation methods for black-box models, making it particularly relevant to comparing the behavior and quality of different explanation techniques.
* **DOI:** https://doi.org/10.1007/s10618-023-00933-9

---

### 15. Explaining Individual Predictions When Features Are Dependent: More Accurate Approximations to Shapley Values

* **Authors:** Aas, K.; Jullum, M.; Løland, A.
* **Year:** 2021
* **Venue:** Artificial Intelligence
* **Topic:** SHAP / Dependent Features
* **Relevance:** Investigates how feature dependence affects SHAP explanations and proposes more accurate approaches for estimating Shapley values when input features are dependent.
* **Volume:** 298
* **Article:** 103502
* **DOI:** https://doi.org/10.1016/j.artint.2021.103502

