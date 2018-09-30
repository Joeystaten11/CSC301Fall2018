# CSC 301, Database Systems Notes (Fall, 2018)
## Megan Squire, Elon University

### Table of Contents
#### Unit 1: Introduction to Databases

* 1.0 [Basic concepts](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit1/1.0Notes.md)
* 1.1 [Things we care about](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit1/1.1Notes.md)
* 1.2 [Database vocabulary](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit1/1.2Notes.md)
* 1.3 [Data types](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit1/1.3Notes.md)
* 1.4 [Basic SQL commands](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit1/1.4Notes.md)

🖥 [Day 1 lab covers 1.0-1.4](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit1/Day1Lab.md) ([Answers](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit1/Day1LabAnswers.md))

#### Unit 2: SQL: SELECT
* 2.0 [Basic SELECT](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit2/2.0Notes.md)
* 2.1 [The WHERE clause](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit2/2.1Notes.md)
* 2.2 [Shortcuts to columns and tables: Aliases](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit2/2.2Notes.md)
* 2.3 [Sorting with ORDER BY](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit2/2.3Notes.md)
* 2.4 [Reducing results with LIMIT](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit2/2.4Notes.md)
* 2.5 [Creating sets with IN](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit2/2.5Notes.md)
* 2.6 Aggregating data
    - 2.6.0 [Simple aggregates](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit2/2.6.0Notes.md)
    - 2.6.1 [Aggregating with GROUP BY](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit2/2.6.1Notes.md)
    - 2.6.2 [Rules of GROUP BY](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit2/2.6.2Notes.md)
    - 2.6.3 [Efficiency](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit2/2.6.3Notes.md)
    - 2.6.4 [HAVING](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit2/2.6.4Notes.md)
    
🖥 [Day 2 lab covers Basic SELECTs, Unit 2.0-2.5](https://github.com/megansquire/CSC301Fall2018/tree/master/Unit2/Day2Lab.md) ([Answers](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit2/Day2LabAnswers.md))

🖥 [Day 3 lab covers Aggregating Data, Unit 2.6](https://github.com/megansquire/CSC301Fall2018/tree/master/Unit2/Day3Lab.md) ([Answers](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit2/Day3LabAnswers.md))

🖥 [Extra practice questions for Unit 2](https://github.com/megansquire/CSC301Fall2018/tree/master/Unit2/Unit2ExtraPractice.md) (Answers included)

#### Unit 3: SQL: Functions and additional commands
* 3.0 [SQL Functions](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit3/3.0Notes.md)
* 3.1 [Date and time functions](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit3/3.1Notes.md)
* 3.2 [String functions](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit3/3.2Notes.md)
* 3.3 [Numeric functions](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit3/3.3Notes.md)
* 3.4 Additional SQL commands: [Data Manipulation](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit3/3.4Notes.md)
    - 3.4.0 SELECT
    - 3.4.1 INSERT
    - 3.4.2 INSERT-SELECT
    - 3.4.3 UPDATE
    - 3.4.4 DELETE
* 3.5 Additional SQL commands: [Data Definition](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit3/3.5Notes.md)
    - 3.5.0 CREATE
    - 3.5.1 DROP
    - 3.5.2 ALTER
    - 3.5.3 RENAME

🖥 [Day 4 lab covers Functions 3.0-3.3](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit3/Day4Lab.md) ([Answers](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit3/Day4LabAnswers.md))

🖥 [Day 5 lab covers Additional SQL Commands 3.4-3.5](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit3/Day5Lab.md) ([Answers](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit3/Day5LabAnswers.md))

#### Unit 4: SQL: Joins and Subqueries
* 4.1 [What are joins for?](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.1Notes.md)
* 4.2 [INNER JOIN](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.2Notes.md)
    - 4.2.1 [Simple lookup table](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.2Notes.md#421-inner-join-example-simple-lookup-table)
    - 4.2.2 [Adding an Aggregate Function](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.2Notes.md#422-inner-join-example-2-adding-an-aggregate-function)
    - 4.2.3 [Selecting from Three+ Tables](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.2Notes.md#423-inner-join-example-3-selecting-from-three-tables)
    - 4.2.4 [Common JOIN Errors](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.2Notes.md#424-common-inner-join-errors)
    - 4.3.5 [Locating an ERD](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.2Notes.md#425-locating-your-erd) inside PhpMyAdmin
* 4.3 [OUTER JOIN](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.3Notes.md)
    - 4.3.1 [Simple Example](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.3Notes.md#431-outer-join-example-1-simple)
    - 4.3.2 [Adding an Aggregate Function](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.3Notes.md#432-outer-join-example-2-adding-an-aggregate)
* 4.4 [More Facts About JOINs](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.4Notes.md)
    - 4.4.1 [Equi-Join](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.4Notes.md#441-equi-join)
    - 4.4.2 [NATURAL JOIN](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.4Notes.md#442-natural-join)
    - 4.4.3 [Theta vs. ANSI Style](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.4Notes.md#443-theta-vs-ansi-style)
    - 4.4.4 [CROSS JOIN](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.4Notes.md#444-cross-join)
* 4.5 [Subqueries](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.5Notes.md)
    - 4.5.1 [Correlated vs. Non-Correlated](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.5Notes.md#451-correlated-vs-non-correlated-subqueries)
    - 4.5.2 [Things to know about Subqueries](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Unit4.5Notes.md#452-things-to-know-about-subqueries)
    
🖥 [Day 6 lab covers INNER JOIN Unit 4.1, 4.2](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Day6Lab.md) ([Answers](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Day6LabAnswers.md))

🖥 [Day 7 lab covers OUTER JOIN Unit 4.3](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Day7Lab.md)([Answers](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Day7LabAnswers.md))

🖥 [Day 8 lab covers Subqueries Unit 4.5](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Day8Lab.md) ([Answers](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Day8LabAnswers.md))

🖥 [Day 9 lab reviews JOINs and subqueries 4.1-4.5](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Day9Lab.md)([Answers](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit4/Day9LabAnswers.md))
#### Unit 5: Database Design
* 5.1 [What is database design?](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit5/Unit5.1Notes.md)
    - 5.1.1 [Where does database design fit in?](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit5/Unit5.1Notes.md#511-where-does-database-design-fit-in)
    - 5.1.2 [Values of database design](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit5/Unit5.1Notes.md#512-values-of-database-design)
* 5.2 [Entity-Relationship Diagrams](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit5/Unit5.2Notes.md)
* 5.3 [Using MySQL Workbench to Create ERDs](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit5/Unit5.3Notes.md)
* 5.4 [Database Normalization](https://github.com/megansquire/CSC301Fall2018/blob/master/Unit5/Unit5.4Notes.md)
* 5.5 [Metadata & Charsets]()
* 5.6 [Views & Indexes]()

#### Unit 6: Database programming in Python

#### Unit 7: JSON, No-SQL, document databases, MongoDB
