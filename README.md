# Automated Payroll Reporting

## Overview

This project documents an end-to-end payroll reporting automation built with Python and Microsoft Excel.

The automation merges payroll source reports, validates payroll totals, updates company-specific reporting workbooks, and generates standardized payroll reports across multiple legal entities and business groups.

The solution transformed a repetitive multi-hour reporting process into an automated workflow that completes in approximately **30 seconds**.

---

# Project Gallery

## Manual Payroll Reporting Process

![Manual Process](screenshots/manual-process.png)

The original workflow required multiple manual steps every pay period, including merging payroll files, updating numerous company workbooks, formatting reports, and validating results.

---

## Payroll Source File Merger

![Payroll Merge](screenshots/payroll-merger.png)

Two payroll exports are automatically combined into a single standardized distribution summary, eliminating manual consolidation before reporting begins.

---

## Payroll Processing Application

![Processing GUI](screenshots/payroll-processing.png)

Simple desktop interface allowing the user to:

* Select merged payroll data
* Choose the payroll period
* Process every company workbook
* Validate output automatically

---

## Company-Level Reporting Output

![Company Output](screenshots/company-output.png)

Automatically updated company payroll workbook with standardized formatting and current payroll information.

The automation eliminates repetitive workbook updates across multiple companies.

---

## Final Payroll Reports

![Final Reports](screenshots/final-report.png)

Generated payroll reports ready for management review.

The workflow produces consistent, repeatable reporting outputs every payroll cycle.

---

# Results

This automation significantly improved payroll reporting efficiency.

## Business Problem

Payroll reporting was performed manually every pay period.

The existing process required:

* Combining multiple payroll exports
* Cleaning and standardizing payroll data
* Updating individual company reporting workbooks
* Producing consolidated payroll reports
* Validating totals between input and output files

Because every company required separate updates, the process was repetitive, time-consuming, and susceptible to manual errors.

---

## Solution

I designed a Python-based automation that performs the complete reporting workflow from beginning to end.

The solution:

* Merges multiple payroll source reports
* Creates a standardized payroll dataset
* Updates company-specific reporting workbooks
* Automatically validates totals
* Produces standardized payroll reporting outputs
* Generates repeatable reports with minimal user interaction

The application provides a simple graphical interface allowing users to select payroll files, choose the pay period, and process every company simultaneously.

---

## Workflow

```text
Payroll Reports
        │
        ▼
Merge Source Files
        │
        ▼
Standardize Payroll Data
        │
        ▼
Validate Totals
        │
        ▼
Update Company Workbooks
        │
        ▼
Generate Final Reports
```

---

## Technologies Used

* Python
* Microsoft Excel
* Tkinter GUI
* Financial Reporting Automation
* Data Processing
* Workflow Automation

---

## Skills Demonstrated

* Python application development
* Desktop GUI development
* Financial systems automation
* Data validation
* Multi-company reporting
* Payroll reporting
* Excel automation
* Business process improvement
* Workflow design

---

### Impact

* Reduced processing time from multiple hours to approximately **30 seconds**
* Eliminated manual consolidation across **7 legal entities**
* Automated reporting across **13 business groups**
* Reduced repetitive manual data entry
* Improved reporting consistency
* Increased confidence through automated validation
* Created a repeatable payroll reporting workflow

---

## Privacy Note

This repository is presented as an anonymized portfolio case study.

The original source code was developed within a previous employer's environment and contained proprietary payroll structures, business rules, company information, and reporting logic.

To respect employer confidentiality, source code has not been included. The screenshots and documentation demonstrate the architecture, workflow, and business value of the solution while protecting proprietary information.

---

## Professional Context

This project demonstrates my experience applying Python automation to finance and accounting operations.

Rather than simply automating individual tasks, the solution automated an entire payroll reporting workflow—from data preparation through validation and final reporting—allowing accounting staff to shift their focus from repetitive processing to higher-value analysis.
