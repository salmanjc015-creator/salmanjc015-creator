# Hi there, I'm Mohammed Salman 👋
### Senior QA Automation Engineer / SDET | Playwright & TypeScript Specialist

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohammed-salman-331129175)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:salmanjc.015@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-salmanjc015--creator-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/salmanjc015-creator)

---

### 👨‍💻 Executive Summary
Results-driven **Senior QA Automation Engineer / SDET** with deep expertise in architecting resilient, production-grade test automation frameworks using **Playwright, TypeScript, and Playwright-BDD**. Specialized in mission-critical enterprise systems (Single Page Applications, Computer-Aided Dispatch & Fleet Management), designing maintainable Page Object Model (POM) architectures, eliminating test flakiness, and optimizing CI/CD test execution pipelines in Azure DevOps and GitHub Actions.

---

### 🛠️ Technical Competency & Tooling

| Domain | Technologies & Libraries |
| :--- | :--- |
| **Automation Frameworks** | Playwright, Playwright-BDD (Cucumber/Gherkin), Cypress, Selenium WebDriver |
| **Languages & Runtimes** | TypeScript, JavaScript (ES6+), Node.js, SQL |
| **Design Patterns & Architecture** | Page Object Model (POM), Action Composition, Custom Fixtures, Atomic State Handlers |
| **CI/CD & DevOps** | Azure DevOps Pipelines (YAML), GitHub Actions, Docker, Test Matrix Parallelization |
| **Test Synchronization & Resilience** | Custom Settle Guards (`loading-wrapper`, DOM masks), 4-Tier Click Escalation, Dynamic Waiters |
| **State Management** | Multi-Role Azure AD / SSO Session Caching (`storageState`), Token Expiry Auto-Refresh |
| **Reporting & Observability** | Allure Reports, Playwright HTML & Trace Viewer, Video/Screenshot Artifacts, MS Teams Webhooks |

---

### 💼 Featured Architecture & Real-World Projects

#### 1. Enterprise Event & Fleet Dispatch Automation Framework
> **Tech Stack:** Playwright · TypeScript · Playwright-BDD · Azure AD SSO · Azure DevOps · Allure
*Architected and maintained an end-to-end BDD automation framework for a large-scale, high-concurrency emergency dispatch and roadside fleet management platform.*

- **Eliminated SPA Flakiness:** Replaced arbitrary sleeps (`waitForTimeout`) with custom settle handlers that monitor React loading overlays (`loading-wrapper`, dynamic spin masks) and DOM readiness, achieving a **99%+ test pass rate**.
- **Container-Scoped Dialog Handling:** Solved complex pointer-event interception bugs where nested draggable React modals (e.g. Schedule Event, Location Verification) were blocked by background forms.
- **SSO Session Caching Architecture:** Designed automated authentication state caching (`storageState`) for Azure AD SSO across parallel test workers, **slashing test cycle runtimes by ~40%**.
- **Declarative BDD Scenario Refactoring:** Led the migration from fragile 14-step imperative UI scripts to clean, 3-step declarative business scenarios (`Given-When-Then`), dramatically improving scenario readability for business stakeholders.
- **Atomic React Component Setters:** Engineered resilient helpers for non-standard React Datepicker / Timepicker controls using keyboard navigation and input masking rather than brittle coordinate clicks.

#### 2. Playwright TypeScript BDD Enterprise Starter (Public Showcase)
> **Tech Stack:** Playwright · Playwright-BDD · TypeScript · GitHub Actions · Allure Reporting
*A production-ready reference architecture showcasing best practices for modern web automation.*

- Modular Page Object Model with decoupled locator dictionaries and business action delegates.
- Dynamic test data seeding and schema verification.
- Cross-browser test matrix execution (Chromium, Firefox, WebKit, Edge) via GitHub Actions CI pipeline.
- Rich failure artifact capture: Playwright Trace Viewer, step-level screenshots, and execution video logs.

---

### 📊 GitHub Activity & Highlights

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=salmanjc015-creator&show_icons=true&theme=radical&hide_border=true" alt="Salman's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=salmanjc015-creator&layout=compact&theme=radical&hide_border=true" alt="Top Languages" />
</p>

---

### 🎯 Core Engineering Principles & SDET Philosophy

1. **Zero Flakiness Culture:** Tests must only fail when there is a genuine product defect. Dynamic synchronization and condition polling always supersede arbitrary timeouts.
2. **Fast Feedback in CI/CD:** Parallel execution, headless runs, and authentication state reuse ensure engineers get test feedback in minutes, not hours.
3. **Living Documentation:** Gherkin scenarios are business specifications first and automation harnesses second. Clean, declarative BDD bridges the gap between Product, QA, and Engineering.

---

### 📬 Connect With Me

- **LinkedIn:** [linkedin.com/in/mohammed-salman-331129175](https://www.linkedin.com/in/mohammed-salman-331129175)
- **Email:** [salmanjc.015@gmail.com](mailto:salmanjc.015@gmail.com)
- **Location:** Open to Senior QA Automation Engineer / SDET opportunities (Australia & Remote)

---
*⭐️ Designed & maintained by Mohammed Salman*
