# 🔒 Governance & Security Controls Documentation

This document details the Row-Level Security (RLS) implementation and Object-Level Security (OLS) architecture for the **FIFA World Cup Historical Analytics** Power BI data model.

---

## 1. Row-Level Security (RLS) Implementation

### Role Definition
* **Role Name:** `CAF_Regional_Analyst`
* **Target Table:** `Dim_Team`
* **Filter Expression:**
  ```dax
  [Team] = "Nigeria"
