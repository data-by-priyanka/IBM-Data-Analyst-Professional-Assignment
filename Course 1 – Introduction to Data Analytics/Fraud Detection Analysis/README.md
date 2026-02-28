# Fraud Detection Analysis – Descriptive Review of Transaction Patterns

## 📌 Project Overview

This assignment focuses on analyzing historical credit card transaction data to identify behavioral patterns and anomalies that may indicate fraudulent activity.

The objective of this analysis is to understand what fraudulent transactions look like using descriptive analytics techniques.

---

## 🎯 Business Context

Organizations monitor transaction data to detect unusual patterns that may signal fraud.

In this project, I analyzed transaction records to:

- Identify abnormal behavior
- Detect suspicious transaction patterns
- Recognize data quality issues
- Interpret spending trends

The analysis is based purely on historical data (Descriptive Analytics).

---

## 🔍 Key Data Points Used for Fraud Detection

The following attributes were examined to detect potential fraud:

- **IP Address & Location**  
  Used to detect geographic mismatches or sudden location changes.

- **Shipping Address**  
  Checked for billing and shipping mismatches or PO Box usage.

- **Transaction Date & Time**  
  Used to flag unusual hours (e.g., midnight activity) or abnormal frequency.

- **Transaction Value**  
  Compared against historical spending patterns to detect large deviations.

- **Product Category & Quantity**  
  Identified bulk purchases or high-resale items (e.g., electronics).

---

## ⚠️ Data Quality Issues Identified

Before performing fraud analysis, I identified the following data issues:

- One transaction had a missing dollar amount.
- Date formats were inconsistent across records.
- One customer profile had missing age information.

These issues must be resolved to ensure accurate and reliable analysis.

---

## 🚨 Suspicious Patterns Identified

### Case 1: User – johnp

- Sudden change in IP address
- Multiple high-value transactions
- Transactions occurring around 1:00 AM

This behavior shows a strong deviation from the user’s historical spending pattern and indicates elevated fraud risk.

---

### Case 2: User – ellend

- $4,895 laptop purchase
- Transaction completed at midnight
- Shipping address listed as a PO Box

The combination of high transaction value, unusual timing, and shipping preference suggests potential fraudulent activity.

---

## 📊 Visualization Insight

The transaction trend visualization shows:

- A stable historical spending pattern
- Followed by a sharp spike in transaction value

This sudden deviation from normal behavior warrants further investigation.

---

## 📈 Type of Analysis Performed

**Descriptive Analytics**

This project focuses on analyzing historical transaction data to identify patterns, trends, and anomalies without making future predictions.

---

## 🚀 Key Skills Demonstrated

- Identifying fraud indicators
- Recognizing behavioral anomalies
- Detecting data quality issues
- Interpreting transaction trends
- Applying descriptive analytics concepts
