# Test Plan

Project: QA Portfolio - Demo Testing
Platform: Web (demoqa.com recommended)
Prepared by: CyberDataCataProjects
Date: 2026-01-19

1. Purpose and Objectives
- Demonstrate structured manual testing: planning, designing test cases, executing, reporting bugs, and tracking test data.
- Provide artifacts suitable for interviews and initial team contributions.

2. Scope
In-scope: Core interactive UI elements (forms, buttons, links), basic workflows (form submission, file upload/download), input validation, navigation and accessibility checks.
Out-of-scope: Performance, security, and extensive cross-browser matrix (can be added later).

3. Test Approach
- Manual test cases organized by type: Smoke, Functional, Regression.
- Exploratory testing during test execution to discover edge cases.
- Use sample test data in test_data.csv.

4. Test Items
- Text Box (Forms)
- Buttons
- Links (including broken links)
- File upload/download
- Checkboxes and radio buttons

5. Test Types
- Smoke: basic sanity checks to ensure major flows work.
- Functional: feature-level tests for expected behavior.
- Regression: re-run critical tests after fixes.

6. Entry Criteria
- Demo site accessible and stable.
- Test cases reviewed.

7. Exit Criteria
- All smoke tests pass.
- No P0/P1 open defects.
- Test execution records updated.

8. Risks and Mitigations
- Demo site instability: schedule testing during low-traffic windows and document intermittent failures.
- Incomplete requirements: adopt exploratory testing and document assumptions.

9. Reporting
- Use BUG_REPORT_TEMPLATE.md for issues.
- Store execution results in SAMPLE_TEST_EXECUTION_REPORT.csv.

10. How I'd extend this
- Add automation (suggested stack: JavaScript + Playwright) for smoke/regression tests.
- Add GitHub Actions CI to run automation on push and PRs.
- Add HTML/JUnit reporting and Docker-based test runner for reproducible runs.
