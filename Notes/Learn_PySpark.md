# DATA_ENGG
# Learn DATA ENGG | PySPark

# PYSPARK
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/85e8ee1f-41a2-42b9-8f82-d91602f6292b)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/94f8c595-4cab-468f-8c45-55a719d9e8bf)

<br></br>
<br></br>
## Worker nodes can many executers, but in Databricks each worker nodes has 1 excecuter.
<br></br>
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/2315cfd7-86dd-4417-93ee-7d5d3a5abdbb)

 <br></br>
 <br></br>
## No. of data partitions = N0. Of Cores or multiple of no. of cores (so that no cores will be idle thus saving money)
## Driver talk to Cluster manager to launch worker nodes, afer that it will directly assign tasks to worker nodes
<br></br>
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/51867393-e20d-43b3-8899-0fd929d2f34e)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/ae8cdf24-8d0f-4267-8153-26fe1b8d17a8)

<br></br>
<br></br>
## Fault tolerant = recover lost data through graph
<br></br>
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/e89be032-d6cc-40e0-8e84-0c41833bf3ab)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/28ad526c-b23f-4620-8463-3eef8319d123)

 <br></br>
 <br></br>
## Dataframe and dataset are internally handled as RDD.
<br></br>
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/7eb41602-f6ed-451c-869f-3377538db1ff)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/bf9e2d1b-a95e-47f2-ae82-c422192b7c36)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/4d3ad1be-9cde-4748-83da-5e30bf8f2add)

<br></br>
<br></br>
## ML operations = more execution memory
## ETL operations = more storage memory
<br></br>
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/aea78052-ed3b-4244-b002-83dc9141670e)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/ea48db95-ffb3-4b96-abaf-4fd537b1cf55)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/abb94188-76de-45da-ab7f-fd38c049139e)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/69cddefc-cb53-4c12-b0bd-176e132caeb6)

<br></br>
<br></br>
## Naroow transformation = No reshuffling of data across nodes
## Wide Transformation = Reshuffling of data across nodes…..Ex. GroupBy
<br></br>
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/a93f7fc9-786d-4731-a7f1-66f6711e3b98)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/c2089991-a97f-41dc-8aa5-4bff971eea3c)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/f3d5e3e7-cd6c-46be-981f-bd68a6b927e3)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/a706084e-1c30-421d-8312-960a7b192571)

<br></br>
<br></br>
## Off HEAp == stores serialized data (bytes form)….ex. RDD, Dataframe
## On-heap memory == When you run Spark applications, you can specify the amount of memory allocated per executor using the spark.executor.memory configuration parameter. This memory is primarily used to store ## data structures, objects, and intermediate results created during the execution of your application's tasks.

<br></br>
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/be4383da-5a85-44c0-8ea6-03364e606005)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/4d63a6eb-1455-45a9-860b-3f1e26e7aad2)


## DAG and Lineage
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/e365f75b-18ca-47cb-8f3b-552670491b30)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/8e395b03-b500-4b3d-915a-0ba9de2b6506)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/9d79a76b-cd8b-4908-a845-0101e0ad6d98)
