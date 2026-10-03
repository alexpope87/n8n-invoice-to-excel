# n8n Invoice to Google Sheets

A simple document automation built with n8n that extracts structured data from PDF invoices and stores it automatically in Google Sheets.

## Problem

Manually reading invoices and copying their data into spreadsheets is repetitive and time-consuming.

The goal of this project was to automate the process using a lightweight n8n workflow.

## Workflow

1. A user uploads a PDF invoice through an n8n form.
2. n8n extracts the text from the PDF.
3. Google Gemini identifies the relevant invoice fields.
4. The structured data is appended automatically to Google Sheets.

## Extracted Fields

- Supplier
- Invoice Number
- Invoice Date
- Due Date
- Subtotal
- VAT
- Total
- Currency
- File Name

## Workflow

![n8n Invoice Workflow](screenshots/workflow.png)

## Tech Stack

- n8n
- Google Gemini
- Google Sheets

## Key Concepts Practiced

- File upload handling
- PDF text extraction
- AI-powered structured data extraction
- Data mapping
- Google Sheets integration
- Workflow automation

## Result

Uploading a PDF invoice automatically creates a structured row in Google Sheets without manual data entry.

## Security

API keys and authentication credentials are not included in this repository.
