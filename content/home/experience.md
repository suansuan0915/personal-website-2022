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
  - title: Graduate Teaching Assistant
    company: Simon Fraser University
    company_url: 'https://www.sfu.ca/computing.html'
    company_logo: sfu-logo
    location: Burnaby, BC, Canada
    date_start: '2022-09-01'
    date_end: '2022-12-31'
    description: |2-
        Responsibilities include:
        
        * Coordinate with the professor and other two TAs on CMPT 726 Machine Learning course by holding office hours,\ndesigning assignment problems & solutions, grading homework, and hold weekly meetings.
        * Tools used: **LaTeX**, **Canvas**, **Gradescope**.

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
        * Applied software engineering best practice during the pipeline building process, including unit testing, **shell scripting**, \nCI\/CD automation using **Jenkins**, version control using **SVN**, etc.).
        * Built **Tableau** dashboards to provide varying levels of visualization for stakeholders and automate data quality monitoring.
        * Collaborated with internal and external stakeholders in Agile environment (**Scrum** meetings, **JIRA**, **Kanban** board) \nabout data feeds and data mappings.

  - title: Operations Data Analyst
    company: Morgan Stanley
    company_url: 'https://www.morganstanley.com/'
    company_logo: MS-logo
    location: Baltimore, MD, United States
    date_start: '2018-01-01'
    date_end: '2018-05-20'
    description: |2-
        Responsibilities include:
        
        * Analyzed 20+ derivatives trading transaction data daily. Created Tableau dashboards and presented to clients and directors.
        * Modeled derivatives product pricing and transactions with the application of Black-Scholes Pricing Models.
        * Queried data from internal database using **MySQL**, quantified risk metrics and developed KRI \nreports in **EXCEL** (v-lookup, pivot table, functions).
        * Streamlined internal risk management processes and improved drafting time by 20%.
        * Led weekly conference calls with Asian, European teams and collaborated with sales and trading teams. 

design:
  columns: '3'
---
