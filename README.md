# Retail_Store_Analytics_BI
An end-to-end Power BI business intelligence solution featuring an optimized star-schema semantic model, advanced DAX time-intelligence calculations, and custom JSON-themed interactive UI layouts.

# 📊 Advanced Interactive Business Intelligence Report

## 🚀 Project Overview
This repository contains a comprehensive, end-to-end Business Intelligence solution built using **Power BI Desktop**. The project transforms raw relational data into an interactive, insights-driven dashboard designed to optimize executive decision-making and track high-level operational performance metrics.

---

## 🛠️ Tech Stack & Architecture
*   **Analytics Tool:** Power BI Desktop
*   **Data Modeling:** Star Schema (Fact & Dimension Tables)
*   **Query Language:** DAX (Data Analysis Expressions) for advanced measures, Power Query (M) for ETL
*   **Core Concepts:** Row-Level Security (RLS), Dynamic Layouts, Shared Themes

---

## 🧩 Key Features & Data Architecture

### 1. Data Model & ETL
*   Implemented an optimized **Star Schema** with explicit relationship cardinalities to prevent cross-filter ambiguity.
*   Cleaned, engineered, and transformed raw data streams within **Power Query** using M-code for data normalization.

### 2. Advanced DAX Calculations
*   Developed complex time-intelligence measures (YoY Growth, Rolling Averages, Year-to-Date performance).
*   Utilized optimized variables (`VAR`) to ensure high-performance rendering across large datasets.

### 3. Dynamic UI/UX Layout
*   Built using a custom responsive reporting canvas utilizing shared base themes (`CY26SU05.json`).
*   Integrated advanced bookmarks, custom tooltips, and conditional formatting to guide user navigation effortlessly.

---

## 📊 Dashboard Preview & Repository Structure
```text
├── Report/
│   ├── Layout                 # Custom layout configurations
│   └── StaticResources/       # Theme files & base JSON layers
├── DataModel                  # Transformed semantic data model
└── Project_Dashboard.pbix     # Main Power BI file
