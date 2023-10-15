# STAT301
Group Project for STAT301

### **Vancouver Crime Report Dataset**

#### **Source**
This dataset has been sourced from Kaggle and can be accessed via the following link: 
[Vancouver Crime Report on Kaggle](https://www.kaggle.com/datasets/agilesifaka/vancouver-crime-report/data).

#### **Description**
The Vancouver Crime Report dataset provides comprehensive data on reported crimes in Vancouver from the years 2003 to 2019.

### **Note on Dataset Modification**

For this assignment, the original dataset from Kaggle, which covered crime records from 2003 to 2019, had to be reduced in size to accommodate GitHub's file size restrictions. The original dataset can be accessed [here](https://www.kaggle.com/datasets/agilesifaka/vancouver-crime-report/code) and is approximately 59.5 MB in size.

To fit within GitHub's 25 MB file size limit, the dataset was filtered to include only records from the years 2014 and 2019. This was done to examine changes over a 5-year gap. The filtering was performed using the `pandas` library in Python, and as a result, the size of the dataset was reduced to 6.4 MB.

#### **Characteristics**
- **Number of Observations**: 624039
- **Number of Variables**: 10

#### **Variables**:
  - `TYPE`: The category of the crime (e.g., Break and Enter Commercial).
  - `YEAR`: The year in which the crime occurred.
  - `MONTH`: The month in which the crime occurred.
  - `DAY`: The day of the month in which the crime occurred.
  - `HOUR`: The hour of the day (in 24-hour format) when the crime occurred.
  - `MINUTE`: The exact minute when the crime occurred.
  - `HUNDRED_BLOCK`: Anonymized block address where the crime took place.
  - `NEIGHBOURHOOD`: The neighborhood in Vancouver where the crime occurred.
  - `X`: The X-coordinate (likely in UTM or a similar coordinate system) for the location of the crime.
  - `Y`: The Y-coordinate (likely in UTM or a similar coordinate system) for the location of the crime.

#### **Data Collection**
The dataset captures crime reports in Vancouver from the year 2003 to 2019. The data collection method and original source are not specified in the provided snippet but may be available on the Kaggle dataset page or from the original data provider.

#### **Usage**
This dataset has been selected for the group project to explore and formulate research questions related to crime patterns in Vancouver. It provides detailed information about the type, time, and location of crimes, making it a valuable resource for analysis.
