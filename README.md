# 🎭 Playwright Demo Project

A group demonstration of Playwright test automation covering four core features.

## Setup

```bash
npm init -y
npm install -D @playwright/test
npx playwright install
mkdir tests fixtures pages
```

## Project Structure

```
playwright-demo/
├── playwright.config.js
├── tests/
│   ├── assertions.spec.js
│   ├── fixtures.spec.js
│   ├── mocking.spec.js
│   └── bdd.spec.js
└── fixtures/
    └── customFixture.js
```

## Features

| Member | Feature    | File                       |
| ------ | ---------- | -------------------------- |
| 1      | Assertions | `tests/assertions.spec.js` |
| 2      | Fixtures   | `tests/fixtures.spec.js`   |
| 3      | Mocking    | `tests/mocking.spec.js`    |
| 4      | BDD Style  | `tests/bdd.spec.js`        |

## Running Tests

```bash
# Run a single test
npx playwright test tests/assertions.spec.js

# Run all tests
npx playwright test

# View HTML report
npx playwright show-report
```

## Expected Output

```
Running 4 tests
✓ Verify Wikipedia homepage
✓ Login page loads correctly
✓ Mock API example
✓ Given user searches Playwright, Then results appear

4 passed
```
