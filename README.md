<div align="center">

# `emmanuel@nairobi:~$ ./initialize_engineer.sh`

```text
┌──────────────────────────────────────────────────────────────────────┐
│                                                                      │
│   ███████╗███╗   ███╗███╗   ███╗ █████╗ ███╗   ██╗██╗   ██╗███████╗ │
│   ██╔════╝████╗ ████║████╗ ████║██╔══██╗████╗  ██║██║   ██║██╔════╝ │
│   █████╗  ██╔████╔██║██╔████╔██║███████║██╔██╗ ██║██║   ██║█████╗   │
│   ██╔══╝  ██║╚██╔╝██║██║╚██╔╝██║██╔══██║██║╚██╗██║╚██╗ ██╔╝██╔══╝   │
│   ███████╗██║ ╚═╝ ██║██║ ╚═╝ ██║██║  ██║██║ ╚████║ ╚████╔╝ ███████╗ │
│   ╚══════╝╚═╝     ╚═╝╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝  ╚═══╝  ╚══════╝ │
│                                                                      │
│                    DATA ENGINEER // BUILDER                          │
│                                                                      │
└──────────────────────────────────────────────────────────────────────┘

[BOOT] Initializing engineering environment...
[ OK ] Python runtime
[ OK ] SQL engine
[ OK ] Snowflake warehouse
[ OK ] dbt transformation layer
[ OK ] Apache Airflow orchestration
[ OK ] Power BI analytics layer
[ OK ] Linux / Git / Docker
[ OK ] Curiosity
[ OK ] "Why?" generator

STATUS: 🟢 ONLINE
LOCATION: Nairobi, Kenya 🇰🇪
```

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=2800&pause=900&color=22C55E&center=true&vCenter=true&width=850&lines=EXTRACT+%E2%86%92+TRANSFORM+%E2%86%92+LOAD;DATA+ENGINEERING+%7C+SOFTWARE+ENGINEERING;PYTHON+%2B+SQL+%2B+SNOWFLAKE+%2B+DBT+%2B+AIRFLOW;BUILDING+DATA+SYSTEMS+THAT+ACTUALLY+RUN;SELF-TAUGHT.+PRODUCTION-MINDED." alt="Typing SVG"/>

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Emmanuel_Leakono-0A66C2?style=flat-square\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/emmanuel-leakono-7125472b8)
[![GitHub](https://img.shields.io/badge/GitHub-LEAKONO-181717?style=flat-square\&logo=github\&logoColor=white)](https://github.com/LEAKONO)
[![Email](https://img.shields.io/badge/Email-Contact-22C55E?style=flat-square\&logo=gmail\&logoColor=white)](mailto:leakonoemmanuel3@gmail.com)

</div>

---

## `01` // SYSTEM IDENTITY

```text
emmanuel@nairobi
-----------------

ROLE        : Junior Data Engineer
BACKGROUND  : Software Engineering
LOCATION    : Nairobi, Kenya 🇰🇪

PRIMARY     : Python / SQL
WAREHOUSE   : Snowflake
TRANSFORM   : dbt
ORCHESTRATE : Apache Airflow
VISUALIZE   : Power BI
CLOUD       : AWS
SYSTEM      : Linux
VERSIONING  : Git / GitHub

EXPERIENCE
----------
Backend Engineering      ███████████████████░░  85%
Data Engineering         ████████████████░░░░░  75%
SQL                      ███████████████████░░  90%
Python                   ███████████████████░░  90%
Cloud / AWS              ████████████░░░░░░░░  60%

UPTIME      : 2+ years building software & data systems
MINDSET     : Understand → Build → Break → Fix → Ship
```

---

## `02` // DATA PIPELINE CONTROL ROOM

```text
                         ┌───────────────────┐
                         │   DATA SOURCES    │
                         │                   │
                         │ APIs • CSV • DBs  │
                         │ External Systems  │
                         └─────────┬─────────┘
                                   │
                                   ▼
                         ┌───────────────────┐
                         │     INGESTION     │
                         │                   │
                         │ Python • REST API │
                         │ Incremental Loads │
                         │ Watermarks        │
                         └─────────┬─────────┘
                                   │
                                   ▼
                    ┌──────────────────────────────┐
                    │         SNOWFLAKE            │
                    │                              │
                    │       RAW → STAGING          │
                    │               ↓              │
                    │             MARTS            │
                    └──────────────┬───────────────┘
                                   │
                         ┌─────────▼─────────┐
                         │       dbt         │
                         │                   │
                         │ Transformations   │
                         │ Tests • Models    │
                         │ Documentation     │
                         └─────────┬─────────┘
                                   │
                                   ▼
                         ┌───────────────────┐
                         │      POWER BI     │
                         │                   │
                         │ KPIs • Analytics  │
                         │ Dashboards        │
                         └───────────────────┘

                    ▲
                    │
              ┌─────┴─────┐
              │  AIRFLOW  │
              │           │
              │ Schedule  │
              │ Retry     │
              │ Monitor   │
              └───────────┘
```

> **Design principle:** data should move predictably, transformations should be reproducible, failures should be observable, and business users should trust the final numbers.

---

## `03` // ENGINEERING STACK

### `data-engineering`

```yaml
languages:
  - Python
  - SQL

warehousing:
  - Snowflake
  - PostgreSQL
  - MySQL

transformation:
  - dbt

orchestration:
  - Apache Airflow

cloud:
  - AWS S3
  - AWS EC2
  - AWS fundamentals

analytics:
  - Power BI
  - Metabase

engineering:
  - Docker
  - Git
  - GitHub Actions
  - Linux
```

### `software-engineering`

```yaml
languages:
  - JavaScript
  - TypeScript
  - Python

frontend:
  - React
  - Redux
  - Tailwind CSS

backend:
  - Django
  - Django REST Framework
  - Flask
  - Node.js
  - Express

security:
  - JWT
  - OAuth2
  - bcrypt

tools:
  - Git
  - Linux
  - Postman
```

---

## `04` // PRODUCTION LAB

```text
┌─────────────────────────────────────────────────────────────────────┐
│ PROJECT                         STATUS             RESULT            │
├─────────────────────────────────────────────────────────────────────┤
│                                                                       │
│ ✈ Flight Operations Analytics   [██████████]       70% faster        │
│   Watermark-based incremental   🟢 SHIPPED        ~30m → ~9m         │
│                                                                       │
│ 🛒 Retail ELT Pipeline          [██████████]       1M+ records       │
│   Snowflake + dbt + Airflow     🟢 SHIPPED        34 quality tests  │
│                                                                       │
│ 🚕 Uber Trip Analytics          [██████████]       End-to-end        │
│   Python + Snowflake + dbt      🟢 SHIPPED        BI-ready marts    │
│                                                                       │
│ 🌐 SafariDesk                   [██████████]       Real features     │
│   React + TypeScript + Django   🟢 COMPLETED      Frontend + APIs   │
│                                                                       │
└─────────────────────────────────────────────────────────────────────┘
```

### ✈ Flight Operations Analytics

**Problem:** Full-refresh ingestion was wasting processing time.

**Solution:** Implemented watermark-based incremental loading.

```text
BEFORE
30 minutes
██████████████████████████████

AFTER
~9 minutes
█████████

IMPROVEMENT → ~70% runtime reduction
```

**Stack:** Python · AviationStack API · Snowflake · dbt · Airflow · Power BI

---

### 🛒 Retail ELT Pipeline

```text
Online Retail II
      │
      ▼
Python ingestion
      │
      ▼
Snowflake RAW
      │
      ▼
dbt STAGING
      │
      ▼
dbt MARTS
      │
      ▼
Power BI
```

**Pipeline output:**

```text
Records processed     1,021,429
Revenue analyzed      £18.93M
Data quality tests    34
Orchestration         Apache Airflow
```

---

### 🚕 Uber Trip Analytics

```text
             NYC TAXI DATA
                   │
                   ▼
              INGESTION
                   │
                   ▼
              SNOWFLAKE
                   │
          ┌────────┴────────┐
          ▼                 ▼
       STAGING             RAW
          │
          ▼
         DBT
          │
          ▼
        MARTS
          │
          ▼
       POWER BI
```

**MARTS**

```text
FACT_TRIP
DIM_DATETIME
DIM_LOCATION
DIM_VENDOR
DIM_PAYMENT_TYPE
```

---

## `05` // DATA ENGINEERING PATTERNS I USE

```text
                 ┌─────────────────────┐
                 │     RAW LAYER       │
                 │                     │
                 │ Preserve source     │
                 │ data as received    │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │   STAGING LAYER     │
                 │                     │
                 │ Clean • Cast •      │
                 │ Standardize         │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │     MARTS LAYER     │
                 │                     │
                 │ Facts • Dimensions  │
                 │ BI-ready models     │
                 └─────────────────────┘
```

```text
✓ Incremental loading
✓ Watermarking
✓ Idempotent pipelines
✓ Data quality testing
✓ Audit logging
✓ Quarantine handling
✓ Dimensional modeling
✓ Star schemas
✓ ETL / ELT
✓ Pipeline monitoring
✓ Failure recovery
```

---

## `06` // AIRFLOW SCHEDULER

```text
$ airflow dags trigger emmanuel_leakono_v2

[2026-08-11 09:41:03] INFO
DAG triggered successfully

[2026-08-11 09:41:04] INFO
Task: extract_source_data              ✓

[2026-08-11 09:41:19] INFO
Task: load_raw                         ✓

[2026-08-11 09:42:01] INFO
Task: dbt_staging                      ✓

[2026-08-11 09:42:37] INFO
Task: dbt_marts                        ✓

[2026-08-11 09:42:49] INFO
Task: data_quality                    ✓

[2026-08-11 09:42:53] INFO
Task: refresh_bi                      ✓

────────────────────────────────────────────
PIPELINE STATUS : 🟢 SUCCESS
ROWS PROCESSED  : 1,021,429
FAILED TASKS    : 0
RETRIES         : 0
────────────────────────────────────────────
```

---

## `07` // `$ whoami --verbose`

```text
> I build data pipelines end to end.

> I care about what happens between
> "the API returned JSON"
> and
> "the dashboard says 18.93M".

> I like understanding the entire path:

        source
          ↓
      ingestion
          ↓
       storage
          ↓
     transformation
          ↓
       modeling
          ↓
       analytics

> My software engineering background taught me
> to think about APIs, databases, systems and failure.

> Data engineering taught me to think about
> reliability, scalability, lineage and trust.

> I'm still learning.

> I'm still breaking things.

> I'm still asking WHY.

> And I'm still shipping.
```

---

## `08` // CURRENTLY LOADING...

```text
[███████████████████████░░░]  AWS
[████████████████████░░░░░]  Data Engineering
[███████████████████░░░░░░]  Distributed Systems
[█████████████████░░░░░░░░]  Kafka
[████████████████░░░░░░░░░]  Cloud Architecture
[███████████████░░░░░░░░░░]  Advanced SQL
```

```text
next_modules = [

    "Kafka & event streaming",
    "AWS data engineering",
    "Distributed data systems",
    "Advanced warehouse architecture",
    "Data platform engineering"

]
```

---

## `09` // ENGINEERING PHILOSOPHY

```text
┌────────────────────────────────────────────────────────────┐
│                                                            │
│  DATA IS NOT JUST SOMETHING TO MOVE.                       │
│                                                            │
│  It needs to be:                                           │
│                                                            │
│       RELIABLE     →     Can I trust it?                   │
│       REPEATABLE   →     Can I run it again safely?        │
│       OBSERVABLE   →     Will I know when it breaks?       │
│       SCALABLE     →     What happens at 100× volume?     │
│       USEFUL       →     Can someone make a decision?     │
│                                                            │
└────────────────────────────────────────────────────────────┘
```

---

## `10` // CONTACT

<div align="center">

```text
┌─────────────────────────────────────────────┐
│                                             │
│  $ ./connect_with_emmanuel.sh               │
│                                             │
│  EMAIL      → leakonoemmanuel3@gmail.com    │
│  GITHUB     → github.com/LEAKONO            │
│  LINKEDIN   → Emmanuel Leakono              │
│  LOCATION   → Nairobi, Kenya 🇰🇪             │
│                                             │
│  status: OPEN_TO_OPPORTUNITIES              │
│                                             │
└─────────────────────────────────────────────┘
```

<a href="https://github.com/LEAKONO">
  <img src="https://img.shields.io/badge/GitHub-LEAKONO-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>
<a href="https://www.linkedin.com/in/emmanuel-leakono-7125472b8">
  <img src="https://img.shields.io/badge/LinkedIn-CONNECT-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<br><br>

```text
pipeline status: 🟢 RUNNING
last deployment: TODAY
failed jobs: 0
coffee: REQUIRED ☕
```

<br>

> *"In God we trust; all others must bring data."*

</div>
