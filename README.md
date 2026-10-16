# Awesome-Test-Automation-RPA

## Top Test Automation & RPA Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Browser Automation, Desktop RPA & Acceptance Testing*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Test Automation & Robotic Process Automation (RPA)**. These tools automate repetitive digital tasks — clicking through web applications, filling forms, extracting data, and validating behavior — enabling both software testing and business process automation without manual intervention.

**Examples** include UiPath, Automation Anywhere, Blue Prism, Microsoft Power Automate, WorkFusion, Kofax RPA, Nintex, Pega Robotic Automation, Appian RPA, and AutomationEdge (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, Python-native automation, and transparent RPA workflows — ideal for teams prioritizing cost control, developers building automation pipelines, and organizations avoiding per-bot enterprise licensing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[UiPath](https://www.uipath.com/)**  
  The market-leading enterprise RPA platform with attended and unattended robots, AI-powered document understanding, and orchestrator for bot management. Pricing is per-bot annual licensing.

- **[Automation Anywhere](https://www.automationanywhere.com/)**  
  Enterprise RPA platform with cloud-native architecture, AI-powered IQ Bot for document processing, and Bot Insight analytics.

- **[Blue Prism](https://www.blueprism.com/)**  
  Enterprise RPA platform with centralized control room, process automation, and intelligent automation capabilities.

- **[Microsoft Power Automate](https://powerautomate.microsoft.com/)**  
  Microsoft's automation service with desktop RPA flows, cloud flows, and 1,000+ connectors. Integrated with Microsoft 365 and Dynamics 365.

- **[WorkFusion](https://www.workfusion.com/)**  
  Intelligent automation platform with RPA, machine learning, and pre-built bots for banking, insurance, and healthcare.

- **[Kofax RPA](https://www.kofax.com/)**  
  Intelligent automation platform with robotic process automation, document intelligence, and process orchestration.

- **[Nintex](https://www.nintex.com/)**  
  Process automation platform with RPA capabilities, workflow design, and document generation.

- **[Pega Robotic Automation](https://www.pega.com/)**  
  RPA capabilities within Pega Platform for automating repetitive tasks and integrating with Pega workflows.

- **[Appian RPA](https://appian.com/)**  
  RPA within Appian's low-code automation platform for end-to-end process automation.

- **[AutomationEdge](https://automationedge.com/)**  
  Hyperautomation platform combining RPA, IT automation, and AI for enterprise process automation.

## Open-Source GitHub Projects

- **[Robot Framework](https://github.com/robotframework/robotframework)**  
  **The leading generic open-source automation framework** for acceptance testing, ATDD, and RPA — 11,400+ GitHub stars . Uses **simple plain text syntax** that's readable by non-programmers, extensible with Python or Java libraries . Ecosystem includes **SeleniumLibrary** for browser automation, **AppiumLibrary** for mobile, and **RPA Framework** with 80+ libraries for desktop, Excel, database, and API automation . The top choice for teams building test automation and RPA on a single framework [citation:3][citation:6].

- **[OpenRPA](https://github.com/open-rpa/openrpa)**  
  **The closest open-source alternative to UiPath** — 2,900+ GitHub stars . Built on Windows Workflow Foundation with a visual drag-and-drop interface. Features browser automation, desktop automation, image recognition, and enterprise-grade security. Best for Windows-centric RPA deployments [citation:6][citation:17].

- **[TagUI](https://github.com/kelaberetiv/TagUI)**  
  **Free and open-source RPA tool for browser and desktop automation** — 6,200+ GitHub stars . Uses simple natural-language commands like `click`, `type`, `read` in plain text scripts. Strong browser automation support with Chrome and Firefox. Command-line focused; desktop application support is more limited than OpenRPA [citation:6][citation:10].

- **[Skyvern](https://github.com/Skyvern-AI/skyvern)**  
  **LLM and computer-vision driven browser RPA agent** — the AI-era alternative to UiPath and Automation Anywhere . Instead of XPath selectors, uses **natural language goals and task definitions** to drive real browsers. Handles unpredictable layouts, dynamic forms, and multi-step portals that traditional RPA struggles with . Ships with a managed cloud for scale, and the open-source core runs in Docker with any LLM provider [citation:13].

- **[Robocorp (Sema4.ai)](https://github.com/robocorp/robocorp)**  
  **Python-native RPA platform with open-source tools** . Provides **Robot Framework** extensions, a VS Code extension, and cloud orchestration. Robot structure follows a standard `robot.yaml` and `tasks.py` pattern. Acquired by Sema4.ai, positioning for AI-powered automation [citation:10].

- **[Taskt (sharpRPA)](https://github.com/saucepleez/taskt)**  
  **Free and open-source RPA tool built on .NET C#** — 1,300+ GitHub stars . Visual process designer for Windows automation scenarios. Element location accuracy is average on complex interfaces, and some features require further stability improvements [citation:6].

- **[Automagica](https://github.com/automagica/automagica)**  
  **Python-based RPA and automation platform** — 3,100+ GitHub stars . Clean API design suited for scripted automation of browsers, Excel, Word, and desktop applications. Command-line oriented; commercial use requires a license [citation:6][citation:17].

- **[Playwright](https://github.com/microsoft/playwright)**  
  **The dominant modern browser automation framework** for test automation. Cross-browser (Chromium, Firefox, WebKit) with **built-in auto-waiting** that eliminates most flaky-test debugging [citation:1]. Features **Trace Viewer** for CI failure debugging, network interception, and native parallelization. The foundation that Skyvern and other AI-RPA tools build upon.

- **[Selenium](https://github.com/SeleniumHQ/selenium)**  
  **The oldest and most language-agnostic browser automation framework.** Bindings for Java, Python, C#, Ruby, JavaScript, and more. Most new projects choose Playwright, but large established suites still run on Selenium. Best for legacy suites and non-JavaScript teams [citation:1][citation:11].

### Additional Strong Open-Source Options

- **SeleniumLibrary (Robot Framework)** — Selenium integration for Robot Framework, enabling browser automation with plain-text syntax [citation:3].
- **RPA Framework** — Robot Framework's collection of 80+ libraries for RPA, covering desktop, browser, Excel, databases, and APIs.
- **Cypress** — E2E testing framework with best-in-class local debugging and time-travel debugging [citation:1].
- **Puppeteer** — Chrome/Chromium-only browser automation from Google's Chrome team [citation:7].

**Frameworks for building custom systems**: Combine **Robot Framework** with **RPA Framework** and **SeleniumLibrary** for a unified test-and-RPA stack, **OpenRPA** for Windows desktop automation, **Skyvern** for AI-driven browser tasks requiring natural language, and **Playwright** for modern browser testing to build a complete open-source automation platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Test automation and RPA tools automate actions across web and desktop systems. **Automation of third-party services must comply with their terms of service** — scraping or automating sites without permission may violate ToS and anti-bot policies. Robotic process automation should be applied to repetitive, rule-based tasks and monitored for exceptions.
- Self-hosted open-source solutions require proper security hardening, credential management, and exception handling for production use.

---

**Made for QA engineers, test automation developers, RPA practitioners, and developers building automation platforms.**  
Let's make test automation and RPA more open, accessible, and intelligent.
