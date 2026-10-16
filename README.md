# Awesome-Business-Process-Automation-BPA

## Top Business Process Automation (BPA) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Workflow Orchestration, BPMN Modeling & Decision Automation*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Business Process Automation (BPA)**. These tools enable organizations to model, execute, and monitor business processes—from visual workflow designers for business analysts to code-first orchestration engines that scale to millions of process instances.



**Examples** include Pega, Appian, ServiceNow, Camunda, UiPath, IBM Cloud Pak for Automation, Microsoft Power Automate, Bizagi, Nintex, and Kissflow (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, BPMN execution, and open workflow engines—ideal for process engineers, automation teams, and developers seeking transparent, vendor-independent BPA infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Pega](https://www.pega.com/)**

  **AI-powered decisioning and workflow automation** with real-time decision management, customer journey orchestration, and predictive analytics. **The enterprise standard** for complex, regulated business processes.



- **[Appian](https://www.appian.com/)**

  **Low-code automation platform** with strong BPM and process mining capabilities. Features **Appian AI**, **Data Fabric**, and low-code development. **Nucleus Research "Leader"**.



- **[ServiceNow](https://www.servicenow.com/)**

  **Enterprise workflow platform** spanning IT, HR, customer service, and security operations. Features **Flow Designer**, **App Engine Studio**, and **IntegrationHub**. **The most comprehensive enterprise workflow platform**.



- **[Camunda Cloud](https://camunda.com/)**

  **Managed version of the open-source Camunda platform**. **The only open-source BPM engine that's been genuinely production-grade for a decade**. **BPMN 2.0 native**—process models are executable, not just documentation. **DMN decision tables** for business rules. **REST and gRPC APIs** for programmatic control.



- **[UiPath](https://www.uipath.com/)**

  **The leading RPA platform** with **attended and unattended robots**, **document understanding**, and **process mining**. **The standard for robotic process automation**.



- **[IBM Cloud Pak for Automation](https://www.ibm.com/products/cloud-pak-for-business-automation)**

  **Enterprise automation platform** combining **workflow, decisions, content, and RPA**. **Deep integration with IBM ecosystem**.



- **[Microsoft Power Automate](https://powerautomate.microsoft.com/)**

  **Microsoft's automation platform** with **400+ connectors**, **AI Builder**, and **desktop flows**. **The most accessible automation tool** for Microsoft 365 users.



- **[Bizagi](https://www.bizagi.com/)**

  **Digital process automation platform** with **BPMN modeling**, **process execution**, and **RPA integration**. **The most BPMN-native commercial platform**.



- **[Nintex](https://www.nintex.com/)**

  **Process automation platform** with **workflow, forms, RPA, and document generation**. **The most comprehensive no-code automation suite**.



- **[Kissflow](https://kissflow.com/)**

  **No-code workflow automation platform** for business users. **The most accessible BPA tool** for non-technical teams.



## Open-Source GitHub Projects



- **[Camunda Platform 7](https://github.com/camunda/camunda-bpm-platform)**

  **Open-source workflow and decision automation platform** (Apache-2.0) . **The only open-source BPM engine that has been genuinely production-grade for a decade**—**Camunda 7 is the "boring" choice in the best sense: BPMN 2.0 native, predictable, and widely understood by teams who've actually run it at scale** . **The Camunda 7 line remains supported through 2030**, which matters for long-lived enterprise process automation . **BPMN 2.0 native**—process models are executable, not just documentation. **DMN decision tables** for business rules. **REST and gRPC APIs** for programmatic control. **The reference implementation for BPMN workflow automation** .



- **[Camunda 8](https://github.com/camunda/camunda)**

  **The next-generation Camunda platform** (Apache-2.0) . **Cloud-native architecture** with **Zeebe engine** for horizontal scaling. **BPMN 2.0 and DMN** support. **Operate** for monitoring, **Tasklist** for human tasks, **Optimize** for analytics, **Identity** for access management. **The most scalable open-source workflow engine**—designed for high-throughput process orchestration .



- **[Flowable](https://github.com/flowable/flowable-engine)**

  **Open-source BPMN, DMN, and CMMN engine** (Apache-2.0) . **The most flexible open-source workflow engine**—supports BPMN 2.0, DMN 1.3, and CMMN 1.1. **Features**: **process engine**, **decision engine**, **case engine**, **form engine**, **content engine**, and **identity engine**. **The most comprehensive open-source BPM suite** with support for multiple modeling standards .



- **[Apache Activiti](https://github.com/Activiti/Activiti)**

  **Lightweight workflow and Business Process Management (BPM) platform** (Apache-2.0) . **The original open-source BPMN engine**—Activiti was the foundation for Camunda, which was forked in 2013. **BPMN 2.0 compliant** with **process engine**, **form engine**, and **REST API**. **The historical reference implementation** for open-source BPM .



- **[jBPM](https://github.com/kiegroup/jbpm)**

  **Business Process Management suite** (Apache-2.0) from the KIE Group (Red Hat) . **Features**: **BPMN 2.0**, **DMN**, **case management**, **process designer**, **form modeler**, **rules engine (Drools)**, and **planning engine (OptaPlanner)** . **The most comprehensive open-source BPM suite** for enterprise Java applications .



- **[Temporal](https://github.com/temporalio/temporal)**

  **Durable execution platform** (MIT) . **The modern alternative to traditional BPM engines**—**workflows are code, not diagrams** . **Features**: **durable execution** (workflows survive process restarts), **automatic retries**, **timeouts**, **signals**, **queries**, **child workflows**, and **versioning** . **Used by Netflix, Snap, and Stripe** for mission-critical orchestration . **The best choice for developer-centric teams** who want code-first workflows instead of visual BPMN modeling .



- **[Apache Airflow](https://github.com/apache/airflow)**

  **Platform to programmatically author, schedule, and monitor workflows** (Apache-2.0) . **The standard for data pipeline orchestration** . **Python-defined DAGs** with massive operator ecosystem . **Best for**: data engineering workflows, ETL pipelines, and scheduled batch processing—**not business process automation with human tasks** .



- **[n8n](https://github.com/n8n-io/n8n)**

  **Workflow automation platform with 400+ integrations** (Sustainable Use License) . **Fair-code licensed**—free for internal use, paid for SaaS resale. **Visual workflow builder** with **custom code nodes** for JavaScript/Python . **Best for**: lightweight integrations, API orchestration, and automation workflows that don't require formal BPMN modeling .



- **[Node-RED](https://github.com/node-red/node-red)**

  **Flow-based programming tool for wiring together hardware devices, APIs, and online services** (Apache-2.0) . **Visual flow editor** with **node palette** . **Best for**: IoT workflows, event-driven automation, and lightweight process orchestration .



- **[OpenBPM](https://github.com/openbpm/openbpm)**

  **Open-source BPM platform** (Apache-2.0) . **Features**: **BPMN 2.0 engine**, **form builder**, **process designer**, **dashboard**, and **REST API** . **The most modern open-source BPM platform** for business users .



- **[ProcessMaker](https://github.com/processmaker/processmaker)**

  **Open-source BPM and workflow automation platform** (GPL-3.0) . **Features**: **BPMN 2.0**, **form builder**, **case management**, **workflow designer**, and **REST API** . **Used by 5,000+ organizations** worldwide .



- **[Bonita](https://github.com/bonitasoft/bonita-engine)**

  **Open-source BPM platform** (GPL-2.0) . **Features**: **BPMN 2.0 engine**, **process designer**, **form builder**, **portal**, and **REST API** . **The most business-user-friendly open-source BPM platform** .



### Additional Strong Open-Source Options



- **[Zeebe](https://github.com/camunda/zeebe)** — **The engine behind Camunda 8** (Apache-2.0) . **Cloud-native, horizontally scalable workflow engine** designed for high-throughput process orchestration .

- **[Operaton](https://github.com/operaton/operaton)** — **Open-source fork of Camunda 7** (Apache-2.0) . **Community-driven continuation** after Camunda's pivot to Camunda 8 . **For teams that need to stay on the Camunda 7 architecture** .

- **[BPMN.io](https://github.com/bpmn-io)** — **Open-source BPMN toolkit** (MIT) . **The standard BPMN renderer and modeler** for web applications . **Used by Camunda, Flowable, and most open-source BPM tools** .

- **[DMN.io](https://github.com/bpmn-io/dmn-js)** — **Open-source DMN decision table toolkit** (MIT) . **The standard DMN renderer and modeler** .

- **[Drools](https://github.com/kiegroup/drools)** — **Business rules management system** (Apache-2.0) . **The standard open-source rules engine** for Java applications .

- **[Kogito](https://github.com/kiegroup/kogito-runtimes)** — **Cloud-native business automation** (Apache-2.0) . **The next-generation Drools/jBPM** for cloud-native deployments .

- **[Apache Camel](https://github.com/apache/camel)** — **Enterprise integration framework** (Apache-2.0) . **The standard for routing and mediation** between systems .

- **[Apache ServiceMix](https://github.com/apache/servicemix)** — **Open-source ESB** (Apache-2.0) . **The standard for enterprise service bus** architectures .

- Community **n8n** workflows for BPA integration and automation orchestration.



**Frameworks for building custom systems**: Combine **Camunda Platform 7** or **Flowable** for BPMN execution with **Temporal** for code-first durable workflows, **Drools** for business rules, **bpmn.io** for process modeling, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade BPA platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Business process automation platforms handling enterprise workflows must comply with data protection regulations (GDPR, CCPA, etc.) and industry-specific compliance requirements.

- **Open-source BPA is mature and production-ready.** Camunda Platform 7 is the only open-source BPM engine that's been genuinely production-grade for a decade . Flowable and jBPM provide comprehensive BPM suites . **These are genuine alternatives to Pega and Appian.**

- **Camunda 7 remains supported through 2030.** This matters for long-lived enterprise process automation—**Camunda 7 is the "boring" choice in the best sense: BPMN 2.0 native, predictable, and widely understood** . For teams that need to stay on this architecture, **Operaton** provides a community-driven fork .

- **BPMN vs. code-first: pick based on your team.** Camunda 7 and Flowable for BPMN-native visual modeling with business analyst involvement . Temporal for developer-centric code-first workflows without diagrams . **BPMN creates shared artifacts between technical and non-technical stakeholders—code-first optimizes for engineering velocity.**

- **The RPA vs. BPA distinction matters.** UiPath and Power Automate focus on **robotic process automation** (UI-level automation). Camunda and Flowable focus on **business process automation** (workflow orchestration with human tasks). **They solve different problems** —many organizations need both.

- Self-hosted open-source solutions require proper workflow engine management, decision modeling, and ongoing maintenance. **Business processes are critical infrastructure**—monitoring, alerting, and error handling are non-negotiable.



---



**Made for process engineers, automation teams, and organizations building transparent BPA solutions.**

Let's make Business Process Automation more open, data-driven, and BPMN-native.
