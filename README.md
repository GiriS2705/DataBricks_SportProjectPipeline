# End-to-End FMCG Data Engineering Pipeline

Enterprise-grade Data Engineering project built using Databricks Free Edition, AWS S3, PySpark, Delta Lake, and Medallion Architecture.

---

# Project Overview

This project demonstrates the implementation of a scalable lakehouse architecture for consolidating data from two FMCG companies after acquisition.

The solution handles:
- Historical backfill processing
- Incremental data ingestion
- Data cleansing and validation
- Unified reporting
- AI-powered analytics

---

# Technology Stack

| Category | Technology |
|---|---|
| Data Platform | Databricks |
| Cloud Storage | AWS S3 |
| Processing Engine | PySpark |
| Architecture | Medallion Architecture |
| Storage Format | Delta Lake |
| Workflow | Databricks Workflows |
| Reporting | Databricks SQL |
| AI Analytics | Databricks Genie |
| Language | Python, SQL |

---

# Architecture

```text
Source Systems
      ↓
AWS S3
      ↓
Bronze Layer
      ↓
Silver Layer
      ↓
Gold Layer
      ↓
Dashboards & AI Analytics
```

---

# Key Features

## Bronze Layer
- Raw ingestion from AWS S3
- Metadata tracking
- Delta Lake storage
- Auditability

## Silver Layer
- Duplicate removal
- Null handling
- Typo correction
- Data standardization
- Schema validation

## Gold Layer
- Business-ready reporting tables
- Parent-child data consolidation
- Aggregated analytics

---

# Incremental Processing

The pipeline supports:
- Historical batch processing
- Incremental daily ingestion
- Merge/Upsert operations
- Change tracking

---

# Workflow Automation

Implemented modular Databricks notebooks for:
- Setup & catalog creation
- Dimension processing
- Fact processing
- Incremental updates

---

# Key Achievements

- Designed enterprise-grade Medallion Architecture
- Built scalable ETL pipelines using PySpark
- Implemented Delta Lake ACID-compliant tables
- Developed parent-child company data consolidation logic
- Enabled AI-powered conversational analytics
- Automated data engineering workflows

---

# Business Impact

The platform delivers:
- Reliable consolidated reporting
- Improved data quality
- Faster analytics delivery
- Scalable cloud-native architecture
- AI-driven business insights

---

# Author

Girish
