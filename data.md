# About data

## Types of data

- Structure
- Semi structure
- Un structure

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
    - Degree = the number of attributes in a relation
    - Cardinality = the number of tuples

<img width="681" alt="image" src="https://github.com/d-khan/deng/assets/11669149/ecb24a42-3b69-487d-a851-f0d74ea09dd5">

  - No order and same data type
