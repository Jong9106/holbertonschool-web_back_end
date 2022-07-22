# 0x0C. MySQL advanced

-   By Guillaume Plessis, Senior Cloud & System Engineer at WeWork and Guillaume, CTO at Holberton school
-   Weight: 1
-   Ongoing project - started
    
    Jul 20, 2022
    
    , must end by
    
    Jul 22, 2022
    
    - you're done with  0% of tasks.
-   Checker was released at
    
    Jul 21, 2022 12:00 AM
    
-   An auto review will be launched at the deadline

### Concepts

_For this project, we expect you to look at this concept:_

-   [Advanced SQL](https://intranet.hbtn.io/concepts/225)

## Resources

**Read or watch**:

-   [MySQL cheatsheet](https://intranet.hbtn.io/rltoken/LPHf_IaJaKHjk5eFPXB0cA "MySQL cheatsheet")
-   [MySQL Performance: How To Leverage MySQL Database Indexing](https://intranet.hbtn.io/rltoken/lLnaxz0ESQy3EHwuMMfvfg "MySQL Performance: How To Leverage MySQL Database Indexing")
-   [Stored Procedure](https://intranet.hbtn.io/rltoken/Sk9qc1Mg-1iLY2CPwRO-GQ "Stored Procedure")
-   [Triggers](https://intranet.hbtn.io/rltoken/rpwsBdE-D0BvNGb_xp4e9g "Triggers")
-   [Views](https://intranet.hbtn.io/rltoken/_QXmgLWifMI5xBYcoU30-g "Views")
-   [Functions and Operators](https://intranet.hbtn.io/rltoken/o8FuG6wEKU7Czfshemkxiw "Functions and Operators")
-   [Trigger Syntax and Examples](https://intranet.hbtn.io/rltoken/_GHvsp9VBoFvcF8e3vR8FA "Trigger Syntax and Examples")
-   [CREATE TABLE Statement](https://intranet.hbtn.io/rltoken/BZ9CZqpTzEz7iN_hUfrLQQ "CREATE TABLE Statement")
-   [CREATE PROCEDURE and CREATE FUNCTION Statements](https://intranet.hbtn.io/rltoken/JD1BbREw66Vg1j8b_G4kkQ "CREATE PROCEDURE and CREATE FUNCTION Statements")
-   [CREATE INDEX Statement](https://intranet.hbtn.io/rltoken/MoxDptxm38J3IviBm2IMEw "CREATE INDEX Statement")
-   [CREATE VIEW Statement](https://intranet.hbtn.io/rltoken/uDiqx_4DI7ZZ8A11C4g5CA "CREATE VIEW Statement")

## Learning Objectives

At the end of this project, you are expected to be able to  [explain to anyone](https://intranet.hbtn.io/rltoken/1Mt4Of9qqJrL_U2lRTeA1Q "explain to anyone"),  **without the help of Google**:

### General

-   How to create tables with constraints
-   How to optimize queries by adding indexes
-   What is and how to implement stored procedures and functions in MySQL
-   What is and how to implement views in MySQL
-   What is and how to implement triggers in MySQL

## Requirements

### General

-   All your files will be executed on Ubuntu 18.04 LTS using  `MySQL 5.7`  (version 5.7.30)
-   All your files should end with a new line
-   All your SQL queries should have a comment just before (i.e. syntax above)
-   All your files should start by a comment describing the task
-   All SQL keywords should be in uppercase (`SELECT`,  `WHERE`…)
-   A  `README.md`  file, at the root of the folder of the project, is mandatory
-   The length of your files will be tested using  `wc`

## More Info

### Comments for your SQL file:

```
$ cat my_script.sql
-- 3 first students in the Batch ID=3
-- because Batch 3 is the best!
SELECT id, name FROM students WHERE batch_id = 3 ORDER BY created_at DESC LIMIT 3;
$

```

### Use “container-on-demand” to run MySQL

-   Ask for container  `Ubuntu 18.04 - Python 3.7`
-   Connect via SSH
-   Or via the WebTerminal
-   In the container, you should start MySQL before playing with it:

```
$ service mysql start
 * MySQL Community Server 5.7.30 is started
$
$ cat 0-list_databases.sql | mysql -uroot -p my_database
Enter password: 
Database
information_schema
mysql
performance_schema
sys
$

```

**In the container, credentials are  `root/root`**

### How to import a SQL dump

```
$ echo "CREATE DATABASE hbtn_0d_tvshows;" | mysql -uroot -p
Enter password: 
$ curl "https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/274/hbtn_0d_tvshows.sql" -s | mysql -uroot -p hbtn_0d_tvshows
Enter password: 
$ echo "SELECT * FROM tv_genres" | mysql -uroot -p hbtn_0d_tvshows
Enter password: 
id  name
1   Drama
2   Mystery
3   Adventure
4   Fantasy
5   Comedy
6   Crime
7   Suspense
8   Thriller
$
```