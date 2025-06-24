# Awesome Data-related MCP Services

> A curated list of modern-data-stack projects that expose a **Model Context Protocol (MCP)** server to enable LLMs / agents

As of June 2025, the list was created while doing a few hours of research/curation with help from `gpt-o3`.
Hoping to leverage the community to augment this list and keep it up to date in a fast-changing landscape.

Please contribute by adding new projects or updating existing ones, with relevant high-level details about the MCP server implementation.

## BI & Analytics
- **Apache Superset**
  - (Official) Superset Improvement Proposal [SIP-171: Model Context Protocol Service](https://github.com/apache/superset/issues/33870)
  - (Community-contributed) [superset-mcp](https://github.com/aptro/superset-mcp), implemented as an MCP-to-REST-bridge
- **Hex**: [hex-mcp](https://github.com/9elements/hex-mcp)
- **Lightdash** — [lightdash-mcp-server](https://github.com/syucream/lightdash-mcp-server)
- **Looker** — [Looker MCP Concept](https://www.getguru.com/reference/looker-mcp)

## Transformation & Orchestration
- **Airflow** - [mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow)
- **dbt Labs** — [dbt-mcp](https://github.com/dbt-labs/dbt-mcp)
- **Dagster**
  - [Accelerate Data Pipeline Development with Dagster Components](https://dagster.io/blog/accelerate-data-pipeline-development-with-dagster-components)
  - [mcp-server-dagster](https://github.com/kyryl-opens-ml/mcp-server-dagster)
- **Prefect** - [mcp-prefect](https://github.com/allen-munsch/mcp-prefect)

## Data Integration / Sync
- **Airbyte**
  - [How we built an MCP Server to create data pipelines](https://airbyte.com/blog/how-we-built-an-mcp-server-to-create-data-pipelines)
  - [PyAirbyte MCP](https://github.com/quintonwall/airbyte-labs-pyairbyte-mcp)
- **Fivetran** — [mcp-fivetran demo server](https://infinitelambda.com/mcp-fivetran-package-server/)

## Data Catalog & Observability
- **DataHub** - [mcp-server-datahub](https://github.com/acryldata/mcp-server-datahub)
- **Secoda** — [Secoda MCP Server](https://docs.secoda.co/features/ai-assistant/secoda-mcp-server)
- **Monte Carlo Data** — [MCP Quick-Start Guide](https://www.montecarlodata.com/blog-model-context-protocol-mcp)

## Databases
- **Snowflake**
  - [Quickstart: Build an MCP Server for Cortex Agents](https://quickstarts.snowflake.com/guide/mcp-server-for-cortex-agents/index.html)
  - [snowflake-mcp](https://github.com/davidamom/snowflake-mcp)
  - [sfguide-mcp-cortex-agents](https://github.com/Snowflake-Labs/sfguide-mcp-cortex-agents)
- **MotherDuck / DuckDB** — [mcp-server-motherduck](https://github.com/motherduckdb/mcp-server-motherduck)
- **BigQuery** - [mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery)

## Contributing
1. Add the project under the correct heading.  
2. Keep descriptions short and include at least one public link.  
3. Alphabetize entries within each section.
