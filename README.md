# Dish Dudhat

**IT Specialist | AI Automation Developer**  
Toronto, Canada · [LinkedIn](https://www.linkedin.com/in/dish-dudhat) · [Email](mailto:dishdudhat85@gmail.com)

> **I build intelligent automation systems that connect business processes, data, and cloud technologies.**

```bash
$ whoami
dish-dudhat

$ cat focus.conf
business_process_automation
ai_assisted_workflows
data_integration
operational_reporting
cloud_analytics     

$ echo $MISSION
Build reliable systems. Automate repetitive work. Turn data into useful decisions.
```

Most of my work starts with a manual process that people have learned to tolerate: a report rebuilt every morning, an attendance file checked line by line, a procedure that lives in one person's head. I turn that into a workflow with defined inputs, validation, exception handling, and a clear owner for the cases a machine shouldn't decide alone.

*A good automation is one nobody has to think about, and anyone can inspect.*

---

## Skills

```toml
[automation]            
tools = ["Power Automate", "n8n", "Office Scripts", "Power Apps", "REST APIs", "Webhooks"]

[programming_and_data]  
tools = ["Python", "JavaScript", "SQL", "Excel", "data validation", "data transformation"]

[ai_automation]        
tools = ["AI-assisted workflows", "document processing", "classification", "human-in-the-loop review"]
exploring = ["AI agents"]

[cloud_analytics]    
tools = ["Microsoft Azure", "cloud storage", "data pipelines", "SQL analytics", "reporting and visualization"]
```

---

## Selected work

| Project | What it does | Stack |
| --- | --- | --- |
| [**Flow IQ**](https://github.com/dudhat52/Flow_IQ-AFTX_AMAZON) | Warehouse scan-history analytics: shift windows, time-off-task gaps, productivity, cage counting, duplicate-timestamp handling, exception review | JavaScript userscripts |
| [**Closio**](https://github.com/dudhat52/Closio-Clothing_store) · [live site](https://closio-clothing-store-dish-dudhats-projects.vercel.app/) | Full-stack clothing store with MVC structure, MongoDB persistence, and a Vercel deployment | Node.js, Express, EJS, MongoDB |
| [**Operations Reporting Automation**](https://github.com/dudhat52/operations-reporting-automation) | A hand-built daily report turned into a scheduled, validated run with an exception log | Power Automate, Python, Excel |
| [**HR Attendance Automation**](https://github.com/dudhat52/hr-attendance-automation) | Late-arrival detection and exception review for attendance files, with a person making the final call | Power Automate, Office Scripts, Excel |
| [**Document-Driven Workflow Automation**](https://github.com/dudhat52/document-workflow-automation) | Turning a written procedure into a reviewed specification and a scheduled workflow | Power Automate, n8n |
| [**Cloud Analytics Learning Lab**](https://github.com/dudhat52/cloud-analytics-learning-lab) | SQL modelling and data-quality checks on fictional data, with Azure next | SQL, Python, Azure |

Flow IQ publishes no proprietary source, internal URLs, or employee data. The case studies are documentation only and use synthetic data.

---

## How I build

```python
def run_workflow(records):
    valid, rejected = validate(records)     # fail loudly at the door
    log(rejected)                           # never drop data silently

    result = transform(valid)

    if needs_judgement(result):
        return human_review(result)         # AI proposes, people approve

    return deliver(result)                  # then log what happened
```

```text
 TRIGGER (schedule / file / webhook / form)
        │
        ▼
 INGEST ──► VALIDATE ──► reject + log bad records
                │
                ▼
          TRANSFORM
     (Office Scripts · Python · SQL)
                │
      ┌─────────┴─────────┐
      ▼                   ▼
  REPORTING          AI-ASSISTED STEP
 (Excel · BI)     (classify · extract · summarize)
      │                   │
      └─────────┬─────────┘
                ▼
       HUMAN REVIEW  ◄── exceptions and low-confidence results
                │
                ▼
     DELIVER + LOG (email · Teams · file · API)
```

1. **Validate before you transform.** Bad input should fail loudly at the door, not quietly in the report.
2. **Every automation needs an exception path.** If a person can't see what was skipped and why, it isn't finished.
3. **AI proposes, people approve** whenever the decision has consequences.

---

## Currently learning

Cloud analytics and cloud data engineering on Microsoft Azure: how data is ingested, stored, modelled, quality-checked, and reported on at scale. I'm practising on fictional data in the [Learning Lab](https://github.com/dudhat52/cloud-analytics-learning-lab).

---

## Contact

```text
email     dishdudhat85@gmail.com
github    github.com/dudhat52
linkedin  linkedin.com/in/dish-dudhat
```

I'm interested in work where an unclear manual process needs to become a defined, testable workflow, and in teams building toward cloud analytics.

*Processes in. Decisions out.*
