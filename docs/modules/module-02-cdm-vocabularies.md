# Module 02 · OMOP CDM Architecture & Standardized Vocabularies

## Overview
Core tables, relationships, standard vs source concepts, and concept hierarchies.

## Objectives
- Read the CDM schema at a high level
- Use concept search (Athena/Atlas) to build robust concept sets
- Understand oncology-relevant concepts (e.g., histology, biomarkers)

## Pre-Reads
- Book of OHDSI – Common Data Model: <https://ohdsi.github.io/TheBookOfOhdsi/CommonDataModel.html>

## Key Resources
- Athena browser: <https://athena.ohdsi.org/>
- Atlas concept sets: <https://ohdsi.github.io/Atlas/>

## Hands-on (Oncology)
- Build a **breast cancer** concept set: include descendants.
- Add **HER2 status** via measurements/markers where available.
- Repeat for **lung cancer** (NSCLC vs SCLC).

## Persona Tips
- **Vocab Experts:** lead concept hierarchy building
- **Statisticians:** check clinical face validity & completeness
- **Data Scientists:** export concept IDs for SQL pipelines
- **Clinicians:** sanity check clinical coverage

## Takeaways
- Strong concept sets = reliable cohorts and analyses.
