# DSA_PROJECT_2
This is my capstone project for Digital Skillup Africa (DSA) course (July 2025) by Incubator Hub.

## PROJECT TOPIC: PALMORA GROUP HR ANALYSIS

### PROJECT OVERVIEW
The objective of this project is to give an insight that will guide the management of Palmora Group to make informed decision on how to address gender inequality as published by the media. The decision will be guided by results gotten from analyzing the data received from the HR department. 

#### Data Source
The data source is Palmoria Group Bonus Rules.xlsx and Palmoria Group emp-data.csv which contains information from the HR department. The CSV file contains 1016 columns/6rows personnel data (e.g name, gender, department, salary) and the Microsoft Excel file contain (6 columns/12 rows) bonus rule that will be used to calculate *BONUS* to be paid to each employee. 

#### Tools Used
-	Microsoft Power Bi

### METHODOLOGY

#### Data Cleaning and Preparation
Below are actions performed
-	Data Inspection 
-	Data cleaning and formatting which include;
     -  Removing rows that does not have salaries, and department indicated as *NULL* by using the *filter* on the respective columns.
     -  Use *Replace Values* to populate the empty cells on the "Gender" column.
     -  Use *Keep Rows* to the ensure rows/values to work with are fixed.
     -  *Duplicate* the table in 12 Number, *Filter* to have one ‘Department’ in a table.
     -  Use *Add Column* then *Conditional Column* to populate the ‘Bonus Ratio’ using the ‘Bonus Rule Microsoft file’ as a guide. Do this for all the 12 duplicated tables.
     -  *Append* all 12 tables to become one.
     -  Use *Add Column* then *Conditional Column* to populate the ‘Salary Structure’ column.
     -  Use *Table Tools* then *New Column* to populate the calculated column ‘Bonus’ by multiplying the values in the ‘Salary’ and ‘Bonus Ratio’ columns.
     -  Use same steps as mentioned above to generate another calculated column “Total Amount paid to Employee” by adding values in the ‘Bonus’ and ‘Salary’ columns.
     -  While using the listed steps ensure to use *Close and Apply* in other to save output.




#### Exploratory Data Analysis (EDA)
This involves the exploring of the data to answer some of the questions like
-	Gender distribution per region 
-	Rating based on gender
-	Salary structure with regards to gender
  
#### Data Analysis
This is where we use the *Report view* to visualize data cleaned and generated.
 Example; On the *Build Tab* choose a preferred chart that best helps to describes/explains the data you are analyzing. 

 

### RESULTS/FINDINGS
-	In general, the organization with regards to all the region has 465 males, 441 females and 40No of not specified gender making it a total of 946 personnel. 
-	Using the bench mark of 5 and above, the following regions and respective departments have more males than females. The difference (in gender) is the number written in
     brackets by each Region_Department.
     Abuja_Lega l(10), Abuja_Accounting (7), Kaduna_Marketing (7), Lagos_Support(6), Kaduna_Legal (5), Product_Management (5), Kaduna_sales(5).

     For Region_Department with more females than males;
     Lagos_Research and Development (8)
     Abuja_Training(7)
     Kaduna_Engineering(5)
-	On rating, more females are rated **Very Good** and **Good** while the **Average**, **Poor** and **Very Poor** rating have more males than females.
-	As required by the new regulation, only 292 employees of Palmora earn $90,000 and above. Using $90, 000 as a minimum, there is gender pay gap in Abuja (male-53, female-39)
     and in Kaduna (male-59, female-47).
 

### RECOMMENDATION
The Palmora Group should issue a media publication to counter the perception published by the media and include the analysis done as evidence.

<img width="1110" height="513" alt="No 5" src="https://github.com/user-attachments/assets/751fbd11-058f-40e3-9a0e-b138370364db" />
<img width="876<img width="925" height="483" alt="4B" src="https://github.com/user-attachments/assets/e830cb73-10ca-4f70-b819-241f1d40a1b8" />
" height="489" alt="No 1" src="https://github.com/user-attachments/assets/4277346b-5e04-491f-aa5e-4f63eecefc0b" />
<img width="742" height="434" alt="No 2" src="https://github.com/user-attachments/assets/c8b6dc9f-2e7f-4102-9fb4-ddd75a17db75" />
<img width="706" height="435" alt="No 3" src="https://github.com/user-attachments/assets/64681e73-ecb6-4714-8442-146bdf115cca" />
<img width="875" height="511" alt="No 4" src="https://github.com/user-attachments/assets/a388c4cf-7823-469d-a9e0-0e10160b3bce" />
<img width="894" height="500" alt="No 1A" src="https://github.com/user-attachments/assets/27051a59-93dd-4b5d-a7b9-00996f2361b9" />
