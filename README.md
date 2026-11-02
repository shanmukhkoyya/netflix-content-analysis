<div align="center">

# THE CATALOGUE EDIT

### A Netflix content-data case study

**EXCEL · POWER QUERY · POWER BI · DAX**

<img src="https://img.shields.io/badge/Workflow-Data%20preparation-275D72?style=flat-square"/>
<img src="https://img.shields.io/badge/Output-Editable%20PBIX-E34A86?style=flat-square"/>

</div>

---

## The editorial question

A streaming catalogue is more than a title count. This project examines how the supplied records are distributed across **Movies and TV Shows, genres, content ratings, countries and release years**.

The assignment follows a complete preparation-to-reporting path: source inspection, data-quality review, Power Query transformations, Power BI modelling, DAX calculations and visual communication.

> **Catalogue date boundary:** This repository analyses the supplied project dataset. It is not connected to Netflix and does not represent the live catalogue today.

## The story pipeline

<table>
  <tr><td align="center"><h2>01</h2><b>Inspect</b><br/>Excel source review</td><td align="center"><h2>02</h2><b>Audit</b><br/>Missing values, duplicates and consistency</td></tr>
  <tr><td align="center"><h2>03</h2><b>Prepare</b><br/>Power Query cleaning</td><td align="center"><h2>04</h2><b>Model</b><br/>Power BI and DAX</td></tr>
  <tr><td align="center"><h2>05</h2><b>Explain</b><br/>Report visuals and findings</td><td align="center"><h2>06</h2><b>Document</b><br/>Supporting project reports</td></tr>
</table>

## The production desk — project files

| Asset | Why it matters |
|---|---|
| [Raw Netflix dataset](Raw_Netflix_Dataset.xlsx) | Original source workbook |
| [Cleaned Netflix dataset](Cleaned_Netflix_Dataset.xlsx) | Prepared data |
| [Data-quality report](Cleaned_Data_Quality_Report.xlsx) | Workbook documenting quality review |
| [Power BI dashboard](Netflix_Content_Analysis_Dashboard.pbix) | Editable report for Power BI Desktop |
| [Documentation library](docs/README.md) | Index to the supporting project reports |

## Questions that guide the analysis

| Editorial angle | Analysis question |
|---|---|
| Format | How do Movies and TV Shows compare in the supplied records? |
| Genre | Which genres are most frequently represented? |
| Rating | Which content-rating groups occur most often? |
| Geography | How is country information distributed? |
| Time | How do title counts vary by release year? |
| Audience fields | What can the available rating-related fields support—and what remains unknown? |

## Visual direction

![Conceptual Netflix dashboard layout](images/dashboard-layout-preview.svg)

<sub>This graphic is a static layout concept, not a screenshot exported from Power BI Desktop. Open the PBIX file to inspect the editable report.</sub>

## Six chapters of the supporting report

The repository includes ten supporting PDF reports covering the project overview, source understanding, Excel quality checks, Power Query preparation, Power BI model, DAX/KPIs, dashboard design, business questions, findings and project conclusion.

**[Browse the numbered PDF documentation index →](docs/README.md)**

## Review the work in sequence

1. Compare the raw and cleaned workbooks.
2. Read the data-quality report and transformation notes.
3. Open the PBIX in Power BI Desktop.
4. Inspect the model, measures, filters and page design.
5. Compare report outputs with the written documentation.

## Interpretation note

All counts and distributions are specific to the supplied workbook. A release-year pattern does not explain why content was added or removed, and descriptive catalogue analysis does not establish audience preference, viewing behaviour or business causation.

---

<p align="center">
  <b>Case study owner: Shanmukh Koyya</b><br/>
  <a href="https://github.com/shanmukhkoyya">GitHub</a> ·
  <a href="https://www.linkedin.com/in/shanmukh-koyya/">LinkedIn</a> ·
  <a href="mailto:shanmukhkoyya1234@gmail.com">Email</a>
</p>