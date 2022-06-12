# sales-summary-report
In this project, i build a report in Power BI from Excel workbook

## Case Study
I was given an excel workbook containing sales records of a business from 2013 to 2014 to answer the following questions
- Which month and year had the most profit?
- Where is the company seeing the most success (by country)?
- Which product and segment should the company continue to invest in?

## Getting the data
[Download the dataset](https://go.microsoft.com/fwlink/?LinkID=521962)

## Preparing data
Using Power Query Editor, 
- i changed the data type of Units Sold(Column) from Decimal to Whole number. Not a good practice but It doesn’t make sense to have 0.2 or 0.5 of a unit sold
- Also i changed the Segement to Uppercase. Just for readability in the Visualization
- Renamed Month name to Months
- Excluded Montana products from the dataset because it was discontiuned(using filtering)
- Added a new table; calendar using DAX formula - calendar = Calendar(DATE(2013,01,01),DATE(2014,12,31))

## Observation
In summary, this report answers this top questions:

Which month and year had the most profit? *December 2014*

Which country is the company seeing the most success in? *In Europe, specifically France and Germany.*

Which product and segment should the company continue to invest in? *The company should continue to invest in the Paseo product and target the Small Business and Government segments.*

## Contact me
Email - jeffenyinnah@gmail.com

[LinkedIn](https://www.linkedin.com/in/amamihe-kaiser/)
