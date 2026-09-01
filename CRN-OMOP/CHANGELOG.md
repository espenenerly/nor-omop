# CHANGELOG

Notable changes to the CRN-OMOP implementation are documented in this file.

The changelog summarizes major changes to data content and ETL processes.

---

## Version 2025.1

CDM release date: 29.07.2026

### New data sources
- Expanded breast cancer, colorectal cancer and melanoma content.
- Added 2025 incident cancer cases.

### Clinical content
- Added comorbidity measures.
- Added recurrence and progression information for selected cancers.
- Added additional molecular biomarkers.

### ETL improvements
- Improved ICD-O-3 mapping coverage.
- Added ICD-O-3 morphology and topography representation.
- Minor mapping corrections 

---

## Version 2024.2

CDM release date: 12.03.2026

Aka v2.2

### New data sources
- Added data from the Norwegian Registry of Lymphoid Malignancies.
- Added data from the Norwegian Colorectal Cancer Registry.
- Added data from the Norwegian Breast Cancer Registry.

### Clinical content
- Added lymphoma prognostic indicators.
- Added breast cancer receptor markers.
- Added colorectal cancer treatment information.

### ETL improvements
- Improved cancer staging representation.
- Improved alignment with OHDSI Oncology conventions.
- Minor mapping corrections 
### Vocabulary
- Updated to 27-FEB-2026
---

## Version 2024.1

CDM release date: 09.09.2025

Aka v2.1

### New data sources
- Added 2024 incident cancer cases.
- Added molecular diagnostics from the Norwegian Lung Cancer Registry.

### Clinical content
- Added EGFR, ALK, ROS1 and PD-L1 biomarkers.

### ETL improvements
- Added quality and completeness indicators.
- Improved measurement representation.
- Improved alignment with OHDSI Oncology conventions.
- Updated vocabulary mappings.
- Updated observation periode.

### Vocabulary update
Update to 27.08.2025

---

## Version 2023.1

CDM release date: 30.04.2025

Aka v2.0

### New data sources
- Added 2022-2023 incident cancer cases.

### Clinical content
- Added ECOG performance status, TNM staging, and morphological grade.
- Added anticancer drug treatment

### ETL improvements
- Updated observation period.
- Added episode-based disease representation.
- removed custom codes.
- Minor mapping corrections. 

### Vocabulary update
Update to 30.08.2024.

---

## Version 2021.1

CDM release date: 01.27.2023.

Aka v1.0

### Initial release

- First operational CRN-OMOP implementation.
- Core Cancer Registry of Norway dataset represented in OMOP CDM.
- Initial oncology mapping framework established.
- 1953-2021 incident cancer cases
- Vocabulary version 09-SEP-22
