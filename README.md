<h1 align="center">Abdul Wajid</h1>

<p align="center"> <strong>Full Stack Software Engineer · Applied AI Engineering</strong></p>

<p align="center">   Python · FastAPI · PHP · Laravel/Vue.js · Magento2/Adobe Commerce · SaaS · LLM/RAG </p>

<p align="center">
  <a href="https://abdulwajid.vercel.app/">Portfolio</a> ·
  <a href="https://www.linkedin.com/in/abdul-wajid-nasir/">LinkedIn</a> ·
  <a href="mailto:abdul.wajid.dev018@gmail.com">Email</a>
</p>

---

## About

Full Stack Software Engineer with 5+ years of hands-on experience in developing and maintaining back end systems, API's, Business Apps, Integrations & e-commerce.

My experience is built around PHP, Laravel & Magento/Adobe Commerce with complex business logic, 3rd party integration, migrations & debugging problems within production environments. My skills have been expanded to develop Python/FastAPI services, SaaS & AI Applications.

Outside of client projects I also create standalone products which include multi-tenancy, LLM integration, RAG, Structured Outputs & Web apps.

I enjoy solving the technical challenges involved in creating reliable software by ensuring business logic is correct, integrations are maintainable, failure is handled correctly & applications continue to function once deployed.

## Selected Projects

### Rapid Sales Force — AI-assisted multi-tenant SaaS

[Live Product](https://rapidsalesforce.live/)

An independent SaaS application, providing sales and business development teams with lead management, job opportunity, candidate profile and application systems using AI.

- Built PostgreSQL schemas for each tenant, backend API, different roles, lead workflows, candidate/resume systems.
- Developed AI assisted tools for analysing jobs, answering application questions, creating CVs and cover letters. These can be configured with different LLM providers.
- Background processing was implemented. This involved the use of Redis/BullMQ Queues, live updates and notification systems within the application.
- Deployment tools were worked on. These included Docker, NGINX, SSL, PM2, PostgreSQL, Redis, Azure and AWS.
- Working on Job Intelligence tools. These include evidence based resume analysis, resuming, source tracking and human review. This is currently being developed locally.

**Stack:** `Next.js` · `NestJS` · `TypeScript` · `TypeORM` · `PostgreSQL` · `Redis` · `BullMQ` · `Socket.io` · `Docker` · `Azure`

### CaptureSlate — Privacy-first recording and capture studio

[Live App](https://captureslate.vercel.app/) · [Downloads](https://captureslate.vercel.app/download)

Self-hosted application for screen, camera, presentaion, screenshot and local media recording and capture.

- Development of screen and camera recording tool that allows for parallel recording, device pre-flight, real-time canvas, presenter layout, annotation tools and privacy areas.
- Development of tools for reviewing recordings, trimming, rotating, exporting of recording, local transcription and browser/device compatibility.
- Implementation of PWA and offline functionality and automated end-to-end testing using Playwright.
- Set-up of Electron base, native save/export tools, Windows x64 release and Windows ARM64 packages.

**Stack:** `TypeScript` · `Vite` · `Media APIs` · `Canvas` · `MediaRecorder` · `PWA` · `Electron` · `Playwright`

### RAG Q&A API — Document-grounded question answering

A Python based FastAPI service that allows querying using document evidence.

- Document ingestion, chunking, context finding, and prompting was implemented.
- Used Pydantic models for request and responses, implemented validation for requests, and handling of missing context and failed providers.
- Responses were structured to give references to the documents used.

**Stack:** `Python` · `FastAPI` · `RAG` · `Embeddings` · `Pydantic` · `LLM APIs`

### Multi-Provider AI Integration

Integrated some Python based components to allow separation of application logic from specific LLM providers.

- Integrated and experimented with various providers such as OpenAI, Anthropic, Google Gemini, Groq and OpenRouter.
- Implemented configuration for the providers, common interface, request/responses, and failure handling.
- Experimenting with embedding, vector databases, semantic/hybrid search, re-ranking, tool calling and LangGraph.

**Stack:** `Python` · `FastAPI` · `LLM APIs` · `Pydantic` · `Provider Abstraction`

### Structured LLM Content Generation API

A FastAPI service to generate structured content using external language models.

- Defined request and response schemas using Pydantic and JSON Schema.
- Added validation for structured responses, re-try, timeouts and invalid responses.
- Logging implemented for requests, responses and errors to help identify issues with the providers.

**Stack:** `Python` · `FastAPI` · `Pydantic` · `JSON Schema` · `REST APIs`

## Professional Engineering Work

Client and production work included working with Laravel/Vue.js applications, Python services, Magento/Adobe Commerce, integration, application support.

### Laravel, Vue.js & Backend Systems

**LeadForcePro / Fusemind**

Laravel/Vue.js lead management application for regional operations, office territory, agent assignment, reporting and permissions.

- Regional, office and agent permissions implemented for lead listing, assignment and transfer.
- Territory and ZIP code validation implemented.
- Lead ownership protections implemented to stop agents from transferring leads that have not been resolved.
- Exporting leads into a single PDF. Up to 100 lead sheets can be exported.
- Lead distribution, notifications, Vue.js 3 stabilisation, reporting from SQL and production fixes.

**Application Modernization — FMRW, Eyemart & DataEntry**

- PHP/Laravel applications upgraded incrementally to PHP 8.3 and Laravel 12.
- Dependency conflicts, outdated code, and framework issues resolved.
- Business processes, deployment, and regression fixes validated.

**Demand Conversions — Third-party Integrations**

- Resware integration, Snowflake views and Microsoft OneDrive actions implemented into Laravel applications.
- API mapping, database processes, filtering of leads and integration issues.

### Python, FastAPI & Portal Integrations

**ASTEC Industries**

- Dealer and customer portal using Python/FastAPI.
- ButterCMS and Documoto integrated.
- Machine 360, product documentation, user groups, and SQL queries to find active/inactive machines.

### Magento / Adobe Commerce

Magento 2 development, upgrades, checkout, custom modules, integration and stabilisation.

Selected work includes:

- **Bizbox:** Upgraded to Magento 2.4.5-p1 from Magento 2.3. Shared checkout process for business.
- **K&N Filters:** Upgraded to Magento 2.4.3-p2 from Magento 2.3. Split into 3 modules (API, Frontend, Admin).
- **VVS:** Migrated from Drupal to Magento 2.4.5-p1. Custom shipping method.
- **Djurs Møbler:** Custom payment integration using a bank API.
- **Drugstore2Door:** Scripts for related products, upsells and category navigation.
- **CleanlineSurf:** Upgraded to Magento 2.4.3-p1 from Magento 2.3. Fixes for compatibility issues. Stabilisation.

Hyvä Theme integration for third party modules. Checkout and payment issues. Custom features for storefront. Multi-step sign-up forms. Dependency issues with Composer. Regression testing after release.

### Workflow Automation & Delivery

- Built n8n workflow to send customer support submissions to different Google Sheets depending on category. Notified owner via email.
- REST APIs, authentication/authorisation, RBAC, JWT/OAuth, SQL queries, background processes and integration with external services.
- Helped with code reviews, QA, Agile delivery, debugging issues in production, preparing for deployment, mentoring and working directly with clients.

## Technical Skills

**Python & Applied AI**
`Python` · `FastAPI` · `Pydantic` · `LLM APIs` · `RAG` · `Embeddings` · `Vector Search` · `Semantic/Hybrid Search` · `Reranking` · `Structured Outputs` · `JSON Schema` · `Prompt Engineering` · `LangGraph` · `Tool Calling` · `Provider Abstraction`

**Backend & Architecture**
`PHP 7/8` · `Laravel 12` · `NestJS` · `Node.js` · `REST APIs` · `MVC` · `Eloquent` · `Composer` · `Service Design` · `SaaS` · `Multi-Tenancy` · `RBAC` · `JWT/OAuth` · `Request Validation` · `Background Jobs`

**Frontend & Product Engineering**
`JavaScript` · `TypeScript` · `Vue.js 3` · `Next.js` · `React` · `HTML5` · `CSS3` · `Tailwind CSS` · `AJAX` · `jQuery` · `Knockout.js` · `Vite` · `Electron` · `Browser Media APIs` · `PWA`

**Magento / Adobe Commerce**
`Magento 2` · `Adobe Commerce` · `Custom Modules` · `Hyvä Theme` · `EAV/Catalog` · `Checkout` · `Payment/Shipping Integrations` · `Dependency Injection` · `Plugins & Observers` · `Service Contracts` · `XML Layouts` · `Platform Upgrades`

**Databases & Messaging**
`PostgreSQL` · `MySQL` · `SQL` · `Snowflake` · `Redis` · `RabbitMQ` · `BullMQ` · `Laravel Queues` · `TypeORM` · `Database Migrations`

**Infrastructure, Testing & Tooling**
`Docker` · `NGINX` · `AWS` · `Laravel Vapor` · `Azure` · `Envoyer` · `PM2` · `Git` · `Bitbucket` · `CI/CD` · `PHPUnit` · `Playwright` · `New Relic` · `n8n` · `Jira` · `Confluence`

**AI-assisted Development**
`OpenAI Codex` · `Claude Code` · `Cursor` · `Windsurf Cascade`

## Experience

**Nexius LLC — Lahore, Pakistan**

**Senior Software Engineer** · Jul 2021 – Nov 2026
- Developed backend and full stack applications using PHP/Laravel, Magento/Adobe Commerce, Python/FastAPI, APIs, integration and modernisation.
- Developed backend features, database driven applications, integration, debugging, testing and live support.

**Additional engagement:** Occasionally worked as a freelancer on Magento development and support for Bemeir LLC.

## Education

**BS Software Engineering**
University of the Punjab · 2017–2021

## Certifications

- [Adobe Certified Professional — Adobe Commerce Developer](https://certification.adobe.com/credential/verify/f0b96a0c-20f4-41eb-afce-3f57652fd913)
- [LLM Engineering — TestDome](https://www.testdome.com/certificates/1fb841065c134868a41c887ec798a126)
- [Prompt Engineering — TestDome](https://www.testdome.com/certificates/425622e7e4974da3a69fa39946ef0921)
- [Python — TestDome](https://www.testdome.com/certificates/5cb428afdca0403898955fb9cf96855b)
- [Python (Basic) — HackerRank](https://www.hackerrank.com/certificates/b49e7c93179f)
- [Problem Solving (Intermediate) — HackerRank Campus Club, AUFS](https://www.hackerrank.com/certificates/2091bfb6021f)
- [Problem Solving (Basic) — HackerRank](https://www.hackerrank.com/certificates/33744e4a879c)
- [PHP — TestDome](https://www.testdome.com/certificates/3216eef7004e4cd39d3868a71086bc9e)

## Contact

- **Portfolio:** [abdulwajid.vercel.app](https://abdulwajid.vercel.app/)
- **LinkedIn:** [linkedin.com/in/abdul-wajid-nasir](https://www.linkedin.com/in/abdul-wajid-nasir/)
- **Email:** [abdul.wajid.dev018@gmail.com](mailto\:abdul.wajid.dev018@gmail.com)
- **Location:** Lahore, Pakistan
- **Availability:** Remote full-time · Contract · Selected freelance work
