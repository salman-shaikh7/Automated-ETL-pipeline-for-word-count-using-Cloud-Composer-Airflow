# Automated ETL pipeline using Cloud Composer (Airflow) and Dataproc (Spark)

## Project Overview
Cloud Composer is the tool for hosting workflows and it is a hosted version of the popular open source workflow tool Apache Airflow.

In this project we will use Google Cloud console to set up a Cloud Composer environment. We will then use Cloud Composer to go through a simple workflow that verifies the existence of a data file, creates a Cloud Dataproc cluster, runs an Apache Hadoop wordcount job on the Cloud Dataproc cluster, and deletes the Cloud Dataproc cluster afterwards.



