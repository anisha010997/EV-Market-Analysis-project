# Tableau Dashboard Plan

## Visual style
- White or very light grey background.
- Teal accent (`#0D9488`) for primary metrics; use consistent colors by category.
- Use one font family, restrained borders, and consistent spacing.
- Put global filters in one horizontal strip or a compact left sidebar.
- Use clear titles, axis labels, and units; avoid decorative chart effects.

## Dashboard 1 — Executive Overview
**KPI cards:** sample annual sales units, average range (km), average battery capacity (kWh), average sample rating.
**Charts:** sales by year (line), sales by vehicle category (bar), battery chemistry mix (bar), manufacturer ranking (bar).
**Filters:** Year, Manufacturer, Vehicle_Category, Battery_Chemistry, Manufacturing_Country.

## Dashboard 2 — Manufacturer Performance
- Horizontal bar: sample annual sales by Manufacturer.
- Scatter plot: Price_USD vs Driving_Range_km; color by Vehicle_Category.
- Bar: average Sample_Customer_Rating_5 by Manufacturer.
- Text table: manufacturer, model count, average range, average price, sample sales.
- Add dashboard filter actions so selecting a manufacturer filters other views.

## Dashboard 3 — Battery & Technology
- Bar: record count by Battery_Chemistry.
- Scatter plot: Battery_Capacity_kWh vs Driving_Range_km; color by chemistry.
- Bar: average range by chemistry.
- Bar: estimated charging hours by category or chemistry.
- Include a note that chemistry-specific sample data is synthetic and should not support real technical conclusions.

## Dashboard 4 — Geography & Customer Insights
- Map or filled map: sample record count by Manufacturing_Country (geographic role required).
- Bar: sample sales by country.
- Dot/bar: average sample rating by vehicle category.
- Scatter plot: Price_USD vs Sample_Customer_Rating_5.
- Add explanatory caption that countries, sales, and ratings are synthetic placeholders.

## Usability checklist
- Add filter cards and set relevant filters to “Apply to Worksheets > All Using This Data Source.”
- Use descriptive tooltips with metric units.
- Sort ranked bars descending.
- Format prices as currency and ratings to one decimal place.
- Use consistent colors across all dashboard pages.
- Check dashboard layout at a laptop-sized canvas before publishing.
