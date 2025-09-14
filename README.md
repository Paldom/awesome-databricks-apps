# Awesome Databricks Apps <!-- Can be published after 30 days [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) -->

> A curated list of awesome samples, starter projects, use-cases, software and resources for building, shipping and operating Databricks Apps.

[Databricks Apps](https://www.databricks.com/product/databricks-apps) enable you to build and deploy data and AI applications directly on the Databricks, with serverless hosting, built-in governance, security, and lakehouse-native data access. Use popular Python or Node.js frameworks to deploy apps directly on Databricks.

[Lakebase](https://www.databricks.com/blog/what-is-a-lakebase) is a fully managed, serverless PostgreSQL OLTP database with decoupled compute and storage, natively integrated with Databricks Apps and the lakehouse, delivering low‑latency transactions, elastic autoscaling, and zero‑copy database branching so you can have transactional and agentic workflows without managing infrastructure.

## Contents

- [Official Templates & Samples](#official-templates--samples)
- [Products / Utility tools hosted on Databricks Apps](#products--utility-tools-hosted-on-databricks-apps)
- [Demo Apps](#demo-apps)
- [Starter Repositories](#starter-repositories)
- [Solution Accelerators](#solution-accelerators)
- [Resources](#resources)
  - [Documentation](#documentation)
  - [Platform Services](#platform-services)
  - [Tooling, SDKs, CLI & Libraries](#tooling-sdks-cli--libraries)
  - [Tutorials, Guides & Learning Materials](#tutorials-guides--learning-materials)
  - [Use Cases](#use-cases)
  - [Blogs and Articles](#blogs-and-articles)
  - [Community](#community)

## Official Templates & Samples

One‑click starter apps maintained by Databricks. Clone locally, customize, and redeploy.

**Official Starters**

- [App Templates Collection](https://github.com/databricks/app-templates) - Complete collection of Databricks App templates across multiple frameworks.
- [Databricks Apps Examples](https://github.com/databricks-solutions/databricks-apps-examples) - Focused example apps illustrating common patterns (auth, env vars, Genie, warehouses).
- [Databricks Apps Cookbook](https://github.com/databricks-solutions/databricks-apps-cookbook) - Ready‑to‑use snippets and patterns for building interactive Databricks Apps.

**Streamlit**
- [Hello World](https://github.com/databricks/app-templates/tree/main/streamlit-hello-world-app) - Basic Streamlit app template.
- [Data App](https://github.com/databricks/app-templates/tree/main/streamlit-data-app) - Streamlit app for data exploration.
- [Data App (On‑Behalf‑Of user)](https://github.com/databricks/app-templates/tree/main/streamlit-data-app-obo-user) - Streamlit data app with OBO authentication.
- [Database App](https://github.com/databricks/app-templates/tree/main/streamlit-database-app) - Streamlit app with database connectivity.
- [Chatbot App](https://github.com/databricks/app-templates/tree/main/streamlit-chatbot-app) - Streamlit-based chatbot application.

**Dash**
- [Hello World](https://github.com/databricks/app-templates/tree/main/dash-hello-world-app) - Basic Dash app template.
- [Data App](https://github.com/databricks/app-templates/tree/main/dash-data-app) - Dash app for data visualization.
- [Data App (On‑Behalf‑Of user)](https://github.com/databricks/app-templates/tree/main/dash-data-app-obo-user) - Dash data app with OBO authentication.
- [Database App](https://github.com/databricks/app-templates/tree/main/dash-database-app) - Dash app with database connectivity.
- [Chatbot App](https://github.com/databricks/app-templates/tree/main/dash-chatbot-app) - Dash-based chatbot application.

**Gradio**
- [Hello World](https://github.com/databricks/app-templates/tree/main/gradio-hello-world-app) - Basic Gradio app template.
- [Data App](https://github.com/databricks/app-templates/tree/main/gradio-data-app) - Gradio app for data exploration.
- [Data App (On‑Behalf‑Of user)](https://github.com/databricks/app-templates/tree/main/gradio-data-app-obo-user) - Gradio data app with OBO authentication.
- [Chatbot App](https://github.com/databricks/app-templates/tree/main/gradio-chatbot-app) - Gradio-based chatbot application.

**Flask / FastAPI**
- [Hello World (Flask)](https://github.com/databricks/app-templates/tree/main/flask-hello-world-app) - Basic Flask app template.
- [Database App (Flask)](https://github.com/databricks/app-templates/tree/main/flask-database-app) - Flask app with database connectivity.

**R Shiny**
- [Hello World](https://github.com/databricks/app-templates/tree/main/shiny-hello-world-app) - Basic R Shiny app template.
- [Data App](https://github.com/databricks/app-templates/tree/main/shiny-data-app) - R Shiny app for data exploration.
- [Data App (On‑Behalf‑Of user)](https://github.com/databricks/app-templates/tree/main/shiny-data-app-obo-user) - R Shiny data app with OBO authentication.
- [Chatbot App](https://github.com/databricks/app-templates/tree/main/shiny-chatbot-app) - R Shiny-based chatbot application.

**Hybrid (Node.js + Python backend)**
- [Node.js + FastAPI Hello World](https://github.com/databricks/app-templates/tree/main/nodejs-fastapi-hello-world-app) - Hybrid app with Node.js frontend and Python backend.

**End‑to‑end Solutions**
- [E2E Chatbot App Template](https://github.com/databricks/app-templates/tree/main/e2e-chatbot-app) - Complete end-to-end chatbot application template.

## Products / Utility tools hosted on Databricks Apps

Full-featured applications and tools deployed as Databricks Apps.

- [KASAL](https://github.com/databrickslabs/kasal) - Build intelligent AI agent workflows with visual simplicity and enterprise power.
- [DBX Policy Builder](https://github.com/zcking/dbx-policy-builder) - Web application to create and manage Databricks cluster policies through a friendly UI.
- [StreamForge](https://github.com/harsha-pasala/streamforge) - Lakeflow StreamForge generates realistic streaming datasets and emits ready‑made Lakehouse pipelines.
- [Databricks WAF Light Tooling](https://github.com/AbhiDatabricks/Databricks-WAF-Light-Tooling) - Lightweight Well‑Architected Framework assessment tool for Databricks workspaces.
- [Visual Query Builder](https://github.com/fpatano/visualquerybuilder) - Modern visual SQL query builder for Unity Catalog with real‑time execution and profiling.
- [n8n on Databricks](https://github.com/hellomikelo/databricks-n8n) - Self-host n8n workflow automation platform as a Databricks App.

## Demo Apps

Example applications showcasing specific features and capabilities.

- [Multi-Genie Agent](https://github.com/ikidata/multi-genie-agent) - Demonstrates working with Databricks Genie via SDK using multiple frameworks.
- [Agent Monitoring Demo](https://github.com/databricks-solutions/agent-monitoring-demo-app) - FastAPI demo showing MLflow 3.0 trace‑based agent monitoring and evaluation.
- [Genie Voice API](https://github.com/Databricks-BR/genie-voice-api) - Interact with Genie via text or voice with optional RAG, built with FastAPI and React.
- [Exploring Code with Apps](https://github.com/databricks-industry-solutions/exploring-code-with-databricks-apps) - Example showing how to explore and summarize codebases using a Databricks App UI.
- [Engineering Recommendation Search](https://github.com/res-ds/eng-rec-search) - RAG search app with vector search and Streamlit UI, plus DAB‑based jobs.
- [Databricks Demos (Japanese)](https://github.com/komae5519pv/komae_dbdemos) - Collection of Databricks demo resources including Genie-Apps integrations.

## Starter Repositories

Templates and boilerplates to kickstart your Databricks Apps development.

- [FastAPI Starter](https://github.com/Paldom/databricks-apps-fastapi-starter) - FastAPI‑based starter template wired for Databricks Apps.
- [Claude Databricks App Template](https://github.com/databricks-solutions/claude-databricks-app-template) - Claude‑native template that scaffolds a multi‑user AI application.
- [Custom MLflow Review App](https://github.com/databricks-solutions/custom-mlflow-review-app) - Template for building custom MLflow review apps with trace views and SME labels.
- [Hackathon Starter Chatbot](https://github.com/srijitcn/hackathon_starter_chatbot) - LangChain‑based agent starter code for hackathons on Mosaic AI.
- [Simple Chatbot App](https://github.com/honnuanand/databricks-chatbot-app) - Simple chatbot example for querying data or documents.
- [Databricks Asset Bundles Example](https://github.com/DavidMorton/databricks-dab-example) - Minimal DAB skeleton that deploys a Databricks App.
- [Databricks DAB Demo](https://github.com/pdemeulenaer/databricks-dab-demo) - Demonstration of Databricks Asset Bundles structure and deployment.

## Solution Accelerators

Industry-specific and use-case focused solutions.

- [Genesis Workbench](https://github.com/databricks-industry-solutions/genesis-workbench) - Open‑source blueprint for Life Sciences with biological models/workflows and NVIDIA BioNeMo integration.
- [AWS DB Agent Workshop](https://github.com/AnanyaDBJ/aws-db-agent-workshop) - Workshop materials to build multi‑turn agents on Databricks Mosaic AI.
- [Automotive Geospatial Accelerator](https://github.com/databricks-industry-solutions/automotive-geospatial-accelerator) - Accelerator for automotive geospatial analytics (location and route analysis).

## Resources

### Documentation

- [Databricks Apps Documentation](https://docs.databricks.com/en/dev-tools/databricks-apps/index.html) - Official documentation for getting started with Databricks Apps.
- [Databricks SDK for Python](https://github.com/databricks/databricks-sdk-py) - Python SDK for Databricks including Apps support.
- [Databricks SDK Examples](https://github.com/databricks/databricks-sdk-py/tree/main/examples/apps) - Official examples from Databricks SDK.

### Platform Services

- [On‑Behalf‑Of (OBO) User Auth for Agents/Apps](https://docs.databricks.com/aws/en/generative-ai/agent-framework/authenticate-on-behalf-of-user) - Run with end‑user permissions.
- [Databricks Genie](https://docs.databricks.com/en/genie/index.html) - Natural language interface for data exploration.
- [Agent Bricks](https://docs.databricks.com/aws/en/generative-ai/agent-bricks/) - Agent Bricks simplifies building domain-specific AI agents, letting users focus on problems, data, and metrics instead of implementation.
- [Unity Catalog](https://docs.databricks.com/en/data-governance/unity-catalog/index.html) - Unified governance for data and AI.
- [Lakeflow Jobs](https://docs.databricks.com/aws/en/jobs/) - Schedule and orchestrate multi‑task data/ML workflows. 
- [Mosaic AI Model Serving](https://docs.databricks.com/aws/en/machine-learning/model-serving/) - Deploy and query models on serverless endpoints.  
- [Mosaic AI Gateway](https://docs.databricks.com/aws/en/ai-gateway/) - Centralized governance, rate‑limits, and observability for model/agent traffic.
- [Vector Search](https://docs.databricks.com/aws/en/generative-ai/vector-search) - Serverless vector database integrated with Unity Catalog.  
- [Lakehouse Monitoring](https://docs.databricks.com/aws/en/lakehouse-monitoring/) - Monitor tables and model inference quality at scale.
- [Secrets Management](https://docs.databricks.com/aws/en/security/secrets/) - Store credentials securely for apps and jobs.  
- [Service Principals](https://docs.databricks.com/aws/en/admin/users-groups/service-principals) - Non‑human identities for automation and CI/CD.  
- [Unity Catalog Volumes](https://docs.databricks.com/aws/en/volumes/) - Govern non‑tabular assets (files, configs, models) for apps.  

### Tooling, SDKs, CLI & Libraries

- [Databricks CLI](https://docs.databricks.com/en/dev-tools/cli/index.html) - Command-line interface for Databricks.
- [Databricks Asset Bundles](https://docs.databricks.com/en/dev-tools/bundles/index.html) - Bundle and deploy Databricks resources.
- [Jobs API](https://docs.databricks.com/api/workspace/jobs) - Programmatically create, run, and manage jobs. 
- [Serving Endpoints API](https://docs.databricks.com/api/workspace/servingendpoints) - Manage serving endpoints via REST.  
- [Create & Query Vector Indexes](https://docs.databricks.com/aws/en/generative-ai/create-query-vector-search) - How‑to for endpoints and indexes.
- [Sync UC tables to Lakebase](https://docs.databricks.com/aws/en/oltp/sync-data/sync-table) - Sync data from Unity Catalog tables to a database instance.
- [Secrets API](https://docs.databricks.com/api/workspace/secrets) - Manage secrets/scopes via REST.  
- [Secrets CLI](https://docs.databricks.com/aws/en/dev-tools/cli/reference/secrets-commands) - CLI for secret scopes and permissions.  
- [Work with Files in Volumes](https://docs.databricks.com/aws/en/volumes/volume-files) - Upload, browse, and create tables from files.
- [MLflow](https://mlflow.org/) - ML lifecycle management platform.

### Tutorials, Guides & Learning Materials

- [Custom MCP Server Hosting](https://docs.databricks.com/aws/en/generative-ai/mcp/custom-mcp) - How to host and connect custom or third‑party MCP servers as Databricks Apps.
- [Vibe Coding Your First Databricks App](https://medium.com/@AI-on-Databricks/vibe-coding-your-first-databricks-app-8d662f41b959) - Hands‑on guide using Dash, Agent Bricks, and AI/BI dashboards.
- [Creating Apps with Asset Bundles](https://medium.com/@macikgozm/creating-and-deploying-a-databricks-app-with-asset-bundles-d72ecfea36d2) - Series on creating and deploying Apps with Asset Bundles and CI/CD.
- [Building Custom MCP Servers](https://medium.com/@AI-on-Databricks/building-custom-mcp-servers-on-databricks-apps-a-practical-guide-48048480ce62) - Practical guide to implementing custom MCP servers.
- [Rapid Prototyping with n8n](https://medium.com/@AI-on-Databricks/rapid-prototyping-ai-systems-with-n8n-in-databricks-182ca146a26a) - Integrating n8n for visual orchestration of agents and MCP tools.
- [Multi-Agent Supervisor Application](https://medium.com/@kaustavpaul-007/building-a-multi-agent-supervisor-application-on-databricks-data-intelligence-platform-f696a4586572) - Tutorial on multi‑agent coordination using Agent Bricks.
- [Building an AI Application with Databricks Apps in 30 Days](https://hiflylabs.com/blog/2025/01/10/build-applications-on-databricks-apps) - Case study on building a production-ready AI app on Databricks Apps, covering architecture choices, CI/CD and scaling strategies.
- [Databricks Resources Collection](https://github.com/leighrobertson512/databricks_resources) - Curated links and examples for Databricks learning.

### Use Cases

- [PII Management App](https://medium.com/towards-data-engineering/databricks-apps-building-a-pii-management-app-on-databricks-d4b2f936af10) - Governance UI using Unity Catalog system tables for PII policies.
- [Reverse ETL with Lakebase](https://www.databricks.com/blog/reverse-etl-lakebase-activate-your-lakehouse-data-operational-analytics) - Syncing lakehouse tables to managed PostgreSQL for operational apps.
- [Using Lakebase as Transactional Layer](https://www.databricks.com/blog/how-use-lakebase-transactional-data-layer-databricks-apps) - Step‑by‑step guide to build Apps with Lakebase.
- [Productivity Boost Case Study](https://medium.com/appic-by-hiflylabs/how-databricks-apps-boosted-our-productivity-da5254485e25) - How Databricks Apps improved productivity of building GenAI tools.

### Blogs and Articles

- [VLDB 2025 Keynote on Lakebase](https://vldb.org/2025/files/keynote/vldb25-keynote3.pdf) - Matei Zaharia's presentation on bridging operational and analytical worlds.
- [Moving Beyond Silos with Lakebase](https://www.linkedin.com/pulse/moving-beyond-silos-why-lakebase-signals-shift-data-application-r8ynf/) - Opinion on Lakebase's impact on data applications.
- [Creating Annotation Apps](https://www.linkedin.com/pulse/how-create-annotation-app-using-databricks-apps-genai-daniel-baraldi-fh8qf/) - Building annotation apps with Databricks Apps and GenAI.
- [Lakebase and Transactions](https://www.linkedin.com/pulse/lakebase-databricks-apps-simple-way-add-transactions-your-lakehouse-e6bwc/) - Adding transactions to lakehouse via Lakebase.

### Community

- [Databricks Community Forum](https://community.databricks.com/) - Official Databricks community forum.
- [Reddit - r/databricks](https://www.reddit.com/r/databricks/) - Databricks subreddit.

## Contributing

Contributions are welcome! Before submitting, please:

1. Ensure the item is **relevant to Databricks Apps** and has a clear, useful README.  
2. Add **one link per PR**. This keeps reviews focused and fast.
3. Keep descriptions **short, one sentence**, starting with a capital letter and ending with a period.  
4. Place items in the **most specific section**.  
5. Avoid duplicates; check if a similar item already exists.  
6. Run linting & link checks locally - Use `npx awesome-lint` (see below) to pass CI.
7. Commit with a clear message and open a PR.  
8. (Nice‑to‑have) Review another open PR and leave actionable feedback.

See **[CONTRIBUTING.md](CONTRIBUTING.md)** for the full contributor guide.

### Validate with `awesome-lint`

```bash
# From the repo root:
npx awesome-lint
```
