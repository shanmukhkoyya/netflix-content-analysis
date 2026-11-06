<div align="center">
<img src="assets/readme-hero.svg" width="100%" alt="Streaming catalogue editorial banner"/>
<h1>THE CATALOGUE EDIT</h1>
<h3>A DATA STORY IN SIX SCENES</h3>
<img src="https://img.shields.io/badge/EXCEL-217346?style=flat-square&logo=microsoftexcel"/> <img src="https://img.shields.io/badge/POWER%20QUERY-00A6A6?style=flat-square"/> <img src="https://img.shields.io/badge/POWER%20BI-F2C811?style=flat-square&logo=powerbi"/>
</div>

## The brief
Explore a supplied streaming catalogue by format, genre, rating, country and release year. This is a static learning dataset—not Netflix's current live catalogue.

## Editorial storyboard
| SCENE | PRODUCTION STEP | DELIVERABLE |
|:--:|---|---|
| 01 | **Ingest** source workbook | Raw Excel |
| 02 | **Inspect** structure and quality | Quality report |
| 03 | **Prepare** fields in Power Query | Cleaned workbook |
| 04 | **Model** the reporting data | Power BI model |
| 05 | **Visualise** catalogue patterns | Dashboard |
| 06 | **Document** decisions | PDF collection |

## The asset shelf
<details open><summary><b>Open the source and prepared files</b></summary>

| ORIGINAL CUT | CLEAN CUT | QUALITY CHECK |
|---|---|---|
| [Raw workbook](Raw_Netflix_Dataset.xlsx) | [Cleaned workbook](Cleaned_Netflix_Dataset.xlsx) | [Quality report](Cleaned_Data_Quality_Report.xlsx) |

</details>

<details><summary><b>Open the reporting package</b></summary>

- [Power BI dashboard](Netflix_Content_Analysis_Dashboard.pbix)
- [Documentation index](docs/README.md)

</details>

## Visual treatment
![Conceptual report layout](images/dashboard-layout-preview.svg)

<sub>Storyboard artwork only—not a screenshot exported from Power BI Desktop.</sub>

## Business recommendations

This project describes the **supply side** of a static catalogue: title type, genre, rating, country and release year. It does not include viewing hours, completion, search demand or subscriber behaviour. Use the catalogue analysis to frame decisions, then validate them with audience and commercial data.

1. **Compare catalogue coverage with audience engagement.** Identify genres, formats and regions with thin catalogue coverage, then compare those gaps with viewing hours, completion rates, search activity and subscriber demand before prioritising new content.
2. **Improve metadata quality.** Standardise genre, country, rating and release-year fields so content can be filtered and compared consistently across reports.
3. **Test content discovery changes.** Use catalogue segments to design small homepage or recommendation-placement tests. Judge them on engagement and completion measures, not on catalogue counts alone.
4. **Review regional and rating suitability.** Combine country and rating fields with local availability, audience requirements and content rights before making localisation or catalogue decisions.

**Decision boundary:** this learning dataset is not Netflix's current live catalogue. It cannot establish popularity, demand, acquisition value or the impact of a content decision. See the [Business Recommendations document](docs/09_Business_Recommendations.pdf) for the project's supporting report.

## Questions for the final cut
🎬 Movies vs TV shows · 🎭 Genre mix · 🔞 Rating distribution · 🌍 Country coverage · 📆 Release-year spread.

**Editorial note:** Catalogue composition does not measure audience preference, viewing behaviour or business causation.