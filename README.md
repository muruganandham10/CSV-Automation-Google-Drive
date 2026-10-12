# Automated CSV Processing and Google Drive File Transfer System

## Project Overview

The Automated CSV Processing and Google Drive File Transfer System is a
Python-based automation project that simplifies CSV file handling using
Google Drive API.

The system automatically identifies the latest CSV file from a Google
Drive folder, downloads the file, processes the data, splits records
into individual CSV files based on unique identifiers, uploads the
generated files to an output folder, and transfers processed files to a
client Google Drive folder.

This project reduces manual file processing efforts and improves data
management efficiency.

------------------------------------------------------------------------

## Features

-   Google Drive authentication and integration
-   Automatically detects the latest CSV file
-   Downloads CSV files from Google Drive
-   Processes CSV data using Pandas
-   Splits large CSV files into individual files
-   Automatically uploads generated files to Google Drive
-   Transfers processed files to client folders
-   Reduces manual data handling

------------------------------------------------------------------------

## Technologies Used

  Technology              Purpose
  ----------------------- ------------------------------
  Python                  Core programming language
  Pandas                  CSV data processing
  Google Drive API        File management and transfer
  Google Colab            Development environment
  Google Authentication   Secure access

------------------------------------------------------------------------

## Workflow

User Google Drive \| v Input Folder \| v Find Latest CSV File \| v
Download CSV \| v CSV Data Processing \| v Split Files Based on Unique
ID \| v Upload Output Files \| v Transfer Files to Client Drive

------------------------------------------------------------------------

## Project Structure

CSV-Automation-Google-Drive

-   CSV_Automation.ipynb
-   main.py
-   transfer.py
-   drive_auth.py
-   config.py
-   requirements.txt
-   Project_Documentation.pdf
-   screenshots/

------------------------------------------------------------------------

## How It Works

### 1. Google Drive Authentication

The application connects with Google Drive using secure authentication.

In Google Colab, authentication is handled using Google authentication
methods.

### 2. Latest CSV Detection

The system searches the configured input folder and automatically
identifies the latest uploaded CSV file.

### 3. CSV Download

The selected CSV file is downloaded from Google Drive for processing.

### 4. CSV Splitting

The system identifies a unique identifier column and creates individual
CSV files.

Supported ID columns:

cust_id, customer_id, id, ID, CustID, CustomerID, customerId

### 5. Upload Process

Generated CSV files are automatically uploaded to the configured output
folder.

### 6. Client Transfer

Processed files are transferred to the client's Google Drive folder
using Google Drive API.

------------------------------------------------------------------------

## Installation

Install required libraries:

pip install -r requirements.txt

------------------------------------------------------------------------

## Requirements

pandas google-api-python-client google-auth google-auth-oauthlib
google-auth-httplib2

------------------------------------------------------------------------

## Usage

1.  Configure Google Drive folder details.
2.  Authenticate Google Drive access.
3.  Run the automation workflow.
4.  Verify generated files in the output folder.

------------------------------------------------------------------------

## Future Enhancements

-   Web-based user interface using Flask
-   Automated scheduling
-   Email notifications
-   Database logging
-   Cloud deployment
-   Advanced monitoring system

------------------------------------------------------------------------

## Author

Muruganandham L

Computer Science Engineering Student

------------------------------------------------------------------------

## Project Status

Completed
