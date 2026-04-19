# Nicholas Rico | Revenue & Commercial Operations Leader

Director of Revenue & Commercial Operations at [Vizgen](https://vizgen.com), a spatial genomics company competing in the single-cell and spatial biology market. I build the commercial data backbone that connects Salesforce, NetSuite, Tableau, HubSpot, and ZoomInfo into a single operating system for a global commercial org.

This repo is where I genericize that work into portable tools, ship AI-powered utilities, and prototype side projects.

## What I Do

I run RevOps as a one-person function supporting commercial teams across NAM, EMEA, and APAC. My job is to make the commercial machine legible, fast, and honest: pipeline you can trust, forecasts that hold up, territories that map cleanly to revenue, and systems that don't lie to each other.

I think in data flows and systems of record. I build with code when declarative tools run out of room, and I productize repeatable work so it scales past me.

## Current Stack

**CRM & Commercial Systems:** Salesforce (Flows, Validation Rules, Approval Processes, Apex-adjacent declarative dev), HubSpot, ZoomInfo, SciLeads
**Data & BI:** Tableau Cloud (Prep, Bridge, ODBC), NetSuite (SuiteAnalytics Connect), SQL, DuckDB
**Code:** Python (pandas, openpyxl, tableauserverclient, Anthropic API), HTML/JS, Excel (PowerQuery, dynamic arrays), Office JS Add-ins
**Integration & Infra:** Azure Static Web Apps, Azure AD, REST APIs, MCP servers, cron-driven ETL

## Featured Work

The projects here are generic, portable versions of patterns I've built in production. Vizgen-specific implementations stay at Vizgen; the reusable ideas live here.

**HubSpot to Salesforce Sync Auditor** _(in progress)_
Diagnostic tool that audits HubSpot to Salesforce sync health: surfaces lag, field mapping drift, duplicate creation patterns, and marketing-contact classification errors. Built against free developer accounts so anyone can run it.

**NetSuite to Tableau Connector Wizard** _(in progress)_
Walks a user through publishing NetSuite tables to Tableau Cloud via ODBC Bridge. Generates Custom SQL scaffolds for common transaction, address, and classification joins. Reduces a multi-day setup to under an hour.

**Excel JS Add-in for CRM Data Sync** _(in progress)_
Office JS add-in that pulls live Salesforce data into Excel with refresh-on-demand. Designed for the ops analyst who lives in spreadsheets and is tired of manual exports.

**AI-Powered RevOps Utilities** _(in progress)_
Small, sharp tools built on the Anthropic API: account classification, lead routing diagnostics, duplicate detection with fuzzy scoring, territory assignment explainers.

**NIH Funding Intelligence** _(earlier work)_
Python tool that queries NIH RePORTER and PubMed APIs to surface grant activity for life sciences commercial teams. Useful for biopharma account prioritization.

## Professional Background

**Director, Revenue & Commercial Operations** @ Vizgen (2026–Present)
Built the end-to-end commercial data stack for a 120-person spatial genomics company. Integrated Salesforce, NetSuite, Tableau, HubSpot, and ZoomInfo into a unified RevOps backbone. Designed territory models, commission plans, pipeline coverage frameworks, and executive dashboards. Shipped a 3-tier microsite strategy for board, territory, and deal-level intelligence.

**Manager, Sales Operations Analytics** @ Akoya Biosciences (2021–2026)
Led BI platform development across commercial and finance systems. Drove measurable gains in data processing speed and sales productivity.

**Sr. Demand Planner / Sr. Sales Analyst** @ SharkNinja (2016–2021)
Forecasting, demand planning, and QlikView automation for a high-velocity consumer products business.

## How I Think About RevOps

A few principles that show up in most of what I build:

- **Systems of record should disagree in public.** If Salesforce and NetSuite tell different stories, the reconciliation belongs in a dashboard, not in someone's head.
- **Human as middleware is a bug.** Anywhere a person copies data between systems is a place for automation or an integration.
- **Ship iteratively, instrument everything.** A rough v1 in production beats a perfect v3 in a deck.
- **Declarative first, code when it runs out.** Salesforce Flow before Apex. Tableau calc before custom SQL. But don't be afraid to drop into code.

## Contact

**LinkedIn:** [nicholas-rico-gauthier](https://www.linkedin.com/in/nicholas-rico-gauthier-97755a4b/)
**Email:** nickrgauthier@gmail.com

Happy to talk RevOps architecture, spatial biology commercial strategy, or side projects.
