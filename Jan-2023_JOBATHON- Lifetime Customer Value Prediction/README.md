# 🚗 VahanBima – Customer Lifetime Value (CLTV) Prediction

## 📌 Problem Statement

**VahanBima** is one of India’s leading motor insurance companies, offering affordable policies with 24/7 claim settlement for both personal and commercial vehicles.  

With nearly 90% of businesses adopting personalized services, VahanBima plans to launch **personalized experience programs**, including:

- Dedicated claim settlement resources  
- Doorstep services  
- Priority support  
- Exclusive benefits  

To enable this, the company wants to segment customers into different tiers based on **Customer Lifetime Value (CLTV)**.

The objective is to build a **high-performance and interpretable machine learning model** to predict CLTV using customer and policy data.

---

## 🎯 Objective

Develop a regression model to predict:

> **Customer Lifetime Value (CLTV)**

The model should:
- Achieve a high **R² score**
- Be interpretable for business decisions
- Generalize well to unseen data

---

## 📊 Dataset Overview

You are provided with three files:

- `train.csv`
- `test.csv`
- `sample_submission.csv`

---

## 🗂️ Train Dataset

Contains ~90,000 records with features and the target variable `cltv`.

| Variable | Description |
|-----------|-------------|
| id | Unique identifier of a customer |
| gender | Gender of the customer |
| area | Area of the customer |
| qualification | Highest qualification of the customer |
| income | Annual income (in ₹) |
| marital_status | Marital Status {0: Single, 1: Married} |
| vintage | Years since first policy date |
| claim_amount | Total claimed amount (in ₹) |
| num_policies | Total number of policies issued |
| policy | Active policy of the customer |
| type_of_policy | Type of active policy |
| cltv | **Customer Lifetime Value (Target Variable)** |

---

## 🗂️ Test Dataset

Contains ~60,000 records. The target variable `cltv` is not provided.

| Variable | Description |
|-----------|-------------|
| id | Unique identifier of a customer |
| gender | Gender of the customer |
| area | Area of the customer |
| qualification | Highest qualification of the customer |
| income | Annual income (in ₹) |
| marital_status | Marital Status {0: Single, 1: Married} |
| vintage | Years since first policy date |
| claim_amount | Total claimed amount (in ₹) |
| num_policies | Total number of policies issued |
| policy | Active policy of the customer |
| type_of_policy | Type of active policy |

---



