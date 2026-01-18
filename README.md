# The Gender Flip and the Boy Child Crisis: A Big Data Analysis of NW/SW Cameroon

## 📊 Project Overview
This project investigates the historical transformation of educational attainment in the North West and South West (NW/SW) regions of Cameroon. By harmonizing multiple survey rounds, I track educational "velocity" across 50 years of birth cohorts to uncover a historic shift in gender dynamics and a modern generational collapse among young males.

### 🔍 Key Discoveries
*   **The Gender Flip (1996):** My model identifies 1996 as the historic "crossover" year. Women born after 1996 (aged 28 and younger) are now statistically more likely to hold a degree than their male peers.
*   **The Boy Child Crisis:** I have documented a sharp "velocity collapse" in male education. Young men born in the "Crisis Impact Zone" (1998–2008) show a likelihood of degree attainment that has regressed to 1960s-era levels.
*   **The Digital Life-Jacket:** Internet access emerged as the #1 predictor of educational survival. In conflict-affected zones, digital connectivity acts as a primary bypass for physical school boycotts.

---

## 🛠 Technical Stack & Methodology
This project follows the **Data Analytics Life Cycle**, moving from raw data harmonization to actionable policy simulations.

*   **Data Source:** Multi-round longitudinal data from Afrobarometer (R7, R8, R9, R10).
*   **Engine:** Python 3.10 with `Statsmodels` (sm.Logit) for rigorous statistical inference.
*   **Modeling:** Polynomial Logistic Regression (2nd Degree) to capture non-linear "Rise and Fall" trends.
*   **Optimization:** Implementated **Threshold Tuning** (re-calibrating to the natural mean of 0.27) to boost model sensitivity (Recall) by **71.9%**.
*   **Partitioning:** Industrial-standard 80/20 Train-Test split via `Scikit-Learn` for validation.

---

## 📈 Visual Highlights
### 1. The Generational Crossover
The hero visualization of this project shows the curved probability of degree attainment, pinpointing the exact "Flip Age" where women took the lead.

### 2. Policy Swing Range
I used the model to simulate seven socio-economic scenarios. The results prove a **50-percentage-point "swing range"** between total systemic collapse and digital-economic transformation.

---

## 🚀 How to Run
1. Clone this repository.
2. Ensure you have the datasets in the `/data` folder.
3. Install dependencies:
   ```bash
   pip install pandas seaborn statsmodels scikit-learn
