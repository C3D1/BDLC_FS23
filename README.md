# Big Data Lab Cluster FS23

```text
██╗    ██╗███████╗██╗      ██████╗ ██████╗ ███╗   ███╗███████╗
██║    ██║██╔════╝██║     ██╔════╝██╔═══██╗████╗ ████║██╔════╝
██║ █╗ ██║█████╗  ██║     ██║     ██║   ██║██╔████╔██║█████╗
██║███╗██║██╔══╝  ██║     ██║     ██║   ██║██║╚██╔╝██║██╔══╝
╚███╔███╔╝███████╗███████╗╚██████╗╚██████╔╝██║ ╚═╝ ██║███████╗
 ╚══╝╚══╝ ╚══════╝╚══════╝ ╚═════╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝
```

This repository is used to provide additional resources for `BDLC_FS23`.

## [V01](./V01/)

- Introduction to the module
- Setup Virtual Machine
- Installation of Apache Hadoop in Standalone Operation

```bash
.
├── disk.md             # how to add additional disk space
├── install_hadoop.md   # how to install Apache Hadoop in Standalone Operation
└── v01_exercises.md    # exercises for this session
```

## [V02](./V02/)

- HDFS, YARN and MapReduce.
- Run the Hadoop services as daemons (pseudo distributed mode).
- Learn how to navigate in `hdfs` (listing, removing and adding files).
- Write an own word count in python.

```bash
.
├── python_solution                         # solutions for v02_exercises
│   ├── mapper.py
│   └── reducer.py
├── install_hadoop_pseudo_distributed.md    # how to install Apache Hadoop in Pseudo Distributed Mode
└── v02_exercises.md                        # exercises for this week
```

## [V03](./V03/)

- Setup and Customize `JupyterLab`.
- Setup some dataset.
- Tune our `Hadoop` Cluster.
- Get familiar with `MapReduce` and `MrJob`.

```bash
.
├── 01_preparing_dataset.md             # some example dataset
├── 02_install_jupyterlab.md            # guide for installing JupyterLab
├── 03_jupyter_lab.md                   # guide for configuring JupyterLab
├── 04_install_mrjob.md                 # guide for installing MRJob
├── 05_tuning_yarn.md                   # using all cores and more memory
├── resources                           # used during the lesson
├── v03_exercises_material              # exercise material
└── v03_exercises.md                    # exercises for this week
```

## [V04](./V04/)

- Installation of MySQL
- Basics of SQL
- SQL to MapReduce

```bash
.
├── resources                           # used during the lesson
│   ├── SQL_to_MR                       # Used for SQL basic understanding and writing SQLs in MapReduce.
└── install_MySQL.md                    # Installation guide for mySQL and Python Magic.
```

## [V05](./V05/)

- Hive
- Installation of Hive

```bash
.
├── 01_install_hive.md                  # Installation guide for Hive.
├── 02_ddl.md                           # Creating databases and tables. Insert data into tables with Hive.
├── resources                           # used during the lesson
│   ├── hive-site.xml                   # Config file for Hive. Will be used when we install Hive.
│   ├── Testing_Hive.ipynb              # Testing if Hive itself works and if the JupyterLab extensions work with Hive as well.
│   └── Testing_MYSQL.ipynb             # Testing if the metastore has been initialized. Testing SQL Magic for JupyterLab.
└── V05_exercises_material              # Exercises for this week
```

## [V06](./V06/)

- Pandas Workshop created by Stefanie Molin

```bash
.
└── pandas_course.md                # Guide to run and install the workshop.
```

## [V07](./V07/)

- Adding MovieLens 25M dataset to Hive.
- Together: Answering some questions to the MovieLens dataset.
- Parquet Files: how to read, save parquet files.
- Save the MovieLens files as parquet.
- Exercise with "die Post" dataset where we also use partitions.

```bash
.
├── 01_movie_lens                    # MovieLens 25M dataset
├── 02_parquet                       # Parquet and python
├── 03_movie_lens_parquet            # All notebooks for movielens to parquet
├── v06_exercises_material           # Exercises for this week
```

## [V08](./V08/)

- Intro to Spark.
- Install Spark.
- Testing Spark Context and SQL Context in our setup.
- Testing Spark in JupyterLab.
- Exercises about Spark and RDDs.

```bash
.
├── v08_exercises_material                   # Exercises for this week
│   ├── 01_PySpark.ipynb                     # This exercise comes from [pnavaro](https://github.com/pnavaro/big-data)
│   └── 02_Text_Processing.ipynb             # Word Count and Text-Generator
├── 01_spark_context.ipynb                   # Testing Spark Context in Jupyterlab.
├── 02_spark_sql.ipynb                       # Testing Spark-SQL in Jupyterlab.
├── install_spark.md                         # How to install Spark.
```
