---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

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
  - title: Engineering Development Group - Intern
    company: MathWorks
    company_url: 'https://www.mathworks.com/'
    company_logo: mathworks
    location: Natick, MA
    date_start: '2023-05-01'
    date_end: '2022-08-01'
    description: |2-
        * Enhanced Ruby web service performance by 42%, delivering search results & suggestions more efficiently by refactoring into a containerized, serverless, RESTful Ruby on Rails architecture, & facilitating cloud migration using Docker & Kubernetes.
        * Achieved a 38% improvement in MATLAB search effectiveness by collaborating with the product team to implement OpenAI API-driven prompt engineering, enhancing Apache Solr search query accuracy and user search term relevancy.

  - title: Senior Software Engineer
    company: MiQ Digital
    company_url: 'https://www.wearemiq.com/'
    company_logo: miq
    location: Bangalore, India
    date_start: '2021-01-01'
    date_end: '2022-06-01'
    description: |2-
        * Led a team of 5 SEs to reduce the data processing time for programmatic ad campaigns from 60 to 1 min & eliminate revenue leakage by designing & developing a distributed system using Kafka, MongoDB, Redis, AWS, Spring Boot & Kubernetes.
        * Improved alert response time by 90% by developing a Java & Spring Boot based web service for pipeline monitoring.
        * Upscaled an on-demand real-time report generation service for advertisers by implementing a NoSQL (MongoDB) database storage solution with caching using Redis, reducing overall latency by 40% & easing the workload for client services teams.
        * Pioneered adoption of Test Driven Development & Sonar across technical teams, enabling a ”Release When Ready” approach.

  - title: Software Engineer II
    company: MiQ Digital
    company_url: 'https://www.wearemiq.com/'
    company_logo: miq
    location: Bangalore, India
    date_start: '2018-06-01'
    date_end: '2020-12-01'
    description: |2-
        * Streamlined advertising campaign management by transitioning the frontend from AngularJS to React, cutting support issues by 40%, and boosting stability and usability. Integrated Hooks, Axios, Jest, Bootstrap, and Lerna for enhanced efficiency.
        * Upgraded on-prem Spring services to Spring Boot v2 REST API web services, containerized with Docker & Helm for  Kubernetes, achieving a 92.5% improvement in API latency (from 200ms to 15ms) & reducing technical debt by 35%.
        * Generated notable monthly savings of $1,500 by optimizing MySQL relational database queries and CPU utilization.
        * Enhanced application reliability & attained 99.9% up-time by implementing Prometheus metrics & Grafana dashboards.
        * As a Scrum Master, improved Agile processes and achieved a remarkable 95% predictability rate and 90% on-time code reviews.

design:
  columns: '4'
---
