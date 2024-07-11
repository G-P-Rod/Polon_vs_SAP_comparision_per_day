# Polon_vs_SAP_comparision_per_day
The project is aimed at data analysis, specifically comparing data from SAP and POLON. The analysis involves extracting, processing, comparing, and formatting data from these sources. Below is an overview of the project with detailed explanations of the code and its components.

## Contents
* [Introduction](#introduction)
* [SAP Data Preparation](#sap-data-preparation)
* [POLON Data Preparation](#polon-data-preparation)
* [Data Comparison and Merge](#data-comparison-and-merge)
* [Styles Changes](#styles-changes)
* [Conclusion](#conclusion)

## Introduction
The project aims to analyze and compare personnel data from SAP and POLON databases, specifically focusing on academic staff at Warsaw University of Technology. It involves tasks such as data extraction, processing, comparison, and formatting for visualization and further analysis.

## SAP Data Preparation
The **'sap_data_prepare'** notebook focuses on preparing data extracted from the SAP database. It includes the following tasks:

**Data Extraction**: Retrieving personnel data from the SAP database.  
**Data Cleaning**: Renaming columns, standardizing formats, and handling missing or duplicate values.  
**Data Segmentation**: Dividing the dataset into two main groups: teachers and non-teachers based on their job roles.  
**Data Formatting**: Standardizing formats for easier comparison with POLON data.  

## POLON Data Preparation
The **'polon_data_prepare'** notebook is dedicated to preparing data obtained from the POLON database. It involves similar tasks as SAP data preparation but tailored to POLON's data structure. Tasks include:

**Data Extraction**: Reading and loading data from the POLON database.  
**Data Filtering**: Selecting records relevant to academic staff at Warsaw University of Technology.  
**Data Standardization**: Standardizing formats, combining name and last name, and renaming columns for consistency.  
**Data Segmentation**: Segmenting data into teachers and non-teachers categories.  

## Data Comparison and Merge
The **'merge_and_save'** notebook focuses on comparing data from SAP and POLON databases and merging them based on unique identifiers (PESEL numbers). It includes the following tasks:

**Teachers Comparison**: Comparing teacher data between SAP and POLON databases.  
**Non-Teachers Comparison**: Comparing non-teacher data between SAP and POLON databases.  
**Saving Comparison Results**: Saving the comparison results to Excel files for further analysis.  

## Styles Changes
The **'styles_changes'** notebook defines functions to apply styles and formatting to Excel worksheets, enhancing the readability and visual appeal of the comparison results. Tasks include:

**Cell Styling**: Setting borders, alignment, and fill colors to improve visual clarity.  
**Column and Row Formatting**: Adjusting column widths and row heights for better presentation.  
**Conditional Formatting**: Applying color codes to highlight differences between corresponding cells.  

## Conclusion
This document details the project structure and the tasks performed in each notebook. Further details about the code can be found in the individual notebooks listed above. An example of the program's output is below:

Comparison of employees from the teacher group:  
![image](https://github.com/G-P-Rod/Polon_vs_SAP_comparision_per_day/assets/143654189/11a9d506-8a65-4ebd-a59f-13d906d2c1a9)

  
Comparison of employees from the not teacher group:  
![image](https://github.com/G-P-Rod/Polon_vs_SAP_comparision_per_day/assets/143654189/9dbdaa8c-5cdd-4993-a3b7-ba671e5c173e)
