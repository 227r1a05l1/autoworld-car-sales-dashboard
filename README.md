# AutoWorld India – Interactive Car Sales Dashboard

## Included files
- `index.html` – browser dashboard (HTML/CSS/JavaScript)
- `AutoWorld_India_Dataset.xlsx` – synthetic dealership workbook used by the dashboard

## Run locally
1. Keep both files in the same folder.
2. Open a terminal in this folder.
3. Run `python -m http.server 8000`
4. Open `http://localhost:8000` in Chrome or Edge.

If Python is not installed, open `index.html` directly and click **Upload Excel** to select the workbook. The dashboard uses internet-hosted libraries (SheetJS and Chart.js), so an internet connection is required.

## Publish with GitHub Pages
1. Create a GitHub repository, for example `autoworld-car-sales-dashboard`.
2. Upload both `index.html` and `AutoWorld_India_Dataset.xlsx` to the repository root.
3. Open repository **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. The website URL will look like:
   `https://YOUR-USERNAME.github.io/autoworld-car-sales-dashboard/`

The dashboard loads the workbook automatically when both files are in the repository root. The workbook is public if the repository is public. Do not upload real customer personal information.

## Dashboard features
- KPI cards for net sales revenue, cars sold, average selling price, gross profit and available stock
- Filters for brand, showroom, region, fuel type and year
- Monthly revenue trend
- Revenue by brand
- Showroom sales performance
- Inventory status
- Sales by fuel type
- Top-selling models and recent transactions

## Data notes
This is a synthetic training dataset. Values and customer identities are fictional and are not actual AutoWorld records or verified market quotations.
