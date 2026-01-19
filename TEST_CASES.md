# Sample Test Cases

Fields: ID | Title | Type | Priority | Preconditions | Steps | Expected Result

-- Smoke Tests --
TC-S-001 | Home page loads | Smoke | High | Demo site up | 1. Navigate to home page 2. Observe page loads within reasonable time | Home page content loads, key navigation present

TC-S-002 | Text Box: submit form | Smoke | High | Demo site up | 1. Open Text Box page 2. Fill required fields 3. Click Submit | Form submission shows entered data confirmation

-- Functional Tests --
TC-F-001 | Text Box: validate required email | Functional | High | Text Box page open | 1. Enter invalid email 2. Submit | Validation message shown; submission blocked

TC-F-002 | File Upload: accept valid file | Functional | Medium | Upload page open | 1. Choose a supported file 2. Upload | File uploads successfully and confirmation shown

-- Regression Tests --
TC-R-001 | Links: no broken links on main sections | Regression | High | Home page open | 1. Click primary links 2. Verify pages load | No broken links; pages reachable
