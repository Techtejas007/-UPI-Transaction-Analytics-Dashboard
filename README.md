# 💳 UPI Transaction Analytics Dashboard

> An interactive Power BI dashboard analyzing UPI payment behavior across cities, banks, merchants, and demographics — helping fintech teams and analysts understand digital payment trends in India.

---

## 📌 Problem Statement

With the explosive growth of UPI payments in India, businesses and analysts struggle to answer key questions:
- Which cities and demographics are driving the most transactions?
- How do transaction volumes trend across months?
- Which banks, merchants, and payment methods are most frequently used?
- What are the differences in sent vs. received transaction patterns?

This dashboard turns raw UPI transaction data into clear, filterable insights.

---

## 🖥️ Dashboard Pages

| Page | Description |
|------|-------------|
| **Page 1 – Transaction Trends** | Line chart & column chart showing transaction volume by month (Year 2024), with full slicer panel |
| **Page 2 – Transaction Breakdown** | Pivot table analysis of transactions by City and Currency |

---

## 🔍 Key Features

- **10 interactive slicers** — filter by Bank (Sent/Received), City, Device Type, Gender, Age Group, Merchant Name, Payment Method, Purpose, and Transaction Type
- **Monthly trend analysis** — dual line + column chart view for YoY comparison
- **Bookmark navigator** — seamless page navigation experience
- **Pivot table drill-down** — cross-tabulate transactions by city and currency

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| **Power BI Desktop** | Dashboard development, DAX measures, report layout |
| **DAX** | Custom KPIs, filters, calculated columns |
| **Power Query (M)** | Data transformation and cleaning |

---

## 📊 Dataset Fields

`BankNameSent` · `BankNameReceived` · `City` · `DeviceType` · `Gender` · `Age Groups` · `MerchantName` · `PaymentMethod` · `Purpose` · `TransactionType` · `Currency`

---

## 💡 Business Impact

- Enables banks and fintech apps to **identify high-volume cities and demographics** for targeted campaigns
- Helps **fraud detection teams** spot unusual transaction patterns by device type and payment method
- Supports **merchant partnerships** by surfacing top-used merchants across demographics
- Provides **product teams** monthly trend data to correlate feature launches with usage spikes

---

## 📁 File

| File | Description |
|------|-------------|
| `UPI_transaction.pbix` | Power BI report file |

---

## 🚀 How to Use

1. Download `UPI_transaction.pbix`
2. Open in **Power BI Desktop** (free download from Microsoft)
3. Use the slicers on each page to filter data by your desired segment
4. Navigate between pages using the bookmark navigator

---

## 👤 Author

**Tejas Bafna** — Data Analyst | Power BI Developer  
📧 tejasbafna311@gmail.com · [LinkedIn](https://linkedin.com) · 📍 Nashik, India
