# E-Commerce Application

## Project Description
This project is a simple E-Commerce application developed as part of the Agile assignment. It demonstrates Agile project management, Git and GitHub version control, and CI/CD automation using GitHub Actions.

## Objectives
- Apply Agile principles and Scrum practices using Jira.
- Create and manage a Git repository using Git and GitHub.
- Implement branching, commits, and merging.
- Configure an automated CI/CD workflow using GitHub Actions.

## Technologies Used
- HTML
- Git
- GitHub
- GitHub Actions
- Jira

## Features
- Display available products.
- Show product names and prices.
- Display special offers.
- Demonstrate source-code management and automated workflows.

## Project Structure
```text
ecommerce-app/
├── index.html
├── README.md
└── .github/
    └── workflows/
        └── ci-cd.yml
```

## CI/CD Pipeline
The GitHub Actions workflow runs when code is pushed to the `main` branch or a pull request targets `main`.

Pipeline stages:
1. Checkout source code.
2. Build the application.
3. Run the test step.
4. Package the application.
5. Execute the configured deployment step.

**Note:** The current example workflow uses placeholder commands for build, test, and deployment. These stages demonstrate the pipeline flow but do not perform a real production deployment.

## How to Run
1. Clone or download this repository.
2. Open `index.html` in a web browser.

## Author
Shravani Tatkare