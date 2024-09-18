# Introduction and Key Terms
This class will cover several related topics:
- Big Data: dealing with data too big to fit on one computer
- Analytics: extracting meaningful information
- Machine Learning: techniques to help when unsure how to use analytics
- Cloud Computing: how to harness multiple computers

# Big Data

- Data that cannot be stored on one computer
    - Have to distribute among multiple computers
    - Have to process using distributed algorithms
    - Can apply big data techniques to small data, but not other way around

## Structured vs Unstructured Data
- Structured data:
    - Clearly defined data types, stored in predefined order
    - Explicitly linked
    - Easily sortable and maintainable
- Unstructured data:
    - Conglomerate of varied data types
    - No explicit links
    - Harder to collect, process, analyze

## Data Warehouse, Data Lake
- Database: Files and programs that hold data for one pearticular set or collection.
- A Data Warehouse is a central repository holding one or more databases.
> Some consider a data warehouse to hold structured data, and a data lake to hold unstructured data.

## Accessing Databases
- Given a database, there are four basic tasks that can be performed:
    - **Query:** Copy some data (*search, fetch, get, read, retrieve*)
    - **Insert:** Add new data to the database (*add, post, store, write, create*)
    - **Update:** Change existing data. (*put, replace, change, modify*)
    - **Delete:** Remove some data.
- Databases do not necessarily implement all four
- Databases usually sit outside of an application
    - has management software that implememts the file access
    - application sends commands to management software
- The industry standard API for interacting with structured database is Structured Query Language (SQL)

## Data Quality
- Not all data is useful; some data is just noise
- Data Quality is a measure of suitability for a particular use, using four criteria:
    - **Accuracy:** correctly represents real wold values
    - **Completeness:** the degree to which all values are filled or represented
    - **Consistency:** the degree to which similar or relateed data values align
    - **Conformity:** the degree to which the data values align with business goals

## Data Cleansing
- Data cleansing can improve the quality of a low quality data set eg.
    - elimination of duplicates
    - remove missing, NULL, NaN
    - converting values to more useful formats

# Analytics
- Once we have the vast amount of data we use:
    - Data Science: analytic techniques to extract valuable information frmo data for decision making and strategic planning
    - Data Mining: The process of identifying patterns that exist within large sets of data
- Big Data, Analytics, and Machine Learning are for **business intelligence** which convert data to actionable insights and recommendations
- How we examine data:
    - Descriptive analytics (what happened)
    - Diagnostic analytics (why did it happen)
    - Predictive analytics (what is likely to happen)
- Some types of analytics:
    - Regression: curve fitting
    - Data Clustering: grouping related data set items
    - Data Classification: assigning data to groups or categories
    - process of identifying key relationships between variables

# Machine Learning
- Using various types of programs to find various patterns in data
- Using programming techniques to mimic some of the ways a human brain works

## Artificial Intelligence
- The ability of machines to mimic the capabilities of the human mind, such as:
    - learning from examples/experience
    - recognizing objects
    - "understanding" and responding to language
    - making decisions
    - solving problems

## Machine Learning
- Subset of AI that provides the ability to automatically learn and improve form experience without being explicitly programmed
- Two basic forms
    - Supervised: Examine training data set to learn to identify patterns
    - Unsupervised: Does not use a training set

## Deep Learning
- Subset of ML, based on artificial neural networks (inspired by human brain)
- learns from vast amount of data, and is good at finding patterns in unstructure data

## Augmented Intelligence
- Refers to human-centered partnership that brings people and AI together to enhance cognitive performance

# Cloud Computing
- The delivery of IT services on-demand over shared networked computing resources
- Computing has become a utility, companies can purchase data from storage providers or computational power from computation providers

## Public Cloud
- A cloud infrastructure system hosted by a cloud service provider
    - Can be accessed by anyone with an internet connection

## Private/Hybrid Clouds
- Private Cloud: used by multiple users within a single entity
    - Can be located on site, off-site by a third party, or both
- Hybrid Cloud: combination of both public and private clouds

## Internal Cloud
- offered by an internal IT department, strictly for in-house use

## External Cloud
- fees are usually charged, and offers customization for clients needs (can be public or private)

## More Clouds
- Personal Cloud: Network attached storage, (pc connected to network solely to store data)
- Consumer Cloud: cloud offers for personal use (eg. DropBox)
- Vertical Cloud: built to serve the needs of several specific industries

## Virtual Machines
- Software that emulates a computer
    - host OS -> hypervisor (virtual hardware) -> guest OS 

## Cloud Services
- Backend-as-a-Service: cloud backend hosted by another company with infrastructure
- Software-as-a-Service: applications hosted by a vendor and sold as subscription licenses to users
- Platform-as-a-Service: cloud provider offers users the necessary software/hardware for the creation/deployment/management of applications
- Infrastructure-as-a-Service: virtual environment delivered to a customer by a cloud provider

## Random Terms
- Service License Agreement (SLA) – the agreement between a cloud service
provider (CSP) and a customer, outlining contractural terms such as
availability, level of service, and performance.
- Elasticity – A cloud storage system’s capability for adapting to client’s
fluctuating workload demands.
- Consumption-Based – The cloud computing pricing model where consumers
are charged for how much of the service they use, rather than a block of time.
- Pay-As-You-Go – a means of purchasing cloud services from a provider that
requires no money down; Instead, it’s based on consumption or via
subscription.
- Load Balancing – The distribution of workloads over a series of resources,
such as servers, to assure that no single server suffers a point of failure.
Yet More Terms
- Multi-Tenancy – The ability of a single platform to run and hold a process,
application, or virtual machine for many users.
- Cloud Portability – The ability of an application and data to move from one
cloud service provider to another cloud service provider.
- Cloud Enablement – Make a could computing environment by writing the
necessary software, infrastructure, and applications.
- Cloudstorming – Assembling multiple cloude computing environments.
- Cloud Broker – An entity which is responsible for managing relationships
between customers and various cloud service providers.
- Cluster Computing – Computing using a cluster of pooled resources and
