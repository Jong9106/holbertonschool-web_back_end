
# 0x0F. ES6 Promises

-   By:  Johann Kerbrat, Engineering Manager at Uber Works
-   Weight:  1
-   Ongoing second chance project - started  Aug 1, 2022 12:00 AM, must end by  Aug 8, 2022 12:00 AM
-   An auto review will be launched at the deadline

#### In a nutshell…

-   **Auto QA review:**  0.0/26 mandatory & 0.0/4 optional
-   **Altogether:**  **0.0%**
    -   Mandatory: 0.0%
    -   Optional: 0.0%
    -   Calculation: 0.0% + (0.0% * 0.0%) == **0.0%**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2019/12/75862d67ca51a042003c.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOU5BHMTQX4%2F20220805%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220805T001621Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=14af0073f418c3750f2cb591439e699f2fcf84519bef4885f8278dcc099c7d09)

## Resources

**Read or watch**:

-   [Promise](https://intranet.hbtn.io/rltoken/mU4W2KkOd6iZ2j3wSekQVQ "Promise")
-   [JavaScript Promise: An introduction](https://intranet.hbtn.io/rltoken/NHrFfJu-_sIrYPAfRq0yLQ "JavaScript Promise: An introduction")
-   [Await](https://intranet.hbtn.io/rltoken/P_KRoM7eWMSM678vWJxN1w "Await")
-   [Async](https://intranet.hbtn.io/rltoken/-CM2Q4-f2aVv8Vpjaexghg "Async")
-   [Throw / Try](https://intranet.hbtn.io/rltoken/AQnTda-fFLGicQJSwrDEqA "Throw / Try")

## Learning Objectives

At the end of this project, you are expected to be able to  [explain to anyone](https://intranet.hbtn.io/rltoken/KO0tz0PrQsQQXmyovbwW9A "explain to anyone"),  **without the help of Google**:

-   Promises (how, why, and what)
-   How to use the  `then`,  `resolve`,  `catch`  methods
-   How to use every method of the Promise object
-   Throw / Try
-   The await operator
-   How to use an  `async`  function

## Requirements

-   All your files will be executed on Ubuntu 18.04 LTS using NodeJS 12.11.x
-   Allowed editors:  `vi`,  `vim`,  `emacs`,  `Visual Studio Code`
-   All your files should end with a new line
-   A  `README.md`  file, at the root of the folder of the project, is mandatory
-   Your code should use the  `js`  extension
-   Your code will be tested using  `Jest`  and the command  `npm run test`
-   Your code will be verified against lint using ESLint
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
-   Install Babel using:  `npm install --save-dev babel-jest @babel/core @babel/preset-env @babel/cli`
-   Install ESLint using:  `npm install --save-dev eslint`

## Files

### `package.json`

Click to show/hide file contents

### `babel.config.js`

Click to show/hide file contents

### `utils.js`

Use when you get to tasks requiring  `uploadPhoto`  and  `createUser`.

Click to show/hide file contents

### `.eslintrc.js`

Click to show/hide file contents

### and…

Don’t forget to run  `$ npm install`  when you have the  `package.json`

## Response Data Format

`uploadPhoto`  returns a response with the format

```
{
  status: 200,
  body: 'photo-profile-1',
}