# AF_BQ

AF installed using [this](https://airflow.apache.org/docs/apache-airflow/stable/start/local.html)  

put DAG in AF/dag folder  

while using BQ, installation of [google-providers](https://pypi.org/project/apache-airflow-providers-google/) is required  

explanation of [AF](https://harshilp.medium.com/101-guide-on-apache-airflow-operators-f9707d8b86c7)  
```
gcloud config set project tenacious-post-355715
```
launch AF w/ the command  
```
airflow standalone
```
[list](https://airflow.apache.org/docs/apache-airflow-providers-google/stable/_api/airflow/providers/google/cloud/operators/bigquery/index.html#airflow.providers.google.cloud.operators.bigquery.BigQueryCheckOperator) of BQ operators in AF  

UI hook config [link](https://hevodata.com/learn/airflow-hooks/)  
