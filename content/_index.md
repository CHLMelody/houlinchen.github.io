---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    id: skill
    content:
      title: Skills
      items:
        - name: RStudio
          # description: 100%
          icon: r-project
          icon_pack: fab
        - name: Python
          icon: python
          icon_pack: fab
        - name: Overleaf
          icon: leaf
          icon_pack: fas
        - name: Data Analysis
          icon: chart-line
          icon_pack: fas
        - name: Artificial Intelligence
          icon: microchip-ai
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
        - title: Marketing Data Analyst
          company: AP Lazer
          company_url: https://aplazer.com/
          company_logo: aplazer
          location: Windsor, Ontario, Canada
          date_start: '2022-09-01'
          date_end: ''
          description: |2-
              * Running paid search and paid social media ad reports, calculating ROI, and making summary and comparison tables.
              * Analyzing the effectiveness of each campaign, ad group, and ad.
              * Combining the static information from the CRM program to provide a focused and simplified data table for the marketing team to improve the ads.
    design:
      columns: '2'
  - block: collection
    id: publication
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      count: 0
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: compact
  - block: markdown
    id: service
    content:
      title: Academic Service
      subtitle: ''
      text: |-
        ### Journal Reviewer
        - [IEEE Access](https://ieeeaccess.ieee.org/)
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: houlin.chen@mail.utoronto.ca
      # address:
      #   street: Hampton Hall 2155, 550 Stadium Mall Drive
      #   city: West Lafayette
      #   region: IN
      #   postcode: '47907'
      #   country: United States
      #   country_code: US
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
