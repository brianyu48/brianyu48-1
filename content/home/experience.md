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
  - title: Research Assistant
    company: Kean University
    company_url: 'https://www.kean.edu/'
    company_logo: Kean
    location: New Jersey, United States
    date_start: '2021-01-01'
    date_end: '2022-02-1'
    description: |2-
        Responsibilities include:
        
        * ESG Stock Analysis

          Used Python to analyze the 4 Chinese major indexes through the Tushare API interface and built
          the GARCH (1,1) model to analyze the volatilities of 4 indexes, proving that ESG can’t perform 
          better in long-term volatility
        * Modelling
        * Deploying

  - title: Consumer Goods Investment Intern
    company: Whales Captial
    company_url: 'http://whalescapital.com/'
    company_logo: 合鲸资本
    location: Shanghai, China
    date_start: '2021-06-15'
    date_end: '2021-08-27'
    description: |2-
        Responsibilities include:
        * Conducted desk research, investigated more than 50 stores, analyzed the profit model of 
          companies, and completed 57 pages analysis report, which supported the whole investment 
          team’s decision not to invest money in start-ups in the bakery industry in China
        * Interviewed 15+ start-up companies’ CEOs with VP and sorted out meeting minutes to facilitate 
          further potential discussion about investment.

design:
  columns: '2'
---
