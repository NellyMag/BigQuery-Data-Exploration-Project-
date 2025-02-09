# Homelessness Data Analysis with BigQuery

<h2>Summary of the project</h2>



In this project, I explored BigQuery's public dataset on homelessness from 2010 to 2018 to identify key trends and insights related to homeless populations. I utilized SQL to analyze the dataset. My primary focus was identifying locations that needed additional support for homeless youth and pinpointing areas that were effectively addressing homelessness. 

The insights drawn from this analysis helped clarify where resources should be directed to improve support for vulnerable populations.
Insights and recommendations are provided in the following key areas:

+ Identified the top 3 Continuum of Care areas (CoC_Name in the table) with the highest number of unaccompanied homeless youth under 18 in the year 2018.

+ Has the number of unsheltered homeless people in Delaware increased over the past 7 years?
  
+ The Safe Haven program was created in 1992 to provide shelter for people who are homeless and have a serious mental illness. However, funding for Safe Havens was cut in 2009. What has been the impact on the number of homeless people?


The query used can be found [here](https://drive.google.com/file/d/1uw3-nUHULeLXIV16lpwADqjCsUw75bJ6/view?usp=sharing).

<h2>Data Structure</h2> 

Data exploration to understand what each column represents and their data type. 

There are several acronyms used in this dataset. For each acronym below, write out what it stands for:
+ CoC = Number of the continuum of care area

+ Sheltered_ES = Homeless on Emergency Shelters
  
+ Sheltered_TH = Homeless in Transitional Housing

+ Sheltered_SH = Homeless in Safe Haven

What are the only 3 columns that are NOT an Integer type?

+ CoC_Number
  
+ CoC_Name
  
+ CoC_Category

Is there any way to determine which state each row of data is located in?

+ CoC_Number includes the state abbreviation and the number.

How many total rows of data are there?

+ 2768

<h2>Summary</h2> 


In 2018, the top three Continuum of Care areas with the most unaccompanied homeless youth under 18 were San Jose, Santa Clara City and County with 506 youth; the Oregon Balance of State with 243 youth; and Las Vegas and Clark County with 214 youth. These locations are ideal for launching a new program to assist unaccompanied homeless children under 18.

Delaware has seen an increase of approximately 322.73% in the number of unsheltered homeless individuals over the past 7 years. 

In 2018, the top three locations with the highest number of homeless individuals in Safe Haven were New York City, Los Angeles City, and Los Angeles County, followed by Boston. Among all Safe Haven locations, 90 of these had at least one homeless individual.



<img width="665" alt="Image" src="https://github.com/user-attachments/assets/aa24d071-397a-461f-a108-44c4223fc4a3" />



<h2>Action</h2>  

In 2018, the states exhibiting the highest overall homeless populations included California, New York, Florida, Texas, Washington, Massachusetts, and Oregon. Evaluate programs that could benefit states with the highest overall homelessness. Lastly, consider the reinstatement of funding for the Safe Haven program, which provides critical safe spaces for individuals experiencing homelessness who also suffer from serious mental illness, particularly in California and New York.


