-------------------------------------------------------------------F23-CS226-Readme-------------------------------------------------------------------------------------------- 
Exploring the Global Job Market : A Big Data Analysis of International Job Postings
-----------------------------------------------------------------------------------
(Mis)Fortune-500
----------------
---Member Names---
Manish Deepak Chugani, mchug002@ucr.edu, 862388066
Tejas Milind Deshpande, tdesh006@ucr.edu, 862393211
Sumedha Girish Atreysa, satre002@ucr.edu, 862395753
Nunna Lakshmi Saranya, nsara014@ucr.edu, 862394536
Xinle Chen, xchen440@ucr.edu, 862334534

There are 3 main Jupyter Notebooks available for viewing the results of MisFortune-500's architecture.

1: CS226_RDBMS_VS_PySpark_VS_Pandas.ipynb: Compares the performance of an RDBMS versus PySparkSQL versus a regular Pandas Dataframe.

2: CS226_SparkSQL_JobLocation_Choropleth_Visualization.ipynb: This notebook is used for visualizing the job market in 2021 during the boom across 
   maps of the United States and the World.

3: CS226_SparkSQL_AllDatasets_Visualization.ipynb: This notebook uses the combined dataframe after data integration and preprocessing to apply 
   PySparkSQL queries and generate the histograms and piechart for analysis

To run any of the 3 notebooks, open the notebooks in Google Colaboratory and run all cells. After running the first cell, you will need to provide
Google Drive access to the notebooks so that it can access the dataset files on google colab. Please make sure the path is correct.
The path by default should be correct since it utilizes "Shareddrives" on Google Drive and the datasets have been shared with the instructor.

The Extra Code folder contains the attempt at a Front-end as demonstrated in the reports and video presentation.
The .ipynb is a flask front-end attempt whereas the .html file is a direct pull of the images using just html code.
Click the Get Images button to retrieve the images for analytics shown in the above Notebooks.

If there is a permission issue, please request access and drop a message to mchug002@ucr.edu to provide the access.

-------------------Author Contributions-----------------------------------------------------
(Mis)Fortune-500:

Manish Deepak Chugani: Choropleths and Analytic Visualizations along with PySparkSQL Queries
Tejas Milind Deshpande: Data Cleaning, PySparkSQL Queries and RDBMS comparison.
Sumedha Girish Atreysa: Data Cleaning, Schema Definition and Pre-processing.
Nunna Lakshmi Saranya: Data Cleaning, Integration and Combination of Dataframes.
Xinle Chen: Pandas Dataframe comparison and Front-end.
