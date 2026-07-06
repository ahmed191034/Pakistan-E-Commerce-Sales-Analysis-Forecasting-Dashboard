# Pakistan-E-Commerce-Sales-Analysis-Forecasting-Dashboard

An end-to-end Power BI project analysing **~1M+ e-commerce transactions** to uncover
revenue drivers, order-fulfilment patterns, and customer payment behaviour — and to
forecast sales for the next six years.

**Tools:** Power BI · Data Cleaning · DAX · Time-Series Forecasting

---

## Business Question

*Where does this online store's revenue actually come from, what's going wrong in order
fulfilment, and how are sales likely to trend over the next six years?*

---

## Dashboard Overview

### Page 1 — Executive Summary
KPI cards (Expected Revenue, Orders Fulfilled, Customers, Discount Amount) alongside
profit by category and a monthly sales trend, with a year slicer for interactivity.

![Executive Summary](images/page1_overview.png)

### Page 2 — Operational Deep-Dive
Order-fulfilment status, category vs. order quantity, and spend by payment method —
the operational detail behind the headline numbers.

![Operational Deep-Dive](images/page2_operations.png)

### Page 3 — Sales Forecast
A time-series forecast projecting sales six years forward, with a confidence band to
show the range of likely outcomes.

![Forecast](images/page3_forecast.png)

---

## Key Findings

- **Mobiles & Tablets dominate profit**, generating several times the profit of the next
  category — a clear signal to prioritise stock and marketing spend there.
- **Sales are strongly seasonal**, peaking sharply in November (likely festive / sale-season
  demand) with a secondary peak in May — informing inventory and campaign timing.
- **Order fulfilment has a notable cancellation and refund rate**: "complete" orders lead,
  but "cancelled" and "refunded" together represent a meaningful share, flagging a
  fulfilment or customer-experience issue worth investigating.
- **Payment behaviour concentrates in a few methods** (Payaxis, Cash on Delivery, and Easypay
  drive most order value), useful for prioritising payment-partner reliability.
- **Forecast points to continued growth**, with the model projecting an upward sales trend
  through 2024.

---

## Process

1. **Data cleaning** — processed and standardised 1M+ raw transactional records, handling
   missing values and inconsistent category labels.
2. **Modelling & measures** — built DAX measures for revenue, fulfilment rates, and
   category-level profit.
3. **Visualisation** — designed a three-page report (overview → operations → forecast) with
   slicers for interactive exploration.
4. **Forecasting** — applied time-series forecasting to project future sales with a
   confidence interval.

---

## What I'd Improve Next

- Refine the forecast model (test seasonal methods such as SARIMA against the built-in
  forecast) given the strong seasonality in the data.
- Clean residual category labels ("Others", "Superstore") for cleaner segmentation.
- Modernise the visual theme for a cleaner, more consistent look.

---

*Dataset: public Pakistan e-commerce dataset. Built as a personal portfolio project.*
