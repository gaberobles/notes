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