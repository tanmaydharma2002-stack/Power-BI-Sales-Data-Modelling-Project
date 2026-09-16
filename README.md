# Sales Data Analytics & Modeling in Power BI

## Overview
This repository contains an end-to-end Power BI data modeling project focused on transforming, restructuring, and modeling a highly complex, non-relational sales dataset into an optimized, report-ready data model. 

The primary objective of this project was to tackle real-world data transformation challenges—handling messy schemas, unstructured tables, and data anomalies—using Power Query and robust star-schema modeling principles.

---

## Key Features & Workflow

* **Data Extraction & Transformation (Power Query):**
  * Cleaned, structurally reshaped, and standardized raw, unorganized sales records.
  * Resolved data quality issues, missing keys, inconsistent column formats, and unpivoted dynamic reporting structures.
  * Applied custom Power Query step logic to isolate factual transactions from dimension metadata.

* **Data Modeling:**
  * Transformed flat, unnormalized files into a clean **Star Schema** architecture (Fact and Dimension tables).
  * Designed grain-consistent relationships, managing key cardinality (1:M) and directionality.
  * Built custom Date/Calendar tables to handle flexible time-intelligence reporting.

* **DAX & Analytical Foundation:**
  * Implemented core DAX measures to support business metrics across revenue, order volumes, and historical comparisons.
  * Built foundational logic to drive dynamic report visual filters seamlessly without redundant model relationships.

---
## Tools Used
* **Power BI Desktop**
* **Power Query (M Engine)**
* **DAX (Data Analysis Expressions)**

---
