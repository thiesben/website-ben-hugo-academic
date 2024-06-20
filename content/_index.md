---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    demo: true
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: CEO
          company: GenCoin
          company_url: ''
          company_logo: org-gc
          location: California
          date_start: '2021-01-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
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
  - block: portfolio
    id: projects
    demo: true
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    demo: true
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: collection
    id: publications
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: markdown
    content:
      title: GitHub & Coding
      text:
        |-
        ## RADICES
        The [Rank Degree Influencer Core Sampler (RaDICeS)](https://github.com/FlxVctr/RADICES) allows to draw an effective sample of a (language-based) Twittersphere as described in [this talk](https://www.youtube.com/watch?v=qsnGTl8d3qU&t=21823s). The underlying method is explained in [this journal article](https://journals.sagepub.com/doi/full/10.1177/2056305120984475). You can also [cite the software itself](https://figshare.com/articles/RADICES/8864777).
        
        ## Affinity Propagation Clustering
        The [`affprop`](https://github.com/thiesben/affinity-propagation-python) package is an Affinity Propagation Clustering ([Frey and Dueck, 2007](https://science.sciencemag.org/content/315/5814/972)) implementation for Python. This package was part of a project of Cliburn Chan’s STA663 Statistical Computation class at [Duke University](https://www.duke.edu/).

        ## trollR 
        [`trollR`](https://schliebs.github.io/trollR/) is an R package and tool to detect toxic language. It scored second place at the LSE Computational Social Sciences Hackathon '18.
    design:
      columns: '2'
  - block: tag_cloud
    demo: true
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    title: Contact
    content:
      email: ben@benthies.de
      autolink: true
    deign:
      columns: '2'
---
