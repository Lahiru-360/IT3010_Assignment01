# Playwright Testing Demonstration

SE3010 – Software Engineering Process & Quality Management
Assignment 1 – Tool Demonstration

## Overview

This project demonstrates the use of **Playwright** as an automated testing tool.
It showcases a complete workflow from **project setup → writing tests → executing tests → generating reports**.

The demonstration highlights key Quality Engineering practices such as **test automation, reusable test setup, API mocking, and behaviour-driven test structure**.

## Project Structure

```
playwright-demo
│
├── tests
│   ├── assertions.spec.js
│   ├── fixtures.spec.js
│   ├── mocking.spec.js
│   └── bdd.spec.js
│
├── fixtures
│   └── customFixture.js
│
├── playwright.config.js
└── package.json
```

## Features Demonstrated

Each team member demonstrates one key feature:

1. **Assertions** – Validate application behavior and UI elements
2. **Fixtures** – Reusable setup and environment preparation
3. **Mocking / Stubbing** – Simulate API responses for isolated testing
4. **BDD-style Tests** – Improve readability using Given-When-Then structure

## Installation

1. Clone the repository

```
git clone <repository-url>
cd playwright-demo
```

2. Install dependencies

```
npm install
```

3. Install Playwright browsers

```
npx playwright install
```

## Running Tests

Run all tests:

```
npx playwright test
```

Run a specific test file:

```
npx playwright test tests/assertions.spec.js
```

## Test Report

Generate the HTML test report:

```
npx playwright show-report
```

The report provides execution results, logs, and debugging information for each test.

## Purpose

This project demonstrates how **Playwright supports automated quality assurance within the software development lifecycle**, helping teams detect defects early and maintain reliable software systems.
