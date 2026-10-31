# Olist E-Commerce Analytics Dashboard

An interactive performance analytics dashboard built to analyze the Olist Brazilian E-commerce dataset. The dashboard provides end-to-end visibility into overall revenue, order volumes, customer satisfaction, payment methods, freight costs, top product categories, and temporal sales trends across different geographic regions.

---
# Olist E-Commerce  Dashboard overview
<img width="590" height="330" alt="2" src="https://github.com/user-attachments/assets/2f7adca0-78e1-433a-abf6-c352f637ebdd" />
<img width="589" height="329" alt="1" src="https://github.com/user-attachments/assets/60bcc2d3-1132-4f43-8f32-e14c44f7ad5e" />
<img width="591" height="328" alt="3" src="https://github.com/user-attachments/assets/c6a0ba5c-cd54-4865-aa6b-1477676e5c0d" />


---

## 📈 High-Level Key Performance Indicators (KPIs)

| Metric | Overall Dashboard Value | Filtered / Time View Value |
| :--- | :---: | :---: |
| **Total Sales** | **13.59M** | **15.19K** |
| **Total Orders** | **99K** | **99K** |
| **Avg. Items Per Order** | **1.13** | **0.00** |
| **Average Review Score** | **4.09 / 5.0** | **4.16 / 5.0** |

---

## 📊 Dashboard Modules & Key Insights

### 1. Payments Overview
* **Total Payment Volume:** **16.01M** across all channels.
* **Payment Method Breakdown:**
  * **Credit Card:** **78%** (13M) — Primary customer payment choice.
  * **Boleto:** **18%** (3M).
  * **Voucher:** **2%** (<1M).
  * **Debit Card & Not Defined:** Remainder (<1%).
* **Payment Installments:** 
  * 1 installment accounts for the highest single portion (**5.9M**).
  * High installment preference at 10 installments (**2.2M**).
* **Freight Cost Analysis:**
  * **Top Freight by Customer State:** São Paulo (**SP**) leads with **0.69M**, followed by Rio de Janeiro (**RJ**) at **0.29M** and Rio Grande do Sul (**RS**) at **0.13M**.
  * **Top Freight by Product Category:** `bed_bath_table` (**0.20M**), `health_beauty` (**0.18M**), `furniture_decor` (**0.17M**), and `sports_leisure` (**0.17M**).

---

### 2. Sales & Product Performance
* **Top Product Categories by Revenue:**
  1. `health_beauty`: **1.44M**
  2. `watches_gifts`: **1.31M**
  3. `bed_bath_table`: **1.24M**
  4. `sports_leisure`: **1.16M**
  5. `computers_accessories`: **1.06M**
  6. `furniture_decor`: **0.90M**
* **Customer Review Distribution:**
  * **5-Star Reviews:** ~58K (Dominant rating).
  * **4-Star Reviews:** ~19K.
  * **1-Star Reviews:** ~11K.
  * **3-Star Reviews:** ~8K.
  * **2-Star Reviews:** ~3K.
* **Geographical Distribution:** Visual map detailing order distribution and seller revenues across Brazilian/US regional boundaries.

---

### 3. Time Series & Trend Analysis

* **Daily Trend (Total Sales by Day):** Peak day sales reach up to **2.0K**, with regular performance spikes at **1.7K** and **1.0K**.
* **Monthly Trend (Total Sales by Month):** High seasonality observed around May (**3.5K** peak), followed by July (**2.1K**) and August (**1.8K**).
* **Quarterly Trend (Total Sales by Quarter):**
  * **Q1:** 2.2K
  * **Q2:** **5.5K** (Peak quarter)
  * **Q3:** 5.0K
  * **Q4:** 2.5K
* **Yearly Trend:** Comparison tracks performance shifts across 2017 (**10.1K**) and 2018 (**5.1K**).

---

## 🎛️ Dynamic Slicers & Filters

The dashboard provides dynamic interactivity with multi-select slicers:
* **Order Status:** Filter by completed, pending, canceled, etc.
* **Date & Time:** Custom date range selection.
* **Customer State & City:** Drill down by specific states (e.g., `AC`, `SP`, `RJ`) or municipalities.
* **Product Category:** Select specific merchandise categories.
