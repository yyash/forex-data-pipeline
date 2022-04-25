# Forex Data Pipeline
A fully functional data pipeline created in **Airflow** using **Spark & Hive** to read forex data from an HTTP Api and store the data in a Hive table.

**Operators Used:**
HttpSensorOperator

FileSensorOperator

PythonOperator

BashOperator

HiveOperator

SparkSubmitOperator

EmailOperator

SlackWebhookOperator

Set dependencies between tasks to achieve a functional and interactive DAG-based Forex Data Pipeline.
