# 🌍 Worldwide Earthquake Events
### End-to-End Data Engineering and Analytics Using Microsoft Fabric

## 📌 Project Overview

This project implements an end-to-end data engineering
and analytics solution using worldwide earthquake data
obtained from the United States Geological Survey (USGS)
Earthquake API.

The solution follows the Medallion Architecture
(Bronze, Silver, Gold) to ingest, process, transform
and prepare earthquake data for analytical purposes.

Microsoft Fabric is used to implement the data
engineering workflow, orchestrate processing activities
and build interactive Power BI visualizations.

## 🎯 Objectives

- Ingest worldwide earthquake event data through
  the USGS API.
- Implement Medallion Architecture.
- Perform data cleansing and transformation.
- Automate notebook execution using Data Factory.
- Create analytical datasets.
- Visualize worldwide earthquake events using Power BI.

## 🛠️ Technology Stack

- Microsoft Fabric
- Python
- PySpark
- SQL
- USGS Earthquake API
- Fabric Lakehouse
- Fabric Data Factory
- Power BI

## 🏗️ Architecture

The project follows three processing layers:

### 1. Bronze Layer
Raw earthquake data ingestion using Python Requests
and JSON.

### 2. Silver Layer
Data cleansing, transformation and preparation
using PySpark.

### 3. Gold Layer
Business-ready analytical datasets for reporting
and visualization.

## ⚙️ Pipeline Orchestration

Microsoft Fabric Data Factory orchestrates
the execution of Bronze, Silver and Gold notebooks.

## 📊 Power BI Dashboard

The dashboard provides insights into:

- Worldwide earthquake distribution
- Earthquake magnitude
- Significance classification
- Geographic distribution
- Historical earthquake events

## 📂 Repository Structure

- notebooks/ - Data processing notebooks
- architecture/ - Architecture diagrams
- pipeline/ - Pipeline documentation
- sql/ - Analytical queries
- dashboard/ - Dashboard screenshots
- documentation/ - Project documentation

## 📡 Data Source

USGS Earthquake API:
https://earthquake.usgs.gov/fdsnws/event/1/

## 👩‍💻 Author

Harini Manickavasagam

Computer Science Engineering
