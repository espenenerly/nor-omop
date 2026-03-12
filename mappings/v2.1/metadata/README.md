# CRN OMOP Mapping Package – Version v2.1

This folder contains the complete CRN OMOP mapping package for version **v2.1**.  
Each version is a fully self‑contained and reproducible snapshot that includes lookup tables, USAGI mappings, ETL specifications, and metadata.

Use this version when running ETL processes, doing QA, or reproducing analyses based on this mapping release.


## 📁 Folder Structure
```
v2.1/
│
├── lookup/                 # Excel lookup file with all mappings across domains
│     └── CRN_lookup_v2.1.xlsx
│
├── usagi/                  # One USAGI file per domain, including approvals and comments
│     ├── conditions_v2.1.csv
│     ├── drugs_v2.1.csv
│     ├── procedures_v2.1.csv
│     ├── measurements_v2.1.csv
│     ├── observations_v2.1.csv
│     └── usagi_project_v2.1.json
│
├── etl-specification/      # ETL transformation specification (DOCX/PDF)
│     └── CRN_ETL_Specification_v2.1.docx
│
└── metadata/               # Additional documentation for version v2.1
├── CHANGELOG.md
└── notes.md
```

## 🔍 Purpose of Version v2.1

Provide a short description here:

- Initial publication of the CRN OMOP mapping package  
- Includes all lookup mappings across domains  
- Contains validated USAGI domain files  
- Includes ETL specification for transforming CRN source data to OMOP CDM  

(Replace with your own details if needed.)

---

## 🧩 Components in This Version

### **1. Lookup File**
**CRN_lookup_v2.1.xlsx** contains the full mapping master file with domain‑specific sheets:

- Conditions  
- Procedures  
- Drugs  
- Measurements  
- Observations  

The lookup file is authoritative for the final mapping content.

---

### **2. USAGI Domain Files**
Each CSV represents the domain‑specific mapping work, including:

- Source codes  
- Standard concepts  
- Mapping status  
- Comments and approvals  
- Decision history  

The JSON project file (`usagi_project_v2.1.json`) stores project‑level metadata.

---

### **3. ETL Specification**
**CRN_ETL_Specification_v2.1.docx** describes:

- Transformation rules  
- Source table interpretation  
- Business logic  
- Field‑level mapping conventions  
- Handling of special cases  
- References to vocabulary versions  

This document should be used together with the lookup/USAGI files.

---

### **4. Metadata**
Contains version‑specific documentation:

- **CHANGELOG.md** — list of all changes introduced in v2.1  
- **notes.md** — free‑form notes, rationale, decisions, limitations  

---

## 🛠 How to Use This Version

1. Use the lookup file for ETL implementation and analytical reference.  
2. Use USAGI CSV files to follow mapping decisions, approvals, and unresolved items.  
3. Follow the ETL specification for implementing transformations from CRN source systems.  
4. Refer to metadata files for historical context and version‑specific notes.

---

## 🔄 Creating New Versions

When preparing the next version (e.g., v2.2):

1. Copy the entire `v2.1` folder  
2. Rename to `v2.2`  
3. Update mappings, USAGI files, and ETL specification  
4. Update `CHANGELOG.md` and titles inside metadata  
5. Commit and tag the new version

---

## 📌 Contact / Ownership

This mapping version is part of the CRN OMOP transformation effort.  
Ownership and maintenance: *Cancer Registry of Norway (CRN)*.
