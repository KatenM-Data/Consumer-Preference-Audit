# ☕ Consumer Preference Statistical Audit (A/B Testing)
**The Goal:** Utilise Inferential Statistics and probability modelling to determine which of two new product variations (Blend A or Blend B) demonstrates a statistically superior consumer preference, enabling data-driven product launching and marketing prioritisation.

---

## 1. 🎯 The Problem Statement (The Objective)
A retail chain introduced two competing coffee blends and needed to decide which one to roll out nationally. Relying on subjective feedback or "average scores" alone is risky, as a high average can often be skewed by outliers or masked by high volatility (dispersion).
*   **The Issue:** The business needed to know not just which blend scored higher, but which one was **consistently preferred** by the target demographic.
*   **The Objective:** Conduct a rigorous statistical audit to identify the "Winning Blend" and measure the consistency of consumer satisfaction.

## 2. 🧠 The Approach (What I did & Why)
I applied a two-stage analytical process using Microsoft Excel's Data Analysis Toolpak:
*   **Descriptive Audit:** Calculated the Mean, Median, and Mode for both samples. **Why:** To identify the "Central Tendency." I prioritised the **Median** for its resistance to extreme outliers.
*   **Volatility Analysis:** Measured the **Interquartile Range (IQR)** and **Standard Deviation**. **Why:** To identify which blend offered the most "stable" experience. I identified that Blend B had lower dispersion, meaning it is more likely to provide a predictable customer experience.
*   **Probability Modelling:** Applied **Poisson Distribution** logic to model customer arrival rates and used multiplication/addition rules to forecast future consumer choices.

## 3. 📊 Visual Impact & The "How" (The Proof)

### A. Hypothesis Validation Logic
I established a rigorous framework to ensure the results were not due to random chance.
![Hypothesis Logic](hypothesis_logic.png)
*How:* Defined the Null Hypothesis ($H_0$) as "No significant difference" to maintain an unbiased baseline before proving the Alternative ($H_1$).

### B. Performance & Dispersion Summary
This audit table compares the raw performance of both blends, highlighting that Blend B has both a higher average and lower dispersion.
![Statistical Summary](stats_summary.png)
*How:* Utilised `=STDEV.S` and `=MEDIAN` functions to contrast the 7.22 average of Blend A against the superior 8.01 of Blend B.

## 4. 💡 Strategic Recommendations & ROI Roadmap
Based on the validated data, I have proposed two strategic solutions to maximise business performance:

### Solution 1: Market Prioritisation (The Winning Bet)
*   **The Data:** Blend B achieved a higher average satisfaction score (8.01) and showed much tighter consistency in customer feedback (meaning the scores were more closely grouped together).
*   **The Action:** Focus the national launch entirely on **Blend B**.
*   **The ROI:** Higher customer retention. Because the data proves Blend B provides a more "stable" and "predictable" experience, the business reduces the risk of negative customer reviews and increases the likelihood of repeat purchases.

### Solution 2: Operational Efficiency (Supply Chain Simplification)
*   **The Data:** Probability analysis (**$P=0.9$**) proves that 90% of the target market is already satisfied by these two options.
*   **The Action:** Cancel the production of Blend A and reallocate that budget to double the marketing intensity for Blend B.
*   **The ROI:** By choosing only the most popular and consistent blend, the business avoids **unnecessary inventory clutter**. This saves the cost of managing, packaging, and storing two different products that serve the same purpose, allowing the company to focus all its resources on the "Winning" product for a higher profit margin.

---

## 5. 🧬 The Technical Deep-Dive
*   **Tool:** Microsoft Excel (Data Analysis Toolpak).
*   **Key Statistical Methods:** Two-Sample T-Tests, Probability Rules (Independent & Mutually Exclusive events), Normal Distribution, and Poisson Distribution.
*   **Best Practice:** Implemented strict spreadsheet integrity by labelling all variables and separating raw data from calculation cells.

---

## 6. 🏆 Project Impact & Core Competencies
This project successfully moved the product strategy from "Guesswork" to **"Mathematical Certainty,"** demonstrating the following technical and strategic competencies:
*   **Statistical Fluency:** Proven ability to differentiate between Mean, Median, and Mode to identify the "True" trend.
*   **Risk Mitigation:** Used Standard Deviation and IQR to measure and reduce business volatility.
*   **Commercial Logic:** Ability to translate abstract $p$-values and probabilities into actionable inventory and marketing decisions.

## 7. ⚙️ Setup & Reproduction
1. Download the `Statistical_Analysis_Katen.xlsx` file.
2. Review the **Summary Statistics** tab to see the formulaic links.
3. Raw data is available in the first two columns for independent verification.

---
*This project was completed as part of the Professional Certificate in Data Analytics & AI (Code Institute).*
