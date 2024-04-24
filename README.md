# Amazon Web Automation Test

This project contains automated tests for filtering and sorting items on the Amazon website using Cypress, TypeScript, and the Page Object Model (POM) approach.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Running Tests](#running-tests)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

#Introduction#

This project aims to automate the testing of the filtering and sorting functionality on the Amazon website. The tests are written using Cypress, a modern end-to-end testing framework, and TypeScript for type safety. The Page Object Model (POM) design pattern is utilized to maintain a clean and maintainable codebase.

#Prerequisites#

Before running the tests, ensure you have the following prerequisites installed:

- Node.js
- npm (Node Package Manager)

#Setup#

1. Clone this repository to your local machine:

   ```bash
   git clone <repository-url>



   Install dependencies:
bash
Copy code
npm install
Running Tests
To run the automated tests, use the following command: npx cypress run, npx cypress open

bash
Copy code
npx cypress run or npx cypress open
This command will execute the Cypress tests in headless mode and generate test reports.

Project Structure
The project follows a standard structure for Cypress test automation projects:

go
Copy code
amazon-web-automation/
│
├── cypress/
│   ├── e2e/
│   │   ├── POM/
│   │   │   └── amazon.feature
│   │   └── sortin.js/
│   │       └── codingchallenge.cy.js
│   
│   └
├── cypress.json
├── package.json
└── README.md


