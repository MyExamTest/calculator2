[![Board Status](https://dev.azure.com/AdamDobosz/7329ffd4-f24f-4516-b188-88bfd7e4afd0/01ad5265-101b-4778-a4f5-424627526904/_apis/work/boardbadge/26446816-92f4-4bf3-9d92-bddd1cc21360)](https://dev.azure.com/AdamDobosz/7329ffd4-f24f-4516-b188-88bfd7e4afd0/_boards/board/t/01ad5265-101b-4778-a4f5-424627526904/Microsoft.RequirementCategory)
Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

