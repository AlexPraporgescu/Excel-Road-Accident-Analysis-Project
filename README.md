# Road-Accident-Analysis-Excel-Project

  ## <ins>Table of Contents</ins>

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Stakeholders](#stakeholders)
- [Data Preparation and Cleaning](#data-preparation-and-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)
- [Notes](#notes)

### <ins>Project Overview</ins>

This data analysis project aims to provide insights into the different aspects influencing the occurence of road accidents in the UK.
By analysing different aspect of the data, I seek to answer the stakeholders questions, identify trends, make data-driven recommendations and
gain a deeper understanding of the factors that may lead to road accidents. There was also created a dynamic dashboard helping the stakeholders gain even more
insights by filtering and sorting the data:

![image](https://github.com/AlexPraporgescu/Road-Accident-Analysis-Excel-Project/assets/158141333/d66936b0-bd4b-498f-9550-129bbfca3b98)

### <ins>Data sources</ins>

Road accident data: The primary dataset used for this analysis was the "Road Accident Data.xlsx" containing detailed information about
different types of road accidents ocuring in the UK. This dataset is an extras of the UK Road Accidents Dataset found on Kaggle.com.

### <ins>Tools</ins>

 - Excel - Data preparation, data cleaning, data analysis, data visualisation (dashboard) [Download here](https://www.microsoft.com/ro-ro/microsoft-365/excel?market=ro).

### <ins>Stakeholders</ins>

 - Ministry of Transport;
 - Road Transport Department;
 - Police Force;
 - Emergency Service Department;
 - Traffic Management Agencies;
 - Public;
 - Media;

### <ins>Data Preparation and Cleaning</ins>

In the initial data preparation phase I performed the following tasks:
1. Data loading and inspection (sorting, filtering, etc.).
2. Removing duplicate values.
3. Correct typing errors in the data using Find & Replace functions.
4. Creating "Month" column by extracting data from "Accident Date" column using text function.
5. Creating "Year" column by extracting data from "Accident Date" column using text function.
6. The typesof vehicles were grouped into fewer cathegories: cars, vans, buses, bikes, agricultural vehicles and other vehicles (in the [dashboard](#project-overview)).
7. The light conditions of the road were grouped in two cathegories: daylight and dark (in the [dasboard](#project-overview)).
8. Road surfaces were grouped into: dry, wet and snow/ice.

 ### <ins>Exploratory Data Analysis</ins>

Exploratory data analysis involved exploring the road accident data to fulfill the following requirements of the stakeholders:
 - Creating a Road Accident Dashboard for year 2021 and 2022 to fnd insights on the following:
 	- Total casualties taken place after the accident (Primary KPI);
 	- Total casualties and percentage of total with respect to accident severity and maximum casualties by type of vehicle (Primary KPI);
	- Total casualties with respect to vehicle type (Secondary KPI);
	- Monthly trend showing comparison of casualties for Current Year and Previous Year;
	- Maximum casualties by Road Type;
	- Distribution of total casualties by Road Surface;
	- Relation between Casualties by Area/Location and by Day/Night;

### <ins>Data Analysis</ins>

The data analysis of the dataset was done by using the following tools available in Excel:
 - Pivot Tables.
 - Doughnut charts.
 - Line graph.
 - Tree map.
 - Bar and line graphs.
 - Slicers (for creating the interactive dashboard).

### <ins>Results and Findings</ins>

The analysis results are comprised in the created [Dashboard](#project-overview). Some of the most important insights are:
 - 79.8% from the total casualties are produced by car accidents and only 1.7% from them are fatal ones. This shoes that car vehicles are involved
in most of the accidents in UK. They are followed by Bikes and Vans.
 - There is a similar trend in between the 2021 and 2022 casualties but there can be seen a slight overall improvment i 2022.
 - Most of the casualties happened on single carriageways in predominantly dry conditions.
 - The majority of the casualties took place in Urban areas and in Daylight conditions.

### <ins>Recommendations</ins>

Based on the analysis, the following actions can be recommended:
1. Some informational campaigns can be developed towards the car drivers, informing them about the risks and consequences of different actions.
2. Single Carriageway roads can be provided with more safety elements like railways, emergency parkings, etc.
3. The trafic in Urban areas can be better regulated and safety habbits enforced by Police forces.

### <ins>Limitations</ins>

 - The dataset that was used in the analysis contained 307972 unique records, which is a rather small sample that may not represent the entire population needed to be taken
into account during analysis for the investigated time interval.
 - There was a large number of records containing blank fields, that could not be filled or eliminated during analysis.

### <ins>References</ins>

1. [Youtube](https://www.youtube.com/)
2. [Stack Overflow](https://stackoverflow.com/)
3. [Kaggle.com](https://www.kaggle.com/)

### <ins>Notes</ins>

- This project represents my practice work in the field of data analysis. The dataset used does not represent the reality and therefore the findings should be treated in accordance.
- For more details about me and my work, or if you want to get in touch with me, please access my [LinkedIn profile](https://www.linkedin.com/in/alexpraporgescu/).
