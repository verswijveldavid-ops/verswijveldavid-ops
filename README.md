# Hi, I'm David Verswijvel

Biomedical scientist (MSc, KU Leuven) building end-to-end data pipelines for clinical trials, safety analysis, and biomedical research. I care about reproducible workflows, honest interpretation, and turning messy data into decisions people can act on.

Based in Ghent, Belgium — open to junior clinical data, bioinformatics, and biomedical data roles, including remote.

## Clinical Data Analytics

End-to-end pipelines across both sides of the drug lifecycle — clinical trials (CDISC SDTM/ADaM, pre-market) and real-world evidence (OMOP CDM, post-market).

| Project | What it demonstrates |
|---|---|
| [Clinical Data Pipeline (CDISC SDTM Pilot)](https://github.com/verswijveldavid-ops/clinical-data-pipeline) | Pre-market clinical trial pipeline on the Xanomeline vs placebo Alzheimer's trial: SQLite + Python data-quality engine (7,339 issues flagged across completeness / validity / consistency), R + `admiral` ADaM datasets (ADSL / ADAE / ADLB), safety analysis by treatment arm, ALT liver-enzyme shift tables, interactive Streamlit dashboard |
| [RWE Pipeline on OMOP (Eunomia GiBleed)](https://github.com/verswijveldavid-ops/rwe-omop-pipeline) · [live dashboard ↗](https://rwe-omop-pipeline-b7bmnfx4uicppdwharuxfb.streamlit.app/) | Post-market real-world evidence pipeline on OMOP-standardized synthetic patient data: DuckDB + Python, NSAID new-user active-comparator design, GI-bleed safety signal analysis with confounder adjustment (crude RR 0.41 → adjusted ~1.0), interactive tabbed Streamlit dashboard with forest plot |

## Bioinformatics

Reproducible analyses of high-throughput biological data.

| Project | What it demonstrates |
|---|---|
| [Blood transcriptomics in Alzheimer's disease](https://github.com/verswijveldavid-ops/ad-blood-transcriptomics) | Reproducible RNA-seq analysis of 42 blood samples: metadata parsing, confounder-aware differential expression, PCA, candidate-gene review, Hallmark GSEA |
| [Estrogen receptor ChIP-seq in MCF-7 cells](https://github.com/verswijveldavid-ops/eralpha-chipseq-mcf7) | FASTQ-to-peaks workflow design, peak annotation, motif analysis, nearest-gene assignment, functional enrichment, honest treatment of experimental limitations |

## Technical focus

- **Clinical data:** CDISC SDTM/ADaM, R + `admiral`, SQL, data-quality engines, safety analysis (TEAE, shift tables)
- **Real-world evidence:** OMOP CDM, DuckDB, cohort building, new-user active-comparator design, confounder adjustment
- **Transcriptomics:** RNA-seq, differential expression (PyDESeq2), pathway enrichment (GSEA)
- **Regulatory genomics:** ChIP-seq, peak calling, motif analysis
- **General:** Python, R, pandas, SQL (SQLite / DuckDB), Streamlit, Git/GitHub, reproducible workflows

## Scientific approach

My biomedical sciences background includes experimental study design, participant-facing research, EEG/EMG data collection, and laboratory quality control. I value reproducible workflows, clear limitations, and conclusions that remain faithful to the evidence — including when a well-designed analysis produces a negative result.

## Connect

- [LinkedIn](https://www.linkedin.com/in/david-verswijvel-9557bb19a)
- [Email](mailto:verswijveldavid@gmail.com)
