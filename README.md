# Digital Health: OP Waiting List Analysis
An analysis of Outpatient waiting list datasets available at National Open Data Portal from data.gov.ie 

This was an assignment completed for the Case Studies in Data Analytics module as part of our studies during the MSc in Computer Science - Data Analytics, Kevan Derrane and I contributed to this assignment. 

The full analysis is contained in the OP-Waiting-List-Analysis.md file.

### Assignment details: 
The task for the student here is to develop an R or Python program to process OP Waiting List*
available on National Open Data portal (http://data.gov.ie/). This involves connecting to the CKAN
platform and accessing the datasets and associated files for each year on the portal. In addition, the
student will be required to integrate files associated with the dataset, analyse them by aggregating
the counts by hospital and finally creating a chart to display the changes in OP waiting list over time
https://data.gov.ie/dataset/op-waiting-list-by-group-hospital (consider datasets from 2014 to 2018):

### Challenges:
There are four primary challenges associated with this task:
1. Accessing the datasets available on Open Data Platform (20 Marks)
Students will need to connect to the National Open Data portal at data.gov.ie using the
CKAN API for R to access OP Waiting List By Group Hospital dataset and
fetch all the related files.
2. Integrating the datasets into one dataset (30 Marks)
This step entails aggregating the selected files obtained in step 1 into one single file. Thus,
the resulting dataset will contain consolidated data from different years.
3. Aggregate counts (20 Marks)
The third step involves generating a summary table for OP Waiting list showing the
changes years wise across several dimensions. This summary table should be available as a
CSV file or any other open data format.
4. Visualisation of the result (30 Marks)
This final step involves presenting the data in the Table generated in Step 3 as a chart.

### Assignment Analysis:
- The OP Waiting list.xlsx file contains the data in question which is available at the National Open Data Portal from data.gov.ie.
- The R_Studio_Assignment_Code.r file contains the R Studio produced to conduct an investigation of the four primary challenges above.
- The OP_Waiting_Full_Analysis.md file contains the full analysis of the dataset.
