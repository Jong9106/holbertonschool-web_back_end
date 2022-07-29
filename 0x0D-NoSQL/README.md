
# 0x0D. NoSQL

-   By Emmanuel Turlay, Staff Software Engineer at Cruise and Guillaume, CTO at Holberton school
-   Weight: 1
-   Ongoing second chance project - started
    
    Jul 25, 2022
    
    , must end by
    
    Aug 1, 2022
    
    - you're done with  192% of tasks.
-   An auto review will be launched at the deadline

#### In a nutshell…

-   **Auto QA review:**  123.0/135 mandatory & 0.0/32 optional
-   **Altogether:**  **91.11%**
    -   Mandatory: 91.11%
    -   Optional: 0.0%
    -   Calculation: 91.11% + (91.11% * 0.0%) == **91.11%**

## Resources

**Read or watch**:

-   [NoSQL Databases Explained](https://intranet.hbtn.io/rltoken/Vyx71sOlnw-ovIEiGB8L6w "NoSQL Databases Explained")
-   [What is NoSQL ?](https://intranet.hbtn.io/rltoken/8VpibJeEpPIdt9VGxXx5EQ "What is NoSQL ?")
-   [MongoDB with Python Crash Course - Tutorial for Beginners](https://intranet.hbtn.io/rltoken/8wsp1YBvkmbmPzdhtjI1uQ "MongoDB with Python Crash Course - Tutorial for Beginners")
-   [MongoDB Tutorial 2 : Insert, Update, Remove, Query](https://intranet.hbtn.io/rltoken/j8Km9rDeAfwz2D3sSoqmHQ "MongoDB Tutorial 2 : Insert, Update, Remove, Query")
-   [Aggregation](https://intranet.hbtn.io/rltoken/sKN0Bd-rI7G3z2JXBC0LqQ "Aggregation")
-   [Introduction to MongoDB and Python](https://intranet.hbtn.io/rltoken/Voj4w7WCWEoXh5BCBJuiow "Introduction to MongoDB and Python")
-   [mongo Shell Methods](https://intranet.hbtn.io/rltoken/NOvsdbmMAbK5lh8BqoIBQQ "mongo Shell Methods")
-   [The mongo Shell](https://intranet.hbtn.io/rltoken/lvKvzY7KzyiB--0x_l3APw "The mongo Shell")

## Learning Objectives

At the end of this project, you are expected to be able to  [explain to anyone](https://intranet.hbtn.io/rltoken/S_WtnnQiHaUABx-sZQzOuw "explain to anyone"),  **without the help of Google**:

### General

-   What NoSQL means
-   What is difference between SQL and NoSQL
-   What is ACID
-   What is a document storage
-   What are NoSQL types
-   What are benefits of a NoSQL database
-   How to query information from a NoSQL database
-   How to insert/update/delete information from a NoSQL database
-   How to use MongoDB

## Requirements

### MongoDB Command File

-   All your files will be interpreted/compiled on Ubuntu 18.04 LTS using  `MongoDB`  (version 4.2)
-   All your files should end with a new line
-   The first line of all your files should be a comment:  `// my comment`
-   A  `README.md`  file, at the root of the folder of the project, is mandatory
-   The length of your files will be tested using  `wc`

### Python Scripts

-   All your files will be interpreted/compiled on Ubuntu 18.04 LTS using  `python3`  (version 3.7) and  `PyMongo`  (version 3.10)
-   All your files should end with a new line
-   The first line of all your files should be exactly  `#!/usr/bin/env python3`
-   A  `README.md`  file, at the root of the folder of the project, is mandatory
-   Your code should use the  `pycodestyle`  style (version 2.5.*)
-   The length of your files will be tested using  `wc`
-   All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
-   All your functions should have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'`
-   Your code should not be executed when imported (by using  `if __name__ == "__main__"`:)

## More Info

### Install MongoDB 4.2 in Ubuntu 18.04

[Official installation guide](https://intranet.hbtn.io/rltoken/WCxsKI9IbJ4EcvsiFy3m8g "Official installation guide")

```
$ wget -qO - https://www.mongodb.org/static/pgp/server-4.2.asc | apt-key add -
$ echo "deb [ arch=amd64,arm64 ] https://repo.mongodb.org/apt/ubuntu bionic/mongodb-org/4.2 multiverse" > /etc/apt/sources.list.d/mongodb-org-4.2.list
$ sudo apt-get update
$ sudo apt-get install -y mongodb-org
...
$  sudo service mongod status
mongod start/running, process 3627
$ mongo --version
MongoDB shell version v4.2.8
git version: 43d25964249164d76d5e04dd6cf38f6111e21f5f
OpenSSL version: OpenSSL 1.1.1  11 Sep 2018
allocator: tcmalloc
modules: none
build environment:
    distmod: ubuntu1804
    distarch: x86_64
    target_arch: x86_64
$  
$ pip3 install pymongo
$ python3
>>> import pymongo
>>> pymongo.__version__
'3.10.1'

```

Potential issue if documents creation doesn’t work or this error:  `Data directory /data/db not found., terminating`  ([source](https://intranet.hbtn.io/rltoken/VahDhQv10rDE_pfficD5hA "source")  and  [source](https://intranet.hbtn.io/rltoken/cPmMqoI8cWh6nR21cMW11w "source"))

```
$ sudo mkdir -p /data/db

```

Or if  `/etc/init.d/mongod`  is missing, please find here an example of the file:

Click to expand/hide file contents

### Use “container-on-demand” to run MongoDB

-   Ask for container  `Ubuntu 18.04 - MongoDB`
-   Connect via SSH
-   Or via the WebTerminal
-   In the container, you should start MongoDB before playing with it:

```
$ service mongod start
* Starting database mongod                                              [ OK ]
$
$ cat 0-list_databases | mongo
MongoDB shell version v4.2.8
connecting to: mongodb://127.0.0.1:27017/?compressors=disabled&gssapiServiceName=mongodb
Implicit session: session { "id" : UUID("70f14b38-6d0b-48e1-a9a4-0534bcf15301") }
MongoDB server version: 4.2.8
admin   0.000GB
config  0.000GB
local   0.000GB
bye
$
```