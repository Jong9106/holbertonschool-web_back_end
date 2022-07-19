
# 0x0B. Redis basic

-   By Emmanuel Turlay, Staff Software Engineer at Cruise
-   Weight: 1
-   Ongoing project - started
    
    Jul 18, 2022
    
    , must end by
    
    Jul 20, 2022
    
    - you're done with  0% of tasks.
-   Checker was released at
    
    Jul 19, 2022 12:00 AM
    
-   An auto review will be launched at the deadline

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/1/40eab4627f1bea7dfe5e.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220719%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220719T200256Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=f97a0ce0ce240ef29186cade2cb5005b3bb1013126795d8f3870de6f0cc569fd)

## Resources

**Read or watch:**

-   [Redis commands](https://intranet.hbtn.io/rltoken/gCGI9l4Jnx2ux3Z7i4vhHQ "Redis commands")
-   [Redis python client](https://intranet.hbtn.io/rltoken/7Tx4uSKfPx9jFCwkCqECeg "Redis python client")
-   [How to Use Redis With Python](https://intranet.hbtn.io/rltoken/KDF4GPwRipbMwBj4SI64PQ "How to Use Redis With Python")
-   [Redis Crash Course Tutorial](https://intranet.hbtn.io/rltoken/4GOanmqONPEgtQqrbUcEVw "Redis Crash Course Tutorial")

## Learning Objectives

-   Learn how to use redis for basic operations
-   Learn how to use redis as a simple cache

## Requirements

-   All of your files will be interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7)
-   All of your files should end with a new line
-   A  `README.md`  file, at the root of the folder of the project, is mandatory
-   The first line of all your files should be exactly  `#!/usr/bin/env python3`
-   Your code should use the  `pycodestyle`  style (version 2.5)
-   All your modules should have documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
-   All your classes should have documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
-   All your functions and methods should have documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'`  and  `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)
-   A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)
-   All your functions and coroutines must be type-annotated.

## Install Redis on Ubuntu 18.04

```
$ sudo apt-get -y install redis-server
$ pip3 install redis
$ sed -i "s/bind .*/bind 127.0.0.1/g" /etc/redis/redis.conf

```

## Use Redis in a container

Redis server is stopped by default - when you are starting a container, you should start it with:  `service redis-server start`