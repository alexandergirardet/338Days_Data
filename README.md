# 338Days_Data
This is my 338 day learning journey in AI, Maths, and Data Engineering. Everyday I will learn new concepts and integrate it into a note taking app. Over time I will post about 338 topics and concepts that I will relate to eachother through projects, use cases and high level concepts. 

## Acknowledgments
To my Grandfather Frank Hieber who serves as an inspiration in my life, always promoting acquiring knowledge through self education. 

## Motivation
Being freed from the constraints of formal education allowed me to explore my own learning style and interests. Despite not having a background in STEM, during the first COVID-19 lockdown, I discovered my passion for coding and data science. I have since been working as a data engineer, which has solidified my desire to pursue a career in this industry. The emergence of innovative technologies like ChatGPT has only increased my motivation to dive deeper into the field of AI. The 338 day data challenge serves as an opportunity for me to continue to grow and improve my skills in a field that I am passionate about. This challenge is a personal milestone that I am eager to achieve through determination and hard work.


## Strategy
My goal is to become proficient in data engineering, machine learning engineering, and to leverage my finance and business background to gain a deeper understanding of creating and managing data-driven organizations.

To accomplish this goal, the challenge will consist of several feats including:

* Reading and summarizing 11 books (1 per month)
* Completing projects
* Participating in 2 bootcamps
* 3 Certificates
* Reading and summarizing research papers

I recognize that working a full-time job will make this challenge more difficult, but it also provides me with the added benefit of being immersed in the world of tech and surrounded by those who are more proficient in these areas, from whom I can learn. I plan to use the techniques and tools outlined by Tiago Forte's [Building a Second Brain](https://github.com/alexandergirardet/Book_Summaries/blob/main/Books/Building_a_Second_Brain.pdf) for my time management, note-taking, and information organization strategy to help me stay on track.

## Outline
This will be subject to change.

### Books

Books  | Status of Completion
------------- | -------------
Mathematics for the non-mathematician  | :construction:
Hands On Machine Learning with Scikit Learn, Keras and TensorFlow | 
Designing Data-Intensive Applications | :construction:
Structure and Interpretation of Computer Programs | :construction:
Machine Learning Engineering | 
Fundamentals of Data Engineering | :construction:
Kimball's Data Warehouse Toolkit | :construction:

### Projects

Books  | Field | Status of Completion
------------- | ------------- | -------------
UK Real Estate Dashboard  | Data Engineering | :construction:
Finance NLP analyst  | NLP and ML Engineering | 
[Airflow project](https://github.com/alexandergirardet/training-projects/tree/main/airflow) | Orchestration and Docker | :white_check_mark:

### Certificates
  
Certificate  | Status of Completion | Proof
------------- | ------------- | -------------
Google Associate Cloud Engineer  | :white_check_mark: | https://www.credential.net/fdd64e5c-48d5-459d-99e5-4df6828e3941#gs.qsdqi3
Google Cloud Professional Data Engineer | | 
Google Cloud Professional Machine Learning Engineer  | | 
Stanford Course in Mathematical Thinking  | :construction: | 

### Bootcamps

Bootcamp  | Status of Completion
------------- | -------------
Data Engineering Zoomcamp  | :construction:
Machine Learning Zoomcamp  |

### Day 1

**Topic:** Mathematical Thinking

I have started this journey by trying to develop my mathematical thinking. I recently completed the first week of lectures and assignments from Stanford's Mathematical Thinking course on Coursera. Through this course, I learned that a major challenge for math practitioners is the shift from a focus on doing to a focus on understanding. The first week of the course covered introductory material, but it provided valuable insights into the historical purpose of mathematics. Originally, mathematics was used primarily for practical purposes such as financial management, but it has evolved to become more abstract and is now used to develop models that use mathematical notation to represent relationships and patterns in everyday life. The purpose of the Mathematical Thinking course is to move away from the ability to simply apply pre-defined functions and theorems and instead understand the mathematical concepts and principles behind them. This approach will allow the individual to generalize and solve similar problems in the future. According to the instructor, individuals who possess this ability to think outside of the mathematical box and apply mathematical thinking to new problems are considered innovative mathematical thinkers. These individuals will be best suited to keep up with the ever-changing demands of industry.

**Content:** Mathematical Thinking Stanford Course

### Day 2

**Topic:** DDIA

Designing Data-Intensive Applications or DDIA by Martin Kleppmann provides a comprehensive overview of modern data systems and the various trade-offs involved in their design. It covers topics such as data modelling, storage, processing, and security, and provides practical advice on how to build scalable, reliable, and maintainable data-intensive applications. The book was highly recommended to me by senior data engineers and architects, as it would deepen my understanding of data systems and designing robust data-driven applications. Today I studied for my Associate Cloud Engineer exam which is in 4 days and took notes on the first chapter of DDIA. Reliability, maintainability, and scalability are the three most important concerns in designing data-intensive software applications. Reliability means making systems work correctly, even when faults occur. Fault-tolerance techniques can hide certain types of faults from the end user. The primary techniques mentioned are: decoupling development features from production usage, where engineers can explore the data without impacting live systems. Thorough testing, including unit tests, whole integration tests, and end-to-end testing. As well as setting up detailed and clear monitoring which can provide early warning systems to check whether our assumptions are validated. Scalability refers to having strategies in place to preserve performance when keeping up with large increases in load. An architecture which is scalable requires an understanding of which operations will be common and which will be rare. Finally, maintainability is about making life better for the engineering and operations teams who work with the system. Good abstraction would involve reducing the complexity of the system, making it easier to modify and adapt. There are three design principles for ensuring maintainability. Operability makes it easier for teams to keep the system running smoothly. Simplicity makes it easier for new engineers to understand the system as a lot of the complexity has been abstracted away. And, evolvability, makes it easier for the engineers to make changes to the system in the future. 

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DDIA/Chapter_1_-_Design_Scalable_systems.pdf)**

**Content:** Designing Data-Intensive Applications and Cloud Guru Google Certified Associate Cloud Engineer course

### Day 3

**Topic:** DDIA

Today's content focused on chapter 2 of DDIA and the Cloud Guru Google Certified ACE course. I learned about data models and networking architecture in google cloud solutions. A short summary of chapter 2 regarding data models. Data models are important in developing software as they impact how the software is written and how problems are solved. Most applications are built on a hierarchy of data models with each layer hiding the complexity of the layer below it by providing a clean data model. There are 3 main general-purpose data models for storage and querying: relational, document and graph-based. The relational model is the most well-known and data is organized into tables and relationships. But there is an "impedance mismatch" between relational data models and object-oriented applications, leading to a disconnect between the models. The document model is hierarchical and similar to JSON and reduces impedance mismatch, but provides less support for joins. The schema-on-read approach is advantageous if item structures are not homogeneous. Both relational and document models are becoming more similar over time.


**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DDIA/Chapter_2_-_Design_Scalable_systems.pdf)**

**Content:** Designing Data-Intensive Applications and Cloud Guru Google Certified Associate Cloud Engineer course

### Day 4

**Topic:** Associate Cloud Engineer

With my goal of gaining the GCP professional data engineer certificate and professional machine learning engineer certificate it is important that I can test and prove my knowledge of leveraging cloud solutions before moving on to the more specialized certifications. The Associate Cloud Engineer exam assesses your ability to deploy applications, monitor services and manage enterprise services. I have given myself a week to study for the exam. Google cloud platform provides Software as a Service, Infrastructure as a Service and Functions as a Service, it is crucial when working with cloud solutions to understand networking concepts for deploying applications. Networking refers to the infrastructure and systems that enable communication between different devices. Understandly a large cloud solution will need to communicate with Google's physical cloud infrastructure securely, and effectively in providing scalable, reliable, and maintainable data-intensive applications. Within Google cloud there are three layers to networking: VPCs, Subnets, and Routers. For the sake of this explanation I will use some analogies but my notes go more in depth. A VPC or virtual private cloud can be thought of as a neighborhood where you can control who gets access to your neighborhood. It is a bit of an authoritarian neighborhood so it can decide who can communicate with eachother and who can communicate with the outside world (as with all authoritarian regimes they say it is for your own safety. In this case it actually is). A subnet can be thought of as a house within the neighborhood, these are where certain resources (think furniture in analogy terms) are logically grouped together based on their shared needs. Again this would be for security reasons, some houses may have more expensive furniture which would need stricter access rules. Routers who can be thought of as traffic directors, they know where all resources are placed and forwards traffic in the neighborhood where it needs to go. Finally these leaves us with the concept of a firewall who can be thought of as bouncers. These bouncers will be stationed outside each house, but also outside the neighborhood. They decided based on the rules you give them, who is allowed access to the places the traffic intends to be. 

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/Certificates/Associate_Cloud_Engineer.pdf)**

**Content:** Cloud Guru Google Certified Associate Cloud Engineer course

### Day 5

**Topic:** Kubernetes

To understand Kubernetes you have to first understand the rise of Agile software practices and the shift from monolithic architecture to microservices. In the previous years when apps were less complex, having all the functionality closely coupled together was not a major problem, as the code bases were relatively light and easy to deploy, this is referred to as monolithic architecture. Today, as apps become much more complex, integrating features such as chatbots, user validation, and large scale databases, the ability to continuously update a large singular code base, test it and redeploy it is no longer viable. Therefore in line with developing faster software practices which are more flexible, agile and true to the core principles of maintainability, reliability and scalability, the microservice architecture become prominent. Today features of an app are broken down into smaller independent components which are loosely coupled and therefore can be scaled, redeployed and updated without impacting the availability of other features. This is possible due to containerization which allows you to deploy code along with it's environments configurations and dependencies, allowing features to run as standalone apps. Kubernetes offers a solution to the problem of managing the deployment, and management of these many containers which when combined together form the basis of the application. There are two main concepts in a cluster, the master node and the worker node. The master node contains the API which allows the developer to communicate with the cluster, and update the clusters nodes. The master node or the control plane, also controls storing the state of the cluster, scheduling and managing the worker nodes. The worker nodes contains pods, which as logical units containing the docker images that hold the functionality of the individual components.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/tree/main/Notes/Data_engineering_bootcamp/Kubernetes.pdf)**

**Content:** Cloud Guru Google Certified Associate Cloud Engineer course and Kubernetes

### Day 6

**Topic:** DDIA Chapter 3 #1 - Databases and Indexing

I successfully passed my Associate Cloud Engineer Exam. I will, in the future provide a summary as an article piece on how I passed it, and what concepts are important to know. Today's topic will regard the concept of databases and how data is indexed, and stored under the hood. Fundamentally, a database needs to do two things. When you give it data, it should store it, and when you ask for it back it should retrieve it efficiently. To achieve these seemingly simple functions, there have been many algorithms and methods invented.

The most simple database is a log based one, which is an append-only sequence of records, this is the quickest method for writing data due to the simplicity of the operation. Indexing is an additional structure on top of the primary data which enables efficient searches. It can drastically accelerate read times, but slow down write times. Hash indexes, are used for key-value data, this means when given a key it will store it and return the value. The Hash table is a popular data structures used for key-value look-up and work by converting the key into an integer and remapping it to an index to reduce storage space. The hash index keeps an in-memory hash map where each key is mapped to a byte offset in the data file where the value can be found. Appending a key-value pair updates the hash map to reflect the offset of the written data. 

Segmentation, involves breaking the log into segments of a certain size and then compacting the segments by removing duplicate historical keys and keeping only the most updated ones. The point of segmentation in databases is to improve the performance, scalability and manageability of the database by dividing it into smaller, more manageable parts called segments. Segmentation helps to reduce the amount of I/O needed to access data, decrease contention for database resources, and simplify the administration and maintenance of the database. Additionally, segmentation can also provide better data security and privacy by allowing administrators to enforce access control on a segment-by-segment basis.

There are some implementation problems with hash indexes, including file format, deleting records, crash recovery, partially written records, and concurrency control. There are advantages of the append-only design, including faster speeds, easier concurrency and crash recovery, and removing the problem of data files being fragmented over time. The disadvantages include the need for the hash table to fit in memory and inefficiency in range queries.

SSTables, is a database design where the sequence of key-value pairs is sorted by key, they are very common in NoSQL databases. The point of SSTables is to provide a fast and efficient way to store large amounts of data on disk in a way that can be easily accessed and queried. They are designed to be highly optimized for read-heavy workloads, providing fast access times for large amounts of data, even on disk-based storage systems. They achieve this by using a number of techniques, including:

  Sorting: The data in an SSTable is stored in sorted order, which allows for efficient indexing and searching.

  Compression: SSTables use efficient compression algorithms to reduce the size of the data on disk, which reduces disk I/O and improves access times.

  Immutable: SSTables are designed to be immutable, meaning once data is written to an SSTable it cannot be modified. This allows for efficient compaction   and garbage collection, which helps to keep the size of the SSTables manageable.

SSTables are more efficient in merging segments, they do not require all keys to be kept in memory, and allow for more efficient range queries. However, you cannot immediately append new key-value pairs to the segment as writes can occur in any order. 

Due to the length of this chapter I will break it down overall several days.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DDIA/Chapter_3_-_Design_scalable_systems.pdf)**

**Content:** Designing Data-Intensive Applications

### Day 7

**Topic:** Docker

As I began working through the Data Engineering Zoomcamp the first topic to come up is Docker and it's use in developing, testing and deploying apps or pipelines. Docker aims to solve the problem of Portability in creating software applications. It enables developers to create, deploy and run applications in standardized and isolated environments. This makes it easier to develop, test, and deploy applications across different environments, ensuring compatibility and consistency of results. The main components of Docker are Docker Client, Docker Daemon, Docker Registry, Docker Engine, Docker Images, and Docker Containers. The Docker Client is the CLI that allows users to interact with the Docker Daemon, build images, and run and manage containers. The Docker Daemon is the core component of the architecture that runs on the host machine, responsible for building images, running containers and managing them. The Docker Registry is where images are stored and can be retrieved by the Docker Client. There are public and private registries such as Docker Hub and Google Container Registry. The Docker Engine is the software that runs on the host machine and provides an interface between the Docker Daemon and the client. The Docker Images are the building blocks of containers and include everything needed to run an application, including code, runtime, system tools, libraries and settings. The Docker Containers are instances of Docker Images that run as isolated processes on the host machine, each with their own file system, networking and resources. In today's course I have created several docker containers that share a network and can communicate with eachother, leading me to the concept of docker compose files. Docker compose files are useful in creating multi-container applications. For example, one container can run a postgres database while another can run PgAdmin (a GUI for managing docker containers). These containers can use the shared network to communicate with eachother so that I can simultaneously interact with the database and monitor it using PgAdmin. 

**[Notes](https://github.com/alexandergirardet/Book_Summaries/tree/main/Notes/Data_engineering_bootcamp/Docker.pdf)**

**Content:** Data Engineering Zoomcamp

### Day 8

**Topic:** Terraform

Working with cloud infrastructure means you are essentially working with virtualized servers far away from your local host. However for your apps to run as anticipated you have to configure these servers in a way that matches your security, hardware and networking needs. This requires a lot of maintaince, surveillance and most importantly preparation. Google Cloud, AWS and Azure provide you with relatively sleek and intuitive UI to adjust your environments. However for a production application which requires a lot of testing, through sandbox and development environments, as well as trying to ensure that your data system respects the concepts of scalibility, maintainability, and reliability. Continuously going through the same process of clicking around on the UI to match your environment configurations is not a good and long term solution. Where is the version control? Or how can you quickly share your environment specs to other developers. This is where Terraform and the concept of Infrastructure as Code comes in or IaC. It is an open source Iac tool that allows you to provision, build and version infrastructure resources in a safe and collaborative manner. Through a series of plugins Terraform can connect to Azure, AWS, and GCP cloud providers, as well as others. Terraform is fairly simple as it is well designed and includes declarative coding conventions using the hashicorp configuration language which is similar to JSON. Declarative code means that you essentially declare what you wish the end state of your app to be, and the compiler will find a way to create that state. In the case of Terraform you declare your wanted state in the main.tf file, as well as provide access to your environment, and tf will use it's backend where it stores the current state of your infrastructure, and will compare and contrast the previous infra to your future declared version and will figure out what changes need to be made to reach it. 

**[Notes](https://github.com/alexandergirardet/Book_Summaries/tree/main/Notes/Data_engineering_bootcamp/Terraform.pdf)**

**Content:** Data Engineering Zoomcamp

### Day 9

**Topic:** DDIA Chapter 3 #2 - Transaction processing vs analytics

Transaction processing and analytics are two different ways of accessing and querying data in a database. Transaction processing is referred to as Online Transaction Processing (OLTP) and it involves inserting and updating records based on user input, with small number of records being queried per transaction. On the other hand, analytics is referred to as Online Analytic Processing (OLAP) and it involves scanning over a large number of records to calculate aggregate statistics and return data that can be used for business intelligence purposes.
Data warehouses are separate databases used to store a read-only copy of the data from OLTP systems. The data is extracted, transformed into an analysis-friendly schema, cleaned and then loaded into the data warehouse. This allows the data to be optimized for analytic access patterns and is why analysts use data warehouses rather than directly querying OLTP systems. This benefit is especially significant in terms of saving on costs on cloud platforms where you are being billed for computing power. Google Cloud's BigQuery stores it's data in a columnar format for better aggregation performance. 

There are two main schemas used in analytics, the star schema and the snowflake schema. The star schema is centered around a fact table, with each row representing an event and foreign key references to dimension tables that represent the who, what, where, when, how and why of the event. The snowflake schema is more normalized but less preferred by analysts. Normalized means splitting larger tables into smaller tables to reduce redundancy. The tables are then linked back together by a key if necessary within a query. There is a cost saving benefit in reducing duplication, however a consideration to take into account with cloud providers is that compute is more expensive than storage. Consider a scenario: you have a 5TB table in BigQuery, there is potential to normalize it, but that would depend on your primary use case. Will most of your queries require all the columns within the same table to be present? In which case you are better off keeping it as is, since joins can be quite computationally expensive which will rack up costs. In the other case, if you have more specific queries for certain columns, you are better off normalizing it where you will be able to make targeted cheaper queries on less wide tables using less storage. 

Data can be stored in a database in either row-based or column-based formats. The difference in storage affects the use cases of the data, as column-based data storage is more efficient for analytics than row-based data storage. The primary difference is that in column-based data storage, data is grouped together within blocks, making it quicker and cheaper to access when querying large number of records.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DDIA/Chapter_3_-_Design_scalable_systems.pdf)**

**Content:** Designing Data-Intensive Applications

### Day 10

**Topic:** Airflow

Workflow orchestration refers to the management and coordination of dependencies between functions in large and complex applications or workflows. The goal of workflow orchestration is to improve the efficiency, reliability, and scalability of data pipelines, as well as to provide an intuitive way to visualize workflows and trigger jobs based on the completion of previous necessary jobs. Additionally, it helps with monitoring and collaboration. An example workflow can be seen as a Directed Acyclic Graph (DAG), which is a visual representation of the relationships between tasks in the workflow and the execution order, including dependencies. Airflow is an Apache open-source framework for workflow orchestration, created by Airbnb, to help solve problems with managing large and complex workflows. The architecture of Airflow consists of a Web Server, a Scheduler, Workers, a Database, and Task Definitions. The Web Server provides a graphical user interface to manage and visualize workflows, trigger DAGs, and view logs and status updates. The Scheduler is responsible for scheduling and triggering tasks in the workflow, and keeping track of task dependencies. Workers are the nodes that perform the required work as defined by Airflow. The Database stores information about the workflow, including task state, execution dates, and task logs. Task Definitions define the individual tasks that can make up the workflow, and can be written in python or any other language. The backend database used by Airflow can be SQLite for local and testing environment tasks, but for production tasks, PostgreSQL is recommended. Redis is used as a distributed cache to share information across a cluster of Airflow workers and as a message queue to handle pub/sub messaging. The CeleryExecutor is a type of executor that allows tasks to be run in parallel on a group of worker nodes and is designed to scale the number of nodes horizontally. To set up Airflow, you will need to store your Google Cloud Platform service account file in the Home directory and upgrade your Docker Compose version, setting the minimum memory for your Docker engine to 5GB. To install Airflow, you can choose to use Docker or pip. If using Docker, you will need to know how to use Docker Compose, as it relies on several containers. If using pip, you can install Airflow and its dependencies directly into your Python environment. Airflow is not particularly well suited for small data engineering tasks due to it's high resource requirements to run. Another solution is prefect, which is a new orchestration tool provided by a for profit company. It's API is more intuitive and UI is nicer, however it's community is significantly smaller.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/tree/main/Notes/Data_engineering_bootcamp/Airflow.pdf)**

**Content:** Data Engineering Zoomcamp

### Day 11

**Topic:** BigQuery

BigQuery is a data warehouse solution offered by Google Cloud Platform (GCP) that is designed to handle very large datasets at a scale of petabytes and to perform high-speed querying. The service is fully managed and serverless, meaning that users do not have to worry about the management of underlying infrastructure or operations. BigQuery tables are stored in a column-oriented format, which is efficient for high-read throughput and allows for quick analysis of data. BigQuery uses a micro-service architecture to allocate storage and processing resources based on usage patterns, which helps to optimize performance and cost efficiency. One key feature of BigQuery is that it supports SQL queries and provides a query service for querying native tables. Data can also be queried from external sources, referred to as federated queries, and a query job can also write to a destination table. BigQuery provides a query validator with a pricing calculator that can be used to estimate costs. BigQuery pricing is based on two models: analysis pricing and storage pricing. Analysis pricing covers the cost of processing queries, including SQL queries, user-defined functions, scripts, and certain data manipulation language (DML) and data definition language (DDL) statements. Storage pricing covers the cost of storing data that has been loaded into BigQuery. The amount of data processed is based on the columns selected and the types of data in the column. BigQuery datasets are organized into units called datasets and are referred to as project.dataset.table. Datasets belong to a project and IAM permissions are required to submit a job to the service. BigQuery datasets can be multi-regional, and every table has a schema that can be entered manually or by supplying a JSON file. Access control is managed through IAM and is configurable at the dataset, table, view, or column level. Additionally, BigQuery provides predefined roles for controlling access to resources and row-level security can be used to create a row access policy. Sharing datasets with other analysts is simple, and an authorized view can be created to share query results with a particular group without giving them access to the underlying data. BigQuery slots are a combination of CPU, memory, and networking resources that are allocated to queries based on intensity. You have access to up to 2000 concurrent slots, which are shared among all queries in a single project. BigQuery uses a columnar data structure, so charges are based on the total data processed in the columns selected. You are not charged for queries that return an error or for queries that retrieve results from the cache. Canceling a running query job might incur charges up to the full cost for the query. I will provide extra infromation on how BigQuery works internally, and how you can monitor the costs relating to it. 

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/Data_engineering_bootcamp/Data_Lakes_and_Data_warehousing.pdf)**

**Content:** Data Engineering Zoomcamp

### Day 12

**Topic:** Computer Systems Architecture

A general-purpose processor is a CPU capable of executing a variety of instructions that can be used by many different types of software applications. The first category is single processor systems. As the name suggests, these systems have only one general purpose processor. Single processor systems also have special-purpose processors that perform device-specific tasks. For example, a keyboard has a microprocessor that converts keystrokes to code to be inputted into the system. The second category is multiprocessor systems. Multiprocessor systems have two or more general-purpose processors that communicate closely with one another. This means they share resources such as memory, peripheral devices, and the computer bus, which is the pathway through which data travels between different components of the system. Multiprocessor systems have several advantages. They increase throughput, which is a measure of a system's performance and efficiency. They also provide economy of scale, which means that as the system increases in size, the cost per unit of output decreases. Furthermore, multiprocessor systems increase reliability by providing redundancy. If one processor fails, the work can be picked up by another processor. There are two types of multiprocessor systems: symmetric multiprocessing and asymmetric multiprocessing. Symmetric multiprocessing involves all CPUs performing a single task at a time. This concentration of processors significantly increases processing power, which could increase the speed of performing tasks. It is scalable as you can easily add additional processors to the system. The disadvantage is that this is a complex system that increases in complexity as the number of processors increases and can also lead to resource contention. Asymmetric multiprocessing involves one of the processors acting as a master and the others acting as slaves. The master processor monitors the slaves and assigns tasks or processes to the processors. If something fails, the master takes care of how to take care of the failure and distribute the load. This allows systems to handle different tasks with different needs. It is also cheaper to implement than a symmetric multiprocessing system. Disadvantages include resource underutilization, as some processors will be assigned to tasks that do not require their full capacity, and the system is limited in scalability as it may require more hardware and software changes to add processors. The third category is clustered systems. Clustered systems are similar to multiprocessor systems, as they gather together multiple CPUs to accomplish computational work. However, the major difference is that clustered systems are composed of two or more individual systems coupled together. The complete system is coupled together, forming a cluster. Clustered systems provide high availability, as they have more than one system, which provides redundancy. They can be structured asymmetrically or symmetrically. Asymmetric clusters have one machine in hot-standby mode (master), while others run applications. Symmetric clusters have two or more hosts that run applications and monitor each other.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/Computer_science/Operating_systems.pdf)**

**Content:** Operating systems course

### Day 13

**Topic:** DDIA Chapter 4 #1 - Encoding

Forward and backward compatibility are essential for building systems that can handle changes to an application over time. When applications evolve, the changes often affect the data, so systems must be able to handle the compatibility of the data between older and newer versions of the application. To achieve forward and backward compatibility, data engineers use encoding and decoding to translate data between in-memory representation and byte sequences. Encoding is the process of converting in-memory objects into a self-contained sequence of bytes, while decoding is the process of converting byte sequences back into in-memory objects. There are various encoding formats available, including language-specific formats like pickle for Python, as well as standardized encodings like JSON, XML, and Binary. Each format has its pros and cons, and the chapter covers them in detail. To address backward and forward compatibility, standardized encodings like Thrift, Protocol Buffers, and Avro use a schema to encode data. These encodings do not include field names in the schema and instead use field tags, which act as aliases for fields. Field tags are crucial to maintaining backward and forward compatibility, even with schema changes. Avro handles schema evolution by allowing the writer's and reader's schema to be different but compatible. The Avro library resolves any differences between the two schemas by comparing them side-by-side. Data flow can happen through different modes, including databases, REST, and RPC. For example, in data flow through databases, backward and forward compatibility is essential, as older and newer versions of the application might access the same database.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DDIA/Chapter_4_-_Design_Scalable_systems.pdf)**

**Content:** Designing Data-Intensive Applications

### Day 14 

**Topic:** Airflow project walkthrough

This project makes use of 3 tools and technologies. Terraform, Airflow, and Docker. The purpose of this project is to create an orchestrated pipeline that will extract data from the web, stage it, process and transform it in a Google Cloud Storage bucket, and then upload it to BigQuery for analysis. Reliability, scalability and maintainability are the primary design concerns when creating data piplines. Using Terraform as our cloud infrastructure as code solution ensures that our cloud configurations can benefit from version control. Airflow enables us to handle task dependencies in a scalable fashion making use of Dags, an example of it's usefulness in this project is the creation of a BigQuery table prior to loading the data into it. Docker provides us with an isolated environment where we can manage our environment variables such as google cloud credentials, and handles dependencies for airflow as well as provides an internal network for the webserver, postgres database and scheduler to communicate. 

**Workflow**
<p align="center">
  <img width="800" height="400" src="https://github.com/alexandergirardet/training-projects/blob/main/airflow/images/airflow_practice_project.drawio.png">
</p>

**Docker**

A little bit more information on our Docker configuration. In this project we have two docker related files: Dockerfile and docker-compose.yaml. This project is making use of a technique known as extending docker images. Within a fully fledged production airflow environment we would usually be hosting a reddis broker, and make use of celery to serve several airflow worker nodes that will handle the actual computing needs of our tasks. However due to the small resource requirements of this project, I configured docker to handle it's computing needs in the airflow scheduler. For this reason we needed to provde the airflow scheduler with several libraries that our project makes use of, most notably the google cloud SDK, and the airflow google providers, which gives us access to the GCP airflow operators. The Dockerfile use a pre-configured airflow image as it's base image, and extends it's configurations by installing the libraries within the requirements.txt, and downloads the Google SDK, and extends the path to access the SDK. Within our docker-compose file which handles the serving of the airflow webserver, the scheduler, and the postgres database we use our custom built airflow image with all the dependencies we need. Finally, as shown in the docker-compose.yaml file, we mounted our google credentials file, and created the environment variable GOOGLE_APPLICATION_CREDENTIALS so that our Google cloud storage client can authenticate itself to access our cloud resources. 

**Terraform**

Terraform is used in this case to provision our Google cloud bucket, and create a BigQuery dataset. We also made use of the variables.tf file to show the practicality of modularizing our terraform components, and prevent redundancy.

**Airflow**

Within our airflow setup we make use of one dag that contains four tasks in our workflow. The extract_data_task makes use of curl and downloads the dataset to a temporary folder within our scheduler. Once this process is complete, the upload_to_gcs_task, initializes the storage client, and sends the file from the temporary folder to our bucket as specified in our airflow variables. The create_table_task will then create a BigQuery table making use of the BigQueryCreateEmptyTableOperator, and finally upload_to_bq_task uses the GCSToBigQueryOperator to upload the GCS file to BigQuery. It is worth noting that both BigQuery operators required an airflow connection, which abstracts validating your google certs. In all this project served as a good introduction to the uses and synergies of airflow, terraform and Docker.

**[Project](https://github.com/alexandergirardet/training-projects/tree/main/airflow)**

**Content:** Airflow, Terraform, Docker, Docker-compose


### Day 15

**Topic:** Origins of Mathematics

Mathematics is a field that has been built upon itself, with each new idea and discovery building on what has come before it. Axioms, which are basic statements or assumptions that are accepted as true without having to be proved, serve as the foundation for the axiomatic method used by the Greeks to derive new results. The axiomatic method allowed mathematicians to use previously proven theories as well as basic logical rules to derive new results consistent with the axioms. This process of logical deduction allowed the Greeks to establish rigorous and precise arguments that are guaranteed to be true if the underlying assumptions are themselves true. This provided a high degree of certainty and reliability in mathematical proofs. Throughout history, different civilizations have contributed to the development of mathematics. The Babylonians, ancient Greeks, Egyptians, and Hindus all made great contributions to the field. These civilizations relied on empirical evidence as the basis for their mathematical methods and formulas. They used practical mathematics to solve everyday problems, which led to the development of various branches of mathematics such as algebra, trigonometry, geometry, and arithmetic. The Greeks viewed mathematics as a field of study in its own right, rather than just as a tool to solve practical problems. The development of theoretical and philosophical study of mathematics allowed the Greeks to detach mathematical use cases from real-world problems and develop more theoretical and philosophical conclusions. It is often said that the Greeks created mathematics and that very little has been added since their time. However, this statement is not entirely true. The body of knowledge and method of study established by the Greeks has allowed for major new breakthroughs and developments in mathematics, especially when mathematicians started working closely with scientists in the seventeenth century. This led to the development of calculus, which provided new tools and techniques for modeling complex systems and enabled advances in physics. The power of abstraction is another key feature of mathematics. Abstraction is the process of simplifying or generalizing objects, events, ideas, or systems to extract the fundamental concepts behind them. Abstraction is a human-made concept that is a product of human language and thinking. In the context of knowledge, abstraction involves separating the key features or characteristics of something from its specific details or context. This allows us to apply abstract concepts across many situations or objects. Abstraction is related to the process of idealization, which is the deliberate distortion or approximation of some features within the physical world. Idealization allows for the creation of simplified models of complex objects or phenomena by assuming certain idealized conditions or properties. The difference between abstraction and idealization is that abstraction is concerned with simplifying and generalizing the properties of concepts or ideas, while idealization is used to simplify the objects and phenomena in the real world. Logical reasoning is a fundamental aspect of mathematics. Deductive reasoning, which is based on drawing conclusions from previous true assumptions or premises using logical principles, provides a high degree of certainty and reliability in mathematical proofs. Inductive reasoning, on the other hand, is the drawing of conclusions or making generalizations based on observations or evidence. The conclusions that are drawn from inductive reasoning are probabilistic and uncertain. Reasoning by analogy and abductive reasoning are other forms of logical reasoning used in mathematics.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/Maths/Mathematics_for_the_non_mathematican.pdf)**

**Content:** Mathematics for the non-mathematician

### Day 16

**Topic:** The data engineering lifecycle

Working in a very large 80 billion dollar company as a data engineer comes with it's benefits, but also (for the short term) it's downsides. On one side you are exposed to the data lifecycle, and how a company applies it in it's everyday workflows and enables better data driven decision making. You also get to work alongside with people that have many more years experience than you. On the other hand however, the company is so vast that getting a clear picture of exactly how you are creating value and where you inputs lie within the data value add chain is very difficult. For this reason I have started to read the Fundamentals of Data Engineering book published by O'Reilly. I believed this book, combined with DDIA, and the data engineering zoomcamp will serve as a good basis for my understanding in DE practices. The central theme of the book revolves around the Data engineering life cycle, which is itself a subset of the data lifecycle (We will get to this through a later book). The lifecycle comprises stages that turn raw data ingredients into useful data products ready for consumption. The author puts forth the idea that as many of the DE technical complexities are abstracted away, DE will shift to data lifecycle engineers and therefore need a higher level view. 
<p align="center">
  <img width="800" height="400" src="https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/static/de_lifecycle.png">
</p>
The lifecycle concerns itself with ingesting data from source and storing it, and then transforming it so that it can be ready for it's final goal of serving it. Storage can occur at many stages within the lifecycle. Additionally, undercurrents are core components to the cycle that enable the data engineering lifecycle to function properly within an industrial production environment. In follow up posts, I will go through each stage and undercurrent highlighted in the image one by one


**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DE_Fundamentals/Fundamentals_of_Data_Engineering_Chapter_2.pdf)**

**Content:** Fundamentals of Data Engineering Chapter 2

### Day 17

**Topic:** Data architecture

Data architecture is a subset of enterprise architecture, which involves analyzing, designing, planning, and implementing a comprehensive framework of an organization's IT and business strategies. The primary objective of enterprise architecture is to ensure that an organization's IT and business strategies are aligned and support each other. Enterprise architecture involves flexible and reversible decisions that allow an organization to adjust its course as the world changes and gather new information. It also involves change management and breaking large initiatives down into smaller changes, with each one being a reversible decision in itself. Trade-offs are inevitable in the engineering space, and data engineers must account for them at every step of the design stage while minimizing high-interest technical debt. Data architecture is the design of systems to support the evolving data needs of an enterprise, achieved by flexible and reversible decisions reached through careful evaluation of trade-offs. There are two components of data architecture, operational architecture, and technical architecture. Operational architecture encompasses the functional requirements of what needs to happen, while technical architecture outlines how data is ingested, stored, transformed, and served along the data engineering lifecycle. Good data architecture serves business requirements with a common, widely reusable set of business blocks while maintaining flexibility and making appropriate trade-offs. Bad architecture, on the other hand, is authoritarian and tries to cram a bunch of one size fits all decisions into a big ball of mud. A big ball of mud is used to describe a system or application that is complex, disorganized, and difficult to maintain or change. It is typically the result of years of ad-hoc development, where decisions are made on the fly and without a clear architecture plan. Therefore, agility is the foundation for good data architecture, which acknowledges that the world is fluid. Bad data architecture, on the other hand, is tightly coupled, rigid, overly centralized, or uses the wrong tools for the job, hampering development and change management.


**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DE_Fundamentals/Fundamentals_of_Data_Engineering_Chapter_3.pdf)**

**Content:** Fundamentals of Data Engineering Chapter 3


### Day 18

**Topic:** Data architecture principles

The principles for good data architecture outline in the book are:

1. Choose common components wisely
2. Plan for failure
3. Architect for scalability
4. Architecture is leadership
5. Always be architecting 
6. Build loosely coupled systems
7. Make reversible decisions
8. Prioritize security 
9. Embrace FinOps

**Choose common components wisely:** Common components are anything that has broad applicability within an organization. Choosing common components that can faciliate team collaboration, and break down silos will enable agility within teams. They must also support robust permissions and security to enable sharing of assets among teams.

**Plan for failure:** Even though modern hardware is highly robust and durable the saying goes "Everything fails, all the time". Consider failures in your design and look into the concepts of Reliability, availability, recovery time objective and recovery point objective.

**Architect for scalability:** One of the three main concerns mentioned in DDIA, make sure you systems have the ability to scale up and down. This is also known as elastic systems that can scale dynamically in response to load in an automated fashion.

**Architecture is leadership:** Data architects should be highly technically competent, but be able to delegate work to others. You should be able to mentor current data engineers, make careful decisions in relation to business context and train engineers in best practices.

**Always be architecting:** Data architects don't simply maintain the existing states, instead they constantly design new and exciting things in response to changes in business and technology. Develop deep knowledge of the current architecture, develop a target architecture and map out a sequencing plan to determine priorities to get there.

**Build loosely coupled systems:** The architecture of the system should be designed to enable teams to test, deploy and change systems without dependencies on other teams. The Bezos API mandate was a watershed moment for Amazon as it put data and services behind APIs which enabled loose coupling of business functions. 

**Make reversible decisions:** With a rapidly shifting data landscape it is important to aim for reversible decisions as they simplify your architecture and keep it agile. 

**Prioritize security:** Assume responsibility for the security of the system you build and maintain. Data engineers should consider themselves security engineers. 

**Embrace FinOps:** Data Engineers need to embrace financial management in cloud environments as it they are more reflective of pay as you go approaches. In this monitoring should be emphasized.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DE_Fundamentals/Fundamentals_of_Data_Engineering_Chapter_3.pdf)**

**Content:** Fundamentals of Data Engineering Chapter 3

### Day 19

**Topic:** Data architecture concepts

The main goal of all architecture concepts is to take data and transform it into something useful for downstream consumption. To achieve this goal, data engineers need to understand domain and services, distributed systems, scalability, designing for failure, tight versus loose coupling, user access, event-driven architecture, and brownfield versus greenfield projects. To begin with, domain refers to the real-world subject area for which you are architecting, while services are a set of functionality whose goal is to accomplish a task. Domains can contain multiple services, and to identify domains, data engineers should focus on what it represents in the real world and work backward by talking to users and stakeholders. The best practice is to avoid architecting in a vacuum. Data engineers are interested in four closely related characteristics of data systems, including scalability, elasticity, availability, and reliability. Scalability allows engineers to increase the capacity of a system to improve performance and handle the demand, while elasticity is the ability of a scalable system to scale dynamically. Availability refers to the percentage of time an IT service or component is in an operable state, while reliability is the system’s probability of meeting defined standards in performing its intended function during a specified interval. Distributed systems are widespread in data architecture, and almost every cloud data warehouse object system has some notion of distribution under the hood. Data engineers need to know how much interdependence they want to include within their various domains, services, and resources. Extremely centralized approaches are known as tightly coupled, while decentralized domains and services that do not have strict dependence on each other are known as loose coupling. Designing good data architecture relies on trade-offs between the tight and loose coupling of domain and services. Multitenancy refers to the ability of a software system or application to serve multiple tenants, or customers, on a shared infrastructure. Multiple users or organizations can access the same software system, and their data is kept separate and secure from other tenants. With multitenancy, there are two factors to consider: performance and security. With multiple large tenants within a cloud system, can the system support consistent performance for all tenants, or will there be a noisy neighbor problem? Regarding security, data must be properly isolated from different tenants. Events are broadly defined as something that happened, typically a change in the state of something. An event-driven workflow encompasses the ability to create, update, and asynchronously move events across various parts of the data engineering lifecycle. This workflow boils down to three main areas: event-production, routing, and consumption. An event must be produced and routed to something that consumes it without tightly coupled dependencies among the producer, event router, and consumer. Finally the context of the project is important. Brownfield projects involve refactoring and reorganizing an existing architecture and are constrained by the choices of the present and past. A popular approach to brownfield projects is the strangler pattern, where new systems slowly and incrementally replace a legacy architecture’s components. Eventually, the legacy system is completely replaced. Greenfield projects are fresh start projects unconstrained by legacy systems, and a common pitfall is teams feeling compelled to reach for the latest and greatest technology fad without understanding how it will impact the project.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DE_Fundamentals/Fundamentals_of_Data_Engineering_Chapter_3.pdf)**

**Content:** Fundamentals of Data Engineering Chapter 3

### Day 20

**Topic:** Data architecture examples

Due to the abstract nature of data architecture, reasoning by example is helpful as it allows us to develop a deeper understanding of the concepts by relating to real life use cases. 

Data Warehouse:
A data warehouse is a central hub used for reporting and analysis. It is highly structured and formatted for analytics use cases. A data warehouse is defined as a subject-oriented, integrated, nonvolatile, and time-variant collection of data in support of management's decisions. Data warehouses are designed to be subject-oriented, integrated, non-volatile, and time-variant. Organizational data warehouse architecture separates online analytical processing from production databases and centralizes and organizes data. Technical data warehouse architecture, on the other hand, reflects the technical nature of the data warehouse. There are two primary ways to load data into a warehouse: ETL and ELT. ETL transforms the data before arriving in the warehouse, while ELT takes advantage of the separation between storage and compute. Previously, compute and storage in data warehouses were tightly coupled, leading to competition of resources. Separating compute and storage means that companies can scale their storage and compute independently of each other. It also reduces the I/O bottlenecks when processing and storing data on the same servers.

Data Marts:
A data mart is a more refined subset of a warehouse designed to serve analytics and reporting focused on a sub-organization.

Data Lake:
A data lake is a centralized repository that can store raw, unprocessed data in its native format. Data lakes enable organizations to store and process data in its unaltered format from multiple sources. Initially started with Hadoop Distributed File System, data lakes quickly became dumping grounds for data, leading to the emergence of data lakehouses.

Data Lakehouses:
Data lakehouses aim to combine the advantages of data warehouses with the advantages of data lakes. The lakehouse approach provides a platform that incorporates the controls, data management, and structures found in data warehouses while still storing data in object storage and supporting a variety of query and transformation engines.

Modern Data Stack:
The modern data stack makes use of cloud-based, plug-and-play, easy-to-use, off-the-shelf components to create a modular and cost-effective data architecture. These components include data pipelines, storage, transformation, data management/governance, monitoring, visualization, and exploration.

Lambda Architecture:
Data engineers wanted a way to combine batch processing and stream processing in a single architecture, as there were scenarios where real-time analysis was needed as well as long-term analysis of the data was relevant. This led to the creation of the Lambda architecture.

Kappa Architecture:
This architecture lies on the thesis of using streaming processing as the backbone for all data handling-ingestion, storage, and serving. Real-time and batch processing can be applied seamlessly to the same data by reading the live event stream directly and replaying large chunks of data for batch processing.

The Dataflow Model and Unified Batch and Streaming:
The dataflow model and the Apache Beam framework allow for unifying code paths. The core idea is to view all data as events, as the aggregation is performed over various types of windows. Real-time and batch processing happen in the same systems using nearly identical code.

Architecture for IoT:
Internet of Things (IoT) is the distributed collection of devices that are connected via a network, allowing them to collect and transmit data. IoT devices can be used in a variety of industries to collect data about the environment around them, including temperature, humidity, and motion. To manage the large volumes of data generated by IoT devices, a specific IoT architecture is required. This architecture consists of three main components: the IoT gateway, ingestion, and storage.

- IoT Gateway:
The IoT gateway is a hub that connects devices and securely routes them to the appropriate destinations on the internet. IoT gateways provide a level of security by acting as a buffer between the internet and the devices, protecting the devices from potential security threats. They also allow devices to connect using extremely little power, making them ideal for use in low-power environments.

- Ingestion:
Ingestion is the process of collecting data from IoT devices and storing it in a data store. This process begins with the IoT gateway, which receives data from the devices and passes it on to the ingestion system. The ingestion system then processes the data and stores it in a data store, such as a message queue or a time-based database.

- Storage:
Storage is a critical component of any IoT architecture, as it enables data to be stored and processed over time. Storage requirements will depend on the latency requirements for the IoT devices in the system. In many cases, a message queue or a time-based database is appropriate for storing IoT data. Data can be batch or near-real-time analyzed, and detections for anomalies can also occur.

Data Mesh:
Data Mesh is a new approach to organizing data and data teams that has emerged to address the challenges organizations face when managing data at scale. The Data Mesh approach emphasizes autonomy, decentralized governance, and domain-driven design. Instead of flowing data from domains into a centrally owned platform, domains need to host and serve their domain datasets in an easily consumable way.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DE_Fundamentals/Fundamentals_of_Data_Engineering_Chapter_3.pdf)**

**Content:** Fundamentals of Data Engineering Chapter 3

### Day 21

**Topic:** Networking on Google Cloud

Networking is an essential component of cloud computing, enabling communication and data exchange between different devices, both within a single organization and across the internet. In the context of Google Cloud, networking can be explained through a series of analogies and consists of three layers: Virtual Private Cloud (VPC), Subnets, and Routers.

A VPC can be thought of as a virtual version of a physical network that houses your resources. It is a secure and isolated environment within the cloud where you can control access to your resources, customize your network configuration, and choose the resource IP addresses. A VPC acts as a private neighborhood for your resources in the cloud. Within a VPC, you can decide which resources can talk to each other and which ones can talk to the outside world. You can control access to them with firewalls, making it an ideal solution for organizations that need a secure and isolated network environment for their resources.

Subnets allow you to further organize and segment your networking into smaller, more manageable parts. Subnets are a smaller part of a larger network, and they can be thought of as houses within a neighborhood. Subnets group services together logically, allowing for granular access to resources, IP address management, network traffic control, and resource organization. For instance, in the context of a stock market app, you could divide the resources into different subnets based on the function of each resource and the security requirements of the application. A web server subnet would contain resources relating to the front-end users of the application and would allow incoming traffic from HTTP and HTTPS ports. A database subnet would contain database resources that store information and stock market data. Firewall rules in this subnet would allow access from the backend application server subnet.

Firewalls serve as a bouncer for the resources in your network. Firewalls ensure granular access to resources, allowing you to set rules for what traffic can access your resources. You can think of firewalls as bouncers at different points in your network, such as at the gate of the neighborhood, at the step of the house, and right in front of the resources. The modularity of the network architecture allows you to have bouncers that ensure access to similar types of resources.

Routers serve as a traffic director, forwarding networking traffic from one part of the network to another. They allow traffic to be routed to your resources within your network and subnets.

IAM permissions and firewall rules allow ingress and egress traffic inside your network. Ingress refers to the flow of data entering a network, while egress refers to the flow of data leaving a network. IAM allows you to set granular policies to practice the principle of least privilege, giving you complete control over your network architecture. Firewall rules allow you to control access to your resources, ensuring the security and performance of your network.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/Certificates/Associate_Cloud_Engineer.pdf)**

**Content:** Associate Cloud Engineer

### Day 22

**Topic:** Real Estate Project

As a aspiring Data Engineer and ML Engineer there are many skills you would like to develop and show off. Over the past few weeks I have learned about the undercurrents relating to managing the data engineering lifecycle, many of these skills are not necessarily hard skills and harder to show a good understanding of through projects. However, the creation of pipelines that handle ingestion, transformation and serving, all while being stored and using software engineering best practices is the goal behind these two projects. Most notably, there will be two projects relating to the data engineering: A batch processing one, and a stream processing one. My Real Estate Project is a batch processing project that handles everything from data extraction, ingestion, transformation and serving. 

The real estate project is an end to end pipeline that uses the web scraping framework, Scrapy, to extract data from Rightmove. A UK based real estate platform that contains listings for rentals and sales across the country. I understand that scraping data can be frowned upon, and I hereby declare that I am not using the data scraped from this website for commercial purposes, and that any use of the data is solely for personal or educational purposes. Additionally I am very sensitive to not overwhleming their servers by putting limits in place for the amount of requests I can make at any time. The goal of the project is to use the data to provide some interesting insights, and create a Machine Learning model that can predict the rental value of a property from it's sale listing. This will reflect by SparkML skills. However in the short term I aim to create a live orchestrated, cloud hosted pipeline that ingests, transforms and stores data every 24 hours, and serves it on a dashboard. 

At the time being I have created a pipeline that extracts sites from rightmove, stores them in a Google Cloud Bucket as a JSON file, and then uses a custom made script that transforms the data and enforces a parquet schema so that the data is reproducible. I chose a Parquet schema as the data for a site contains embedded JSON in a few columns. Finally the data is stored in a new GCS folder as processed parquet files. Thus far I have extracted roughly 3000 sites, and I have visualized their locations below using Data Studio. 

<p align="center">
  <img width="500" height="500" src="https://github.com/alexandergirardet/real_estate_analytics/blob/main/src/rightmove_locations.png">
</p>

**[Project](https://github.com/alexandergirardet/real_estate_analytics/tree/main)**

**Content:** Real estate Project

### Day 23

**Topic:** Computation

SICP is considered a classic computer science book that has influenced many other programming languages and books. It's emphasis on the fundamental concepts in computer science using it's approachable stle of building up to more complex topic, as well as the paradigm shift and emphasis on critical thinking makes it a must read for aspiring programmers. 

Programming is a highly intellectual activity that involves creating models of real or mental processes. These models are used to understand and predict the behavior of the process. However, the task of creating these models can be complex, with intricate details that are not fully understood at the outset. Thus, programmers need to continuously refine and improve their models over time as they gain more insight into the process.

To achieve correctness in programming, it is essential to develop a collection of standard program structures whose correctness is assured. This becomes increasingly important as programs get larger and more complicated.

In the context of SICP, the authors aim to establish the idea that a computer language is not just a way of getting a computer to perform operations, but rather, it is a novel formal medium for expressing ideas about methodology. Computer science is not a science but a revolution in the way we think and express what we think. This change has led to the emergence of procedural epistemology, which is the study of the structure of knowledge from an imperative point of view, as opposed to the more declarative view taken in mathematics.

Lisp, the programming language used in SICP, is particularly well-suited for teaching fundamental computer science concepts such as recursion, abstraction, and higher-order functions. Lisp's minimal syntax, powerful list manipulation facilities, and support for recursion, abstraction, and higher-order functions make it an ideal language for teaching the importance of proper syntax and syntax trees.

**[Notes](https://github.com/alexandergirardet/real_estate_analytics/tree/main)** TO FIX

**Content:** SICP

### Day 24

**Topic:** Fundamentals of Data Engineering Chapter 4 Part 1

Choosing the right technology for data engineering requires a lot of considerations. In this blog post, we will discuss the key factors to keep in mind when choosing the appropriate technology for data engineering lifecycle. The primary aim of data engineering is to design reliable and robust systems to carry data through the full lifecycle and serve the needs of end-users. Therefore, it is vital to focus on the value added to the end-user rather than chasing bleeding-edge technology. The following are key considerations when choosing the right tools for data engineering:

Architecture first design
It is essential to focus on the what, why, and when of architecture rather than how, which refers to the tools. While tools are necessary for data engineering, they should not be the primary focus when designing the architecture.

Team size and capabilities
The size of the team and their capabilities are crucial in determining the complexity of tools to adopt to produce the architecture. Small teams should use managed solutions and SaaS to put off technical complexity and focus on adding value, while large teams can benefit from more complex tools.

Speed to market
Speed to market is a crucial consideration in data engineering. It is essential to choose technologies that help deliver features and data faster while maintaining high-quality standards and security. It also means working in a tight feedback loop of launching, learning, iterating, and making improvements.

Interoperability
Interoperability describes how various technologies or systems connect, exchange information, and interact. It is vital to choose tools that interact seamlessly with other tools across the data engineering lifecycle. Modularity and flexibility should be designed into the architecture to allow for the easy swapping of technologies as new practices and alternatives evolve.

Cost optimization and business value
The total cost of ownership (TCO) and the total opportunity cost of ownership (TOCO) should be considered when choosing tools. It is essential to understand the basic costs you can control, such as direct and indirect costs, and how expenses fall into two big groups: operating expenses (OPEX) and capital expenses (CAPEX). An opex-first approach centered on the cloud and flexible pay-as-you-go tech is recommended. FinOps is a useful practice that applies DevOps-like practices of monitoring and dynamically adjusting systems to fully operationalize financial accountability and business value.

Today versus the future: Immutable versus transitory technologies
When choosing technologies, it is vital to focus on the present and near future while considering handling future unknowns and evolution. Identifying immutable technologies from transitory ones every two years, using the immutable technologies as your base and building transitory tools around them, and considering how easy it is to transition from a chosen technology is recommended.

Location
Premises, Cloud, Multi-Cloud, and Hybrid cloud are the options for location. It is essential to choose the right location depending on the company's specific needs. Cloud providers use virtualization to sell slices of hardware but also sell these pieces with varying technical characteristics and risks attached, similar to financial derivatives. An opex-first approach is recommended, and users should aim to increase business value by leveraging the dynamic value of the cloud.

Managing your own hardware
Very large companies may have specific needs where the economies of scale at which managing your hardware and network connections make sense. This usually requires massive workloads.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DE_Fundamentals/Fundamentals_of_Data_engineering_Chapter_4.pdf)**

**Content:** Fundamentals of Data Engineering Chapter 4

### Day 25

**Topic:** Kimball's Data Warehouse Toolkit Chapter 1 Part 1

In the world of business intelligence, data warehousing is a critical process that allows organizations to gather and analyze data to make informed decisions. One of the most popular approaches to data warehousing is the Kimball Dimensional Modeling Approach. This approach, developed by Ralph Kimball, emphasizes the use of dimensional modeling, which is a way of organizing data into easy-to-understand, multidimensional views. This approach has been widely adopted by businesses around the world due to its simplicity and effectiveness.

Snowflaking and Star Schemas
The Kimball approach involves the use of star schemas, which consist of a central fact table surrounded by dimension tables. This arrangement makes it easy to query data and perform analysis. The approach also advises against normalizing data by storing only a code in the product dimension and creating a separate lookup table. Instead, dimension tables are typically denormalized with flattened many-to-one relationships within a single dimension table, which increases storage capacity.

Data Granularity and Dimensionality
The Kimball approach also emphasizes data granularity, which is the specificity of the data. Granularity refers to the amount of detail in the data. The most granular data has the most dimensionality, meaning that it has more attributes or dimensions than less granular data. This is important because users may be interested in seeing the most fine-grained data. Additionally, in dimensional models, you can add completely new dimensions to the schema as long as a single value of that dimension is defined for each existing fact row.

Operational Source Systems
The Kimball approach recognizes that operational source systems, which capture a business's transactions, are outside of the data warehouse, and thus, outside of the DW/BI environment. You have no control over the content or format of the data.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/kimball_warehouse/The_data_warehouse_toolkit_Chapter_1.pdf)**

**Content:** Kimball's Data Warehouse Toolkit

### Day 26

**Topic:** Kimball's Data Warehouse Toolkit Chapter 1 Part 2

Extract, Transformation, and Load System
The ETL system is an essential part of the DW/BI environment. Extraction is the first step in the process of getting data into the DW. Once the data is extracted and copied in, it belongs to the DW. You will then transform the data such as cleansing it or dealing with missing elements. This adds value to the data. The load part is the physical structuring of the data into the presentation area's target dimensional models.

Presentation Area to Support BI
The DW presentation area is where data is organized, stored, and made available for direct querying by users, report writers, and other analytical BI apps. The presentation area should be structured around business process measurements events. This naturally aligns with the operational source data capture systems. They should not be designed to deliver the report of the day. You should construct a single fact table for atomic sales metrics rather than populating several similar databases.

All the dimensional structures must be built using common, conformed dimensions. The bus architecture is crucial in the presentation area as it prevents standalone tables that cannot be tied together. This is the bane of DW as it will lead to incompatible views of the enterprise. The bus architecture is a framework that enables agile, decentralized, realistically scoped, and iteratively made DW.

BI Applications
A BI application refers to the range of capabilities provided to business users to leverage the presentation area for analytic decision making.

Restaurant Metaphor for the Kimball Architecture
The Kimball approach is sometimes illustrated using the restaurant metaphor. The data warehouse ETL system is like the restaurant's kitchen. Source data is magically transformed into meaningful, presentable information. The back room ETL system must be laid out and architected long before any data is extracted from the source. The kitchen is designed to ensure throughput. Data quality comes in like raw ingredients that must be checked, conditions are continually monitored to ensure high integrity, and the kitchen is cut off from the presentation

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/kimball_warehouse/The_data_warehouse_toolkit_Chapter_1.pdf)**

**Content:** Kimball's Data Warehouse Toolkit

### Day 27

**Topic:** The Enterprise Data Warehouse Bus Architecture 

The Enterprise Data Warehouse (EDW) Bus Architecture is an incremental approach to building an enterprise DW system that decomposes planning processes into manageable pieces. It focuses on business processes, providing integration across standardized conformed dimensions that are reused across processes. The EDW Bus Matrix is an essential tool for designing and communicating the architecture, where the rows represent business processes and the columns represent dimensions. The shaded cells indicate whether a dimension is associated with a given business process.

The EDW Bus Matrix provides an architectural framework while also decomposing the program to encourage manageable agile implementations corresponding to the rows on the matrix. The detailed implementation bus matrix is a more granular version of the EDW Bus Matrix, showing specific fact tables or OLAP cubes. However, the implementation bus matrix is yet to be read from chapter 5.

Once the EDW Bus Matrix rows have been identified, the opportunity/stakeholder matrix can be drafted by replacing the dimension columns with business functions such as marketing, sales, and finance. Then, the matrix cells can be shaded to indicate which business functions are interested in which business process rows. This matrix is used to identify which business groups should be invited to the collaborative design sessions for each process-centric row.

Overall, the EDW Bus Architecture provides a systematic approach to building an enterprise DW system that focuses on business processes and delivers integration across standardized conformed dimensions. The use of matrices such as the EDW Bus Matrix and the opportunity/stakeholder matrix facilitates communication and collaboration among stakeholders involved in the process-centric rows.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/kimball_warehouse/The_data_warehouse_toolkit_Chapter_1.pdf)**

**Content:** Kimball's Data Warehouse Toolkit

### Day 28

**Topic:** Big Week for AI

Last week, Monday 13th of March to Sunday 19th was a massive week for Artificial Intelligence. This could be a week that is world changing depending on the new tools and uses that originate from the AI products/updates released this week. 

Monday: Stanford introduced the Alpaca 7B model. This is a large language model that has similar performance to GPT3 but more importantly is much more leightweight. It is trained on 52,000 instructions. An instruction is used to guide the model towards generating a certain type of output based on an input in the context of the instruction. GPT3 is a 165B model which makes it a lot more heavy weight compared to the Alpaca model. The Alpaca model could theoritically be trained from your laptop with a failry sophisticated Graphic's card. The impact of this release is that we are one step closer to democratizing largue language models.

Tuesday: Google released AI functionality inside of their workspace tools, such as google docs and Gmail. Where you can autocomplete your emails, write articles etc... Very similar to GPT3 but directly inside of Google tools. Additionally, it will also be integrated inside of google sheets and slides. I would be very curious to see the impact it has on financial models that rely on sheets/excel to be properly run. Google also announced that they will be releasing PaLM API to a select amount of developers to build upon. PaLM is a multi-mode model which means it can accept both text and images as inputs. Anthropic introduced Claude, which is also another LLM based chat bot. Finally, GPT 4 was released.  Waching the live demo blew me away, GPT4 can understand much more complex prompts, but much like PaLM it will also bea multi-mode model as well. GPT4 in the demo was able to create the HTML and Javascript for a website template based on the sketch on a paper that was inputed into the model.

Wednesday: Midjourney released V5, and a magazine. The magazine is a curated collection of images from the community. But more importantly V5 is out which produces much more photo realistic images. Another major change is that Midjourney V5 is reimplementing image weights and more importantly will allow you to create images based on long prompts. It now accepts prompts as full sentences. This now enables ChatGPT to generate prompts to make images, ingest the image and update it's prompts based on the feedback from the ingested image. Incredible.

Thursday: Microsoft announced 365 co-pilot which is very similar to the Google Workspace announcement. Microsoft also introduced the new business chat, where it takes all the data from all of your Microsoft suite tools, and answer your question based on meeting notes, emails, and notes. It essentially creates a finetuned ChatGPT model for you. 

There were no more notable updates from the rest of the week. But I will be watching the Nvidia GTC conference regarding AI breakthroughs. 

**Content:** AI Updates

### Day 29

**Topic:** Jinja and DBT pairing

Jinja is a template engine that uses Python to generate dynamic markup languages. It allows developers to define variables and placeholders within a template, which are replaced with real values at runtime. Additionally, Jinja enables control structures like loops, conditionals, and macros for more complex template processing. DBT, on the other hand, is a data transformation tool that uses SQL to define models. By integrating Jinja with DBT, you can inject SQL based on inputs or parameters, making your data transformation logic more modular and maintainable. 

Jinja enables you to create a programming environment with SQL and follow best practices for software engineering. It allows for data engineers to utilize SQL in ways that weren't usually possible. By providing users with statements that are used to control flow, expressions that can output a string based on a variable. DE have much more uses for SQL based transformations. 

Macros is a jinja concept that is analogous to functions in Object oriented programming languages. It provides modularity in SQL and DBT allow you to create DRY (Don't Repeat Yourself) code. Additionally, it enables you to create consistent pipelines that make use of the same macros which can be greatly used with Kimball type datawarehouses. 

DBT also provides some advanced built in functions that can be used to create more complex macros. A few are: The run_query function allows you to run queries and return the results in a DBT macro, similar to a pandas DataFrame. The log function helps you monitor what's happening under the hood, which is useful when creating complex macros: The execute variable returns True when DBT is in "execute" mode, allowing you to defer compilation to the point of execution.

Overall Jinja is a great addition to the DBT environment and allows far greater flexibility in the transformation process of your data pipelines, and enable modeling of the data using SWE best practices. 

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DBT/jinja.pdf)**

**Content:** Jinja

### Day 30

**Topic:** SQL Window Functions

SQL Window Functions are a powerful tool for data engineers to analyze data and perform calculations based on a specific subset of rows within a larger dataset. In this blog post, we will explore the steps to understand SQL Window Functions and provide examples of different functions and syntax.

Step 1: Understand the Syntax

The syntax of SQL Window Functions is essential to understanding how they operate. The basic syntax is as follows:

function_name() OVER (PARTITION BY partition_clause ORDER BY order_clause ROWS BETWEEN frame_start AND frame_end);

The function_name is the calculation to be performed, such as SUM, AVG, or ROW_NUMBER. The OVER keyword is used to define the window function, with arguments to specify the partitioning, ordering, and range of rows over which the function should be computed.

Step 2: Choose a Function

There are many functions to choose from in a window function. Some of the most common include:

* SUM()
* AVG()
* MIN()
* MAX()
* ROW_NUMBER()
* RANK()
* LEAD()
* DENSE_RANK()
* LAG()
* PERCENT_RANK()
* NTH_VALUE()
* NTILE()

ROW_NUMBER: This function assigns a unique integer value to each row in the result set, based on the order specified in the ORDER_BY clause. It is useful when you need to number rows for grouping or ranking purposes. For example, use ROW_NUMBER to assign a unique ID to each row in a result set for further processing.

RANK: This function assigns a rank to each row in the result set, based on the order specified in the ORDER_BY clause. If multiple rows have the same value, they will receive the same rank, and the next rank will be skipped. For example, if three rows have the same value, and have the rank 1, 2, and 2, then the next rank will be 4 not 3. This is useful when you want to identify the top or bottom N rows in a result set, based on some criteria.

DENSE_RANK: This function assigns a rank to each row in the result set, based on the order specified in the ORDER_BY clause. If multiple rows have the same value, they will receive the same rank, and the next rank will be the next consecutive integer. For example, if three rows have the same value and have the rank, 1, 2, and 2, then the next rank will be 3. This is useful when you want to identify the top or bottom N rows in a result set, based on some criteria but you want to include ties.

LEAD: This function returns the value of a column in the next row of the result set, based on the order specified in the ORDER_BY clause. You can also specify an offset to retrieve the value from a row farther ahead. LEAD is useful when you want to compare a value in a row to the next or future values in the result set. For example, to calculate a percentage change or to identify trends.

LAG: This function returns the value of a column in the previous row of the result set, based on the order specified in the ORDER_BY clause. You can also specify an offset to retrieve the value from a row farther behind. LAG is useful when you want to compare a value in a row to the previous or past values in the result set. For example, to calculate a percentage change or to identify trends.

Step 3: Specify the Partitioning

The PARTITION_BY clause specifies how the rows should be partitioned. This means that the function will be computed separately for each partition. For example, if you want to compute a moving average for each customer, you might partition the data by Customer ID.

Step 4: Specify the Ordering

The ORDER_BY clause determines the order in which the rows are processed within each partition. This means that the window function will be computed in the order specified by the ORDER_BY clause. If you use a SUM function to calculate a running total of sales for each month, you might order the rows by month so that the function is applied in chronological order.

Step 5: Specify the Frame

The ROWS_BETWEEN clause specifies the frame of rows over which the function should be computed. This means that the function will be applied to a subset of rows within each partition, based on their position relative to the current row. The function takes two keywords to specify the start and end of the frame.

For example, you might specify ‘ROWS BETWEEN 2 PRECEDING AND CURRENT ROW’ to compute a moving average based on the last three months of data.

There are five possible frame specifications:

UNBOUNDED PRECEDING: Includes all rows from the beginning of the partition up to and including the current row.
n PRECEDING: Includes n rows before the current row up to and including the current row.
CURRENT ROW: Includes only the current row.
n FOLLOWING: Includes the current row up to and including n rows after the current row.
UNBOUNDED FOLLOWING: Includes all rows from the current row up to the end of the partition.
Window Function Visualized

To help visualize how SQL Window Functions work, let's review the key concepts.

Unlike normal aggregation functions with grouping, which only return one row per group, window functions return all rows, each having their calculated value based on their defined window. Window functions use the OVER keyword and its arguments to define the calculation window.

There are three parts to a window function:

Grouping: This defines the group that each row belongs to (PARTITION BY).
Order: This sorts values within each group and makes the window expand incrementally within each group (ORDER BY).
Range: This is used to further define the window size within each group (ROWS or RANGE).
Using these three parts, we can create powerful window functions that provide insights into our data.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/SQL/window_functions.pdf)**

**Content:** SQL

### Day 31

**Topic:** Update on estatewise project -- Completed orchestrated pipeline locally

This is a quick update regarding my estatewise project. I have completed the development of my pipeline that runs locally on my docker environment. My pipeline relies on 5 docker containers:

* postgres: which is an image of postgres database that allows me to host it locally on docker, and access it through the docker network.
* airflow-init: A container that is only run upon launch to trigger the launch of airflow, deploys it's dependencies and set's up the environment.
* airflow-webserver: A container containing the web server that hosts the airflow UI, allowing me to interact with airflow.
* airflow-scheduler: A container containing the airflow scheduler. In a production environment you would use worker nodes through celery or kubernetes but it is not necessary for this low scale flow at the moment.
* scrapyd-app: A container containing scrapyd which is an app for hosting and deploying scrapy spiders which allow me to extract data from the web in a asynchronous fashion.

<p align="center">
  <img width="900" height="500" src="https://github.com/alexandergirardet/real_estate_analytics/blob/main/src/docker_containers.png">
</p>


These containers share a bridge network. A bridge network is a shared network between docker containers that allow them to communicate between eachother. It is set up automatically with docker-compose. Within my applications I can access other apps through their container name. For example I access the scapyd app using: http://scrapyd-app:6800/.

My Airflow dag contains 5 tasks:
* print-projects: Prints the projects currently hosted on scrapyd. I do this for logging reasons.
* print-spiders: Prints the spiders currently hosted on scrapyd. I do this for logging reasons.
* schedule-job-task: Schedules a scrapyd job through a Post request which will receive the job ID as response. The job ID is sent to the next task as an XCom.
* check-job-status: This python task will extract the Job ID from the XCom, and monitor the job for 5 minutes. Either the job has ended before 5 minutes or it will trigger a shutdown of the job at the end of 5 minutes. 
* Trigger-transfromation: Bash task that cd into my transformation app and launches the processor.py script which triggers the transformation of the newly arrived files in GCP. Each raw file will be processed and transformed from JSON into a Parquet file with a strict schema. 

<p align="center">
  <img width="900" height="120" src="https://github.com/alexandergirardet/real_estate_analytics/blob/main/src/airflow_tasks.png">
</p>

An Xcom (short communication) is a mechanism to share small amount of information between tasks within a dag.

As you can see below I have successfully ran a full flow which takes on average 6-7 minutes. 

<p align="center">
  <img width="900" height="200" src="https://github.com/alexandergirardet/real_estate_analytics/blob/main/src/successful_run.png">
</p>

While my pipeline now works in a local environment there is still a lot of work to do done for this project to be production ready. I will integrate terraform into the project for my cloud infrastructure. Clean up the code and add comments where necessary. Move key files to more appropriate locations and add more security for passwords using environment variables. Create a CI/CD pipeline to run my app using Cloud Run, and allow for seamless updates to my code. Enable airflow and my scrapd-app to interact with a cloud hosted PostgreSQL instance. Once this is done I will launch the pipeline to run every 24 hours. From there I will begin working on integrating other data sources that I will model using a dimensional data model and transform with DBT. Once I am comfortable I will create the dashboard.

**[Project](https://github.com/alexandergirardet/real_estate_analytics/tree/main)**

**Content:** Estate Wise project

### Day 31

**Topic:** Continuous Integration and Continuous Deployment

Software development has come a long way since the traditional Waterfall model. The Waterfall approach is a linear, sequential approach to software development in which each phase of the development process must be completed before moving to the next phase. Although this approach has been widely used in the past, it has several limitations that have led to the development of new models such as Agile and DevOps.

The Agile model was developed as a response to the limitations of the Waterfall model. It focuses on quick feedback from clients and the development of prototypes. This is done by creating small actionable blocks called sprints that allow for immediate feedback from clients, which is then integrated into the next sprint. The entire process revolves around feedback loops, which allows for continuous improvement and faster delivery of software. Although the Agile model has several advantages, it still has its own limitations such as the lack of testing on production systems.

This limitation led to the development of the DevOps model, which aims to bring the development and operations teams into a single team. The goal of this model is to create software that is tested in a production environment, eliminating bugs and ensuring smooth deployment. The operations team provides feedback on the production environment, allowing the development team to create software that meets the needs of the end-users.

The DevOps model involves several processes such as planning, coding, building, testing, releasing, deploying, operating, and monitoring. These processes are carried out using tools such as Git, Maven, Selenium, Jenkins, Ansible, and Terraform. These tools allow for automation of the processes, which reduces the time taken to create and deliver software, reduces the complexity of maintaining an application, and improves collaboration between developers and operations teams.

The DevOps model also involves continuous delivery, continuous integration, and continuous deployment processes. Continuous delivery involves the plan, code, build, and test environment. Continuous integration involves testing the code to quickly identify any defects in the code. Continuous deployment involves pushing the code to production, where it will be deployed and monitored.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/Notes/devops.pdf)**

**Content:** CI/CD

### Day 32

**Topic:** Fundamentals of Data Engineering Chapter 4 Part 2

In the rapidly evolving world of data engineering, companies face an array of choices when it comes to cloud solutions, open source software, and proprietary technologies. This blog post delves into the key considerations that should inform your decision-making process, touching on topics such as hybrid and multicloud solutions, the pros and cons of monolithic versus modular systems, and the ongoing debate between serverless and server-based architectures.

As companies increasingly adopt cloud services, many choose to maintain certain workloads on-premises while moving others to the cloud, creating hybrid cloud environments. In some cases, data-intensive applications may benefit from a multicloud strategy, which entails deploying workloads to multiple public clouds to overcome network latency and bandwidth limitations.

However, managing multicloud solutions can be complex, and a new generation of "cloud of clouds" tools aims to reduce this complexity by offering services across clouds, seamlessly replicating data between them, or managing workloads from a single work pane. Solutions like Snowflake are part of this evolving trend, and it's crucial to keep an eye on such developments as they unfold.

When selecting a data engineering solution, it's essential to consider whether building and customizing a solution will provide a competitive advantage or if it's better to use existing solutions. This choice often boils down to the two types of data engineers:

Type A (Abstraction) engineer: Focuses on using off-the-shelf products and avoiding undifferentiated heavy lifting by keeping data architecture abstract and straightforward.
Type B (Build) engineer: Develops custom data tools and systems that scale and leverage a company's core competency and competitive advantage.

It's important to embrace abstraction and Type A behavior whenever possible. However, if a competitive advantage can be provided, lean towards Type B behavior.


When committing to open-source software (OSS) in a data engineering lifecycle, proper scrutiny is vital. OSS can be divided into two categories:

* Community-managed OSS: Success depends on a strong community and vibrant user base. Consider factors such as mindshare, maturity, troubleshooting, project management, team, community management, and roadmap.
* Commercial OSS (COSS): Addresses the drawbacks of hosting and maintaining OSS solutions by offering managed services, typically as cloud SaaS offerings (e.g., Databricks, Confluent, DBT labs). Evaluate factors like value, delivery model, support, releases, sales cycles, and community support.

The debate between monolithic and modular systems in software architecture continues to evolve. Monolithic systems are self-contained and favor simplicity, while modular systems lean towards decoupled, best-of-breed technologies performing tasks at which they are uniquely great.

Each approach has its advantages and disadvantages, and choosing the right one depends on your specific needs and goals. Data modularity enables teams to be agile and adopt new tools, but it comes with increased complexity and management overhead.

When deploying jobs, consider the pros and cons of serverless offerings versus managing your own servers. Serverless solutions enable pay-as-you-go consumption pricing models, while server-based approaches may offer more control and flexibility.

Containers play a significant role in both serverless and microservices, providing many benefits of virtualization without the overhead of carrying an entire operating system kernel. However, they do not provide the same security and isolation as full virtual machines (VMs).

**Content:** Fundamentals of Data Engineering

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DE_Fundamentals/Fundamentals_of_Data_engineering_Chapter_4.pdf)**

### Day 33

**Topic:** Fundamentals of Data Engineering Chapter 5 Part 1

As a Data Engineer, your primary role is to take data from source systems, process it, and make it helpful for serving downstream use cases. Before interacting with raw data, it's essential to understand where the data exists, how it's generated, and its characteristics and quirks. This blog post delves into data generation in source systems, providing an in-depth understanding of analog and digital data, various source systems, and the key concepts that Data Engineers should be familiar with.

As data proliferates, the expectation is that a data engineer's role will shift heavily towards understanding the interplay between data sources and destinations. The basic plumbing task of moving data from A to B will dramatically simplify. However, it will still be crucial to understand the nature of data as it's created in source systems.

Sources of Data: How is Data Created?
Data is an unorganized, context-less collection of facts and figures, created in many ways, both analog and digital.

Analog Data:
Analog data creation occurs in real-world interactions, often through speech or physical movement. It is represented by a continuous signal and is transient, meaning it cannot be easily replicated or reproduced as it is temporary and changes over time. Transient analog data is characterized by its variability, unpredictability, and sensitivity to environmental factors.

Digital Data:
Digital data is either created by converting analog data to digital form or is the native product of a digital system. Digital data is represented in a discrete form through 1s and 0s. It is more easily reproducible and more precisely replicated without loss of data.

A data engineer should be familiar with the source system and how its data is generated. You should put in the effort to read the source system's documentation and understand its patterns and quirks.

Source Systems: Main Ideas
Files and Unstructured Data
A file is a sequence of bytes, typically stored on a disk. Applications often write data to files, which may store local parameters, events, logs, images, and audio. Common file formats include Excel, CSV, TXT, JSON, and XML.

Application programming interfaces (APIs) are a standard way of exchanging data between systems. While an API should abstract away the complexity of dealing with source systems, they can still be complex.

An application database stores the state of an application. Typically, an application database is an online transaction processing (OLTP) system - a database that reads and writes individual data records at a high rate. OLTP systems are less suited to use cases driven by analytics at scale due to their row-based storage.

ACID (atomicity, consistency, isolation, durability) is a set of critical database characteristics that ensure the database maintains a consistent picture of the world, dramatically simplifying the app developer's task. Engineers must understand operating with and without ACID. Some distributed databases use relaxed consistency constraints, such as eventual consistency, to improve performance.

Atomic transactions ensure consistency and integrity of data within a database. Running analytical queries on an OLTP system is not scalable, so data engineers must understand the inner workings of OLTP systems and application backends to set up appropriate integrations with analytics systems without degrading production application performance.

An OLAP system is built to run large analytical queries and is typically inefficient at handling lookups of individual records.

Change Data Capture (CDC)
CDC is a method for extracting each change event (insert, update, delete) that occurs in a database. It is frequently leveraged to replicate between databases in near real-time or create an event stream for downstream processing. Relational databases often generate an event log stored on the database server that can be processed to create a stream, while NoSQL databases can send a log or event stream to a target storage location.

A log captures information about events that occur in systems. All logs track events and event metadata. They should capture who, what, and where. Log encoding can be in binary, semi-structured, or plain text format. Log resolution refers to the amount of event data captured in a log. Log latency refers to whether logs are processed in batch or real-time.

Database logs ensure the integrity and consistency of databases. Write-ahead logs, which are binary files, enable recoverability. The database server receives writes and update requests to a database table, storing each operation in the log before acknowledging the request.

CRUD (Create, Read, Update, and Delete) is a transactional pattern used in programming and represents the four basic operations of persistent storage.

The insert-only pattern retains history directly in a table containing data. Rather than updating records, new records get inserted with a timestamp indicating when they were created. A current state is made by looking at the most recent records based on ID.

In relation to event-driven architecture, you will likely face two terms: message queue and streaming platform. Though often used interchangeably, there is an essential difference between them.

A message is raw data communicated across two or more systems. A message is typically sent through a message queue from a publisher to a consumer, and once the message is delivered, it is removed from the queue. Messages are discrete and singular signals in an event-driven system.

A stream is an append-only log of event records. As events occur, they are accumulated in an ordered sequence, with a timestamp or an ID ordering events. Streams are used when you care about what happened over many events. Due to the append-only nature of streams, records in a stream are persisted over a long retention window.

When we view data as continuous and expect to consume it shortly after production, time becomes an essential consideration for all data ingestion. The key types of time are event time, ingestion time, and process time. Recording these various times in an automated way will enable more effective monitoring along your data workflows, allowing you to identify bottlenecks and optimize processes.

**Content:** Fundamentals of Data Engineering

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DE_Fundamentals/Fundamentals_of_Data_engineering_Chapter_4.pdf)**

### Day 34

**Topic:** Fundamentals of Data Engineering Chapter 5 Part 2

A data engineer should have a deep understanding of upstream source systems in which their pipelines depend on. These technologies will change over time, but there are key ideas that will remain the same. We start with Database Management Systems (DBMS).

A DBMS consists of several key components:

Storage Engine: Handles the organization and storage of data on disk, ensuring efficient retrieval and modification.
Query Optimizer: Responsible for analyzing queries and selecting the most efficient execution plan to optimize performance.
Disaster Recovery: Ensures the protection and recovery of data in case of failures or disasters.
Indexes and Lookups

Understanding the types of indexes your database uses and the best patterns for designing and managing them is essential. Common index types include B-trees and log-structured merge-trees (LSM). Efficient extraction of information is crucial for performance and resource utilization.

It's important to know the scaling strategy of a database, whether it scales with demand, and if it scales vertically or horizontally. Vertical scaling involves adding more resources to a single server, while horizontal scaling distributes the load across multiple servers.

Databases may be fully consistent or support relaxed consistency models, such as eventual consistency. Optional consistency modes for reads and writes, like strongly consistent reads, may also be available.

Relational databases store data in tables with rows and columns, and each row has the same schema. They are typically ACID compliant, ensuring data consistency, and are suitable for storing rapidly changing application states.

NoSQL databases prioritize performance, scalability, and schema flexibility over relational constraints. They often abandon strong consistency, joins, or fixed schema. Types of NoSQL databases include:

Key-Value: A simple and scalable type of NoSQL database that retrieves records using a unique key.
Document: Similar to key-value stores, but with support for nested objects, typically stored in a JSON-like format.
Wide-Column: Optimized for storing massive amounts of data with high transaction rates and extremely low latency.
Graph: Store data in a mathematical graph structure, suitable for analyzing connectivity between elements.
Search: Non-relational databases designed for searching complex and straightforward semantic and structural characteristics of data.
Time-Series: Optimized for retrieving and processing time-series data, often used in IoT and event-driven applications.
APIs

APIs, particularly those built around HTTP, are essential for data engineering. Key types of APIs include:

REST: Representational State Transfer, a stateless interaction model, where each call is independent and self-contained.
GraphQL: Allows more flexible and expressive queries than REST APIs, retrieving multiple data models in a single request.
Webhooks: Event-based data transmission patterns that enable real-time communication based on events.
RPC and gRPC: Remote procedure calls that allow running procedures on remote systems, abstracting away network complexity, and promoting efficient code writing.
By diving deeper into the characteristics and trade-offs of various database technologies and APIs, data engineers can make more informed decisions when designing and managing efficient, scalable systems. This knowledge lays the foundation for building robust data engineering solutions capable of adapting to the ever-evolving landscape of data-driven applications.

**Content:** Fundamentals of Data Engineering

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DE_Fundamentals/fundamentals_of_data_engineering_chapter_5.pdf)**


### Day 35

**Topic:** Fundamentals of Data Engineering Chapter 5 Part 3

Data sharing has become increasingly important in the modern data-driven world. With the advent of cloud data sharing, multitenant systems have emerged that support sharing data among tenants, allowing organizations to manage their data and share it selectively with other units. This facilitates data decentralization, which streamlines data pipelines within an organization. Additionally, data marketplaces have become centralized platforms for buying and selling data, further enabling collaboration and innovation.

Event-driven architectures are becoming more popular due to the rise of data apps, which integrate real-time analytics directly into applications. Message queues and event-streaming platforms are key components of such architectures, as they enable asynchronous communication between discrete systems, decoupling them from each other. Message queues support a publish and subscribe model, where data is published to a queue and delivered to one or more subscribers. Designing for out-of-order message delivery, scalability, and fault tolerance are critical aspects to consider when implementing message queues.

Event streaming platforms, on the other hand, ingest and process data in an ordered log of records. They retain data for a certain period, allowing for replaying messages from a past point in time. These platforms use topics, stream partitions, and fault tolerance mechanisms to ensure the robustness and scalability of the system. Data engineers should be mindful of potential issues like hotspotting when designing event streaming systems.

Collaboration with various stakeholders is crucial in data engineering. Systems stakeholders, such as software engineers and application developers, build and maintain the source systems, while data stakeholders own and control access to the data. Establishing data contracts and service level agreements with data providers can help set expectations and ensure data quality. Understanding data management practices in source systems, including data governance, data quality, and schema management, is also essential.

Security is a key concern in data engineering. Ensuring data is secure and encrypted in the source system, as well as during transfer and storage, is vital. Data engineers should also consider DataOps principles, like automation, observability, and incident response, to achieve operational excellence throughout the entire stack.

Finally, it's important to understand the upstream data architecture and how it impacts the data engineering process. This includes reliability, durability, availability, and the people involved. Data orchestration, which requires the correct network access, authentication, and authorization, plays a significant role in ensuring seamless access to source systems. Software engineering considerations, such as networking, access patterns, parallelization, and deployment, should not be overlooked.

**Content:** Fundamentals of Data Engineering

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DE_Fundamentals/fundamentals_of_data_engineering_chapter_5.pdf)**

### Day 36

**Topic:** Data engineering in GCP. Storage solutions

When it comes to data storage and management in Google Cloud Platform (GCP), there is a wide range of options to choose from. This blog post aims to provide an in-depth understanding of various data storage options in GCP, as well as key considerations and best practices for working with data.

Understanding Data Storage Options in GCP
To make an informed decision on where to store your data in GCP, it is essential to understand the key differences between various storage options:

Cloud Storage: Ideal for unstructured object storage. Provides regional, dual-region, or multi-region access with different storage classes such as standard, nearline, coldline, and archive.

Cloud BigTable: Petabyte-scale NoSQL database designed for wide column high write volume data like time-series, transactional, or IoT data.

BigQuery: Petabyte-scale analytics data warehouse that supports fast SQL queries across large datasets.

Cloud Spanner: Global SQL-based relational database offering horizontal scalability, high availability, and strong consistency.

Cloud SQL: Managed MySQL and PostgreSQL instances with built-in backups, replicas, and failover. It is vertically scalable.

Firestore: Fully-managed NoSQL document database with large collections of small JSON documents, realtime database functionality, and strong consistency.

Cloud Memorystore: Managed Redis instances used as an in-memory DB, cache, or message broker. Provides built-in high availability and is vertically scalable.

Key Considerations for Managing Data
When working with data in GCP, it is essential to consider:

Sources and sinks: Ensure the data source format is appropriate for the data sink and whether any preparation work is required.
Structured and unstructured data: Determine how data will be processed and stored, ensuring structured data conforms to the correct model.
Batched and streaming: Identify if pipelines are required for data ingestion and if latency and time-windowing are a concern.
Data Modelling
Structured data requires a consistent model that may involve data preparation or transformation. The stages of data modeling include:

Conceptual: Identify entities, their attributes, and relationships in the data.
Logical: Determine the structure of entities and if the model can be normalized.
Physical: Implement the database by defining keys and indexes.
Cloud Storage Features
Cloud Storage offers fully managed object storage for unstructured data with multiple storage classes and life cycle management. It provides secure and durable storage, with objects being stored as opaque data. Access to Google Cloud Storage can be achieved through the HTTP API, GCP console, SDKs, or gsutil.

Service Accounts and Access Control
Identity & Access management in GCP is controlled by policies containing members and roles. Service accounts are specific accounts created for specific tasks, and their identities can be assumed by applications or workloads. Access control can be managed through IAM for bulk access to buckets and ACLs for granular access.

Data Transfer Services
GCP offers various data transfer services, including:

Cloud Storage Transfer Service: Automates the transfer of data from sources like AWS S3 or HTTP to Google Cloud Storage.
BigQuery Data Transfer Service: Automates data transfer to BigQuery from sources like Cloud Storage, YouTube, or S3.
Transfer Appliance: A physical rackable storage device for transferring large amounts of data to GCP.
Cloud SQL Features and High Availability
Cloud SQL offers managed SQL instances with multiple database engines, scalability, and availability. It provides automated backups, instance restores, and point-in-time recovery. High availability can be achieved through regional and zonal replication.

Composite Index: A composite index is an index that consists of two or more columns in a database table. These indexes are useful when you need to search or sort data based on multiple columns. Composite indexes can improve query performance by allowing the database engine to scan fewer rows when processing a query.

Cloud Memorystore is a managed Redis and Memcached service that provides a fully managed in-memory data store service built on Google Cloud Platform. It's designed for use cases that require low latency and high throughput, such as caching, real-time analytics, and gaming leaderboards.

Key features of Cloud Memorystore:
Fully managed Redis instances
Automatically handles patching, updates, and backups
In-memory database
Provides fast access to data by storing it in memory instead of disk
Cache or message broker
Can be used as a cache for frequently accessed data or as a message broker for pub/sub messaging
Built-in high availability
Supports replication across multiple zones for high availability
Vertically scalable
Allows for easy scaling of memory and network bandwidth
Use cases for Cloud Memorystore:
Caching
Store frequently accessed data in memory to reduce latency and improve application performance
Real-time analytics
Perform fast, in-memory computations on large datasets for real-time analytics and insights
Gaming leaderboards
Maintain and update gaming leaderboards with low latency and high throughput

**Content:** Cloud Guru Professional Data Engineer

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/Data_engineering_bootcamp/storage_and_databases.pdf)**

### Day 37

**Topic:** Data engineering in GCP. Big Data Ecosystem

MapReduce is a programming model and a distributed implementation of that model, created at Google to address the challenge of processing massive jobs across data centers over many machines. By abstracting away the distributed systems management work, MapReduce provides a standardized framework for designing solutions for data processing problems. The model handles the parallelization and execution of tasks across several machines, taking care of partitioning, scheduling, fault tolerance, networking, and storage behind the scenes. MapReduce jobs are split into small chunks, using a master and worker cluster model, with failed worker jobs being reassigned and output files partitioned.

At a high level, the map function takes an input and produces a set of intermediate key/value pairs, while the reduce function merges intermediate values associated with the same intermediate key, forming a smaller set of values. MapReduce is executed over three stages: Map, Shuffle, and Reduce. The map phase does not require communication across machines to be completed, while the shuffle stage sorts the keys so that computers handling the reduce stage get the same keys. Finally, the reduce stage combines the results together.

Hadoop is an open source file processing and distributed storage system, providing HDFS (Hadoop Distributed File System) as a distributed file system that allows for the storage of large datasets across a cluster of commodity hardware. HDFS is designed to handle large files and is fault-tolerant, replicating data across multiple nodes in the cluster to ensure availability in the event of hardware failures. Hadoop also provides MapReduce as a programming model and processing framework that allows for the parallel processing of data stored in HDFS. Additionally, Hadoop offers a variety of other tools and technologies, such as Spark, Hive, Pig, and HBase, that extend its capabilities and make it more flexible and powerful.

Apache Spark was developed to address the limitations of MapReduce implemented through the Hadoop framework, such as its linear dataflow, which made it difficult to run complex calculations. Designed as a general-purpose cluster-computing framework, Spark allows for concurrent computational jobs to be run across massive datasets, using the concept of resilient distributed data multisets that can be accessed as a form of distributed shared memory. Spark supports multiple programming languages, including Python, Java, Scala, and R, and requires a cluster manager and a storage system to function.

Apache Kafka is a distributed streaming platform that allows for the publication and subscription to streams of records, acting like a message bus for data with high throughput and low latency. Kafka APIs include Producer, Consumer, Streams, and Connector, providing various functions for publishing, subscribing, processing, and connecting to external systems. Kafka's architecture consists of brokers, which manage partitions and store data locally on their disks, and Zookeeper ensembles, which manage consensus across brokers and handle failure management. Topics in Kafka are a collection of related messages or events, which can be partitioned and allocated across several brokers for proper scaling.

**Content:** Cloud Guru Professional Data Engineer

**[Notes](https://github.com/alexandergirardet/Book_Summaries/tree/main/Notes/Data_engineering_bootcamp)**

### Day 38

**Topic:** Data engineering in GCP. Pub/Sub

Pub/Sub is a powerful messaging system that facilitates communication between components in a distributed system. At its core, a message bus acts as a common communication platform, allowing for unified communication protocols and prioritization. This can be beneficial, as it provides a single interface for communication and simplifies the process of controlling and managing messages. However, it can also introduce potential bottlenecks or single points of failure, as well as potential security issues.

Messaging middleware, such as the Pub/Sub system, serves as a messaging layer between components, ensuring data resilience and reducing dependency between components. This creates loosely coupled and resilient systems, acting as a shock absorber for any unexpected disruptions.

Cloud Pub/Sub is a fully-managed, serverless messaging service that supports multiple publisher and subscriber patterns, at-least-once delivery, and both real-time and batch processing. It integrates seamlessly with other Google Cloud services, such as Cloud Dataflow. Common use cases for Cloud Pub/Sub include distributing workloads, asynchronous workflows, event notifications, distributed logging, and device data streaming.

Pub/Sub supports several messaging patterns, such as one-to-one, one-to-many, and many-to-many. To publish messages, you simply create a message containing your data, send a request to the Pub/Sub API, and specify the topic. To receive messages, create a subscription to a topic, with pull being the default delivery method. Messages must be acknowledged; otherwise, they remain at the top of the queue. Alternatively, you can use push to send messages to an HTTPS endpoint with a valid SSL certificate.

Cloud Pub/Sub offers various integration options, including client libraries, Cloud Dataflow, Cloud Functions, Cloud Run, and Cloud IoT Core. For development purposes, you can also use a local Pub/Sub emulator.

In terms of advanced features, Pub/Sub guarantees at-least-once delivery of each message for every subscription, and undelivered messages are deleted after a specified retention duration. Subscriptions expire after 31 days of inactivity, and new subscriptions with the same name have no relationship to previous subscriptions. Pub/Sub also allows you to seek and retain acknowledged messages for up to 7 days, and create snapshots for easier code deployment.

Although Pub/Sub does not guarantee message ordering, you can use timestamps to ensure the correct order when it matters. For transactional ordering, consider alternative solutions. Pub/Sub stores messages in the nearest region, and you can control this using message storage policies. Keep in mind that this can lead to additional egress fees.

Monitoring is essential for a healthy Pub/Sub system. Key metrics include total utilization in bytes, subscription utilization in bytes, and undelivered messages belonging to a subscription. Access control is equally important, and you can use service accounts for authorization and grant per-topic or per-subscription permissions. Always follow the security principle of least privilege.

**Content:** Cloud Guru Professional Data Engineer

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/Data_engineering_bootcamp/pub%3Asub.pdf)**

### Day 39

**Topic:** Raw ingredients of storage. Fundamentals of DE Chapter 6 Part 1

As data gets stored multiple times in the Data Engineering lifecycle, it is important to understand the use cases and particularities of available storage solutions in choosing your data architecture. To understand data storage solutions, we will focus on the raw ingredients of storage, which are the lower levels of abstraction that persist across different use cases and solutions. These raw ingredients include HDD, SSD, RAM, Networking, Serialization, Compression, and CPU.

HDDs (Hard Disk Drives) are traditional storage devices that use spinning platters and magnetic heads for reading and writing data. They are cost-effective and offer large storage capacities. However, HDDs have physical limitations, such as slower transfer speeds and seek times, which make them less suitable for use cases requiring low latency and high IOPS (Input/Output Operations Per Second).

On the other hand, SSDs (Solid State Drives) store data in flash memory cells without any moving parts, which allows them to achieve faster transfer speeds and IOPS. While SSDs are more expensive than HDDs, they are popular for OLTP (Online Transaction Processing) systems that require high IOPS.

RAM (Random Access Memory) is volatile memory, meaning it does not store data persistently. It is used in conjunction with CPUs for executing programs and processing data. RAM offers significantly higher transfer speeds and faster retrieval times than SSD storage but is much more expensive. Data engineers need to consider the bandwidth and retrieval latency of RAM when designing storage systems.

In distributed data storage systems, networking and CPUs play a critical role in servicing requests, aggregating reads, and distributing writes. Data engineers must understand how networking affects the systems they build and use, balancing durability and availability against performance and cost benefits.

Serialization is the process of converting data into a standard format suitable for storage or transmission. Data engineers must choose serialization formats and standards that balance interoperability with performance considerations.

Compression reduces the size of data, which can lead to cost savings and improved performance. However, compression algorithms interact with other aspects of storage systems in complex ways, and compressing and decompressing data entails extra time and resource consumption.

Caching involves storing frequently or recently accessed data in a fast-access layer to improve performance. The faster the cache, the higher the cost and the less storage space available. Caches are critical for data serving, processing, and transformation. Archive storage, on the other hand, provides inferior access characteristics at lower costs, making it suitable for long-term storage of infrequently accessed data.

**Content:** Fundamentals of Data Engineering

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DE_Fundamentals/fundamentals_of_DE_chapter_6.pdf)**

### Day 40

**Topic:** Data Storage systems. Fundamentals of DE Chapter 6 Part 2

Data storage systems are the abstraction level above raw storage ingredients, such as magnetic disks. As data storage and access patterns become more complex, distributed storage is necessary. Distributed storage involves storing data on multiple servers, enabling redundancy, scalability, and faster processing. Data engineers must be aware of the consistency paradigms in distributed systems and make decisions regarding consistency at the database technology level, the configuration parameters for the database, and at the individual query level.

Data consistency refers to the concept of data reflecting the true state of the objects or entities it represents. In distributed systems, where data is partitioned or replicated across servers located in different geographic areas, consistency becomes a challenge. There are two main consistency patterns: ACID and BASE. ACID transactions ensure strong consistency, while BASE transactions prioritize availability and partition tolerance over strict consistency.

Eventual consistency is a consistency paradigm that allows data to be temporarily inconsistent across nodes over time, eventually bringing the data into a consistent state. Partition tolerance is the ability of a distributed system to continue operating in the case of a network outage or failure that prevents communication between nodes. On the other hand, strong consistency ensures that any reads against the database return consistent values, at the expense of higher latency.

Storage formatting is a way of storing data on disk in a way that allows easy access. There are three types of storage formatting: file storage, block storage, and object storage. File storage organizes files into a directory tree, while block storage is the raw storage provided by SSDs and HDDs. Object storage is similar to file storage, but with key differences.

File storage systems can be found on local disk partitions, network-attached storage (NAS) systems, or cloud file system services. Local disk storage supports full read-after-write consistency, while NAS systems provide a centralized and shared storage space for files. Cloud file system services, such as Amazon Elastic File System (EFS), offer a fully managed file system for use with multiple cloud VMs and applications.

Block storage is used in transactional databases and as the default option for OS boot disks on cloud VMs. Redundant arrays of independent disks (RAID) parallelize storage on a single server, increasing redundancy and performance. Storage access networks (SAN) provide virtualized block storage devices over a network, typically from a storage pool, allowing for enhanced performance, availability, and durability.

Cloud virtualized block storage solutions, such as Amazon Elastic Block Store (EBS), offer similar benefits to SAN but abstract away the complexity of SAN clusters and networking details. EBS stores data separately from the instance host server but in the same zone, supporting high performance and low latency. EBS is suitable for use cases such as databases where data persistence is important.

Cloud providers offer block storage volumes that are physically attached to the host server running a VM. These storage volumes are generally low cost and included with the price of the VM. Local instance volumes are useful for ephemeral jobs, such as consuming data from S3, processing it locally, and storing it back in S3.

**Content:** Fundamentals of Data Engineering

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DE_Fundamentals/fundamentals_of_DE_chapter_6.pdf)**

### Day 41

**Topic:** Data Storage systems. Fundamentals of DE Chapter 6 Part 3

Cloud virtualized block storage, such as Elastic Block Store (EBS), offers engineers an alternative to traditional Storage Area Network (SAN) clusters by managing the storage separately from the instance host server while maintaining high performance and low latency. EBS ensures data persistence, making it suitable for use cases like databases that require data to be stored even when an EC2 instance shuts down or fails.

EBS performance metrics include Input/Output Operations Per Second (IOPS) and throughput. It replicates data across at least two separate host machines, protecting data from disk failures, and allows point-in-time snapshots while the drive is in use.

Local instance volumes offered by cloud providers are physically attached to the host server running a virtual machine (VM). They are low-cost and included with the price of the VM but lack the advanced virtualization features of EBS. However, they are useful as a local cache for ephemeral jobs, such as consuming data from S3, processing it locally, and storing it back in S3. It is essential to plan for worst-case scenarios, such as local disk failure or VM shutdown, when considering local storage.

Object storage has become increasingly important, with services like Amazon S3 and Google Cloud Storage (GCS) widely used. It is a key-value store for immutable data objects and does not support append operations or random writes. Instead, objects are written as a stream of bytes, and once written, the data is immutable. This makes object storage suitable for serving high volume web traffic or delivering data to highly parallel distributed query engines.

Cloud object storage plays a crucial role in separating compute and storage, allowing engineers to process data with ephemeral clusters and scale these clusters up and down on demand. This provides virtually limitless storage, as data is only limited by the number of disks in cloud environments.

Object stores are ideal repositories for unstructured data in any format, including raw text, images, videos, and audio, and can be used in machine learning pipelines. However, they do not handle update operations as well as transactional databases.

Cloud vendors offer various storage classes and tiers, with some offering discounted storage pricing in exchange for reduced access or durability. Additionally, object store synchronization solutions like s3fs and Amazon S3 File Gateway have become popular, allowing users to mount an S3 bucket as local storage.

Cache and memory-based storage systems, such as Memcached and Redis, offer low-latency results and reduce load on backend systems. These systems are designed for caching database query results, API call responses, and more.

The Hadoop Distributed File System (HDFS) is similar to object storage but with a key difference: compute and storage are on the same node. It is still used in legacy systems and sometimes with Spark clusters.

Streaming storage systems, like Kafka, have different requirements compared to non-streaming data storage. They are designed for temporal data storage and support replay, allowing a range of historical stored data to be returned.

Indexes, partitioning, and clustering are important concepts in data storage. Indexes allow for fast lookup of individual records, while partitions and clustering allow for faster scan speeds by reducing the amount of data that needs to be scanned. Columnar serialization in databases enables scans on only the required data for a particular query, further improving performance.

**Content:** Fundamentals of Data Engineering

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/DE_Fundamentals/fundamentals_of_DE_chapter_6.pdf)**

### Day 42

**Topic:** Data engineering in GCP. Dataflow

Dataflow is a powerful ETL (Extract, Transform, Load) tool used to transform data, providing a fully managed and serverless experience. It leverages the open-source Apache Beam SDK and supports both real-time and batch processing, seamlessly handling autoscaling of worker resources. Each Dataflow pipeline has a source and a sink, where data is ingested from and output to, respectively.

The driver program, written in either Python or Java, defines the full set of transformations the data undergoes from ingestion to final output. This program is submitted to the runner, which manages the execution of the pipeline and translates it for the back-end. Dataflow represents both the driver program and the runner.

PCollections (short for Parallel Collections) are used to represent data as it is transformed in the pipeline. A PCollection is a potentially distributed multi-element dataset that can represent both batch and streaming data. It is created from an external data source and used as input for transforms, which output new PCollections. Multiple transforms are combined to define the pipeline.

When designing a pipeline, it is essential to understand the necessary transformations, the location of data, and the input and output data structures and formats. Pipelines can be structured as linear, branching, or merging, and they can have multiple sources. Each Dataflow pipeline represents a Directed Acyclic Graph (DAG), a graph with a finite number of vertices and edges with no directed cycles.

Creating a Dataflow pipeline involves creating a pipeline object, creating a PCollection using a read or create transform, applying multiple transforms as required, writing out the final PCollection to the pipeline sink, and executing the pipeline using a pipeline runner.

Dataflow pipeline concepts include ParDo, a transform for generic parallel processing, and aggregation, where user-defined functions can be applied. PCollection elements must be of the same type, and they are immutable and unchanging. Each element of a PCollection is associated with a timestamp.

Apache Beam's core transforms include ParDo, GroupByKey, CoGroupByKey, Combine, Flatten, and Partition. Advanced Dataflow concepts include event time, window types, watermarks, and triggers. Event time is the time at which a data element occurs, while window types include fixed time windows, sliding windows, per-session windows, and single global windows.

In terms of security and access, Dataflow pipelines can be run locally for testing or using the Cloud Dataflow managed service. Google Cloud Platform (GCP) service accounts are used for the Cloud Dataflow service and worker instances. Access and security mechanisms include submission of the pipeline, evaluation of the pipeline, and accessing telemetry or metrics. Dataflow also supports regional endpoints and machine learning integration.

Cloud Dataflow SQL allows users to develop and run Cloud Dataflow jobs from the BigQuery web UI. It integrates with Apache Beam SQL, with Cloud Dataflow SQL being the GCP version of Apache Beam SQL. This integration facilitates the development of complex data processing pipelines while leveraging the powerful capabilities of Dataflow.

**Content:** Cloud Guru Professional Data Engineer

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Notes/Data_engineering_bootcamp/dataflow.pdf)**
