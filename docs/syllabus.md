# 📚 Syllabus — OHDSI Train-the-Trainer (Oncology-Focused)

This is the master syllabus of required/optional readings and tools **by module** and **by persona**. Use it to prep before sessions and to assign follow-ups afterward.

---

## A) Syllabus by Module

> 💡 Tip: Chapters refer to the online [Book of OHDSI](https://ohdsi.github.io/TheBookOfOhdsi/). Oncology specifics: [Oncology Extension](https://ohdsi.github.io/CommonDataModel/oncology.html). Methods primers on bias/confounding: [RWD Guide](https://rwd.guide/).

| Module | Primary Readings | Tools & Docs | Optional/Context |
|---|---|---|---|
| **0. Orientation** | OHDSI.org – [Who We Are](https://www.ohdsi.org/who-we-are/) | OHDSI Forum (Introduce Yourself) | **EXCELERATE TtT** (source curriculum): https://github.com/TrainTheTrainer/EXCELERATE-TtT |
| **1. Intro to OHDSI/OMOP** | Book ch.1 *Journey of OHDSI*; ch.2 *Common Data Model* | Research Roadmap (OMOP/Atlas overview) | OHDSI YouTube overview |
| **2. CDM & Vocabularies** | Book ch.2 (CDM) | Athena; Atlas → Concept Sets; **Oncology Extension** | RWD Guide (code system concepts) |
| **3. ETL to OMOP** | Book ch.3 (ETL) | White Rabbit; Rabbit-in-a-Hat; Usagi | RWD Guide (data handling patterns) |
| **4. Data Quality** | Book ch.4 (Data Quality) | **Data Quality Dashboard** docs | Kahn framework paper (EGEMS) |
| **5. Analytics & Epi** | Book ch.12 (Estimation), ch.13 (Prediction), ch.19 (Study Steps) | Atlas user guide; HADES index | RWD Guide (bias/confounding) |
| **6. Security & Compliance** | Institutional HIPAA/GDPR primers | OHDSI privacy guidance | IRB FAQs (local) |
| **7. Team Building** | Book ch.15 (Community) | GitHub best practices; agile boards | Workgroup meeting notes |
| **8. Advanced Topics** | Book ch.14 (HADES) | HADES packages; **Oncology Extension** | NLP/NOTE_NLP, FHIR mapping notes |
| **9. Train-the-Trainer** | Adult learning primers | **EXCELERATE TtT** sessions | OHDSI tutorial decks |
| **10. Capstone** | Reuse ch.12/13/19 as needed | Atlas export → SQL/R | Exemplars from prior cohorts |
| **11. Wrap-Up** | Book ch.15 (Community) | Workgroups directory | EHDEN Academy catalog |
| **12. Refresher** | Book ch.19 (Study Steps) | Latest OHDSI release notes | Oncology WG updates |

---

## B) Syllabus by Persona

> These are **augmentations** on top of the module readings.

### Vocabulary / Terminology Experts
- **Core Modules:**  
  - Module 2 (*Book of OHDSI ch.2* – Common Data Model, vocabularies)  
  - Module 3 (ETL and mapping exercises)  
  - Module 4 (Data Quality – resolving unmapped concepts)
- **Tools to Master:**  
  - **Athena** – vocabulary browser for SNOMED, RxNorm, LOINC, oncology concepts  
  - **Atlas Concept Sets** – searching, descendant inclusion, set logic  
  - **Usagi** – semi-automated mapping of local codes to OMOP standard concepts  
  - **White Rabbit / Rabbit-in-a-Hat** – source data profiling and ETL design
- **Practical Exercises:**  
  - Build and validate concept sets for breast and lung cancer (including HER2 and other biomarkers).  
  - Use Usagi to map local oncology codes to standard concepts.  
  - Verify concept set integrity using Atlas (check descendants and exclusions).  
- **Key References:**  
  - [Athena Browser](https://athena.ohdsi.org/)  
  - [Atlas Concept Sets](https://ohdsi.github.io/Atlas/#/conceptsets)  
  - [Usagi GitHub](https://github.com/OHDSI/Usagi)  
  - [White Rabbit / Rabbit-in-a-Hat](https://github.com/OHDSI/WhiteRabbit)  
  - [Oncology Extension Documentation](https://ohdsi.github.io/CommonDataModel/oncology.html)


### Statisticians (tool-skeptical / design-focused)
- **Core:** Module 4 (DQD); Module 5 (Book ch.12, ch.13, ch.19); RWD Guide (bias/confounding)  
- **Do:** Critique cohort design for confounding/misclassification; propose PS/stratification strategies.  
- **Refs:** HADES CohortMethod tutorials; Atlas incidence/characterization.

### Data Scientists (SQL / code-first)
- **Core:** Module 2 (schema deep-dive), Module 5 (Atlas→SQL), Module 8 (HADES, PLP)  
- **Do:** Export Atlas SQL; reproduce in R/Python; parameterize + version with GitHub.  
- **Refs:** DatabaseConnector, FeatureExtraction, PatientLevelPrediction.

### Clinicians / Residents (Atlas-first)
- **Core:** Module 5 (Atlas cohort discovery) + Module 2 (concept search basics)  
- **Do:** Build HER2+ breast cancer cohort; interpret characterization & clinical plausibility.  
- **Refs:** Atlas quickstart video; Oncology WG topics.

---

## How to Use
- **In class:** Facilitators assign the “Primary Readings” row per module.  
- **After class:** Use persona lists for deeper self-study.  
- **As a trainer:** Bookmark [Book of OHDSI](https://ohdsi.github.io/TheBookOfOhdsi/), [RWD Guide](https://rwd.guide/), and [Oncology Extension](https://ohdsi.github.io/CommonDataModel/oncology.html) for just-in-time referencing.
