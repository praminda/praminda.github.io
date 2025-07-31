---
layout: post
title: Data Connectors
site: https://www.macrometa.com/docs/connections
role: Lead Engineer
date: 2024-03-01
---

An ETL workflow framework on Macrometa GDN that automates data extraction, transformation, and loading between document collections and external sources. It supports log-based (CDC) and batch ingestion, schema inference, transformations using C8QL, and enables real-time data sync across Oracle, MySQL, PostgreSQL, MongoDB, Snowflake, and more.

I designed and implemented the workflow management and controller layer for Connection Workflows, including all external APIs for the controller. I also contributed to the Meltano-based workflow execution and Argo Workflows orchestration layer. Many of the available connectors are also my contributions.

- **Languages**: `Java`, `Python`  
- **Tools**:  
  - Macrometa GDN – Storing data and executing transformations using stream workers
  - Oracle/MySQL/MongoDB/PostgreSQL  – to sync records with each database
  - Meltano - ETL definition framework
  - pypi - to host connector packages https://pypi.org/search/?q=macrometa-&o=
  - Argo workflows - workflow orchestration engine
