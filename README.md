# Test Automation for Wiley Online Library

This project contains automated test cases for verifying key functionalities of the Wiley Online Library website using Playwright. The tests include user registration, login, and browsing content by category.

## Prerequisites

Before running the tests, ensure the following requirements are met:

- **Node.js**: Install the latest stable version of Node.js from [Node.js Official Site](https://nodejs.org/).
- **Playwright**: Install Playwright for browser automation testing.
- **Supported Browsers**: Ensure you have the required browsers installed (Chromium, Firefox, WebKit). Playwright will handle the installation of the necessary browser binaries during setup.

## Installation

Follow these steps to set up the project:

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Install Playwright browsers:
   ```bash
   npx playwright install
   ```

## Project Structure

- `tests/`
  - Contains the test scripts written in Playwright.
- `package.json`
  - Includes project dependencies and scripts.
- `README.md`
  - Project documentation.

## Test Cases

### 1. Verify New User Registration
This test ensures a new user can successfully create an account on the Wiley Online Library platform and is redirected to the verification page.

### 2. Verify User Login
This test verifies that a user can log in using valid credentials and is redirected to the dashboard.

### 3. Verify Browsing Content by Category
This test checks if a user can browse content by selecting a category (e.g., "Architecture & Planning") and verifies that relevant content is displayed.

## Running the Tests

### Execute All Tests
To run all test cases:
```bash
npx playwright test
```

### Run Specific Test
To run a specific test, use the following command:
```bash
npx playwright test <test-file-name>
```
For example:
```bash
npx playwright test tests/wiley-tests.spec.js
```

### View Test Report
Playwright automatically generates test reports. To view the report, run:
```bash
npx playwright show-report
```

## Test Logs
Test logs are displayed in the console output. Each test includes console messages to indicate the success of each test step.

## Troubleshooting

- **Browser Not Launching:**
  Ensure the required browsers are installed by running:
  ```bash
  npx playwright install
  ```

- **Dependency Errors:**
  Run `npm install` to ensure all required dependencies are installed.

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License.

## Contact

For any questions or issues, please contact:
- **Email:** randika2000@gmail.com
