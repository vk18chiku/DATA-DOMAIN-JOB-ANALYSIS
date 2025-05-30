# DATA-DOMAIN-JOB-ANALYSIS

# Power BI Dashboard for Recruitment Data Integration and Analysis

## Overview

Our client, a recruitment and selection firm, recently acquired a substantial volume of data in response to a surge in job inquiries within the data field. This data was sourced from multiple channels—some normalized, others centralized—and contains detailed information on job openings. However, it is currently in a highly disorganized state, making it challenging to extract valuable insights.

This project focuses on cleaning, structuring, and preparing this data for reporting in **Power BI**, while optimizing performance despite the large dataset.

---

## Current Challenges with the Database
### 1. Data Inconsistencies and Missing Information
- The database is filled with inconsistencies and missing values.
- Critical job details are embedded within lengthy, unstructured paragraphs, complicating data extraction.

### 2. Fragmented and Disconnected Data Tables
- Multiple tables are poorly structured and fragmented.
- Lack of defined relationships has resulted in isolated data silos, impeding integration.

### 3. Challenges Due to Size of the Data
- The dataset contains over **700,000 rows**, creating processing and performance difficulties.
- Efficient data handling is required to avoid performance degradation in Power BI.

### 4. Power BI Report Optimization
- The final Power BI report must be fully optimized for both performance and usability.
- It should enable fast querying and provide actionable, accurate insights.

---

## Project Objectives

1. **Create a structured database** using the provided disparate tables.
2. **Build a consolidated table** in Power BI using the final structured schema.
3. Ensure the output is **performance-optimized** and scalable for future use by the in-house team.

---

## Final Consolidated Schema

| Column Name           | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| `Job_id`              | A unique identifier for each job posting.                                   |
| `Job_title`           | The title of the job position.                                              |
| `Job_field`           | Industry or field of the job (e.g., Data Science, Data Engineering).        |
| `Company_name`        | The organization offering the job.                                          |
| `Job_location`        | Geographical location of the job (e.g., city, state, remote).               |
| `Job_posting_date`    | Date when the job was posted.                                               |
| `Job_level`           | Required experience level (e.g., entry-level, mid-level, senior-level).     |
| `Job_type`            | Job structure (e.g., on-site, hybrid, remote).                              |
| `Job_skills`          | Required or preferred skills for the position.                              |
| `Job_employment_type` | Employment nature (e.g., contractual, permanent).                           |
| `Summary`             | A brief overview of the job responsibilities and requirements.              |

---

## Technologies Used

- **Power BI** for visualization and report development
- **SQL Server / T-SQL** for database creation and transformation
- **Python** (optional) for preprocessing and automation of cleaning tasks

---

## Outcome

By the end of this project, the client will have:
- A well-structured, reliable database formed from disorganized inputs
- A Power BI dashboard that can efficiently handle large volumes of job data
- Actionable insights that aid in faster, more informed hiring decisions

---

## Future Scope

The in-house team can continue using the structured database for ongoing recruitment analysis and integrate additional data sources as needed with minimal disruption.

---

**Author:** *[UTTAM KUMAR MAHATO]*  


