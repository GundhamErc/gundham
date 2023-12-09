---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Generating Unstable Dynamics in dispersive Hamiltonian fluids
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: experience
    id: team
    content:
      title: Team members
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Alberto Maspero
          company: PI
          company_url: '/workspaces/gundham/assets/media/icon.png'
          company_logo: 
          location: 
          date_start: '2021-01-01'
          date_end: ''
          description: |2-
              Xavier is an ICREA Research Professor at the University of Barcelona since 2020. Previously, he has been Assistant Professor at Universität Zürich, as well as R. H. Bing Instructor at the University of Texas at Austin. He is a mathematician who works on Partial Differential Equations (PDEs). 
        - title: Pinco Pallo
          company: Postdoc
          company_url: ''
          company_logo:
          location: 
          date_start: '2016-01-01'
          date_end: '2020-12-31'
          description: |2-
              the first postdoc?
    design:
      columns: '2'
  
  
  - block: portfolio
    id: projects
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

  - block: collection
    id: featured
    content:
      title: Recent Publications
      text: 
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  - block: collection
    id: activities
    content:
      title: Activities
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact

  - block: markdown
    id: host
    content:
      title: Host institution
      text: SISSA is the best institute in Italy
    design:
      columns: '2'
      view: showcase

  


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        We always look for new potential members or collaborations, feel free to contact us
      # Contact (add or remove contact options as necessary)
      email: gundham.erc@proton.me
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        street: Via Bonomea 265
        city: Trieste
        #region: 
        postcode: '34126'
        country: Italy
        #country_code: US
      #directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      #coordinates:
      #  latitude: '37.4275'
      #  longitude: '-122.1697'  
      #contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #    link: 'skype:echo123?call'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
          # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    design:
      columns: '2'
---
