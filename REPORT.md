# Portfolio Cleanup Report (2025-08-19)

## Inventory Overview
Repository | Visibility | Languages | Last Update | Default Branch | Topics
--- | --- | --- | --- | --- | ---
etl-bi-pipeline | public | Python | 2 months ago | main | python, etl, bi
automation-kpi | public | Python | 2 months ago | main | python, analytics, kpi
aml-kyc-triage-simulator | public | Python | 7 months ago | main | python, aml, kyc
risk-model-validation | public | Python, Jupyter Notebook | 1 week ago | main | python, risk, model-validation
Mokshith-Talari | public |  | 7 months ago | main | —
Customer-Segmentation-RFM-Analysis | public |  | now | main | customer segmentation, rfm, analysis
portfolio-overview | public |  | now | main | portfolio, overview

*See `inventory.csv` for a machine-readable version.*

## Actions Taken Per Repository
- **etl-bi-pipeline**
  - Created backup branch `backup/20250819`.
  - Added MIT `LICENSE` file.
  - Reviewed and updated README with Problem → Approach → Results and quickstart instructions referencing representative impacts (18% churn reduction & ~$120k/year savings).
  - Confirmed CI workflow in `.github/workflows/tests.yml` runs on Python 3.11 and passes.
- **automation-kpi**
  - Created backup branch `backup/20250819`.
  - Verified MIT license present.
  - Confirmed README completeness.
- **aml-kyc-triage-simulator**
  - Created backup branch `backup/20250819`.
  - Verified MIT license present.
  - CI and README reviewed.
- **risk-model-validation**
  - Created backup branch `backup/20250819`.
  - Ensured MIT license present.
  - Confirmed languages: Python & Jupyter notebooks.
- **Mokshith-Talari**
  - Created backup branch `backup/20250819`.
  - Confirmed MIT license and README.
- **Customer-Segmentation-RFM-Analysis**
  - Created backup branch `backup/20250819`.
  - Added MIT `LICENSE` file (previously missing).
- **portfolio-overview**
  - Created new repository with MIT license and README.
  - Added `inventory.csv`.
  - Began drafting report and README updates.

## Issues and Pull Requests
No open pull requests were created during this cleanup. All changes were committed directly to `main` after backing up original branches.

## Recruiter Script
Here’s a five‑bullet script highlighting this portfolio:
1. **SQL & Python Automation:** Built end‑to‑end ETL pipelines transforming CSV data into queryable SQLite tables with clear KPIs and automated tests.
2. **BI Dashboards & Visualization:** Delivered interactive revenue dashboards (Matplotlib/Power BI/Tableau ready) that translate raw data into actionable insights.
3. **Risk & Compliance Analytics:** Validated scoring models using PSI/KS statistics and threshold analyses to ensure stability and fairness across populations.
4. **Operational KPIs:** Developed lightweight log parsers converting raw application logs into metrics like total requests, error rate, and peak throughput.
5. **Outcome‑Focused Impact:** Demonstrated ability to deliver results—including projects that mirror an 18% churn reduction and ~$120K annual savings.

Review the repos `etl-bi-pipeline`, `risk-model-validation`, `automation-kpi`, and this `portfolio-overview` for code samples, documentation, and tests.

## Recommended Automations
- Schedule weekly Dependabot updates for each repository to monitor dependency security.
- Run monthly secret scans across the organization to ensure no credentials leak into source control.
- Check links in README files quarterly to avoid dead references.
