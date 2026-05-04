# Playwright Python UI Test Automation Project

## Project Overview

This project automates UI test scenarios using Playwright with Python and records execution results in an Excel file using openpyxl.

The automation reads test case data from an Excel sheet, performs UI interactions on the target web application, and writes the actual results and pass/fail status back to the Excel file.

---

## Technologies Used

 Python
 Playwright (Python)
 openpyxl (Excel handling)

---


## Installation Steps

1. Install required dependencies: pip install playwright openpyxl

2. Install Playwright browsers: playwright install


## How to Run the Test

Run the automation script using the following command:

python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open

---

## Test Execution Details

 The script reads test scenarios from the Excel file.
 Executes UI actions using Playwright.
 Captures actual results.
 Updates the Excel file with:

   Actual Result
   Status (Pass/Fail)

---

## Important Notes

 Ensure the Excel file is 'closed' before running the script.
 Make sure the correct file name is used in the command.
 Internet connection is required to access the test URL.
---

## Output

After execution:

The Excel file will be updated automatically with test results.

---

## Repository Access

This repository is public.

---
