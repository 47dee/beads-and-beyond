# Beads & Beyond by Subha: order page

- `index.html`: the page. Settings are at the top of the script (owner number, Google Sheet link).
- `products.js`: backup product list, used when no Google Sheet link is set (or if the sheet cannot be reached).
- `images/`: product photos named by code (e.g. `BR-ADCBB.jpg`) plus `logo.jpg`.

## Manage products from a Google Sheet
1. Upload `BeadsAndBeyond_Products_Sheet.xlsx` to Google Drive and open it with Google Sheets.
2. File > Share > Publish to web > choose the "Website Products" tab and "Comma-separated values (.csv)" > Publish.
3. Copy the link and paste it into `SHEET_CSV_URL` in `index.html` (between the quotes). Save.
