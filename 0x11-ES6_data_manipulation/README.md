# 0x11. ES6 data manipulation

-   By:  Johann Kerbrat, Engineering Manager at Uber Works
-   Weight:  1
-   Project will start  Aug 8, 2022 12:00 AM, must end by  Aug 10, 2022 12:00 AM
-   was  released at  Aug 9, 2022 12:00 AM
-   An auto review will be launched at the deadline

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/12/6ab7bec4727cb5c91257.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220809%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220809T223602Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=c78eb6c2379688152733f605e64c33a257b61c5aa176ebdc8a761af9d2563b2c)

## Resources

**Read or watch**:

-   [Array](https://intranet.hbtn.io/rltoken/DIsNNOXZExl3N3eb_ucyXQ "Array")
-   [Typed Array](https://intranet.hbtn.io/rltoken/EXbyPrXEhGoD1kPbiEPC9g "Typed Array")
-   [Set Data Structure](https://intranet.hbtn.io/rltoken/dYX70DxM_ibZ0SlDbbscOQ "Set Data Structure")
-   [Map Data Structure](https://intranet.hbtn.io/rltoken/weXVkufXRyUwQvQazDkzLg "Map Data Structure")
-   [WeakMap](https://intranet.hbtn.io/rltoken/X1ba6W8dGSnUKOTN4CzPVA "WeakMap")

## Learning Objectives

At the end of this project, you are expected to be able to  [explain to anyone](https://intranet.hbtn.io/rltoken/1KBjL212N3602ZMIOnVK0A "explain to anyone"),  **without the help of Google**:

-   How to use map, filter and reduce on arrays
-   Typed arrays
-   The Set, Map, and Weak link data structures

## Requirements

-   All your files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
-   Allowed editors:  `vi`,  `vim`,  `emacs`,  `Visual Studio Code`
-   All your files should end with a new line
-   A  `README.md`  file, at the root of the folder of the project, is mandatory
-   Your code should use the  `js`  extension
-   Your code will be tested using  `Jest`  and the command  `npm run test`
-   Your code will be verified against lint using ESLint
-   Your code needs to pass all the tests and lint. You can verify the entire project running  `npm run full-test`
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

### and…

Don’t forget to run  `$ npm install`  when you have the  `package.json`