# OMOP Mappings for MIREDA

This repository contains OMOP Common Data Model (CDM) concept mappings used for harmonising birth cohort data within the **Mother and Infant Research Electronic Data Analysis (MIREDA)** initiative.

These mappings were developed to standardise data across multiple UK birth cohorts, enabling federated, privacy-preserving research into maternal, infant, and child health outcomes across the life course.

---

## 🔍 About MIREDA

MIREDA is a UK-wide partnership that aims to harmonise and standardise birth cohort data using the OMOP CDM. Its primary goal is to enable **federated analysis** across birth cohorts from all four UK nations, facilitating longitudinal research while respecting data privacy and governance frameworks.

MIREDA seeks to address disparities in data structure, content, and vocabulary across different health datasets by transforming them into a shared, consistent format using OMOP.

---

## 🧒 Participating Birth Cohorts

The following cohorts are part of the MIREDA initiative:

- **CPRD (Clinical Practice Research Datalink)** – England-wide primary care cohort  
- **MuM-PreDiCT** – A subset of CPRD focused on maternal multimorbidity  
- **Born in Wales (BiW)** – National cohort covering live births in Wales  
- **Born in Scotland (BiS)** – Regional cohort from NHS Borders and NHS Lothian  
- **Born in Bradford (BiBBS / BiB4All)** – A diverse population birth cohort in Bradford  
- **eLIXIR (Born in South London)** – A South London-based linked birth cohort

These cohorts collectively represent **over 4.3 million live births since 2014**, with approximately **500,000 new births added annually**.

---

## 🧰 Repository Structure

- `mapping_tables/`: Finalised OMOP concept mapping tables for each birth cohort
- `README.md`: Project overview and context (this file)

---

## 🎯 Purpose of the Mappings

The mappings in this repository support:

- **Federated analysis** across UK-wide Trusted Research Environments (TREs)
- **Standardised representation** of maternal and infant health data
- **FAIR data principles**: Findable, Accessible, Interoperable, Reusable
- Reusability of mappings and ETL tools by other projects adopting the OMOP CDM

---

## 🔐 Data Security

All person-level data remain within the secure environments of each TRE. Mappings and code can be shared, but data itself is only accessible via **Health Data Research UK (HDRUK)** through approved data access requests.

---

## 📎 Resources

- [MIREDA Project Page (NCPHWR)](https://ncphwr.org.uk/portfolio/mireda/)
- [Health Data Research UK Innovation Gateway](https://www.healthdatagateway.org/)
- [OMOP Common Data Model](https://www.ohdsi.org/data-standardization/the-common-data-model/)

---

## 📬 Contact

For questions, suggestions, or collaboration, please contact:  
**Armando Mendez**  
📧 armando.mendez@nottingham.ac.uk

---

*This work is supported by grants from MRC [MR/X02055X/1], MatCHNet [U20005/302873], and [MR/X009742/1].*
