# 🧮 Tableau Dashboard: Banking KPIs & Employee Analytics

## 📊 Overview

This Tableau dashboard provides interactive insights into key performance indicators (KPIs) across banking services and HR metrics. It includes filters, visual breakdowns by demographics and tenure, and an **export functionality** for end-user convenience.

---

## ✅ Features

### 📌 KPIs Tracked
- Total Bank Deposits
- Total Bank Loans
- Number of Checking Accounts
- Number of Savings Accounts
- Employee Attrition Count
- Attrition Rate
- Active Employees

### 📈 Visualizations
- **Pie Charts**:
  - Customer Segmentation: High / Medium / Low
  - Nationality Distribution
- **Bar & Line Charts**:
  - KPI Trends Over Time
- **Heatmaps**:
  - Attrition by Department

### 🔍 Filters
- **Gender** (Male / Female)
- **Joined Year**
- **Income Band**
- **Nationality**
- **Department**
- **Attrition Status**
- **Account Type**

### 📤 Export Button
- Users can download:
  - Full Dashboard as PDF
  - Individual Data Sheets (CSV)
- Implemented via **URL Action** or **Extension**

---

## 🚀 How to Use

### 1. View Dashboard
Visit the published Tableau Public link or embedded view.

### 2. Apply Filters
Use filter panels to drill down into demographics, accounts, or employee data.

### 3. Export Data
Click the **Export** button on the dashboard to:
- Download the full dashboard as a **PDF**
- Export specific data tables as **CSV**

> If the export doesn't work, ensure:
> - You're logged into Tableau Public
> - Pop-up blockers are disabled
> - The original author enabled download permission

---

## 🛠️ Tech Stack

- **Tableau Desktop** for visualization development
- **Tableau Public** for publishing
- **Custom Dashboard Buttons** for navigation and export
- Optional: **JavaScript API** or **Tableau Extensions** for advanced export

---

## 📎 How Export Button Works

### Option 1: URL Action for PDF Export

1. Create a **Dashboard Button or Image**
2. Add **Dashboard Action → URL Action**
3. Use this URL pattern:
