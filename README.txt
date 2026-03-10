# Playwright Automation Framework

Automation framework for E2E shopping flow.

## Tech Stack

- Playwright
- Python
- Pytest
- Allure Reports

## Features

- Page Object Model
- Locator Fallback Mechanism
- Data Driven Testing
- Parallel Execution
- Screenshot Logging

## Scenario

1. Search items under max price
2. Add items to cart
3. Validate cart total

## Run Tests

pytest

## Parallel Execution

pytest -n 3

## Reports

pytest --alluredir=allure-results
allure serve allure-results