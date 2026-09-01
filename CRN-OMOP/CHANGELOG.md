# CHANGELOG

Notable changes to the CRN-OMOP implementation are documented in this file.

The changelog summarizes major changes to data content and ETL processes.

---

## Version 2025.1

CDM release date: 2026-07-29

### New data sources
- Expanded breast cancer, colorectal cancer, and melanoma content.
- Added 2025 incident cancer cases.

### Clinical content
- Added comorbidity measures.
- Added recurrence and progression information for selected cancers.
- Added additional molecular biomarkers.

### ETL improvements
- Improved ICD-O-3 mapping coverage.
- Minor mapping corrections.

---

## Version 2024.2

CDM release date: 2026-03-12

Legacy version identifier: v2.2

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
- Minor mapping corrections.

### Vocabulary
- Updated vocabulary release to 2026-02-27.

---

## Version 2024.1

CDM release date: 2025-09-09

Legacy version identifier: v2.1

### New data sources
- Added 2024 incident cancer cases.
- Added molecular diagnostics from the Norwegian Lung Cancer Registry.

### Clinical content
- Added EGFR, ALK, ROS1, and PD-L1 biomarkers.

### ETL improvements
- Added quality and completeness indicators.
- Improved measurement representation.
- Improved alignment with OHDSI Oncology conventions.
- Updated vocabulary mappings.
- Updated observation period.

### Vocabulary
- Updated vocabulary release to 2025-08-27.

---

## Version 2023.1

CDM release date: 2025-04-30

Legacy version identifier: v2.0

### New data sources
- Added 2022-2023 incident cancer cases.

### Clinical content
- Added ECOG performance status, TNM staging, and morphological grade.
- Added anticancer drug treatment.

### ETL improvements
- Updated observation period.
- Added episode-based disease representation.
- Removed custom codes.
- Minor mapping corrections.

### Vocabulary
- Updated vocabulary release to 2024-08-30.

---

## Version 2021.1

CDM release date: 2023-01-27

Legacy version identifier: v1.0

### Initial release

- First operational CRN-OMOP implementation.
- Core Cancer Registry of Norway dataset represented in OMOP CDM.
- Initial oncology mapping framework established.
- Added incident cancer cases from 1953-2021.
- Vocabulary version 2022-09-09.
