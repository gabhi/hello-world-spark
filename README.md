# hello-world-spark
Hello world sample from http://spark.apache.org/docs/latest/quick-start.html

Run
``sbt package``

````
spark-submit \
  --class "SimpleApp" \
  target/scala-2.11/simple-project_2.11-1.0.jar
````
