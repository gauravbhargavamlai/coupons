# coupons
Here’s a clean and concise `README.md` file you can upload to your GitHub repository to explain the purpose and findings of your Coffee House Coupon analysis:

---

# ☕ Coffee House Coupon Acceptance Analysis

This project explores the behavioral patterns and demographic indicators that influence the acceptance of **Coffee House coupons** using data from `coupons.csv`.

## 📌 Objective

The primary goal is to develop a **data-driven hypothesis** around who is more likely to accept Coffee House coupons based on:

* Frequency of coffee shop visits
* Age group
* Education level

## 🧪 Methodology

We segmented the dataset into the following groups:

* **Group A:** Frequent Coffee House visitors (more than once per month)
* **Group B:** Drivers under the age of 30
* **Group Not C:** Drivers who do **not** have a graduate degree (Master’s or Doctorate)

We then calculated and compared the **coupon acceptance rate (`Y`)** for each group.

## 📊 Results

| Group                         | Size | Acceptance Rate |
| ----------------------------- | ---- | --------------- |
| Frequent Visitors (Group A)   | 880  | **67.5%**       |
| Younger Drivers (Group B)     | 1881 | 53.43%          |
| Not Highly Educated (Group C) | 3398 | 49.74%          |

## 💡 Hypothesis

> **Drivers who already visit coffee houses frequently are significantly more likely to accept Coffee House coupons, regardless of age or education level.**

This suggests that **habitual behavior** is a stronger predictor of coupon acceptance than demographics.

## 📂 File

* `coffee_coupon_analysis.ipynb`: Jupyter Notebook that performs data preprocessing, segmentation, and analysis.

## ✅ Next Steps

* Build a logistic regression model to test the independent effect of coffee visit frequency on coupon acceptance.
* Explore cross-category behavior (e.g., do frequent coffee drinkers also accept restaurant coupons?).

