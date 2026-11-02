# Netflix Catalogue Analysis

<p align="center">
  <em>A data-preparation and business-intelligence case study</em><br>
  <strong>EXCEL&nbsp; / &nbsp;POWER QUERY&nbsp; / &nbsp;POWER BI&nbsp; / &nbsp;DAX</strong>
</p>

---

## The story in one minute

A catalogue dataset can answer more than “how many titles are there?” This project explores how the supplied Netflix dataset is distributed across Movies and TV Shows, genres, ratings, countries and release years.

The work follows a multi-tool workflow: inspect the source in Excel, assess data quality, transform fields in Power Query, prepare a Power BI model, and communicate findings through report visuals and written documentation.

> **Dataset boundary:** This is an analysis of the supplied project dataset. It is not a live connection to Netflix and should not be read as a description of the current catalogue.

## Explore the deliverables

| Start here | What it contains |
|---|---|
| [Raw dataset](Raw_Netflix_Dataset.xlsx) | Original workbook supplied for the analysis |
| [Cleaned dataset](Cleaned_Netflix_Dataset.xlsx) | Prepared workbook |
| [Data-quality report](Cleaned_Data_Quality_Report.xlsx) | Quality assessment workbook |
| [Power BI report](Netflix_Content_Analysis_Dashboard.pbix) | Editable report file for Power BI Desktop |
| [Project documentation](docs/README.md) | Index to the supporting reports |

## Questions explored

- What is the split between Movies and TV Shows?
- Which genres occur most frequently in the supplied records?
- Which content-rating categories appear most often?
- How is country information distributed?
- How do title counts vary by release year?
- What can the available rating and audience fields tell us—and what can they not tell us?

## How the analysis is organised

| Stage | Tool | Work performed |
|---|---|---|
| 01 · Understand | Excel | Inspect the source structure, fields and records |
| 02 · Assess | Excel | Review missing values, duplicates and consistency |
| 03 · Prepare | Power Query | Clean and standardise selected fields |
| 04 · Model | Power BI | Load the prepared data and organise the reporting model |
| 05 · Calculate | DAX | Create measures and KPI calculations for the report |
| 06 · Communicate | Power BI | Arrange visuals and filters around the analysis questions |

The exact transformation details and supporting explanations are in the numbered reports under `docs/`.

## Report preview

![Conceptual Netflix dashboard layout](images/dashboard-layout-preview.svg)

<sub>The image above is a static layout concept, not a screenshot exported from Power BI Desktop. Open the PBIX file to inspect the editable report.</sub>

## Documentation library

Ten project reports are available:

| Report | Focus |
|---|---|
| [01 — Project Overview](docs/01_Project_Overview.pdf) | Scope and workflow |
| [02 — Data Collection and Understanding](docs/02_Data_Collection_and_Understanding.pdf) | Source review |
| [03 — Excel Data Quality Assessment](docs/03_Excel_Data_Quality_Assessment.pdf) | Data-quality checks |
| [04 — Power Query Cleaning and Transformation](docs/04_Power_Query_Data_Cleaning_and_Transformation.pdf) | Preparation steps |
| [05 — Power BI Data Model](docs/05_Power_BI_Data_Model.pdf) | Model structure |
| [06 — DAX Measures and KPIs](docs/06_DAX_Measures_and_KPIs.pdf) | Calculations |
| [07 — Dashboard Design and Visualization](docs/07_Dashboard_Design_and_Visualization.pdf) | Visual design |
| [08 — Business Questions and Insights](docs/08_Business_Questions_and_Insights.pdf) | Interpretation |
| [09 — Business Recommendations](docs/09_Business_Recommendations.pdf) | Dataset-based suggestions |
| [10 — Final Project Report](docs/10_Final_Project_Report.pdf) | Consolidated report |

## Open the project locally

**Requirements:** Microsoft Excel and Power BI Desktop.

1. Clone or download this repository.
2. Inspect `Raw_Netflix_Dataset.xlsx` first.
3. Review `Cleaned_Data_Quality_Report.xlsx` and `Cleaned_Netflix_Dataset.xlsx`.
4. Open `Netflix_Content_Analysis_Dashboard.pbix` in Power BI Desktop.
5. Review the model, measures, report pages and filters.
6. Use the PDF library when you need the written process behind the report.

## Interpretation notes

- All findings depend on the records and fields in the supplied workbook.
- The project does not represent Netflix's current live catalogue.
- Release-year patterns describe the records in this dataset; they do not establish why content was produced or removed.
- Revenue, subscriptions, viewer behaviour and platform performance are outside the scope unless supported by suitable data.
- The preview graphic is conceptual. The PBIX is the report artifact to inspect.

---

**Project author:** Shanmukh Koyya  
[GitHub profile](https://github.com/shanmukhkoyya) · [LinkedIn](https://www.linkedin.com/in/shanmukh-koyya/) · [Email](mailto:shanmukhkoyya1234@gmail.com)
