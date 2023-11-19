# Log Management System

## Overview

This project implements a log management system with a Log Ingestor and Query Interface. The Log Ingestor efficiently ingests logs in a specified format, and the Query Interface provides a user-friendly interface for full-text search and filtering.

## How to Run

### Log Ingestor

1. Install the required dependencies:
   ```bash
   pip install flask elasticsearch
Run the Log Ingestor:
cd log_ingestor
python log_ingestor.py


Query Interface
Install the required dependencies:pip install flask elasticsearch
Run the Query Interface:cd query_interface
python query_interface.py

Certainly! Let's create a sample README.md file to provide instructions on running the project, describe the system design, list features, and identify any potential issues.

markdown
Copy code
# Log Management System

## Overview

This project implements a log management system with a Log Ingestor and Query Interface. The Log Ingestor efficiently ingests logs in a specified format, and the Query Interface provides a user-friendly interface for full-text search and filtering.

## How to Run

### Log Ingestor

1. Install the required dependencies:
   ```bash
   pip install flask elasticsearch
Run the Log Ingestor:
bash
Copy code
cd log_ingestor
python log_ingestor.py
Query Interface
Install the required dependencies:

bash
Copy code
pip install flask elasticsearch
Run the Query Interface:

bash
Copy code
cd query_interface
python query_interface.py
Access the Query Interface at http://localhost:3001 in your web browser.

System Design
The system consists of two main components:

Log Ingestor: Responsible for ingesting logs into Elasticsearch. It runs on port 3000 and supports bulk ingestion.

Query Interface: A web-based interface for searching logs in Elasticsearch. It runs on port 3001 and allows full-text search and filtering based on log fields.

Features Implemented
Efficient log ingestion using Elasticsearch.
Full-text search in logs.
Filters based on log fields (level, message, resourceId, timestamp, traceId, spanId, commit, metadata.parentResourceId).
Bulk ingestion support for the Log Ingestor.
Identified Issues
No identified issues at the moment. Please report any issues or improvements.
