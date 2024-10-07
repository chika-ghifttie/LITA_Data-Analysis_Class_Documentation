# LITA_Data-Analysis_Class_Documentation

### Project Title: Pioneer Staff Schedule Analysis

### Project Overview
---
The project focuses on cleaning and analyzing the Pioneer Staff Schedule Data of 'Just Vacated Limited'. The dataset provided contains names of pioneering staff members and company locations. In this analysis, we seek to extract and clean data, standardize staff names, remove unnecessary spaces and also generate more data to enable us perform basic data analysis.

### Data Sources
---
The data used for this project was provided by our instructor via our Telegram group for educational purpose. The original source of the data is in the form of an Excel file named Text.xlsx.

### Tools Used
---
- Microsoft Excel [Download Here](https://www.microsoft.com)
    1. For Data Cleaning
    2. For Analysis
    3. For Data Visualization
- SQL - Structured Query Language [Version 20.0]
    1. For Querying of Data
    2. For Grouping of Data
- GitHub for Portfolio Building

### Data Cleaning And Preparation
---
#### Initial Data Limitations And Challenges
  - Only staff name and location were provided
  - Names scattered with inconsistent format (Block Letters, Mixed Case)
  - Unnecessary spaces in names
    
    INITIAL DATA TABLE (Dirty Data)

      ![Dirty Data](https://github.com/user-attachments/assets/9863972a-afeb-4f74-9b96-9e8c3f7d0160)

    #### Cleaning Steps
    To ensure a robust dataset and to facilitate analysis, The following cleaning steps were performed:
      - *Addressed scattered formatting and unnecessary spacing in names,*
      - *A realistic Salary Data was also generated as this was not available in the original Dataset. This was achieved by using Excel's "RAND" Function.*

        CLEANED DATA TABLE
        ![Cleaned Data1](https://github.com/user-attachments/assets/1a691bb1-b786-4444-99a0-a93a17bfb7d5)

        ### Exploratory Data Analysis
        ---
        This has to do with exploring of data to answer some questions about the data. The Staff Data was explored to address inconsistencies and answer key questions such as :
        - What is the Total No of Staffs?
        - What is the Average Salary of Staff?
        - What is the Highest Salary of Staff?
        - What is the Fourth Highest Salary of Staff?

          ### Data Analysis
          ---
          This section provides a collection of some basic code,queries and even DAX expressions used in this analysis;

          ```SSQL
          SELECT Location, Salary FROM
          Staff GROUP BY Location
          ```
          ### Data Visualization
          ---
          ![Bar Chart 1](https://github.com/user-attachments/assets/e4cc6029-83df-4032-8d53-143b492e3529)

          #### Findings And Insights
          ---
          

        
        

    
        
    
    

    


