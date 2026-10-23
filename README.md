# Sales Data Ingestion Automation

## Overview

This project automates the ingestion of sales CSV attachments received through Gmail into a Supabase PostgreSQL database using n8n.

By reducing manual file handling and data transfer, the workflow helps streamline sales data collection and makes the data available for querying and further analysis.

## Business Value

- **Reduced manual effort:** Minimizes repetitive steps involved in transferring sales data from email attachments to a database.
- **Streamlined data ingestion:** Establishes a consistent workflow for processing incoming sales files.
- **Improved data accessibility:** Centralizes sales records in PostgreSQL for easier querying and analysis.
- **More time for analysis:** Reduces routine data-handling work, allowing greater focus on data quality and generating business insights.

## Technology Stack

- **n8n** — Workflow automation
- **Gmail** — Sales CSV source
- **Supabase PostgreSQL** — Database storage

## Workflow

1. Retrieve sales CSV attachments from Gmail.
2. Parse and prepare the sales data.
3. Insert the processed records into Supabase PostgreSQL.

## Workflow Architecture

```text
Gmail → n8n → CSV Processing → Supabase PostgreSQL
```

## Workflow Demonstration

### n8n Automation Workflow
<img width="1281" height="585" alt="Screenshot 2026-10-23 061850" src="https://github.com/user-attachments/assets/5dedbc0b-1a23-4650-ad66-bd1f154a45ce" />

## Outcome

A repeatable, automated process for moving sales data from email attachments into a structured database, supporting more efficient data access and downstream analysis.

## Connect

**LinkedIn:** [View my profile](YOUR-LINKEDIN-URL)
