# Fabric KPI Pipeline Migration

This project demonstrates the migration of legacy KPI reports into Microsoft Fabric using the medallion architecture (Silver → Gold) and Power BI.

## Tools Used
- Microsoft Fabric (Lakehouse, Gold Layer)
- Azure Data Factory (ADF)
- Power BI (with Row-Level Security)
- SharePoint
- Python, SQL

## Repo Contents
- `dax_measures.md`: DAX formulas used in Power BI
- `gold_model_description.md`: Data model logic in the Gold layer
- `uat_issue_log_sample.xlsx`: Sample of UAT validation log
- `pbix_sample_screenshot.png`: Dashboard preview (no real data)

## Impact
- Improved refresh time by 30%
- Applied Row-Level Security across departments
- Enabled reliable KPI insights via automated pipelines
