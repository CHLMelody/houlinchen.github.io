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
        image:
          filename: background.jpg
          filters:
            brightness: 1
          size: cover
          position: center
          parallax: true
          text_color_light: true
  - block: markdown
    id: 
    content:
      title: 
      subtitle: ''
      text: |-
        Greetings! I am currently a graduate student at [Cornell University](https://www.cornell.edu/) in the [Department of Statistics and Data Science](https://stat.cornell.edu/). I graduated in 2024 with an Honours B.S. degree in the [Faculty of Arts and Science](https://www.artsci.utoronto.ca/) at the [University of Toronto](https://www.utoronto.ca/), Toronto, ON, Canada. During my undergraduate studies, I was a visiting student at [Renmin University of China](https://www.ruc.edu.cn/en) and [Nankai University](https://en.nankai.edu.cn/) in Summer 2021. I have engaged in multiple projects including Bayesian estimation for distributional differences, multiple linear regression for multivariate data analysis, and Monte Carlo approximations. My research interests continue to focus on Applied Statistics, Environmental Science, Data Analysis, and Machine Learning.
        {style="text-align: justify;"}
  - block: experience
    id: education
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Master of Professional Studies
          company: Cornell University
          company_url: https://www.cornell.edu/
          company_logo: cornell
          location: Ithaca, New York, USA
          date_start: '2024-08-26'
          date_end: ''
        - title: Honours Bachelor of Science
          company: University of Toronto
          company_url: https://www.utoronto.ca/
          company_logo: uoft
          location: Toronto, Ontario, Canada
          date_start: '2020-09-01'
          date_end: '2024-05-07'
          description: |2-
              * Mathematics: Groups and Symmetries, Complex Variables, and Nonlinear Optimization.
              * Statistics: Methods of Data Analysis I, Methods for multivariate data, and Applied Bayesian Statistics.
        - title: Visiting Student
          company: Renmin University of China
          company_url: 'https://www.ruc.edu.cn/en'
          company_logo: renmin
          location: Beijing, China
          date_start: '2021-05-01'
          date_end: '2021-08-31'
          description: |2-
        - title: Visiting Student
          company: Nankai University
          company_url: 'https://en.nankai.edu.cn/'
          company_logo: nankai
          location: Tianjin, China
          date_start: '2021-05-01'
          date_end: '2021-08-31'
          description: |2-
    design:
      columns: '2'
  - block: experience
    id: experience
    content:
      title: Work Experience
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
          company: University of Toronto
          company_url: https://www.utoronto.ca/
          company_logo: uoft
          location: Toronto, Ontario, Canada
          date_start: '2024-01-01'
          date_end: '2024-08-31'
          description: |2-
              * Data analysis, modeling, and quantification in environmental-related projects.
        - title: Marketing Data Analyst
          company: AP Lazer
          company_url: https://aplazer.com/
          company_logo: aplazer
          location: Windsor, Ontario, Canada
          date_start: '2022-09-01'
          date_end: '2024-08-31'
          description: |2-
              * Running paid search and paid social media ad reports, calculating ROI, and making summary and comparison tables.
              * Analyzing the effectiveness of each campaign, ad group, and ad.
              * Combining the static information from the CRM program to provide a focused and simplified data table for the marketing team to improve the ads.
    design:
      columns: '2'
  - block: collection
    id: publication
    content:
      title: Publication
      # text: |-
        # {{% callout note %}}
        # Quickly discover relevant content by [filtering publications](./publication/).
        # {{% /callout %}}
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
        - [IEEE Internet of Things Journal](https://ieee-iotj.org/)
        - [IEEE Access](https://ieeeaccess.ieee.org/)
    design:
      columns: '2'
  - block: features
    id: skill
    content:
      title: Skill
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
        - name: Machine Learning
          icon: head-side-virus
          icon_pack: fas
        - name: Acedemic Writing
          icon: book
          icon_pack: fas
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
