Module 20 Challenge: GitHub Actions CI/CD Setup

Your task is to take starter code and create a CI/CD pipeline using GitHub Actions to run the component tests via Cypress when a Pull Request is made to the develop branch, and the application is deployed when code is merged from develop to the main branch.

User Story

* AS A software engineer looking to integrate a CI/CD pipeline in a codebase
* I WANT a full-stack application that runs test cases when a Pull Request is made to the develop branch and automatically deploys to Render when the code is merged to main
* SO THAT I can ensure that all code integrations are clean and pass the proper requirements and that the application is constantly updated when major releases are made to the main branch

Acceptance Criteria

* GIVEN a full-stack application
* WHEN I upload new features to the application
* THEN I should be making Pull Requests to a develop branch first
* WHEN I create a Pull Request to a develop branch
* THEN I should be executing a GitHub Action that checks the Cypress component tests
* WHEN I see that the tests pass on GitHub Action
* THEN I should see those test results on GitHub Action and merge the code
* WHEN I push the code from the develop branch to the main branch
* THEN I should see that another GitHub Action triggers and should automatically deploy to Render


DEPLOYMENT: https://dashboard.render.com/web/srv-cv7qpp1c1ekc73d19pag

