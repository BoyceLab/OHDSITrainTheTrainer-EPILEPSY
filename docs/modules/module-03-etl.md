# Module 03 · Extract–Transform–Load (ETL) to OMOP

!!! info "Program Context"
    Within the two-day boot camp, this module provides practical tooling for mapping oncology data so all personas can support sites effectively.

## Overview
Source data profiling, mapping, and loading with OHDSI tools.

## Objectives
- Profile sources (White Rabbit), design mappings (Rabbit in a Hat)
- Map local codes (Usagi/Athena)
- Document ETL and handle missing/inconsistent data

## Key Resources
- White Rabbit / Rabbit in a Hat: <https://github.com/OHDSI/WhiteRabbit>
- Usagi: <https://github.com/OHDSI/Usagi>

## Hands-on (Mini-Mapping)
Map sample ICD-10-CM and local terms to standard concepts (breast/lung CA). Decide target tables/fields (Condition, Procedure, Measurement).

## Persona Tips
- **Vocab:** resolve unmapped; maintain mapping logs  
- **Data Sci:** parameterize transforms; version ETL  
- **Statisticians/Clinicians:** understand ETL implications for analysis

## Takeaways
Documented, transparent ETL underpins trustable analytics.

