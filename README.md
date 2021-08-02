Distributed Data Processing using Apache Spark and SageMaker Processing

Apache Spark is a unified analytics engine for large-scale data processing. The Spark framework is often used within the context of machine learning workflows to run data transformation or feature engineering workloads at scale. Amazon SageMaker provides a set of prebuilt Docker images that include Apache Spark and other dependencies needed to run distributed data processing jobs on Amazon SageMaker. This example notebook demonstrates how to use the prebuilt Spark images on SageMaker Processing using the SageMaker Python SDK.

This notebook walks through the following scenarios to illustrate the functionality of the SageMaker Spark Container:

* Running a basic PySpark application using the SageMaker Python SDK’s PySparkProcessor class

* Viewing the Spark UI via the start_history_server() function of a PySparkProcessor object

* Adding additional python and jar file dependencies to jobs

* Running a basic Java/Scala-based Spark job using the SageMaker Python SDK’s SparkJarProcessor class

* Specifying additional Spark configuration
