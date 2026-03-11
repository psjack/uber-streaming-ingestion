# Uber Streaming Data Pipeline

End-to-end **data engineering pipeline** for processing Uber ride data using **PySpark**, implementing a layered **Bronze → Silver architecture** for scalable data processing and analytics.

---

# Architecture

> Architecture diagram will be added here.

```
![Architecture Diagram](diagrams/Architecture Diagram.png)

```

---

# Project Overview

This project demonstrates a modern **data engineering workflow** for processing ride data using **PySpark-based transformation pipelines**.

The pipeline performs:

• Raw data ingestion
• Data cleaning and transformation
• Data modeling
• Creation of analytics-ready datasets

The implementation follows a **layered data architecture** commonly used in modern data lake systems.

---

# Data Pipeline Layers

## Bronze Layer

Raw ingestion layer that captures incoming ride data with minimal transformation.

Responsibilities:

• Preserve raw source data
• Handle schema ingestion
• Maintain original dataset structure

---

## Silver Layer

Data cleansing and transformation layer.

Responsibilities:

• Data validation
• Data standardization
• Schema modeling
• Preparation of structured analytical datasets

---

# Tech Stack

* **Python**
* **PySpark**
* **SQL**
* **Jupyter Notebooks**
* **Data Lake Architecture**

---

# Project Structure

```
uber-streaming-ingestion/

misc/
    arrays.json
    map_cities.json

notebooks/
    uber_bronze_adls.ipynb
    uber_silver_obt.ipynb

src/
    ingestion/
        ingest.py

    transformations/
        model.py
        silver.py
        silver_obt.sql

.gitignore
README.md
```

---

# Key Features

• Modular PySpark transformation pipeline
• Bronze → Silver data processing architecture
• Data validation utilities
• Structured analytics-ready datasets

---

# Future Improvements

• Implement Gold analytics layer
• Add orchestration using workflow scheduler
• Introduce automated testing
• Add real-time streaming ingestion

---

# Author

**Param Judge**
