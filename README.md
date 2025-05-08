# Govtool Test Reports

This repository stores Allure reports generated during the integration and backend test workflows of the [Govtool repository](https://github.com/IntersectMBO/govtool).

## Workflows

### Integration Test Workflow
- Defined in: [test_integration_playwright.yml](https://github.com/IntersectMBO/govtool/blob/develop/.github/workflows/test_integration_playwright.yml)
- The report is deployed to the `gh-pages` branch via the `Deploy report to Github Pages` step in the `publish-report` job.

### Backend Test Workflow
- Defined in: [test_backend.yml](https://github.com/IntersectMBO/govtool/blob/develop/.github/workflows/test_backend.yml)
- The report is deployed to the `gh-pages` branch via the `Deploy report to Github Pages` step in the `publish-report` job.

## Running Workflows
Workflows can be executed in two ways:
1. **Automatically**: Triggered after a successful QA workflow.
2. **Manually**:
   - Navigate to the workflow's action page (e.g., [Backend Test Workflow](https://github.com/IntersectMBO/govtool/actions/workflows/test_backend.yml)).
   - Click **Run workflow** in the top-right corner.
   - Select the appropriate branch, deployment, and network.
   - Start the test.
   - Once completed, the Allure report is pushed to the `gh-pages` branch, maintaining the folder structure.

## Allure Reports
- Reports are stored in the [gh-pages branch](https://github.com/IntersectMBO/govtool-test-reports/tree/gh-pages/).
- Details on folder structure and report history maintenance are available in the `gh-pages` branch documentation.


## Report Links
- **All Projects**: [https://intersectmbo.github.io/govtool-test-reports/](https://intersectmbo.github.io/govtool-test-reports/)
- **govtool-frontend**: [https://intersectmbo.github.io/govtool-test-reports/govtool-frontend](https://intersectmbo.github.io/govtool-test-reports/govtool-frontend)
- **govtool-backend**: [https://intersectmbo.github.io/govtool-test-reports/govtool-backend](https://intersectmbo.github.io/govtool-test-reports/govtool-backend)
- **web-app-boilerplate**: [https://intersectmbo.github.io/govtool-test-reports/web-app-boilerplate](https://intersectmbo.github.io/govtool-test-reports/web-app-boilerplate)
