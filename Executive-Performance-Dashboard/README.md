# 🟦 Executive Performance & Failure Analysis Workbook  
A high-level, executive-friendly dashboard for understanding API health, failures, and performance trends.

---

## 📌 Overview
This workbook provides a **quick, decision-focused overview** of your application's reliability and latency.  
It is designed for:

- Engineering Managers  
- Architects  
- Product Owners  
- On-call Leaders  
- Executive Stakeholders  

The Executive dashboard highlights **what changed**, **how severe it is**, and **where attention is needed**.

---

## ⭐ Key Features

### 🔹 New vs Existing Failure Detection  
Automatically identifies:  
- **Newly introduced issues** (last 24h)  
- **Existing recurring failures** based on a baseline window  
- Uses intelligent comparison logic (7d, 14d, 28d, 60d)

### 🔹 Request Volume & Error Trends  
- Visual trending of failed requests  
- 400/500 segmentation  
- Operation-level filtering  
- Clean separation of failure types

### 🔹 Response Time Spike Analysis  
- Average, p80, p95, p99 comparison  
- Baseline overlay for anomaly detection  
- Highlights sudden degradation patterns

### 🔹 Multi-parameter control  
- Time range selector  
- Operation selector  
- Result code selector  
- Baseline comparison selector

---

## 🖼️ Screenshot  
Below is a snapshot of the Executive Workbook:

![Executive Performance Workbook](Executive_Performance_Workbook%20Screenshot.png)

---

## 🚀 How to Install

1. Open Azure Portal → **Application Insights**  
2. Navigate to **Workbooks**  
3. Select **New → Advanced Editor**  
4. Paste the JSON from:

##Executive_Performance_Workbook.json##

5. Update all placeholders (search for `{YOUR-`):  
- Subscription ID  
- Resource group  
- Application Insights name  
- Optional display name  
6. Click **Apply** → Save the workbook.

---

## ⚙️ Parameters Used

| Parameter Name | Type | Purpose |
|----------------|------|---------|
| **Show** | Dropdown | Select failure categories |
| **In** | Multiselect | Filter by operation/request name |
| **OverTimeRange** | Time picker | Select the primary analysis window |
| **UseComparisonTimeRangeOf** | Auto | Select baseline comparison window |
| **RequestFilters** | Multiselect | Filter unique failure patterns |
| **IncludeResultCodes** | Multiselect | 400/500 segmentation |

---

## 📁 Folder Contents

<img width="504" height="164" alt="image" src="https://github.com/user-attachments/assets/125174f2-2b10-44d5-b27d-b9f0082c123c" />


---

## 📝 Notes
- This dashboard is intentionally **short and executive-focused**.  
- For deeper RCA or dependency insights, use the **Detailed Performance Workbook**.  
- All filters are designed to help executives understand **trend direction**, not raw data volume.

---

If you'd like enhancements (dark mode version, heatmaps, alert integration), feel free to submit feedback or PRs!



