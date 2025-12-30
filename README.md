# Playwright TodoMVC Automation Framework

## Project Overview

An End-to-End (E2E) testing automation framework built using Playwright and JavaScript for testing the React-based TodoMVC application. This project highlights the importance of robust test design and modern testing practices.

This framework automates critical user interactions with the TodoMVC app, showcasing:

***Reliable Locator Strategies: Leveraging getByRole and getByTestId for effective and stable element selection.**

***Atomic Test Design: Emphasizing the importance of modular, reusable, and easy-to-maintain tests.**

***Page Interventions: Automating user actions like clicking, inputting text, filtering, and checking tasks.**

***State Validation & Assertions: Verifying task states (active/completed) after performing actions to ensure expected behavior.**

## Tech Stack
***Automation Tool- Playwright**

***Language- Javascript**

***TestRunner- Playwright Test**

***Reporting- Playwright HTML Reporter**

## Test Scenarios Covered

The framework currently covers several key user scenarios, outlined in the todo.spec.js test file:

Task Creation: Adding multiple Todo items dynamically, verifying they're added correctly.

Task Management: Marking items as completed and ensuring state changes are reflected.

Filtering: Verifying the 'Active' vs. 'Completed' filters work as expected.

State Verification: Ensuring Todo items' visibility and state align with user actions (e.g., marking as complete).
