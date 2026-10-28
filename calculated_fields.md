# Example Tableau Calculated Fields

Create these calculated fields only after connecting `data/ev_market_data.csv`.

## Total Sample Sales
```tableau
SUM([Sample_Annual_Sales_Units])
```

## Average Driving Range (km)
```tableau
AVG([Driving_Range_km])
```

## Average Battery Capacity (kWh)
```tableau
AVG([Battery_Capacity_kWh])
```

## Average Sample Rating
```tableau
AVG([Sample_Customer_Rating_5])
```

## Sample Sales Share
```tableau
SUM([Sample_Annual_Sales_Units]) / TOTAL(SUM([Sample_Annual_Sales_Units]))
```
Set the table calculation to compute using Manufacturer (or the dimension used in the chart).

## Model Count
```tableau
COUNTD([Vehicle_ID])
```

## Important
The included sales and ratings are synthetic. These calculations demonstrate Tableau techniques; they are not actual market statistics. For year-over-year growth, use a date/year-aware table calculation such as Percent Difference from Previous when the view is sorted by Year.
