---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Data Engineer Intern
    company: Insurance Corporation of British Columbia (ICBC)
    company_url: 'https://www.icbc.com/Pages/default.aspx'
    company_logo: icbc-logo
    location: Vancouver, BC, Canada
    date_start: '2022-05-01'
    date_end: '2022-09-01'
    description: |2-
        Responsibilities include:
        
        * Developed and maintained an ETL data pipeline in **Spark Scala** with 100% accuracy to facilitate data migration.
        * Implemented data validation using **SQL** queries to extract large scale data from different databases (**Oracle**, **Drill**, **Hive**).
        * Applied software engineering best practice during the pipeline building process, including unit testing, **shell scripting**, CI\/CD automation using **Jenkins**, version control using **SVN**, etc.).
        * Built **Tableau** dashboards to provide varying levels of visualization for stakeholders and automate data quality monitoring.
        * Collaborated with internal and external stakeholders in Agile environment (**Scrum** meetings, **JIRA**, **Kanban** board) about data feeds and data mappings.

  - title: Professor of Semiconductor Physics
    company: University X
    company_url: ''
    company_logo: org-x
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '2'
---
