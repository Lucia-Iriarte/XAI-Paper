# Explainable Toxicity Prediction Through XAI and LLMs

This repository contains the materials associated with the research project:

**"Explainable Toxicity Prediction Through XAI and LLMs"**

developed as part of the **Iniciación a la Investigación 2026** program at the **Universidad Católica del Uruguay (UCU)**.

## Project Overview

Machine Learning models can accurately predict molecular toxicity, but their decisions are often difficult to interpret. This project investigates the use of Explainable Artificial Intelligence (XAI) techniques—specifically **SHAP** and **LIME**—combined with a consensus strategy and a Large Language Model (LLM) acting as a communication layer.

The objective is to evaluate whether LLM-generated narratives can communicate XAI evidence while preserving the information provided by the explainability methods.

## Repository Contents

* `XAI-Paper.pdf` – Full research paper.
* `Poster.pdf` – Scientific poster presented at Iniciación a la Investigación 2026.

## Methodology

1. Train supervised machine learning models on a molecular toxicity dataset.
2. Select the best-performing models according to F1-score.
3. Generate local explanations using SHAP and LIME.
4. Build a consensus representation of feature importance.
5. Generate natural-language explanations using an LLM.
6. Evaluate fidelity, factuality, and hallucination rates.

## Authors

* Lucía Iriarte
* Magdalena Cabrera
* Fiorella Cravero
* Gustavo E. Vazquez

Department of Computer Science and Artificial Intelligence
Universidad Católica del Uruguay
