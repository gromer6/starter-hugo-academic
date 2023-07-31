---
# Leave the homepage title empty to use the site title
title: Guido A. Romero
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    id: skills
    content:
      title: Skills
      items:
        - name: Economics
          icon: coins
          icon_pack: fas
        - name: Statistics
          icon: chart-line
          icon_pack: fas
        - name: Python
          icon: python
          icon_pack: fab
        - name: R
          icon: r-project
          icon_pack: fab
        
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Research Assistant
          company: Emory University
          company_url: ''
          company_logo: emory-logo
          location: Georgia
          date_start: '2023-07-17'
          date_end: ''
        - title: Research and Teaching Assistant
          company: Universidad EAFIT
          company_url: ''
          company_logo: eafit-logo
          location: Medellin, Colombia
          date_start: '2018-01-20'
          date_end: '2020-12-11'
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/course/7001978e09a69a08799eaf16439a51c57d11eb3f
          date_end: ''
          date_start: '2023-02-08'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: Intermediate Regression with statsmodels in Python
          url: ''
        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/course/5de3ca8d240a4ec901010cb66be6d4253a5d6603
          date_end: ''
          date_start: '2023-01-13'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: Introduction to Version Control with Git
        - certificate_url: https://www.datacamp.com/statement-of-accomplishment/course/22082160d8529ff57e489e8a37e72cbbab349f2f
          date_end: ''
          date_start: '2023-07-24'
          description: ''
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in Python'
          url: ''
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please leave me a message and I will reply as soon as possible.
      # Contact (add or remove contact options as necessary)
      email: guido.romero@emory.edu
      address:
        street: 1516 Clifton Road
        city: Atlanta
        region: GA
        postcode: '30322'
        country: United States
        country_code: US
      directions: 4th floor.
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: https://twitter.com/guidoromero98
        - icon: linkedin
          name: Also on LinkedIn
          icon_pack: fab
          link: https://www.linkedin.com/in/guido-anthony-romero/
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
