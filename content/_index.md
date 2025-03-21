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

  # - block: experience
  #   id: team
  #   content:
  #     title: Team members
  #     # Date format for experience
  #     #   Refer to https://docs.hugoblox.com/customization/#date-format
  #     date_format: Jan 2006
  #     # Experiences.
  #     #   Add/remove as many `experience` items below as you like.
  #     #   Required fields are `title`, `company`, and `date_start`.
  #     #   Leave `date_end` empty if it's your current employer.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - title: Alberto Maspero
  #         company: Principal Investigator
  #         company_url: 'https://people.sissa.it/~amaspero/'
  #         company_logo: 
  #         location: 
  #         date_start: '2024-01-01'
  #         date_end: ''
  #         description: |2-
  #             Alberto is  associate   Professor at SISSA since 2022. Previously, he has been assistant Professor at SISSA. He got a PhD in Mathematics  in 2014, in cotutelle between the University of Zurich and University of Milan.
  #             He is a mathematician who works on Partial Differential Equations (PDEs). 
  #       - title: Pinco Pallo
  #         company: Postdoc
  #         company_url: ''
  #         company_logo:
  #         location: 
  #         date_start: '2016-01-01'
  #         date_end: '2020-12-31'
  #         description: |2-
  #             the first postdoc?
  #   design:
  #     columns: '2'
  
  
  - block: portfolio
    id: team
    content:
      title: Team members
      filters:
        folders:
          - team
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      #buttons:
      #  - name: 
      #    tag: 'Energy cascades'
      #  - name: Deep Learning
      #    tag: Deep Learning
      #  - name: Other
      #   tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
        


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
      #buttons:
      #  - name: 
      #    tag: 'Energy cascades'
      #  - name: Deep Learning
      #    tag: Deep Learning
      #  - name: Other
      #   tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true



  - block: markdown
    id: host
    content:
      title: Host institution
      text: |2-
        [SISSA](https://www.sissa.it/) – Scuola Internazionale Superiore di Studi Avanzati – was founded in 1978 and is a scientific center of excellence within the national and international academic scene.
        ![image info](SISSA.jpeg)
        Located in Italy, in the city of Trieste, it features about 70 professors, 130 researchers, 300 PhD students. The School is surrounded by a 25 acre park, and offers a stunning view of the Gulf of Trieste.
        The quality level of the research is further confirmed by the fact that within the competitive field of European funding schemes SISSA holds the top position among Italian scientific institutes in terms of research grants obtained in relation to the number of researchers and professors. 
    design:
      columns: '2'
      view: showcase



  - block: collection
    id: publication
    content:
      title: Publications
      text: 
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

#  - block: collection
#    id: activities
#    content:
#      title: Activities
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact


  - block: markdown
    id: open
    content:
      title: Open access policy
      text: |2-
        All papers published under ERC grants must comply with a specific open access policy. This is a quick recap of best practices for compliance, meant for project members:
        - Put all preprints on a public repository before submission ([arXiv](https://arxiv.org/), [HAL](https://hal.archives-ouvertes.fr/), [SISSA preprint server](https://preprints.sissa.it/)). Note that [CVGMT](https://cvgmt.sns.it/) does not qualify as an open access repository.

        - Before submission, check the policy of the journal. It must permit the publication of the **accepted** version of the paper on a public repository with an **embargo period not longer than 6 months**. Use the following tool: [Open Policy Finder](https://openpolicyfinder.jisc.ac.uk/).

        - After acceptance, update the preprint server with the accepted version as soon as the embargo period has elapsed. Provide the DOI link as soon as it is available.

        - An alternative to the previous two points applies to journals that have special agreements with the HI and allow for gold open access publication without fees. 

        A list of such agreements is available here: [Read & Publish Transformative Agreements](https://library.sissa.it/readpublish-transformative-agreements).  

        Official guidelines can be found here: [ERC Open Access Guidelines](https://ec.europa.eu/research/participants/docs/h2020-funding-guide/cross-cutting-issues/open-access-data-management/open-access_en.htm#repository).
        
        See also the page [Open Science ERC](https://erc.europa.eu/manage-your-project/open-science). 

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


[def]: https://assets.digitalocean.com/articles/alligator/boo.svg