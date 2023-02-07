# 338Days_Data
This is my 338 day learning journey in AI, Maths, and Data Engineering.

## Acknowledgments
To my Grandfather Frank Hieber who serves as an inspiration in my life, always promoting acquiring knowledge through self education. 

## Motivation
Being freed from the constraints of formal education allowed me to explore my own learning style and interests. Despite not having a background in STEM, during the first COVID-19 lockdown, I discovered my passion for coding and data science. I have since been working as a data engineer, which has solidified my desire to pursue a career in this industry. The emergence of innovative technologies like ChatGPT has only increased my motivation to dive deeper into the field of AI. The 338 day data challenge serves as an opportunity for me to continue to grow and improve my skills in a field that I am passionate about. This challenge is a personal milestone that I am eager to achieve through determination and hard work.


## Strategy
My goal is to become proficient in data engineering, machine learning engineering, and to leverage my finance and business background to gain a deeper understanding of creating and managing data-driven organizations.

To accomplish this goal, the challenge will consist of several feats including:

* Reading and summarizing 11 books (1 per month)
* Completing 4 projects (1 per quarter)
* Participating in 2 bootcamps
* 3 Certificates
* Reading and summarizing 48 research papers (1 per week)
* Writing 48 articles (1 per week)

I recognize that working a full-time job will make this challenge more difficult, but it also provides me with the added benefit of being immersed in the world of tech and surrounded by those who are more proficient in these areas, from whom I can learn. I plan to use the techniques and tools outlined by Tiago Forte's [Building a Second Brain](https://github.com/alexandergirardet/Book_Summaries/blob/main/Building_a_Second_Brain.pdf) for my time management, note-taking, and information organization strategy to help me stay on track.

## Outline
This will be subject to change.

### Books

Books  | Status of Completion
------------- | -------------
Mathematics for Machine Learning  | :construction:
Hands On Machine Learning with Scikit Learn, Keras and TensorFlow | 
Speech and Language Processing | 
Designing Data-Intensive Applications | :construction:
Machine Learning Engineering | 

### Projects

Books  | Field | Status of Completion
------------- | ------------- | -------------
UK Real Estate Dashboard  | Data Engineering | :construction:
Finance NLP analyst  | NLP and ML Engineering | 

### Certificates
  
Certificate  | Status of Completion | Proof
------------- | ------------- | -------------
Google Associate Cloud Engineer  | :white_check_mark: | 
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
Article Name  | 1


# Journal

### Day 1
I have started this journey by trying to develop my mathematical thinking. I recently completed the first week of lectures and assignments from Stanford's Mathematical Thinking course on Coursera. Through this course, I learned that a major challenge for math practitioners is the shift from a focus on doing to a focus on understanding. The first week of the course covered introductory material, but it provided valuable insights into the historical purpose of mathematics. Originally, mathematics was used primarily for practical purposes such as financial management, but it has evolved to become more abstract and is now used to develop models that use mathematical notation to represent relationships and patterns in everyday life. The purpose of the Mathematical Thinking course is to move away from the ability to simply apply pre-defined functions and theorems and instead understand the mathematical concepts and principles behind them. This approach will allow the individual to generalize and solve similar problems in the future. According to the instructor, individuals who possess this ability to think outside of the mathematical box and apply mathematical thinking to new problems are considered innovative mathematical thinkers. These individuals will be best suited to keep up with the ever-changing demands of industry.

**Content:** Mathematical Thinking Stanford Course

### Day 2
Designing Data-Intensive Applications or DDIA by Martin Kleppmann provides a comprehensive overview of modern data systems and the various trade-offs involved in their design. It covers topics such as data modelling, storage, processing, and security, and provides practical advice on how to build scalable, reliable, and maintainable data-intensive applications. The book was highly recommended to me by senior data engineers and architects, as it would deepen my understanding of data systems and designing robust data-driven applications. Today I studied for my Associate Cloud Engineer exam which is in 4 days and took notes on the first chapter of DDIA. Reliability, maintainability, and scalability are the three most important concerns in designing data-intensive software applications. Reliability means making systems work correctly, even when faults occur. Fault-tolerance techniques can hide certain types of faults from the end user. The primary techniques mentioned are: decoupling development features from production usage, where engineers can explore the data without impacting live systems. Thorough testing, including unit tests, whole integration tests, and end-to-end testing. As well as setting up detailed and clear monitoring which can provide early warning systems to check whether our assumptions are validated. Scalability refers to having strategies in place to preserve performance when keeping up with large increases in load. An architecture which is scalable requires an understanding of which operations will be common and which will be rare. Finally, maintainability is about making life better for the engineering and operations teams who work with the system. Good abstraction would involve reducing the complexity of the system, making it easier to modify and adapt. There are three design principles for ensuring maintainability. Operability makes it easier for teams to keep the system running smoothly. Simplicity makes it easier for new engineers to understand the system as a lot of the complexity has been abstracted away. And, evolvability, makes it easier for the engineers to make changes to the system in the future. 

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Chapter_1_-_Design_Scalable_systems.pdf)**

**Content:** Designing Data-Intensive Applications and Cloud Guru Google Certified Associate Cloud Engineer course

### Day 3
Today's content focused on chapter 2 of DDIA and the Cloud Guru Google Certified ACE course. I learned about data models and networking architecture in google cloud solutions. A short summary of chapter 2 regarding data models. Data models are important in developing software as they impact how the software is written and how problems are solved. Most applications are built on a hierarchy of data models with each layer hiding the complexity of the layer below it by providing a clean data model. There are 3 main general-purpose data models for storage and querying: relational, document and graph-based. The relational model is the most well-known and data is organized into tables and relationships. But there is an "impedance mismatch" between relational data models and object-oriented applications, leading to a disconnect between the models. The document model is hierarchical and similar to JSON and reduces impedance mismatch, but provides less support for joins. The schema-on-read approach is advantageous if item structures are not homogeneous. Both relational and document models are becoming more similar over time.


**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Chapter_2_-_Design_Scalable_systems.pdf)**

**Content:** Designing Data-Intensive Applications and Cloud Guru Google Certified Associate Cloud Engineer course

### Day 4
With my goal of gaining the GCP professional data engineer certificate and professional machine learning engineer certificate it is important that I can test and prove my knowledge of leveraging cloud solutions before moving on to the more specialized certifications. The Associate Cloud Engineer exam assesses your ability to deploy applications, monitor services and manage enterprise services. I have given myself a week to study for the exam. Google cloud platform provides Software as a Service, Infrastructure as a Service and Functions as a Service, it is crucial when working with cloud solutions to understand networking concepts for deploying applications. Networking refers to the infrastructure and systems that enable communication between different devices. Understandly a large cloud solution will need to communicate with Google's physical cloud infrastructure securely, and effectively in providing scalable, reliable, and maintainable data-intensive applications. Within Google cloud there are three layers to networking: VPCs, Subnets, and Routers. For the sake of this explanation I will use some analogies but my notes go more in depth. A VPC or virtual private cloud can be thought of as a neighborhood where you can control who gets access to your neighborhood. It is a bit of an authoritarian neighborhood so it can decide who can communicate with eachother and who can communicate with the outside world (as with all authoritarian regimes they say it is for your own safety. In this case it actually is). A subnet can be thought of as a house within the neighborhood, these are where certain resources (think furniture in analogy terms) are logically grouped together based on their shared needs. Again this would be for security reasons, some houses may have more expensive furniture which would need stricter access rules. Routers who can be thought of as traffic directors, they know where all resources are placed and forwards traffic in the neighborhood where it needs to go. Finally these leaves us with the concept of a firewall who can be thought of as bouncers. These bouncers will be stationed outside each house, but also outside the neighborhood. They decided based on the rules you give them, who is allowed access to the places the traffic intends to be. 

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Associate_Cloud_Engineer.pdf)**

**Content:** Cloud Guru Google Certified Associate Cloud Engineer course

### Day 5
To understand Kubernetes you have to first understand the rise of Agile software practices and the shift from monolithic architecture to microservices. In the previous years when apps were less complex, having all the functionality closely coupled together was not a major problem, as the code bases were relatively light and easy to deploy, this is referred to as monolithic architecture. Today, as apps become much more complex, integrating features such as chatbots, user validation, and large scale databases, the ability to continuously update a large singular code base, test it and redeploy it is no longer viable. Therefore in line with developing faster software practices which are more flexible, agile and true to the core principles of maintainability, reliability and scalability, the microservice architecture become prominent. Today features of an app are broken down into smaller independent components which are loosely coupled and therefore can be scaled, redeployed and updated without impacting the availability of other features. This is possible due to containerization which allows you to deploy code along with it's environments configurations and dependencies, allowing features to run as standalone apps. Kubernetes offers a solution to the problem of managing the deployment, and management of these many containers which when combined together form the basis of the application. There are two main concepts in a cluster, the master node and the worker node. The master node contains the API which allows the developer to communicate with the cluster, and update the clusters nodes. The master node or the control plane, also controls storing the state of the cluster, scheduling and managing the worker nodes. The worker nodes contains pods, which as logical units containing the docker images that hold the functionality of the individual components.

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Kubernetes.pdf)**

**Content:** Cloud Guru Google Certified Associate Cloud Engineer course and Kubernetes

### Day 6

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

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Chapter_3_-_Design_scalable_systems.pdf)**

**Content:** Designing Data-Intensive Applications

### Day 7

**Topic:** Docker

As I began working through the Data Engineering Zoomcamp the first topic to come up is Docker and it's use in developing, testing and deploying apps or pipelines. Docker aims to solve the problem of Portability in creating software applications. It enables developers to create, deploy and run applications in standardized and isolated environments. This makes it easier to develop, test, and deploy applications across different environments, ensuring compatibility and consistency of results. The main components of Docker are Docker Client, Docker Daemon, Docker Registry, Docker Engine, Docker Images, and Docker Containers. The Docker Client is the CLI that allows users to interact with the Docker Daemon, build images, and run and manage containers. The Docker Daemon is the core component of the architecture that runs on the host machine, responsible for building images, running containers and managing them. The Docker Registry is where images are stored and can be retrieved by the Docker Client. There are public and private registries such as Docker Hub and Google Container Registry. The Docker Engine is the software that runs on the host machine and provides an interface between the Docker Daemon and the client. The Docker Images are the building blocks of containers and include everything needed to run an application, including code, runtime, system tools, libraries and settings. The Docker Containers are instances of Docker Images that run as isolated processes on the host machine, each with their own file system, networking and resources. In today's course I have created several docker containers that share a network and can communicate with eachother, leading me to the concept of docker compose files. Docker compose files are useful in creating multi-container applications. For example, one container can run a postgres database while another can run PgAdmin (a GUI for managing docker containers). These containers can use the shared network to communicate with eachother so that I can simultaneously interact with the database and monitor it using PgAdmin. 

**[Notes](https://github.com/alexandergirardet/Book_Summaries/blob/main/Docker.pdf)**

**Content:** Data Engineering Zoomcamp



