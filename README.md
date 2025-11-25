# RAWgraphs


Author email: 22f3001685@ds.study.iitm.ac.in

This folder contains:
- `salaries.csv` : sample data (18 rows) for a beeswarm plot showing salary distribution by department and level.
- `chart.png` : a preview beeswarm-like plot generated locally with seaborn (for preview only). The validated `chart.png` for your repo must be created using RAWGraphs as requested — instructions are below.

## How to use with RAWGraphs
1. Go to https://rawgraphs.io/
2. Click **Start** → **Load your data** → paste the contents of `salaries.csv` (open it in a text editor and copy) or upload the CSV.
3. Choose **Beeswarm Plot**.
4. Map:
   - `Y` (or axis): `salary` (continuous)
   - `X` (or grouping / stratify): `level` or `department` depending on layout preference
   - `Color` (or color-by): `department`
   - `Size` or `Point size`: leave default or map to nothing (salary is already on axis)
5. Customize colors: pick a professional palette (e.g., `Set2` or `Tableau`), adjust point radius for readability.
6. Add labels: Title: "Employee Salary Distribution — Beeswarm", subtitle explaining sample sizes, axis labels.
7. Export: choose PNG, set canvas to 512×512 (or between 300–512), and download.

Verify your exported PNG dimensions before committing to repository.
