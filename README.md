Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

![image](https://user-images.githubusercontent.com/68406555/138098678-0345a03f-7608-4b58-89c9-d1dc677a44cb.png)

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

