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
