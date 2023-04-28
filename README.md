# VBA Homework Solution: The VBA of Wall Street

## Background

In this homework assignment, I used VBA scripting to analyze generated stock market data for 2018, 2019, and 2020. 

### Before opening the homework spreadsheet and coding in VBA

1. I created a new repository in GitHub for this project called `VBA-challenge`. 

2. Inside the new repository that I created, I attempted to add the Excel Spreadsheet "Multiple_year_stock_data.xlsx", that included the stock data to be used for analysis; however, it was too large to upload to GitHub.  That spreadsheet can be downloaded at Module 2 Challenge link https://courses.bootcampspot.com/courses/3527/assignments/54069?module_item_id=961284

### After developing and running the VBA macro to analyze the generated stock market data for 2018, 2019, and 2020

1. Attempted to add the Macro Enabled Excel Spreadsheet and VBA Macro file, "Multiple_year_stock_data_solution.xlsm", that resulted from running the VBA macro script for analysis.  However, it was too large to upload to GitHub.  

2. Uploaded the screenshots of the solution worksheets, for each of the years 2018, 2019, and 2020.  These 3 screenshots are the solution tabs from the Macro Enabled Excel Spreadsheet titled "Multiple_year_stock_data_solution.xlsm". (Please refer to bullet 1 above).

3. Uploaded the main VBA script to run the analysis in 2 different extension files; .bas (extension version when exporting macro from "Multiple_year_stock_data_solution.xlsm") and .txt.  Please copy the VBA script code from the Multiple_year_stock_data_solution.txt file and paste it to run  using data at the excel spreadsheet "Multiple_year_stock_data.xlsx" that can be downloaded at Module 2 Challenge.  

### Files including data used for analysis and the solution output

* Multiple_year_stock_data.xlsx - Ran VBA scripts on this data to generate the final solution output.  
* Multiple_year_stock_data_solution.xlsm - The macro enabled spreadsheet that included the final solution output and VBA macro script.

### VBA Scripting file versions; in .bas and .txt (please refer to bullet 3 above)

* Module1.bas

* Multiple_year_stock_data_solution.txt (Please copy and paste this VBA script, lines 2 to 142, to run using "Multiple_year_stock_data.xlsx" data) 

### Stock Market Analyses screenshots

* Screenshot Multiple_year_stock_data_solution 2018 worksheet.jpg

* Screenshot Multiple_year_stock_data_solution 2019 worksheet.jpg

* Screenshot Multiple_year_stock_data_solution 2020 worksheet.jpg

## Analysis Steps

1. Created a script that loops through all the stocks for one year and generated output for the following information:
  	* The ticker symbol.
  	* Yearly change from opening price at the beginning of a given year to the closing price at the end of that year.
  	* The percent change from opening price at the beginning of a given year to the closing price at the end of that year.
	* The total stock volume of the stock.

2. Used conditional formatting that highlighted positive yearly change in green and negative yearly change in red.

3. Added functionality to the script to return the stock ticker with the "Greatest % increase", "Greatest % decrease", and "Greatest total volume". 

4. Made the appropriate adjustments to the VBA script to allow it to run on every worksheet (that is, every year) just by running the VBA script once.

## References

* Dataset generated by Trilogy Education Services, LLC.
* Our instructor, Ms. Alexandria Kalika, provided us with a skeleton VBA script to get us started.
* Study group initiated by fellow student, Mr. Abel Habte, was extremely helpful in resolving some of the VBA script issues I was struggling with.
