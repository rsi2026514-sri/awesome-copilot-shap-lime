# Tools and Libraries

This section lists tools and Python libraries that can be used to implement, analyze, and compare explainability methods such as SHAP and LIME.

## 1. SHAP

* **Name:** SHAP (SHapley Additive exPlanations)
* **Type:** Python explainability library
* **Purpose:** Explains the output of machine-learning models using Shapley-value-based methods.
* **Key capabilities:** SHAP provides explainers for tree-based models, linear models, neural networks, and model-agnostic applications.
* **Relevance to this project:** SHAP is one of the two primary explainability methods being compared in this project.
* **Installation:** `pip install shap`
* **Official documentation:** https://shap.readthedocs.io/
* **GitHub:** https://github.com/shap/shap

SHAP's official documentation describes it as a game-theoretic approach for explaining machine-learning model outputs.

---

## 2. LIME

* **Name:** LIME (Local Interpretable Model-agnostic Explanations)
* **Type:** Python explainability library
* **Purpose:** Generates local explanations for individual predictions made by machine-learning models.
* **Key capabilities:** LIME can be used with different types of models and supports explanation of tabular, text, and image data.
* **Relevance to this project:** LIME is the second primary explainability method being compared against SHAP and AI-generated explanations.
* **Installation:** `pip install lime`
* **Official documentation:** https://lime.readthedocs.io/
* **GitHub:** https://github.com/marcotcr/lime

The official LIME documentation provides guidance on setting up models, generating explanations, and working with LIME outputs.

---

## 3. Scikit-learn

* **Name:** scikit-learn
* **Type:** Python machine-learning library
* **Purpose:** Provides tools for building, training, evaluating, and preprocessing machine-learning models.
* **Key capabilities:** Classification, regression, clustering, preprocessing, feature selection, model selection, and model evaluation.
* **Relevance to this project:** It can be used to train baseline machine-learning models on the selected datasets before applying SHAP and LIME.
* **Installation:** `pip install scikit-learn`
* **Official documentation:** https://scikit-learn.org/
* **GitHub:** https://github.com/scikit-learn/scikit-learn

Scikit-learn provides supervised and unsupervised learning algorithms as well as preprocessing, model selection, and evaluation utilities.

---

## 4. InterpretML

* **Name:** InterpretML
* **Type:** Python interpretability toolkit
* **Purpose:** Provides tools for training interpretable models and explaining existing machine-learning models.
* **Key capabilities:** Supports glass-box models as well as explanations for black-box machine-learning pipelines.
* **Relevance to this project:** It provides an additional explainability framework that can be used to understand and compare different explanation approaches.
* **Installation:** `pip install interpret`
* **Official documentation:** https://interpret.ml/
* **GitHub:** https://github.com/interpretml/interpret

InterpretML's official documentation describes support for both interpretable models and explanations of existing black-box ML pipelines.

---

## 5. Alibi

* **Name:** Alibi
* **Type:** Python machine-learning explainability library
* **Purpose:** Provides algorithms for explaining, evaluating, and interpreting machine-learning models.
* **Key capabilities:** Supports several explainability techniques for different types of machine-learning problems.
* **Relevance to this project:** Alibi can provide additional explanation methods that can be used as a comparison point when evaluating SHAP, LIME, and AI-generated explanations.
* **Installation:** `pip install alibi`
* **Official documentation:** https://docs.seldon.ai/alibi/
* **GitHub:** https://github.com/SeldonIO/alibi

---

## Suggested Experimental Workflow

The tools can be combined into the following workflow:

1. Select one of the datasets listed in `datasets/datasets.md`.
2. Use **scikit-learn** to preprocess the data and train a machine-learning model.
3. Use **SHAP** to generate feature-attribution explanations.
4. Use **LIME** to generate local explanations for the same predictions.
5. Use **InterpretML** or **Alibi** for additional explainability analysis.
6. Compare the resulting explanations with explanations produced by an AI Copilot.
7. Evaluate differences in important features, explanation consistency, and interpretability.
