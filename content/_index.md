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
    design:
      spacing:
        padding: ['0', '0', '30px', '0']

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
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
        - name: All
          tag: '*'
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
      spacing:
        padding: ['30px', '0', '30px', '0']


sections:
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Read my latest paper on LLMs
          icon: arxiv
          url: https://arxiv.org/abs/2304.01852
        - text: Watch my new YouTube video to achieve 20x productivity
          icon: youtube
          url: https://youtube.com
        - text: Connect with me on LinkedIn
          icon: linkedin
          url: https://linkedin.com

  - block: collection
    id: featured
    content:
      title: Publications
      text: |-
        See all publications on [Google Scholar](https://scholar.google.ca/citations?user=C7wIKb8AAAAJ).
      buttons:
        - title: Read my latest paper on Google Scholar
          icon: google-scholar # Alternatively, use `google-scholar` icon from `ai` icon pack
          icon_pack: ai
          url: https://scholar.google.ca/citations?user=C7wIKb8AAAAJ
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '1'
      view: card
      spacing:
        padding: ['30px', '0', '0', '0']
  - block: collection
    content:
      title: 
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '1'
      view: citation
      spacing:
        padding: ['0', '0', '30px', '0']

  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      columns: '1'
      view: showcase
      spacing:
        padding: ['30px', '0', '30px', '0']

  - block: collection
    id: posts
    content:
      title: Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: showcase
      columns: '1'
      spacing:
        padding: ['30px', '0', '30px', '0']

  - block: contact
    id: contact
    content:
      title: Contact
      # Contact (add or remove contact options as necessary)
      email: han.ren@eng.ox.ac.uk
      address:
        street: Department of Engineering Science, University of Oxford, Parks Road
        city: Oxford
        region: Oxfordshire
        postcode: 'OX1 3PJ'
        country: United Kingdom
        country_code: UK
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '51.76025'
        longitude: '-1.25966'  
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '1'
      spacing:
        padding: ['30px', '0', '30px', '0']
---
