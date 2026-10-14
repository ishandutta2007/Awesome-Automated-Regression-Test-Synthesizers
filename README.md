# Awesome-Automated-Regression-Test-Synthesizers

## Top Automated Regression Test Synthesizers Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Test Generation, Self-Healing Locators & Record-to-Suite Automation*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Automated Regression Test Synthesizers**. These tools observe user actions, application behavior, and code changes to auto-generate maintainable regression test suites—reducing the manual effort of writing and updating tests as applications evolve.



**Examples** include OctoPerf, mabl, Testim, Diffblue, Qodo (CodiumAI), Functionize, QA Wolf, Applitools, Tricentis, and Katalon (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, AI-driven test generation, and open self-healing frameworks—ideal for QA engineers, developers, and teams seeking transparent, vendor-independent test automation.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[OctoPerf](https://octoperf.com/)**  

  Load testing platform with AI-powered test generation from recorded user sessions. Features JMeter-compatible test creation, real-time analytics, and cloud load generation.



- **[mabl](https://www.mabl.com/)**  

  AI-native test automation platform with auto-healing tests, intelligent wait times, and visual regression detection. Creates tests from recorded browser interactions with minimal code.



- **[Testim](https://www.testim.io/)**  

  AI-powered test automation with self-healing locators and smart assertions. Records user actions to generate stable tests that adapt to UI changes.



- **[Diffblue Cover](https://www.diffblue.com/)**  

  Autonomous unit test generation for Java using reinforcement learning. Writes and maintains entire regression suites for existing codebases.



- **[Qodo (CodiumAI)](https://www.qodo.ai/)**  

  AI-powered test generation and code review. Features Qodo Gen for IDE test generation, Qodo Merge for PR analysis, and Qodo Cover for coverage-driven test synthesis.



- **[Functionize](https://www.functionize.com/)**  

  AI-powered test automation with natural language test creation, self-healing, and autonomous test maintenance.



- **[QA Wolf](https://www.qawolf.com/)**  

  Human-assisted test automation service creating Playwright test suites for web applications. Combines AI generation with QA engineer oversight.



- **[Applitools](https://applitools.com/)**  

  Visual AI testing platform with automated visual regression detection. Features Ultrafast Test Cloud and root-cause analysis for visual differences.



- **[Tricentis](https://www.tricentis.com/)**  

  Enterprise test automation with model-based testing and AI-driven test generation. Features Tosca for codeless automation and qTest for test management.



- **[Katalon](https://katalon.com/)**  

  Test automation platform with AI-powered test generation, self-healing, and cross-platform testing. Features StudioAssist for AI test creation and TestOps for orchestration.



## Open-Source GitHub Projects



- **[Test-Agent](https://github.com/codefuse-ai/Test-Agent)**  

  Open-source AI test agent from CodeFuse (Apache-2.0). Features **TestGPT-7B** model (based on CodeLlama-7B) for unit test generation, **TestModel** for generating test cases from code, and **TestAgent** for IDE integration. Provides VS Code extension and web UI. The most substantial open-source effort specifically targeting unit test synthesis .



- **[Keploy](https://github.com/keploy/keploy)**  

  Open-source API and integration test generation platform (Apache-2.0). Records real user traffic and converts it into **deterministic test cases with data mocks**. Features automatic dependency mocking, no code changes required, and support for Go, Java, Node.js, Python, and Rust. Tests run in CI/CD pipelines. 3,000+ GitHub stars. **The strongest open-source option for API-level regression test synthesis** .



- **[EvoSuite](https://github.com/EvoSuite/evosuite)**  

  Automatic test suite generation for Java classes (LGPL-2.1). Uses **search-based software testing** (genetic algorithms) to evolve test suites that maximize code coverage and mutation score. Generates JUnit-compatible tests. Mature research-backed tool with 2,000+ GitHub stars. **Industry standard for automated unit test generation in Java** .



- **[Randoop](https://github.com/randoop/randoop)**  

  Automatic random test generation for Java (MIT). Feedback-directed random testing that generates unit tests detecting contract violations and exceptions. Actively maintained by the University of Washington. Complements search-based approaches like EvoSuite .



- **[Diffblue Cover (Community Edition)](https://www.diffblue.com/community-edition/)**  

  Free community edition of Diffblue's Java test generator. Reinforced learning-based test generation for IntelliJ IDEA. Commercial licensing for enterprise features.



- **[PIT (Pitest)](https://github.com/hcoles/pitest)**  

  Mutation testing system for Java and JVM (Apache-2.0). Not a test generator itself, but essential for evaluating generated test quality. Reports mutation coverage to identify weak tests. Integrates with Maven, Gradle, and CI pipelines.



- **[Pytest-testmon](https://github.com/tarpas/pytest-testmon)**  

  Pytest plugin for **test impact analysis** (MIT). Selects and runs only tests affected by code changes. Significantly reduces regression test execution time in CI. Complements test generation by optimizing which tests to run .



- **[Hypothesis](https://github.com/HypothesisWorks/hypothesis)**  

  Property-based testing library for Python (MPL-2.0). Generates test cases from specifications rather than examples. Finds edge cases humans miss. Foundation for regression test synthesis in Python projects .



- **[Schemathesis](https://github.com/schemathesis/schemathesis)**  

  Property-based API testing from OpenAPI/GraphQL schemas (MIT). Automatically generates test cases that find crashes, validation errors, and spec violations. Complements Keploy for API regression testing .



- **[Playwright Codegen](https://github.com/microsoft/playwright)**  

  Built-in code generator in Playwright (Apache-2.0). Records browser interactions and outputs runnable Playwright test code. Foundation for record-to-suite workflows. Supports Chromium, Firefox, and WebKit.



- **[Selenium IDE](https://github.com/SeleniumHQ/selenium-ide)**  

  Browser extension for recording and playing back Selenium tests (Apache-2.0). Exports to multiple languages. Classic record-and-replay tool for regression test creation.



### Additional Strong Open-Source Options



- **[CodeceptJS](https://github.com/codeceptjs/CodeceptJS)** — End-to-end testing framework (MIT) with AI-powered locators and scenario-driven test generation.

- **[Cucumber](https://github.com/cucumber/cucumber-js)** — BDD framework (MIT) for writing executable specifications that become regression tests.

- **[Robot Framework](https://github.com/robotframework/robotframework)** — Generic test automation framework (Apache-2.0) with keyword-driven test generation.

- **[Gauge](https://github.com/getgauge/gauge)** — Lightweight cross-platform test automation (Apache-2.0) with Markdown-based specifications.

- **[Jest](https://github.com/jestjs/jest)** — JavaScript testing framework (MIT) with snapshot testing for regression detection.

- **[Vitest](https://github.com/vitest-dev/vitest)** — Vite-native test framework (MIT) with snapshot and coverage support.

- Community **n8n** workflows for test result aggregation and regression alerting.



**Frameworks for building custom systems**: Combine **Keploy** for API test synthesis from traffic with **EvoSuite** or **Randoop** for Java unit test generation, **Test-Agent** for AI-powered IDE test creation, **Schemathesis** for property-based API testing, and **PIT** for mutation-quality validation—creating a fully self-hosted, enterprise-grade regression test synthesis platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Test synthesis tools generating code must be reviewed before committing to production repositories. Generated tests can encode incorrect assumptions or miss critical edge cases.

- **Generated tests are not automatically good tests.** Coverage metrics (line, branch) can be gamed by trivial assertions. Mutation testing (PIT, Stryker) provides stronger signal—a test suite that kills mutants is more likely to catch real regressions. Pair generation with mutation analysis for meaningful quality assessment.

- **Record-and-replay tests are fragile.** UI-based tests break when selectors, timing, or DOM structure change. Self-healing locators (mabl, Testim) reduce but don't eliminate maintenance. API-level tests (Keploy, Schemathesis) are generally more stable than UI tests.

- **AI test generation is probabilistic.** Models may produce tests that pass but don't actually validate behavior, or that hardcode expected values from the current implementation rather than from the specification. Human review of generated assertions remains essential.

- Self-hosted open-source solutions require proper security hardening, CI/CD integration, and ongoing maintenance. Test data may contain PII—ensure generated mocks and fixtures comply with data protection regulations.



---



**Made for QA engineers, developers, DevOps teams, and organizations building transparent test automation solutions.**  

Let's make Automated Regression Test Synthesis more open, data-driven, and reliable.
