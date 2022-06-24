# 0x07. Session authentication

-   By Guillaume, CTO at Holberton School
-   Weight: 1
-   Ongoing project - started
    
    Jun 22, 2022
    
    , must end by
    
    Jun 24, 2022
    
    - you're done with  0% of tasks.
-   Checker was released at
    
    Jun 23, 2022 12:00 AM
    
-   An auto review will be launched at the deadline

## Background Context

In this project, you will implement a  **Session Authentication**. You are not allowed to install any other module.

In the industry, you should  **not**  implement your own Session authentication system and use a module or framework that doing it for you (like in Python-Flask:  [Flask-HTTPAuth](https://intranet.hbtn.io/rltoken/qXRfnHdkAH61gmZbC2xGzw "Flask-HTTPAuth")). Here, for the learning purpose, we will walk through each step of this mechanism to understand it by doing.

## Resources

**Read or watch**:

-   [REST API Authentication Mechanisms - Only the session auth part](https://intranet.hbtn.io/rltoken/2BkSCmFq5HYwztDCQuAwvg "REST API Authentication Mechanisms - Only the session auth part")
-   [HTTP Cookie](https://intranet.hbtn.io/rltoken/NMb6uXgVOVq0Tv7x_dbLEA "HTTP Cookie")
-   [Flask](https://intranet.hbtn.io/rltoken/D0AUceSjWti95ffW06MTHQ "Flask")
-   [Flask Cookie](https://intranet.hbtn.io/rltoken/-TgSvgacXt556tD3bMFXcg "Flask Cookie")

## Learning Objectives

At the end of this project, you are expected to be able to  [explain to anyone](https://intranet.hbtn.io/rltoken/VwUGR-ylC9X9sBp-uI4TyA "explain to anyone"),  **without the help of Google**:

### General

-   What authentication means
-   What session authentication means
-   What Cookies are
-   How to send Cookies
-   How to parse Cookies

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