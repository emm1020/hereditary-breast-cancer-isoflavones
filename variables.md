# Variables Used in the Study

This document describes the key variables used in the SAS analysis for the hereditary breast cancer study on isoflavone intake.

| Variable Name     | Description                                                   | Type                      | Example        |
|-------------------|---------------------------------------------------------------|---------------------------|----------------|
| age_at_diagnosis  | Age at first breast cancer diagnosis                          | Continuous (years)        | 42             |
| bc_status         | Breast cancer status (0 = no, 1 = yes)                        | Binary                    | 1              |
| isf_intake        | Isoflavone intake group (based on FFQ quantile categories)    | Categorical (Low/Med/High)| High           |
| marriage          | Ever married                                                  | Binary (0 = No, 1 = Yes)  | 1              |
| parity            | Number of childbirths                                         | Integer                   | 2              |
| alcohol           | Current alcohol use                                           | Binary (0 = No, 1 = Yes)  | 0              |
| activity          | Regular physical activity                                     | Binary (0 = No, 1 = Yes)  | 1              |
| energy            | Total daily energy intake                                     | Continuous (kcal/day)     | 2050           |
| brca_status       | BRCA mutation status                                          | Categorical (0 = None, 1 = BRCA1, 2 = BRCA2) | 2 |
| birth_cohort      | Year group for stratification                                 | Categorical               | 1970-1979      |
| sampling_weight   | Sampling weight applied to Cox model                          | Continuous                | 0.83           |
