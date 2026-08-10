<div align="center">

# Hi, I'm Aniket Dwivedi 👋

### The Data Guy 🛠️ — Data Engineer · Data Architect · Governed Lakehouse Platforms — with serious BI skills on top

**Data & AI Evangelist · AVP / Solutions Architect, Chief Data Office @ DWS Group (Deutsche Bank)** · Pune, India

<p>
  <a href="https://www.linkedin.com/in/dwivedianiket/"><img src="https://img.shields.io/badge/LinkedIn-dwivedianiket-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.aniketdwivedi.com"><img src="https://img.shields.io/badge/Website-aniketdwivedi.com-2E7D32?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="mailto:aniket.dwivedi@icloud.com"><img src="https://img.shields.io/badge/Email-aniket.dwivedi@icloud.com-0071E3?style=for-the-badge&logo=icloud&logoColor=white" alt="Email"></a>
</p>

</div>

---

## 🚀 About Me

- 🔧 **15+ years as a Data Engineer & Data Architect** — ETL/ELT pipelines in **Python · PySpark · SQL/PL-SQL · Alteryx** over **Snowflake, Databricks, Oracle, Teradata** and Big Data back ends, for global banking, asset management & financial services (DWS/Deutsche Bank, JPMorgan Chase, Emerson)
- 🏗️ **Data platform architect** — dimensional, Data Vault 2.0 and data-vault modelling, data marts/warehouses, conformed dimensions & certified datasets; lakehouse on **Microsoft Fabric (OneLake) & Azure**; federated SQL with **Starburst/Trino**; REST-API ingestion & automation
- 🛡️ **Governed by design (DAMA CDMP)** — Collibra glossary, lineage & stewardship, data-quality rules, MDM and "data-as-an-asset" operating models for a Chief Data Office
- 📊 **BI when the data's ready to talk** — 5× Tableau-certified architect running **500+ workbook** estates (RLS, performance tuning, Server-to-Cloud migration); Power BI & CRM Analytics
- 🤖 **Agentic AI on governed data** — Salesforce **Agentforce & Data 360 (Data Cloud)** with responsible-AI controls (**IAPP AIGP**); **TOGAF** Enterprise Architect · **SAFe** delivery under regulatory (FED) deadlines

## 📂 What I've Published

Open-source reference implementations of the patterns above. **Everything here was
executed before it was published** — the pipelines run, the tests pass, and the
numbers in each README came from a real run rather than an estimate.

| Repository | What it is | Proof |
|---|---|---|
| **[sap-data-vault-2](https://github.com/aniketdwivedi7388/sap-data-vault-2)** | Data Vault 2.0 over real SAP procurement tables (LFA1, EKKO, EKPO, EKBE, MARA). Four source systems, hubs / links / multi-source satellites, hash keys & diffs, PIT + bridge, business vault, star marts. | Runs in 60s on DuckDB · 32 tests |
| **[lakehouse-pipeline-patterns](https://github.com/aniketdwivedi7388/lakehouse-pipeline-patterns)** | PySpark medallion architecture — incremental ingestion with watermarks, SCD Type 2, a declarative data-quality engine, as-of dimensional joins. | Runs on a laptop, no cluster · 23 tests |
| **[pyspark-rdd-internals](https://github.com/aniketdwivedi7388/pyspark-rdd-internals)** | What actually happens on the cluster: map-side combine, shuffle bytes, partitioning, caching, skew — each **measured**, then shown as the DataFrame/SQL equivalent you should ship. | 28 tests · real measurements |
| **[pydb-connect](https://github.com/aniketdwivedi7388/pydb-connect)** | Config-driven connectivity across MySQL, Postgres, Oracle, Snowflake, SQLite and ADLS. Secrets never in the repo, connections that always close, bulk loads that batch, retries that classify errors. | 172 tests · imports with zero drivers |
| **[data-governance-toolkit](https://github.com/aniketdwivedi7388/data-governance-toolkit)** | The working artefacts of a governance function — glossary templates, a 61-rule DQ catalogue with a runnable YAML-driven engine, stewardship operating model, RACIs, CDO KPI framework, lineage guide. | DAMA-DMBOK aligned · runnable gate |
| **[governed-ai-grounding](https://github.com/aniketdwivedi7388/governed-ai-grounding)** | Grounding enterprise AI agents in governed data — reference architecture, semantic layer as metric contract, guardrail patterns, AI controls mapping, evaluation harness. | Runnable eval harness, CI-ready |
| **[tableau-architecture-playbook](https://github.com/aniketdwivedi7388/tableau-architecture-playbook)** | Enterprise Tableau at scale — certified data sources, RLS patterns, performance tuning, content rationalisation, Server→Cloud migration runbooks, estate-audit / Hyper API / TabPy scripts. | Read-only audit tooling included |

Three of these reproduce failure modes I have actually hit and fixed — a future-dated
row poisoning a watermark so a job silently ingests nothing forever; SAP purchase-order
numbers colliding across instances because they are not globally unique; a quality suite
reporting 100% pass on broken data because `NULL > 0` is `NULL`, not `false`.
Reproducing a bug is worth more than describing one.

## 🛠️ Tech Stack

**Data Engineering & Pipelines**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="PySpark">
  <img src="https://img.shields.io/badge/SQL%20·%20PL/SQL-4479A1?style=for-the-badge" alt="SQL / PL-SQL">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="R">
  <img src="https://img.shields.io/badge/Alteryx-0078C0?style=for-the-badge&logo=alteryx&logoColor=white" alt="Alteryx">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/ETL%20·%20ELT-5C6BC0?style=for-the-badge" alt="ETL / ELT">
  <img src="https://img.shields.io/badge/REST%20APIs-6DB33F?style=for-the-badge" alt="REST APIs">
</p>

**Data Platforms, Lakehouse & Cloud**

<p>
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks">
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" alt="Snowflake">
  <img src="https://img.shields.io/badge/Oracle%20·%20PL/SQL-F80000?style=for-the-badge&logo=oracle&logoColor=white" alt="Oracle">
  <img src="https://img.shields.io/badge/Teradata-F37440?style=for-the-badge&logo=teradata&logoColor=white" alt="Teradata">
  <img src="https://img.shields.io/badge/IBM%20DB2-052FAD?style=for-the-badge&logo=ibm&logoColor=white" alt="IBM DB2">
  <img src="https://img.shields.io/badge/Apache%20Hive-FDEE21?style=for-the-badge&logo=apachehive&logoColor=black" alt="Apache Hive">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black" alt="DuckDB">
  <img src="https://img.shields.io/badge/Starburst%20·%20Trino-DD00A1?style=for-the-badge&logo=trino&logoColor=white" alt="Starburst / Trino">
  <img src="https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Microsoft Azure">
  <img src="https://img.shields.io/badge/Microsoft%20Fabric%20·%20OneLake-117865?style=for-the-badge" alt="Microsoft Fabric">
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Google Cloud">
  <img src="https://img.shields.io/badge/SAP-0FAAFF?style=for-the-badge&logo=sap&logoColor=white" alt="SAP">
</p>

**BI & Analytics**

<p>
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau">
  <img src="https://img.shields.io/badge/Tableau%20Pulse-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Tableau Pulse">
  <img src="https://img.shields.io/badge/TabPy%20·%20Hyper%20API-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="TabPy / Hyper API">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/CRM%20Analytics%20·%20Einstein-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" alt="CRM Analytics / Einstein">
  <img src="https://img.shields.io/badge/Qlik-009845?style=for-the-badge&logo=qlik&logoColor=white" alt="Qlik">
  <img src="https://img.shields.io/badge/IBM%20Cognos-052FAD?style=for-the-badge&logo=ibm&logoColor=white" alt="IBM Cognos">
</p>

**Governance, Salesforce & Delivery**

<p>
  <img src="https://img.shields.io/badge/Collibra-233C56?style=for-the-badge" alt="Collibra">
  <img src="https://img.shields.io/badge/DAMA--DMBOK-1B3A57?style=for-the-badge" alt="DAMA-DMBOK">
  <img src="https://img.shields.io/badge/Data%20Vault%202.0-6A1B9A?style=for-the-badge" alt="Data Vault 2.0">
  <img src="https://img.shields.io/badge/Salesforce%20Agentforce-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" alt="Salesforce Agentforce">
  <img src="https://img.shields.io/badge/Data%20360%20(Data%20Cloud)-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" alt="Data 360">
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira">
  <img src="https://img.shields.io/badge/Confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white" alt="Confluence">
  <img src="https://img.shields.io/badge/SAFe%20·%20Agile-1E62AD?style=for-the-badge" alt="SAFe / Agile">
</p>

## 🏆 Certifications

<div align="center">
<p>
  <img src="https://www.databricks.com/sites/default/files/2024-05/professional-badge-de.png" height="90" alt="Databricks Certified Data Engineer Professional" title="Databricks Certified Data Engineer Professional">
  <img src="badges/togaf-ea.jpg" height="90" alt="TOGAF Enterprise Architecture Practitioner" title="TOGAF Enterprise Architecture Practitioner">
  <img src="badges/cdmp-practitioner.png" height="90" alt="DAMA CDMP Practitioner" title="DAMA CDMP Practitioner">
  <img src="badges/cdmp-dgsp.png" height="90" alt="CDMP Data Governance & Stewardship" title="CDMP Data Governance & Stewardship">
  <img src="badges/cdmp-dwbi.png" height="90" alt="CDMP Data Warehousing & BI" title="CDMP Data Warehousing & BI">
  <img src="badges/aigp.png" height="90" alt="IAPP AI Governance Professional" title="IAPP AI Governance Professional">
  <img src="badges/snowpro-core.png" height="90" alt="Snowflake SnowPro Core" title="Snowflake SnowPro Core">
  <img src="badges/safe-agilist.png" height="90" alt="Certified SAFe Agilist (AI-Empowered)" title="Certified SAFe Agilist (AI-Empowered)">
</p>

<p>
  <img src="https://img.shields.io/badge/Salesforce-5×%20Tableau%20Certified-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Salesforce 5× Tableau Certified">
  <img src="https://img.shields.io/badge/Salesforce-Agentforce%20Specialist-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" alt="Salesforce Certified Agentforce Specialist">
  <img src="https://img.shields.io/badge/Salesforce-Data%20360%20Consultant-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" alt="Salesforce Certified Data 360 Consultant">
  <img src="https://img.shields.io/badge/Salesforce-CRM%20Analytics%20%26%20Einstein%20Discovery-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" alt="CRM Analytics and Einstein Discovery Consultant">
  <a href="https://learn.microsoft.com/en-us/users/aniketdwivedi-5142/credentials"><img src="https://img.shields.io/badge/Microsoft-Fabric%20Analytics%20Engineer%20(DP--600)-117865?style=for-the-badge" alt="Microsoft Fabric Analytics Engineer Associate"></a>
  <img src="https://img.shields.io/badge/Google%20Cloud-Certified-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Google Cloud Certified">
  <img src="https://img.shields.io/badge/BCS-Certified%20Business%20Analyst-2C5697?style=for-the-badge" alt="BCS Certified Business Analyst">
</p>
</div>

| Area | Credentials |
|---|---|
| 🔧 **Data Engineering** | **Databricks Certified Data Engineer Professional** · **Snowflake SnowPro Core** · Microsoft **[Fabric Analytics Engineer Associate](https://learn.microsoft.com/en-us/users/aniketdwivedi-5142/credentials)** (DP-600) |
| ☁️ **Salesforce — 5× Tableau certified** | **Tableau Architect** · **Tableau Data Analyst** · Tableau Desktop Specialist · **Agentforce Specialist** · **Data 360 Consultant** · **CRM Analytics & Einstein Discovery Consultant** |
| 🛡️ **Data Management** | **DAMA CDMP Practitioner** — specialisations in Data Governance & Stewardship (DGSP) and Data Warehousing & BI · **IAPP AIGP** (AI Governance Professional) |
| 🏗️ **Architecture & Cloud** | **TOGAF Enterprise Architecture Practitioner** (The Open Group) · Google Cloud |
| 🔄 **Agile & Analysis** | Certified **SAFe Agilist** (AI-Empowered) · **BCS Certified Business Analyst** |

## 🏢 Domains

Data platforms are only as good as the domain understanding behind them. Where
I have delivered:

| Domain | Depth |
|---|---|
| **Asset & Investment Management** | Chief Data Office reporting, AUM and net-flow metrics, mandate and benchmark data, investment-risk and controls reporting, regulatory (FED) submissions |
| **Banking & Credit Risk** | Credit-card and corporate credit-risk estates — exposure, delinquency, vintage, loss forecasting and portfolio-risk reporting on governed warehouse foundations |
| **Procurement & Supply Chain** | Purchase-to-pay and SAP procurement data (purchase orders, goods receipts, vendor master, info records), inventory, logistics, vendor performance and on-time-delivery analytics |
| **Retail & Omnichannel** | Market-basket analysis, cross-sell and loyalty segmentation, competitor price-index tracking for dynamic pricing, store-traffic prediction |
| **Insurance** | Policy and claims analytics, predictive risk modelling |
| **Energy & Telecom** | Power-distribution and smart-meter style operational data, network and customer-experience reporting |

## 📌 Signature Projects

**🏛️ "House of Data" — Governed Data Foundation + Agentic AI** · *DWS (Deutsche Bank Group)*<br>
Engineered the Chief Data Office's single-source data foundation — ingestion, harmonisation and modelling across **Snowflake, Azure & Microsoft Fabric**, federated through **Starburst/Trino**, governed in **Collibra** — then built agentic-AI experiences on **Agentforce, Prompt Builder & Data 360** so leadership can ask natural-language questions on governance, quality and lineage, feeding senior risk dashboards and regulatory (FED) reporting.

**🚢 COVID-19 Live Global Ports & Shipping-Routes Command Center** · *Emerson*<br>
**Python + REST-API ingestion pipelines** feeding a live Tableau dashboard with real-time status of countries, borders and ports — best/most-affordable route recommendations across Sea, Air & Land with live climate-warning overlays. The procurement team's daily command center as global supply lines changed by the hour.

**📦 Data-as-a-Service at Scale** · *Emerson Core Data Analytics CoE*<br>
Owned the full pipeline — data marts, dimensional models, **ETL with Tableau Prep · Alteryx · Oracle SQL · Python** (incl. Scrapy web-scraping of alternative data) — deploying **150+ governed dashboards globally**; embedded MDM & anomaly monitoring that helped identify **$20M in supply-chain savings**.

**🏦 Credit-Risk Data & Analytics — Consumer & Corporate Banking** · *JPMorgan Chase*<br>
Built governed data foundations on **Snowflake** with enterprise **ETL/ELT pipelines (Python — pandas/NumPy, Alteryx)** over Oracle & Big Data back ends, powering exposure, delinquency, vintage and portfolio-risk reporting for credit-card operations with audited source-to-target lineage.

**🛒 Omnichannel Retail Analytics — Walmart & Office Depot** · *DenuoSource*<br>
Market-basket analysis, cross-sell/upsell recommendations, loyalty segmentation, **Python-based competitor price-index pipelines** for dynamic pricing, and store-traffic prediction on Teradata-backed data.

## 💼 Career at a Glance

| Organisation | Role | Focus |
|---|---|---|
| **DWS Group** (Deutsche Bank) | AVP · Solutions Architect, Chief Data Office | House of Data · governed data platform · agentic AI |
| **Aditi Consulting** | Senior Consultant | Tableau Next · Data Cloud |
| **Escalent** | Product Manager | Enterprise Architecture & Data Modelling · Tableau BI |
| **JPMorgan Chase & Co.** | AVP · Tableau Design Architect | Data Architecture & Governance · Tableau BI |
| **eClerx** | Senior Process Manager · Lead Data Consultant | BI delivery · Cognos→Tableau migration |
| **Emerson** | Senior Data Engineer · BI Solution Architect | Supply-chain data platform · Data-as-a-Service · BI |
| **Accenture** | Senior Data Analyst · Tableau Consultant | Insurance analytics · predictive risk models · BI |
| **TCS** | Data Analyst · Tableau Trainer | CX analytics · Tableau enablement · BI |
| **DenuoSource** | Business Analyst · Tableau Consultant | Retail analytics (Walmart, Office Depot) · BI |

## 🎯 Current Focus

- ⚡ **Data Engineering** — lakehouse pipelines with **Databricks & PySpark** (certified Data Engineer Professional), Microsoft Fabric/OneLake, Snowflake & Starburst/Trino federation
- 🏗️ **Data Architecture** — Data Vault 2.0 for multi-source landscapes, TOGAF-driven target-state design, conformed dimensions and governed semantic layers at CDO scale
- 🤖 **Agentic analytics** — Agentforce agents grounded in governed data, Tableau Pulse proactive insights
- 🛡️ **AI governance** — extending DAMA-style controls to AI/agentic data pipelines (IAPP AIGP)

## 🤝 Let's Talk

Always happy to compare notes with people working on the same problems. Particularly
interested in conversations about:

- **Data platform & architecture leadership** — Data Architect, Principal / Lead Data Engineer, Data Platform Lead
- **Chief Data Office and governance transformation** — operating models, DAMA-aligned frameworks, Collibra adoption
- **Enterprise BI at scale** — Tableau architecture, migration and rationalisation
- **Agentic AI on governed data** — and where the governance actually has to sit

Open to consulting, advisory and speaking on any of the above.

📫 **[LinkedIn](https://www.linkedin.com/in/dwivedianiket/)** · **[aniketdwivedi.com](https://www.aniketdwivedi.com)** · **[aniket.dwivedi@icloud.com](mailto:aniket.dwivedi@icloud.com)**

## 📈 GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=aniketdwivedi7388&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&title_color=0071E3&icon_color=0071E3" alt="GitHub Stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aniketdwivedi7388&layout=compact&hide_border=true&langs_count=8&title_color=0071E3" alt="Top Languages" height="165">
</p>

---

<div align="center">

💬 *Everything in the repositories above is runnable. Clone it, run it, tell me where I'm wrong.*

</div>
