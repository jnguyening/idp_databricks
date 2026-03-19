# Intelligent Document Processing (IDP) 

## Overview

This project demonstrates a complete Intelligent Document Processing (IDP) pipeline within Databricks. The goal is to ingest, classify, and extract structured data from unstructured documents—specifically invoices, purchase orders, and receipts—directly from a Databricks Volume and store the structured data into managed tables.

## Key Features

* AI_PARSE_DOCUMENT: To convert unstructured document content into a parsable format
* AI_CLASSIFY: To automatically categorize documents as Invoice, Purchase Order, or Receipt based on content, not just file names
* AI_EXTRACT: To pull specific key-value pairs (e.g., Vendor Name, Total Amount, Dates) into structured data
* Automated Pipeline: Once set up, new files can be dropped into the volume and processed using a single run all command.

## Tools Used
* Databricks: The primary environment for executing the pipeline.
