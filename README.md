# A/B Testing: Mobile App UI Redesign

This project demonstrates an analysis of A/B test results for a **Mobile App**. We tested two different versions of the app's main screen to see which one performs better. The initial version of a screen offers users to buy a subscription for $4,99 (**Variant A**). While the alternative screen allows them to buy a subscription for $4,99 but with the 50% sale (**Variant B**).

### Project Goal

The primary goal of this analysis was to test the hypothesis that a redesigned interface (**Variant B**) would lead to a statistically significant increase in user engagement and subscription rates compared to the original design (**Variant A**).

### Analysis Tasks
1.  **Hypothesis Testing:** Using statistical method (permutation test) to compare key metrics - conversion.
2.  **Conclusion & Recommendations:** Providing data-backed recommendations on whether to roll out the new interface.

---

### Technologies Used

* **Language:** Python
* **Libraries:** `pandas`, `numpy`, `scipy.stats`, `matplotlib.pyplot`, `seaborn`
* **Environment:** Jupyter Notebook

---

### Project Outcomes

The analysis showed that **Variant B** resulted in a **2.8 percentage points increase in conversion**. These results were found to be statistically significant, leading to the recommendation to fully implement the new interface.

---

### How to Run This Analysis

1.  Clone the repository:
    git clone https://github.com/OlenaRyzuk/Data-Analyst-Portfolio.git
2.  Install dependencies:
    `pip install -r requirements.txt`
3.  Launch Jupyter Notebook and open the `notebooks/yoga_app_ab_test_analysis.ipynb` file.

---
