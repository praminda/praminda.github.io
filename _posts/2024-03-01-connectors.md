---
layout: post
title: Data Connectors
site: https://www.macrometa.com/docs/connections
role: Lead Engineer
date: 2024-03-01
priority: 4
categories: [Data]
---

An ETL workflow framework on Macrometa GDN that automates data extraction, transformation, and loading between document collections and external sources. It supports log-based CDC and batch ingestion, schema inference, transformations using C8QL, and enables real-time data sync across Oracle, MySQL, PostgreSQL, MongoDB, Snowflake, and more.

**Key responsibilities:**
- Designed and implemented the workflow management and controller layer for Connection Workflows, including all external APIs for the controller that enable users to configure, trigger, and monitor data connector workflows.
- Contributed to the Meltano-based workflow execution and Argo Workflows orchestration layer. 
- Contributed to or owned many of the available connectors.
- Contributed to GUI development and debugging as needed.

**Languages**: `Java`, `Python`  
**Tools**:  
  - `Macrometa GDN` – storing data and executing transformations using stream workers
  - `Oracle`, `MySQL`, `MongoDB`, `PostgreSQL` – syncing records with each database
  - `Meltano` – ETL definition framework
  - `PyPI` – hosting connector packages: https://pypi.org/search/?q=macrometa-&o=
  - `Argo Workflows` – workflow orchestration engine
  - `React` – implementing required GUI components for the GDN console
