# US Presidents and Vice Presidents Data Cleaning 

**→ Project Focus:** Data Cleaning  
**→ Data Set Source:** `.xlsx`    
**→ Dataset Overview:** Contains information about US Presidents, Vice Presidents, their names, positions parties as well as their salaries.  

## Data Cleaning Steps
I followed these steps to clean up my data:  
**1.** Removed duplicate rows.  
**2.** Removed unnecessary columns.  
**3.** Cleaned `President` and `Vice President` columns, using `TRIM` and `PROPER` Excel functions.  
**4.** Cleaned `Prior Position` column: removed anomalies `e.g (1839â€“1841)`.  
**5.** Standardized `Party` column:  
   - Removed anomalies *e.g* `(April 4, 1841  â€“  September 13, 1841)`.  
   - Corrected Data entry error *e.g* (`Demorcatic` → `Democratic`, `Republicans` → `Republican`).
   
**6.** Converted `Salary` column from currency to numeric type for futur calculations.  
**7.** Converted `Date Created` and `Date Updated` columns to proper date format.     



***PS: Check the file to see the original Excel file and the cleaned version.***
