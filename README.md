<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│  $ airflow dags trigger emmanuel_leakono_v2                 │
│  [2026-08-11 09:41:03] INFO - DAG triggered successfully     │
│  [2026-08-11 09:41:03] INFO - Scheduler: it's_a_me_engine    │
└─────────────────────────────────────────────────────────────┘
```

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&duration=2800&pause=900&color=22C55E&center=true&vCenter=true&width=800&lines=EXTRACT+%E2%86%92+TRANSFORM+%E2%86%92+LOAD;Data+Engineer+%7C+Software+Engineer;Nairobi%2C+Kenya+%F0%9F%87%B0%F0%9F%87%AA;Self-taught.+Production-minded." alt="Typing SVG" />

</div>

<br>

<table align="center">
<tr>
<td valign="top">

```
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

```
emmanuel@nairobi
-----------------
OS ..........  Data Engineer (Junior)
Host ........  Nairobi, Kenya
Kernel ......  self-taught, est. zero-laptop-experience
Uptime ......  2+ years, backend & data systems
Shell .......  bash / zsh (linux)
Editor ......  VS Code

Lang.Data ...  Python, SQL
Lang.Web ....  JavaScript, TypeScript

Stack.Data ..  Snowflake, dbt, Airflow, Power BI
Stack.Web ...  React, Django, Node.js, Express

Contact.Mail   leakonoemmanuel3@gmail.com
Contact.Hub .  github.com/LEAKONO
Contact.In ..  /in/emmanuel-leakono-7125472b8

-----------------
🟩🟩🟩🟩 🟨🟨🟨🟨 🟥🟥🟥🟥 ⬛⬛⬛⬛
```

</td>
</tr>
</table>

<br>

## `⛁` pipeline architecture

```mermaid
flowchart LR
    A[("fa:fa-database RAW")] -->|extract| B[/"STAGING"/]
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
```
python
sql             # window functions, CTEs
snowflake
postgresql / mysql / mongodb
dbt             # certified: Fundamentals
apache-airflow  # certified: Essentials
aws-s3
power-bi
docker + github-actions
```

</td>
<td valign="top" width="50%">

**// software engineering**
```
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

<br>

## `⛁` `$ whoami --verbose`

```
> built three production-style data pipelines end to end —
> ingestion, warehousing, transformation, orchestration, and BI —
> plus a backend internship shipping real features on a deadline.
> still learning. still shipping. still asking why.
```

<br>

```
$ fortune | cowsay
 _________________________________________
/ "In God we trust; all others must       \
\ bring data." — W. Edwards Deming        /
 -----------------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
```

<br>

<div align="center">

**`⛁` connect**

[![Email](https://img.shields.io/badge/-leakonoemmanuel3@gmail.com-22C55E?style=flat-square&logo=gmail&logoColor=white)](mailto:leakonoemmanuel3@gmail.com)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-22C55E?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emmanuel-leakono-7125472b8/)
[![Portfolio](https://img.shields.io/badge/-Portfolio-22C55E?style=flat-square&logo=vercel&logoColor=white)](https://leakono-portfolio.vercel.app/)

<sub>pipeline status: <b>🟢 running</b> · last dag run: today</sub>

</div>
