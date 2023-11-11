WORKFLOW CA - Noroff

Badges.

[![Deploy static content to Pages](https://github.com/KarenBonillaM/social-media-client-workflow-ca/actions/workflows/pages.yml/badge.svg)](https://github.com/KarenBonillaM/social-media-client-workflow-ca/actions/workflows/pages.yml)

[![Automated Unit Testing](https://github.com/KarenBonillaM/social-media-client-workflow-ca/actions/workflows/unit-test.yml/badge.svg?branch=workflow)](https://github.com/KarenBonillaM/social-media-client-workflow-ca/actions/workflows/unit-test.yml)

[![E2E Testing](https://github.com/jakotide/social-media-client/actions/workflows/e2e-testing.yml/badge.svg?branch=workflow)](https://github.com/jakotide/social-media-client/actions/workflows/e2e-testing.yml)

Description.

Using the skills and knowledge from "Workflow" course, we have to improve the quality of a package by establishing helpful workflows that make the development process more efficient.

In this CA I was tasked with improving the quality of a social media application by providing various development workflows as well as a testing strategy.

Getting Started.

- Clone the repository.

  git clone <git@github.com:KarenBonillaM/social-media-client-workflow-ca.git>

- Install dependencies.

  npm install

- Build SASS.

  npm run build

Configurations.

- Prettier: Keeps the codebase clean and easy to read.
- ESlint: Makes sure the JavaScript is well written and that follows the coding standards.
- Hooks: I used a pre-commit hook that will automatically run ESLint and Prettier on all files in the repository.

Testing

Unit Testing with Jest.
Testing the login and logout functions. The login functions, fetches and storage a token. The logout function, remove the token from local storage.

npm run test-unit

End to end Testing with Cypress:
The purpose of e2e testing is to simulate the experience of a real world end user as they traverse a web application. In this project e2e test proves that the user can login and have access to their profile, user can't login with invalid credentials and user can logout.

npm run test-e2e
