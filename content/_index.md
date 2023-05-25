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
    design:
      background:
        image: background.jpg
        filters:
          brightness: 0.6
        size: cover
        position: center
        parallax: true
        text_color_light: true
  - block: features
    id: skill
    content:
      title: Skills
      items:
        - name: R
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas
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
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
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
