# CHANGELOG

All notable changes to the CRN-OMOP implementation are documented in this file.

The changelog summarizes major changes to data content, ETL processes, mappings and documentation.

---

## [2025.1]

### New data sources
- Expanded breast cancer, colorectal cancer and melanoma content.
- Added 2025 incident cancer cases.

### Clinical content
- Added comorbidity measures (CCI).
- Added recurrence and progression information for selected cancers.
- Added additional molecular biomarkers.

### ETL improvements
- Improved ICD-O-3 mapping coverage.
- Added ICD-O-3 morphology and topography representation.
- Minor mapping corrections 

---

## [2025.2 (~2.2)]

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
- Update to 27-FEB-2026
---

## [2024.2 (~2.1)]

### New data sources
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
Update to 27-08.2025

---

## [2023.1 (~2.0)]

CDM release date: 30-04-2025

### New data sources
- Added 2022-2023 incident cancer cases.

### Clinical content
- Added ECOG, TNM, Morpholigical grades
- Added drug treatment

### ETL improvements
- Updated observation periode.
- removed custom codes
- Added episode-based disease representation.
- Minor mapping corrections 

### Vocabulary update
Update to 30-08.2024

---

## [2022.1 (~1.0)]

CDM release date: 01-27-2023

### Initial release

- First operational CRN-OMOP implementation.
- Core Cancer Registry of Norway dataset represented in OMOP CDM.
- Initial oncology mapping framework established.
- 1953-2021 incident cancer cases
- Vocabulary version 09-SEP-22
