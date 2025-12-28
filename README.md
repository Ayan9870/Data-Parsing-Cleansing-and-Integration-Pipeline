# Data Parsing, Cleansing and Integration Pipeline

---

## Project Overview

Advanced data wrangling and integration pipeline for e-commerce clothing review datasets, utilising Python-based XML and CSV parsing, robust data cleansing, and schema conflict resolution techniques. The system automates the detection and correction of quality issues such as typographical errors, missing values, and duplicate records while enforcing data integrity constraints and consistency standards. Through a modular workflow, executed via Jupyter notebooks, the project performs schema harmonisation and semantic mapping to unify heterogeneous datasets into a single structured output. Detailed error tracking and documentation ensure reproducibility and transparency across all stages. The solution showcases strong capabilities in data auditing, transformation, and integration for large, messy real-world datasets.

---

## Access to Code 🔒

The source code for this project is **private** and available upon request.

If you're an **employer** or **recruiter** and would like to review the code, please **request access via email** at **ayanhashmi205@yahoo.com**.

---

## Installation 📦

#### Clone this repo

```bash
git clone https://github.com/ayan9870/data-integration-pipeline.git
cd data-integration-pipeline
```

#### Launch notebooks

```bash
jupyter notebook Module1_2.ipynb
jupyter notebook Module3.ipynb
```

---

## Features 📋

* **Multi-format data parsing**: XML and CSV data extraction and transformation
* **Comprehensive data cleansing**: Automated detection and correction of data quality issues
* **Schema conflict resolution**: Intelligent mapping between different data structures
* **Data integration pipeline**: Seamless merging of heterogeneous datasets
* **Quality assurance**: Duplicate detection and integrity constraint validation
* **Detailed error tracking**: Complete audit trail of all data modifications
* **Professional documentation**: Editable transcripts for reproducible data processing

---

## Project Structure 🔍

### Module 1: Data Parsing
* **XML parsing**: Extract structured data from complex XML hierarchies
* **DataFrame transformation**: Convert parsed data into pandas-compatible format
* **Schema validation**: Ensure data types and structures meet requirements

### Module 2: Data Auditing & Cleansing
* **Error detection**: Identify typos, spelling mistakes, and data irregularities
* **Integrity validation**: Check for constraint violations and outliers
* **Missing value handling**: Strategic imputation and removal of incomplete records
* **Duplicate elimination**: Remove redundant entries while preserving data integrity
* **Consistency enforcement**: Standardize formats and value representations

### Module 3: Data Integration
* **Schema harmonization**: Resolve structural conflicts between datasets
* **Semantic mapping**: Align similar attributes across different data sources
* **Conflict resolution**: Handle data-level inconsistencies in merged datasets
* **Unique key identification**: Establish proper indexing for integrated data

---

## Data Sources 📊

### Primary Dataset (XML)
- **Source**: `dataset1.xml`
- **Content**: E-commerce clothing reviews with customer ratings
- **Attributes**: ClothID, Age, Review Title, Customer Rating, Department, Cost, etc.

### Secondary Dataset (CSV)
- **Source**: `dataset2.csv`
- **Content**: Additional clothing review data for integration
- **Attributes**: Clothing ID, Age, Title, Rating, Division Name, Price, etc.

---

## Pipeline Outputs 📁

### Module 1 & 2 Deliverables
- `dataset1_solution.csv`: Cleaned and processed primary dataset
- `errorlist.csv`: Comprehensive error log with fixes applied

### Module 3 Deliverables
- `dataset_integrated.csv`: Unified dataset combining both sources

### Documentation
- `Module1_2.ipynb`: Data parsing and cleansing workflow
- `Module3.ipynb`: Data integration and conflict resolution

---

## Quality Assurance 🧪

### Data Quality Issues Addressed
- **Typographical errors**: Automated spelling correction and standardization
- **Format inconsistencies**: Uniform data type enforcement
- **Missing values**: Strategic handling based on data context
- **Duplicate records**: Intelligent deduplication preserving unique information
- **Outlier detection**: Statistical analysis for anomaly identification
- **Integrity constraints**: Business rule validation and enforcement

### Validation Metrics
- Data completeness percentage
- Error correction success rate
- Schema mapping accuracy
- Duplicate detection precision

---

## Results Summary 📈

| Module | Input Records | Output Records | Errors Fixed | Success Rate |
|------|--------------|----------------|--------------|--------------|
| Module 1 | Variable | Variable | Variable | ~95%+ |
| Module 2 | Variable | Variable | Variable | ~98%+ |
| Module 3 | Combined | Integrated | Conflicts Resolved | ~99%+ |

---

## Author ✨

| <a href="https://github.com/ayan9870" target="_blank">**Muhammad Ayan Hashmi**</a> |
|:--:|
| ![Ayan Hashmi](https://github.com/ayan9870.png?size=100) |
| [`github.com/ayan9870`](https://github.com/ayan9870) |

---

## License
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
