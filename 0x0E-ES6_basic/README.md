# 0x0E. ES6 Basics

-   By Johann Kerbrat, Engineering Manager at Uber Works
-   Weight: 1
-   Ongoing project - started
    
    Jul 27, 2022
    
    , must end by
    
    Jul 29, 2022
    
    - you're done with  0% of tasks.
-   Checker was released at
    
    Jul 28, 2022 12:00 AM
    
-   An auto review will be launched at the deadline

### Concepts

_For this project, we expect you to look at this concept:_

-   [Software Linter](https://intranet.hbtn.io/concepts/354)

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/12/08806026ef621f900121.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220729%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220729T043150Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=34170fdbbf335201c249ccfa8c9b7584eeed22ca8b6e35188cd84125dcfec5fd)

## Resources

**Read or watch**:

-   [ECMAScript 6 - ECMAScript 2015](https://intranet.hbtn.io/rltoken/xb8-jbZtHwJDYX6RDOBM5w "ECMAScript 6 - ECMAScript 2015")
-   [Statements and declarations](https://intranet.hbtn.io/rltoken/AtYvlcC9-tnRj7sonlSSpA "Statements and declarations")
-   [Arrow functions](https://intranet.hbtn.io/rltoken/MwaeOv5xOAFSVZgKy99JfA "Arrow functions")
-   [Default parameters](https://intranet.hbtn.io/rltoken/UMDDlt1fHOd_rf-eaL9CdA "Default parameters")
-   [Rest parameter](https://intranet.hbtn.io/rltoken/saAaBn7WnBT2w-5bGp-BJQ "Rest parameter")
-   [Javascript ES6 — Iterables and Iterators](https://intranet.hbtn.io/rltoken/zwBb6qP69k4Yxk9x9Ir4-w "Javascript ES6 — Iterables and Iterators")

## Learning Objectives

At the end of this project, you are expected to be able to  [explain to anyone](https://intranet.hbtn.io/rltoken/sUuHz_VAAG4zTfHf9-O7zA "explain to anyone"),  **without the help of Google**:

-   What ES6 is
-   New features introduced in ES6
-   The difference between a constant and a variable
-   Block-scoped variables
-   Arrow functions and function parameters default to them
-   Rest and spread function parameters
-   String templating in ES6
-   Object creation and their properties in ES6
-   Iterators and for-of loops

## Requirements

### General

-   All your files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
-   Allowed editors:  `vi`,  `vim`,  `emacs`,  `Visual Studio Code`
-   All your files should end with a new line
-   A  `README.md`  file, at the root of the folder of the project, is mandatory
-   Your code should use the  `js`  extension
-   Your code will be tested using the  [Jest Testing Framework](https://intranet.hbtn.io/rltoken/YNZDqjw9SKhZou9dfX2ujw "Jest Testing Framework")
-   Your code will be analyzed using the linter  [ESLint](https://intranet.hbtn.io/rltoken/GXmDOSQ5GfehKsuYS1PsMQ "ESLint")  along with specific rules that we’ll provide
-   All of your functions must be exported

## Setup

### Install NodeJS 12.11.x

(in your home directory):

```
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y

```

```
$ nodejs -v
v12.11.1
$ npm -v
6.11.3

```

### Install Jest, Babel, and ESLint

in your project directory:

-   Install Jest using:  `npm install --save-dev jest`
-   Install Babel using:  `npm install --save-dev babel-jest @babel/core @babel/preset-env`
-   Install ESLint using:  `npm install --save-dev eslint`

## Configuration files

### `package.json`

Click to show/hide file contents

### `babel.config.js`

Click to show/hide file contents

### `.eslintrc.js`

Click to show/hide file contents

### Finally…

Don’t forget to run  `npm install`  from the terminal of your project folder to install all necessary project dependencies.