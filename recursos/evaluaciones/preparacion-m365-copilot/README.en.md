# Microsoft 365 Copilot Readiness Assessment

[Spanish](README.md) · [English](README.en.md)

![Microsoft 365 Copilot Readiness Assessment](banner-evaluacion-preparacion-m365-copilot.png)

An interactive tool for assessing an organization's readiness before deploying **Microsoft 365 Copilot**.

The assessment helps you:

- verify essential requirements;
- identify critical blockers;
- understand readiness by dimension;
- prioritize pending actions;
- and generate a simple report with the results.

> **Important:** The result is indicative and based on official Microsoft requirements, guidance, and recommendations. It does not constitute an official certification, a technical audit, or an automated validation of tenant configuration.

## Open the interactive assessment

**[Start the Microsoft 365 Copilot readiness assessment](https://aespese29.github.io/ia-toolbox/recursos/evaluacion-preparacion-m365-copilot/index.html)**

The assessment opens directly in your browser through GitHub Pages. You do not need to install applications, download files, or sign in.

You can also [view the `index.html` source file](./index.html) in the repository.

## What it includes

- 25 checks across five dimensions.
- Fixed responses: **Verified**, **In progress**, **Not started**, and **Not applicable**.
- Critical requirements that act as blockers.
- Overall score and score by dimension.
- Indicative readiness status.
- Detected blockers and recommended priorities.
- Supplementary module for assessing agent readiness.
- Results report that can be saved locally as a PDF.

## Dimensions assessed

### 1. Strategy and leadership

Objectives, executive sponsorship, responsible team, pilot scope, and success criteria.

### 2. Technical readiness

Licensing, identity, Exchange Online, application compatibility, update channels, and connectivity.

### 3. Security, data, and compliance

Permissions, access to information, data protection, auditing, and compliance controls.

### 4. Adoption and use cases

Pilot group, priority scenarios, champions, training, communication, community, and support.

### 5. Measurement and continuous improvement

Metrics, feedback, usage review, success stories, and criteria for expanding the deployment.

### Supplementary agent module

Assesses basic aspects of agent definition, knowledge, permissions, costs, publishing, and maintenance.

This module is optional and **does not change the main Microsoft 365 Copilot readiness result**.

## How scoring works

Each check uses a fixed response:

- **Verified:** 2 points.
- **In progress:** 1 point.
- **Not started:** 0 points.
- **Not applicable:** excluded from the calculation.

```text
Score = points earned / applicable points possible × 100
```

Essential requirements act as blocking controls. A high score does not compensate for an unresolved critical requirement.

## Readiness statuses

### Preparation required

At least one critical requirement remains unresolved.

### Preparation in progress

Critical requirements have been fully or partially addressed, but relevant elements are still missing before a controlled pilot can begin.

### Ready for pilot

The organization has the indicative conditions needed to begin a controlled pilot and measure its results.

### Ready to expand

The organization demonstrates a high level of readiness and can consider a controlled expansion using its governance and measurement criteria.

> Microsoft does not publish a universal score that certifies an organization's readiness level. The levels and thresholds in this tool are indicative criteria defined by IA Toolbox.

## Results report

At the end of the assessment, the following are displayed:

- overall status;
- indicative score;
- result by dimension;
- number of critical blockers;
- pending checks;
- recommended priorities;
- and, if the optional module is completed, the agent readiness result.

The **Save report as PDF** option opens the browser's print function. From there, you can select **Save as PDF**.

## Privacy by design

The assessment runs entirely in the browser.

- Responses are processed locally using JavaScript.
- No responses are sent to any server.
- No external forms, APIs, or databases are used.
- No cookies, `localStorage`, or `sessionStorage` are used.
- No analytics services are integrated.
- No names, email addresses, domains, files, or identifying information are requested.
- Responses disappear when the page is refreshed or closed.
- The report is generated and saved only on the user's device.

### Do not enter confidential information

The assessment only needs the status of each check. Do not enter or share:

- confidential organizational information;
- personal or identifying data;
- names of customers, people, projects, or departments;
- internal security configurations;
- credentials, keys, or access information;
- documents, screenshots, or corporate content;
- technical details that could reveal the tenant configuration.

## Scope and limitations

The result does not constitute:

- an official Microsoft certification;
- a technical or security audit;
- a regulatory compliance assessment;
- an automated validation of tenant configuration;
- or a guarantee of readiness to deploy Microsoft 365 Copilot.

To verify an environment's actual configuration, use official Microsoft tools and reports and carry out the appropriate technical, security, compliance, and adoption reviews.

## Official references

- [Microsoft Copilot Readiness Report](https://learn.microsoft.com/en-us/microsoft-365/admin/activity-reports/microsoft-365-copilot-readiness?view=o365-worldwide)
- [Microsoft Copilot adoption and onboarding guide for IT admins](https://learn.microsoft.com/en-us/microsoft-365/copilot/microsoft-365-copilot-enablement-resources)
- [Microsoft 365 Copilot adoption planning checklist](https://adoption.microsoft.com/en-us/copilot/essential-guide/plan/)
- [Microsoft 365 Copilot Adoption Playbook](https://www.microsoft.com/en-us/microsoft-365-copilot/copilot-adoption-guide)
- [Automated Readiness Assessment for Microsoft 365 Copilot and Agents](https://github.com/microsoft/m365-copilot-automated-readiness-assessment)

## Technical verification of version 1.0

Version 1.0 was reviewed to confirm that it:

- does not transmit or retain responses;
- does not use cookies or local or session storage;
- contains no submission forms;
- does not allow file uploads;
- does not integrate analytics services;
- does not request confidential information;
- and does not need identifying data to calculate the result.

**Technical verification date:** August 20, 2026.

## Resource structure

Create the structure from the **repository root**, avoiding repeating a folder name:

```text
ia-toolbox/
└── recursos/
    └── evaluacion-preparacion-m365-copilot/
        ├── README.md
        ├── index.html
        └── banner-evaluacion-preparacion-m365-copilot.png
```

All three files must be in the same folder.

## Publishing with GitHub Pages

Configure GitHub Pages with:

```text
Source: Deploy from a branch
Branch: main
Folder: /(root)
```

With this structure, the assessment will be available at:

```text
https://aespese29.github.io/ia-toolbox/recursos/evaluacion-preparacion-m365-copilot/index.html
```

## Use and contributions

This resource is part of **IA Toolbox**, a collection of practical materials about applied artificial intelligence, Microsoft 365 Copilot, and agents.

If you find something that needs updating or want to suggest an improvement, you can open an issue in the repository.

---

**Adrián Espés** · Microsoft MVP · M365 Copilot<br>
[adrianespes.com](https://adrianespes.com)

**Version:** 1.0<br>
**Published:** August 20, 2026
