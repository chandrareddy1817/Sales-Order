# 📊 Acme Co. Sales Data Analysis (2014–2018)

## 🎯 Objective

Deliver actionable insights from Acme Co.'s 2014–2018 sales data to:

- Identify top-performing products, channels, and regions driving **revenue** and **profit**
- Uncover **seasonal trends** and **anomalies** for optimized planning
- Spot **pricing and margin risks** from outlier transactions
- Inform **pricing**, **promotion**, and **market-expansion** strategies

These findings guide the design of a **Power BI dashboard** to support strategic decision-making and sustainable growth.

---

## 📂 Dataset Overview

The dataset contains 5 years (2014–2018) of transaction-level sales data, including:

- Order details (`order_date`, `order_number`)
- Financials (`unit_price`, `cost`, `budget`, `revenue`)
- Product and sales channel information
- Customer and location data (`region`, `state`, `county`)

---

## 🛠️ Tools & Technologies

- **Python**: Pandas, Matplotlib, Seaborn for data cleaning and analysis
- **Power BI**: Interactive dashboard for business users
- **Jupyter Notebook**: Analysis workflows and insight generation

---

## 🔍 Key Insights

### 📆 Monthly Revenue Cycle
- Revenue remains stable around **$26.5M** across 2014–2017.
- Sharpest drop (~**$21.2M**) in **early 2017** indicates a potential disruption or business anomaly.
- No strong seasonal spikes, suggesting **non-seasonal revenue flow**.

### 📦 Channel Mix
- **Wholesale** dominates: **54%** of revenue.
- **Distributors**: 31% | **Exports**: 15%
- **Opportunity:** Scale international presence through exports.

### 🏆 Top Products (by Revenue)
- **Product 26**: ~$110M
- **Product 13**: ~$68M–75M
- Bottom performers: ~$52M–57M range
- Concentrated revenue contribution from top SKUs.

### 💰 Profit Margins
- Margins vary from **~18% to ~60%**
- No strong correlation to unit price
- Horizontal bands in scatterplots suggest **standardized pricing tiers**.

### 🗓️ Seasonal Volume
- No strong monthly trends, but slight **May–June uptick** in volume.
- Volume dip in **early 2017 (~$21.2M)** requires investigation (e.g., supply chain issue or market shift).

### 🌎 Regional Performance
- **California** leads with:
  - ~$230M in revenue
  - **7500+ orders**
- Other top states:
  - **Illinois, Florida, Texas**: ~$85M–110M revenue & 3500–4500 orders
  - **New York, Indiana**: ~$54M & 2000+ orders

---

## 📊 Power BI Dashboard (Coming Soon)

The dashboard will provide:

- Dynamic KPIs for revenue, profit, and order volume
- Filters by year, region, product, and channel
- Time-series visualizations for monthly revenue and margins
- Geographic sales heatmaps and customer distribution

---

## 📌 Conclusion

The data reveals valuable insights into Acme Co.'s operational strengths, market dynamics, and pricing strategies. These findings enable:

- Data-backed **pricing and promotional decisions**
- Identification of **regional growth opportunities**
- Enhanced **risk mitigation** through outlier detection

The accompanying Power BI dashboard will turn these insights into an interactive decision-making tool for stakeholders.

---

📁 *This repository includes the Python notebooks, cleaned datasets, and dashboard files for reference and reuse.*
