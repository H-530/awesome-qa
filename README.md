# 🚀 Awesome QA (Quality Assurance) [![Awesome](https://awesome.re/badge-svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md)

> A curated and exhaustive list of software quality assurance (QA) engineering resources, tools, frameworks, automation stacks, and best practices.

---

## 📑 Table of Contents

- [Foundations & Theory](#-foundations--theory)
- [Web UI Automation](#-web-ui-automation)
- [Mobile Automation](#-mobile-automation)
- [API & Microservices Testing](#-api--microservices-testing)
- [Performance & Load Testing](#-performance--load-testing)
- [Security & Penetration Testing](#-security--penetration-testing)
- [Accessibility (a11y) Testing](#-accessibility-a11y-testing)
- [Visual & Cross-Browser Testing](#-visual--cross-browser-testing)
- [Behavior-Driven Development (BDD)](#-behavior-driven-development-bdd)
- [Test Management & ALM](#-test-management--alm)
- [Continuous Integration & DevOps (CI/CD)](#-continuous-integration--devops-cicd)
- [AI in Testing (QA & AI)](#-ai-in-testing-qa--ai)
- [Mocking, Stubs & Test Data Management](#-mocking-stubs--test-data-management)
- [Communities, Blogs & Learning](#-communities-blogs--learning)

---

## 🧠 Foundations & Theory
*Core concepts, international standards, methodologies, and quality principles.*

* [ISTQB Syllabus](https://www.istqb.org/) - International Software Testing Qualifications Board standards.
* [The Test Automation Pyramid](https://martinfowler.com/articles/practical-test-pyramid.html) - Martin Fowler's classic guide on test distribution.
* [Exploratory Testing (Satisfice)](https://www.satisfice.com/) - James Bach and Michael Bolton’s heuristics and methodologies.
* [Software Testing Help](https://www.softwaretestinghelp.com/) - Massive hub of theoretical and practical QA tutorials.
* [Ministry of Testing - Quality Criteria](https://www.ministryoftesting.com/) - Modern software testing definitions and paradigms.

---

## 🌐 Web UI Automation
*Modern frameworks and tools for End-to-End (E2E) browser testing.*

* [Playwright](https://playwright.dev/) - Fast, reliable, and multi-language modern E2E framework by Microsoft.
* [Cypress](https://www.cypress.io/) - JavaScript-based front-end testing tool built for modern web applications.
* [Selenium](https://www.selenium.dev/) - The industry-standard veterano for browser automation across multiple languages.
* [WebdriverIO](https://webdriver.io/) - Next-gen extensible automation framework for Node.js.
* [Puppeteer](https://pptr.dev/) - Node library providing a high-level API over Chrome/Chromium DevTools Protocol.
* [Nightwatch.js](https://nightwatchjs.org/) - End-to-end testing framework written in Node.js using the W3C WebDriver API.

---

## 📱 Mobile Automation
*Solutions for native, hybrid, and mobile web applications (iOS & Android).*

* [Appium](https://appium.io/) - Open-source cross-platform automation framework for native, hybrid, and mobile web apps.
* [Detox](https://wix.github.io/Detox/) - Gray-box E2E testing and automation framework for mobile apps (optimized for React Native).
* [Espresso](https://developer.android.com/training/testing/espresso) - Google's native Android UI testing framework.
* [XCUITest](https://developer.apple.com/library/archive/documentation/DeveloperTools/Conceptual/testing_with_xcode/chapters/04-writing_ui_tests.html) - Apple's native framework for iOS UI testing.
* [Maestro](https://maestro.mobile.dev/) - Painless and fast mobile UI automation framework.

---

## 🔌 API & Microservices Testing
*Backend, contract validation, and protocol testing (REST, GraphQL, gRPC, WebSockets).*

* [Postman](https://www.postman.com/) - The industry-standard collaboration platform for API development and testing.
* [RestAssured](https://rest-assured.io/) - Java DSL for simplifying testing and validation of REST services.
* [Pact](https://pact.io/) - World-leading Consumer-Driven Contract Testing framework.
* [Bruno](https://www.usebruno.com/) - Fast, git-friendly open-source API client.
* [Karate Framework](https://www.karatelabs.io/) - Unified tool combining API testing, mocks, performance, and UI via BDD syntax.
* [Insomnia](https://insomnia.rest/) - Collaborative API design and testing platform.

---

## ⚡ Performance & Load Testing
*Scalability, stress, endurance testing, and high-concurrency measuring.*

* [k6](https://k6.io/) - Developer-friendly open-source load testing tool written in Go (JavaScript/TypeScript scripts).
* [JMeter](https://jmeter.apache.org/) - Classic open-source application designed to load test functional behavior and measure performance.
* [Locust](https://locust.io/) - Python-based load testing framework where user behavior is defined with clean code.
* [Artillery](https://www.artillery.io/) - Modern performance and resilience testing toolkit for APIs and serverless apps.
* [Gatling](https://gatling.io/) - Highly capable load testing tool based on Scala, Akka, and Netty.

---

## 🔒 Security & Penetration Testing
*Vulnerability scanning, code analysis, and infrastructure safety.*

* [OWASP ZAP](https://www.zaproxy.org/) - The world's most widely used web app security scanner.
* [OWASP Top 10](https://owasp.org/www-project-top-ten/) - Standard awareness document representing critical web application security risks.
* [SonarQube](https://www.sonarqube.org/) - Continuous inspection of code quality and security vulnerabilities (SAST).
* [Trivy](https://aquasecurity.github.io/trivy/) - Comprehensive security scanner for containers, file systems, and CI/CD pipelines.

---

## ♿ Accessibility (a11y) Testing
*Ensuring digital inclusion, compliance (WCAG), and screen-reader friendliness.*

* [axe-core](https://www.deque.com/axe/) - Industry-leading accessibility engine for automated tests and CI/CD integration.
* [Lighthouse](https://developers.google.com/web/tools/lighthouse) - Google's automated auditing tool for performance, accessibility, and SEO.
* [Pa11y](https://pa11y.org/) - Automated accessibility testing tool running HTML_CodeSniffer.
* [WAVE](https://wave.webaim.org/) - Web accessibility evaluation tool for developers.

---

## 👁️ Visual & Cross-Browser Testing
*Detecting pixel regression, layout shifts, and visual anomalies.*

* [Applitools](https://applitools.com/) - AI-powered visual cloud testing and monitoring platform.
* [Percy](https://percy.io/) - Continuous visual review platform integrated into CI workflows.
* [BackstopJS](https://github.com/garris/backstopJS/) - Catch CSS regression pain with automated visual headless browser testing.
* [BrowserStack](https://www.browserstack.com/) - Cloud-based cross-browser and real device testing infrastructure.
* [Sauce Labs](https://saucelabs.com/) - Continuous testing cloud for web and mobile applications.

---

## 🥒 Behavior-Driven Development (BDD)
*Collaboration frameworks utilizing Gherkin syntax (Given-When-Then).*

* [Cucumber](https://cucumber.io/) - Open-source software supporting executable specifications in Gherkin language.
* [Behave](https://behave.readthedocs.io/) - Python BDD framework.
* [SpecFlow / SpecFlow-ecosystem](https://specflow.org/) - Leading .NET BDD bridge.

---

## 📊 Test Management & ALM
*Test case organizing, execution tracking, and QA metrics reporting.*

* [Allure Report](https://allure.qatools.ru/) - Flexible, lightweight multi-language test report framework with stunning web UI.
* [Xray](https://www.getxray.app/) - Native and robust test management tool integrated inside Jira.
* [TestRail](https://www.testrail.com/) - Comprehensive test management software for QA teams.
* [Zephyr Scale](https://smartbear.com/test-management/zephyr-scale/) - Enterprise-grade test management inside Jira.
* [Qase](https://qase.io/) - Modern test management platform with built-in TMS, test plan management, and reporting.

---

## 🔄 Continuous Integration & DevOps (CI/CD)
*Running tests automatically in delivery pipelines.*

* [GitHub Actions](https://github.com/features/actions) - Automate, customize, and execute software development workflows right in GitHub.
* [GitLab CI/CD](https://about.gitlab.com/stages-devops-lifecycle/continuous-integration/) - Built-in continuous integration and deployment pipelines.
* [Jenkins](https://www.jenkins.io/) - The extensible open-source automation server for CI/CD pipelines.
* [CircleCI](https://circleci.com/) - Fast and scalable cloud-based CI/CD platform.

---

## 🤖 AI in Testing (QA & AI)
*AI agents, self-healing code, test generator bots, and LLM automation assistants.*

* [Mabl](https://www.mabl.com/) - Intelligent low-code SaaS testing platform with automatic self-healing capabilities.
* [Testim](https://www.testim.io/) - AI-powered end-to-end testing with ML-driven locators and self-maintenance.
* [Qodo (CodiumAI)](https://www.qodo.ai/) - Intelligent code analysis and test-suite generation based on context.
* [Playwright CodeGen / AI Assistants](https://playwright.dev/) - Integrated AI toolsets for prompt-to-test and script generation.

---

## 🎭 Mocking, Stubs & Test Data Management
*Simulating unstable backends, third-party APIs, and managing isolated databases.*

* [WireMock](https://wiremock.org/) - Flexible API mocking library for stubbing and fault injection.
* [LocalStack](https://localstack.cloud/) - Fully functional local AWS cloud stack for offline integration testing.
* [MSW (Mock Service Worker)](https://mswjs.io/) - API mocking library using Service Worker interception for browser and Node.
* [Moxios / Nock](https://github.com/nock/nock) - HTTP server mocking and expectations library for Node.js.

---

## 🌐 Communities, Blogs & Learning
*Places to learn, connect, earn certifications, and stay ahead of trends.*

* [Ministry of Testing Club](https://www.ministryoftesting.com/) - Massive global community of software testers.
* [Test Automation University (TAU)](https://testautomationu.applitools.com/) - Free comprehensive learning paths and certificates on automated testing.
* [The Test Guild](https://testguild.com/) - Podcasts, expert interviews, and articles covering automation, AI, and performance.
* [Let's Code It](https://www.letskodeit.com/) - Hands-on courses focusing on QA automation and coding skills.

---

## 🤝 Contributing

Contributions are always welcome and greatly appreciated! 

Please check out the [Contributing Guidelines](CONTRIBUTING.md) before submitting a Pull Request.

### Rules for adding a resource:
1. Ensure the tool or resource is active, high quality, and industry-relevant.
2. Place it in alphabetical order within its respective category.
3. Keep descriptions concise, informative, and professional in English.

---

## 📜 License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
