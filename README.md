# Excel Challenge: Kickstart My Chart
by Kurt Pessa

## Initial Steps
1. Created new space `excel-challenge` in Google Drive.
2. Stored `excel-challenge.xlsx` and `excel-challenge.docx` in folder with shareable link at  `https://github.com/kpessa/excel-challenge`

### Section 1 - Manipulating Data
1. Used conditional formatting to color different cells based on `state` column. 
![](Images/state.png)
2. Created a new `column O`  called `Percent Funded" to determine how much money a campaign made to reach its initial goal. 
![](Images/percent_funded.png) 
	- Used conditional formatting to fill each cells using a three-color scale. 
![](Images/three_color_scale.png)
3. Created a new `column P` called `Average Donation` using a formula to uncover how much each backer for the project paid on average.	
![](Images/average_donation.png)
4. Created a new `column Q` named `Sub-Category`, which used a split-like excel-functions `=LEFT()` and `=RIGHT()` to split the `Category and Sub-Category` into two parts.
![](Images/split.png)

### Section 2 - PivotTable1
1. Created a pivot table in a new sheet that counted how many campaigns were successful, failed, canceled or currently live per **category**.
2. Created a stacked column pivot chart that can be filtered by `country`
![](Images/pivot_table_1.png)

### Section 3 - PivotTable2
1. Created a pivot table in a new sheet that counted how many campaigns were successful, failed, canceled or currently live per **sub-category**.
2. Created a stacked column pivot chart that can be filtered by `country` and `parent-category`
![](Images/pivot_table_2.png)
