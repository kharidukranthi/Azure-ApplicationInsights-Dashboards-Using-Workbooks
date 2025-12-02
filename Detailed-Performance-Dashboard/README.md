# 🟩 Detailed Performance & Failure Analysis Workbook  
A deep-dive engineering dashboard for diagnosing performance bottlenecks, failures, dependencies, and latency variations.

---

## 📌 Overview
This workbook provides **full technical visibility** into application behavior, failures, exceptions, and dependency performance.  
It is designed for:

- Developers  
- SRE / DevOps Engineers  
- Performance Engineers  
- RCA / On-call responders  

It supports **end-to-end analysis** from traffic → failures → exceptions → dependencies → detailed operation drilldowns.

---

## ⭐ Key Features

### 🔹 Application Traffic & Trends  
- Total request volume  
- Traffic shifts and anomalies  
- Baseline vs current comparison  
- Per-operation filters

### 🔹 Failure Analysis  
- New vs Existing failures  
- Unique failure pattern detection  
- Request-level failure drill-down  
- Smart 400/500 code segmentation

### 🔹 Exception Trends  
- System exceptions vs custom exceptions  
- New vs existing exception types  
- Volume spikes and code-specific breakdowns

### 🔹 Dependency Performance  
- Slow dependency identification  
- Failed vs successful dependency calls  
- Visual breakdown of latency  
- Dependency error types and URLs

### 🔹 Percentile-based Performance Analysis  
- p50 / p95 / p99 latency  
- Mean, median values  
- Trend-over-time charts  
- Per-operation performance insights

### 🔹 Operation Drilldown Mode  
Click any operation to unlock:
- Operation-specific performance charts  
- Dependency breakdown just for that operation  
- Time-trend graphs  
- Outlier duration distribution  
- Top dependency offenders for the operation  

---

## 🖼️ Screenshot  
Below is a snapshot of the Detailed Workbook:

![Detailed Performance Workbook](Detailed_Performance_Workbook%20Screenshot.png)

---

## 🚀 How to Install

1. Open Azure Portal → **Application Insights**  
2. Navigate to **Workbooks**

   Detailed_Performance_Workbook.JSON

5. Replace placeholders such as `{YOUR-SUBSCRIPTIONID}`  
6. Click **Apply** and then **Save**.

---

## ⚙️ Parameters Used

| Parameter | Type | Purpose |
|----------|------|---------|
| **OverTimeRange** | Time picker | Main analysis period |
| **UseComparisonTimeRangeOf** | Auto | Baseline window |
| **IncludeResultCodes** | Multiselect | Error segmentation |
| **RequestFilters** | Multiselect | Request name filtering |
| **Operation** | Auto | Selected from table rows |
| **DependencyFilters** | Multiselect | Dependency-level filters |
| **ExceptionFilters** | Multiselect | Exception filtering |

---

## 🧠 How to Use the Dashboard Effectively

### ✔️ Step 1 — Check traffic health  
Look for unusual drops/spikes.

### ✔️ Step 2 — Review New Failures  
Identify fast-emerging issues.

### ✔️ Step 3 — Drill into Exceptions  
Spot recurring or new exception sources.

### ✔️ Step 4 — Analyze Dependencies  
Find slow or failing backend APIs, services, or SQL calls.

### ✔️ Step 5 — Operation Drilldown  
Click a row in the Performance table to isolate one operation.

---

## 📁 Folder Contents

<img width="562" height="166" alt="image" src="https://github.com/user-attachments/assets/c7e71951-6efc-4e3c-b075-477948905107" />



---

## 📝 Notes
- This is the **primary RCA dashboard** for engineers.  
- Use this for troubleshooting incidents, failures, dependency timeouts, and performance regressions.  
- Designed to complement the **Executive** dashboard’s high-level summary.


4. Select **New → Advanced Editor**  
5. Paste the JSON from:  
