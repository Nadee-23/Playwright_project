# Playwright_project
# SwiftTranslator – Singlish to Sinhala Conversion (Playwright Tests)

This project contains **automated functional and UI test cases** for the **SwiftTranslator** web application, which converts **Singlish text into Sinhala**.  
The tests are written using **Playwright** and cover positive, negative, and UI behavior scenarios.

---

## 📌 Project Overview

- **Application Under Test:** https://www.swifttranslator.com/
- **Testing Tool:** Playwright
- **Language:** JavaScript
- **Test Type:** Functional Testing & UI Testing
- **Browsers Tested:** Chromium, Firefox, WebKit

---

## Project Structure

project-root/
│
├── function_test.spec.js # Main Playwright test file
├── playwright.config.js # Playwright configuration
├── package.json # Project dependencies and scripts
├── test-results/ # Playwright test reports (auto-generated)
└── README.md # Project documentation
Navigate to the project folder:
cd your-repo-name

Install dependencies:
npm install

Install Playwright browsers:
npx playwright install

Run all tests:
npx playwright test

Run tests in headed mode:
npx playwright test function_test.spec.js --headed

Run tests using Playwright UI:
npx playwright test --ui

Run a specific test file:
npx playwright test function_test.spec.js

Stopping Test Execution:
Ctrl + C

To view the HTML report:
npx playwright show-report

You can see the function report under the test result folder.

