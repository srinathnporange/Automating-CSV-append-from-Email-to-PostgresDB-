# Automating-CSV-Append-from-Email-to-Postgres-DB
End-to-end automated data ingestion pipeline built using n8n, Gmail, and Supabase.
Automated ETL pipeline that captures CSV attachments from incoming emails using Gmail, processes and extracts the structured data using n8n, and automatically loads the records into a PostgreSQL database hosted on Supabase.
The workflow automatically detects incoming emails with CSV sales reports, extracts the file contents, transforms the data into structured records, and loads it into a PostgreSQL database.
