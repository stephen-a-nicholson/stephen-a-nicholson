# Stephen Nicholson

I've been a data engineer for most of my career, and for the last couple of years I've been building Databricks platforms on Azure, which in practice means Terraform, Unity Catalog, private networking, and CI/CD that the client's own team can run after I've gone. Before that I spent a few years at NatWest working on Spark pipelines and fraud detection, with a mix of banking, fintech and consulting work on AWS and on-prem either side of it.

I write about data engineering, AI, Terraform and architecture on [LinkedIn](https://www.linkedin.com/in/stephen-nicholson/), and I've been a Databricks Champion since March 2026.

## Projects

**[databricks-platform-ops-agent](https://github.com/stephen-a-nicholson/databricks-platform-ops-agent)**
Audits Databricks Terraform for security, standards and platform misconfigurations, and explains why each one matters. Runs locally or as a GitHub Action on every pull request, no cloud credentials needed.

**[agent-factory](https://github.com/stephen-a-nicholson/agent-factory)**
A Databricks Declarative Automation Bundle that turns one `domain.yml` into a deployed Genie agent and a RAG agent, with evaluation gating promotion, rollback and observability. Includes a standalone quality-gates package that blocks a bundle from deploying when it breaks the rules.

**[databricks-dev-containers](https://github.com/stephen-a-nicholson/databricks-dev-containers)**
Local PySpark development in VS Code with Dev Containers, Databricks Connect and a CI/CD pipeline, so production code lives in `.py` files under version control rather than notebooks.

If you're working on similar problems I'm always up for comparing notes.
