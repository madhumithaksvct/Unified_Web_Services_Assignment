# Unified_Web_Services_Assignment
# QA Engineer Practical Assessment – Madhumitha K

## Candidate Name
Madhumitha K

## Tools and Frameworks Used (Completed Tasks)

| Category | Tools / Frameworks |
|----------|---------------------|
| Manual Testing | Microsoft Excel |
| Automation Testing | Java, Selenium WebDriver, TestNG, Maven, WebDriverManager |

## Tasks Completed

- [x] **Task 1:** 25 manual test cases for Claude.ai – `claude_testcases.xlsx`
- [x] **Task 2:** Automation scripts for SauceDemo (login, checkout, locked user test) – `sauce_demo_automation/`
- [ ] **Task 3:** Performance testing (ReqRes API) – *in progress / will be added soon*

## How to Run Automation Tests (Task 2)

### Prerequisites
- Java JDK 17+
- Maven
- Chrome browser

### Steps
1. Go to the `sauce_demo_automation` folder.
2. Run `mvn clean test` (or use IDE: right-click `testng.xml` → Run as TestNG Suite).
3. Test report is generated in `test-output/index.html`.

## How to Run Load Tests (Task 3 – Not Yet Completed)

*This section will be updated once the JMeter/k6 test is finished.*

## Assumptions & Issues Faced (For Completed Tasks)

### Assumptions
- Claude.ai test cases assume a free account is available; UI element names may vary.
- Automation tests use Chrome and WebDriverManager – no manual driver setup.

### Issues Faced & Resolutions
| Issue | Resolution |
|-------|-------------|
| Checkout test failed due to slow cart loading | Added explicit `WebDriverWait` for cart badge and checkout button. |
| Writing 25 unique test cases | Structured by module (Login, Signup, Conversation, File Upload, History, Settings, Edge). |

## Repository Structure
