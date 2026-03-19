# Intelligent Document Processing (IDP) 

## Overview

This project demonstrates a complete pipeline for transforming unstructured data from PDF documents (invoices, purchase orders, and receipts) into structured, usable data within a Databricks environment. It leverages state-of-the-art Document Intelligence capabilities to automate data extraction and classification.

## Key Features

* PDF Parsing: Utilizes AI parse document to extract raw text and table data from unstructured PDFs.
* AI Classification: Uses AI classify to automatically categorize files into invoices, purchase orders, or receipts based on their content, not just their filenames.
* Intelligent Extraction: Employs AI extract to pull specific key-value pairs (e.g., vendor name, total amount, date) from categorized documents into structured tables.
* Automated Pipeline: Once set up, new files can be dropped into the volume and processed using a single run all command.

## Tools Used
* Databricks
