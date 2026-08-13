# Predicting Synergistic and Antagonistic Micellization Effects in Surfactant Blends for Optimized Formulation Design

**Sofía González-Núñez, Carlos Amador, Mariano Martín**

## Overview

This repository accompanies the manuscript **"Predicting Synergistic and Antagonistic Micellization Effects in Surfactant Blends for Optimized Formulation Design"** and contains the datasets, trained machine-learning models, and validation results used in the study.

Surfactant mixtures exhibit complex non-ideal interactions that strongly influence micellization behavior and formulation performance. Within **Regular Solution Theory (RST)**, these interactions are described by the interaction parameter **β**, which is traditionally obtained from experimental mixture measurements. This work presents a hybrid computational framework that combines **machine-learning prediction of β**, **thermodynamic CMC calculations using RST**, and **multi-objective optimization** for formulation screening, enabling prediction and optimization of surfactant formulations without requiring experimental mixture data.

## Repository contents

* **Curated β-interaction dataset** derived from experimental CMC measurements of binary surfactant mixtures.
* **Trained β-prediction models** (ANN, LightGBM, and XGBoost), including the corresponding model parameter files.
* **Trained pure-component CMC and SAScore prediction models**, including the corresponding model parameter files.
* **Binary-mixture validation dataset** together with end-to-end CMC predictions obtained using both **ANN-predicted β values** and the **ideal-mixing assumption (β = 0)**.
* **Ternary-mixture validation dataset** together with the corresponding end-to-end prediction results.



