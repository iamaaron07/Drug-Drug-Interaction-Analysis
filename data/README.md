# Sample Data

## Datasets Used

This project is based on two datasets:

### 1. SafeICU Dataset

The SafeICU dataset is a real-world, de-identified Pediatric Intensive Care Unit (PICU) database developed through a collaboration between the Department of Pediatrics, All India Institute of Medical Sciences (AIIMS), New Delhi and the Centre of Excellence in Healthcare, IIIT-Delhi. It contains longitudinal clinical data collected from pediatric ICU patients and is intended to support research in artificial intelligence, clinical decision support, and critical care. :contentReference[oaicite:0]{index=0}

The project uses the following tables from the SafeICU dataset:

- **patient.csv** – Patient demographics including age, gender, and mortality status.
- **admission.csv** – Hospital admission and discharge information used to calculate length of stay.
- **noteevents.csv** – Clinical notes containing medication information used for drug extraction.

---

### 2. DDInter Database

The DDInter database is used as the drug–drug interaction reference database.

It contains information such as:

- Drug A
- Drug B
- Interaction severity (Major, Moderate, Minor)
- Drug identifiers (DDInter IDs)

The database is used to identify clinically significant interactions between drugs prescribed to the same patient.

---

## Dataset Availability

The original SafeICU and DDInter datasets are **not included** in this repository due to licensing and data-sharing restrictions.

Users can obtain access to the SafeICU dataset through the official SafeICU portal after fulfilling the required data access agreement. :contentReference[oaicite:1]{index=1}

