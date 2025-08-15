# HEDIS Quality Audit Tools 🧾📊

A Python- and SQL-based framework for streamlining HEDIS quality audits, aligning chart review processes with NCQA guidelines using de-identified clinical and claims data.

> 🚧 This project contains conceptual blueprints only. Source data and logic are modeled after real audits but fully anonymized.

---

## 📌 Use Case

Organizations must calculate HEDIS quality measures from fragmented EHR and claims data. This repo offers tools to:

- Automate flagging of non-compliant records
- Standardize audit prep using measure definitions (e.g., CDC, CBP, IMA)
- Provide audit trails, visual dashboards, and clean exportable reports

---

## ⚙️ Tools Used

- **Python**: pandas, numpy, datetime, PyYAML
- **SQL**: PostgreSQL / MS SQL Server syntax
- **Visualization**: matplotlib / Tableau-ready exports
- **Data**: Anonymized CSVs simulating chart review datasets

---

## 📁 Repo Structure

hedis-quality-audit-tools/
├── sample_data/
│   ├── patients.csv
│   ├── encounters.csv
│   └── labs.csv
├── notebooks/
│   └── cdc_audit_workflow.ipynb
├── scripts/
│   ├── clean_data.py
│   ├── hedis_measure_cdc.sql
│   └── generate_reports.py
└── README.md

---

## 📈 Output Example

- 🎯 Summary table of compliance rates by measure  
- 🧾 Exportable audit log (CSV, XLSX)  
- 📊 Dashboard-ready datasets for Power BI / Tableau  

---

## 🔒 Compliance Note

This repo contains **NO real patient data**. Logic is based on public documentation of NCQA and HEDIS specs.  
For live deployments, align with HIPAA, CMS, and organization policies.

---

## 🤝 Contact

**Daniel Allen, RN, MBA**  
Founder @ [QMTRY.ai](https://qmtry.ai)  
📧 [daniel@qmtry.ai](mailto:daniel@qmtry.ai)  
🐙 [GitHub](https://github.com/daniel-QMTRY)  
🔗 [LinkedIn](https://www.linkedin.com/in/daniel-allen-mba/)

