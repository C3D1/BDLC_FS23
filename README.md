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

<!-- ## [V05](./V05/)

- Hive
- Installation of Hive

```bash
.
├── resources                           # used during the lesson
│   ├── SQL_to_MR                       # Used for SQL basic understanding and writing SQLs in MapReduce.
│   ├── Formatter_JupyterLab.md         # Question about formatters from last week.
│   ├── hive-site.xml                   # Config file for Hive. Will be used when we install Hive.
│   ├── Testing_Hive.ipynb              # Testing if Hive itself works and if the JupyterLab extensions work with Hive as well.
│   └── Testing_MYSQL.ipynb             # Testing if the metastore has been initialized. Testing SQL Magic for JupyterLab.
├── V04_exercises_material               # Exercises for this week
├── ddl.md                              # Creating databases and tables. Insert data into tables with Hive.
└── install_hive.md                     # Installation guide for Hive.
``` -->
