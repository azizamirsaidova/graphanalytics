# Graph Analytics Demo 

This repository provides notebook that briefly explains the usage of Spark and Graphframes in conducting graph analytics

Notebooks highlights the followings:
1. GraphFrames Basic Attributes: nodes, edges, degrees, inDegrees, outDegrees.
2. Built-In Algorithms: connected components, pagerank, triangle count, label propagation

## Dependencies

```bash
# install java
!apt-get install openjdk-8-jdk-headless -qq > /dev/null

# install spark (change the version number if needed)
!wget -q https://archive.apache.org/dist/spark/spark-3.2.0/spark-3.2.0-bin-hadoop3.2.tgz

# unzip the spark file to the current folder
!tar xf spark-3.2.0-bin-hadoop3.2.tgz

# set your spark folder to your system path environment. 
import os
os.environ["JAVA_HOME"] = "/usr/lib/jvm/java-8-openjdk-amd64"
os.environ["SPARK_HOME"] = "/content/spark-3.2.0-bin-hadoop3.2"

# install findspark using pip
!pip install -q findspark

# install pyspark
!pip3 install pyspark==3.2.0

# install graphframes
!pip3 install graphframes

```
