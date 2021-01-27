The project is a capstone project provided by Udacity to showcase the learnings of the student throughout the program.
The following are three datasets used to complete the project: 
- i94 Immigration: This dataset contains details of all U.S. immigrant's information. This data comes from the U.S. National Tourism and Trade Office.
- U.S. City Demographic Data: This dataset contains population details of all U.S. Cities, and census-designated places include gender & race information. This data came from OpenSoft. 
- Country Data: This data contains code for all countries in the world. This data comes from I94_SAS_Labels_Descriptions provided by Udacity.



The project builds a data lake using Pyspark to support the US immigration department's analytics department to query the information needed by extracting data from all the sources. 
Pyspark was used to build the ETL pipeline. The data sources have been cleaned, transformed to create new features, and then saved the data tables as a parquet file. 
The conceptual data model is a star schema that contains fact and dimensions tables.
