# COVID-19 Database Web App (Streamlit)

## Overview
This project is a Python-based web application for managing and analyzing COVID-19 PCR test data. It was developed to support laboratory workflows by providing a simple interface for storing, searching, and visualizing diagnostic test results.

The application is built using Streamlit and allows secure user authentication, data entry, and basic statistical analysis.

---

## Features

- 🔐 User authentication (login system)
- 🧾 Input and storage of PCR test data
- 🔎 Search functionality for patient records
- 📊 Visualization of test results (bar plots)
- 📈 Basic statistical analysis using binomial distribution
- 🗑️ Data management (delete entries or full dataset)
- ☁️ Cloud-based storage via JSONBin API

---

## Technologies

- Python
- Streamlit
- Pandas
- Matplotlib
- YAML (configuration)
- JSONBin (data storage)

---

## Application Workflow

1. **User Login**
   - Authentication via username and password

2. **Data Input**
   - Enter patient data:
     - Case number
     - Name
     - Age
     - Gender
     - Test result
     - Test date

3. **Data Storage**
   - Data is stored remotely using JSONBin API

4. **Data Analysis**
   - Automatic calculation of:
     - Total tests
     - Positive cases
     - Binomial probability

5. **Visualization**
   - Bar chart showing distribution of test results

6. **Data Management**
   - Search records
   - Delete specific or all entries

---

## Example Output

- 📋 Table of test results
- 🔍 Filtered search results
- 📊 Bar plot of positive vs negative tests
- 📈 Statistical summary

---

## Project Structure
main_app.py        # Main Streamlit application
config.yaml        # Authentication configuration
jsonbin.py         # API interaction for data storage
requirements.txt   # Dependencies

---

## Methods

- **Data processing:** Pandas DataFrame operations
- **Statistical analysis:** Binomial distribution
- **Visualization:** Matplotlib
- **Authentication:** Streamlit Authenticator

---

## Context

This project was developed as a student project to simulate a digital system for managing diagnostic COVID-19 PCR test data during a pandemic setting.

---

## Author

Michèle Pfister  
Bsc Biomedical laboratory Diagnostics
