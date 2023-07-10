# DATA_ENGG
# Learn DATA ENGG | PySPark

# PYSPARK
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/3c51c34b-25c6-4303-960e-c12adbe23d2f)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/954f9a81-627f-421f-8e72-1e125cd5cf9b)


<br></br>
<br></br>
## Worker nodes can many executers, but in Databricks each worker nodes has 1 excecuter.
<br></br>
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/5afdf89f-b753-4efe-9804-068eac5bceb7)


 <br></br>
 <br></br>
## No. of data partitions = N0. Of Cores or multiple of no. of cores (so that no cores will be idle thus saving money)
## Driver talk to Cluster manager to launch worker nodes, afer that it will directly assign tasks to worker nodes
<br></br>
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/d3c6c336-3aaf-44a1-a73b-9321299963dd)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/bbb09fce-178d-419d-ae4b-1c673d8ce11c)

<br></br>
<br></br>
## Fault tolerant = recover lost data through graph
<br></br>
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/4af337ea-ff6f-4b66-98b0-ac95c94ff555)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/82e785e1-d96f-44f7-9e3b-93e117cee9d8)

 <br></br>
 <br></br>
## Dataframe and dataset are internally handled as RDD.
<br></br>
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/3f5d6919-af6f-426a-bdcd-52afb2750462)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/2dadd6a1-3345-4789-9928-e5f402c989d6)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/e2390fb9-f60d-479a-a947-bef0d9a9d794)

<br></br>
<br></br>
## ML operations = more execution memory
## ETL operations = more storage memory
<br></br>
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/5a485c30-d953-431c-ac01-72822a1a8132)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/57e5ae37-9cde-42ac-9f9b-d04f0dd0b022)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/fa698b96-e19a-499a-89d3-fe2adfc1c701)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/a916c287-118b-4c10-89ef-51da6de2628b)

<br></br>
<br></br>
## Naroow transformation = No reshuffling of data across nodes
## Wide Transformation = Reshuffling of data across nodes…..Ex. GroupBy
<br></br>
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/7fed4ac5-f03e-4789-8282-5810ca5789b3)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/c9a5468e-399e-4b5a-9305-8d184f74643e)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/ba31a50d-9bd9-44a7-a14e-0f003ee2e051)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/549534a4-daf9-43ba-8fda-60f50dc2e0c0)

<br></br>
<br></br>
## Off HEAp == stores serialized data (bytes form)….ex. RDD, Dataframe
## On-heap memory == When you run Spark applications, you can specify the amount of memory allocated per executor using the spark.executor.memory configuration parameter. This memory is primarily used to store ## data structures, objects, and intermediate results created during the execution of your application's tasks.

<br></br>
<br></br>

![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/2a4237df-bd3e-419b-bcbe-b85abd3cb82d)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/2386a00d-a6e7-47e6-a632-3ce637ae2c30)

<br></br>
<br></br>

## DAG and Lineage
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/66fb0bf1-4897-4dd4-a0f0-934fcaeaa787)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/cb4c4d54-e65f-43e3-a04c-4d96ab81f90c)
![image](https://github.com/aniketghodake10/DATA_ENGG/assets/38704659/1d64fcd6-2bfb-4066-a9fa-eaedc61251a8)
