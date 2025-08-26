# Module 02 · OMOP CDM Architecture & Standardized Vocabularies

!!! info "Program Context"
    The program differentiates content by persona while keeping shared competencies. This module equips all roles to use vocabularies effectively for oncology cohorts.

## Overview
Core tables, relationships, standard vs source concepts, and concept hierarchies.

## Objectives
- Read the CDM schema at a high level
- Use concept search (Athena/Atlas) to build robust concept sets
- Understand oncology-relevant concepts (histology, biomarkers)

## Pre-Reads
- Book of OHDSI – Common Data Model: <https://ohdsi.github.io/TheBookOfOhdsi/CommonDataModel.html>

## Key Resources
- Athena: <https://athena.ohdsi.org/>
- Atlas Concept Sets: <https://ohdsi.github.io/Atlas/#/conceptsets>
- Oncology WG: <https://forums.ohdsi.org/tag/oncology>

## Hands-on (Oncology)
- Build a **breast cancer** concept set (include descendants)  
- Add **HER2 status** via measurements/markers where available  
- Repeat for **lung cancer** (NSCLC vs SCLC)

## Persona Tips
- **Vocab:** lead concept hierarchy building  
- **Statisticians:** check clinical face validity & completeness  
- **Data Sci:** export concept IDs for SQL pipelines  
- **Clinicians:** sanity check clinical coverage

## Takeaways
Strong concept sets = reliable cohorts and analyses.

