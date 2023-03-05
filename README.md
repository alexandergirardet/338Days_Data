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
* Writing articles

I recognize that working a full-time job will make this challenge more difficult, but it also provides me with the added benefit of being immersed in the world of tech and surrounded by those who are more proficient in these areas, from whom I can learn. I plan to use the techniques and tools outlined by Tiago Forte's [Building a Second Brain](https://github.com/alexandergirardet/Book_Summaries/blob/main/Books/Building_a_Second_Brain.pdf) for my time management, note-taking, and information organization strategy to help me stay on track.

## Outline
This will be subject to change.

### Books

Books  | Status of Completion
------------- | -------------
Mathematics for Machine Learning  |
Mathematics for the non-mathematician  | :construction:
Hands On Machine Learning with Scikit Learn, Keras and TensorFlow | 
Speech and Language Processing | 
Designing Data-Intensive Applications | :construction:
Machine Learning Engineering | 
Fundamentals of Data Engineering | :construction:

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

### Research Papers

Paper  | #
------------- | -------------
Paper Name | 1

### Articles

Article  | # 
------------- | -------------
How I passed the Associate Cloud Engineer Exam | 


# Journal

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

