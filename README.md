# Automating-CSV-Append-from-Email-to-Postgres-DB
End-to-end automated data ingestion pipeline built using n8n, Gmail, and Supabase.
Automated ETL pipeline that captures CSV attachments from incoming emails using Gmail, processes and extracts the structured data using n8n, and automatically loads the records into a PostgreSQL database hosted on Supabase.
The workflow automatically detects incoming emails with CSV sales reports, extracts the file contents, transforms the data into structured records, and loads it into a PostgreSQL database.

# AI Workflow Automation for Data Analysts

This project demonstrates an automated data ingestion pipeline using n8n, Gmail, and Supabase (PostgreSQL).

## 🚀 Project Overview

The workflow automatically:

1. Triggers when a Gmail email with a CSV attachment is received
2. Extracts the CSV file from the email
3. Converts binary file to structured data
4. Parses the CSV records
5. Loads the data into a PostgreSQL database using Supabase

This removes manual steps such as downloading files and uploading them to databases.

---

## 🛠 Tools Used

- n8n (Workflow Automation)
- Gmail Trigger
- Supabase (PostgreSQL Database)
- CSV Data Processing

---

## 🔄 Workflow

Gmail Trigger  
⬇  
Extract File from Email  
⬇  
Convert Binary to CSV  
⬇  
Extract Data  https://github.com/srinathnporange/Automating-CSV-append-from-Email-to-PostgresDB-/blob/main/README.md
⬇  
Insert rows into PostgreSQL (Supabase)

---

## 📸 Workflow Screenshot
[https://github.com/srinathnporange/Automating-CSV-append-from-Email-to-PostgresDB-/blob/main/workflow_n8n.PNG](https://github.com/srinathnporange/Automating-CSV-append-from-Email-to-PostgresDB-/blob/main/workflow_n8n.PNG)

---

## 📊 Database Table

[Database](https://github.com/srinathnporange/Automating-CSV-append-from-Email-to-PostgresDB-/blob/main/Capture.PNG)

---

## 🎯 Business Value

This automation helps data analysts:

- Eliminate manual data uploads
- Automate ETL pipelines
- Build scalable reporting workflows
- Integrate operational systems with analytics databases

---

## 🔮 Future Improvements

- Add error handling
- Automate dashboard refresh
- Integrate Power BI reporting

