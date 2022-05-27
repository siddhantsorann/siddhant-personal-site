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
  - title: Senior Software Engineer
    company: MiQ Digital
    company_url: 'https://www.wearemiq.com/'
    company_logo: miq
    location: Bangalore, India
    date_start: '2021-01-01'
    date_end: '2022-06-01'
    description: |2-
        * Became one of the youngest Senior Software Engineers across the organization.
        * Led the team to design and develop a new distributed system to aggregate complex data using libraries and technologies like Kafka, RDS, Spring Boot, REST, and Kubernetes, making it future-proof, scalable, and highly available, thereby reducing the time taken from 60 mins   to 45 sec and eliminate revenue leakage.
        * Worked on optimizing DB queries and the CPU usage of our Aurora instance. This allowed us to use a smaller instance, saving the company USD 1,711 monthly.
        * Volunteered to establish protocols for Trunk Based Development across products to make them “Release When Ready”. Automated the CI/CD pipelines and introduced Component and Integration Tests; this allowed features to be tested and deployed to production as soon as a PR was merged, leading to a 25% increase in dev efficiency.
        * Performed a PoC on automated code quality tools. Worked with teams across MiQ to onboard them onto Sonarcloud to help improve the overall code quality in the organization and provide reports to management.
  - title: Software Engineer II
    company: MiQ Digital
    company_url: 'https://www.wearemiq.com/'
    company_logo: miq
    location: Bangalore, India
    date_start: '2020-01-01'
    date_end: '2021-01-01'
    description: |2-
        * Invited to the London HQ, after interacting with the users, developed a microservice for better monitoring and alerting of our pipelines, reducing the alerting delay from 30 mins to 1 min. 
        * Led a project to provide updated data to users by 9 AM across all timezones, improving from 1 PM previously.
        * Upgraded the front-end from AngularJS to React using Hooks, Axios, Jest, Semantic Versioning, and Lerna. This reduced our support issues by 40%. 
        * Mentored junior developers to help them grow as software engineers. Took multiple learning sessions for the tech team on various topics like React fundamentals, design principles, CI/CD, SonarCloud, and code coverage.
        * As a scrum master, I helped improve the scrum and agile practices of the team and the organization. As a result, my team averaged 93% predictability, one of the highest in the organization.
  - title: Software Engineer I
    company: MiQ Digital
    company_url: 'https://www.wearemiq.com/'
    company_logo: miq
    location: Bangalore, India
    date_start: '2018-07-01'
    date_end: '2020-01-01'
    description: |2-
        * Upgraded eight different microservices to Spring Boot 2.x from 1.x, reducing the overall tech debt by 70%.
        * Upgraded an application written in AngularJS to Angular 5. Used all the latest tools like Jenkins, Docker, Helm, and Kubernetes to implement an auto-scaling infrastructure, improving page load times by 60%.  
  - title: Software Engineering Intern
    company: Daimler
    company_url: 'https://www.daimlerfinancialservices.in/en/index.htm'
    company_logo: daimler
    location: Pune, India
    date_start: '2017-05-01'
    date_end: '2017-07-01'
    description: |2-
        * Developed a chatbot allowing the users an efficient and user-friendly access to information. It understood the users’ requests and guided them to the relevant information without having to browse through the website. It also provided information about what the users requested to help organize the information on the website.

  # - title: Software Engineering Intern
  #   company: Daimler
  #   company_url: 'https://www.daimlerfinancialservices.in/en/index.html'
  #   company_logo: miq
  #   location: Pune, India
  #   date_start: '2017-05-01'
  #   date_end: '2017-0-01'
  #   description: |2-
  #       * Upgraded eight different microservices to Spring Boot 2.x from 1.x, reducing the overall tech debt by 70%.
  #       * Upgraded an application written in AngularJS to Angular 5. Used all the latest tools like Jenkins, Docker, Helm, and Kubernetes to implement an auto-scaling infrastructure, improving page load times by 60%.  





  # - title: Professor of Semiconductor Physics
  #   company: University X
  #   company_url: ''
  #   company_logo: org-x
  #   location: California
  #   date_start: '2016-01-01'
  #   date_end: '2020-12-31'
  #   description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '4'
---
