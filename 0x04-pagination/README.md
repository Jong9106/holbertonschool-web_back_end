# 0x04. Pagination

-   By Emmanuel Turlay, Staff Software Engineer at Cruise
-   Weight: 1
-   Ongoing project - started
    
    Jun 13, 2022
    
    , must end by
    
    Jun 15, 2022
    
    - you're done with  0% of tasks.
-   Checker was released at
    
    Jun 14, 2022 12:00 AM
    
-   An auto review will be launched at the deadline

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/12/3646eb02de6527ca5d83.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220615%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220615T020910Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=14b2f74900cea27b19e6231c86466f4f08c562c1cf3056464352609ea9f2a923)  ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/12/746187b76bea1f46030e.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220615%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220615T020910Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=086083e58648915103b7f37374de6548cc33c921b25a956c3ee38d3786f9bc74)  ![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/12/665ce871c2ecc66a8e71.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220615%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220615T020910Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=35715dc480d0a73171f7651ea372e3f266e2803013bd99f4cbdc2fda9755577b)

## Resources

**Read or watch:**

-   [REST API Design: Pagination](https://intranet.hbtn.io/rltoken/TjO9hjRkzAR2F2jNcUX7fQ "REST API Design: Pagination")
-   [HATEOAS](https://intranet.hbtn.io/rltoken/7wmXMksUnZokxW_oHlLxrA "HATEOAS")

## Learning Objectives

At the end of this project, you are expected to be able to  [explain to anyone](https://intranet.hbtn.io/rltoken/-ZGwuw8X0hQXvV6o5daT_Q "explain to anyone"),  **without the help of Google**:

-   How to paginate a dataset with simple page and page_size parameters
-   How to paginate a dataset with hypermedia metadata
-   How to paginate in a deletion-resilient manner

## Requirements

-   All your files will be interpreted/compiled on Ubuntu 18.04 LTS using  `python3`  (version 3.7)
-   All your files should end with a new line
-   The first line of all your files should be exactly  `#!/usr/bin/env python3`
-   A  `README.md`  file, at the root of the folder of the project, is mandatory
-   Your code should use the  `pycodestyle`  style (version 2.5.*)
-   The length of your files will be tested using  `wc`
-   All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
-   All your functions should have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'`
-   A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)
-   All your functions and coroutines must be type-annotated.

## Setup:  `Popular_Baby_Names.csv`

[use this data file](https://intranet.hbtn.io/rltoken/wXTj4w6EoYUAWEOYI9p8Gw "use this data file")  for your project