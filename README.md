### LITA CLASS DATA ANALYSIS PROJECT: SALARY ANALYSIS
---

## Context

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

### Project Overview
---
The project involves calculating the total salary, average salary, highest and lowest salary of the data set to provide insights into overall compensation levels.

### Data Sources
---
The dataset was sourced from the ID and Co.'s HR Information System. The dataset includes the followwing information about the employees;
- Staff Names
- States
- Staff's salaries

### Tools Used
---
- Microsoft Excel [Download Here](https://wwww.microsoft.com)
  1. For Data Cleaning
  2. For Analysis
  3. For Visualization- Column chart was used to visually represent key insights
### Data Cleaning and Preparations
---
In the initial phase of the Data Cleaning and preparations,the following action were performed;
1. Data loading and Inspection
2. Handling missing variables
3. Data Cleaning and formating

### Exploratory Data Analysis
---
EDA invoved the exploring of Data to answer some questions about the Data which are as follows;
-Total Salrary of staffs in a Bayelsa State
- Average salary staffs in Oyo State
- Highest Salary in Edo State
- Lowest Salary in Taraba State
- Total number of staffs in Nassarawa State
- Grand Total of the staffs' sallaries
- Average salary of staffs in all the states
- Highest Salary amoung all the staffs
- Lowest Salary amoung all the staffs
- Total No of Staffs in Company
- Fourth Highest Salary amoung all the staffs
- Third Lowest Salary amoung all the staffs



### Data Analysis
---
## Formulars Used
## Excel Functions
- **Grand Total Salary**:
  `SUM(D8:D27)` - Sums all salaries in the cells from D8 through D27
  ![Screenshot (182)](https://github.com/user-attachments/assets/e234ff91-6f6b-4286-b595-068d6d35dd38)
- **Average Salary**:
  `AVERAGE(D8:D27)` - Calculate the Average salary of all the staffs from cells D8 to D27
  ![Screenshot (185)](https://github.com/user-attachments/assets/a241d50e-fa77-42d7-b8e3-c04d95dfb62d)

- **Highest Salary**:
  `MAX(D8:D27)` - To calculate the highest salary among the staffs from cells D8 to D27
  ![Screenshot (185)](https://github.com/user-attachments/assets/ff482a78-03fb-4d96-b563-1adaf18b19ad)

- **Lowest Salary**:
  `MIN(D8:D27)` - To calculate the lowest salary among the staffs from cells D8 to D27
  ![Screenshot (186)](https://github.com/user-attachments/assets/a33e9d60-b0d0-4100-affd-d2dd862809fc)

- **Total Number of Staffs**:
  `COUNT(D8:D27)` - To calculate the total number of staffs from cells D8 to D27
  ![Screenshot (186)3](https://github.com/user-attachments/assets/53cd68dc-2bae-4f4c-95ce-ed48cd7d100e)

- **Fourth Highest Salary**:
  `LARGE(D8:D27,4)` - To calculate the Fourth Highest Salary amoung all the staffs
  ![Screenshot (186)5](https://github.com/user-attachments/assets/61cef03a-3d28-465b-94f3-7144c9cef05e)

- **Third Lowest Salary**:
  `SMALL(D8:D27,3)` - To calculate the Third Lowest Salary amoung all the staffs
  ![Screenshot (186)2](https://github.com/user-attachments/assets/3b4e3a39-a3a8-4678-a53b-ce9e9d9590b8)

#### Contional Functions
- **Bayelsa Total Salary**:
  `SUMIF(C8:C27,C9,D8:D27)` - To calculate the total salary collected by the staffs in Bayelsa state
  ![Screenshot (187)](https://github.com/user-attachments/assets/f315fc06-8052-4da3-bcd8-5ab4ec6e078e)

- **Average Salary of Oyo**:
  `AVERAGEIF(C8:C27,C20,D8:D27)` - To calculate the total salary collected by the staffs in Oyo state
  ![Screenshot (188)](https://github.com/user-attachments/assets/a28fd99c-cacd-4aca-b286-e903d214eb95)

- **Higest Salary in Edo**:
  ` MAXIFS(D8:D27,C8:C27,C12)` - To calculate the highest salary collected by the staffs in Edo state
  ![Screenshot (188)](https://github.com/user-attachments/assets/f1861776-dcde-44af-8a60-6669bf542925)

- **Total Number of Staffs in Nassarawa**:
  ` COUNTIF(C8:C27,C16)` - To calculate the Total number of staffs in  Nassarawa state
  ![Screenshot (187)7](https://github.com/user-attachments/assets/d0b4922a-ef00-4e35-bbab-8ed4b36be063)

- **Lowest Salary in Taraba**:
  ` MINIFS(D8:D27,C8:C27,C23)` - To calculate the Lowest salary collected by the staffs in Taraba state
  ![Screenshot (187)9](https://github.com/user-attachments/assets/0e874a9b-ae0e-4677-b590-689d11e02657)

 

### Data Visualization
---
## Salary by States Column Chart 
![Screenshot (181)](https://github.com/user-attachments/assets/e0d60f72-3964-46fc-b804-ab9f98f0049a)
### 1. Inferences
- The state with the highest total salary is Bayelsa and with the least salary is Cross River State.
- Salaries are high in Bayelsa indicating that the cost of living is high andmay also indicate that the state has a high demand for the skills and roles employed  in the company.

### 2. Strategic Recommendation
- The management should consdider conducting regular salary benchmark in each states to make sure that the salaries align with local market rate and cost of living.
- They should also offer pay increases based on skill levels or certificates which can help bridge the gap across states and reward employess for their contributions.
  
### 3. Conclusion
Strategic interventions like cost of living adjustments and skills based pay can address the differences in salariescreating a more equitable, transparentcompensation structure.
