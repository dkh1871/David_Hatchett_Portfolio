# Distributed Data Processing Project

## Description

This project focused on the basics of distributed data processing to gain an understanding of the concepts and tools involved.
The environment was provided by the instructor and was used to practice the concepts. The goal of the project was to build an end-to-end machine learning pipeline. Below, the Pipeline and the steps taken to complete the project are walked through.

### Technologies used:
- HDFS
- Hive
- Hbase
- Nifi
- Spark
- YARN

## Pipeline Flow
![Data Pipeline](images/DataPipeLine.png)

### Nifi Flow
![Nifi Flow](images/obj1_nifi_data_all_run.png)

### Verify HDFS File
![HDFS File](images/obj1_nifi_hdfs_ls.png)

### Hive Table
![Hive Table](images/obj2_hive_create_table.png)  

![Hive Table](images/obj2_hive_skip_header.png)

### Verify Hive Table
![Verify Hive Table](images/obj2_hive_sql_verify.png)

### Prepare environment for Spark Job  
Install packages on the Main Node
![Prepare enviroment for Spark Job Main](images/obj3_main_setup.png)  

Install packages on Worker1 Node
![Prepare enviroment for Spark Job Worker1](images/obj3_wrk1_setup.png)  

Install packages on Worker2 Node
![Prepare enviroment for Spark Job Worker2](images/obj3_wrk2_setup.png)  

Start the Thrift Server
![Start the Thrift Server](images/obj3_no_hub.png)  

### Create Hbase Table
![Create Hbase Table](images/obj4_create_table.png)  

### Run Spark Job
![Run Spark Job](images/sprk_log_1.png)  

![Run Spark Job2](images/obj5_running.png)  

### Verify Spark Job
![Verify Spark Job](images/obj7_hbscan.png)  
