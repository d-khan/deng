# About data

## Types of data

- Structured
- Semi structured
- Unstructured

## Data sources

- Relational databases
- Flat files and XML datasets
- APIs and web services
- Web scraping
- Data streams and feeds
- Social platforms
- Sensor devices

## File formats

- Delimited text files
  - CVS, TSV
- Spreadsheets
  - XLSX (Rows and columns)
- Language
  - XML, JSON (platform and programming language independent)

## Data repositories

After gathering data, data repositories are used to store data.

- Structure or semi-structure are often stored in databases (relational or non-relational databases)

Online Transactional Processing System (OLTP)

- Designed to store high-volume day-to-day operational data
- Mostly relational and can be non-relational

Online Analytical Processing (OLAP) Systems

- Optimized for conducting complex data structures.
- Include relational and non-relational databases, data warehouses, data lakes and big data stores

## Building blocks

- Building blocks of a relationship are:
  - Entities (rectangle shape)
  - Relationship sets (diamond shape)
  - Crows foot notations (> | <)

## Relational model concepts

- Building blocks

  - Relation and sets

  - Set is an unordered collection of distinct elements

  - No order and same data type

  - Relation

    - Relation scheme: name of a relation, name and type of each column

    ```sql
    AUTHOR(Author_ID:char,
          lastname: varchar)
    ```

    - Relation instance - a table made up of rows and columns
    - Column headings are called attributes
    - Row = tuple
    - Degree = the number of attributes in a relation (columns)
    - Cardinality = the number of tuples (rows)

<img width="681" alt="image" src="https://github.com/d-khan/deng/assets/11669149/ecb24a42-3b69-487d-a851-f0d74ea09dd5">

  - No order and same data type



## Database architecture

- Single-tier architecture - single user environment, database resides on the user's system.
- 2-tier architecture - Client-server - client application and database server run in separate tiers.
- 3-tier architecture - Client - Application server - Database server

<img width="693" alt="image" src="https://github.com/d-khan/deng/assets/11669149/37f8d6a8-bc74-42f7-8901-4ac997a37e37">

<img width="675" alt="image" src="https://github.com/d-khan/deng/assets/11669149/a7a68469-c869-422a-af6c-849f6170f6de">

## Relational database offerings

<img width="1237" alt="image" src="https://github.com/d-khan/deng/assets/11669149/da6da6b1-2ec1-4363-b73e-d591fbabeeab">

<img width="631" alt="image" src="https://github.com/d-khan/deng/assets/11669149/d1e3d074-ae5c-4d76-97b8-0a78b41009a1">

<img width="617" alt="image" src="https://github.com/d-khan/deng/assets/11669149/d3f289a7-a032-420c-bb72-201cc1f716a4"><img width="663" alt="image" src="https://github.com/d-khan/deng/assets/11669149/ecf4186e-3657-4849-b737-5dc711265a6a">

## MySQL

<img width="687" alt="image" src="https://github.com/d-khan/deng/assets/11669149/8d35beee-1083-4d05-9930-749cebd73157">

<img width="702" alt="image" src="https://github.com/d-khan/deng/assets/11669149/5746960c-e706-4615-94d5-f94eaa10dad4">

## PostgreSQL

<img width="652" alt="image" src="https://github.com/d-khan/deng/assets/11669149/9df1cb9e-22d7-4e9c-b161-fb57f3e1238b">

## SQL

SQL statement types

- DDL (Data Definition Language)
  - Define, change, or drop data
  - CREATE, ALTER, TRUNCATE, DROP
- DML (Data Manipulation Language)
  - CRUD operation (create, read, update and delete)

<img width="662" alt="image" src="https://github.com/d-khan/deng/assets/11669149/b6ea48cf-e190-4a3c-ab47-c8dc850cdb20">

## Database hierarchy

![image](https://github.com/d-khan/deng/assets/11669149/a45f8d75-6510-4727-bbde-ba0cd538c5ed)

## Database instances

![image](https://github.com/d-khan/deng/assets/11669149/eabfe3eb-4b4e-4140-9bc2-cb34073d9e3d)

## Relational databases

![image](https://github.com/d-khan/deng/assets/11669149/5939206b-5c1c-4652-b772-f783d8106326)

## Schemas

![image](https://github.com/d-khan/deng/assets/11669149/b3df44ce-8e62-483b-b9a7-670cb0336872)

## Database partitions

![image](https://github.com/d-khan/deng/assets/11669149/8ba5846d-2337-4e56-9e46-a4011a1d4303)

## Database objects

![image](https://github.com/d-khan/deng/assets/11669149/73c4958b-fdaa-4677-9ae0-84f325023f11)

## Normalization

![image](https://github.com/d-khan/deng/assets/11669149/361e57a7-4a9d-4069-ab73-97f52bc57632)

## First normal form

![image](https://github.com/d-khan/deng/assets/11669149/2bdf3265-0a7e-4e9c-a6c0-b58f16074bd7)

![image](https://github.com/d-khan/deng/assets/11669149/28f3eba2-9dab-4aa2-aa22-09e0601867c8)

![image](https://github.com/d-khan/deng/assets/11669149/4bcef68e-78a2-48b8-8c8e-6fd49f845787)

## Second normal form

![image](https://github.com/d-khan/deng/assets/11669149/7f9dc4fa-9e8b-47b5-8d80-b280607cd758)

![image](https://github.com/d-khan/deng/assets/11669149/f997e0b8-b533-4c5b-87b9-2e7a346800a0)

![image](https://github.com/d-khan/deng/assets/11669149/b1983d68-62b4-4560-8e62-431061cc6085)

## Third normal form

![image](https://github.com/d-khan/deng/assets/11669149/a4ec151d-400c-4249-9bbc-e73114d83569)

![image](https://github.com/d-khan/deng/assets/11669149/f388fbcd-4860-413d-8f80-645e4eb75129)

## Contraints
### Entity integrity constraints
With the Entity Integrity Constraint no attribute participating in the primary key is allowed to accept NULL values.
<img width="683" alt="image" src="https://github.com/d-khan/deng/assets/11669149/48ef9d5e-30f3-4c46-85b1-9602e223a777">
<img width="667" alt="image" src="https://github.com/d-khan/deng/assets/11669149/e9c207fd-10fc-4c56-8ad6-8c7fb5ff7621">

### Referential integrity constraints
Referential integrity constraint defines relationships between tables and ensures that these relationships remain valid. The validity of the data is enforced using a combination of Primary Keys and Foreign Keys.
<img width="651" alt="image" src="https://github.com/d-khan/deng/assets/11669149/daf6e265-20b7-4712-816c-cbf4717d4c56">

### Semantic integrity constraints
Correctness of the data
<img width="658" alt="image" src="https://github.com/d-khan/deng/assets/11669149/9477aa2f-5030-4983-9009-f63f90583b3e">

### Domain integrity constraints
Valid data type
<img width="671" alt="image" src="https://github.com/d-khan/deng/assets/11669149/9b04b301-f80a-45ae-a5e4-c7cee89303c2">

### Null integrity constraints
Attribute cannot be NULL
<img width="669" alt="image" src="https://github.com/d-khan/deng/assets/11669149/afb31e0d-b603-47f4-9f49-171a37784ebb">

### Check integrity constaints
Range of valid values
<img width="654" alt="image" src="https://github.com/d-khan/deng/assets/11669149/aa8d92a9-8b47-439a-a46f-ca15c3cf8948">

## PostgreSQL RDBMS
<img width="691" alt="image" src="https://github.com/d-khan/deng/assets/11669149/5f1a8069-cbb0-4001-ab09-a0d7dfa1b7db">

## The database life cycle
<img width="656" alt="image" src="https://github.com/d-khan/deng/assets/11669149/79b2c37a-ad76-4e2a-8bfe-666dd3893cd5">

## The database hierarchy
<img width="623" alt="Screen Shot 2023-06-03 at 7 48 40 AM" src="https://github.com/d-khan/deng/assets/11669149/9724db81-ba64-4cfb-8317-03c7e3af3f4d">

## Common database objects
<img width="619" alt="image" src="https://github.com/d-khan/deng/assets/11669149/c782276b-0020-4d93-a449-77116810aa6f">

## Db2 system objects
<img width="597" alt="image" src="https://github.com/d-khan/deng/assets/11669149/5f794c17-221e-4201-84ae-8d128c018e1b">

## MySQL system objects
<img width="462" alt="image" src="https://github.com/d-khan/deng/assets/11669149/b3486c37-2de6-47bd-ac02-55e0d88653d3">

## PostgreSQL system objects
<img width="566" alt="image" src="https://github.com/d-khan/deng/assets/11669149/33078e96-9ba2-4da7-8bef-18b762ee2147">

## Configuration file examples
<img width="575" alt="image" src="https://github.com/d-khan/deng/assets/11669149/6c7dcc68-db63-4211-955c-e5b49522e141">

## Tablespace benefits
<img width="614" alt="image" src="https://github.com/d-khan/deng/assets/11669149/6c810bf6-9417-46e1-acd1-e45a0b0f9515">

> Difference between containers and tablespaces

## Physical and logical backup
<img width="612" alt="image" src="https://github.com/d-khan/deng/assets/11669149/01108b3d-14db-43e1-8b0f-2b2586abacff">

## Types of backup
- Full backup
- Point in time backup
- Differential backup: A copy of any data that has changed since the last full backup was taken.
- Incremental backup: A copy of any data that has changed since the last backup of any type that was taken.

## Transaction log usage example
<img width="612" alt="image" src="https://github.com/d-khan/deng/assets/11669149/427496ad-bd84-4c2c-9a66-896ab0f9a44e">

## Storing transaction log file
<img width="615" alt="image" src="https://github.com/d-khan/deng/assets/11669149/120e64ef-b39c-467e-8499-0008a048b619">
<img width="614" alt="image" src="https://github.com/d-khan/deng/assets/11669149/1fc95cfb-aa7e-48ea-87e9-cec7b5e04a81">

## Basic anatomy of a database log
<img width="602" alt="image" src="https://github.com/d-khan/deng/assets/11669149/71edbc90-ee89-4555-b19b-b7264b4ea133">









