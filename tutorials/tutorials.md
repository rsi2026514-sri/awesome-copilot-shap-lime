# Tutorials and Learning Resources

A curated collection of tutorials, documentation, notebooks, and learning resources for understanding and applying explainable AI methods, especially SHAP and LIME.

---

## 1. SHAP Documentation and API Examples

**Resource:** SHAP API Examples

**Description:**
The official SHAP documentation provides API examples and Jupyter notebooks demonstrating different SHAP explainers, maskers, models, and visualization methods. It is useful for learning how to generate and interpret SHAP explanations in practical machine-learning applications.

**Topics covered:**

* SHAP explainers
* Feature attribution
* SHAP visualization
* Beeswarm plots
* Waterfall plots
* Decision plots
* Text and image explanations

**Link:**
https://shap.readthedocs.io/en/latest/api_examples.html

---

## 2. Understanding Tree SHAP for Simple Models

**Resource:** Understanding Tree SHAP for Simple Models

**Description:**
This official SHAP tutorial uses small decision-tree examples to explain how SHAP values are calculated and how individual features contribute to model predictions. It is particularly useful for understanding the intuition behind Tree SHAP.

**Topics covered:**

* SHAP values
* Feature contributions
* Tree-based models
* Expected model output
* Simple decision-tree examples
* Interaction between features

**Link:**
https://shap.readthedocs.io/en/latest/example_notebooks/tabular_examples/tree_based_models/Understanding%20Tree%20SHAP%20for%20Simple%20Models.html

---

## 3. LIME Documentation and User Manual

**Resource:** LIME Documentation

**Description:**
The official LIME documentation introduces the LIME framework and explains how to set up and use LIME for interpreting machine-learning models. It includes information about the inner workings of LIME, model functions, outputs, and configuration.

**Topics covered:**

* Introduction to LIME
* Installing and setting up LIME
* How LIME works
* Model functions
* LIME outputs
* Post-processing

**Link:**
https://lime.readthedocs.io/en/latest/

---

## 4. InterpretML Getting Started Tutorial

**Resource:** InterpretML Getting Started

**Description:**
The InterpretML getting-started guide demonstrates how to use InterpretML for interpretable machine learning and explaining existing black-box ML pipelines. The tutorial uses the UCI Adult Income dataset and provides a practical introduction to explainability.

**Topics covered:**

* Installing InterpretML
* Loading datasets
* Training interpretable models
* Explaining black-box models
* Model interpretability
* Practical XAI workflow

**Link:**
https://interpret.ml/docs/index.html

---

## 5. Scikit-learn Model Inspection Guide

**Resource:** Scikit-learn Inspection Guide

**Description:**
The scikit-learn inspection guide provides practical methods for understanding model behavior. It covers techniques such as Partial Dependence Plots (PDP), Individual Conditional Expectation (ICE), and permutation feature importance. These methods can be used alongside SHAP and LIME when comparing different explainability approaches.

**Topics covered:**

* Model inspection
* Partial Dependence Plots
* Individual Conditional Expectation
* Permutation feature importance
* Feature contribution analysis
* Model debugging and interpretation

**Link:**
https://scikit-learn.org/stable/inspection.html

---

## How These Resources Support This Repository

These resources provide complementary approaches for studying explainable AI:

| Resource                | Main Focus                              | Relevance   |
| ----------------------- | --------------------------------------- | ----------- |
| SHAP API Examples       | SHAP explanations and visualizations    | High        |
| Tree SHAP Tutorial      | Understanding SHAP values               | High        |
| LIME Documentation      | Local model explanations                | High        |
| InterpretML             | Practical interpretable ML              | High        |
| Scikit-learn Inspection | Model inspection and feature importance | Medium–High |

Together, these resources help researchers understand how different explainability techniques work and provide practical foundations for comparing explanations produced by AI-assisted systems with explanations generated using SHAP and LIME.

## Suggested Learning Sequence

1. Start with the **LIME Documentation** to understand local surrogate explanations.
2. Study the **SHAP API Examples** to understand SHAP explainers and visualizations.
3. Read **Understanding Tree SHAP for Simple Models** to develop intuition about SHAP values.
4. Complete the **InterpretML Getting Started** tutorial for practical XAI experience.
5. Use the **Scikit-learn Inspection Guide** to understand complementary model-inspection techniques.

These resources can be used as practical learning material before conducting experiments comparing AI Copilot explanations with manual SHAP/LIME analysis.
