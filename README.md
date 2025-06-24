### Laboratorio AWS Glue

<img width="498" alt="Image" src="https://github.com/user-attachments/assets/25fe4137-04f4-46ef-87fa-024bcf3ecdff" />

### Objetivo
Construir un ETL (Extract, Transform, Load) que utilice DynamicFrames en AWS Glue.
### Descripción
Este código lee desde el AWS Glue Datacatalog dos tablas en una base de datos, después realiza un join entre ambas tablas y calcula el total de la venta. Finalmente, escribe el resultado en un archivo Parquet en S3.
### Servicios de AWS a Utilizar
[Amazon Athena](https://aws.amazon.com/athena/).
[AWS Glue](https://aws.amazon.com/glue/).
[AWS Glue Data Catalog](https://docs.aws.amazon.com/es_es/glue/latest/dg/start-data-catalog.html).
[AWS Glue Crawler](https://docs.aws.amazon.com/glue/latest/dg/add-crawler.html).
[Amazon S3](https://aws.amazon.com/s3/).
[IAM](https://aws.amazon.com/iam/).
