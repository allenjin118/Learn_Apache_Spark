# Study Note for Spark
## RDD
1. Operators
* Transformations
  Transformations are lazy operations and are the methods that take a RDD as the input and return another RDD as the output. They do not chage RDD
  e.g map(), flatMap(), filter(), mapPartitions(), MapPartitionsWithIndex(), sample(), union(), intersection(), distinct(), groupByKey(), reduceByKey(), join(), cogroup(), cartesion(), pipe(), coalesce(), repartition(), partitionBy()
* Actions
  
