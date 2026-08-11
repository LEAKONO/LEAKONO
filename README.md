<div align="center">

```text
$ ./initialize_engineer.sh

Loading engineer profile...

identity     → Emmanuel Leakono
role         → Data Engineer
location     → Nairobi, Kenya 🇰🇪
specialty    → Data Pipelines & Analytics

initializing stack...

python       → [████████████████████] READY
sql          → [████████████████████] READY
snowflake    → [████████████████████] READY
dbt          → [████████████████████] READY
airflow      → [████████████████████] READY
power-bi     → [████████████████████] READY

────────────────────────────────────────────
SYSTEM STATUS   : 🟢 ONLINE
PIPELINE STATUS : 🟢 RUNNING
────────────────────────────────────────────
```

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=2800&pause=900&color=22C55E&center=true&vCenter=true&width=850&lines=EXTRACT+%E2%86%92+TRANSFORM+%E2%86%92+LOAD;Data+Engineer+%7C+Software+Engineer;Python+%2B+SQL+%2B+Snowflake+%2B+dbt+%2B+Airflow;Building+production-minded+data+systems" alt="Typing SVG" />

</div>

<br>

<table align="center">
<tr>
<td valign="top">

```text
        ┌────────────────────────┐
        │   E M M A N U E L      │
        │      L E A K O N O     │
        ├────────────────────────┤
        │  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  │  ← marts   (bi-ready)
        │  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  │  ← staging (typed)
        │  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  │  ← raw     (ingested)
        ├────────────────────────┤
        │   >_ data engineer     │
        └────────────────────────┘
               ▓▓▓▓▓▓▓▓▓▓
              ▓▓▓▓▓▓▓▓▓▓▓▓
             ▓▓▓▓▓▓▓▓▓▓▓▓▓▓
```

</td>
<td valign="top">

```text
emmanuel@nairobi
-----------------
OS ..........  Data Engineer
Host ........  Nairobi, Kenya
Kernel ......  learn → build → ship
Uptime ......  2+ years, backend & data systems
Shell .......  bash / zsh (linux)
Editor ......  VS Code

Lang ........  Python, SQL
Cloud .......  AWS
Storage .....  Amazon S3
Warehouse ...  Snowflake
Transform ...  dbt
Orchestrate .  Apache Airflow
Analytics ...  Power BI

Contact.Mail   leakonoemmanuel3@gmail.com
Contact.Hub .  github.com/LEAKONO
Contact.In ..  /in/emmanuel-leakono-7125472b8

-----------------
STATUS .......  BUILDING
MODE .........  SHIPPING
FOCUS ........  DATA ENGINEERING
```

</td>
</tr>
</table>

<br>

## `⛁` pipeline architecture

```mermaid
flowchart LR
    A[("RAW")] -->|extract| B[/"STAGING"/]
    B -->|dbt transform| C{{"MARTS"}}
    C -->|load| D[["Power BI"]]
    E["Orchestration\nApache Airflow"] -.schedules & retries.-> A
    E -.schedules & retries.-> B
    E -.schedules & retries.-> C

    style A fill:#1a1a2e,stroke:#22C55E,color:#22C55E
    style B fill:#1a1a2e,stroke:#22C55E,color:#22C55E
    style C fill:#1a1a2e,stroke:#22C55E,color:#22C55E
    style D fill:#1a1a2e,stroke:#22C55E,color:#22C55E
    style E fill:#16161f,stroke:#eab308,color:#eab308
```

<br>

## `⛁` tech stack — `requirements.txt`

<table align="center">
<tr>
<td valign="top" width="50%">

**// data engineering**
```text
python
sql             # window functions, CTEs
snowflake
postgresql / mysql
dbt             # certified: Fundamentals
apache-airflow  # certified: Essentials
aws
power-bi
docker + github-actions
```

</td>
<td valign="top" width="50%">

**// software engineering**
```text
javascript (es6+) / typescript
react + redux + tailwind
django + drf / flask
node.js + express
jwt / oauth2 / bcrypt
git + linux + postman
```

</td>
</tr>
</table>

<br>

## `⛁` `$ tail -f build_log.txt`

```diff
+ [PASS] flight-ops-analytics-platform   watermark incremental loads → 70% faster runtime
+ [PASS] retail_pipeline                 1M+ transactions → star schema + dbt quality tests
+ [PASS] uber-trip-analytics-platform    10K+ simulated daily trips, incremental pipelines
+ [DONE] safaridesk_internship           react/typescript frontend + django/postgres apis
```

```text
watermark incremental loading — relative runtime
before  ██████████████████████████████  100%
after   █████████                        30%
```

<br>

## `⛁` `$ whoami --verbose`

```text
> built three production-style data pipelines end to end —
> ingestion, warehousing, transformation, orchestration, and BI —
> plus a backend internship shipping real features on a deadline.
> building reliable systems. shipping continuously.
```

<br>

## `⛁` currently loading...

```text
AWS Cloud Practitioner   [██████████░░░░░░░░░░]  IN PROGRESS
```

```python
next_targets = [
    "Kafka & event streaming",
    "Distributed data systems",
    "Advanced warehouse architecture",
    "Cloud architecture patterns",
    "Advanced SQL",
]
```

<br>

## `⛁` `$ cat engineering_principles.txt`

```text
reliable      → pipelines should recover
observable    → failures should be visible
reproducible  → transformations should be deterministic
scalable      → design for the next 100×
useful        → data should drive decisions
```

<br>

<div align="center">

**`⛁` connect**

[![Email](https://img.shields.io/badge/-leakonoemmanuel3@gmail.com-22C55E?style=flat-square&logo=gmail&logoColor=white)](mailto:leakonoemmanuel3@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-22C55E?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emmanuel-leakono-7125472b8/)
[![Portfolio](https://img.shields.io/badge/-Portfolio-22C55E?style=flat-square&logo=vercel&logoColor=white)](https://leakono-portfolio.vercel.app/)

<sub>building data systems · Nairobi, Kenya 🇰🇪 · available for opportunities</sub>

</div>
