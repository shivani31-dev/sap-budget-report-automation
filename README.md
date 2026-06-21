# 🚀 SAP Budget Report Automation

## 📌 Overview

SAP Budget Report Automation is a Python-based automation solution developed during my internship project. The application processes SAP Project System (PS) exported budget data files, performs data cleaning, WBS (Work Breakdown Structure) classification, data transformation, and automatically generates professionally formatted Excel reports.

The goal of this project is to reduce manual effort, improve reporting accuracy, and automate budget report generation using Python and Excel automation techniques.

---

## 🎯 Project Objectives

* Automate SAP exported budget report processing.
* Eliminate repetitive manual Excel operations.
* Improve reporting efficiency and accuracy.
* Generate standardized Excel reports.
* Classify and analyze WBS elements automatically.

---

## ⚙️ Features

### ✅ Data Processing

* SAP DAT File Processing
* Automated Data Cleaning
* Data Validation
* Data Transformation

### ✅ WBS Management

* WBS Element Classification
* Summary WBS Detection
* Transaction WBS Detection
* WBS Name Mapping

### ✅ Excel Automation

* Automated Excel Report Generation
* Freeze Panes
* Currency Formatting
* Auto Column Width Adjustment
* Header Formatting
* Alternate Row Coloring
* Summary WBS Highlighting

### ✅ Report Enhancement

* Professional Report Layout
* Budget Analysis Support
* Structured Output Generation

---

## 🏗️ System Architecture

```text
SAP Exported DAT File
           │
           ▼
     Data Cleaning
           │
           ▼
    Data Processing
           │
           ▼
   WBS Classification
           │
           ▼
   Excel Generation
           │
           ▼
   Excel Formatting
           │
           ▼
  Final Budget Report
```

---

## 🔄 Workflow

```text
Select DAT File
      │
      ▼
Read Data
      │
      ▼
Clean Data
      │
      ▼
Transform Data
      │
      ▼
Map WBS Names
      │
      ▼
Classify WBS Elements
      │
      ▼
Generate Excel Report
      │
      ▼
Apply Formatting
      │
      ▼
Save Final Report
```

---

## 📂 Project Structure

```text
SAP-Budget-Report-Automation
│
├── README.md
├── LICENSE
├── requirements.txt
│
├── assets
│   ├── banner.png
│   ├── architecture.png
│   ├── workflow.png
│   └── report_preview.png
│
├── input
│   ├── sample_budget.dat
│   └── WBS_NAMES.xlsx
│
├── output
│   └── Budget_Report.xlsx
│
├── src
│   ├── main.py
│   ├── file_handler.py
│   ├── data_processor.py
│   ├── excel_formatter.py
│   └── config.py
│
└── docs
    └── Internship_Report.pdf
```

---

## 🛠️ Technologies Used

| Technology | Purpose                  |
| ---------- | ------------------------ |
| Python     | Core Development         |
| Pandas     | Data Processing          |
| OpenPyXL   | Excel Formatting         |
| XlsxWriter | Excel Report Generation  |
| PySide6    | File Selection Interface |
| NumPy      | Data Handling            |

---

## 📊 Sample Input

```text
Object    Cost    Jan    Feb
WBS-01    10000   5000   5000
WBS-02    15000   7000   8000
WBS-03    20000   10000  10000
```

---

## 📈 Sample Output

| WBS    | Description     | Budget |
| ------ | --------------- | ------ |
| WBS-01 | Civil Work      | 10000  |
| WBS-02 | Electrical Work | 15000  |
| WBS-03 | Mechanical Work | 20000  |

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/sap-budget-report-automation.git
cd sap-budget-report-automation
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Project

```bash
python src/main.py
```

---

## 📋 Output Features

* Professional Excel Report
* Freeze Panes Support
* Currency Formatting
* Dynamic Column Width
* Highlighted Summary WBS
* Structured Budget Report

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Python Programming
* Data Processing using Pandas
* Excel Automation
* Report Generation
* Data Cleaning Techniques
* SAP Budget Report Analysis
* Software Project Documentation

---

## 📄 Documentation

Detailed project documentation is available in:

```text
docs/Internship_Report.pdf
```

---

## 👨‍💻 Author

**SHIVANI.K**

Python Developer | Data Automation Enthusiast

---

## ⭐ Acknowledgement

This project was developed as part of an internship project focused on automating SAP budget reporting processes using Python-based data processing and Excel automation techniques.
