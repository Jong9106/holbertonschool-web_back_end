# 0x06. Basic authentication

-   By Guillaume, CTO at Holberton School
-   Weight: 1
-   Ongoing project - started
    
    Jun 20, 2022
    
    , must end by
    
    Jun 22, 2022
    
    - you're done with  0% of tasks.
-   Checker was released at
    
    Jun 21, 2022 12:00 AM
    
-   An auto review will be launched at the deadline

## Background Context

In this project, you will learn what the authentication process means and implement a  **Basic Authentication**  on a simple API.

In the industry, you should  **not**  implement your own Basic authentication system and use a module or framework that doing it for you (like in Python-Flask:  [Flask-HTTPAuth](https://intranet.hbtn.io/rltoken/ck5nE4pv5NdWV38srlET0Q "Flask-HTTPAuth")). Here, for the learning purpose, we will walk through each step of this mechanism to understand it by doing.

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/5/6ccb363443a8f301bc2bc38d7a08e9650117de7c.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220622%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220622T022745Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=7feca04b38798245317cd21690c068dcf44552ee840be9a42e9dc1017d9ab80c)

## Resources

**Read or watch**:

-   [REST API Authentication Mechanisms](https://intranet.hbtn.io/rltoken/Yx1Na2qEzCLnke8RnpACDw "REST API Authentication Mechanisms")
-   [Base64 in Python](https://intranet.hbtn.io/rltoken/R2kTeyWl2ef19mdxQuffww "Base64 in Python")
-   [HTTP header Authorization](https://intranet.hbtn.io/rltoken/5BfGd-_oV9Asi_Ymi_lRSA "HTTP header Authorization")
-   [Flask](https://intranet.hbtn.io/rltoken/3ivma6PpGZfjzDrA2zLq7g "Flask")
-   [Base64 - concept](https://intranet.hbtn.io/rltoken/8ckHTvJq00WnvgEmn6GGtg "Base64 - concept")

## Learning Objectives

At the end of this project, you are expected to be able to  [explain to anyone](https://intranet.hbtn.io/rltoken/SzP_ze3i3creBPylmPrRZQ "explain to anyone"),  **without the help of Google**:

### General

-   What authentication means
-   What Base64 is
-   How to encode a string in Base64
-   What Basic authentication means
-   How to send the Authorization header

## Requirements

### Python Scripts

-   All your files will be interpreted/compiled on Ubuntu 18.04 LTS using  `python3`  (version 3.7)
-   All your files should end with a new line
-   The first line of all your files should be exactly  `#!/usr/bin/env python3`
-   A  `README.md`  file, at the root of the folder of the project, is mandatory
-   Your code should use the  `pycodestyle`  style (version 2.5)
-   All your files must be executable
-   The length of your files will be tested using  `wc`
-   All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
-   All your classes should have a documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
-   All your functions (inside and outside a class) should have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'`  and  `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)
-   A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)