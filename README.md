# Olist E-Commerce Sales Dashboard

An interactive Business Intelligence dashboard analyzing sales, customer behavior, product performance, and operational metrics of Olist — a Brazilian e-commerce platform — covering transactions from **2016 to 2018**.

---

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Initial data exploration and preprocessing |
| SQL | Data querying, transformation, and aggregation |
| Power BI Desktop | Dashboard design and interactive visualization |

---

## Data Source

- **Source:** [Kaggle — Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- **Period:** 2016 – 2018
- **Coverage:** Brazilian e-commerce transactions across multiple states
- **Unit of analysis:** Orders, customers, sellers, and products

### Key variables used

| Variable | Description |
|---|---|
| Revenue | Total sales value per order |
| Order Status | Delivered, shipped, canceled, invoiced, processing |
| Review Score | Customer rating (1–5 scale) |
| Payment Type | Credit card, boleto, voucher, debit card |
| Freight Value | Shipping cost per order |
| Product Category | Category of purchased products |
| Seller/Customer State | Brazilian state of seller or buyer |

---

## Dashboard Overview

This dashboard consists of **2 pages**, each serving a different analytical purpose.

---

### Page 1 — Executive Overview

A high-level summary of Olist's overall business performance and key sales metrics.

**KPI Cards:**
- **Total Revenue:** 14.10M
- **Total Orders:** 884
- **Average Review Score:** 4.08
- **Average Order Value:** 15.95K
- **Average Freight Value:** 1.93K

**Visuals included:**
- **Revenue by Customer State** — São Paulo (SP) leads with 5.8M, followed by Rio de Janeiro (RJ) at 2.1M and Minas Gerais (MG) at 1.7M
- **Revenue Trend** — time series from Jan 2017 to Jul 2018, with a notable peak around mid-2018
- **Review Distribution** — majority of customers give a score of 5, with 587 reviews, showing high overall satisfaction
- **Order Status** — 97% of orders are successfully delivered, with only 1.6% in other statuses (shipped, canceled, etc.)

---

### Page 2 — Product & Operations Insights

A deeper look into product performance, seller activity, payment behavior, and logistics.

**Visuals included:**
- **Payment Method Distribution** — credit card dominates at 69.6%, followed by boleto (22.4%) and voucher (6.8%)
- **Seller Performance by State** — SP has the highest number of active sellers (500+), far ahead of other states
- **Average Review by Category** — several categories consistently receive perfect 5.0 ratings, including agro_industri, fashion_mal, home_confort, la_cuisine, musical_instr, party_supplies, and small_applia
- **Top Product Categories by Revenue** — sports_leisure leads at 1.64M, followed by cool_stuff (1.47M) and watches_gifts (1.41M)
- **Shipping Cost vs Product Price** — scatter plot showing that higher-priced products do not always incur higher shipping costs, suggesting shipping is not purely price-driven

---

## How to Use

1. **Open the Power BI file** — download and open the `.pbix` file in Power BI Desktop.
2. **Use slicers** — filter by Year, Payment Type, and Customer State using the dropdown slicers on Page 1.
3. **Navigate between pages** — use the **"View Details"** button to go to Page 2 (Product & Operations), and **"Go Back"** to return to the Executive Overview.
4. **Interact with visuals** — click any bar, slice, or data point to cross-filter other visuals on the same page.

---

## Glossary

| Term | Meaning |
|---|---|
| Freight Value | Shipping cost charged per order |
| KPI | Key Performance Indicator |

---

> **Note:** This dashboard was built for academic and portfolio purposes using a publicly available dataset from Kaggle. All figures are derived from the original Olist dataset without modification.
