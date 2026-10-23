# Automated Sales Data Ingestion Using n8n

## Overview

This project automates the ingestion of sales data received as CSV email attachments. Using n8n, Gmail, and Supabase PostgreSQL, the workflow retrieves sales files, processes their contents, and loads the records into a database for querying and analysis.

## Technology Stack

- **n8n** — Workflow automation
- **Gmail** — Sales CSV attachment source
- **Supabase PostgreSQL** — Database storage

## Workflow

1. Monitor Gmail for emails containing sales CSV attachments.
2. Retrieve and parse the sales data.
3. Prepare the records for database insertion.
4. Load the processed data into Supabase PostgreSQL.

## Architecture

```text
Gmail → n8n → Sales CSV Processing → Supabase PostgreSQL
```

## Outcome

A repeatable process for transferring sales data from email attachments into a structured database, supporting downstream sales analysis and reporting.

## Security

Store credentials securely in n8n and exclude API keys, passwords, and database credentials from version control.

## Connect

**LinkedIn:** www.linkedin.com/in/biya-rocky-dataanalyst
