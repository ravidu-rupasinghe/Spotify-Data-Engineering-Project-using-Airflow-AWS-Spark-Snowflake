# Spotify-Data-Engineering-Project-using-Airflow-AWS-Spark-Snowflake
![Spotify data pipeline](https://github.com/ravidu-rupasinghe/Spotify-Data-Engineering-Project-using-Airflow-AWS-Spark-Snowflake/blob/main/dags/aws.drawio_4d2e4a43.gif)

The architecture shown is a cloud-native data pipeline using AWS services and other tools like Spark, Snowflake, and Power BI. It starts with data ingestion from Spotify, processed using Lambda (Python), stored in S3 buckets, transformed using Apache Spark, loaded into Snowflake using Snowpipe, and then visualized through Power BI. Airflow is used for orchestration, and Docker provides a containerized environment for deployment.
