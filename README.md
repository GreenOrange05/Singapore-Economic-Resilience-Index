# The Singapore Efficiency Paradox: Structural Divergence & The J-Curve (2014-2024)

> *"Efficiency is the vaccine, but liquidity is the antibody. Without the latter, the patient may not survive the cure."*

![J-Curve Findings](images/Figure3_JCurve.png)


## 📄 Project Overview
**Can a country be "too efficient" for its own good?**
This Capstone Project challenges the "Smart Nation" mandate by analyzing 10 years of sectoral data (2014-2024). Using a custom **Economic Resilience Index (ERI)**, I uncovered the **"Efficiency Curse"**: the counter-intuitive finding that rapid digital transformation *lowers* economic resilience in labor-intensive sectors for up to 2 years before benefits materialize.

### 📥 Read the Full Paper
[**Click here to view the Executive Report (PDF)**](./THE_EFFICIENCY_PARADOX.pdf)

## 📊 Key Findings (The "Singapore Paradox")
1.  **The Twin Test:** Standard economic metrics (Volatility/GDP) mask risk. My robust **Semi-Deviation Index (V2)** revealed hidden fragility in high-growth sectors.
2.  **Structural Divergence:** Tech adoption correlates *positively* with resilience in Finance but *negatively* in Construction ($r = -0.15$).
3.  **The J-Curve:** We proved a "Valley of Death" timeline. Resilience drops by **18%** in Year 1 (The Fever) before rising **22%** in Year 3 (The Immunity).

## 🛠️ Repository Structure
This analysis is broken into modular notebooks for reproducibility:

* **`01_Data_Prep.ipynb`**: Cleaning SingStat/MOM macro-data and handling missing time-series values.
* **`02_ERI_Construction.ipynb`**: Building the Index. Comparisons of Arithmetic vs. Geometric Means.
* **`03_Modeling_JCurve.ipynb`**: The core econometric engine (Fixed Effects Panel Regression).
* **`04_Visualizations.ipynb`**: Generating the Twin Test and Diagnostic Plots.
* **`05_Policy_Simulation.ipynb`**: The "Transition Trap" simulation model (Figure 4) demonstrating the liquidity risks of digitalization.

## 🚀 How to Run
(Instructions for future users)
1. Clone the repo.
2. Run notebooks `01` through `05` in order.
