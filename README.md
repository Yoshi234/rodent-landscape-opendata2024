# rodent-landscape-opendata2024

This repository includes code corresponding to work done 
as part of a midterm project for *STAT 3255: Introduction 
to Data Science*. The class notes for this course
can be found at [statsids24](https://statds.github.io/ids-s24/).
Additionally, this work was presented as part of 
*New York Open Data Week*

A pdf of the report can be found in the main release for 
this project. Additionally, the slides presented at New York 
Open Data are also included as part of the release. 

The data required to replicate this anlaysis can be obtained 
by going to 
[NYC Rodent Inspection data](https://data.cityofnewyork.us/Health/Rodent-Inspection/p937-wjvj/about_data)
and filtering for `INSPECTION_DATE` between 11:59:59 pm of 12/31/2021
and 12:00:00 am of 01/01/2024. Additionally, you will need to filter the 
data such that `INSPECTION_TYPE` is either Initial or Compliance (which should be 
close to 108 MB). Please note that this analysis was conducted during 
early March of 2024. Since the data is constantly being updated,
you may not obtain the same results as expressed in the report
due to changes in the data which have occurred. When you download this
data, please make sure to label it as "rodents_2022-2023.csv" or, change
the file read in the report to the one you choose. 
