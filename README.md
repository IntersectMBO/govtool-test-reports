# Govtool Test Reports

This repository stores Allure reports generated during the integration and backend test workflows of the [Govtool repository](https://github.com/IntersectMBO/govtool).


## Report Links

- **All Projects**: [https://intersectmbo.github.io/govtool-test-reports/](https://intersectmbo.github.io/govtool-test-reports/)


### QA Environment
- **govtool-frontend**: [https://intersectmbo.github.io/govtool-test-reports/qa/govtool-frontend](https://intersectmbo.github.io/govtool-test-reports/qa/govtool-frontend)
- **govtool-backend**: [https://intersectmbo.github.io/govtool-test-reports/qa/govtool-backend](https://intersectmbo.github.io/govtool-test-reports/qa/govtool-backend)

### Dev Environment
- **govtool-frontend**: [https://intersectmbo.github.io/govtool-test-reports/dev/govtool-frontend](https://intersectmbo.github.io/govtool-test-reports/dev/govtool-frontend)
- **govtool-backend**: [https://intersectmbo.github.io/govtool-test-reports/dev/govtool-backend](https://intersectmbo.github.io/govtool-test-reports/dev/govtool-backend)

### Preview Environment
- **govtool-frontend**: [https://intersectmbo.github.io/govtool-test-reports/preview/govtool-frontend](https://intersectmbo.github.io/govtool-test-reports/preview/govtool-frontend)
- **govtool-backend**: [https://intersectmbo.github.io/govtool-test-reports/preview/govtool-backend](https://intersectmbo.github.io/govtool-test-reports/preview/govtool-backend)
- **nightly-govtool-frontend**: [https://intersectmbo.github.io/govtool-test-reports/preview/nightly-govtool-frontend](https://intersectmbo.github.io/govtool-test-reports/preview/nightly-govtool-frontend)
- **nightly-govtool-backend**: [https://intersectmbo.github.io/govtool-test-reports/preview/nightly-govtool-backend](https://intersectmbo.github.io/govtool-test-reports/preview/nightly-govtool-backend)

### Mainnet Environment
- **govtool-frontend**: [https://intersectmbo.github.io/govtool-test-reports/mainnet/govtool-frontend](https://intersectmbo.github.io/govtool-test-reports/mainnet/govtool-frontend)
- **govtool-backend**: [https://intersectmbo.github.io/govtool-test-reports/mainnet/govtool-backend](https://intersectmbo.github.io/govtool-test-reports/mainnet/govtool-backend)

### Boilerplate
- **web-app-boilerplate**: [https://intersectmbo.github.io/govtool-test-reports/web-app-boilerplate](https://intersectmbo.github.io/govtool-test-reports/web-app-boilerplate)


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
