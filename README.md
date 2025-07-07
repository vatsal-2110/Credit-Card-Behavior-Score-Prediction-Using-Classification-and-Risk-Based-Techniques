# 💳 Credit Card Behaviour Score Prediction  
**Using Classification and Risk-Based Techniques**

---

<p align="center">
  <img src="https://img.shields.io/badge/Model-Type%3A%20Binary%20Classification-blue" alt="Model Type"/>
  <img src="https://img.shields.io/badge/Imbalanced%20Data-Handled%20with%20SMOTENC-orange"/>
  <img src="https://img.shields.io/badge/Key%20Metric-F2%20Score-9cf"/>
</p>

---

## 📌 Overview

This project presents a complete **machine learning pipeline** to predict whether a customer is likely to **default on their credit card payment in the next month**, based on historical **financial behavior and demographic data**.

The solution tackles **real-world challenges** such as:

- ⚖️ **Highly imbalanced data**
- 🧠 **Model interpretability**
- 💼 **Business-driven risk alignment**

It applies a blend of **feature engineering**, **threshold tuning**, and **model comparison** across logistic regression, tree-based models, and ensemble methods.

---

## 🎯 Problem Statement

The objective is to build a predictive system for:

> **Will the customer default on their credit card payment next month?**

🔍 **Target variable**: `next_month_default`  
📈 **Task type**: Binary classification (`0` = No Default, `1` = Default)

### 🔢 Input Data Includes:
- **📊 Credit Capacity**
  - `LIMIT_BAL` (credit limit)
- **🧑 Demographics**
  - `age`, `education`, `marriage`, `sex`
- **💵 Monthly Billing & Payments**
  - `bill_amt1`–`bill_amt6`, `pay_amt1`–`pay_amt6`
- **⏱️ Payment Delay History**
  - `pay_0`, `pay_2`–`pay_6`

---

## ❗ Real-World Challenge

- The dataset is **highly imbalanced** — many more non-defaulters than defaulters
- Traditional metrics like accuracy can be **misleading**
- Emphasis is placed on:
  - 🔍 **Recall** — Catching as many defaulters as possible
  - 📊 **F2 Score** — A recall-weighted evaluation metric
  - 🤖 **Model transparency** — Understanding why a customer is flagged

---

Stay tuned for sections on:

✅ Feature Engineering  
✅ Model Training & Threshold Optimization  
✅ Performance Comparison  
✅ Business Recommendations
