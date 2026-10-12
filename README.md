# Awesome-Energy-Utilities-CRM

## Top Energy & Utilities CRM Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Utility Customer Management, Billing & Field Operations*  

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Energy & Utilities CRM**. These tools help utilities, retail energy suppliers, and mini-grid operators manage customer relationships, billing cycles, meter data, field service operations, and clean energy programs.



**Examples** include Salesforce Energy and Utilities Cloud, Oracle Utilities Customer Cloud, SAP for Utilities, Hansen Technologies, Gentrack, SEW Smart Customer Mobile, Uplight, VertexOne, Fluentgrid, and Agility CIS (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, smart meter integration, and open utility management — ideal for utilities, mini-grid operators, and developers seeking transparent, vendor-independent customer management solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Energy & Utilities Customer Information System (CIS) and CRM market is valued between **$2 billion and $10 billion** (scaling past **$20 billion** by the 2030s, driven by smart metering, DER integration, and grid modernization). The sector is **moderately fragmented**: while legacy enterprise titans (Oracle, SAP, and Salesforce) dominate large-scale utility operations, regional regulatory variations, retail deregulation, and modern composable architectures have fostered specialized high-growth mid-market competitors and digital customer-engagement platforms.

## SaaS/Hosted Platforms

| Platform | Company Size (Revenue / Valuation) | Pricing | Free Tier / Trial Limit | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Oracle Utilities Customer Cloud](https://www.oracle.com/utilities/)** | **~$415B–$440B Valuation** (~$57B–$67B FY25/26 Rev) | Tiered SaaS from **$1.00 – $3.00/billable customer/month** (enterprise subscription base) | **30-day trial** via Oracle Cloud Free Tier ($300 cloud credits; production CCS requires sales-provisioned PoC sandbox) | Comprehensive customer information system (CIS) and billing platform for utilities. Features meter-to-cash processing, customer self-service, and integration with Oracle Utilities applications. |
| **[SAP for Utilities](https://www.sap.com/industries/utilities.html)** | **~$220B–$245B Valuation** (~€37B–€38B+ FY25/26 Rev) | Entry RISE/Cloud packages from **~$2,000 – $5,000/FUE/year** (or volumetric Point of Delivery rates) | **30-day free trial** for SAP Cloud for Energy / S/4HANA Cloud (guided tour with sample utility data; extendable up to 90 days on SAP BTP) | Enterprise solution for utility customer management, billing, and device management. Integrated with SAP S/4HANA for financial and operational processes. |
| **[Salesforce Energy and Utilities Cloud](https://www.salesforce.com/energy-utilities/)** | **~$185B–$200B Valuation** (~$41.5B FY26 Rev) | Starting at **$350/user/month** (Starter Core) up to **$650–$700/user/month** (Service Max) | **30-day free trial** (pre-configured environment with sample utility data and guided workflows; no credit card required) | Purpose-built CRM for utilities and energy companies. Features Industries CPQ for rates and pricing, OmniStudio for guided workflows, Smart Utility Contact Centre, clean energy program management, and field service for utilities. |
| **[Uplight](https://uplight.com/)** | **$1.5B Valuation** (~$100M+ ARR) | Modular subscriptions starting from **$10,000/year** (custom-scoped utility base packages) | **14 to 30-day guided evaluation pilot / sandbox** upon request (no self-serve free-forever tier) | Customer energy engagement platform. Features personalized energy insights, demand response, and marketplace solutions for utilities. Backed by Schneider Electric and Octopus Energy. |
| **[Hansen Technologies](https://www.hansencx.com/)** | **~A$690M–$700M Market Cap** (~A$386M Annual Rev) | Modular enterprise CIS/billing deployments from **A$100,000+/year** (or A$0.50–$2.00/meter/year) | **Custom 30-day proof-of-concept (PoC)** environment for qualified utility operators (no public free tier) | Customer care and billing solutions for utilities and telecommunications. Features revenue management, meter data management, and customer engagement. |
| **[Gentrack](https://www.gentrack.com/)** | **~NZD $410M–$460M Market Cap** (~NZD $220M–$230M Annual Rev) | Custom deployment baseline starting from **NZ$500,000** (one-time deployment tier + recurring SaaS) | **Interactive guided product demo / 30-day pilot sandbox** arranged via sales (no self-serve free tier) | Utility billing and customer care platform. Features billing, CRM, meter data management, and market interaction for energy retailers. |
| **[VertexOne](https://www.vertexone.net/)** | **~$200M+ Valuation** (~$150M–$160M Annual Rev) | Directory baseline starting at **$1.00/user/month** (enterprise CIS contracts scale by connection/meter count) | **14 to 30-day utility proof-of-concept (PoC)** upon enterprise qualification (no public free tier) | Customer information system and billing platform for utilities. Features billing, CRM, and customer self-service supporting 400+ utilities. |
| **[SEW Smart Customer Mobile](https://www.sew.ai/)** | **~$100M–$150M Valuation** (~$50M–$80M ARR) | Private enterprise offers starting from **$25,000–$50,000/year** (scaled by customer connection volume) | **30-day enterprise pilot / staged demo sandbox** upon request via AWS Marketplace / direct sales (no public free tier) | Digital customer engagement platform for utilities. Features mobile app, self-service portal, and omnichannel communication. |
| **[Fluentgrid](https://www.fluentgrid.com/)** | **~₹700M–₹1,000M Valuation** (~₹200M–₹220M Annual Rev) | Modular packages starting from **₹500,000+/year** (~$6,000/year base depending on consumer footprint) | **30-day tailored proof-of-concept / demo sandbox** for municipal and regional utilities (no public free tier) | Smart utility solutions including customer management, billing, and field service management. |
| **[Agility CIS](https://www.agilitycis.com/)** | **~$150M–$200M Valuation** (Tally Group / SilverTree PE; ~$25M–$40M Rev) | Tiered meter/retailer baseline starting from **$30,000/year** (custom volumetric rates per consumer) | **30-day guided proof-of-concept / demo access** upon sales consultation (no public free tier) | Customer information system for energy and utility retailers. Features billing, CRM, and market operations. |



## Open-Source GitHub Projects



- **[MicroPowerManager](https://github.com/EnAccess/micropowermanager-backend)**  

  Open-source management tool for decentralized utilities (Docker Hub, PHP 8.0/Laravel 11/Vue.js 2.6/MySQL 8.4) . Originally developed by INENSUS and first launched in 2020. Provides customer relationship management (CRM), comprehensive ticketing and maintenance system, and asset management for mini-grid operators. Integrates with Steamaco, Spark, Calin, and Stron smart meters .



- **[NeoBill](https://sourceforge.net/projects/solidstate/)**  

  Web-based customer management and billing solution for small & medium businesses (GPLv2, PHP 8.3/MySQL) . Features multi-user system, recurring billing for any asset or service, stock tracking, Stripe integration, UPS live rates, and auto-tracking. Designed for extreme performance and tight security.



- **[Mwanzo Flats Management System](https://github.com/Fredrickmureti/tenant-management-system)**  

  Modern tenant management and utility billing platform (React/TypeScript/Supabase) . Features admin dashboard for tenant management, billing cycles with meter readings and rates, payment tracking with balance auto-computation, and tenant self-service portal. Uses Supabase Auth with Row Level Security (RLS) ensuring tenants can only see their own data.



- **[InvoicePlane](https://github.com/InvoicePlane/InvoicePlane)**  

  Self-hosted open-source application for managing quotes, invoices, clients, and payments (48.9 MB, v1.7.1) . Provides CRM-like customer management, quotes with one-click client approval, customizable invoice templates, and PayPal integration. Suitable for small utilities and service providers.



- **[oomi-influx](https://pypi.org/project/oomi-influx/)**  

  Headless ETL tool that pulls 15-minute electricity consumption data from Oomi customer portal (Salesforce Experience Cloud) and writes directly to InfluxDB 2.x . No browser or GUI required — designed to run unattended on Raspberry Pi or Linux server. Replays browser HTTP calls to fetch consumption data.



- **[openMIC](https://github.com/GridProtectionAlliance/openMIC)**  

  Meter Information Collection system (C#, .NET 4.6+) . Interrogates multiple vendors' DFRs (Digital Fault Recorders) via IP/FTP, Modem RAS, or Modbus. Features scheduled interrogation, data organization, meter problem logging, and mobile-ready web app for status monitoring.



- **[3PhaseInsight](https://zenodo.org/records/21072541)**  

  Open-source data platform for energy analytics (PostgreSQL/Airflow/Dask/Parquet) . Ingests smart meter time-series data, maintains LV network topology, and runs Data Apps via Airflow DAGs. API serves results via FastAPI. Framework available as Python library (3phi-framework) for building custom analytics.



- **[metrify-smart-metering](https://github.com/kanhaiya-gupta/DataEngineering-metrify-smart-metering)**  

  Real-time smart meter data pipeline (Python/Kafka/Snowflake/Airflow/dbt) . Features scalable energy data processing with clean architecture, REST API, and enterprise monitoring. Docker and Kubernetes deployment available.



- **[dlms-bridge-mcp](https://pypi.org/project/dlms-bridge-mcp/)**  

  Bridge DLMS/COSEM smart-meter data to AI systems (Python, v0.1.1) . Parses IEC 62056 meter data and maps to modern systems with NIS2 and GDPR governance. MCP server for AI agent integration.



- **[aemo-mdff-reader](https://pypi.org/project/aemo-mdff-reader/)**  

  Fast, zero-dependency streaming reader for AEMO NEM12 and NEM13 metering files (Python, MDFF v2.6) . O(1) memory for millions of intervals, ~2M readings/sec on columnar fast path. Includes CLI, pandas/MySQL extras, and validation tools.



### Additional Strong Open-Source Options



- **[OpenPAYGO Token](https://github.com/EnAccess/OpenPAYGO-Token)** — Open-source token system for PAYGO functionality in energy products (MIT).

- **[OpenPAYGO Pass](https://github.com/EnAccess/OpenPAYGO-Pass)** — Enhanced PAYGO activation for areas without mobile money.

- **[Steama-Meter Package](https://github.com/inensus/Steama-Meter-Package)** — Steamaco meter integration for MicroPowerManager.

- **[Spark Meter Integration](https://github.com/EnAccess)** — Spark meter integration for MicroPowerManager.

- **[Open Smart Meter](https://github.com/search?q=open+smart+meter)** — Open-source GSM smart meter enabling affordable solar energy adoption.

- Community **n8n** workflows for utility billing automation and customer notifications.



**Frameworks for building custom systems**: Combine **MicroPowerManager** or **NeoBill** as the core utility CRM with **oomi-influx** or **metrify-smart-metering** for consumption data ingestion, **3PhaseInsight** for analytics, and **PostgreSQL** for persistence — creating a fully self-hosted, enterprise-grade energy utility CRM platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Energy utility CRMs handling customer and consumption data must comply with data protection regulations (GDPR, CCPA, etc.) and utility industry regulations.

- Self-hosted open-source solutions require proper security hardening, meter integration configuration, and ongoing maintenance for production reliability.



---



**Made for utility operators, energy retailers, mini-grid managers, and developers building transparent energy CRM solutions.**  

Let's make Energy & Utilities CRM more open, data-driven, and efficient.
