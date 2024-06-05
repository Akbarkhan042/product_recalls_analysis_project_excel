# PRODUCT RECALL ANALYSIS IN EXCEL

## PROJECT OVERVIEW

A product recall is a process initiated by manufacturers or distributors to remove or correct products that violate laws administered by regulatory bodies. These recalls aim to protect public health and well-being from products that pose risks of injury, gross deception, or are otherwise defective. Manufacturers and distributors undertake recalls voluntarily, though the regulatory bodies can issue orders for recalls in rare cases where a voluntary recall is not initiated.

Recalls involve several key components, including the development of a recall strategy that considers factors like the severity of the health hazard, ease of identifying the product, and the degree to which the product's deficiency is apparent to consumers or users. The recalling firm is responsible for notifying its direct accounts about the recall, providing clear information about the product, the reason for the recall, and instructions on how to handle the recalled products.

This communication is crucial for ensuring that the product is properly disposed of or corrected to prevent further harm.


![OIP](https://github.com/Akbarkhan042/product_recalls_analysis_project_excel/assets/156647226/b7d0da7e-7dc7-42f2-a527-514d46036a66)


Consumers play a critical role in product recalls by responding to recall notifications and taking appropriate actions, such as returning or disposing of the recalled products.


## TABLE OF CONTENT
[PROJECT OBJECTIVE](#project-objective)

[PROJECT WORKFLOW](#project-workflow)

[DATA CLEANING](#data-cleaning)

[DATA TRANSFORMATION](#data-transformation)

[DATA ANALYSIS](#data-analysis)

[DATA VISUALIZATION](#data-visualization)

[Dashboard in action Video.](#dashboard-in-action-video)

[FINDINGS](#findings)





## PROJECT OBJECTIVE

The objective of this data analysis project is to analyze the dataset having records about all the products recalls made by various manufacturers across different industries, visualize the results and create a dashboard of the results witha filter and interactivity.

The various Questions were explored like what is the  yearly trend of recalls and potentially affected consumers, types of recalls made, the manufacturers that made the most recalls, what is the most ferquent cause for recall etc.

### Dataset
The dataset contains recall records made by different manufacturers for the year 1994 through 2022.

We are working with 11 columns & 26590 rows of data.

### Tool
This project was completed in MS Excel only. From data import to data profiling, cleaning and transformation was all performed in Excel. Then after the dataset was analysed, visuals were created on the basis of those analysis and a dashboard was created with interactivity.

Different Excel tools that were utelised in this project:
- Power Query  : For data import, profiling, cleaning & transformation.
- Pivot Table  : For data summarization & aggregation and analysis.
- Pivot Chart  : For visualization.

## PROJECT WORKFLOW

The project workflow consisted of Data Import to Excel via the Power Query. Once the data was imported to power query the data was profiled for errors, nulls, empty records using various tool fror data profiling. Upon the completion of data profiling we proceeded to data cleaning and transformations.

## DATA CLEANING

As this dataset comes from Kaggle it was fairly clean and required very less cleaning. The data had soe nulls which was replaced to "unknown" using the replace value tool of power query. The data had some capitalization issue therefore we used textual tool like proper to getit into proper format.

The dataset also contained some column that were nor need for the analysis so we removed those using the remove column tool.

## DATA TRANSFORMATION

Not much of data transformation was required in this project.
We extracted year, month number and month name from the data column. For this purpose the Date tool from the Add Column tab was used because our aim was to add more columns to the dataset.


## DATA ANALYSIS

When the data cleaning and data transformation were complete we loaded the dataset to Pivot Table in order to summarize, aggregate and analyze our data.

We created different pivot tables to analyze different aspects of our dataset. We sorted and filtered the pivot tables too in order to arrange them in decending order and extract the top-10 values only.

The data field settings was utelized to get our intended aggregation like sum, average, count etc for the numerical values and to remane the columns in pivot tables accordingly.

## DATA VISUALIZATION

When we were done with our required analysis we visualized the results of the pivot tables using the Pivot Charts.

- Simple charts like a combo chart having 2 field as an Area chart and Line chart was used to display the trent over time.
- Pie chart was used to dipict part to whole relation.
- Bar charts was used to show the manufacturers with most recalls & potentially affected consumers and the most frequent cause for recall.
- A minimal design was chosen with very suttle colors in order to not make the dashboard busy.
- Popping colors was primarily used to guide viewer's attention to are of interest.

  

## **Dashboard in action Video.**



https://github.com/Akbarkhan042/product_recalls_analysis_project_excel/assets/156647226/6d891d17-1af9-4f01-87ca-2d9de8f2968b


## FINDINGS

Upon the completion of our data analysis we have the following findings.

1. The number of recall and potentially affected consumers follow an overall upwards trend over the years.
2. Automobile related recalls are the biggest category while *Child-seat* related recalls are the smallest amounting to **1%** of total but in my opinion that's still a lot.
3. Thye top-5 manufacturers with the most number of recalls made are all in the automobile sector of which top-3 are USA based & 4th is Germany based. This high number of recalls by automobile companies is in part due to the huge number of components used in them and the supplychain used where components comes fro tier1, tier2, tier3 or even more suppliers making quality control a daunting task.
4. The top-3 spots for the manufacturers with the most number of potentially affected consumers are again taken by automobile companies. At 4th place we have **TAKATA**- a Japanese manufacturer of *airbags* very infamous for their faulty airbags that resulted in a recall of approx 3.6 million vehicles.
5. The top-5 most frequent cause for recalls was equipment, electrical system, steering, suspension and service brake related issues.





