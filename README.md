<p align="center"><img src="assets/readme-hero.svg" width="100%" alt="Streaming catalogue analytics"/></p>

<div align="center">

# THE CATALOGUE EDIT
### A streaming-library data story

<img src="https://img.shields.io/badge/EXCEL-217346?logo=microsoftexcel&style=for-the-badge"/>
<img src="https://img.shields.io/badge/POWER%20QUERY-00A6A6?style=for-the-badge"/>
<img src="https://img.shields.io/badge/POWER%20BI-F2C811?logo=powerbi&style=for-the-badge"/>

</div>

## Editor's brief

A supplied streaming catalogue is explored by format, genre, content rating, country and release year. This is an offline project dataset—not Netflix's current live catalogue.

## Production storyboard

<table>
<tr><td align="center" width="33%"><h2>01</h2><strong>INGEST</strong><br/>Excel source</td><td align="center" width="33%"><h2>02</h2><strong>INSPECT</strong><br/>Data-quality review</td><td align="center" width="33%"><h2>03</h2><strong>PREPARE</strong><br/>Power Query</td></tr>
<tr><td align="center"><h2>04</h2><strong>MODEL</strong><br/>Power BI structure</td><td align="center"><h2>05</h2><strong>VISUALISE</strong><br/>DAX & report</td><td align="center"><h2>06</h2><strong>DOCUMENT</strong><br/>PDF reports</td></tr>
</table>

## Browse the production assets

| Cut | Deliverable | File |
|---|---|---|
| Original | Raw workbook | [Open XLSX](Raw_Netflix_Dataset.xlsx) |
| Prepared | Cleaned workbook | [Open XLSX](Cleaned_Netflix_Dataset.xlsx) |
| Quality | Data-quality report | [Open XLSX](Cleaned_Data_Quality_Report.xlsx) |
| Dashboard | Power BI report | [Open PBIX](Netflix_Content_Analysis_Dashboard.pbix) |
| Documentation | Report collection | [Open index](docs/README.md) |

## Visual direction

![Conceptual dashboard layout](images/dashboard-layout-preview.svg)

<sub>Concept artwork for the report layout; not a screenshot exported from Power BI.</sub>

## Questions for the analyst

- 🎬 Is the supplied catalogue weighted toward movies or TV shows?
- 🎭 Which genres appear most often?
- 🔞 How are content ratings distributed?
- 🌍 Which countries appear in the dataset?
- 📆 How does release-year coverage vary?

<details><summary><strong>Reviewer's screening checklist</strong></summary>

- Compare raw and cleaned workbook structures.
- Inspect the quality report and documented cleaning decisions.
- Open the PBIX and review model relationships.
- Check measures and visual interactions.
- Reconcile reported patterns to the source data.

</details>

**Interpretation limit:** Catalogue composition does not reveal audience preference, viewing behaviour or business causation.