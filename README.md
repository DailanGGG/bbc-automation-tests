# bbc-automation-tests
Automated E2E test suite for Big O Business Center built with Cypress.

# Bigo Business Center - Cypress E2E Tests

Automated End-to-End (E2E) test suite for **Bigo Business Center** built with [Cypress](https://cypress.io).

## Prerequisites

Before running the tests, ensure you have the following installed on your machine:
* [Node.js](https://nodejs.org) (v18 or higher recommended)
* npm or yarn

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/DailanGGG/bbc-automation-tests.git
   ```

2. **Navigate to the project directory:**
   ```bash
   bbc-automation-tests
   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Environment Configuration (Optional):**
   If the project requires credentials or environment variables, create a `cypress.env.json` file in the root directory based on your test environment needs.

## Running Tests

* **Interactive Mode (Cypress Test Runner):**
  Opens the Cypress UI to run and debug tests visually.
  ```bash
  npx cypress open
  ```

* **Headless Mode (CLI):**
  Runs all tests in the terminal without opening the browser UI.
  ```bash
  npx cypress run
  ```

## Project Structure

```text
├── cypress/
│   ├── e2e/              # Automated test specs (*.cy.js / *.cy.ts)
│   ├── fixtures/         # Static test data (JSON files)
│   └── support/          # Custom commands and global configurations
├── cypress.config.js     # Cypress configuration file
├── package.json          # Project dependencies and scripts
└── README.md             # Project documentation
```
