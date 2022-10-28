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
    date_end: '2022-02-01'
    description: |2-
        Responsibilities include:
        * ESG Stock Analysis:
            1.Used Python to analyze the 4 Chinese major indexes through the Tushare API interface and built
              the GARCH (1,1) model to analyze the volatilities of 4 indexes, proving that ESG can’t perform 
              better in long-term volatility
            2.Classified 800 stocks into four groups based on their ESG scores and period returns; applied KNN, 
              SVM, and AdaBoost models to achieve the result that the highest accuracies of KNN (K=3) and SVM 
              (Sigmoid kernel) are 29.17% and 28.75%, no better than randomly selected accuracy (25%), 
              proving ESG can’t perform better in returns
            3.Applied Monte Carlo Simulation to simulate 10 to 15 stocks’ portfolios among 300+ stocks to 
              analyze the good ESG and bad ESG portfolios’ Sharp ratio performances, giving Chinese investors 
              advice that investors shouldn’t invest all money into high-performance ESG stocks if they pursue 
              high risk-return rate
        * Air Quality Analysis:
            1.Applied PCA to reduce variable dimensions from 6 to 3 and got the cumulative contribution 
              exceeding 85%; the results show that sulfur oxides, nitrogen oxides, and other particular 
              respiratory particulate matters still play significant roles as air pollutants in cities of China
            2.Built TOPSIS model rank using MATLAB and got the 31 major Chinese cities’ air quality, achieving 
              the result that air pollution is concentrated in North China and high-altitude cities

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
          further potential discussion about investment

design:
  columns: '2'
---
