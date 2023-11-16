# Databricks Pipeline end to end

This simple yet effective end-to-end project demonstrates how to use Databricks Pipeline using jobs to build a dataset using Notebooks in Databricks and then using Spark to manipulate them and storage them in Delta lakehouse using Hive Metastore.

First a websprapping was made from the salaries of the [MLS](https://mlsplayers.org/resources/salary-guide).

We used unnit test to make sure the data was correct.

Those two processes, the data extraction and the data validation, were made using Databricks Notebooks and their triggering is scheduled using Databricks Jobs.

<img src="/workspaces/databricks_end_to_end/project/static/DatabricksJobs.png" alt="Jobs output">

Finally, the data was used to create a dashboard using Tableau.

The video with the DEMO can be found [here](https://youtu.be/VXxZTcMS7hc).


The final product is a Tableau Dashboard with some insights about the data:

<img src="https://github.com/bugarin10/databricks_job_sample/blob/main/project/static/tableau.png" alt="Tableau output">
