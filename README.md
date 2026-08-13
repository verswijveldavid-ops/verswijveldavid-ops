# Hi, I'm David Verswijvel

Biomedical scientist (MSc, KU Leuven) building **clinical data analytics** and **real-world evidence** pipelines. I care about reproducible workflows, honest interpretation of results, and turning messy real-world data into decisions people can act on.

Based in Ghent, Belgium — open to remote junior roles: Clinical Data Analyst, Real-World Evidence Analyst, Clinical Data Scientist, Health Data Analyst.

---

## Projects on real patient data

| Project | What it demonstrates |
|---|---|
| [🎗️ Breast Cancer Survival — TCGA-BRCA](https://github.com/verswijveldavid-ops/oncology-survival-pipeline) · [live dashboard ↗](https://oncology-survival-pipeline-husupmr7t8azdx3xjdbc9p.streamlit.app/) | End-to-end survival analysis on **1,076 real breast cancer patients** from the NCI Genomic Data Commons (TCGA-BRCA). Reconciled follow-up records across four sources (**found 48 patients marked "Alive" who had actually died**), mapped the raw data into **CDISC SDTM & ADaM** with `admiral`, ran Kaplan-Meier + Cox regression (Stage IV HR 6.70, Stage III 1.64, Age 1.23). Streamlit dashboard. |
| [🍬 Diet & Chronic Disease — NHANES](https://github.com/verswijveldavid-ops/dietary-oncology) · [live dashboard ↗](https://dietary-oncology-ygadx9y5d79iuirkez2bom.streamlit.app/) | Survey-weighted logistic regression on **~4,700 real US adults** (CDC NHANES 2017–2018). Tested sugar intake against **13 chronic diseases**. Result: sugar is broadly null; smoking and obesity are the real drivers; the "sugar looks protective for diabetes" result is reverse causation (patients cut sugar *after* diagnosis). Streamlit dashboard. |

## Standard training-data projects (CDISC & OMOP)

Built on the industry-standard training datasets published by **CDISC** and **OHDSI** — the same datasets pharma teams and universities use to learn these workflows.

| Project | What it demonstrates |
|---|---|
| [💊 Clinical Data Pipeline — CDISC SDTM Pilot](https://github.com/verswijveldavid-ops/clinical-data-pipeline) · [live dashboard ↗](https://clinical-data-pipeline-xqiebyvrkddveejacq6jjs.streamlit.app/) | Pre-market clinical-trial pipeline (Xanomeline vs placebo Alzheimer's trial): SQLite + Python data-quality engine (**7,645 issues flagged** across completeness / validity / consistency), R + `admiral` ADaM datasets (ADSL / ADAE / ADLB), safety analysis (TEAE rates 76.7% / 87.5% / 95.8% by arm — dose-dependent signal), ALT liver-enzyme shift table, Streamlit dashboard. |
| [🌐 RWE Pipeline — OMOP Eunomia](https://github.com/verswijveldavid-ops/rwe-omop-pipeline) · [live dashboard ↗](https://rwe-omop-pipeline-b7bmnfx4uicppdwharuxfb.streamlit.app/) | Post-market real-world evidence pipeline on OMOP-standardised data: DuckDB + Python, NSAID new-user active-comparator design, GI-bleed safety signal. Headline: **crude RR 0.49 collapses to adjusted OR 0.98 after age/sex adjustment** — textbook confounding demonstration. Streamlit dashboard with forest plot. |

---

## Technical focus

- **Clinical data:** CDISC SDTM/ADaM, R + `admiral` (pharmaverse), SQL, data-quality engines, safety analysis (TEAE, shift tables)
- **Real-world evidence:** OMOP CDM, DuckDB, cohort building, new-user active-comparator design, confounder adjustment, causal inference
- **Survival analysis:** Kaplan-Meier, Cox regression, time-to-event (`lifelines`, R `survival` + `survminer`)
- **Statistical modelling:** logistic regression, survey-weighted analysis (NHANES sampling design), sensitivity analyses
- **General:** Python (pandas, statsmodels), R, SQL (SQLite / DuckDB), Streamlit, Git/GitHub, reproducible workflows

## Approach

My biomedical sciences background includes experimental study design, participant-facing research, EEG/EMG data collection, and laboratory quality control. I value reproducible workflows, clear limitations, and conclusions that stay faithful to the evidence — including when the evidence is a well-designed **null result**. Every project's `learning_log.md` shows the reasoning, mistakes, and fixes along the way.

## Connect

- [LinkedIn](https://www.linkedin.com/in/david-verswijvel-9557bb19a)
- [Email](mailto:verswijveldavid@gmail.com)
