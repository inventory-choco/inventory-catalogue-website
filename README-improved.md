# Inventory Catalogue Website

A GitHub Pages product catalogue powered by CSV files.

## Files to upload

- `index.html` — full searchable catalogue
- `New_Arrival.html` — new arrivals page
- `inventory_data.csv` — full catalogue data
- `New_Arrivals.csv` — new arrivals data
- `dirham-symbol.svg` — AED price icon
- `images/` — full catalogue product images
- `New_Arrivals_Images/` — new arrivals product images

## How to add products

1. Add a new row in `inventory_data.csv`.
2. Keep the same column names.
3. Upload the product image to the `images` folder.
4. Put the exact image filename in the `Image Filename` column.
5. Commit and push to GitHub.

## How to add categories

Add the category name in the `Category` column. The website automatically creates the dropdown and category chips.

## Recommended CSV columns

`Item Code`, `Item Description`, `Barcode`, `UOM`, `Category`, `Price`, `Color`, `Flavor`, `Weight Per Piece(In Grams)`, `Image Filename`

## GitHub Pages settings

Use branch: `main`  
Folder: `/root`  
Main page filename must be exactly `index.html`.
